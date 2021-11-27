---
layout:     single
title:      "第K个语法符号"
date:       2018-02-18 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Recursion, Math]
permalink:  /problems/k-th-symbol-in-grammar/
---

## 779. 第K个语法符号 (Medium)

{% raw %}

<p>在第一行我们写上一个 <code>0</code>。接下来的每一行，将前一行中的<code>0</code>替换为<code>01</code>，<code>1</code>替换为<code>10</code>。</p>

<p>给定行数&nbsp;<code>N</code>&nbsp;和序数 <code>K</code>，返回第 <code>N</code> 行中第 <code>K</code>个字符。（<code>K</code>从1开始）</p>

<p><br>
<strong>例子:</strong></p>

<pre><strong>输入:</strong> N = 1, K = 1
<strong>输出:</strong> 0

<strong>输入:</strong> N = 2, K = 1
<strong>输出:</strong> 0

<strong>输入:</strong> N = 2, K = 2
<strong>输出:</strong> 1

<strong>输入:</strong> N = 4, K = 5
<strong>输出:</strong> 1

<strong>解释:</strong>
第一行: 0
第二行: 01
第三行: 0110
第四行: 01101001
</pre>

<p><br>
<strong>注意：</strong></p>

<ol>
	<li><code>N</code>&nbsp;的范围&nbsp;<code>[1, 30]</code>.</li>
	<li><code>K</code>&nbsp;的范围&nbsp;<code>[1, 2^(N-1)]</code>.</li>
</ol>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[递归](https://github.com/awesee/leetcode/tree/main/tag/recursion/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/k-th-symbol-in-grammar)
