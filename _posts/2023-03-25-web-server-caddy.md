---
layout:     single
title:      "终极Web服务器-Caddy"
date:       2023-03-25 15:04:05 +0800
categories: [Linux]
tags:       [Linux, Web]
---

## 背景

现在的Nginx是一款非常流行的Web服务器，我们经常用它来做静态资源托管或反向代理。最近发现了一款全新的Web服务器Caddy，GitHub Star 46.9k+ 。试用了一下 Caddy，发现它使用起来比Nginx优雅多了，功能也很强，简单介绍一下然后推荐给大家！

![file](/assets/images/posts/20230325_caddy.png)

## 简介

Caddy是一款功能强大，可扩展的平台，可以为您的站点、服务和应用程序提供服务，通常用做Web服务器或代理，采用Go语言编写。Caddy有下面这些开箱即用的特性:

* 全自动支持HTTP/2协议，无需任何配置。
* Caddy 使用 Let’s Encrypt 让你的站点全自动变成HTTPS，无需任何配置。
* 合理使用多核，得益于Go的特性。
* 完全支持IPv6环境。
* Caddy 对WebSockets有很好的支持。
* 自动把Markdown转成 HTML。
* Caddy 对log格式的定义很容易。
* 易于部署 得益于Go的特性，Caddy只是一个小小的二进制文件，没有依赖，很好部署。
* 得益于Go的跨平台特性，Caddy很容易的支持了三大主流系统：Windows、 Linux、Mac。

## 安装

Linux 或 Mac 一键安装命令

```bash
curl -sS https://webi.sh/caddy | sh
```

Linux 系统还可以通过执行DNF或YUM命令安装

```bash
dnf install caddy -y
```

Mac 系统可以通过Homebrew安装

```bash
brew install caddy
```

Windows 系统可以通过Chocolatey安装

```bash
choco install caddy
```

更多安装方式详见官网安装教程：<https://caddyserver.com/docs/install>

## 搭建静态文件服务

创建 `/etc/caddy/Caddyfile` 文件，编写以下内容：

```bash
# 第一个静态网站
awesee.cn, www.awesee.cn, m.awesee.cn {
	# 设置网站根目录
	root * /home/shuo/www/blog.awesee.cn
	file_server
}
```

通过 `systemctl` 启动Caddy服务

```bash
sudo systemctl start  caddy
```

打开浏览器，就可以看到部署的静态网站了。

搭建多个静态网站。

```bash
# 第一个静态网站
awesee.cn, www.awesee.cn, m.awesee.cn {
	# 设置网站根目录
	root * /home/shuo/www/blog.awesee.cn
	file_server
}

# 第二个静态网站
avatar.awesee.cn {
	root * /home/shuo/www/vue-color-avatar/dist
	file_server
}
```

## 反向代理服务

修改 `/etc/caddy/Caddyfile` 文件，添加以下内容：

```bash
# 第一个静态网站
awesee.cn, www.awesee.cn, m.awesee.cn {
	# 设置网站根目录
	root * /home/shuo/www/blog.awesee.cn
	file_server
}

# 第二个静态网站
avatar.awesee.cn {
	root * /home/shuo/www/vue-color-avatar/dist
	file_server
}

# 反向代理服务
proxy.awesee.cn {
	# 要代理的本机端口
	reverse_proxy :32080
}
```

通过 `systemctl` 重启Caddy服务

```bash
sudo systemctl restart  caddy
```

到此完成了静态网站的搭建及反向代理服务实现，并且你的站点全自动变成HTTPS，无需任何配置。更多使用方法详见官方文档。

<https://caddyserver.com/docs/>