---
layout:     single
title:      "二维区域和检索 - 矩阵不可变"
date:       2016-10-31 21:30:00 +0800
categories: [leetcode]
tags:       [dynamic-programming]
permalink:  /range-sum-query-2d-immutable/
---

## 304. 二维区域和检索 - 矩阵不可变 (Medium)

<p>给定一个二维矩阵，计算其子矩形范围内元素的总和，该子矩阵的左上角为 (<em>row</em>1,&nbsp;<em>col</em>1) ，右下角为 (<em>row</em>2,&nbsp;<em>col</em>2)。</p>

<p><img alt="Range Sum Query 2D" src="/static/images/courses/range_sum_query_2d.png"><br>
<small>上图子矩阵左上角&nbsp;(row1, col1) = <strong>(2, 1)</strong>&nbsp;，右下角(row2, col2) = <strong>(4, 3)，</strong>该子矩形内元素的总和为 8。</small></p>

<p><strong>示例:</strong></p>

<pre>给定 matrix = [
  [3, 0, 1, 4, 2],
  [5, 6, 3, 2, 1],
  [1, 2, 0, 1, 5],
  [4, 1, 0, 1, 7],
  [1, 0, 3, 0, 5]
]

sumRegion(2, 1, 4, 3) -&gt; 8
sumRegion(1, 1, 2, 2) -&gt; 11
sumRegion(1, 2, 2, 4) -&gt; 12
</pre>

<p><strong>说明:</strong></p>

<ol>
	<li>你可以假设矩阵不可变。</li>
	<li>会多次调用&nbsp;<em>sumRegion&nbsp;</em>方法<em>。</em></li>
	<li>你可以假设&nbsp;<em>row</em>1 &le; <em>row</em>2 且&nbsp;<em>col</em>1 &le; <em>col</em>2。</li>
</ol>

### 相关话题
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### 相似题目
  1. [区域和检索 - 数组不可变](/range-sum-query-immutable) (Easy)
  1. [Range Sum Query 2D - Mutable](/range-sum-query-2d-mutable) (Hard)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/range-sum-query-2d-immutable)
