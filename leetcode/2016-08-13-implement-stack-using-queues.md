---
layout:     single
title:      "用队列实现栈"
date:       2016-08-13 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Design, Queue]
permalink:  /problems/implement-stack-using-queues/
---

## 225. 用队列实现栈 (Easy)

{% raw %}

<p>请你仅使用两个队列实现一个后入先出（LIFO）的栈，并支持普通栈的全部四种操作（<code>push</code>、<code>top</code>、<code>pop</code> 和 <code>empty</code>）。</p>

<p>实现 <code>MyStack</code> 类：</p>

<ul>
	<li><code>void push(int x)</code> 将元素 x 压入栈顶。</li>
	<li><code>int pop()</code> 移除并返回栈顶元素。</li>
	<li><code>int top()</code> 返回栈顶元素。</li>
	<li><code>boolean empty()</code> 如果栈是空的，返回 <code>true</code> ；否则，返回 <code>false</code> 。</li>
</ul>

<p> </p>

<p><strong>注意：</strong></p>

<ul>
	<li>你只能使用队列的基本操作 —— 也就是 <code>push to back</code>、<code>peek/pop from front</code>、<code>size</code> 和 <code>is empty</code> 这些操作。</li>
	<li>你所使用的语言也许不支持队列。 你可以使用 list （列表）或者 deque（双端队列）来模拟一个队列 , 只要是标准的队列操作即可。</li>
</ul>

<p> </p>

<p><strong>示例：</strong></p>

<pre>
<strong>输入：</strong>
["MyStack", "push", "push", "top", "pop", "empty"]
[[], [1], [2], [], [], []]
<strong>输出：</strong>
[null, null, null, 2, 2, false]

<strong>解释：</strong>
MyStack myStack = new MyStack();
myStack.push(1);
myStack.push(2);
myStack.top(); // 返回 2
myStack.pop(); // 返回 2
myStack.empty(); // 返回 False
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= x <= 9</code></li>
	<li>最多调用<code>100</code> 次 <code>push</code>、<code>pop</code>、<code>top</code> 和 <code>empty</code></li>
	<li>每次调用 <code>pop</code> 和 <code>top</code> 都保证栈不为空</li>
</ul>

<p> </p>

<p><strong>进阶：</strong>你能否实现每种操作的均摊时间复杂度为 <code>O(1)</code> 的栈？换句话说，执行 <code>n</code> 个操作的总时间复杂度 <code>O(n)</code> ，尽管其中某个操作可能需要比其他操作更长的时间。你可以使用两个以上的队列。</p>

{% endraw %}

### 相关话题
  [[栈](https://github.com/awesee/leetcode/tree/main/tag/stack/README.md)]
  [[设计](https://github.com/awesee/leetcode/tree/main/tag/design/README.md)]
  [[队列](https://github.com/awesee/leetcode/tree/main/tag/queue/README.md)]

### 相似题目
  1. [用栈实现队列](/problems/implement-queue-using-stacks) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/implement-stack-using-queues)
