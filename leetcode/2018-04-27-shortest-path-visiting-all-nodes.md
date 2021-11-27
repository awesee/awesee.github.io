---
layout:     single
title:      "访问所有节点的最短路径"
date:       2018-04-27 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Breadth-First Search, Graph, Dynamic Programming, Bitmask]
permalink:  /problems/shortest-path-visiting-all-nodes/
---

## 847. 访问所有节点的最短路径 (Hard)

{% raw %}

<p>给出&nbsp;<code>graph</code>&nbsp;为有 N 个节点（编号为&nbsp;<code>0, 1, 2, ..., N-1</code>）的无向连通图。&nbsp;</p>

<p><code>graph.length = N</code>，且只有节点 <code>i</code>&nbsp;和 <code>j</code>&nbsp;连通时，<code>j != i</code>&nbsp;在列表&nbsp;<code>graph[i]</code>&nbsp;中恰好出现一次。</p>

<p>返回能够访问所有节点的最短路径的长度。你可以在任一节点开始和停止，也可以多次重访节点，并且可以重用边。</p>

<p>&nbsp;</p>

<ol>
</ol>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>[[1,2,3],[0],[0],[0]]
<strong>输出：</strong>4
<strong>解释：</strong>一个可能的路径为 [1,0,2,0,3]</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>[[1],[0,2,4],[1,3,4],[2],[1,2]]
<strong>输出：</strong>4
<strong>解释：</strong>一个可能的路径为 [0,1,4,2,3]
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= graph.length &lt;= 12</code></li>
	<li><code>0 &lt;= graph[i].length &lt;&nbsp;graph.length</code></li>
</ol>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[广度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/breadth-first-search/README.md)]
  [[图](https://github.com/awesee/leetcode/tree/main/tag/graph/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[状态压缩](https://github.com/awesee/leetcode/tree/main/tag/bitmask/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/shortest-path-visiting-all-nodes)
