---
layout:     single
title:      "寻找重复的子树"
date:       2017-10-14 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Breadth-First Search, Binary Tree]
permalink:  /problems/find-duplicate-subtrees/
---

## 652. 寻找重复的子树 (Medium)

{% raw %}

<p>给定一棵二叉树，返回所有重复的子树。对于同一类的重复子树，你只需要返回其中任意<strong>一棵</strong>的根结点即可。</p>

<p>两棵树重复是指它们具有相同的结构以及相同的结点值。</p>

<p><strong>示例 1：</strong></p>

<pre>        1
       / \
      2   3
     /   / \
    4   2   4
       /
      4
</pre>

<p>下面是两个重复的子树：</p>

<pre>      2
     /
    4
</pre>

<p>和</p>

<pre>    4
</pre>

<p>因此，你需要以列表的形式返回上述重复子树的根结点。</p>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/breadth-first-search/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

### 相似题目
  1. [二叉树的序列化与反序列化](/problems/serialize-and-deserialize-binary-tree) (Hard)
  1. [序列化和反序列化二叉搜索树](/problems/serialize-and-deserialize-bst) (Medium)
  1. [根据二叉树创建字符串](/problems/construct-string-from-binary-tree) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/find-duplicate-subtrees)
