---
layout:     single
title:      "求解方程"
date:       2017-10-02 21:30:00 +0800
categories: [Leetcode]
tags:       [Math, String, Simulation]
permalink:  /problems/solve-the-equation/
---

## 640. 求解方程 (Medium)

{% raw %}

<p>求解一个给定的方程，将<code>x</code>以字符串&quot;x=#value&quot;的形式返回。该方程仅包含&#39;+&#39;，&#39; - &#39;操作，变量&nbsp;<code>x</code>&nbsp;和其对应系数。</p>

<p>如果方程没有解，请返回&ldquo;No solution&rdquo;。</p>

<p>如果方程有无限解，则返回&ldquo;Infinite solutions&rdquo;。</p>

<p>如果方程中只有一个解，要保证返回值&nbsp;<code>x</code>&nbsp;是一个整数。</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入:</strong> &quot;x+5-3+x=6+x-2&quot;
<strong>输出:</strong> &quot;x=2&quot;
</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入:</strong> &quot;x=x&quot;
<strong>输出:</strong> &quot;Infinite solutions&quot;
</pre>

<p><strong>示例 3:</strong></p>

<pre><strong>输入:</strong> &quot;2x=x&quot;
<strong>输出:</strong> &quot;x=0&quot;
</pre>

<p><strong>示例 4:</strong></p>

<pre><strong>输入:</strong> &quot;2x+3x-6x=x+2&quot;
<strong>输出:</strong> &quot;x=-1&quot;
</pre>

<p><strong>示例 5:</strong></p>

<pre><strong>输入:</strong> &quot;x=x+2&quot;
<strong>输出:</strong> &quot;No solution&quot;
</pre>

{% endraw %}

### 相关话题
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[模拟](https://github.com/awesee/leetcode/tree/main/tag/simulation/README.md)]

### 相似题目
  1. [分数加减运算](/problems/fraction-addition-and-subtraction) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/solve-the-equation)
