---
layout:     single
title:      "叶子相似的树"
date:       2018-05-22 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Binary Tree]
permalink:  /problems/leaf-similar-trees/
---

## 872. 叶子相似的树 (Easy)

{% raw %}

<p>请考虑一棵二叉树上所有的叶子，这些叶子的值按从左到右的顺序排列形成一个 <strong>叶值序列 </strong>。</p>

<p><img alt="" src="https://s3-lc-upload.s3.amazonaws.com/uploads/2018/07/16/tree.png" style="height: 240px; width: 300px;" /></p>

<p>举个例子，如上图所示，给定一棵叶值序列为 <code>(6, 7, 4, 9, 8)</code> 的树。</p>

<p>如果有两棵二叉树的叶值序列是相同，那么我们就认为它们是 <em>叶相似 </em>的。</p>

<p>如果给定的两个根结点分别为 <code>root1</code> 和 <code>root2</code> 的树是叶相似的，则返回 <code>true</code>；否则返回 <code>false</code> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<p><img alt="" src="https://assets.leetcode.com/uploads/2020/09/03/leaf-similar-1.jpg" style="height: 297px; width: 750px;" /></p>

<pre>
<strong>输入：</strong>root1 = [3,5,1,6,2,9,8,null,null,7,4], root2 = [3,5,1,6,7,4,2,null,null,null,null,null,null,9,8]
<strong>输出：</strong>true
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>root1 = [1], root2 = [1]
<strong>输出：</strong>true
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>root1 = [1], root2 = [2]
<strong>输出：</strong>false
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>root1 = [1,2], root2 = [2,2]
<strong>输出：</strong>true
</pre>

<p><strong>示例 5：</strong></p>

<p><img alt="" src="https://assets.leetcode.com/uploads/2020/09/03/leaf-similar-2.jpg" style="height: 165px; width: 450px;" /></p>

<pre>
<strong>输入：</strong>root1 = [1,2,3], root2 = [1,3,2]
<strong>输出：</strong>false
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>给定的两棵树可能会有 <code>1</code> 到 <code>200</code> 个结点。</li>
	<li>给定的两棵树上的值介于 <code>0</code> 到 <code>200</code> 之间。</li>
</ul>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/master/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/master/tag/binary-tree/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/leaf-similar-trees)
