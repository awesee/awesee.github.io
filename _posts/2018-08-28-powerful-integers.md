---
layout:     single
title:      "强整数"
date:       2018-08-28 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, Math]
permalink:  /problems/powerful-integers/
---

## 970. 强整数 (Medium)

{% raw %}

<p>给定两个正整数 <code>x</code> 和 <code>y</code>，如果某一整数等于 <code>x^i + y^j</code>，其中整数&nbsp;<code>i &gt;= 0</code> 且&nbsp;<code>j &gt;= 0</code>，那么我们认为该整数是一个<em>强整数</em>。</p>

<p>返回值小于或等于&nbsp;<code>bound</code>&nbsp;的所有<em>强整数</em>组成的列表。</p>

<p>你可以按任何顺序返回答案。在你的回答中，每个值最多出现一次。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>x = 2, y = 3, bound = 10
<strong>输出：</strong>[2,3,4,5,7,9,10]
<strong>解释： </strong>
2 = 2^0 + 3^0
3 = 2^1 + 3^0
4 = 2^0 + 3^1
5 = 2^1 + 3^1
7 = 2^2 + 3^1
9 = 2^3 + 3^0
10 = 2^0 + 3^2
</pre>

<p><strong>示例&nbsp;2：</strong></p>

<pre><strong>输入：</strong>x = 3, y = 5, bound = 15
<strong>输出：</strong>[2,4,6,8,10,14]
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= x &lt;= 100</code></li>
	<li><code>1 &lt;= y&nbsp;&lt;= 100</code></li>
	<li><code>0 &lt;= bound&nbsp;&lt;= 10^6</code></li>
</ul>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/powerful-integers)
