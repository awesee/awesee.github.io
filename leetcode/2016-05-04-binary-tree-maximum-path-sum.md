---
layout:     single
title:      "二叉树中的最大路径和"
date:       2016-05-04 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-first Search]
permalink:  /problems/binary-tree-maximum-path-sum/
---

## 124. 二叉树中的最大路径和 (Hard)

{% raw %}

<p>给定一个<strong>非空</strong>二叉树，返回其最大路径和。</p>

<p>本题中，路径被定义为一条从树中任意节点出发，沿父节点-子节点连接，达到任意节点的序列。该路径<strong>至少包含一个</strong>节点，且不一定经过根节点。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>[1,2,3]

       <strong>1</strong>
      <strong>/ \</strong>
     <strong>2</strong>   <strong>3</strong>

<strong>输出：</strong>6
</pre>

<p><strong>示例&nbsp;2：</strong></p>

<pre><strong>输入：</strong>[-10,9,20,null,null,15,7]

&nbsp;  -10
&nbsp; &nbsp;/ \
&nbsp; 9 &nbsp;<strong>20</strong>
&nbsp; &nbsp; <strong>/ &nbsp;\</strong>
&nbsp; &nbsp;<strong>15 &nbsp; 7</strong>

<strong>输出：</strong>42</pre>

{% endraw %}

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]

### 相似题目
  1. [路径总和](/problems/path-sum) (Easy)
  1. [求根到叶子节点数字之和](/problems/sum-root-to-leaf-numbers) (Medium)
  1. [路径和 IV](/problems/path-sum-iv) (Medium)
  1. [最长同值路径](/problems/longest-univalue-path) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/binary-tree-maximum-path-sum)
