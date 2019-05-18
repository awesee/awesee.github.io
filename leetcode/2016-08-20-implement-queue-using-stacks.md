---
layout:     single
title:      "用栈实现队列"
date:       2016-08-20 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Design]
permalink:  /implement-queue-using-stacks/
---

## 232. 用栈实现队列 (Easy)

<p>使用栈实现队列的下列操作：</p>

<ul>
	<li>push(x) -- 将一个元素放入队列的尾部。</li>
	<li>pop() -- 从队列首部移除元素。</li>
	<li>peek() -- 返回队列首部的元素。</li>
	<li>empty() -- 返回队列是否为空。</li>
</ul>

<p><strong>示例:</strong></p>

<pre>MyQueue queue = new MyQueue();

queue.push(1);
queue.push(2);  
queue.peek();  // 返回 1
queue.pop();   // 返回 1
queue.empty(); // 返回 false</pre>

<p><strong>说明:</strong></p>

<ul>
	<li>你只能使用标准的栈操作 -- 也就是只有&nbsp;<code>push to top</code>,&nbsp;<code>peek/pop from top</code>,&nbsp;<code>size</code>, 和&nbsp;<code>is empty</code>&nbsp;操作是合法的。</li>
	<li>你所使用的语言也许不支持栈。你可以使用 list 或者 deque（双端队列）来模拟一个栈，只要是标准的栈操作即可。</li>
	<li>假设所有操作都是有效的 （例如，一个空的队列不会调用 pop 或者 peek 操作）。</li>
</ul>

### 相关话题
  [[栈](https://github.com/openset/leetcode/tree/master/tag/stack/README.md)]
  [[设计](https://github.com/openset/leetcode/tree/master/tag/design/README.md)]

### 相似题目
  1. [用队列实现栈](/implement-stack-using-queues) (Easy)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/implement-queue-using-stacks)
