---
layout:     single
title:      "二叉搜索树结点最小距离"
date:       2018-02-22 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Recursion]
permalink:  /minimum-distance-between-bst-nodes/
---

## 783. 二叉搜索树结点最小距离 (Easy)

<p>给定一个二叉搜索树的根结点&nbsp;<code>root</code>, 返回树中任意两节点的差的最小值。</p>

<p><strong>示例：</strong></p>

<pre>
<strong>输入:</strong> root = [4,2,6,1,3,null,null]
<strong>输出:</strong> 1
<strong>解释:</strong>
注意，root是树结点对象(TreeNode object)，而不是数组。

给定的树 [4,2,6,1,3,null,null] 可表示为下图:

          4
        /   \
      2      6
     / \    
    1   3  

最小的差值是 1, 它是节点1和节点2的差值, 也是节点3和节点2的差值。</pre>

<p><strong>注意：</strong></p>

<ol>
	<li>二叉树的大小范围在 <code>2</code> 到&nbsp;<code>100</code>。</li>
	<li>二叉树总是有效的，每个节点的值都是整数，且不重复。</li>
</ol>

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[递归](https://github.com/openset/leetcode/tree/master/tag/recursion/README.md)]

### 相似题目
  1. [二叉树的中序遍历](/binary-tree-inorder-traversal) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/minimum-distance-between-bst-nodes)
