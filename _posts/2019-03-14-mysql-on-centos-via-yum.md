---
layout: single
title:  "CentOS通过yum安装MySQL"
date:   2019-03-14 21:30:00 +0800
categories: [Linux, Database]
tags: [Yum, MySQL, Guide]
---

Yum默认源搜索MySQL，查找到的结果是mariadb，它是MySQL的一个分支。为了保证稳定性，安装版本一般不是很新。
所以第一步我们需要安装MySQL的Yum源。

## 下载安装MySQL官方的Yum Repository
根据Linux发行版本（CentOS、Fedora都属于红帽系），从[MySQL官方](http://dev.mysql.com/downloads/repo/yum/)获取Yum Repository。
[Yum Repository](https://repo.mysql.com/) 

```bash
$ sudo rpm -Uvh https://repo.mysql.com/mysql57-community-release-el7.rpm
```

## 安装MySQL数据库的服务器版本
```bash
$ sudo yum install mysql-community-server
```

## 启动数据库

```bash
$ systemctl start  mysqld
```

查询数据库状态
```bash
$ systemctl status mysqld
```

## 获取初始密码

使用Yum安装并启动MySQL服务后，MySQL进程会自动在进程日志中打印root用户的初始密码：
```bash
$ grep 'temporary password' /var/log/mysqld.log 

// Output:
// 2019-03-14T02:14:19.084352Z 1 [Note] A temporary password is generated for root@localhost: G8g-0+w/daL1

```

## 修改root用户密码

使用获取到的root用户的初始密码，然后进行修改：

```bash
// 登录
$ mysql -uroot -p

// 修改密码 
// 为了加强安全性, MySQL5.7以后, 默认密码验证策略必须符合长度, 且必须含有数字, 小写或大写字母, 特殊字符
$ mysql> ALTER USER 'root'@'localhost' IDENTIFIED BY 'new password';

// 退出
$ mysql> exit
```

## 安装完毕

至此，使用Yum方法在CentOS7中安装MySQL5.7数据库完毕。可以使用新的root密码登陆MySQL了。
