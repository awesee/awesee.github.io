---
layout:     single
title:      "数组的度"
date:       2017-11-28 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table]
permalink:  /problems/degree-of-an-array/
---

## 697. 数组的度 (Easy)

{% raw %}

<p>给定一个非空且只包含非负数的整数数组 <code>nums</code>，数组的度的定义是指数组里任一元素出现频数的最大值。</p>

<p>你的任务是在 <code>nums</code> 中找到与 <code>nums</code> 拥有相同大小的度的最短连续子数组，返回其长度。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>[1, 2, 2, 3, 1]
<strong>输出：</strong>2
<strong>解释：</strong>
输入数组的度是2，因为元素1和2的出现频数最大，均为2.
连续子数组里面拥有相同度的有如下所示:
[1, 2, 2, 3, 1], [1, 2, 2, 3], [2, 2, 3, 1], [1, 2, 2], [2, 2, 3], [2, 2]
最短连续子数组[2, 2]的长度为2，所以返回2.
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>[1,2,2,3,1,4,2]
<strong>输出：</strong>6
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>nums.length</code> 在1到 50,000 区间范围内。</li>
	<li><code>nums[i]</code> 是一个在 0 到 49,999 范围内的整数。</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]

### 相似题目
  1. [最大子序和](/problems/maximum-subarray) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/degree-of-an-array)
