---
layout:     single
title:      "从前序与中序遍历序列构造二叉树"
date:       2016-04-15 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Array, Hash Table, Divide and Conquer, Binary Tree]
permalink:  /problems/construct-binary-tree-from-preorder-and-inorder-traversal/
---

## 105. 从前序与中序遍历序列构造二叉树 (Medium)

{% raw %}

<p>给定一棵树的前序遍历 <code>preorder</code> 与中序遍历  <code>inorder</code>。请构造二叉树并返回其根节点。</p>

<p> </p>

<p><strong>示例 1:</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2021/02/19/tree.jpg" />
<pre>
<strong>Input:</strong> preorder = [3,9,20,15,7], inorder = [9,3,15,20,7]
<strong>Output:</strong> [3,9,20,null,null,15,7]
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>Input:</strong> preorder = [-1], inorder = [-1]
<strong>Output:</strong> [-1]
</pre>

<p> </p>

<p><strong>提示:</strong></p>

<ul>
	<li><code>1 <= preorder.length <= 3000</code></li>
	<li><code>inorder.length == preorder.length</code></li>
	<li><code>-3000 <= preorder[i], inorder[i] <= 3000</code></li>
	<li><code>preorder</code> 和 <code>inorder</code> 均无重复元素</li>
	<li><code>inorder</code> 均出现在 <code>preorder</code></li>
	<li><code>preorder</code> 保证为二叉树的前序遍历序列</li>
	<li><code>inorder</code> 保证为二叉树的中序遍历序列</li>
</ul>

{% endraw %}

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[分治](https://github.com/openset/leetcode/tree/master/tag/divide-and-conquer/README.md)]
  [[二叉树](https://github.com/openset/leetcode/tree/master/tag/binary-tree/README.md)]

### 相似题目
  1. [从中序与后序遍历序列构造二叉树](/problems/construct-binary-tree-from-inorder-and-postorder-traversal) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/construct-binary-tree-from-preorder-and-inorder-traversal)
