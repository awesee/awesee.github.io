---
layout:     single
title:      "最小差值 II"
date:       2018-06-29 21:30:00 +0800
categories: [leetcode]
tags:       [greedy, math]
permalink:  /smallest-range-ii/
---

## 910. 最小差值 II (Medium)

<p>给定一个整数数组 <code>A</code>，对于每个整数 <code>A[i]</code>，我们可以选择<strong>&nbsp;<code>x = -K</code>&nbsp;或是&nbsp;<code>x = K</code></strong>，并将&nbsp;<code>x</code>&nbsp;加到&nbsp;<code>A[i]</code>&nbsp;中。</p>

<p>在此过程之后，我们得到一些数组&nbsp;<code>B</code>。</p>

<p>返回 <code>B</code>&nbsp;的最大值和 <code>B</code>&nbsp;的最小值之间可能存在的最小差值。</p>

<p>&nbsp;</p>

<ol>
</ol>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>A = [1], K = 0
<strong>输出：</strong>0
<strong>解释：</strong>B = [1]
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>A = [0,10], K = 2
<strong>输出：</strong>6
<strong>解释：</strong>B = [2,8]
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>A = [1,3,6], K = 3
<strong>输出：</strong>3
<strong>解释：</strong>B = [4,6,3]
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= A.length &lt;= 10000</code></li>
	<li><code>0 &lt;= A[i] &lt;= 10000</code></li>
	<li><code>0 &lt;= K &lt;= 10000</code></li>
</ol>

### 相关话题
  [[贪心算法](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/smallest-range-ii)