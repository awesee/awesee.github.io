---
layout:     single
title:      "填充每个节点的下一个右侧节点指针 II"
date:       2016-04-27 21:30:00 +0800
categories: [leetcode]
tags:       [tree, depth-first-search]
permalink:  /populating-next-right-pointers-in-each-node-ii/
---

## 117. 填充每个节点的下一个右侧节点指针 II (Medium)

<p>给定一个二叉树</p>

<pre>struct Node {
  int val;
  Node *left;
  Node *right;
  Node *next;
}</pre>

<p>填充它的每个 next 指针，让这个指针指向其下一个右侧节点。如果找不到下一个右侧节点，则将 next 指针设置为 <code>NULL</code>。</p>

<p>初始状态下，所有&nbsp;next 指针都被设置为 <code>NULL</code>。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<p><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/02/15/117_sample.png" style="height: 218px; width: 640px;"></p>

<pre><strong>输入：</strong>{&quot;$id&quot;:&quot;1&quot;,&quot;left&quot;:{&quot;$id&quot;:&quot;2&quot;,&quot;left&quot;:{&quot;$id&quot;:&quot;3&quot;,&quot;left&quot;:null,&quot;next&quot;:null,&quot;right&quot;:null,&quot;val&quot;:4},&quot;next&quot;:null,&quot;right&quot;:{&quot;$id&quot;:&quot;4&quot;,&quot;left&quot;:null,&quot;next&quot;:null,&quot;right&quot;:null,&quot;val&quot;:5},&quot;val&quot;:2},&quot;next&quot;:null,&quot;right&quot;:{&quot;$id&quot;:&quot;5&quot;,&quot;left&quot;:null,&quot;next&quot;:null,&quot;right&quot;:{&quot;$id&quot;:&quot;6&quot;,&quot;left&quot;:null,&quot;next&quot;:null,&quot;right&quot;:null,&quot;val&quot;:7},&quot;val&quot;:3},&quot;val&quot;:1}

<strong>输出：</strong>{&quot;$id&quot;:&quot;1&quot;,&quot;left&quot;:{&quot;$id&quot;:&quot;2&quot;,&quot;left&quot;:{&quot;$id&quot;:&quot;3&quot;,&quot;left&quot;:null,&quot;next&quot;:{&quot;$id&quot;:&quot;4&quot;,&quot;left&quot;:null,&quot;next&quot;:{&quot;$id&quot;:&quot;5&quot;,&quot;left&quot;:null,&quot;next&quot;:null,&quot;right&quot;:null,&quot;val&quot;:7},&quot;right&quot;:null,&quot;val&quot;:5},&quot;right&quot;:null,&quot;val&quot;:4},&quot;next&quot;:{&quot;$id&quot;:&quot;6&quot;,&quot;left&quot;:null,&quot;next&quot;:null,&quot;right&quot;:{&quot;$ref&quot;:&quot;5&quot;},&quot;val&quot;:3},&quot;right&quot;:{&quot;$ref&quot;:&quot;4&quot;},&quot;val&quot;:2},&quot;next&quot;:null,&quot;right&quot;:{&quot;$ref&quot;:&quot;6&quot;},&quot;val&quot;:1}

<strong>解释：</strong>给定二叉树如图 A 所示，你的函数应该填充它的每个 next 指针，以指向其下一个右侧节点，如图 B 所示。</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li>你只能使用常量级额外空间。</li>
	<li>使用递归解题也符合要求，本题中递归程序占用的栈空间不算做额外的空间复杂度。</li>
</ul>

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]

### 相似题目
  1. [填充每个节点的下一个右侧节点指针](/populating-next-right-pointers-in-each-node) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/populating-next-right-pointers-in-each-node-ii)