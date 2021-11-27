---
layout:     single
title:      "搜索二维矩阵 II"
date:       2016-08-28 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Binary Search, Divide and Conquer, Matrix]
permalink:  /problems/search-a-2d-matrix-ii/
---

## 240. 搜索二维矩阵 II (Medium)

{% raw %}

<p>编写一个高效的算法来搜索 <code><em>m</em> x <em>n</em></code> 矩阵 <code>matrix</code> 中的一个目标值 <code>target</code> 。该矩阵具有以下特性：</p>

<ul>
	<li>每行的元素从左到右升序排列。</li>
	<li>每列的元素从上到下升序排列。</li>
</ul>

<p> </p>

<p><b>示例 1：</b></p>
<img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/11/25/searchgrid2.jpg" />
<pre>
<b>输入：</b>matrix = [[1,4,7,11,15],[2,5,8,12,19],[3,6,9,16,22],[10,13,14,17,24],[18,21,23,26,30]], target = 5
<b>输出：</b>true
</pre>

<p><b>示例 2：</b></p>
<img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/11/25/searchgrid.jpg" />
<pre>
<b>输入：</b>matrix = [[1,4,7,11,15],[2,5,8,12,19],[3,6,9,16,22],[10,13,14,17,24],[18,21,23,26,30]], target = 20
<b>输出：</b>false
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>m == matrix.length</code></li>
	<li><code>n == matrix[i].length</code></li>
	<li><code>1 <= n, m <= 300</code></li>
	<li><code>-10<sup>9</sup> <= matix[i][j] <= 10<sup>9</sup></code></li>
	<li>每行的所有元素从左到右升序排列</li>
	<li>每列的所有元素从上到下升序排列</li>
	<li><code>-10<sup>9</sup> <= target <= 10<sup>9</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[分治](https://github.com/awesee/leetcode/tree/main/tag/divide-and-conquer/README.md)]
  [[矩阵](https://github.com/awesee/leetcode/tree/main/tag/matrix/README.md)]

### 相似题目
  1. [搜索二维矩阵](/problems/search-a-2d-matrix) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/search-a-2d-matrix-ii)
