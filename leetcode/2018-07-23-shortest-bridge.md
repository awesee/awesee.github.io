---
layout:     single
title:      "最短的桥"
date:       2018-07-23 21:30:00 +0800
categories: [Leetcode]
tags:       [Depth-First Search, Breadth-First Search, Array, Matrix]
permalink:  /problems/shortest-bridge/
---

## 934. 最短的桥 (Medium)

{% raw %}

<p>在给定的二维二进制数组 <code>A</code> 中，存在两座岛。（岛是由四面相连的 <code>1</code> 形成的一个最大组。）</p>

<p>现在，我们可以将 <code>0</code> 变为 <code>1</code>，以使两座岛连接起来，变成一座岛。</p>

<p>返回必须翻转的 <code>0</code> 的最小数目。（可以保证答案至少是 <code>1</code> 。）</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>A = [[0,1],[1,0]]
<strong>输出：</strong>1
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>A = [[0,1,0],[0,0,0],[0,0,1]]
<strong>输出：</strong>2
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>A = [[1,1,1,1,1],[1,0,0,0,1],[1,0,1,0,1],[1,0,0,0,1],[1,1,1,1,1]]
<strong>输出：</strong>1</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>2 <= A.length == A[0].length <= 100</code></li>
	<li><code>A[i][j] == 0</code> 或 <code>A[i][j] == 1</code></li>
</ul>

{% endraw %}

### 相关话题
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/openset/leetcode/tree/master/tag/breadth-first-search/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[矩阵](https://github.com/openset/leetcode/tree/master/tag/matrix/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/shortest-bridge)
