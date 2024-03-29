---
layout:     single
title:      "火柴拼正方形"
date:       2017-04-18 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Array, Dynamic Programming, Backtracking, Bitmask]
permalink:  /problems/matchsticks-to-square/
---

## 473. 火柴拼正方形 (Medium)

{% raw %}

<p>还记得童话《卖火柴的小女孩》吗？现在，你知道小女孩有多少根火柴，请找出一种能使用所有火柴拼成一个正方形的方法。不能折断火柴，可以把火柴连接起来，并且每根火柴都要用到。</p>

<p>输入为小女孩拥有火柴的数目，每根火柴用其长度表示。输出即为是否能用所有的火柴拼成正方形。</p>

<p><strong>示例&nbsp;1:</strong></p>

<pre>
<strong>输入:</strong> [1,1,2,2,2]
<strong>输出:</strong> true

<strong>解释:</strong> 能拼成一个边长为2的正方形，每边两根火柴。
</pre>

<p><strong>示例&nbsp;2:</strong></p>

<pre>
<strong>输入:</strong> [3,3,3,3,4]
<strong>输出:</strong> false

<strong>解释:</strong> 不能用所有火柴拼成一个正方形。
</pre>

<p><strong>注意:</strong></p>

<ol>
	<li>给定的火柴长度和在&nbsp;<code>0</code>&nbsp;到&nbsp;<code>10^9</code>之间。</li>
	<li>火柴数组的长度不超过15。</li>
</ol>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[回溯](https://github.com/awesee/leetcode/tree/main/tag/backtracking/README.md)]
  [[状态压缩](https://github.com/awesee/leetcode/tree/main/tag/bitmask/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/matchsticks-to-square)
