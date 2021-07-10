---
layout:     single
title:      "位1的个数"
date:       2016-07-10 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation]
permalink:  /problems/number-of-1-bits/
---

## 191. 位1的个数 (Easy)

{% raw %}

<p>编写一个函数，输入是一个无符号整数（以二进制串的形式），返回其二进制表达式中数字位数为 '1' 的个数（也被称为<a href="https://baike.baidu.com/item/%E6%B1%89%E6%98%8E%E9%87%8D%E9%87%8F" target="_blank">汉明重量</a>）。</p>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>请注意，在某些语言（如 Java）中，没有无符号整数类型。在这种情况下，输入和输出都将被指定为有符号整数类型，并且不应影响您的实现，因为无论整数是有符号的还是无符号的，其内部的二进制表示形式都是相同的。</li>
	<li>在 Java 中，编译器使用<a href="https://baike.baidu.com/item/二进制补码/5295284" target="_blank">二进制补码</a>记法来表示有符号整数。因此，在上面的 <strong>示例 3</strong> 中，输入表示有符号整数 <code>-3</code>。</li>
</ul>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>00000000000000000000000000001011
<strong>输出：</strong>3
<strong>解释：</strong>输入的二进制串 <code><strong>00000000000000000000000000001011</strong> 中，共有三位为 '1'。</code>
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>00000000000000000000000010000000
<strong>输出：</strong>1
<strong>解释：</strong>输入的二进制串 <strong>00000000000000000000000010000000</strong> 中，共有一位为 '1'。
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>11111111111111111111111111111101
<strong>输出：</strong>31
<strong>解释：</strong>输入的二进制串 <strong>11111111111111111111111111111101</strong> 中，共有 31 位为 '1'。</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>输入必须是长度为 <code>32</code> 的 <strong>二进制串</strong> 。</li>
</ul>

<ul>
</ul>

<p> </p>

<p><strong>进阶</strong>：</p>

<ul>
	<li>如果多次调用这个函数，你将如何优化你的算法？</li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/openset/leetcode/tree/master/tag/bit-manipulation/README.md)]

### 相似题目
  1. [颠倒二进制位](/problems/reverse-bits) (Easy)
  1. [2 的幂](/problems/power-of-two) (Easy)
  1. [比特位计数](/problems/counting-bits) (Easy)
  1. [二进制手表](/problems/binary-watch) (Easy)
  1. [汉明距离](/problems/hamming-distance) (Easy)
  1. [交替位二进制数](/problems/binary-number-with-alternating-bits) (Easy)
  1. [二进制表示中质数个计算置位](/problems/prime-number-of-set-bits-in-binary-representation) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/number-of-1-bits)
