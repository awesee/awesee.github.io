---
layout:     single
title:      "递增的三元子序列"
date:       2016-11-30 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Array]
permalink:  /problems/increasing-triplet-subsequence/
---

## 334. 递增的三元子序列 (Medium)

{% raw %}

<p>给你一个整数数组 <code>nums</code> ，判断这个数组中是否存在长度为 <code>3</code> 的递增子序列。</p>

<p>如果存在这样的三元组下标 <code>(i, j, k)</code> 且满足 <code>i < j < k</code> ，使得 <code>nums[i] < nums[j] < nums[k]</code> ，返回 <code>true</code> ；否则，返回 <code>false</code> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [1,2,3,4,5]
<strong>输出：</strong>true
<strong>解释：</strong>任何 i < j < k 的三元组都满足题意
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [5,4,3,2,1]
<strong>输出：</strong>false
<strong>解释：</strong>不存在满足题意的三元组</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>nums = [2,1,5,0,4,6]
<strong>输出：</strong>true
<strong>解释：</strong>三元组 (3, 4, 5) 满足题意，因为 nums[3] == 0 < nums[4] == 4 < nums[5] == 6
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 10<sup>5</sup></code></li>
	<li><code>-2<sup>31</sup> <= nums[i] <= 2<sup>31</sup> - 1</code></li>
</ul>

<p> </p>

<p><strong>进阶：</strong>你能实现时间复杂度为 <code>O(n)</code> ，空间复杂度为 <code>O(1)</code> 的解决方案吗？</p>

{% endraw %}

### 相关话题
  [[贪心](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]

### 相似题目
  1. [最长递增子序列](/problems/longest-increasing-subsequence) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/increasing-triplet-subsequence)
