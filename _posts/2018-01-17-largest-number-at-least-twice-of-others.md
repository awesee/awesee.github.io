---
layout:     single
title:      "至少是其他数字两倍的最大数"
date:       2018-01-17 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Sorting]
permalink:  /problems/largest-number-at-least-twice-of-others/
---

## 747. 至少是其他数字两倍的最大数 (Easy)

{% raw %}

<p>给你一个整数数组 <code>nums</code> ，其中总是存在 <strong>唯一的</strong> 一个最大整数 。</p>

<p>请你找出数组中的最大元素并检查它是否 <strong>至少是数组中每个其他数字的两倍</strong> 。如果是，则返回 <strong>最大元素的下标</strong> ，否则返回 <code>-1</code> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [3,6,1,0]
<strong>输出：</strong>1
<strong>解释：</strong>6 是最大的整数，对于数组中的其他整数，6 大于数组中其他元素的两倍。6 的下标是 1 ，所以返回 1 。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [1,2,3,4]
<strong>输出：</strong>-1
<strong>解释：</strong>4 没有超过 3 的两倍大，所以返回 -1 。</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>nums = [1]
<strong>输出：</strong>0
<strong>解释：</strong>因为不存在其他数字，所以认为现有数字 1 至少是其他数字的两倍。
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 50</code></li>
	<li><code>0 <= nums[i] <= 100</code></li>
	<li><code>nums</code> 中的最大元素是唯一的</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[排序](https://github.com/openset/leetcode/tree/master/tag/sorting/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/largest-number-at-least-twice-of-others)
