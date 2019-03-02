---
layout:     single
title:      "乘积小于K的子数组"
date:       2017-12-14 21:30:00 +0800
categories: [leetcode]
tags:       [Array, Two Pointers]
permalink:  /subarray-product-less-than-k/
---

## 713. 乘积小于K的子数组 (Medium)

<p>给定一个正整数数组&nbsp;<code>nums</code>。</p>

<p>找出该数组内乘积小于&nbsp;<code>k</code>&nbsp;的连续的子数组的个数。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> nums = [10,5,2,6], k = 100
<strong>输出:</strong> 8
<strong>解释:</strong> 8个乘积小于100的子数组分别为: [10], [5], [2], [6], [10,5], [5,2], [2,6], [5,2,6]。
需要注意的是 [10,5,2] 并不是乘积小于100的子数组。
</pre>

<p><strong>说明:</strong></p>

<ul>
	<li><code>0 &lt; nums.length &lt;= 50000</code></li>
	<li><code>0 &lt; nums[i] &lt; 1000</code></li>
	<li><code>0 &lt;= k &lt; 10^6</code></li>
</ul>

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[双指针](https://github.com/openset/leetcode/tree/master/tag/two-pointers/README.md)]

### 相似题目
  1. [乘积最大子序列](/maximum-product-subarray) (Medium)
  1. [Maximum Size Subarray Sum Equals k](/maximum-size-subarray-sum-equals-k) (Medium)
  1. [和为K的子数组](/subarray-sum-equals-k) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/subarray-product-less-than-k)
