---
layout:     single
title:      "二叉树中的最长交错路径"
date:       2019-10-04 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Dynamic Programming, Binary Tree]
permalink:  /problems/longest-zigzag-path-in-a-binary-tree/
---

## 1372. 二叉树中的最长交错路径 (Medium)

{% raw %}

<p>给你一棵以&nbsp;<code>root</code>&nbsp;为根的二叉树，二叉树中的交错路径定义如下：</p>

<ul>
	<li>选择二叉树中 <strong>任意</strong>&nbsp;节点和一个方向（左或者右）。</li>
	<li>如果前进方向为右，那么移动到当前节点的的右子节点，否则移动到它的左子节点。</li>
	<li>改变前进方向：左变右或者右变左。</li>
	<li>重复第二步和第三步，直到你在树中无法继续移动。</li>
</ul>

<p>交错路径的长度定义为：<strong>访问过的节点数目 - 1</strong>（单个节点的路径长度为 0 ）。</p>

<p>请你返回给定树中最长 <strong>交错路径</strong>&nbsp;的长度。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<p><strong><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/03/07/sample_1_1702.png" style="height: 283px; width: 151px;"></strong></p>

<pre><strong>输入：</strong>root = [1,null,1,1,1,null,null,1,1,null,1,null,null,null,1,null,1]
<strong>输出：</strong>3
<strong>解释：</strong>蓝色节点为树中最长交错路径（右 -&gt; 左 -&gt; 右）。
</pre>

<p><strong>示例 2：</strong></p>

<p><strong><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/03/07/sample_2_1702.png" style="height: 253px; width: 120px;"></strong></p>

<pre><strong>输入：</strong>root = [1,1,1,null,1,null,null,1,1,null,1]
<strong>输出：</strong>4
<strong>解释：</strong>蓝色节点为树中最长交错路径（左 -&gt; 右 -&gt; 左 -&gt; 右）。
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>root = [1]
<strong>输出：</strong>0
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li>每棵树最多有&nbsp;<code>50000</code>&nbsp;个节点。</li>
	<li>每个节点的值在&nbsp;<code>[1, 100]</code> 之间。</li>
</ul>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/longest-zigzag-path-in-a-binary-tree)
