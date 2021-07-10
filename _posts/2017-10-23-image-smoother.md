---
layout:     single
title:      "图片平滑器"
date:       2017-10-23 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Matrix]
permalink:  /problems/image-smoother/
---

## 661. 图片平滑器 (Easy)

{% raw %}

<p>包含整数的二维矩阵 M 表示一个图片的灰度。你需要设计一个平滑器来让每一个单元的灰度成为平均灰度&nbsp;(向下舍入) ，平均灰度的计算是周围的8个单元和它本身的值求平均，如果周围的单元格不足八个，则尽可能多的利用它们。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong>
[[1,1,1],
 [1,0,1],
 [1,1,1]]
<strong>输出:</strong>
[[0, 0, 0],
 [0, 0, 0],
 [0, 0, 0]]
<strong>解释:</strong>
对于点 (0,0), (0,2), (2,0), (2,2): 平均(3/4) = 平均(0.75) = 0
对于点 (0,1), (1,0), (1,2), (2,1): 平均(5/6) = 平均(0.83333333) = 0
对于点 (1,1): 平均(8/9) = 平均(0.88888889) = 0
</pre>

<p><strong>注意:</strong></p>

<ol>
	<li>给定矩阵中的整数范围为 [0, 255]。</li>
	<li>矩阵的长和宽的范围均为&nbsp;[1, 150]。</li>
</ol>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[矩阵](https://github.com/openset/leetcode/tree/master/tag/matrix/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/image-smoother)
