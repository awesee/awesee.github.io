---
layout:     single
title:      "三等分"
date:       2018-07-16 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Math]
permalink:  /problems/three-equal-parts/
---

## 927. 三等分 (Hard)

{% raw %}

<p>给定一个由 <code>0</code> 和 <code>1</code> 组成的数组&nbsp;<code>A</code>，将数组分成 3&nbsp;个非空的部分，使得所有这些部分表示相同的二进制值。</p>

<p>如果可以做到，请返回<strong>任何</strong>&nbsp;<code>[i, j]</code>，其中 <code>i+1 &lt; j</code>，这样一来：</p>

<ul>
	<li><code>A[0], A[1], ..., A[i]</code>&nbsp;组成第一部分；</li>
	<li><code>A[i+1], A[i+2], ..., A[j-1]</code>&nbsp;作为第二部分；</li>
	<li><code>A[j], A[j+1], ..., A[A.length - 1]</code> 是第三部分。</li>
	<li>这三个部分所表示的二进制值相等。</li>
</ul>

<p>如果无法做到，就返回&nbsp;<code>[-1, -1]</code>。</p>

<p>注意，在考虑每个部分所表示的二进制时，应当将其看作一个整体。例如，<code>[1,1,0]</code>&nbsp;表示十进制中的&nbsp;<code>6</code>，而不会是&nbsp;<code>3</code>。此外，前导零也是被允许的，所以&nbsp;<code>[0,1,1]</code> 和&nbsp;<code>[1,1]</code>&nbsp;表示相同的值。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>[1,0,1,0,1]
<strong>输出：</strong>[0,3]
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输出：</strong>[1,1,0,1,1]
<strong>输出：</strong>[-1,-1]</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>3 &lt;= A.length &lt;= 30000</code></li>
	<li><code>A[i] == 0</code>&nbsp;或&nbsp;<code>A[i] == 1</code></li>
</ol>

<p>&nbsp;</p>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/three-equal-parts)
