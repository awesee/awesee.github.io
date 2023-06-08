---
layout:     single
title:      "常见问题解答"
date:       2023-01-02 15:04:05 +0800
categories: [Guide]
tags:       [Guide]
---

## 搜索包含指定内容的文件
```bash
# 方法一
$ grep "指定内容" -rl /path/to/dir
# 方法二
$ find /path/to/dir -type f [-maxdepth n] [-mindepth n] -print0 |xargs -0 grep "指定内容"  
```

## 创建指定大小，不占磁盘空间的文件
```bash
$ dd if=/dev/null of=/path/to/file [bs=1024] count=0 seek=20000000
```

## 镜像网站
```bash
$ wget --mirror --convert-links --adjust-extension --page-requisites --no-parent https://www.example.com
```

## 获取图片详细信息
```bash
$ identify -verbose example.jpg
```

## 视频无损压缩
```bash
$ ffmpeg -i in.mp4 [-crf 18] [-vf scale=-1:1080] out.mp4
```

## M3U8 Download
```bash
$ ffmpeg -i https://example.com/index.m3u8 -c copy out.mp4
```

## 视频转图片
```bash
$ ffmpeg -i in.mp4 -r 30 [-t 60 -s 3480x2160] out/%4d.jpg 
```

## 图片转视频
```bash
$ ffmpeg -i out/%4d.jpg -r 30 out.mp4
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
