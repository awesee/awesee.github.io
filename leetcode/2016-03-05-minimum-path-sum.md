---
layout:     single
title:      "最小路径和"
date:       2016-03-05 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Dynamic Programming, Matrix]
permalink:  /problems/minimum-path-sum/
---

## 64. 最小路径和 (Medium)

{% raw %}

<p>给定一个包含非负整数的 <code><em>m</em> x <em>n</em></code> 网格 <code>grid</code> ，请找出一条从左上角到右下角的路径，使得路径上的数字总和为最小。</p>

<p><strong>说明：</strong>每次只能向下或者向右移动一步。</p>

<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/11/05/minpath.jpg" style="width: 242px; height: 242px;" />
<pre>
<strong>输入：</strong>grid = [[1,3,1],[1,5,1],[4,2,1]]
<strong>输出：</strong>7
<strong>解释：</strong>因为路径 1→3→1→1→1 的总和最小。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>grid = [[1,2,3],[4,5,6]]
<strong>输出：</strong>12
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>m == grid.length</code></li>
	<li><code>n == grid[i].length</code></li>
	<li><code>1 <= m, n <= 200</code></li>
	<li><code>0 <= grid[i][j] <= 100</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]
  [[矩阵](https://github.com/openset/leetcode/tree/master/tag/matrix/README.md)]

### 相似题目
  1. [不同路径](/problems/unique-paths) (Medium)
  1. [地下城游戏](/problems/dungeon-game) (Hard)
  1. [摘樱桃](/problems/cherry-pickup) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/minimum-path-sum)
