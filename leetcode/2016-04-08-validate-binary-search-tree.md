---
layout:     single
title:      "验证二叉搜索树"
date:       2016-04-08 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Binary Search Tree, Binary Tree]
permalink:  /problems/validate-binary-search-tree/
---

## 98. 验证二叉搜索树 (Medium)

{% raw %}

<p>给定一个二叉树，判断其是否是一个有效的二叉搜索树。</p>

<p>假设一个二叉搜索树具有如下特征：</p>

<ul>
	<li>节点的左子树只包含<strong>小于</strong>当前节点的数。</li>
	<li>节点的右子树只包含<strong>大于</strong>当前节点的数。</li>
	<li>所有左子树和右子树自身必须也是二叉搜索树。</li>
</ul>

<p><strong>示例&nbsp;1:</strong></p>

<pre><strong>输入:</strong>
    2
   / \
  1   3
<strong>输出:</strong> true
</pre>

<p><strong>示例&nbsp;2:</strong></p>

<pre><strong>输入:
</strong>    5
   / \
  1   4
&nbsp;    / \
&nbsp;   3   6
<strong>输出:</strong> false
<strong>解释:</strong> 输入为: [5,1,4,null,null,3,6]。
&nbsp;    根节点的值为 5 ，但是其右子节点值为 4 。
</pre>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[二叉搜索树](https://github.com/awesee/leetcode/tree/main/tag/binary-search-tree/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

### 相似题目
  1. [二叉树的中序遍历](/problems/binary-tree-inorder-traversal) (Easy)
  1. [二叉搜索树中的众数](/problems/find-mode-in-binary-search-tree) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/validate-binary-search-tree)
