---
layout:     single
title:      "我的日程安排表 III"
date:       2018-01-02 21:30:00 +0800
categories: [Leetcode]
tags:       [Design, Segment Tree, Ordered Set]
permalink:  /problems/my-calendar-iii/
---

## 732. 我的日程安排表 III (Hard)

{% raw %}

<p>当 <code>k</code> 个日程安排有一些时间上的交叉时（例如 <code>k</code> 个日程安排都在同一时间内），就会产生 <code>k</code> 次预订。</p>

<p>给你一些日程安排 <code>[start, end)</code> ，请你在每个日程安排添加后，返回一个整数 <code>k</code> ，表示所有先前日程安排会产生的最大 <code>k</code> 次预订。</p>

<p>实现一个 <code>MyCalendarThree</code> 类来存放你的日程安排，你可以一直添加新的日程安排。</p>

<ul>
	<li><code>MyCalendarThree()</code> 初始化对象。</li>
	<li><code>int book(int start, int end)</code> 返回一个整数 <code>k</code> ，表示日历中存在的 <code>k</code> 次预订的最大值。</li>
</ul>

<p> </p>

<p><strong>示例：</strong></p>

<pre>
<strong>输入：</strong>
["MyCalendarThree", "book", "book", "book", "book", "book", "book"]
[[], [10, 20], [50, 60], [10, 40], [5, 15], [5, 10], [25, 55]]
<strong>输出：</strong>
[null, 1, 1, 2, 3, 3, 3]

<strong>解释：</strong>
MyCalendarThree myCalendarThree = new MyCalendarThree();
myCalendarThree.book(10, 20); // 返回 1 ，第一个日程安排可以预订并且不存在相交，所以最大 k 次预订是 1 次预订。
myCalendarThree.book(50, 60); // 返回 1 ，第二个日程安排可以预订并且不存在相交，所以最大 k 次预订是 1 次预订。
myCalendarThree.book(10, 40); // 返回 2 ，第三个日程安排 [10, 40) 与第一个日程安排相交，所以最大 k 次预订是 2 次预订。
myCalendarThree.book(5, 15); // 返回 3 ，剩下的日程安排的最大 k 次预订是 3 次预订。
myCalendarThree.book(5, 10); // 返回 3
myCalendarThree.book(25, 55); // 返回 3
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 <= start < end <= 10<sup>9</sup></code></li>
	<li>每个测试用例，调用 <code>book</code> 函数最多不超过 <code>400</code>次</li>
</ul>

{% endraw %}

### 相关话题
  [[设计](https://github.com/awesee/leetcode/tree/main/tag/design/README.md)]
  [[线段树](https://github.com/awesee/leetcode/tree/main/tag/segment-tree/README.md)]
  [[有序集合](https://github.com/awesee/leetcode/tree/main/tag/ordered-set/README.md)]

### 相似题目
  1. [我的日程安排表 I](/problems/my-calendar-i) (Medium)
  1. [我的日程安排表 II](/problems/my-calendar-ii) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/my-calendar-iii)
