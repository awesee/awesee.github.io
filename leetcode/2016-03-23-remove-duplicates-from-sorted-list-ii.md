---
layout:     single
title:      "删除排序链表中的重复元素 II"
date:       2016-03-23 21:30:00 +0800
categories: [Leetcode]
tags:       [Linked List, Two Pointers]
permalink:  /problems/remove-duplicates-from-sorted-list-ii/
---

## 82. 删除排序链表中的重复元素 II (Medium)

{% raw %}

<p>存在一个按升序排列的链表，给你这个链表的头节点 <code>head</code> ，请你删除链表中所有存在数字重复情况的节点，只保留原始链表中 <strong>没有重复出现</strong><em> </em>的数字。</p>

<p>返回同样按升序排列的结果链表。</p>

<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2021/01/04/linkedlist1.jpg" style="width: 500px; height: 142px;" />
<pre>
<strong>输入：</strong>head = [1,2,3,3,4,4,5]
<strong>输出：</strong>[1,2,5]
</pre>

<p><strong>示例 2：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2021/01/04/linkedlist2.jpg" style="width: 500px; height: 205px;" />
<pre>
<strong>输入：</strong>head = [1,1,1,2,3]
<strong>输出：</strong>[2,3]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>链表中节点数目在范围 <code>[0, 300]</code> 内</li>
	<li><code>-100 <= Node.val <= 100</code></li>
	<li>题目数据保证链表已经按升序排列</li>
</ul>

{% endraw %}

### 相关话题
  [[链表](https://github.com/awesee/leetcode/tree/main/tag/linked-list/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]

### 相似题目
  1. [删除排序链表中的重复元素](/problems/remove-duplicates-from-sorted-list) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/remove-duplicates-from-sorted-list-ii)
