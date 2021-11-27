---
layout:     single
title:      "序列化和反序列化二叉搜索树"
date:       2017-03-25 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Breadth-First Search, Design, Binary Search Tree, String, Binary Tree]
permalink:  /problems/serialize-and-deserialize-bst/
---

## 449. 序列化和反序列化二叉搜索树 (Medium)

{% raw %}

<p>序列化是将数据结构或对象转换为一系列位的过程，以便它可以存储在文件或内存缓冲区中，或通过网络连接链路传输，以便稍后在同一个或另一个计算机环境中重建。</p>

<p>设计一个算法来序列化和反序列化<strong> 二叉搜索树</strong> 。 对序列化/反序列化算法的工作方式没有限制。 您只需确保二叉搜索树可以序列化为字符串，并且可以将该字符串反序列化为最初的二叉搜索树。</p>

<p><strong>编码的字符串应尽可能紧凑。</strong></p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>root = [2,1,3]
<strong>输出：</strong>[2,1,3]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>root = []
<strong>输出：</strong>[]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>树中节点数范围是 <code>[0, 10<sup>4</sup>]</code></li>
	<li><code>0 <= Node.val <= 10<sup>4</sup></code></li>
	<li>题目数据 <strong>保证</strong> 输入的树是一棵二叉搜索树。</li>
</ul>

<p> </p>

<p><strong>注意</strong>：不要使用类成员/全局/静态变量来存储状态。 你的序列化和反序列化算法应该是无状态的。</p>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/breadth-first-search/README.md)]
  [[设计](https://github.com/awesee/leetcode/tree/main/tag/design/README.md)]
  [[二叉搜索树](https://github.com/awesee/leetcode/tree/main/tag/binary-search-tree/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

### 相似题目
  1. [二叉树的序列化与反序列化](/problems/serialize-and-deserialize-binary-tree) (Hard)
  1. [寻找重复的子树](/problems/find-duplicate-subtrees) (Medium)
  1. [序列化和反序列化 N 叉树](/problems/serialize-and-deserialize-n-ary-tree) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/serialize-and-deserialize-bst)
