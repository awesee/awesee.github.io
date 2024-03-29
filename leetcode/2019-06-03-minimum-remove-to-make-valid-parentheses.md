---
layout:     single
title:      "移除无效的括号"
date:       2019-06-03 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, String]
permalink:  /problems/minimum-remove-to-make-valid-parentheses/
---

## 1249. 移除无效的括号 (Medium)

{% raw %}

<p>给你一个由 <code>&#39;(&#39;</code>、<code>&#39;)&#39;</code> 和小写字母组成的字符串 <code>s</code>。</p>

<p>你需要从字符串中删除最少数目的 <code>&#39;(&#39;</code> 或者 <code>&#39;)&#39;</code>&nbsp;（可以删除任意位置的括号)，使得剩下的「括号字符串」有效。</p>

<p>请返回任意一个合法字符串。</p>

<p>有效「括号字符串」应当符合以下&nbsp;<strong>任意一条&nbsp;</strong>要求：</p>

<ul>
	<li>空字符串或只包含小写字母的字符串</li>
	<li>可以被写作&nbsp;<code>AB</code>（<code>A</code>&nbsp;连接&nbsp;<code>B</code>）的字符串，其中&nbsp;<code>A</code>&nbsp;和&nbsp;<code>B</code>&nbsp;都是有效「括号字符串」</li>
	<li>可以被写作&nbsp;<code>(A)</code>&nbsp;的字符串，其中&nbsp;<code>A</code>&nbsp;是一个有效的「括号字符串」</li>
</ul>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>s = &quot;lee(t(c)o)de)&quot;
<strong>输出：</strong>&quot;lee(t(c)o)de&quot;
<strong>解释：</strong>&quot;lee(t(co)de)&quot; , &quot;lee(t(c)ode)&quot; 也是一个可行答案。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>s = &quot;a)b(c)d&quot;
<strong>输出：</strong>&quot;ab(c)d&quot;
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>s = &quot;))((&quot;
<strong>输出：</strong>&quot;&quot;
<strong>解释：</strong>空字符串也是有效的
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>s = &quot;(a(b(c)d)&quot;
<strong>输出：</strong>&quot;a(b(c)d)&quot;
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= s.length &lt;= 10^5</code></li>
	<li><code>s[i]</code>&nbsp;可能是&nbsp;<code>&#39;(&#39;</code>、<code>&#39;)&#39;</code>&nbsp;或英文小写字母</li>
</ul>

{% endraw %}

### 相关话题
  [[栈](https://github.com/awesee/leetcode/tree/main/tag/stack/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/minimum-remove-to-make-valid-parentheses)
