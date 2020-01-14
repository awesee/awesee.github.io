---
layout:     single
title:      "矩阵区域和"
date:       2019-08-07 21:30:00 +0800
categories: [Leetcode]
tags:       [Dynamic Programming]
permalink:  /problems/matrix-block-sum/
---

## 1314. 矩阵区域和 (Medium)

{% raw %}

<p>给你一个&nbsp;<code>m * n</code>&nbsp;的矩阵&nbsp;<code>mat</code>&nbsp;和一个整数&nbsp;<code>K</code> ，请你返回一个矩阵&nbsp;<code>answer</code>&nbsp;，其中每个&nbsp;<code>answer[i][j]</code>&nbsp;是所有满足下述条件的元素&nbsp;<code>mat[r][c]</code> 的和：&nbsp;</p>

<ul>
	<li><code>i - K &lt;= r &lt;= i + K, j - K &lt;= c &lt;= j + K</code>&nbsp;</li>
	<li><code>(r, c)</code>&nbsp;在矩阵内。</li>
</ul>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>mat = [[1,2,3],[4,5,6],[7,8,9]], K = 1
<strong>输出：</strong>[[12,21,16],[27,45,33],[24,39,28]]
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>mat = [[1,2,3],[4,5,6],[7,8,9]], K = 2
<strong>输出：</strong>[[45,45,45],[45,45,45],[45,45,45]]
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>m ==&nbsp;mat.length</code></li>
	<li><code>n ==&nbsp;mat[i].length</code></li>
	<li><code>1 &lt;= m, n, K &lt;= 100</code></li>
	<li><code>1 &lt;= mat[i][j] &lt;= 100</code></li>
</ul>

{% endraw %}

### 相关话题
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/matrix-block-sum)
