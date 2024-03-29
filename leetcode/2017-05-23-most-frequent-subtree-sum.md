---
layout:     single
title:      "出现次数最多的子树元素和"
date:       2017-05-23 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Hash Table, Binary Tree]
permalink:  /problems/most-frequent-subtree-sum/
---

## 508. 出现次数最多的子树元素和 (Medium)

{% raw %}

<p>给你一个二叉树的根结点，请你找出出现次数最多的子树元素和。一个结点的「子树元素和」定义为以该结点为根的二叉树上所有结点的元素之和（包括结点本身）。</p>

<p>你需要返回出现次数最多的子树元素和。如果有多个元素出现的次数相同，返回所有出现次数最多的子树元素和（不限顺序）。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong><br>
输入:</p>

<pre>  5
 /  \
2   -3
</pre>

<p>返回&nbsp;[2, -3, 4]，所有的值均只出现一次，以任意顺序返回所有值。</p>

<p><strong>示例&nbsp;2：</strong><br>
输入：</p>

<pre>  5
 /  \
2   -5
</pre>

<p>返回&nbsp;[2]，只有 2 出现两次，-5 只出现 1 次。</p>

<p>&nbsp;</p>

<p><strong>提示：</strong>&nbsp;假设任意子树元素和均可以用 32 位有符号整数表示。</p>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

### 相似题目
  1. [另一棵树的子树](/problems/subtree-of-another-tree) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/most-frequent-subtree-sum)
