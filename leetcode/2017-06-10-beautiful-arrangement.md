---
layout:     single
title:      "优美的排列"
date:       2017-06-10 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Array, Dynamic Programming, Backtracking, Bitmask]
permalink:  /problems/beautiful-arrangement/
---

## 526. 优美的排列 (Medium)

{% raw %}

<p>假设有从 1 到 n 的 n 个整数。用这些整数构造一个数组 <code>perm</code>（<strong>下标从 1 开始</strong>），只要满足下述条件 <strong>之一</strong> ，该数组就是一个 <strong>优美的排列</strong> ：</p>

<ul>
	<li><code>perm[i]</code> 能够被 <code>i</code> 整除</li>
	<li><code>i</code> 能够被 <code>perm[i]</code> 整除</li>
</ul>

<p>给你一个整数 <code>n</code> ，返回可以构造的 <strong>优美排列 </strong>的 <strong>数量</strong> 。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>n = 2
<strong>输出：</strong>2
<b>解释：</b>
第 1 个优美的排列是 [1,2]：
    - perm[1] = 1 能被 i = 1 整除
    - perm[2] = 2 能被 i = 2 整除
第 2 个优美的排列是 [2,1]:
    - perm[1] = 2 能被 i = 1 整除
    - i = 2 能被 perm[2] = 1 整除
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>n = 1
<strong>输出：</strong>1
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= n &lt;= 15</code></li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[回溯](https://github.com/awesee/leetcode/tree/main/tag/backtracking/README.md)]
  [[状态压缩](https://github.com/awesee/leetcode/tree/main/tag/bitmask/README.md)]

### 相似题目
  1. [优美的排列 II](/problems/beautiful-arrangement-ii) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/beautiful-arrangement)
