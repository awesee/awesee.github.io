---
layout:     single
title:      "和为 K 的子数组"
date:       2017-07-14 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, Prefix Sum]
permalink:  /problems/subarray-sum-equals-k/
---

## 560. 和为 K 的子数组 (Medium)

{% raw %}

<p>给你一个整数数组 <code>nums</code> 和一个整数&nbsp;<code>k</code> ，请你统计并返回该数组中和为&nbsp;<code>k</code><strong>&nbsp;</strong>的连续子数组的个数。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [1,1,1], k = 2
<strong>输出：</strong>2
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [1,2,3], k = 3
<strong>输出：</strong>2
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= nums.length &lt;= 2 * 10<sup>4</sup></code></li>
	<li><code>-1000 &lt;= nums[i] &lt;= 1000</code></li>
	<li><code>-10<sup>7</sup> &lt;= k &lt;= 10<sup>7</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[前缀和](https://github.com/openset/leetcode/tree/master/tag/prefix-sum/README.md)]

### 相似题目
  1. [两数之和](/problems/two-sum) (Easy)
  1. [连续的子数组和](/problems/continuous-subarray-sum) (Medium)
  1. [乘积小于K的子数组](/problems/subarray-product-less-than-k) (Medium)
  1. [寻找数组的中心下标](/problems/find-pivot-index) (Easy)
  1. [和可被 K 整除的子数组](/problems/subarray-sums-divisible-by-k) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/subarray-sum-equals-k)
