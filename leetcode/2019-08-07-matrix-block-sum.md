---
layout:     single
title:      "矩阵区域和"
date:       2019-08-07 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Matrix, Prefix Sum]
permalink:  /problems/matrix-block-sum/
---

## 1314. 矩阵区域和 (Medium)

{% raw %}

<p>给你一个 <code>m x n</code> 的矩阵 <code>mat</code> 和一个整数 <code>k</code> ，请你返回一个矩阵 <code>answer</code> ，其中每个 <code>answer[i][j]</code> 是所有满足下述条件的元素 <code>mat[r][c]</code> 的和： </p>

<ul>
	<li><code>i - k <= r <= i + k, </code></li>
	<li><code>j - k <= c <= j + k</code> 且</li>
	<li><code>(r, c)</code> 在矩阵内。</li>
</ul>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>mat = [[1,2,3],[4,5,6],[7,8,9]], k = 1
<strong>输出：</strong>[[12,21,16],[27,45,33],[24,39,28]]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>mat = [[1,2,3],[4,5,6],[7,8,9]], k = 2
<strong>输出：</strong>[[45,45,45],[45,45,45],[45,45,45]]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>m == mat.length</code></li>
	<li><code>n == mat[i].length</code></li>
	<li><code>1 <= m, n, k <= 100</code></li>
	<li><code>1 <= mat[i][j] <= 100</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[矩阵](https://github.com/openset/leetcode/tree/master/tag/matrix/README.md)]
  [[前缀和](https://github.com/openset/leetcode/tree/master/tag/prefix-sum/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/matrix-block-sum)
