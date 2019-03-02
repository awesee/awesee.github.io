---
layout:     single
title:      字符集和字符编码
date:       2019-02-20 18:30:00 +0800
categories: [Computer]
tags:       [Charset, Encoding]
---

## 基础知识
计算机中储存的信息都是用二进制数表示的；而我们在屏幕上看到的汉字,英文等字符是二进制数转换之后的结果。
通俗的说，按照何种规则将字符存储在计算机中，如'a'用什么表示，称为"编码"；
反之，将存储在计算机中的二进制数解析显示出来，称为"解码"。在解码过程中，如果使用了错误的解码规则，
则导致'a'解析成'b'或者乱码。

[字符集（Charset）](https://baike.baidu.com/item/%E5%AD%97%E7%AC%A6%E9%9B%86)：是一个系统支持的所有抽象字符的集合。字符是各种文字和符号的总称，包括各国家文字、标点符号、图形符号、数字等。

[字符编码（Character Encoding）](https://baike.baidu.com/item/%E5%AD%97%E7%AC%A6%E7%BC%96%E7%A0%81)：也称字集码，是把字符集中的字符编码为指定集合中某一对象（例如：比特模式、自然数序列、8位组或者电脉冲），以便文本在计算机中存储和通过通信网络的传递。

## 常用字符集和字符编码
常见字符集名称：ASCII字符集、GB2312字符集、BIG5字符集、 GB18030字符集、Unicode字符集等。

[UCS](https://baike.baidu.com/item/%E9%80%9A%E7%94%A8%E5%AD%97%E7%AC%A6%E9%9B%86)：通用字符集（Universal Character Set，UCS）是由ISO制定的ISO 10646（或称ISO/IEC 10646）标准所定义的字符编码方式，采用4字节编码。

通用字符集是与UNICODE同类的组织，UCS-2和UNICODE兼容。
位数：它有UCS-2和UCS-4两种格式，分别是2字节和4字节。
范围：UCS-4只是在UCS-2前面加了0×0000。

UNICODE字符集

作用：为世界650种语言进行统一编码，兼容ISO-8859-1。

位数：UNICODE字符集有多个编码方式，分别是UTF-8，UTF-16和UTF-32。

[EUC-CN](https://en.wikipedia.org/wiki/Extended_Unix_Code#EUC-CN)：EUC-CN是GB2312最常用的表示方法。浏览器编码表上的“GB2312”，通常都是指“EUC-CN”表示法。

[CP936](https://en.wikipedia.org/wiki/Code_page_936_(Microsoft_Windows)): GBK是对GB2312-80的扩展，也就是CP936字码表（Code Page 936）的扩展（之前CP936和GB 2312-80一模一样），
最早实现于Windows 95简体中文版。虽然GBK收录GB 13000.1-93的全部字符，但GBK是一种编码方式并向下兼容GB2312；
而GB 13000.1-93等同于Unicode 1.1是一种字符集，它的几种编码方式如UTF8、UTF16LE等，与GBK完全不兼容。

[GB18030](https://baike.baidu.com/item/gb18030)：国家标准GB18030-2000《信息交换用汉字编码字符集基本集的补充》是我国继GB2312-1980和GB13000-1993之后最重要的汉字编码标准，是我国计算机系统必须遵循的基础性标准之一。

GB18030-2000编码标准是由信息产业部和国家质量技术监督局在2000年 3月17日联合发布的，并且将作为一项国家标准在2001年的1月正式强制执行。

GB18030-2005《信息技术中文编码字符集》是我国制订的以汉字为主并包含多种我国少数民族文字（如藏、蒙古、傣、彝、朝鲜、维吾尔文等）的超大型中文编码字符集强制性标准，其中收入汉字70000余个。

[UTF-8](https://baike.baidu.com/item/UTF-8/481798)：UTF-8（8-bit Unicode Transformation Format）是一种针对Unicode的可变长度字符编码，又称万国码，由Ken Thompson于1992年创建。现在已经标准化为RFC 3629。UTF-8用1到6个字节编码Unicode字符。用在网页上可以统一页面显示中文简体繁体及其它语言（如英文，日文，韩文）。
