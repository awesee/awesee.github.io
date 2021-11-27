---
layout:     single
title:      "二叉搜索树中的搜索"
date:       2017-12-01 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Binary Search Tree, Binary Tree]
permalink:  /problems/search-in-a-binary-search-tree/
---

## 700. 二叉搜索树中的搜索 (Easy)

{% raw %}

<p>给定二叉搜索树（BST）的根节点和一个值。 你需要在BST中找到节点值等于给定值的节点。 返回以该节点为根的子树。 如果节点不存在，则返回 NULL。</p>

<p>例如，</p>

<pre>
给定二叉搜索树:

        4
       / \
      2   7
     / \
    1   3

和值: 2
</pre>

<p>你应该返回如下子树:</p>

<pre>
      2     
     / \   
    1   3
</pre>

<p>在上述示例中，如果要找的值是 <code>5</code>，但因为没有节点值为 <code>5</code>，我们应该返回 <code>NULL</code>。</p>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[二叉搜索树](https://github.com/awesee/leetcode/tree/main/tag/binary-search-tree/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

### 相似题目
  1. [最接近的二叉搜索树值](/problems/closest-binary-search-tree-value) (Easy)
  1. [二叉搜索树中的插入操作](/problems/insert-into-a-binary-search-tree) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/search-in-a-binary-search-tree)
