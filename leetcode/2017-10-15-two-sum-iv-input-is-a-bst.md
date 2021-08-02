---
layout:     single
title:      "两数之和 IV - 输入 BST"
date:       2017-10-15 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Breadth-First Search, Binary Search Tree, Hash Table, Two Pointers, Binary Tree]
permalink:  /problems/two-sum-iv-input-is-a-bst/
---

## 653. 两数之和 IV - 输入 BST (Easy)

{% raw %}

<p>给定一个二叉搜索树 <code>root</code> 和一个目标结果 <code>k</code>，如果 BST 中存在两个元素且它们的和等于给定的目标结果，则返回 <code>true</code>。</p>

<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/09/21/sum_tree_1.jpg" />
<pre>
<strong>输入:</strong> root = [5,3,6,2,4,null,7], k = 9
<strong>输出:</strong> true
</pre>

<p><strong>示例 2：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/09/21/sum_tree_2.jpg" />
<pre>
<strong>输入:</strong> root = [5,3,6,2,4,null,7], k = 28
<strong>输出:</strong> false
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入:</strong> root = [2,1,3], k = 4
<strong>输出:</strong> true
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入:</strong> root = [2,1,3], k = 1
<strong>输出:</strong> false
</pre>

<p><strong>示例 5：</strong></p>

<pre>
<strong>输入:</strong> root = [2,1,3], k = 3
<strong>输出:</strong> true
</pre>

<p> </p>

<p><strong>提示:</strong></p>

<ul>
	<li>二叉树的节点个数的范围是  <code>[1, 10<sup>4</sup>]</code>.</li>
	<li><code>-10<sup>4</sup> <= Node.val <= 10<sup>4</sup></code></li>
	<li><code>root</code> 为二叉搜索树</li>
	<li><code>-10<sup>5</sup> <= k <= 10<sup>5</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/openset/leetcode/tree/master/tag/breadth-first-search/README.md)]
  [[二叉搜索树](https://github.com/openset/leetcode/tree/master/tag/binary-search-tree/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[双指针](https://github.com/openset/leetcode/tree/master/tag/two-pointers/README.md)]
  [[二叉树](https://github.com/openset/leetcode/tree/master/tag/binary-tree/README.md)]

### 相似题目
  1. [两数之和](/problems/two-sum) (Easy)
  1. [两数之和 II - 输入有序数组](/problems/two-sum-ii-input-array-is-sorted) (Easy)
  1. [两数之和 III - 数据结构设计](/problems/two-sum-iii-data-structure-design) (Easy)
  1. [查找两棵二叉搜索树之和](/problems/two-sum-bsts) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/two-sum-iv-input-is-a-bst)
