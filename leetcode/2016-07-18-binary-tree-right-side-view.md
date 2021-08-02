---
layout:     single
title:      "二叉树的右视图"
date:       2016-07-18 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Breadth-First Search, Binary Tree]
permalink:  /problems/binary-tree-right-side-view/
---

## 199. 二叉树的右视图 (Medium)

{% raw %}

<p>给定一个二叉树的 <strong>根节点</strong> <code>root</code>，想象自己站在它的右侧，按照从顶部到底部的顺序，返回从右侧所能看到的节点值。</p>

<p> </p>

<p><strong>示例 1:</strong></p>

<p><img src="https://assets.leetcode.com/uploads/2021/02/14/tree.jpg" style="width: 270px; " /></p>

<pre>
<strong>输入:</strong> [1,2,3,null,5,null,4]
<strong>输出:</strong> [1,3,4]
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> [1,null,3]
<strong>输出:</strong> [1,3]
</pre>

<p><strong>示例 3:</strong></p>

<pre>
<strong>输入:</strong> []
<strong>输出:</strong> []
</pre>

<p> </p>

<p><strong>提示:</strong></p>

<ul>
	<li>二叉树的节点个数的范围是 <code>[0,100]</code></li>
	<li><meta charset="UTF-8" /><code>-100 <= Node.val <= 100</code> </li>
</ul>

{% endraw %}

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/openset/leetcode/tree/master/tag/breadth-first-search/README.md)]
  [[二叉树](https://github.com/openset/leetcode/tree/master/tag/binary-tree/README.md)]

### 相似题目
  1. [填充每个节点的下一个右侧节点指针](/problems/populating-next-right-pointers-in-each-node) (Medium)
  1. [二叉树的边界](/problems/boundary-of-binary-tree) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/binary-tree-right-side-view)
