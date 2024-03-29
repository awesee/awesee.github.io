---
layout:     single
title:      "翻转等价二叉树"
date:       2018-08-09 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Binary Tree]
permalink:  /problems/flip-equivalent-binary-trees/
---

## 951. 翻转等价二叉树 (Medium)

{% raw %}

<p>我们可以为二叉树 T 定义一个翻转操作，如下所示：选择任意节点，然后交换它的左子树和右子树。</p>

<p>只要经过一定次数的翻转操作后，能使 X 等于 Y，我们就称二叉树 X <em>翻转等价</em>于二叉树 Y。</p>

<p>编写一个判断两个二叉树是否是<em>翻转等价</em>的函数。这些树由根节点&nbsp;<code>root1</code> 和 <code>root2</code>&nbsp;给出。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>root1 = [1,2,3,4,5,6,null,null,null,7,8], root2 = [1,3,2,null,6,4,5,null,null,null,null,8,7]
<strong>输出：</strong>true
<strong>解释：</strong>我们翻转值为 1，3 以及 5 的三个节点。
<img alt="Flipped Trees Diagram" src="https://assets.leetcode.com/uploads/2018/11/29/tree_ex.png" style="height: 220px; width: 500px;">
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li>每棵树最多有&nbsp;<code>100</code>&nbsp;个节点。</li>
	<li>每棵树中的每个值都是唯一的、在 <code>[0, 99]</code>&nbsp;范围内的整数。</li>
</ol>

<p>&nbsp;</p>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/flip-equivalent-binary-trees)
