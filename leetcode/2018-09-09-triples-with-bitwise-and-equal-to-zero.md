---
layout:     single
title:      "按位与为零的三元组"
date:       2018-09-09 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Array, Hash Table]
permalink:  /problems/triples-with-bitwise-and-equal-to-zero/
---

## 982. 按位与为零的三元组 (Hard)

{% raw %}

<p>给定一个整数数组&nbsp;<code>A</code>，找出索引为 (i, j, k) 的三元组，使得：</p>

<ul>
	<li><code>0 &lt;= i &lt; A.length</code></li>
	<li><code>0 &lt;= j &lt; A.length</code></li>
	<li><code>0 &lt;= k &lt; A.length</code></li>
	<li><code>A[i]&nbsp;&amp; A[j]&nbsp;&amp; A[k] == 0</code>，其中&nbsp;<code>&amp;</code>&nbsp;表示按位与（AND）操作符。</li>
</ul>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>[2,1,3]
<strong>输出：</strong>12
<strong>解释：</strong>我们可以选出如下 i, j, k 三元组：
(i=0, j=0, k=1) : 2 &amp; 2 &amp; 1
(i=0, j=1, k=0) : 2 &amp; 1 &amp; 2
(i=0, j=1, k=1) : 2 &amp; 1 &amp; 1
(i=0, j=1, k=2) : 2 &amp; 1 &amp; 3
(i=0, j=2, k=1) : 2 &amp; 3 &amp; 1
(i=1, j=0, k=0) : 1 &amp; 2 &amp; 2
(i=1, j=0, k=1) : 1 &amp; 2 &amp; 1
(i=1, j=0, k=2) : 1 &amp; 2 &amp; 3
(i=1, j=1, k=0) : 1 &amp; 1 &amp; 2
(i=1, j=2, k=0) : 1 &amp; 3 &amp; 2
(i=2, j=0, k=1) : 3 &amp; 2 &amp; 1
(i=2, j=1, k=0) : 3 &amp; 1 &amp; 2
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= A.length &lt;= 1000</code></li>
	<li><code>0 &lt;= A[i] &lt; 2^16</code></li>
</ol>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/triples-with-bitwise-and-equal-to-zero)
