---
layout:     single
title:      "正方形数组的数目"
date:       2018-09-23 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Array, Math, Dynamic Programming, Backtracking, Bitmask]
permalink:  /problems/number-of-squareful-arrays/
---

## 996. 正方形数组的数目 (Hard)

{% raw %}

<p>给定一个非负整数数组&nbsp;<code>A</code>，如果该数组每对相邻元素之和是一个完全平方数，则称这一数组为<em>正方形</em>数组。</p>

<p>返回 A 的正方形排列的数目。两个排列 <code>A1</code> 和 <code>A2</code> 不同的充要条件是存在某个索引 <code>i</code>，使得 A1[i] != A2[i]。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>[1,17,8]
<strong>输出：</strong>2
<strong>解释：</strong>
[1,8,17] 和 [17,8,1] 都是有效的排列。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>[2,2,2]
<strong>输出：</strong>1
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= A.length &lt;= 12</code></li>
	<li><code>0 &lt;= A[i] &lt;= 1e9</code></li>
</ol>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/openset/leetcode/tree/master/tag/bit-manipulation/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]
  [[回溯](https://github.com/openset/leetcode/tree/master/tag/backtracking/README.md)]
  [[状态压缩](https://github.com/openset/leetcode/tree/master/tag/bitmask/README.md)]

### 相似题目
  1. [全排列 II](/problems/permutations-ii) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/number-of-squareful-arrays)
