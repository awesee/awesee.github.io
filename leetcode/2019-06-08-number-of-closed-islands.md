---
layout:     single
title:      "统计封闭岛屿的数目"
date:       2019-06-08 21:30:00 +0800
categories: [Leetcode]
tags:       [Depth-First Search, Breadth-First Search, Union Find, Array, Matrix]
permalink:  /problems/number-of-closed-islands/
---

## 1254. 统计封闭岛屿的数目 (Medium)

{% raw %}

<p>有一个二维矩阵 <code>grid</code>&nbsp;，每个位置要么是陆地（记号为&nbsp;<code>0</code> ）要么是水域（记号为&nbsp;<code>1</code> ）。</p>

<p>我们从一块陆地出发，每次可以往上下左右&nbsp;4 个方向相邻区域走，能走到的所有陆地区域，我们将其称为一座「<strong>岛屿</strong>」。</p>

<p>如果一座岛屿&nbsp;<strong>完全</strong>&nbsp;由水域包围，即陆地边缘上下左右所有相邻区域都是水域，那么我们将其称为 「<strong>封闭岛屿</strong>」。</p>

<p>请返回封闭岛屿的数目。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<p><img src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/11/07/sample_3_1610.png"></p>

<pre><strong>输入：</strong>grid = [[1,1,1,1,1,1,1,0],[1,0,0,0,0,1,1,0],[1,0,1,0,1,1,1,0],[1,0,0,0,0,1,0,1],[1,1,1,1,1,1,1,0]]
<strong>输出：</strong>2
<strong>解释：</strong>
灰色区域的岛屿是封闭岛屿，因为这座岛屿完全被水域包围（即被 1 区域包围）。</pre>

<p><strong>示例 2：</strong></p>

<p><img src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/11/07/sample_4_1610.png"></p>

<pre><strong>输入：</strong>grid = [[0,0,1,0,0],[0,1,0,1,0],[0,1,1,1,0]]
<strong>输出：</strong>1
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>grid = [[1,1,1,1,1,1,1],
&nbsp;            [1,0,0,0,0,0,1],
&nbsp;            [1,0,1,1,1,0,1],
&nbsp;            [1,0,1,0,1,0,1],
&nbsp;            [1,0,1,1,1,0,1],
&nbsp;            [1,0,0,0,0,0,1],
             [1,1,1,1,1,1,1]]
<strong>输出：</strong>2
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= grid.length, grid[0].length &lt;= 100</code></li>
	<li><code>0 &lt;= grid[i][j] &lt;=1</code></li>
</ul>

{% endraw %}

### 相关话题
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/breadth-first-search/README.md)]
  [[并查集](https://github.com/awesee/leetcode/tree/main/tag/union-find/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[矩阵](https://github.com/awesee/leetcode/tree/main/tag/matrix/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/number-of-closed-islands)
