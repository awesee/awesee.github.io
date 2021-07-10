---
layout:     single
title:      "连续数组"
date:       2017-06-09 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, Prefix Sum]
permalink:  /problems/contiguous-array/
---

## 525. 连续数组 (Medium)

{% raw %}

<p>给定一个二进制数组 <code>nums</code> , 找到含有相同数量的 <code>0</code> 和 <code>1</code> 的最长连续子数组，并返回该子数组的长度。</p>

<p> </p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> nums = [0,1]
<strong>输出:</strong> 2
<strong>说明:</strong> [0, 1] 是具有相同数量 0 和 1 的最长连续子数组。</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> nums = [0,1,0]
<strong>输出:</strong> 2
<strong>说明:</strong> [0, 1] (或 [1, 0]) 是具有相同数量0和1的最长连续子数组。</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 10<sup>5</sup></code></li>
	<li><code>nums[i]</code> 不是 <code>0</code> 就是 <code>1</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[前缀和](https://github.com/openset/leetcode/tree/master/tag/prefix-sum/README.md)]

### 相似题目
  1. [和等于 k 的最长子数组长度](/problems/maximum-size-subarray-sum-equals-k) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/contiguous-array)
