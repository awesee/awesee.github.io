---
layout:     single
title:      "坏了的计算器"
date:       2018-09-18 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Math]
permalink:  /problems/broken-calculator/
---

## 991. 坏了的计算器 (Medium)

{% raw %}

<p>在显示着数字的坏计算器上，我们可以执行以下两种操作：</p>

<ul>
	<li><strong>双倍（Double）：</strong>将显示屏上的数字乘 2；</li>
	<li><strong>递减（Decrement）：</strong>将显示屏上的数字减 1 。</li>
</ul>

<p>最初，计算器显示数字&nbsp;<code>X</code>。</p>

<p>返回显示数字&nbsp;<code>Y</code>&nbsp;所需的最小操作数。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>X = 2, Y = 3
<strong>输出：</strong>2
<strong>解释：</strong>先进行双倍运算，然后再进行递减运算 {2 -&gt; 4 -&gt; 3}.
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>X = 5, Y = 8
<strong>输出：</strong>2
<strong>解释：</strong>先递减，再双倍 {5 -&gt; 4 -&gt; 8}.
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>X = 3, Y = 10
<strong>输出：</strong>3
<strong>解释：</strong>先双倍，然后递减，再双倍 {3 -&gt; 6 -&gt; 5 -&gt; 10}.
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>X = 1024, Y = 1
<strong>输出：</strong>1023
<strong>解释：</strong>执行递减运算 1023 次
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= X &lt;= 10^9</code></li>
	<li><code>1 &lt;= Y &lt;= 10^9</code></li>
</ol>

{% endraw %}

### 相关话题
  [[贪心](https://github.com/awesee/leetcode/tree/main/tag/greedy/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]

### 相似题目
  1. [只有两个键的键盘](/problems/2-keys-keyboard) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/broken-calculator)
