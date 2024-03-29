---
layout:     single
title:      "最大宽度坡"
date:       2018-08-20 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Array, Monotonic Stack]
permalink:  /problems/maximum-width-ramp/
---

## 962. 最大宽度坡 (Medium)

{% raw %}

<p>给定一个整数数组&nbsp;<code>A</code>，<em>坡</em>是元组&nbsp;<code>(i, j)</code>，其中&nbsp;&nbsp;<code>i &lt; j</code>&nbsp;且&nbsp;<code>A[i] &lt;= A[j]</code>。这样的坡的宽度为&nbsp;<code>j - i</code>。</p>

<p>找出&nbsp;<code>A</code>&nbsp;中的坡的最大宽度，如果不存在，返回 0 。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>[6,0,8,2,1,5]
<strong>输出：</strong>4
<strong>解释：</strong>
最大宽度的坡为 (i, j) = (1, 5): A[1] = 0 且 A[5] = 5.
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>[9,8,1,0,1,9,4,0,4,1]
<strong>输出：</strong>7
<strong>解释：</strong>
最大宽度的坡为 (i, j) = (2, 9): A[2] = 1 且 A[9] = 1.
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>2 &lt;= A.length &lt;= 50000</code></li>
	<li><code>0 &lt;= A[i] &lt;= 50000</code></li>
</ol>

<p>&nbsp;</p>

{% endraw %}

### 相关话题
  [[栈](https://github.com/awesee/leetcode/tree/main/tag/stack/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[单调栈](https://github.com/awesee/leetcode/tree/main/tag/monotonic-stack/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/maximum-width-ramp)
