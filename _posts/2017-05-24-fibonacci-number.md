---
layout:     single
title:      "斐波那契数"
date:       2017-05-24 21:30:00 +0800
categories: [Leetcode]
tags:       [Recursion, Memoization, Math, Dynamic Programming]
permalink:  /problems/fibonacci-number/
---

## 509. 斐波那契数 (Easy)

{% raw %}

<p><strong>斐波那契数</strong>，通常用 <code>F(n)</code> 表示，形成的序列称为 <strong>斐波那契数列</strong> 。该数列由 <code>0</code> 和 <code>1</code> 开始，后面的每一项数字都是前面两项数字的和。也就是：</p>

<pre>
F(0) = 0，F(1) = 1
F(n) = F(n - 1) + F(n - 2)，其中 n > 1
</pre>

<p>给你 <code>n</code> ，请计算 <code>F(n)</code> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>2
<strong>输出：</strong>1
<strong>解释：</strong>F(2) = F(1) + F(0) = 1 + 0 = 1
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>3
<strong>输出：</strong>2
<strong>解释：</strong>F(3) = F(2) + F(1) = 1 + 1 = 2
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>4
<strong>输出：</strong>3
<strong>解释：</strong>F(4) = F(3) + F(2) = 2 + 1 = 3
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 <= n <= 30</code></li>
</ul>

{% endraw %}

### 相关话题
  [[递归](https://github.com/awesee/leetcode/tree/main/tag/recursion/README.md)]
  [[记忆化搜索](https://github.com/awesee/leetcode/tree/main/tag/memoization/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

### 相似题目
  1. [爬楼梯](/problems/climbing-stairs) (Easy)
  1. [将数组拆分成斐波那契序列](/problems/split-array-into-fibonacci-sequence) (Medium)
  1. [最长的斐波那契子序列的长度](/problems/length-of-longest-fibonacci-subsequence) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/fibonacci-number)
