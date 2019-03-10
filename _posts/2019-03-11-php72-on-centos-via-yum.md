---
layout: single
title:  "CentOS通过yum安装php72"
date:   2019-03-11 21:30:00 +0800
categories: [Linux]
tags: [Yum, PHP, Guide]
---

PHP 7.2.14已于2019年1月10日在PHP.net上发布，也可通过Yum在Webtatic上获得CentOS / RHEL 7.5。

要安装，首先必须将与CentOS / RHEL版本对应的Webtatic EL yum存储库信息添加到yum：
   
CentOS / RHEL 7.x：
```base
$ sudo yum install epel-release
$ sudo rpm -Uvh https://mirror.webtatic.com/yum/el7/webtatic-release.rpm
```

现在您可以通过执行以下操作来安装PHP 7.2的mod_php SAPI（以及opcode缓存）：
```base
$ sudo yum install mod_php72w php72w-opcache
```

您也可以通过以下方式安装PHP 7.2的php-fpm SAPI（以及opcode缓存）：
```base
$ sudo yum install php72w-fpm php72w-opcache
```

您可能还需要安装PHP命令行工具：
```base
$ sudo yum install php72w-cli
```

---
[[原文链接](https://webtatic.com/packages/php72/)]
