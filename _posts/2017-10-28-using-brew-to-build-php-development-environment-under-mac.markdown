---
layout:     single
title:      "Mac下用brew搭建PHP开发环境"
date:       2017-10-28 18:30:00 +0800
categories: [PHP]
tags:       [Mac]
---

## 搭建过程
- 安装 Homebrew
- `$ brew search php` （非必要）
- `$ brew options php71` （非必要） 
- `$ brew install homebrew/php/php71 --with-httpd` Apache环境
- `$ brew install mysql`
- `$ brew install homebrew/php/php71-xdebug` 安装扩展（非必要）
- `which apachectl 或 which httpd` 查询httpd位置（非必要）
- `apachectl -V 或 httpd -V` 查看Apache配置文件位置（非必要）
- `php -m` 查询已安装模块（非必要）
- `php --ini` 查询php.ini文件（非必要）
- `$ brew services list`  详细使用运行brew services可以查看帮助（非必要）
- `$ sudo brew services run httpd` 需要root权限（80，443端口需要）
- `$ brew services run mysql`

## 一、安装 Homebrew
> Homebrew是macOS 缺失的软件包管理器。安装过程也非常简单：
```bash
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" 
```
将以上命令粘贴至终端。脚本会在执行前暂停，并说明将它将做什么。

## 二、环境搭建（简洁方式）
```bash
$ brew search php
```

查询可用的formula，注意以下几个：
```bash
homebrew/php/php56
homebrew/php/php70
homebrew/php/php71
homebrew/php/php72
```

PHP后面的数字代表PHP版本，`homebrew/php/php72-redis` 类似这样的是PHP版本对用的扩展。
默认是不会安装Apache Handler module，可以使用 `--with-httpd` 参数。 

安装mysql，php扩展方法一样。

## 三、遇到问题及处理方式（重点）

### 安装模块不可用

#### 原因1: 线程安全和非线程安全

`brew reinstall -fs php71-mcrypt`  重新安装线程安全模块

运行 `brew install` 可以添加 `--interactive` 参数，解释如下
```bash
$ brew help install
brew install --interactive [--git] formula:
    If --interactive (or -i) is passed, download and patch formula, then
    open a shell. This allows the user to run ./configure --help and
    otherwise determine how to turn the software package into a Homebrew
    formula.

    If --git (or -g) is passed, Homebrew will create a Git repository, useful for
    creating patches to the software.
```

#### 原因2: 模块不可用
```bash 
PHP Warning:  PHP Startup: Unable to load dynamic library '/usr/local/opt/php71-redis/redis.so' - dlopen(/usr/local/opt/php71-redis/redis.so, 9): Symbol not found: _basic_globals
  Referenced from: /usr/local/opt/php71-redis/redis.so
  Expected in: flat namespace
 in /usr/local/opt/php71-redis/redis.so in Unknown on line 0

Warning: PHP Startup: Unable to load dynamic library '/usr/local/opt/php71-redis/redis.so' - dlopen(/usr/local/opt/php71-redis/redis.so, 9): Symbol not found: _basic_globals
  Referenced from: /usr/local/opt/php71-redis/redis.so
  Expected in: flat namespace
 in /usr/local/opt/php71-redis/redis.so in Unknown on line 0
```

解决方法：添加 `--build-from-source (or -s)`  参数

例如： `brew reinstall --build-from-source php71-redis`

_**Thanks.**_
