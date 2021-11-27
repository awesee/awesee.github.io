---
layout:     single
title:      "有序链表转换二叉搜索树"
date:       2016-04-19 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Binary Search Tree, Linked List, Divide and Conquer, Binary Tree]
permalink:  /problems/convert-sorted-list-to-binary-search-tree/
---

## 109. 有序链表转换二叉搜索树 (Medium)

{% raw %}

<p>给定一个单链表，其中的元素按升序排序，将其转换为高度平衡的二叉搜索树。</p>

<p>本题中，一个高度平衡二叉树是指一个二叉树<em>每个节点&nbsp;</em>的左右两个子树的高度差的绝对值不超过 1。</p>

<p><strong>示例:</strong></p>

<pre>给定的有序链表： [-10, -3, 0, 5, 9],

一个可能的答案是：[0, -3, 9, -10, null, 5], 它可以表示下面这个高度平衡二叉搜索树：

      0
     / \
   -3   9
   /   /
 -10  5
</pre>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[二叉搜索树](https://github.com/awesee/leetcode/tree/main/tag/binary-search-tree/README.md)]
  [[链表](https://github.com/awesee/leetcode/tree/main/tag/linked-list/README.md)]
  [[分治](https://github.com/awesee/leetcode/tree/main/tag/divide-and-conquer/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

### 相似题目
  1. [将有序数组转换为二叉搜索树](/problems/convert-sorted-array-to-binary-search-tree) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/convert-sorted-list-to-binary-search-tree)
