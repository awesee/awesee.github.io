---
layout:     single
title:      "找出第 k 小的距离对"
date:       2017-12-20 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Two Pointers, Binary Search, Sorting]
permalink:  /problems/find-k-th-smallest-pair-distance/
---

## 719. 找出第 k 小的距离对 (Hard)

{% raw %}

<p>给定一个整数数组，返回所有数对之间的第 k 个最小<strong>距离</strong>。一对 (A, B) 的距离被定义为 A 和 B 之间的绝对差值。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入：</strong>
nums = [1,3,1]
k = 1
<strong>输出：0</strong> 
<strong>解释：</strong>
所有数对如下：
(1,3) -&gt; 2
(1,1) -&gt; 0
(3,1) -&gt; 2
因此第 1 个最小距离的数对是 (1,1)，它们之间的距离为 0。
</pre>

<p><strong>提示:</strong></p>

<ol>
	<li><code>2 &lt;= len(nums) &lt;= 10000</code>.</li>
	<li><code>0 &lt;= nums[i] &lt; 1000000</code>.</li>
	<li><code>1 &lt;= k &lt;= len(nums) * (len(nums) - 1) / 2</code>.</li>
</ol>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]

### 相似题目
  1. [查找和最小的K对数字](/problems/find-k-pairs-with-smallest-sums) (Medium)
  1. [有序矩阵中第 K 小的元素](/problems/kth-smallest-element-in-a-sorted-matrix) (Medium)
  1. [找到 K 个最接近的元素](/problems/find-k-closest-elements) (Medium)
  1. [乘法表中第k小的数](/problems/kth-smallest-number-in-multiplication-table) (Hard)
  1. [第 K 个最小的素数分数](/problems/k-th-smallest-prime-fraction) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/find-k-th-smallest-pair-distance)
