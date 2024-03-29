---
layout:     single
title:      "阶乘函数后 K 个零"
date:       2018-03-04 21:30:00 +0800
categories: [Leetcode]
tags:       [Math, Binary Search]
permalink:  /problems/preimage-size-of-factorial-zeroes-function/
---

## 793. 阶乘函数后 K 个零 (Hard)

{% raw %}

<p> <code>f(x)</code> 是 <code>x!</code> 末尾是 0 的数量。（回想一下 <code>x! = 1 * 2 * 3 * ... * x</code>，且 <code>0! = 1</code> ）</p>

<p>例如， <code>f(3) = 0</code> ，因为 3! = 6 的末尾没有 0 ；而 <code>f(11) = 2</code> ，因为 11!= 39916800 末端有 2 个 0 。给定 <code>K</code>，找出多少个非负整数 <code>x</code> ，能满足 <code>f(x) = K</code> 。</p>

<p> </p>

<p><strong>示例 1：</strong><strong> </strong></p>

<pre>
<strong>输入：</strong>K = 0<strong>
输出：</strong>5<strong>
解释：</strong>0!, 1!, 2!, 3!, and 4! 均符合 K = 0 的条件。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>K = 5
<strong>输出：</strong>0
<strong>解释：</strong>没有匹配到这样的 x!，符合 K = 5 的条件。</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>
	<p><code>K</code> 是范围在 <code>[0, 10^9]</code> 的整数<strong>。</strong></p>
	</li>
</ul>

{% endraw %}

### 相关话题
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]

### 相似题目
  1. [阶乘后的零](/problems/factorial-trailing-zeroes) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/preimage-size-of-factorial-zeroes-function)
