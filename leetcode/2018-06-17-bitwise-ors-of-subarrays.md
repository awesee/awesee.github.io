---
layout:     single
title:      "子数组按位或操作"
date:       2018-06-17 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Array, Dynamic Programming]
permalink:  /problems/bitwise-ors-of-subarrays/
---

## 898. 子数组按位或操作 (Medium)

{% raw %}

<p>我们有一个非负整数数组&nbsp;<code>A</code>。</p>

<p>对于每个（连续的）子数组&nbsp;<code>B =&nbsp;[A[i], A[i+1], ..., A[j]]</code> （&nbsp;<code>i &lt;= j</code>），我们对&nbsp;<code>B</code>&nbsp;中的每个元素进行按位或操作，获得结果&nbsp;<code>A[i] | A[i+1] | ... | A[j]</code>。</p>

<p>返回可能结果的数量。 （多次出现的结果在最终答案中仅计算一次。）</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>[0]
<strong>输出：</strong>1
<strong>解释：</strong>
只有一个可能的结果 0 。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>[1,1,2]
<strong>输出：</strong>3
<strong>解释：</strong>
可能的子数组为 [1]，[1]，[2]，[1, 1]，[1, 2]，[1, 1, 2]。
产生的结果为 1，1，2，1，3，3 。
有三个唯一值，所以答案是 3 。
</pre>

<p><strong>示例&nbsp;3：</strong></p>

<pre><strong>输入：</strong>[1,2,4]
<strong>输出：</strong>6
<strong>解释：</strong>
可能的结果是 1，2，3，4，6，以及 7 。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= A.length &lt;= 50000</code></li>
	<li><code>0 &lt;= A[i] &lt;= 10^9</code></li>
</ol>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/bitwise-ors-of-subarrays)
