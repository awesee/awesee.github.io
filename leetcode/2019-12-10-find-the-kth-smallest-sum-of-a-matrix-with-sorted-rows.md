---
layout:     single
title:      "有序矩阵中的第 k 个最小数组和"
date:       2019-12-10 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Binary Search, Matrix, Heap (Priority Queue)]
permalink:  /problems/find-the-kth-smallest-sum-of-a-matrix-with-sorted-rows/
---

## 1439. 有序矩阵中的第 k 个最小数组和 (Hard)

{% raw %}

<p>给你一个 <code>m&nbsp;* n</code> 的矩阵 <code>mat</code>，以及一个整数 <code>k</code> ，矩阵中的每一行都以非递减的顺序排列。</p>

<p>你可以从每一行中选出 1 个元素形成一个数组。返回所有可能数组中的第 k 个 <strong>最小</strong> 数组和。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>mat = [[1,3,11],[2,4,6]], k = 5
<strong>输出：</strong>7
<strong>解释：</strong>从每一行中选出一个元素，前 k 个和最小的数组分别是：
[1,2], [1,4], [3,2], [3,4], [1,6]。其中第 5 个的和是 7 。  </pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>mat = [[1,3,11],[2,4,6]], k = 9
<strong>输出：</strong>17
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>mat = [[1,10,10],[1,4,5],[2,3,6]], k = 7
<strong>输出：</strong>9
<strong>解释：</strong>从每一行中选出一个元素，前 k 个和最小的数组分别是：
[1,1,2], [1,1,3], [1,4,2], [1,4,3], [1,1,6], [1,5,2], [1,5,3]。其中第 7 个的和是 9 。 
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>mat = [[1,1,10],[2,2,9]], k = 7
<strong>输出：</strong>12
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>m == mat.length</code></li>
	<li><code>n == mat.length[i]</code></li>
	<li><code>1 &lt;= m, n &lt;= 40</code></li>
	<li><code>1 &lt;= k &lt;= min(200, n ^&nbsp;m)</code></li>
	<li><code>1 &lt;= mat[i][j] &lt;= 5000</code></li>
	<li><code>mat[i]</code> 是一个非递减数组</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[矩阵](https://github.com/awesee/leetcode/tree/main/tag/matrix/README.md)]
  [[堆（优先队列）](https://github.com/awesee/leetcode/tree/main/tag/heap-priority-queue/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/find-the-kth-smallest-sum-of-a-matrix-with-sorted-rows)
