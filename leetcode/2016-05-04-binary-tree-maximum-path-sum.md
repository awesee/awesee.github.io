---
layout:     single
title:      "二叉树中的最大路径和"
date:       2016-05-04 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Dynamic Programming, Binary Tree]
permalink:  /problems/binary-tree-maximum-path-sum/
---

## 124. 二叉树中的最大路径和 (Hard)

{% raw %}

<p><strong>路径</strong> 被定义为一条从树中任意节点出发，沿父节点-子节点连接，达到任意节点的序列。同一个节点在一条路径序列中 <strong>至多出现一次</strong> 。该路径<strong> 至少包含一个 </strong>节点，且不一定经过根节点。</p>

<p><strong>路径和</strong> 是路径中各节点值的总和。</p>

<p>给你一个二叉树的根节点 <code>root</code> ，返回其 <strong>最大路径和</strong> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/10/13/exx1.jpg" style="width: 322px; height: 182px;" />
<pre>
<strong>输入：</strong>root = [1,2,3]
<strong>输出：</strong>6
<strong>解释：</strong>最优路径是 2 -> 1 -> 3 ，路径和为 2 + 1 + 3 = 6</pre>

<p><strong>示例 2：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/10/13/exx2.jpg" />
<pre>
<strong>输入：</strong>root = [-10,9,20,null,null,15,7]
<strong>输出：</strong>42
<strong>解释：</strong>最优路径是 15 -> 20 -> 7 ，路径和为 15 + 20 + 7 = 42
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>树中节点数目范围是 <code>[1, 3 * 10<sup>4</sup>]</code></li>
	<li><code>-1000 <= Node.val <= 1000</code></li>
</ul>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

### 相似题目
  1. [路径总和](/problems/path-sum) (Easy)
  1. [求根节点到叶节点数字之和](/problems/sum-root-to-leaf-numbers) (Medium)
  1. [路径总和 IV](/problems/path-sum-iv) (Medium)
  1. [最长同值路径](/problems/longest-univalue-path) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/binary-tree-maximum-path-sum)
