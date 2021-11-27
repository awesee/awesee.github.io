---
layout:     single
title:      "递增子序列"
date:       2017-05-06 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Array, Hash Table, Backtracking]
permalink:  /problems/increasing-subsequences/
---

## 491. 递增子序列 (Medium)

{% raw %}

<p>给你一个整数数组 <code>nums</code> ，找出并返回所有该数组中不同的递增子序列，递增子序列中 <strong>至少有两个元素</strong> 。你可以按 <strong>任意顺序</strong> 返回答案。</p>

<p>数组中可能含有重复元素，如出现两个整数相等，也可以视作递增序列的一种特殊情况。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [4,6,7,7]
<strong>输出：</strong>[[4,6],[4,6,7],[4,6,7,7],[4,7],[4,7,7],[6,7],[6,7,7],[7,7]]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [4,4,3,2,1]
<strong>输出：</strong>[[4,4]]
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= nums.length &lt;= 15</code></li>
	<li><code>-100 &lt;= nums[i] &lt;= 100</code></li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/master/tag/bit-manipulation/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/master/tag/hash-table/README.md)]
  [[回溯](https://github.com/awesee/leetcode/tree/master/tag/backtracking/README.md)]

### 相似题目
  1. [最长数对链](/problems/maximum-length-of-pair-chain) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/increasing-subsequences)
