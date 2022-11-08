---
layout: single
title:  "systemd 服务"
date:   2019-05-12 09:30:00 +0800
categories: [Linux]
tags: [Tool]
---

systemd 是一个 Linux 系统基础组件的集合，提供了一个系统和服务管理器，运行为 PID 1 并负责启动其它程序。
功能包括：支持并行化任务；同时采用 socket 式与 D-Bus 总线式激活服务；按需启动守护进程（daemon）；
利用 Linux 的 cgroups 监视进程；支持快照和系统恢复；维护挂载点和自动挂载点；各服务间基于依赖关系进行精密控制。
systemd 支持 SysV 和 LSB 初始脚本，可以替代 sysvinit。
除此之外，功能还包括日志进程、控制基础系统配置，维护登陆用户列表以及系统账户、运行时目录和设置，可以运行容器和虚拟机，
可以简单的管理网络配置、网络时间同步、日志转发和名称解析等。

### systemd 简介
首先 systemd 是一个用户空间的程序，属于应用程序，不属于 Linux 内核范畴。
systemd 是 Linux 系统中最新的初始化系统（init），它主要的设计目标是克服 sysvinit 固有的缺点，提高系统的启动速度。

Linux内核加载启动后，用户空间的第一个进程就是初始化进程，这个程序的物理文件约定位于/sbin/init，
当然也可以通过传递内核参数来让内核启动指定的程序。这个进程的特点是进程号为1，代表第一个运行的用户空间进程。
不同发行版采用了不同的启动程序，主要有以下几种主流选择：

  1. 以 Ubuntu 为代表的 Linux 发行版采用 upstart
  1. CentOS7.0 版本之前的 System V init
  1. CentOS7.0 版本的 systemd

systemd 架构图:
![file](/assets/images/posts/20190512093000.png)

### systemd 基本使用

查看当前安装的版本
```bash
$ systemctl --version

systemd 219
+PAM +AUDIT +SELINUX +IMA -APPARMOR +SMACK +SYSVINIT +UTMP +LIBCRYPTSETUP +GCRYPT +GNUTLS +ACL +XZ +LZ4 -SECCOMP +BLKID +ELFUTILS +KMOD +IDN
```

分析系统状态
```bash
$ systemctl status
```

输出激活的单元
```bash
$ systemctl 
或
$ systemctl list-units
```

输出运行失败的单元
```bash
$ systemctl --failed
```

所有可用的单元文件存放在 /usr/lib/systemd/system/ 和 /etc/systemd/system/ 目录（后者优先级更高）。查看所有已安装服务：
```bash
$ systemctl list-unit-files
```

### 系统管理
systemd 并不是一个命令，而是一组命令，涉及到系统管理的方方面面。

```bash
# 重启系统
$ sudo systemctl reboot

# 关闭系统，切断电源
$ sudo systemctl poweroff

# CPU停止工作
$ sudo systemctl halt

# 暂停系统
$ sudo systemctl suspend

# 让系统进入冬眠状态
$ sudo systemctl hibernate

# 让系统进入交互式休眠状态
$ sudo systemctl hybrid-sleep

# 启动进入救援状态（单用户状态）
$ sudo systemctl rescue
```

`systemd-analyze` 命令用于查看启动耗时
```bash
# 查看启动耗时
$ systemd-analyze                                                                                       

# 查看每个服务的启动耗时
$ systemd-analyze blame

# 显示瀑布状的启动过程流
$ systemd-analyze critical-chain

# 显示指定服务的启动流
$ systemd-analyze critical-chain atd.service
```

`hostnamectl` 命令用于查看当前主机的信息
```bash
# 显示当前主机的信息
$ hostnamectl

# 设置主机名。
$ sudo hostnamectl set-hostname awesee
```

`localectl` 命令用于查看本地化设置
```bash
# 查看本地化设置
$ localectl

# 设置本地化参数。
$ sudo localectl set-locale LANG=zh_CN.utf8
$ sudo localectl set-keymap zh_CN
```

`timedatectl` 命令用于查看当前时区设置
```bash
# 查看当前时区设置
$ timedatectl

# 显示所有可用的时区
$ timedatectl list-timezones                                                                                   

# 设置当前时区
$ sudo timedatectl set-timezone Asia/Shanghai
$ sudo timedatectl set-time YYYY-MM-DD
$ sudo timedatectl set-time HH:MM:SS
```

`loginctl` 命令用于查看当前登录的用户
```bash
# 列出当前session
$ loginctl list-sessions

# 列出当前登录用户
$ loginctl list-users

# 列出显示指定用户的信息
$ loginctl show-user shuo
```

### systemd unit
对于开发者来说，工作量最大的部分应该是编写配置单元文件，定义所需要的单元。

systemd unit 类型

| Unit Type | File Extension | Description |
| --- | --- | --- |
| Service unit | `.service` | 服务类 |
| Target unit | `.target` | 一个 unit 服务组，用于模拟实现运行级别|
| Automount unit | `.automount` | 文件系统自动挂载点|
| Device unit | `.device` | 内核识别的设备文件|
| Mount unit | `.mount` | 文件系统挂载点|
| Path unit | `.path` | 文件或目录|
| Scope unit | `.scope` | 外部创建的进程|
| Slice unit | `.slice` | A group of hierarchically organized units that manage system processes.|
| Snapshot unit | `.snapshot` | 系统快照|
| Socket unit | `.socket` | 套接字|
| Swap unit | `.swap` | 标识 swap 设备|
| Timer unit | `.timer` | systemd 的计时器|

unit 文件保存位置

| Directory| Description |
| --- | --- |
| /usr/lib/systemd/system/ | RPM 包安装时分发的 unit 文件 |
| /run/systemd/system/ | systemd 运行时创建的文件 |
| /etc/systemd/system/ | systemctl enable 创建的 unit 文件 |

### 管理系统服务
systemd 的主要命令行工具是  `systemctl` 。

多数管理员应该都已经非常熟悉系统服务和 init 系统的管理，比如 service、chkconfig 以及 telinit 命令的使用。
systemd 也完成同样的管理任务，只是命令工具 systemctl 的语法有所不同而已。

systemd 命令和 sysvinit 命令对比:

| service | systemctl | Description |
| --- | --- | --- |
| service name start | systemctl start name.service | 启动服务 |
| service name stop  | systemctl stop name.service | 停止服务 |
| service name restart | systemctl restart name.service | 重启服务（没启动的服务会启动） |
| service namecondrestart | systemctl try-restart name.service | 只重启正在运行的服务 |
| service name reload | systemctl reload name.service | 重载配置文件 |
| service name status | systemctl status name.service | 检查服务状态|
| service name status | systemctl is-active name.service | 检查服务是否启动
| service --status-all | systemctl list-units --type service --all | 显示所有的服务状态 |

chkconfig 和 systemctl 命令对比:

| chkconfig | systemctl | Description |
| --- | --- | --- |
| chkconfig name on | systemctl enable name.service | 启用开机自启服务 |
| chkconfig name off | systemctl disable name.service | 停用自启服务 |
| chkconfig --list name | systemctl status name.service | 检查服务状态 |
| chkconfig --list name | systemctl is-enabled name.service  | 查看服务是否自启 |
| chkconfig --list | systemctl list-unit-files --type service | 查看所有服务 |
| chkconfig --list | systemctl list-dependencies --after | 列出在指定服务之前启动的服务（依赖）|
| chkconfig --list | systemctl list-dependencies --before | 列出在指定服务之后启动的服务（被依赖）|

---
### 参考资料

  1. [systemd - ArchWiki](https://wiki.archlinux.org/index.php/systemd)

  1. [systemctl 命令完全指南](https://linux.cn/article-5926-1.html)
