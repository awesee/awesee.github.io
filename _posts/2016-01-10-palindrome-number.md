---
layout:     single
title:      "回文数"
date:       2016-01-10 21:30:00 +0800
categories: [Leetcode]
tags:       [Math]
permalink:  /problems/palindrome-number/
---

## 9. 回文数 (Easy)

{% raw %}

<p>给你一个整数 <code>x</code> ，如果 <code>x</code> 是一个回文整数，返回 <code>ture</code> ；否则，返回 <code>false</code> 。</p>

<p>回文数是指正序（从左向右）和倒序（从右向左）读都是一样的整数。例如，<code>121</code> 是回文，而 <code>123</code> 不是。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>x = 121
<strong>输出：</strong>true
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>x = -121
<strong>输出：</strong>false
<strong>解释：</strong>从左向右读, 为 -121 。 从右向左读, 为 121- 。因此它不是一个回文数。
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>x = 10
<strong>输出：</strong>false
<strong>解释：</strong>从右向左读, 为 01 。因此它不是一个回文数。
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>x = -101
<strong>输出：</strong>false
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>-2<sup>31</sup> <= x <= 2<sup>31</sup> - 1</code></li>
</ul>

<p> </p>

<p><strong>进阶：</strong>你能不将整数转为字符串来解决这个问题吗？</p>

{% endraw %}

### 相关话题
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

### 相似题目
  1. [回文链表](/problems/palindrome-linked-list) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/palindrome-number)
