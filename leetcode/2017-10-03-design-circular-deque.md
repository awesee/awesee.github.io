---
layout:     single
title:      "设计循环双端队列"
date:       2017-10-03 21:30:00 +0800
categories: [Leetcode]
tags:       [Design, Queue, Array, Linked List]
permalink:  /problems/design-circular-deque/
---

## 641. 设计循环双端队列 (Medium)

{% raw %}

<p>设计实现双端队列。<br>
你的实现需要支持以下操作：</p>

<ul>
	<li>MyCircularDeque(k)：构造函数,双端队列的大小为k。</li>
	<li>insertFront()：将一个元素添加到双端队列头部。 如果操作成功返回 true。</li>
	<li>insertLast()：将一个元素添加到双端队列尾部。如果操作成功返回 true。</li>
	<li>deleteFront()：从双端队列头部删除一个元素。 如果操作成功返回 true。</li>
	<li>deleteLast()：从双端队列尾部删除一个元素。如果操作成功返回 true。</li>
	<li>getFront()：从双端队列头部获得一个元素。如果双端队列为空，返回 -1。</li>
	<li>getRear()：获得双端队列的最后一个元素。&nbsp;如果双端队列为空，返回 -1。</li>
	<li>isEmpty()：检查双端队列是否为空。</li>
	<li>isFull()：检查双端队列是否满了。</li>
</ul>

<p><strong>示例：</strong></p>

<pre>MyCircularDeque circularDeque = new MycircularDeque(3); // 设置容量大小为3
circularDeque.insertLast(1);			        // 返回 true
circularDeque.insertLast(2);			        // 返回 true
circularDeque.insertFront(3);			        // 返回 true
circularDeque.insertFront(4);			        // 已经满了，返回 false
circularDeque.getRear();  				// 返回 2
circularDeque.isFull();				        // 返回 true
circularDeque.deleteLast();			        // 返回 true
circularDeque.insertFront(4);			        // 返回 true
circularDeque.getFront();				// 返回 4
&nbsp;</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li>所有值的范围为 [1, 1000]</li>
	<li>操作次数的范围为 [1, 1000]</li>
	<li>请不要使用内置的双端队列库。</li>
</ul>

{% endraw %}

### 相关话题
  [[设计](https://github.com/awesee/leetcode/tree/main/tag/design/README.md)]
  [[队列](https://github.com/awesee/leetcode/tree/main/tag/queue/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[链表](https://github.com/awesee/leetcode/tree/main/tag/linked-list/README.md)]

### 相似题目
  1. [设计循环队列](/problems/design-circular-queue) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/design-circular-deque)
