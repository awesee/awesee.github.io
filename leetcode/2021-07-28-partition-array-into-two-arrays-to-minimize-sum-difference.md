---
layout:     single
title:      "将数组分成两个数组并最小化数组和的差"
date:       2021-07-28 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Array, Two Pointers, Binary Search, Dynamic Programming, Bitmask, Ordered Set]
permalink:  /problems/partition-array-into-two-arrays-to-minimize-sum-difference/
---

## 2035. 将数组分成两个数组并最小化数组和的差 (Hard)

{% raw %}

<p>给你一个长度为 <code>2 * n</code>&nbsp;的整数数组。你需要将&nbsp;<code>nums</code>&nbsp;分成&nbsp;<strong>两个</strong>&nbsp;长度为&nbsp;<code>n</code>&nbsp;的数组，分别求出两个数组的和，并 <strong>最小化</strong>&nbsp;两个数组和之&nbsp;<b>差的绝对值</b>&nbsp;。<code>nums</code>&nbsp;中每个元素都需要放入两个数组之一。</p>

<p>请你返回&nbsp;<strong>最小</strong>&nbsp;的数组和之差。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<p><img alt="example-1" src="https://assets.leetcode.com/uploads/2021/10/02/ex1.png" style="width: 240px; height: 106px;"></p>

<pre><b>输入：</b>nums = [3,9,7,3]
<b>输出：</b>2
<strong>解释：</strong>最优分组方案是分成 [3,9] 和 [7,3] 。
数组和之差的绝对值为 abs((3 + 9) - (7 + 3)) = 2 。
</pre>

<p><strong>示例 2：</strong></p>

<pre><b>输入：</b>nums = [-36,36]
<b>输出：</b>72
<strong>解释：</strong>最优分组方案是分成 [-36] 和 [36] 。
数组和之差的绝对值为 abs((-36) - (36)) = 72 。
</pre>

<p><strong>示例 3：</strong></p>

<p><img alt="example-3" src="https://assets.leetcode.com/uploads/2021/10/02/ex3.png" style="width: 316px; height: 106px;"></p>

<pre><b>输入：</b>nums = [2,-1,0,4,-2,-9]
<b>输出：</b>0
<strong>解释：</strong>最优分组方案是分成 [2,4,-9] 和 [-1,0,-2] 。
数组和之差的绝对值为 abs((2 + 4 + -9) - (-1 + 0 + -2)) = 0 。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= n &lt;= 15</code></li>
	<li><code>nums.length == 2 * n</code></li>
	<li><code>-10<sup>7</sup> &lt;= nums[i] &lt;= 10<sup>7</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/master/tag/bit-manipulation/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/master/tag/array/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/master/tag/two-pointers/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/master/tag/binary-search/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/master/tag/dynamic-programming/README.md)]
  [[状态压缩](https://github.com/awesee/leetcode/tree/master/tag/bitmask/README.md)]
  [[有序集合](https://github.com/awesee/leetcode/tree/master/tag/ordered-set/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/partition-array-into-two-arrays-to-minimize-sum-difference)
