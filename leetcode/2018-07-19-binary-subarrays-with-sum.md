---
layout:     single
title:      "和相同的二元子数组"
date:       2018-07-19 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, Prefix Sum, Sliding Window]
permalink:  /problems/binary-subarrays-with-sum/
---

## 930. 和相同的二元子数组 (Medium)

{% raw %}

<p>给你一个二元数组 <code>nums</code> ，和一个整数 <code>goal</code> ，请你统计并返回有多少个和为 <code>goal</code> 的<strong> 非空</strong> 子数组。</p>

<p><strong>子数组</strong> 是数组的一段连续部分。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [1,0,1,0,1], goal = 2
<strong>输出：</strong>4
<strong>解释：</strong>
有 4 个满足题目要求的子数组：[1,0,1]、[1,0,1,0]、[0,1,0,1]、[1,0,1]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [0,0,0,0,0], goal = 0
<strong>输出：</strong>15
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 3 * 10<sup>4</sup></code></li>
	<li><code>nums[i]</code> 不是 <code>0</code> 就是 <code>1</code></li>
	<li><code>0 <= goal <= nums.length</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/master/tag/hash-table/README.md)]
  [[前缀和](https://github.com/awesee/leetcode/tree/master/tag/prefix-sum/README.md)]
  [[滑动窗口](https://github.com/awesee/leetcode/tree/master/tag/sliding-window/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/binary-subarrays-with-sum)
