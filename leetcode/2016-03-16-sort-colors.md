---
layout:     single
title:      "颜色分类"
date:       2016-03-16 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Two Pointers, Sorting]
permalink:  /problems/sort-colors/
---

## 75. 颜色分类 (Medium)

{% raw %}

<p>给定一个包含红色、白色和蓝色，一共 <code>n</code><em> </em>个元素的数组，<strong><a href="https://baike.baidu.com/item/%E5%8E%9F%E5%9C%B0%E7%AE%97%E6%B3%95" target="_blank">原地</a></strong>对它们进行排序，使得相同颜色的元素相邻，并按照红色、白色、蓝色顺序排列。</p>

<p>此题中，我们使用整数 <code>0</code>、 <code>1</code> 和 <code>2</code> 分别表示红色、白色和蓝色。</p>

<ul>
</ul>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [2,0,2,1,1,0]
<strong>输出：</strong>[0,0,1,1,2,2]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [2,0,1]
<strong>输出：</strong>[0,1,2]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>nums = [0]
<strong>输出：</strong>[0]
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>nums = [1]
<strong>输出：</strong>[1]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>n == nums.length</code></li>
	<li><code>1 <= n <= 300</code></li>
	<li><code>nums[i]</code> 为 <code>0</code>、<code>1</code> 或 <code>2</code></li>
</ul>

<p> </p>

<p><strong>进阶：</strong></p>

<ul>
	<li>你可以不使用代码库中的排序函数来解决这道题吗？</li>
	<li>你能想出一个仅使用常数空间的一趟扫描算法吗？</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]

### 相似题目
  1. [排序链表](/problems/sort-list) (Medium)
  1. [摆动排序](/problems/wiggle-sort) (Medium)
  1. [摆动排序 II](/problems/wiggle-sort-ii) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/sort-colors)
