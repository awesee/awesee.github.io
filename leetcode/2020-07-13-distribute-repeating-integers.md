---
layout:     single
title:      "分配重复整数"
date:       2020-07-13 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Array, Dynamic Programming, Backtracking, Bitmask]
permalink:  /problems/distribute-repeating-integers/
---

## 1655. 分配重复整数 (Hard)

{% raw %}

<p>给你一个长度为 <code>n</code> 的整数数组 <code>nums</code> ，这个数组中至多有 <code>50</code> 个不同的值。同时你有 <code>m</code> 个顾客的订单 <code>quantity</code> ，其中，整数 <code>quantity[i]</code> 是第 <code>i</code> 位顾客订单的数目。请你判断是否能将 <code>nums</code> 中的整数分配给这些顾客，且满足：</p>

<ul>
	<li>第 <code>i</code> 位顾客 <strong>恰好 </strong>有 <code>quantity[i]</code> 个整数。</li>
	<li>第 <code>i</code> 位顾客拿到的整数都是 <strong>相同的</strong> 。</li>
	<li>每位顾客都满足上述两个要求。</li>
</ul>

<p>如果你可以分配 <code>nums</code> 中的整数满足上面的要求，那么请返回 <code>true</code> ，否则返回 <code>false</code> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre><b>输入：</b>nums = [1,2,3,4], quantity = [2]
<b>输出：</b>false
<strong>解释：</strong>第 0 位顾客没办法得到两个相同的整数。
</pre>

<p><strong>示例 2：</strong></p>

<pre><b>输入：</b>nums = [1,2,3,3], quantity = [2]
<b>输出：</b>true
<b>解释：</b>第 0 位顾客得到 [3,3] 。整数 [1,2] 都没有被使用。
</pre>

<p><strong>示例 3：</strong></p>

<pre><b>输入：</b>nums = [1,1,2,2], quantity = [2,2]
<b>输出：</b>true
<b>解释：</b>第 0 位顾客得到 [1,1] ，第 1 位顾客得到 [2,2] 。
</pre>

<p><strong>示例 4：</strong></p>

<pre><b>输入：</b>nums = [1,1,2,3], quantity = [2,2]
<b>输出：</b>false
<b>解释：</b>尽管第 0 位顾客可以得到 [1,1] ，第 1 位顾客没法得到 2 个一样的整数。</pre>

<p><strong>示例 5：</strong></p>

<pre><b>输入：</b>nums = [1,1,1,1,1], quantity = [2,3]
<b>输出：</b>true
<b>解释：</b>第 0 位顾客得到 [1,1] ，第 1 位顾客得到 [1,1,1] 。
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>n == nums.length</code></li>
	<li><code>1 &lt;= n &lt;= 10<sup>5</sup></code></li>
	<li><code>1 &lt;= nums[i] &lt;= 1000</code></li>
	<li><code>m == quantity.length</code></li>
	<li><code>1 &lt;= m &lt;= 10</code></li>
	<li><code>1 &lt;= quantity[i] &lt;= 10<sup>5</sup></code></li>
	<li><code>nums</code> 中至多有 <code>50</code> 个不同的数字。</li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[回溯](https://github.com/awesee/leetcode/tree/main/tag/backtracking/README.md)]
  [[状态压缩](https://github.com/awesee/leetcode/tree/main/tag/bitmask/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/distribute-repeating-integers)
