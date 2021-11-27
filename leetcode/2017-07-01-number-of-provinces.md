---
layout:     single
title:      "省份数量"
date:       2017-07-01 21:30:00 +0800
categories: [Leetcode]
tags:       [Depth-First Search, Breadth-First Search, Union Find, Graph]
permalink:  /problems/number-of-provinces/
---

## 547. 省份数量 (Medium)

{% raw %}

<div class="original__bRMd">
<div>
<p>有 <code>n</code> 个城市，其中一些彼此相连，另一些没有相连。如果城市 <code>a</code> 与城市 <code>b</code> 直接相连，且城市 <code>b</code> 与城市 <code>c</code> 直接相连，那么城市 <code>a</code> 与城市 <code>c</code> 间接相连。</p>

<p><strong>省份</strong> 是一组直接或间接相连的城市，组内不含其他没有相连的城市。</p>

<p>给你一个 <code>n x n</code> 的矩阵 <code>isConnected</code> ，其中 <code>isConnected[i][j] = 1</code> 表示第 <code>i</code> 个城市和第 <code>j</code> 个城市直接相连，而 <code>isConnected[i][j] = 0</code> 表示二者不直接相连。</p>

<p>返回矩阵中 <strong>省份</strong> 的数量。</p>

<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/12/24/graph1.jpg" style="width: 222px; height: 142px;" />
<pre>
<strong>输入：</strong>isConnected = [[1,1,0],[1,1,0],[0,0,1]]
<strong>输出：</strong>2
</pre>

<p><strong>示例 2：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/12/24/graph2.jpg" style="width: 222px; height: 142px;" />
<pre>
<strong>输入：</strong>isConnected = [[1,0,0],[0,1,0],[0,0,1]]
<strong>输出：</strong>3
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= n <= 200</code></li>
	<li><code>n == isConnected.length</code></li>
	<li><code>n == isConnected[i].length</code></li>
	<li><code>isConnected[i][j]</code> 为 <code>1</code> 或 <code>0</code></li>
	<li><code>isConnected[i][i] == 1</code></li>
	<li><code>isConnected[i][j] == isConnected[j][i]</code></li>
</ul>
</div>
</div>

{% endraw %}

### 相关话题
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/awesee/leetcode/tree/master/tag/breadth-first-search/README.md)]
  [[并查集](https://github.com/awesee/leetcode/tree/master/tag/union-find/README.md)]
  [[图](https://github.com/awesee/leetcode/tree/master/tag/graph/README.md)]

### 相似题目
  1. [无向图中连通分量的数目](/problems/number-of-connected-components-in-an-undirected-graph) (Medium)
  1. [机器人能否返回原点](/problems/robot-return-to-origin) (Easy)
  1. [句子相似性](/problems/sentence-similarity) (Easy)
  1. [句子相似性 II](/problems/sentence-similarity-ii) (Medium)
  1. [彼此熟识的最早时间](/problems/the-earliest-moment-when-everyone-become-friends) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/number-of-provinces)
