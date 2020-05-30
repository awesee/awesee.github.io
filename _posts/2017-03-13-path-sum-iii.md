---
layout:     single
title:      "路径总和 III"
date:       2017-03-13 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree]
permalink:  /problems/path-sum-iii/
---

## 437. 路径总和 III (Easy)

{% raw %}

<p>给定一个二叉树，它的每个结点都存放着一个整数值。</p>

<p>找出路径和等于给定数值的路径总数。</p>

<p>路径不需要从根节点开始，也不需要在叶子节点结束，但是路径方向必须是向下的（只能从父节点到子节点）。</p>

<p>二叉树不超过1000个节点，且节点数值范围是 [-1000000,1000000] 的整数。</p>

<p><strong>示例：</strong></p>

<pre>root = [10,5,-3,3,2,null,11,3,-2,null,1], sum = 8

      10
     /  \
    <strong>5</strong>   <strong>-3</strong>
   <strong>/</strong> <strong>\</strong>    <strong>\</strong>
  <strong>3</strong>   <strong>2</strong>   <strong>11</strong>
 / \   <strong>\</strong>
3  -2   <strong>1</strong>

返回 3。和等于 8 的路径有:

1.  5 -&gt; 3
2.  5 -&gt; 2 -&gt; 1
3.  -3 -&gt; 11
</pre>

{% endraw %}

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]

### 相似题目
  1. [路径总和](/problems/path-sum) (Easy)
  1. [路径总和 II](/problems/path-sum-ii) (Medium)
  1. [路径和 IV](/problems/path-sum-iv) (Medium)
  1. [最长同值路径](/problems/longest-univalue-path) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/path-sum-iii)
