---
layout:     single
title:      "仅含 1 的子串数"
date:       2020-02-22 21:30:00 +0800
categories: [Leetcode]
tags:       [Math, String]
permalink:  /problems/number-of-substrings-with-only-1s/
---

## 1513. 仅含 1 的子串数 (Medium)

{% raw %}

<p>给你一个二进制字符串 <code>s</code>（仅由 &#39;0&#39; 和 &#39;1&#39; 组成的字符串）。</p>

<p>返回所有字符都为 1 的子字符串的数目。</p>

<p>由于答案可能很大，请你将它对 10^9 + 7 取模后返回。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>s = &quot;0110111&quot;
<strong>输出</strong>：9
<strong>解释：</strong>共有 9 个子字符串仅由 &#39;1&#39; 组成
&quot;1&quot; -&gt; 5 次
&quot;11&quot; -&gt; 3 次
&quot;111&quot; -&gt; 1 次</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>s = &quot;101&quot;
<strong>输出：</strong>2
<strong>解释：</strong>子字符串 &quot;1&quot; 在 s 中共出现 2 次
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>s = &quot;111111&quot;
<strong>输出：</strong>21
<strong>解释：</strong>每个子字符串都仅由 &#39;1&#39; 组成
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>s = &quot;000&quot;
<strong>输出：</strong>0
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>s[i] == &#39;0&#39;</code> 或 <code>s[i] == &#39;1&#39;</code></li>
	<li><code>1 &lt;= s.length &lt;= 10^5</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/number-of-substrings-with-only-1s)
