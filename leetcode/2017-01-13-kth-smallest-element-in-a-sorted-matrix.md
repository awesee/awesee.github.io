---
layout:     single
title:      "有序矩阵中第 K 小的元素"
date:       2017-01-13 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Binary Search, Matrix, Sorting, Heap (Priority Queue)]
permalink:  /problems/kth-smallest-element-in-a-sorted-matrix/
---

## 378. 有序矩阵中第 K 小的元素 (Medium)

{% raw %}

<p>给你一个 <code>n x n</code><em> </em>矩阵 <code>matrix</code> ，其中每行和每列元素均按升序排序，找到矩阵中第 <code>k</code> 小的元素。<br />
请注意，它是 <strong>排序后</strong> 的第 <code>k</code> 小元素，而不是第 <code>k</code> 个 <strong>不同</strong> 的元素。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>matrix = [[1,5,9],[10,11,13],[12,13,15]], k = 8
<strong>输出：</strong>13
<strong>解释：</strong>矩阵中的元素为 [1,5,9,10,11,12,13,<strong>13</strong>,15]，第 8 小元素是 13
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>matrix = [[-5]], k = 1
<strong>输出：</strong>-5
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>n == matrix.length</code></li>
	<li><code>n == matrix[i].length</code></li>
	<li><code>1 <= n <= 300</code></li>
	<li><code>-10<sup>9</sup> <= matrix[i][j] <= 10<sup>9</sup></code></li>
	<li>题目数据 <strong>保证</strong> <code>matrix</code> 中的所有行和列都按 <strong>非递减顺序</strong> 排列</li>
	<li><code>1 <= k <= n<sup>2</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[矩阵](https://github.com/awesee/leetcode/tree/main/tag/matrix/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]
  [[堆（优先队列）](https://github.com/awesee/leetcode/tree/main/tag/heap-priority-queue/README.md)]

### 相似题目
  1. [查找和最小的K对数字](/problems/find-k-pairs-with-smallest-sums) (Medium)
  1. [乘法表中第k小的数](/problems/kth-smallest-number-in-multiplication-table) (Hard)
  1. [找出第 k 小的距离对](/problems/find-k-th-smallest-pair-distance) (Hard)
  1. [第 K 个最小的素数分数](/problems/k-th-smallest-prime-fraction) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/kth-smallest-element-in-a-sorted-matrix)
