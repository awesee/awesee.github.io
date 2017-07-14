---
layout: default
title:  "如何创建一个自己的 Composer 库"
date:   2017-06-21 18:30:00 +0800
categories: articles
---

## 起因
最近在做微信公众号开发，会开发很多小型H5活动，每次开发新的项目都需要下载框架，然后修改一下默认配置，添加一些自定义方法，而这里面微信授权，回调，分享等好多接口都一样，然后就想能一能用composer create-project创建项目时这些都是已经修改好的呢？下面是创建流程：

## 1、Composer是什么
Composer 是 PHP 的一个依赖管理工具。它允许你申明项目所依赖的代码库，它会在你的项目中为你安装他们。
具体的见 [简介 | Composer](http://docs.phpcomposer.com/00-intro.html)。

## 2、需要做哪些准备
- [GitHub 账号](https://github.com)  相信每一位程序员都有。
- [Packagist 账号](https://packagist.org) 这个你就不一定有了。（可以使用GitHub账户授权登录）

## 3、创建自己的项目
可以先在GitHub上创建一个仓库，然后克隆到本地，接下来就是创建自己的Project。在项目跟目录添加一个composer.json文件，用来描述项目信息，提交到Packagist会检测这个文件。文件内容如下：
```json
{
    "name": "your-vendor-name/package-name",
    "description": "A short description of what your package does",
    "type": "project",
    "license": "MIT",
    "minimum-stability": "stable",
    "require": {}
}
```
详细见 [Creating a composer.json file](https://packagist.org/about)。
注意这里的type，详细配置见 [composer.json 架构](http://docs.phpcomposer.com/04-schema.html)。
最后可以用 `composer validate ` 命令验证一下。
修改完后提交到GitHub版本库。

## 4、在Packagist官网提交你的Package
进入Packagist官网，登录你的账户，点击Submit
![file](https://dn-phphub.qbox.me/uploads/images/201706/12/16817/kfvuAqxAmO.png)
填写你提交到GitHub的仓库地址。点击Check，根据提示提交即可。
稍等片刻，你会看到如下界面，然后你就可以使用这个库了。
![file](https://dn-phphub.qbox.me/uploads/images/201706/12/16817/qX9CGAj5O6.png)

到这里就结束了吗？NO NO NO，如果你修改代码，它还不能自动更新。

## 5、Packagist包自动更新
- Go to your GitHub repository
- Click the "Settings" button
- Click "Integrations & services"
- Add a "Packagist" service, and configure it with your API token, plus your Packagist username
- Check the "Active" box and submit the form

详细见 [How to submit packages?](https://packagist.org/about)
管理你的包版本详见 [Managing package versions](https://packagist.org/about)

## 6、Last but not least
到这里基本就结束了。一切都好了，但是突然看到Packagist账户头像是默认的，类似下面这样：
![file](https://dn-phphub.qbox.me/uploads/images/201706/12/16817/N4lPAVIHGH.png)
作为一个有强迫症的程序员，我很想用自定义的头像。可是Packagist账户设置没有修改头像的选项。
接下来要特别感谢 [@overtrue](https://github.com/overtrue) 安大大的帮助
![file](https://dn-phphub.qbox.me/uploads/images/201706/12/16817/30HiWa22KT.png)
原来Packagist用的是全球公认的头像
[Gravatar](http://cn.gravatar.com/) - 一个属于你自己的全球通用头像
接下来就是注册Gravatar，上传头像绑定自己的邮箱地址。
![file](https://dn-phphub.qbox.me/uploads/images/201706/12/16817/sHRQeRn23n.png)
注册如有遇到国内163邮箱，QQ邮箱提示邮箱地址被屏蔽可以用微软邮箱，翻墙可以用Gmail，注册后可以修改。

_**Thanks.**_