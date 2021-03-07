---
layout: single
title:  "常见问题解答"
date:   2048-01-02 15:04:05 +0800
categories: [Guide]
tags: [Guide]
---

## 镜像网站
```bash
$ wget --mirror --convert-links --adjust-extension --page-requisites --no-parent https://www.example.com
```

## 获取图片详细信息
```bash
$ identify -verbose example.jpg
```

## M3U8 Download
```bash
$ ffmpeg -i https://example.com/index.m3u8 -c copy out.flv
```

## Mac 允许任何来源
```bash
$ sudo spctl --master-disable
```

## 计算机常见术语及缩写

  [Abbreviations](/guide-abbreviations)

## What does el5, el6, and el7 mean?

EL is short for Red Hat Enterprise Linux (EL).

  - EL5 is the download for Red Hat 5.x, CentOS 5.x, CloudLinux 5.x.
  - EL6 is the download for Red Hat 6.x, CentOS 6.x, and CloudLinux 6.x.
  - EL7 is the download for Red Hat 7.x, CentOS 7.x, and CloudLinux 7.x.

## The .netrc file

  [netrc, .netrc](https://linux.die.net/man/5/netrc) - user configuration for ftp
