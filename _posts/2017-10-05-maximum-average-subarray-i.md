---
layout:     single
title:      "子数组最大平均数 I"
date:       2017-10-05 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Sliding Window]
permalink:  /problems/maximum-average-subarray-i/
---

## 643. 子数组最大平均数 I (Easy)

{% raw %}

<p>给你一个由 <code>n</code> 个元素组成的整数数组 <code>nums</code> 和一个整数 <code>k</code> 。</p>

<p>请你找出平均数最大且 <strong>长度为 <code>k</code></strong> 的连续子数组，并输出该最大平均数。</p>

<p>任何误差小于 <code>10<sup>-5</sup></code> 的答案都将被视为正确答案。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [1,12,-5,-6,50,3], k = 4
<strong>输出：</strong>12.75
<strong>解释：</strong>最大平均数 (12-5-6+50)/4 = 51/4 = 12.75
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [5], k = 1
<strong>输出：</strong>5.00000
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>n == nums.length</code></li>
	<li><code>1 &lt;= k &lt;= n &lt;= 10<sup>5</sup></code></li>
	<li><code>-10<sup>4</sup> &lt;= nums[i] &lt;= 10<sup>4</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[滑动窗口](https://github.com/awesee/leetcode/tree/main/tag/sliding-window/README.md)]

### 相似题目
  1. [子数组最大平均数 II](/problems/maximum-average-subarray-ii) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/maximum-average-subarray-i)
