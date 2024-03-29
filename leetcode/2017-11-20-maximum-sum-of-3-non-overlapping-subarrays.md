---
layout:     single
title:      "三个无重叠子数组的最大和"
date:       2017-11-20 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Dynamic Programming]
permalink:  /problems/maximum-sum-of-3-non-overlapping-subarrays/
---

## 689. 三个无重叠子数组的最大和 (Hard)

{% raw %}

<p>给定数组&nbsp;<code>nums</code>&nbsp;由正整数组成，找到三个互不重叠的子数组的最大和。</p>

<p>每个子数组的长度为<code>k</code>，我们要使这<code>3*k</code>个项的和最大化。</p>

<p>返回每个区间起始索引的列表（索引从 0 开始）。如果有多个结果，返回字典序最小的一个。</p>

<p><strong>示例:</strong></p>

<pre>
<strong>输入:</strong> [1,2,1,2,6,7,5,1], 2
<strong>输出:</strong> [0, 3, 5]
<strong>解释:</strong> 子数组 [1, 2], [2, 6], [7, 5] 对应的起始索引为 [0, 3, 5]。
我们也可以取 [2, 1], 但是结果 [1, 3, 5] 在字典序上更大。
</pre>

<p><strong>注意:</strong></p>

<ul>
	<li><code>nums.length</code>的范围在<code>[1, 20000]</code>之间。</li>
	<li><code>nums[i]</code>的范围在<code>[1, 65535]</code>之间。</li>
	<li><code>k</code>的范围在<code>[1, floor(nums.length / 3)]</code>之间。</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/master/tag/array/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/master/tag/dynamic-programming/README.md)]

### 相似题目
  1. [买卖股票的最佳时机 III](/problems/best-time-to-buy-and-sell-stock-iii) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/maximum-sum-of-3-non-overlapping-subarrays)
