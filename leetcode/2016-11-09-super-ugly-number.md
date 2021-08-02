---
layout:     single
title:      "超级丑数"
date:       2016-11-09 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, Math, Dynamic Programming, Heap (Priority Queue)]
permalink:  /problems/super-ugly-number/
---

## 313. 超级丑数 (Medium)

{% raw %}

<p><strong>超级丑数</strong> 是一个正整数，并满足其所有质因数都出现在质数数组 <code>primes</code> 中。</p>

<p>给你一个整数 <code>n</code> 和一个整数数组 <code>primes</code> ，返回第 <code>n</code> 个 <strong>超级丑数</strong> 。</p>

<p>题目数据保证第 <code>n</code> 个 <strong>超级丑数</strong> 在 <strong>32-bit</strong> 带符号整数范围内。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>n = 12, <code>primes</code> = <code>[2,7,13,19]</code>
<strong>输出：</strong>32 
<strong>解释：</strong>给定长度为 4 的质数数组 primes = [2,7,13,19]，前 12 个超级丑数序列为：[1,2,4,7,8,13,14,16,19,26,28,32] 。</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>n = 1, primes = [2,3,5]
<strong>输出：</strong>1
<strong>解释：</strong>1 不含质因数，因此它的所有质因数都在质数数组 primes = [2,3,5] 中。
</pre>
&nbsp;

<div class="top-view__1vxA">
<div class="original__bRMd">
<div>
<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= n &lt;= 10<sup>6</sup></code></li>
	<li><code>1 &lt;= primes.length &lt;= 100</code></li>
	<li><code>2 &lt;= primes[i] &lt;= 1000</code></li>
	<li>题目数据<strong> 保证</strong> <code>primes[i]</code> 是一个质数</li>
	<li><code>primes</code> 中的所有值都 <strong>互不相同</strong> ，且按 <strong>递增顺序</strong> 排列</li>
</ul>
</div>
</div>
</div>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]
  [[堆（优先队列）](https://github.com/openset/leetcode/tree/master/tag/heap-priority-queue/README.md)]

### 相似题目
  1. [丑数 II](/problems/ugly-number-ii) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/super-ugly-number)
