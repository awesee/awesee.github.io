---
layout:     single
title:      "最大二叉树"
date:       2017-10-16 21:30:00 +0800
categories: [leetcode]
tags:       [Tree]
permalink:  /maximum-binary-tree/
---

## 654. 最大二叉树 (Medium)

<p>给定一个不含重复元素的整数数组。一个以此数组构建的最大二叉树定义如下：</p>

<ol>
	<li>二叉树的根是数组中的最大元素。</li>
	<li>左子树是通过数组中最大值左边部分构造出的最大二叉树。</li>
	<li>右子树是通过数组中最大值右边部分构造出的最大二叉树。</li>
</ol>

<p>通过给定的数组构建最大二叉树，并且输出这个树的根节点。</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>输入:</strong> [3,2,1,6,0,5]
<strong>输入:</strong> 返回下面这棵树的根节点：

      6
    /   \
   3     5
    \    / 
     2  0   
       \
        1
</pre>

<p><strong>注意:</strong></p>

<ol>
	<li>给定的数组的大小在 [1, 1000] 之间。</li>
</ol>

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/maximum-binary-tree)
