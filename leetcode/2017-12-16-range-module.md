---
layout:     single
title:      "Range 模块"
date:       2017-12-16 21:30:00 +0800
categories: [Leetcode]
tags:       [Design, Segment Tree, Ordered Set]
permalink:  /problems/range-module/
---

## 715. Range 模块 (Hard)

{% raw %}

<p>Range 模块是跟踪数字范围的模块。你的任务是以一种有效的方式设计和实现以下接口。</p>

<ul>
	<li><code>addRange(int left, int right)</code> 添加半开区间&nbsp;<code>[left, right)</code>，跟踪该区间中的每个实数。添加与当前跟踪的数字部分重叠的区间时，应当添加在区间&nbsp;<code>[left, right)</code>&nbsp;中尚未跟踪的任何数字到该区间中。</li>
	<li><code>queryRange(int left, int right)</code>&nbsp;只有在当前正在跟踪区间&nbsp;<code>[left, right)</code>&nbsp;中的每一个实数时，才返回 true。</li>
	<li><code>removeRange(int left, int right)</code>&nbsp;停止跟踪区间&nbsp;<code>[left, right)</code>&nbsp;中当前正在跟踪的每个实数。</li>
</ul>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>addRange(10, 20)</strong>: null
<strong>removeRange(14, 16)</strong>: null
<strong>queryRange(10, 14)</strong>: true （区间 [10, 14) 中的每个数都正在被跟踪）
<strong>queryRange(13, 15)</strong>: false （未跟踪区间 [13, 15) 中像 14, 14.03, 14.17 这样的数字）
<strong>queryRange(16, 17)</strong>: true （尽管执行了删除操作，区间 [16, 17) 中的数字 16 仍然会被跟踪）
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li>半开区间&nbsp;<code>[left, right)</code>&nbsp;表示所有满足&nbsp;<code>left &lt;= x &lt; right</code>&nbsp;的实数。</li>
	<li>对&nbsp;<code>addRange, queryRange, removeRange</code>&nbsp;的所有调用中&nbsp;<code>0 &lt; left &lt; right &lt; 10^9</code>。</li>
	<li>在单个测试用例中，对&nbsp;<code>addRange</code>&nbsp;的调用总数不超过&nbsp;<code>1000</code>&nbsp;次。</li>
	<li>在单个测试用例中，对&nbsp; <code>queryRange</code> 的调用总数不超过 <code>5000</code> 次。</li>
	<li>在单个测试用例中，对 <code>removeRange</code> 的调用总数不超过&nbsp;<code>1000</code>&nbsp;次。</li>
</ul>

<p>&nbsp;</p>

{% endraw %}

### 相关话题
  [[设计](https://github.com/awesee/leetcode/tree/main/tag/design/README.md)]
  [[线段树](https://github.com/awesee/leetcode/tree/main/tag/segment-tree/README.md)]
  [[有序集合](https://github.com/awesee/leetcode/tree/main/tag/ordered-set/README.md)]

### 相似题目
  1. [合并区间](/problems/merge-intervals) (Medium)
  1. [插入区间](/problems/insert-interval) (Medium)
  1. [将数据流变为多个不相交区间](/problems/data-stream-as-disjoint-intervals) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/range-module)
