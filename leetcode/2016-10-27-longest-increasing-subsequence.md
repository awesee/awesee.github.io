---
layout:     single
title:      "最长递增子序列"
date:       2016-10-27 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Binary Search, Dynamic Programming]
permalink:  /problems/longest-increasing-subsequence/
---

## 300. 最长递增子序列 (Medium)

{% raw %}

<p>给你一个整数数组 <code>nums</code> ，找到其中最长严格递增子序列的长度。</p>

<p>子序列是由数组派生而来的序列，删除（或不删除）数组中的元素而不改变其余元素的顺序。例如，<code>[3,6,2,7]</code> 是数组 <code>[0,3,1,6,2,2,7]</code> 的子序列。</p>
 

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [10,9,2,5,3,7,101,18]
<strong>输出：</strong>4
<strong>解释：</strong>最长递增子序列是 [2,3,7,101]，因此长度为 4 。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [0,1,0,3,2,3]
<strong>输出：</strong>4
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>nums = [7,7,7,7,7,7,7]
<strong>输出：</strong>1
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 2500</code></li>
	<li><code>-10<sup>4</sup> <= nums[i] <= 10<sup>4</sup></code></li>
</ul>

<p> </p>

<p><b>进阶：</b></p>

<ul>
	<li>你可以设计时间复杂度为 <code>O(n<sup>2</sup>)</code> 的解决方案吗？</li>
	<li>你能将算法的时间复杂度降低到 <code>O(n log(n))</code> 吗?</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

### 相似题目
  1. [递增的三元子序列](/problems/increasing-triplet-subsequence) (Medium)
  1. [俄罗斯套娃信封问题](/problems/russian-doll-envelopes) (Hard)
  1. [最长数对链](/problems/maximum-length-of-pair-chain) (Medium)
  1. [最长递增子序列的个数](/problems/number-of-longest-increasing-subsequence) (Medium)
  1. [两个字符串的最小ASCII删除和](/problems/minimum-ascii-delete-sum-for-two-strings) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/longest-increasing-subsequence)
