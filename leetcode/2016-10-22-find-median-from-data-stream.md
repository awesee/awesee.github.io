---
layout:     single
title:      "数据流的中位数"
date:       2016-10-22 21:30:00 +0800
categories: [Leetcode]
tags:       [Design, Two Pointers, Data Stream, Sorting, Heap (Priority Queue)]
permalink:  /problems/find-median-from-data-stream/
---

## 295. 数据流的中位数 (Hard)

{% raw %}

<p>中位数是有序列表中间的数。如果列表长度是偶数，中位数则是中间两个数的平均值。</p>

<p>例如，</p>

<p>[2,3,4]&nbsp;的中位数是 3</p>

<p>[2,3] 的中位数是 (2 + 3) / 2 = 2.5</p>

<p>设计一个支持以下两种操作的数据结构：</p>

<ul>
	<li>void addNum(int num) - 从数据流中添加一个整数到数据结构中。</li>
	<li>double findMedian() - 返回目前所有元素的中位数。</li>
</ul>

<p><strong>示例：</strong></p>

<pre>addNum(1)
addNum(2)
findMedian() -&gt; 1.5
addNum(3) 
findMedian() -&gt; 2</pre>

<p><strong>进阶:</strong></p>

<ol>
	<li>如果数据流中所有整数都在 0 到 100 范围内，你将如何优化你的算法？</li>
	<li>如果数据流中 99% 的整数都在 0 到 100 范围内，你将如何优化你的算法？</li>
</ol>

{% endraw %}

### 相关话题
  [[设计](https://github.com/awesee/leetcode/tree/main/tag/design/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]
  [[数据流](https://github.com/awesee/leetcode/tree/main/tag/data-stream/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]
  [[堆（优先队列）](https://github.com/awesee/leetcode/tree/main/tag/heap-priority-queue/README.md)]

### 相似题目
  1. [滑动窗口中位数](/problems/sliding-window-median) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/find-median-from-data-stream)
