---
layout:     single
title:      "二叉搜索树迭代器"
date:       2016-06-22 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Tree, Design, Binary Search Tree, Binary Tree, Iterator]
permalink:  /problems/binary-search-tree-iterator/
---

## 173. 二叉搜索树迭代器 (Medium)

{% raw %}

实现一个二叉搜索树迭代器类<code>BSTIterator</code> ，表示一个按中序遍历二叉搜索树（BST）的迭代器：
<div class="original__bRMd">
<div>
<ul>
	<li><code>BSTIterator(TreeNode root)</code> 初始化 <code>BSTIterator</code> 类的一个对象。BST 的根节点 <code>root</code> 会作为构造函数的一部分给出。指针应初始化为一个不存在于 BST 中的数字，且该数字小于 BST 中的任何元素。</li>
	<li><code>boolean hasNext()</code> 如果向指针右侧遍历存在数字，则返回 <code>true</code> ；否则返回 <code>false</code> 。</li>
	<li><code>int next()</code>将指针向右移动，然后返回指针处的数字。</li>
</ul>

<p>注意，指针初始化为一个不存在于 BST 中的数字，所以对 <code>next()</code> 的首次调用将返回 BST 中的最小元素。</p>
</div>
</div>

<p>你可以假设 <code>next()</code> 调用总是有效的，也就是说，当调用 <code>next()</code> 时，BST 的中序遍历中至少存在一个下一个数字。</p>

<p> </p>

<p><strong>示例：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2018/12/25/bst-tree.png" style="width: 189px; height: 178px;" />
<pre>
<strong>输入</strong>
["BSTIterator", "next", "next", "hasNext", "next", "hasNext", "next", "hasNext", "next", "hasNext"]
[[[7, 3, 15, null, null, 9, 20]], [], [], [], [], [], [], [], [], []]
<strong>输出</strong>
[null, 3, 7, true, 9, true, 15, true, 20, false]

<strong>解释</strong>
BSTIterator bSTIterator = new BSTIterator([7, 3, 15, null, null, 9, 20]);
bSTIterator.next();    // 返回 3
bSTIterator.next();    // 返回 7
bSTIterator.hasNext(); // 返回 True
bSTIterator.next();    // 返回 9
bSTIterator.hasNext(); // 返回 True
bSTIterator.next();    // 返回 15
bSTIterator.hasNext(); // 返回 True
bSTIterator.next();    // 返回 20
bSTIterator.hasNext(); // 返回 False
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>树中节点的数目在范围 <code>[1, 10<sup>5</sup>]</code> 内</li>
	<li><code>0 <= Node.val <= 10<sup>6</sup></code></li>
	<li>最多调用 <code>10<sup>5</sup></code> 次 <code>hasNext</code> 和 <code>next</code> 操作</li>
</ul>

<p> </p>

<p><strong>进阶：</strong></p>

<ul>
	<li>你可以设计一个满足下述条件的解决方案吗？<code>next()</code> 和 <code>hasNext()</code> 操作均摊时间复杂度为 <code>O(1)</code> ，并使用 <code>O(h)</code> 内存。其中 <code>h</code> 是树的高度。</li>
</ul>

{% endraw %}

### 相关话题
  [[栈](https://github.com/openset/leetcode/tree/master/tag/stack/README.md)]
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[设计](https://github.com/openset/leetcode/tree/master/tag/design/README.md)]
  [[二叉搜索树](https://github.com/openset/leetcode/tree/master/tag/binary-search-tree/README.md)]
  [[二叉树](https://github.com/openset/leetcode/tree/master/tag/binary-tree/README.md)]
  [[迭代器](https://github.com/openset/leetcode/tree/master/tag/iterator/README.md)]

### 相似题目
  1. [二叉树的中序遍历](/problems/binary-tree-inorder-traversal) (Easy)
  1. [展开二维向量](/problems/flatten-2d-vector) (Medium)
  1. [锯齿迭代器](/problems/zigzag-iterator) (Medium)
  1. [顶端迭代器](/problems/peeking-iterator) (Medium)
  1. [二叉搜索树中的中序后继](/problems/inorder-successor-in-bst) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/binary-search-tree-iterator)
