---
layout:     single
title:      "连续的子数组和"
date:       2017-06-07 21:30:00 +0800
categories: [leetcode]
tags:       [math, dynamic-programming]
permalink:  /continuous-subarray-sum/
---

## 523. 连续的子数组和 (Medium)

<p>给定一个包含<strong>非负数</strong>的数组和一个目标<strong>整数</strong>&nbsp;k，编写一个函数来判断该数组是否含有连续的子数组，其大小至少为 2，总和为 <strong>k</strong> 的倍数，即总和为 n*k，其中 n 也是一个<strong>整数</strong>。</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入:</strong> [23,2,4,6,7], k = 6
<strong>输出:</strong> True
<strong>解释:</strong> [2,4] 是一个大小为 2 的子数组，并且和为 6。
</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入:</strong> [23,2,6,4,7], k = 6
<strong>输出:</strong> True
<strong>解释:</strong> [23,2,6,4,7]是大小为 5 的子数组，并且和为 42。
</pre>

<p><strong>说明:</strong></p>

<ol>
	<li>数组的长度不会超过10,000。</li>
	<li>你可以认为所有数字总和在 32 位有符号整数范围内。</li>
</ol>

### 相关话题
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### 相似题目
  1. [和为K的子数组](/subarray-sum-equals-k) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/continuous-subarray-sum)
