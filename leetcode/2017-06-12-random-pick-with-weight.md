---
layout:     single
title:      "按权重随机选择"
date:       2017-06-12 21:30:00 +0800
categories: [leetcode]
tags:       [Binary Search, Random]
permalink:  /random-pick-with-weight/
---

## 528. 按权重随机选择 (Medium)

<p>给定一个正整数数组&nbsp;<code>w</code> ，其中&nbsp;<code>w[i]</code>&nbsp;代表位置&nbsp;<code>i</code>&nbsp;的权重，请写一个函数&nbsp;<code>pickIndex</code>&nbsp;，它可以随机地获取位置&nbsp;<code>i</code>，选取位置&nbsp;<code>i</code>&nbsp;的概率与&nbsp;<code>w[i]</code>&nbsp;成正比。</p>

<p>说明:</p>

<ol>
	<li><code>1 &lt;= w.length &lt;= 10000</code></li>
	<li><code>1 &lt;= w[i] &lt;= 10^5</code></li>
	<li><code>pickIndex</code>&nbsp;将被调用不超过&nbsp;<code>10000</code>&nbsp;次</li>
</ol>

<p><strong>示例1:</strong></p>

<pre>
<strong>输入: 
</strong>[&quot;Solution&quot;,&quot;pickIndex&quot;]
[[[1]],[]]
<strong>输出: </strong>[null,0]
</pre>

<p><strong>示例2:</strong></p>

<pre>
<strong>输入: 
</strong>[&quot;Solution&quot;,&quot;pickIndex&quot;,&quot;pickIndex&quot;,&quot;pickIndex&quot;,&quot;pickIndex&quot;,&quot;pickIndex&quot;]
[[[1,3]],[],[],[],[],[]]
<strong>输出: </strong>[null,0,1,1,1,0]</pre>

<p><strong>输入语法说明：</strong></p>

<p>输入是两个列表：调用成员函数名和调用的参数。<code>Solution</code>&nbsp;的构造函数有一个参数，即数组&nbsp;<code>w</code>。<code>pickIndex</code>&nbsp;没有参数。输入参数是一个列表，即使参数为空，也会输入一个 [] 空列表。</p>

### 相关话题
  [[二分查找](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]
  [[Random](https://github.com/openset/leetcode/tree/master/tag/random/README.md)]

### 相似题目
  1. [随机数索引](/random-pick-index) (Medium)
  1. [黑名单中的随机数](/random-pick-with-blacklist) (Hard)
  1. [非重叠矩形中的随机点](/random-point-in-non-overlapping-rectangles) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/random-pick-with-weight)
