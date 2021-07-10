---
layout:     single
title:      "区间和的个数"
date:       2016-11-23 21:30:00 +0800
categories: [Leetcode]
tags:       [Binary Indexed Tree, Segment Tree, Array, Binary Search, Divide and Conquer, Ordered Set, Merge Sort]
permalink:  /problems/count-of-range-sum/
---

## 327. 区间和的个数 (Hard)

{% raw %}

<p>给你一个整数数组 <code>nums</code> 以及两个整数 <code>lower</code> 和 <code>upper</code> 。求数组中，值位于范围 <code>[lower, upper]</code> （包含 <code>lower</code> 和 <code>upper</code>）之内的 <strong>区间和的个数</strong> 。</p>

<p><strong>区间和</strong> <code>S(i, j)</code> 表示在 <code>nums</code> 中，位置从 <code>i</code> 到 <code>j</code> 的元素之和，包含 <code>i</code> 和 <code>j</code> (<code>i</code> ≤ <code>j</code>)。</p>

<p> </p>
<strong>示例 1：</strong>

<pre>
<strong>输入：</strong>nums = [-2,5,-1], lower = -2, upper = 2
<strong>输出：</strong>3
<strong>解释：</strong>存在三个区间：[0,0]、[2,2] 和 [0,2] ，对应的区间和分别是：-2 、-1 、2 。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [0], lower = 0, upper = 0
<strong>输出：</strong>1
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 10<sup>5</sup></code></li>
	<li><code>-2<sup>31</sup> <= nums[i] <= 2<sup>31</sup> - 1</code></li>
	<li><code>-10<sup>5</sup> <= lower <= upper <= 10<sup>5</sup></code></li>
	<li>题目数据保证答案是一个 <strong>32 位</strong> 的整数</li>
</ul>

{% endraw %}

### 相关话题
  [[树状数组](https://github.com/openset/leetcode/tree/master/tag/binary-indexed-tree/README.md)]
  [[线段树](https://github.com/openset/leetcode/tree/master/tag/segment-tree/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[二分查找](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]
  [[分治](https://github.com/openset/leetcode/tree/master/tag/divide-and-conquer/README.md)]
  [[有序集合](https://github.com/openset/leetcode/tree/master/tag/ordered-set/README.md)]
  [[归并排序](https://github.com/openset/leetcode/tree/master/tag/merge-sort/README.md)]

### 相似题目
  1. [计算右侧小于当前元素的个数](/problems/count-of-smaller-numbers-after-self) (Hard)
  1. [翻转对](/problems/reverse-pairs) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/count-of-range-sum)
