---
layout:     single
title:      "链表的中间结点"
date:       2018-05-26 21:30:00 +0800
categories: [Leetcode]
tags:       [Linked List, Two Pointers]
permalink:  /problems/middle-of-the-linked-list/
---

## 876. 链表的中间结点 (Easy)

{% raw %}

<p>给定一个头结点为 <code>head</code> 的非空单链表，返回链表的中间结点。</p>

<p>如果有两个中间结点，则返回第二个中间结点。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>[1,2,3,4,5]
<strong>输出：</strong>此列表中的结点 3 (序列化形式：[3,4,5])
返回的结点值为 3 。 (测评系统对该结点序列化表述是 [3,4,5])。
注意，我们返回了一个 ListNode 类型的对象 ans，这样：
ans.val = 3, ans.next.val = 4, ans.next.next.val = 5, 以及 ans.next.next.next = NULL.
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>[1,2,3,4,5,6]
<strong>输出：</strong>此列表中的结点 4 (序列化形式：[4,5,6])
由于该列表有两个中间结点，值分别为 3 和 4，我们返回第二个结点。
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>给定链表的结点数介于 <code>1</code> 和 <code>100</code> 之间。</li>
</ul>

{% endraw %}

### 相关话题
  [[链表](https://github.com/awesee/leetcode/tree/main/tag/linked-list/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/middle-of-the-linked-list)
