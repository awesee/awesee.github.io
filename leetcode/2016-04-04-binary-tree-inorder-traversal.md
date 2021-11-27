---
layout:     single
title:      "二叉树的中序遍历"
date:       2016-04-04 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Tree, Depth-First Search, Binary Tree]
permalink:  /problems/binary-tree-inorder-traversal/
---

## 94. 二叉树的中序遍历 (Easy)

{% raw %}

<p>给定一个二叉树的根节点 <code>root</code> ，返回它的 <strong>中序</strong> 遍历。</p>

<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/09/15/inorder_1.jpg" style="width: 202px; height: 324px;" />
<pre>
<strong>输入：</strong>root = [1,null,2,3]
<strong>输出：</strong>[1,3,2]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>root = []
<strong>输出：</strong>[]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>root = [1]
<strong>输出：</strong>[1]
</pre>

<p><strong>示例 4：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/09/15/inorder_5.jpg" style="width: 202px; height: 202px;" />
<pre>
<strong>输入：</strong>root = [1,2]
<strong>输出：</strong>[2,1]
</pre>

<p><strong>示例 5：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/09/15/inorder_4.jpg" style="width: 202px; height: 202px;" />
<pre>
<strong>输入：</strong>root = [1,null,2]
<strong>输出：</strong>[1,2]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>树中节点数目在范围 <code>[0, 100]</code> 内</li>
	<li><code>-100 <= Node.val <= 100</code></li>
</ul>

<p> </p>

<p><strong>进阶:</strong> 递归算法很简单，你可以通过迭代算法完成吗？</p>

{% endraw %}

### 相关话题
  [[栈](https://github.com/awesee/leetcode/tree/main/tag/stack/README.md)]
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

### 相似题目
  1. [验证二叉搜索树](/problems/validate-binary-search-tree) (Medium)
  1. [二叉树的前序遍历](/problems/binary-tree-preorder-traversal) (Easy)
  1. [二叉树的后序遍历](/problems/binary-tree-postorder-traversal) (Easy)
  1. [二叉搜索树迭代器](/problems/binary-search-tree-iterator) (Medium)
  1. [二叉搜索树中第K小的元素](/problems/kth-smallest-element-in-a-bst) (Medium)
  1. [最接近的二叉搜索树值 II](/problems/closest-binary-search-tree-value-ii) (Hard)
  1. [二叉搜索树中的中序后继](/problems/inorder-successor-in-bst) (Medium)
  1. [将二叉搜索树转化为排序的双向链表](/problems/convert-binary-search-tree-to-sorted-doubly-linked-list) (Medium)
  1. [二叉搜索树节点最小距离](/problems/minimum-distance-between-bst-nodes) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/binary-tree-inorder-traversal)
