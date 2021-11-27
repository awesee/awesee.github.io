---
layout:     single
title:      "合并两个有序链表"
date:       2016-01-22 21:30:00 +0800
categories: [Leetcode]
tags:       [Recursion, Linked List]
permalink:  /problems/merge-two-sorted-lists/
---

## 21. 合并两个有序链表 (Easy)

{% raw %}

<p>将两个升序链表合并为一个新的 <strong>升序</strong> 链表并返回。新链表是通过拼接给定的两个链表的所有节点组成的。 </p>

<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/10/03/merge_ex1.jpg" style="width: 662px; height: 302px;" />
<pre>
<strong>输入：</strong>l1 = [1,2,4], l2 = [1,3,4]
<strong>输出：</strong>[1,1,2,3,4,4]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>l1 = [], l2 = []
<strong>输出：</strong>[]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>l1 = [], l2 = [0]
<strong>输出：</strong>[0]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>两个链表的节点数目范围是 <code>[0, 50]</code></li>
	<li><code>-100 <= Node.val <= 100</code></li>
	<li><code>l1</code> 和 <code>l2</code> 均按 <strong>非递减顺序</strong> 排列</li>
</ul>

{% endraw %}

### 相关话题
  [[递归](https://github.com/awesee/leetcode/tree/main/tag/recursion/README.md)]
  [[链表](https://github.com/awesee/leetcode/tree/main/tag/linked-list/README.md)]

### 相似题目
  1. [合并K个升序链表](/problems/merge-k-sorted-lists) (Hard)
  1. [合并两个有序数组](/problems/merge-sorted-array) (Easy)
  1. [排序链表](/problems/sort-list) (Medium)
  1. [最短单词距离 II](/problems/shortest-word-distance-ii) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/merge-two-sorted-lists)
