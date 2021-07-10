---
layout:     single
title:      "字符串的最大公因子"
date:       2018-12-07 21:30:00 +0800
categories: [Leetcode]
tags:       [Math, String]
permalink:  /problems/greatest-common-divisor-of-strings/
---

## 1071. 字符串的最大公因子 (Easy)

{% raw %}

<p>对于字符串 <code>S</code> 和 <code>T</code>，只有在 <code>S = T + ... + T</code>（<code>T</code> 自身连接 1 次或多次）时，我们才认定 “<code>T</code> 能除尽 <code>S</code>”。</p>

<p>返回最长字符串 <code>X</code>，要求满足 <code>X</code> 能除尽 <code>str1</code> 且 <code>X</code> 能除尽 <code>str2</code>。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>str1 = "ABCABC", str2 = "ABC"
<strong>输出：</strong>"ABC"
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>str1 = "ABABAB", str2 = "ABAB"
<strong>输出：</strong>"AB"
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>str1 = "LEET", str2 = "CODE"
<strong>输出：</strong>""
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 <= str1.length <= 1000</code></li>
	<li><code>1 <= str2.length <= 1000</code></li>
	<li><code>str1[i]</code> 和 <code>str2[i]</code> 为大写英文字母</li>
</ol>

{% endraw %}

### 相关话题
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/greatest-common-divisor-of-strings)
