---
layout:     single
title:      "矩阵中的幻方"
date:       2018-04-20 21:30:00 +0800
categories: [leetcode]
tags:       [array]
permalink:  /magic-squares-in-grid/
---

## 840. 矩阵中的幻方 (Easy)

<p>3 x 3 的幻方是一个填充有<strong>从 1 到 9</strong> 的不同数字的 3 x 3 矩阵，其中每行，每列以及两条对角线上的各数之和都相等。</p>

<p>给定一个由整数组成的 N &times; N 矩阵，其中有多少个 3 &times; 3 的 &ldquo;幻方&rdquo; 子矩阵？（每个子矩阵都是连续的）。</p>

<p>&nbsp;</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入: </strong>[[4,3,8,4],
      [9,5,1,9],
      [2,7,6,2]]
<strong>输出: </strong>1
<strong>解释: </strong>
下面的子矩阵是一个 3 x 3 的幻方：
438
951
276

而这一个不是：
384
519
762

总的来说，在本示例所给定的矩阵中只有一个 3 x 3 的幻方子矩阵。
</pre>

<p><strong>提示:</strong></p>

<ol>
	<li><code>1 &lt;= grid.length = grid[0].length&nbsp;&lt;= 10</code></li>
	<li><code>0 &lt;= grid[i][j] &lt;= 15</code></li>
</ol>

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/magic-squares-in-grid)