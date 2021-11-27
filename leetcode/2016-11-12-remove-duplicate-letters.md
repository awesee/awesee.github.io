---
layout:     single
title:      "去除重复字母"
date:       2016-11-12 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Greedy, String, Monotonic Stack]
permalink:  /problems/remove-duplicate-letters/
---

## 316. 去除重复字母 (Medium)

{% raw %}

<p>给你一个字符串 <code>s</code> ，请你去除字符串中重复的字母，使得每个字母只出现一次。需保证 <strong>返回结果的字典序最小</strong>（要求不能打乱其他字符的相对位置）。</p>

<p><strong>注意：</strong>该题与 1081 <a href="https://leetcode-cn.com/problems/smallest-subsequence-of-distinct-characters">https://leetcode-cn.com/problems/smallest-subsequence-of-distinct-characters</a> 相同</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong><code>s = "bcabc"</code>
<strong>输出<code>：</code></strong><code>"abc"</code>
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong><code>s = "cbacdcbc"</code>
<strong>输出：</strong><code>"acdb"</code></pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= s.length <= 10<sup>4</sup></code></li>
	<li><code>s</code> 由小写英文字母组成</li>
</ul>

{% endraw %}

### 相关话题
  [[栈](https://github.com/awesee/leetcode/tree/master/tag/stack/README.md)]
  [[贪心](https://github.com/awesee/leetcode/tree/master/tag/greedy/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/master/tag/string/README.md)]
  [[单调栈](https://github.com/awesee/leetcode/tree/master/tag/monotonic-stack/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/remove-duplicate-letters)
