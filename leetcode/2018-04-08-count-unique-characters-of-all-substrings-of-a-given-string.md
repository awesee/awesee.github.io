---
layout:     single
title:      "统计子串中的唯一字符"
date:       2018-04-08 21:30:00 +0800
categories: [Leetcode]
tags:       [String, Dynamic Programming]
permalink:  /problems/count-unique-characters-of-all-substrings-of-a-given-string/
---

## 828. 统计子串中的唯一字符 (Hard)

{% raw %}

<p>我们定义了一个函数 <code>countUniqueChars(s)</code> 来统计字符串 <code>s</code> 中的唯一字符，并返回唯一字符的个数。</p>

<p>例如：<code>s = "LEETCODE"</code> ，则其中 <code>"L"</code>, <code>"T"</code>,<code>"C"</code>,<code>"O"</code>,<code>"D"</code> 都是唯一字符，因为它们只出现一次，所以 <code>countUniqueChars(s) = 5</code> 。</p>

<p>本题将会给你一个字符串 <code>s</code> ，我们需要返回 <code>countUniqueChars(t)</code> 的总和，其中 <code>t</code> 是 <code>s</code> 的子字符串。注意，某些子字符串可能是重复的，但你统计时也必须算上这些重复的子字符串（也就是说，你必须统计 <code>s</code> 的所有子字符串中的唯一字符）。</p>

<p>由于答案可能非常大，请将结果 <strong>mod 10 ^ 9 + 7</strong> 后再返回。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入: </strong>s = "ABC"
<strong>输出: </strong>10
<strong>解释:</strong> 所有可能的子串为："A","B","C","AB","BC" 和 "ABC"。
     其中，每一个子串都由独特字符构成。
     所以其长度总和为：1 + 1 + 1 + 2 + 2 + 3 = 10
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入: </strong>s = "ABA"
<strong>输出: </strong>8
<strong>解释: </strong>除<code>了 countUniqueChars</code>("ABA") = 1 之外，其余与示例 1 相同。
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>s = "LEETCODE"
<strong>输出：</strong>92
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 <= s.length <= 10^4</code></li>
	<li><code>s</code> 只包含大写英文字符</li>
</ul>

{% endraw %}

### 相关话题
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/count-unique-characters-of-all-substrings-of-a-given-string)
