---
layout:     single
title:      "累加数"
date:       2016-11-02 21:30:00 +0800
categories: [Leetcode]
tags:       [String, Backtracking]
permalink:  /problems/additive-number/
---

## 306. 累加数 (Medium)

{% raw %}

<p>累加数是一个字符串，组成它的数字可以形成累加序列。</p>

<p>一个有效的累加序列必须<strong>至少</strong>包含 3 个数。除了最开始的两个数以外，字符串中的其他数都等于它之前两个数相加的和。</p>

<p>给定一个只包含数字&nbsp;<code>&#39;0&#39;-&#39;9&#39;</code>&nbsp;的字符串，编写一个算法来判断给定输入是否是累加数。</p>

<p><strong>说明:&nbsp;</strong>累加序列里的数不会以 0 开头，所以不会出现&nbsp;<code>1, 2, 03</code> 或者&nbsp;<code>1, 02, 3</code>&nbsp;的情况。</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入:</strong> <code>&quot;112358&quot;</code>
<strong>输出:</strong> true 
<strong>解释: </strong>累加序列为: <code>1, 1, 2, 3, 5, 8 </code>。1 + 1 = 2, 1 + 2 = 3, 2 + 3 = 5, 3 + 5 = 8
</pre>

<p><strong>示例&nbsp;2:</strong></p>

<pre><strong>输入:</strong> <code>&quot;199100199&quot;</code>
<strong>输出:</strong> true 
<strong>解释: </strong>累加序列为: <code>1, 99, 100, 199。</code>1 + 99 = 100, 99 + 100 = 199</pre>

<p><strong>进阶:</strong><br>
你如何处理一个溢出的过大的整数输入?</p>

{% endraw %}

### 相关话题
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[回溯](https://github.com/awesee/leetcode/tree/main/tag/backtracking/README.md)]

### 相似题目
  1. [将数组拆分成斐波那契序列](/problems/split-array-into-fibonacci-sequence) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/additive-number)
