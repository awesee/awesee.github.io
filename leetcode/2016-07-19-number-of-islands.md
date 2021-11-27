---
layout:     single
title:      "岛屿数量"
date:       2016-07-19 21:30:00 +0800
categories: [Leetcode]
tags:       [Depth-First Search, Breadth-First Search, Union Find, Array, Matrix]
permalink:  /problems/number-of-islands/
---

## 200. 岛屿数量 (Medium)

{% raw %}

<p>给你一个由 <code>'1'</code>（陆地）和 <code>'0'</code>（水）组成的的二维网格，请你计算网格中岛屿的数量。</p>

<p>岛屿总是被水包围，并且每座岛屿只能由水平方向和/或竖直方向上相邻的陆地连接形成。</p>

<p>此外，你可以假设该网格的四条边均被水包围。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>grid = [
  ["1","1","1","1","0"],
  ["1","1","0","1","0"],
  ["1","1","0","0","0"],
  ["0","0","0","0","0"]
]
<strong>输出：</strong>1
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>grid = [
  ["1","1","0","0","0"],
  ["1","1","0","0","0"],
  ["0","0","1","0","0"],
  ["0","0","0","1","1"]
]
<strong>输出：</strong>3
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>m == grid.length</code></li>
	<li><code>n == grid[i].length</code></li>
	<li><code>1 <= m, n <= 300</code></li>
	<li><code>grid[i][j]</code> 的值为 <code>'0'</code> 或 <code>'1'</code></li>
</ul>

{% endraw %}

### 相关话题
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/breadth-first-search/README.md)]
  [[并查集](https://github.com/awesee/leetcode/tree/main/tag/union-find/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[矩阵](https://github.com/awesee/leetcode/tree/main/tag/matrix/README.md)]

### 相似题目
  1. [被围绕的区域](/problems/surrounded-regions) (Medium)
  1. [墙与门](/problems/walls-and-gates) (Medium)
  1. [岛屿数量 II](/problems/number-of-islands-ii) (Hard)
  1. [无向图中连通分量的数目](/problems/number-of-connected-components-in-an-undirected-graph) (Medium)
  1. [不同岛屿的数量](/problems/number-of-distinct-islands) (Medium)
  1. [岛屿的最大面积](/problems/max-area-of-island) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/number-of-islands)
