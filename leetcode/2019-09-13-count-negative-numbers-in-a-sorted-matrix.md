---
layout:     single
title:      "统计有序矩阵中的负数"
date:       2019-09-13 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Binary Search, Matrix]
permalink:  /problems/count-negative-numbers-in-a-sorted-matrix/
---

## 1351. 统计有序矩阵中的负数 (Easy)

{% raw %}

<p>给你一个 <code>m * n</code> 的矩阵 <code>grid</code>，矩阵中的元素无论是按行还是按列，都以非递增顺序排列。 </p>

<p>请你统计并返回 <code>grid</code> 中 <strong>负数</strong> 的数目。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>grid = [[4,3,2,-1],[3,2,1,-1],[1,1,-1,-2],[-1,-1,-2,-3]]
<strong>输出：</strong>8
<strong>解释：</strong>矩阵中共有 8 个负数。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>grid = [[3,2],[1,0]]
<strong>输出：</strong>0
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>grid = [[1,-1],[-1,-1]]
<strong>输出：</strong>3
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>grid = [[-1]]
<strong>输出：</strong>1
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>m == grid.length</code></li>
	<li><code>n == grid[i].length</code></li>
	<li><code>1 <= m, n <= 100</code></li>
	<li><code>-100 <= grid[i][j] <= 100</code></li>
</ul>

<p> </p>

<p><strong>进阶：</strong>你可以设计一个时间复杂度为 <code>O(n + m)</code> 的解决方案吗？</p>

<p> </p>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[矩阵](https://github.com/awesee/leetcode/tree/main/tag/matrix/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/count-negative-numbers-in-a-sorted-matrix)
