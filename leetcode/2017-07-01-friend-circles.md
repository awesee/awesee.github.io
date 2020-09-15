---
layout:     single
title:      "朋友圈"
date:       2017-07-01 21:30:00 +0800
categories: [Leetcode]
tags:       [Depth-first Search, Union Find]
permalink:  /problems/friend-circles/
---

## 547. 朋友圈 (Medium)

{% raw %}

<p>班上有&nbsp;<strong>N&nbsp;</strong>名学生。其中有些人是朋友，有些则不是。他们的友谊具有是传递性。如果已知 A 是 B&nbsp;的朋友，B 是 C&nbsp;的朋友，那么我们可以认为 A 也是 C&nbsp;的朋友。所谓的朋友圈，是指所有朋友的集合。</p>

<p>给定一个&nbsp;<strong>N * N&nbsp;</strong>的矩阵&nbsp;<strong>M</strong>，表示班级中学生之间的朋友关系。如果M[i][j] = 1，表示已知第 i 个和 j 个学生<strong>互为</strong>朋友关系，否则为不知道。你必须输出所有学生中的已知的朋友圈总数。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>
[[1,1,0],
 [1,1,0],
 [0,0,1]]
<strong>输出：</strong>2 
<strong>解释：</strong>已知学生 0 和学生 1 互为朋友，他们在一个朋友圈。
第2个学生自己在一个朋友圈。所以返回 2 。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>
[[1,1,0],
 [1,1,1],
 [0,1,1]]
<strong>输出：</strong>1
<strong>解释：</strong>已知学生 0 和学生 1 互为朋友，学生 1 和学生 2 互为朋友，所以学生 0 和学生 2 也是朋友，所以他们三个在一个朋友圈，返回 1 。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= N &lt;= 200</code></li>
	<li><code>M[i][i] == 1</code></li>
	<li><code>M[i][j] == M[j][i]</code></li>
</ul>

{% endraw %}

### 相关话题
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[并查集](https://github.com/openset/leetcode/tree/master/tag/union-find/README.md)]

### 相似题目
  1. [无向图中连通分量的数目](/problems/number-of-connected-components-in-an-undirected-graph) (Medium)
  1. [机器人能否返回原点](/problems/robot-return-to-origin) (Easy)
  1. [句子相似性](/problems/sentence-similarity) (Easy)
  1. [句子相似性 II](/problems/sentence-similarity-ii) (Medium)
  1. [彼此熟识的最早时间](/problems/the-earliest-moment-when-everyone-become-friends) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/friend-circles)
