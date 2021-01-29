---
layout:     single
title:      "两两交换链表中的节点"
date:       2016-01-25 21:30:00 +0800
categories: [Leetcode]
tags:       [Recursion, Linked List]
permalink:  /problems/swap-nodes-in-pairs/
---

## 24. 两两交换链表中的节点 (Medium)

{% raw %}

<p>给定一个链表，两两交换其中相邻的节点，并返回交换后的链表。</p>

<p><strong>你不能只是单纯的改变节点内部的值</strong>，而是需要实际的进行节点交换。</p>

<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/10/03/swap_ex1.jpg" style="width: 422px; height: 222px;" />
<pre>
<strong>输入：</strong>head = [1,2,3,4]
<strong>输出：</strong>[2,1,4,3]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>head = []
<strong>输出：</strong>[]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>head = [1]
<strong>输出：</strong>[1]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>链表中节点的数目在范围 <code>[0, 100]</code> 内</li>
	<li><code>0 <= Node.val <= 100</code></li>
</ul>

<p> </p>

<p><strong>进阶：</strong>你能在不修改链表节点值的情况下解决这个问题吗?（也就是说，仅修改节点本身。）</p>

{% endraw %}

### 相关话题
  [[递归](https://github.com/openset/leetcode/tree/master/tag/recursion/README.md)]
  [[链表](https://github.com/openset/leetcode/tree/master/tag/linked-list/README.md)]

### 相似题目
  1. [K 个一组翻转链表](/problems/reverse-nodes-in-k-group) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/swap-nodes-in-pairs)
