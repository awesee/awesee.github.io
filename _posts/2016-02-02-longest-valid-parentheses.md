---
layout:     single
title:      "最长有效括号"
date:       2016-02-02 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, String, Dynamic Programming]
permalink:  /problems/longest-valid-parentheses/
---

## 32. 最长有效括号 (Hard)

{% raw %}

<p>给你一个只包含 <code>'('</code> 和 <code>')'</code> 的字符串，找出最长有效（格式正确且连续）括号子串的长度。</p>

<p> </p>

<div class="original__bRMd">
<div>
<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>s = "(()"
<strong>输出：</strong>2
<strong>解释：</strong>最长有效括号子串是 "()"
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>s = ")()())"
<strong>输出：</strong>4
<strong>解释：</strong>最长有效括号子串是 "()()"
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>s = ""
<strong>输出：</strong>0
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 <= s.length <= 3 * 10<sup>4</sup></code></li>
	<li><code>s[i]</code> 为 <code>'('</code> 或 <code>')'</code></li>
</ul>
</div>
</div>

{% endraw %}

### 相关话题
  [[栈](https://github.com/openset/leetcode/tree/master/tag/stack/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### 相似题目
  1. [有效的括号](/problems/valid-parentheses) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/longest-valid-parentheses)
