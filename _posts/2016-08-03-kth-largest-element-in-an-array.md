---
layout:     single
title:      "数组中的第K个最大元素"
date:       2016-08-03 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Divide and Conquer, Quickselect, Sorting, Heap (Priority Queue)]
permalink:  /problems/kth-largest-element-in-an-array/
---

## 215. 数组中的第K个最大元素 (Medium)

{% raw %}

<p>给定整数数组 <code>nums</code> 和整数 <code>k</code>，请返回数组中第 <code><strong>k</strong></code> 个最大的元素。</p>

<p>请注意，你需要找的是数组排序后的第 <code>k</code> 个最大的元素，而不是第 <code>k</code> 个不同的元素。</p>

<p> </p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> <code>[3,2,1,5,6,4] 和</code> k = 2
<strong>输出:</strong> 5
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> <code>[3,2,3,1,2,4,5,5,6] 和</code> k = 4
<strong>输出:</strong> 4</pre>

<p> </p>

<p><strong>提示： </strong></p>

<ul>
	<li><code>1 <= k <= nums.length <= 10<sup>4</sup></code></li>
	<li><code>-10<sup>4</sup> <= nums[i] <= 10<sup>4</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[分治](https://github.com/openset/leetcode/tree/master/tag/divide-and-conquer/README.md)]
  [[快速选择](https://github.com/openset/leetcode/tree/master/tag/quickselect/README.md)]
  [[排序](https://github.com/openset/leetcode/tree/master/tag/sorting/README.md)]
  [[堆（优先队列）](https://github.com/openset/leetcode/tree/master/tag/heap-priority-queue/README.md)]

### 相似题目
  1. [摆动排序 II](/problems/wiggle-sort-ii) (Medium)
  1. [前 K 个高频元素](/problems/top-k-frequent-elements) (Medium)
  1. [第三大的数](/problems/third-maximum-number) (Easy)
  1. [数据流中的第 K 大元素](/problems/kth-largest-element-in-a-stream) (Easy)
  1. [最接近原点的 K 个点](/problems/k-closest-points-to-origin) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/kth-largest-element-in-an-array)
