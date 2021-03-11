---
layout:     single
title:      "移除链表元素"
date:       2016-07-22 21:30:00 +0800
categories: [Leetcode]
tags:       [Linked List]
permalink:  /problems/remove-linked-list-elements/
---

## 203. 移除链表元素 (Easy)

{% raw %}

给你一个链表的头节点 <code>head</code> 和一个整数 <code>val</code> ，请你删除链表中所有满足 <code>Node.val == val</code> 的节点，并返回 <strong>新的头节点</strong> 。
<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2021/03/06/removelinked-list.jpg" style="width: 500px; height: 142px;" />
<pre>
<strong>输入：</strong>head = [1,2,6,3,4,5,6], val = 6
<strong>输出：</strong>[1,2,3,4,5]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>head = [], val = 1
<strong>输出：</strong>[]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>head = [7,7,7,7], val = 7
<strong>输出：</strong>[]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>列表中的节点在范围 <code>[0, 10<sup>4</sup>]</code> 内</li>
	<li><code>1 <= Node.val <= 50</code></li>
	<li><code>0 <= k <= 50</code></li>
</ul>

{% endraw %}

### 相关话题
  [[链表](https://github.com/openset/leetcode/tree/master/tag/linked-list/README.md)]

### 相似题目
  1. [移除元素](/problems/remove-element) (Easy)
  1. [删除链表中的节点](/problems/delete-node-in-a-linked-list) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/remove-linked-list-elements)
