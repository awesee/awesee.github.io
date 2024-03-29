---
layout:     single
title:      "树中距离之和"
date:       2018-04-14 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Graph, Dynamic Programming]
permalink:  /problems/sum-of-distances-in-tree/
---

## 834. 树中距离之和 (Hard)

{% raw %}

<p>给定一个无向、连通的树。树中有 <code>N</code> 个标记为 <code>0...N-1</code> 的节点以及 <code>N-1</code>&nbsp;条边&nbsp;。</p>

<p>第 <code>i</code> 条边连接节点&nbsp;<code>edges[i][0]</code> 和 <code>edges[i][1]</code>&nbsp;。</p>

<p>返回一个表示节点 <code>i</code> 与其他所有节点距离之和的列表 <code>ans</code>。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入: </strong>N = 6, edges = [[0,1],[0,2],[2,3],[2,4],[2,5]]
<strong>输出: </strong>[8,12,6,10,10,10]
<strong>解释: </strong>
如下为给定的树的示意图：
  0
 / \
1   2
   /|\
  3 4 5

我们可以计算出 dist(0,1) + dist(0,2) + dist(0,3) + dist(0,4) + dist(0,5) 
也就是 1 + 1 + 2 + 2 + 2 = 8。 因此，answer[0] = 8，以此类推。
</pre>

<p><strong>说明:</strong>&nbsp;<code>1 &lt;= N &lt;= 10000</code></p>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[图](https://github.com/awesee/leetcode/tree/main/tag/graph/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

### 相似题目
  1. [在二叉树中分配硬币](/problems/distribute-coins-in-binary-tree) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/sum-of-distances-in-tree)
