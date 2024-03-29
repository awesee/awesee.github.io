---
layout:     single
title:      "修剪二叉搜索树"
date:       2017-10-31 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Binary Search Tree, Binary Tree]
permalink:  /problems/trim-a-binary-search-tree/
---

## 669. 修剪二叉搜索树 (Medium)

{% raw %}

<p>给你二叉搜索树的根节点 <code>root</code> ，同时给定最小边界<code>low</code> 和最大边界 <code>high</code>。通过修剪二叉搜索树，使得所有节点的值在<code>[low, high]</code>中。修剪树不应该改变保留在树中的元素的相对结构（即，如果没有被移除，原有的父代子代关系都应当保留）。 可以证明，存在唯一的答案。</p>

<p>所以结果应当返回修剪好的二叉搜索树的新的根节点。注意，根节点可能会根据给定的边界发生改变。</p>

<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/09/09/trim1.jpg" style="width: 450px; height: 126px;" />
<pre>
<strong>输入：</strong>root = [1,0,2], low = 1, high = 2
<strong>输出：</strong>[1,null,2]
</pre>

<p><strong>示例 2：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/09/09/trim2.jpg" style="width: 450px; height: 277px;" />
<pre>
<strong>输入：</strong>root = [3,0,4,null,2,null,null,1], low = 1, high = 3
<strong>输出：</strong>[3,2,null,1]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>root = [1], low = 1, high = 2
<strong>输出：</strong>[1]
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>root = [1,null,2], low = 1, high = 3
<strong>输出：</strong>[1,null,2]
</pre>

<p><strong>示例 5：</strong></p>

<pre>
<strong>输入：</strong>root = [1,null,2], low = 2, high = 4
<strong>输出：</strong>[2]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>树中节点数在范围 <code>[1, 10<sup>4</sup>]</code> 内</li>
	<li><code>0 <= Node.val <= 10<sup>4</sup></code></li>
	<li>树中每个节点的值都是唯一的</li>
	<li>题目数据保证输入是一棵有效的二叉搜索树</li>
	<li><code>0 <= low <= high <= 10<sup>4</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[二叉搜索树](https://github.com/awesee/leetcode/tree/main/tag/binary-search-tree/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/trim-a-binary-search-tree)
