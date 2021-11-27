---
layout:     single
title:      "划分为k个相等的子集"
date:       2017-11-29 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Memoization, Array, Dynamic Programming, Backtracking, Bitmask]
permalink:  /problems/partition-to-k-equal-sum-subsets/
---

## 698. 划分为k个相等的子集 (Medium)

{% raw %}

<p>给定一个整数数组&nbsp;&nbsp;<code>nums</code> 和一个正整数 <code>k</code>，找出是否有可能把这个数组分成 <code>k</code> 个非空子集，其总和都相等。</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong> nums = [4, 3, 2, 3, 5, 2, 1], k = 4
<strong>输出：</strong> True
<strong>说明：</strong> 有可能将其分成 4 个子集（5），（1,4），（2,3），（2,3）等于总和。</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= k &lt;= len(nums) &lt;= 16</code></li>
	<li><code>0 &lt; nums[i] &lt; 10000</code></li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[记忆化搜索](https://github.com/awesee/leetcode/tree/main/tag/memoization/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[回溯](https://github.com/awesee/leetcode/tree/main/tag/backtracking/README.md)]
  [[状态压缩](https://github.com/awesee/leetcode/tree/main/tag/bitmask/README.md)]

### 相似题目
  1. [分割等和子集](/problems/partition-equal-subset-sum) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/partition-to-k-equal-sum-subsets)
