---
layout:     single
title:      "最大连续1的个数 III"
date:       2018-10-01 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Binary Search, Prefix Sum, Sliding Window]
permalink:  /problems/max-consecutive-ones-iii/
---

## 1004. 最大连续1的个数 III (Medium)

{% raw %}

<p>给定一个由若干 <code>0</code> 和 <code>1</code> 组成的数组&nbsp;<code>A</code>，我们最多可以将&nbsp;<code>K</code>&nbsp;个值从 0 变成 1 。</p>

<p>返回仅包含 1 的最长（连续）子数组的长度。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>A = [1,1,1,0,0,0,1,1,1,1,0], K = 2
<strong>输出：</strong>6
<strong>解释： </strong>
[1,1,1,0,0,<strong>1</strong>,1,1,1,1,<strong>1</strong>]
粗体数字从 0 翻转到 1，最长的子数组长度为 6。</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>A = [0,0,1,1,0,0,1,1,1,0,1,1,0,0,0,1,1,1,1], K = 3
<strong>输出：</strong>10
<strong>解释：</strong>
[0,0,1,1,<strong>1</strong>,<strong>1</strong>,1,1,1,<strong>1</strong>,1,1,0,0,0,1,1,1,1]
粗体数字从 0 翻转到 1，最长的子数组长度为 10。</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= A.length &lt;= 20000</code></li>
	<li><code>0 &lt;= K &lt;= A.length</code></li>
	<li><code>A[i]</code> 为&nbsp;<code>0</code>&nbsp;或&nbsp;<code>1</code>&nbsp;</li>
</ol>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[前缀和](https://github.com/awesee/leetcode/tree/main/tag/prefix-sum/README.md)]
  [[滑动窗口](https://github.com/awesee/leetcode/tree/main/tag/sliding-window/README.md)]

### 相似题目
  1. [至多包含 K 个不同字符的最长子串](/problems/longest-substring-with-at-most-k-distinct-characters) (Medium)
  1. [替换后的最长重复字符](/problems/longest-repeating-character-replacement) (Medium)
  1. [最大连续 1 的个数](/problems/max-consecutive-ones) (Easy)
  1. [最大连续1的个数 II](/problems/max-consecutive-ones-ii) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/max-consecutive-ones-iii)
