---
layout:     single
title:      "旋转链表"
date:       2016-03-02 21:30:00 +0800
categories: [Leetcode]
tags:       [Linked List, Two Pointers]
permalink:  /problems/rotate-list/
---

## 61. 旋转链表 (Medium)

{% raw %}

<p>给你一个链表的头节点 <code>head</code> ，旋转链表，将链表每个节点向右移动 <code>k</code><em> </em>个位置。</p>

<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/11/13/rotate1.jpg" style="width: 600px; height: 254px;" />
<pre>
<strong>输入：</strong>head = [1,2,3,4,5], k = 2
<strong>输出：</strong>[4,5,1,2,3]
</pre>

<p><strong>示例 2：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/11/13/roate2.jpg" style="width: 472px; height: 542px;" />
<pre>
<strong>输入：</strong>head = [0,1,2], k = 4
<strong>输出：</strong>[2,0,1]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>链表中节点的数目在范围 <code>[0, 500]</code> 内</li>
	<li><code>-100 <= Node.val <= 100</code></li>
	<li><code>0 <= k <= 2 * 10<sup>9</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[链表](https://github.com/awesee/leetcode/tree/main/tag/linked-list/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]

### 相似题目
  1. [旋转数组](/problems/rotate-array) (Medium)
  1. [分隔链表](/problems/split-linked-list-in-parts) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/rotate-list)
