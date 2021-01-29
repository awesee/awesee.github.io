---
layout:     single
title:      "寻找峰值"
date:       2016-06-11 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Binary Search]
permalink:  /problems/find-peak-element/
---

## 162. 寻找峰值 (Medium)

{% raw %}

<p>峰值元素是指其值大于左右相邻值的元素。</p>

<p>给你一个输入数组 <code>nums</code>，找到峰值元素并返回其索引。数组可能包含多个峰值，在这种情况下，返回 <strong>任何一个峰值</strong> 所在位置即可。</p>

<p>你可以假设 <code>nums[-1] = nums[n] = -∞</code> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = <code>[1,2,3,1]</code>
<strong>输出：</strong>2
<strong>解释：</strong>3 是峰值元素，你的函数应该返回其索引 2。</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = <code>[</code>1,2,1,3,5,6,4]
<strong>输出：</strong>1 或 5 
<strong>解释：</strong>你的函数可以返回索引 1，其峰值元素为 2；
     或者返回索引 5， 其峰值元素为 6。
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 1000</code></li>
	<li><code>-2<sup>31</sup> <= nums[i] <= 2<sup>31</sup> - 1</code></li>
	<li>对于所有有效的 <code>i</code> 都有 <code>nums[i] != nums[i + 1]</code></li>
</ul>

<p> </p>

<p><strong>进阶：</strong>你可以实现时间复杂度为 <code>O(logN)</code><em> </em>的解决方案吗？</p>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[二分查找](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]

### 相似题目
  1. [山脉数组的峰顶索引](/problems/peak-index-in-a-mountain-array) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/find-peak-element)
