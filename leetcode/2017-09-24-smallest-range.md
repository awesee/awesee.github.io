---
layout:     single
title:      "最小区间"
date:       2017-09-24 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, Two Pointers, String]
permalink:  /problems/smallest-range/
---

## 632. 最小区间 (Hard)

{% raw %}

<p>你有&nbsp;<code>k</code>&nbsp;个升序排列的整数数组。找到一个<strong>最小</strong>区间，使得&nbsp;<code>k</code>&nbsp;个列表中的每个列表至少有一个数包含在其中。</p>

<p>我们定义如果&nbsp;<code>b-a &lt; d-c</code>&nbsp;或者在&nbsp;<code>b-a == d-c</code>&nbsp;时&nbsp;<code>a &lt; c</code>，则区间 [a,b] 比 [c,d] 小。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong>[[4,10,15,24,26], [0,9,12,20], [5,18,22,30]]
<strong>输出:</strong> [20,24]
<strong>解释:</strong> 
列表 1：[4, 10, 15, 24, 26]，24 在区间 [20,24] 中。
列表 2：[0, 9, 12, 20]，20 在区间 [20,24] 中。
列表 3：[5, 18, 22, 30]，22 在区间 [20,24] 中。
</pre>

<p><strong>注意:</strong></p>

<ol>
	<li>给定的列表可能包含重复元素，所以在这里升序表示 &gt;= 。</li>
	<li>1 &lt;= <code>k</code> &lt;= 3500</li>
	<li>-10<sup>5</sup> &lt;= <code>元素的值</code>&nbsp;&lt;= 10<sup>5</sup></li>
	<li><strong>对于使用Java的用户，请注意传入类型已修改为List&lt;List&lt;Integer&gt;&gt;。重置代码模板后可以看到这项改动。</strong></li>
</ol>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

### 相似题目
  1. [最小覆盖子串](/minimum-window-substring) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/smallest-range)
