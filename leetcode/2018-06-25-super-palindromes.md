---
layout:     single
title:      "超级回文数"
date:       2018-06-25 21:30:00 +0800
categories: [Leetcode]
tags:       [Math, Enumeration]
permalink:  /problems/super-palindromes/
---

## 906. 超级回文数 (Hard)

{% raw %}

<p>如果一个正整数自身是回文数，而且它也是一个回文数的平方，那么我们称这个数为超级回文数。</p>

<p>现在，给定两个正整数&nbsp;<code>L</code> 和&nbsp;<code>R</code> （以字符串形式表示），返回包含在范围 <code>[L, R]</code> 中的超级回文数的数目。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>L = &quot;4&quot;, R = &quot;1000&quot;
<strong>输出：</strong>4
<strong>解释：
</strong>4，9，121，以及 484 是超级回文数。
注意 676 不是一个超级回文数： 26 * 26 = 676，但是 26 不是回文数。</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= len(L) &lt;= 18</code></li>
	<li><code>1 &lt;= len(R) &lt;= 18</code></li>
	<li><code>L</code> 和&nbsp;<code>R</code>&nbsp;是表示&nbsp;<code>[1, 10^18)</code>&nbsp;范围的整数的字符串。</li>
	<li><code>int(L) &lt;= int(R)</code></li>
</ol>

<p>&nbsp;</p>

{% endraw %}

### 相关话题
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[枚举](https://github.com/awesee/leetcode/tree/main/tag/enumeration/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/super-palindromes)
