---
layout:     single
title:      "根据前序和后序遍历构造二叉树"
date:       2018-06-08 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Array, Hash Table, Divide and Conquer, Binary Tree]
permalink:  /problems/construct-binary-tree-from-preorder-and-postorder-traversal/
---

## 889. 根据前序和后序遍历构造二叉树 (Medium)

{% raw %}

<p>返回与给定的前序和后序遍历匹配的任何二叉树。</p>

<p>&nbsp;<code>pre</code>&nbsp;和&nbsp;<code>post</code>&nbsp;遍历中的值是不同的正整数。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>pre = [1,2,4,5,3,6,7], post = [4,5,2,6,7,3,1]
<strong>输出：</strong>[1,2,3,4,5,6,7]
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= pre.length == post.length &lt;= 30</code></li>
	<li><code>pre[]</code>&nbsp;和&nbsp;<code>post[]</code>&nbsp;都是&nbsp;<code>1, 2, ..., pre.length</code>&nbsp;的排列</li>
	<li>每个输入保证至少有一个答案。如果有多个答案，可以返回其中一个。</li>
</ul>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[分治](https://github.com/awesee/leetcode/tree/main/tag/divide-and-conquer/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/construct-binary-tree-from-preorder-and-postorder-traversal)
