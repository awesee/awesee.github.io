---
layout:     single
title:      "最长重复子数组"
date:       2017-12-19 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Binary Search, Dynamic Programming, Sliding Window, Hash Function, Rolling Hash]
permalink:  /problems/maximum-length-of-repeated-subarray/
---

## 718. 最长重复子数组 (Medium)

{% raw %}

<p>给两个整数数组&nbsp;<code>A</code>&nbsp;和&nbsp;<code>B</code>&nbsp;，返回两个数组中公共的、长度最长的子数组的长度。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>
A: [1,2,3,2,1]
B: [3,2,1,4,7]
<strong>输出：</strong>3
<strong>解释：</strong>
长度最长的公共子数组是 [3, 2, 1] 。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= len(A), len(B) &lt;= 1000</code></li>
	<li><code>0 &lt;= A[i], B[i] &lt; 100</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[滑动窗口](https://github.com/awesee/leetcode/tree/main/tag/sliding-window/README.md)]
  [[哈希函数](https://github.com/awesee/leetcode/tree/main/tag/hash-function/README.md)]
  [[滚动哈希](https://github.com/awesee/leetcode/tree/main/tag/rolling-hash/README.md)]

### 相似题目
  1. [长度最小的子数组](/problems/minimum-size-subarray-sum) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/maximum-length-of-repeated-subarray)
