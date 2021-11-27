---
layout:     single
title:      "2 的幂"
date:       2016-08-19 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Recursion, Math]
permalink:  /problems/power-of-two/
---

## 231. 2 的幂 (Easy)

{% raw %}

<p>给你一个整数 <code>n</code>，请你判断该整数是否是 2 的幂次方。如果是，返回 <code>true</code> ；否则，返回 <code>false</code> 。</p>

<p>如果存在一个整数 <code>x</code> 使得 <code>n == 2<sup>x</sup></code> ，则认为 <code>n</code> 是 2 的幂次方。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>n = 1
<strong>输出：</strong>true
<strong>解释：</strong>2<sup>0</sup> = 1
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>n = 16
<strong>输出：</strong>true
<strong>解释：</strong>2<sup>4</sup> = 16
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>n = 3
<strong>输出：</strong>false
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>n = 4
<strong>输出：</strong>true
</pre>

<p><strong>示例 5：</strong></p>

<pre>
<strong>输入：</strong>n = 5
<strong>输出：</strong>false
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>-2<sup>31</sup> <= n <= 2<sup>31</sup> - 1</code></li>
</ul>

<p> </p>

<p><strong>进阶：</strong>你能够不使用循环/递归解决此问题吗？</p>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[递归](https://github.com/awesee/leetcode/tree/main/tag/recursion/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]

### 相似题目
  1. [位1的个数](/problems/number-of-1-bits) (Easy)
  1. [3的幂](/problems/power-of-three) (Easy)
  1. [4的幂](/problems/power-of-four) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/power-of-two)
