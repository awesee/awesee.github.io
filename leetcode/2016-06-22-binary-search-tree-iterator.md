---
layout:     single
title:      "二叉搜索树迭代器"
date:       2016-06-22 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Tree, Design]
permalink:  /problems/binary-search-tree-iterator/
---

## 173. 二叉搜索树迭代器 (Medium)

{% raw %}

<p>实现一个二叉搜索树迭代器。你将使用二叉搜索树的根节点初始化迭代器。</p>

<p>调用 <code>next()</code> 将返回二叉搜索树中的下一个最小的数。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<p><strong><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2018/12/25/bst-tree.png" style="height: 178px; width: 189px;"></strong></p>

<pre>BSTIterator iterator = new BSTIterator(root);
iterator.next();    // 返回 3
iterator.next();    // 返回 7
iterator.hasNext(); // 返回 true
iterator.next();    // 返回 9
iterator.hasNext(); // 返回 true
iterator.next();    // 返回 15
iterator.hasNext(); // 返回 true
iterator.next();    // 返回 20
iterator.hasNext(); // 返回 false</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>next()</code>&nbsp;和&nbsp;<code>hasNext()</code>&nbsp;操作的时间复杂度是&nbsp;O(1)，并使用&nbsp;O(<em>h</em>) 内存，其中&nbsp;<em>h&nbsp;</em>是树的高度。</li>
	<li>你可以假设&nbsp;<code>next()</code>&nbsp;调用总是有效的，也就是说，当调用 <code>next()</code>&nbsp;时，BST 中至少存在一个下一个最小的数。</li>
</ul>

{% endraw %}

### 相关话题
  [[栈](https://github.com/openset/leetcode/tree/master/tag/stack/README.md)]
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[设计](https://github.com/openset/leetcode/tree/master/tag/design/README.md)]

### 相似题目
  1. [二叉树的中序遍历](/problems/binary-tree-inorder-traversal) (Medium)
  1. [展开二维向量](/problems/flatten-2d-vector) (Medium)
  1. [锯齿迭代器](/problems/zigzag-iterator) (Medium)
  1. [顶端迭代器](/problems/peeking-iterator) (Medium)
  1. [二叉搜索树中的顺序后继](/problems/inorder-successor-in-bst) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/binary-search-tree-iterator)
