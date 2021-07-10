---
layout:     single
title:      "二叉搜索树节点最小距离"
date:       2018-02-22 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Breadth-First Search, Binary Search Tree, Binary Tree]
permalink:  /problems/minimum-distance-between-bst-nodes/
---

## 783. 二叉搜索树节点最小距离 (Easy)

{% raw %}

<p>给你一个二叉搜索树的根节点 <code>root</code> ，返回 <strong>树中任意两不同节点值之间的最小差值</strong> 。</p>

<p><strong>注意：</strong>本题与 530：<a href="https://leetcode-cn.com/problems/minimum-absolute-difference-in-bst/">https://leetcode-cn.com/problems/minimum-absolute-difference-in-bst/</a> 相同</p>

<p> </p>

<div class="original__bRMd">
<div>
<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2021/02/05/bst1.jpg" style="width: 292px; height: 301px;" />
<pre>
<strong>输入：</strong>root = [4,2,6,1,3]
<strong>输出：</strong>1
</pre>

<p><strong>示例 2：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2021/02/05/bst2.jpg" style="width: 282px; height: 301px;" />
<pre>
<strong>输入：</strong>root = [1,0,48,null,null,12,49]
<strong>输出：</strong>1
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>树中节点数目在范围 <code>[2, 100]</code> 内</li>
	<li><code>0 <= Node.val <= 10<sup>5</sup></code></li>
	<li>差值是一个正数，其数值等于两值之差的绝对值</li>
</ul>
</div>
</div>

{% endraw %}

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/openset/leetcode/tree/master/tag/breadth-first-search/README.md)]
  [[二叉搜索树](https://github.com/openset/leetcode/tree/master/tag/binary-search-tree/README.md)]
  [[二叉树](https://github.com/openset/leetcode/tree/master/tag/binary-tree/README.md)]

### 相似题目
  1. [二叉树的中序遍历](/problems/binary-tree-inorder-traversal) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/minimum-distance-between-bst-nodes)
