---
layout:     single
title:      "交换链表中的节点"
date:       2020-09-17 21:30:00 +0800
categories: [Leetcode]
tags:       [Linked List, Two Pointers]
permalink:  /problems/swapping-nodes-in-a-linked-list/
---

## 1721. 交换链表中的节点 (Medium)

{% raw %}

<p>给你链表的头节点 <code>head</code> 和一个整数 <code>k</code> 。</p>

<p><strong>交换</strong> 链表正数第 <code>k</code> 个节点和倒数第 <code>k</code> 个节点的值后，返回链表的头节点（链表 <strong>从 1 开始索引</strong>）。</p>

<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2021/01/10/linked1.jpg" style="width: 722px; height: 202px;" />
<pre>
<strong>输入：</strong>head = [1,2,3,4,5], k = 2
<strong>输出：</strong>[1,4,3,2,5]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>head = [7,9,6,6,7,8,3,0,9,5], k = 5
<strong>输出：</strong>[7,9,6,6,8,7,3,0,9,5]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>head = [1], k = 1
<strong>输出：</strong>[1]
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>head = [1,2], k = 1
<strong>输出：</strong>[2,1]
</pre>

<p><strong>示例 5：</strong></p>

<pre>
<strong>输入：</strong>head = [1,2,3], k = 2
<strong>输出：</strong>[1,2,3]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>链表中节点的数目是 <code>n</code></li>
	<li><code>1 <= k <= n <= 10<sup>5</sup></code></li>
	<li><code>0 <= Node.val <= 100</code></li>
</ul>

{% endraw %}

### 相关话题
  [[链表](https://github.com/awesee/leetcode/tree/main/tag/linked-list/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/swapping-nodes-in-a-linked-list)
