---
layout:     single
title:      "最长同值路径"
date:       2017-11-18 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Binary Tree]
permalink:  /problems/longest-univalue-path/
---

## 687. 最长同值路径 (Medium)

{% raw %}

<p>给定一个二叉树，找到最长的路径，这个路径中的每个节点具有相同值。 这条路径可以经过也可以不经过根节点。</p>

<p><strong>注意</strong>：两个节点之间的路径长度由它们之间的边数表示。</p>

<p><strong>示例 1:</strong></p>

<p>输入:</p>

<pre>
              5
             / \
            4   5
           / \   \
          1   1   5
</pre>

<p>输出:</p>

<pre>
2
</pre>

<p><strong>示例 2:</strong></p>

<p>输入:</p>

<pre>
              1
             / \
            4   5
           / \   \
          4   4   5
</pre>

<p>输出:</p>

<pre>
2
</pre>

<p><strong>注意:</strong> 给定的二叉树不超过10000个结点。&nbsp;树的高度不超过1000。</p>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/master/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/master/tag/binary-tree/README.md)]

### 相似题目
  1. [二叉树中的最大路径和](/problems/binary-tree-maximum-path-sum) (Hard)
  1. [统计同值子树](/problems/count-univalue-subtrees) (Medium)
  1. [路径总和 III](/problems/path-sum-iii) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/longest-univalue-path)
