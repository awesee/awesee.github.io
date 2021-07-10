---
layout:     single
title:      "不同字符的最小子序列"
date:       2018-12-17 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Greedy, String, Monotonic Stack]
permalink:  /problems/smallest-subsequence-of-distinct-characters/
---

## 1081. 不同字符的最小子序列 (Medium)

{% raw %}

<p>返回 <code>s</code> 字典序最小的子序列，该子序列包含 <code>s</code> 的所有不同字符，且只包含一次。</p>

<p><strong>注意：</strong>该题与 316 <a href="https://leetcode.com/problems/remove-duplicate-letters/">https://leetcode.com/problems/remove-duplicate-letters/</a> 相同</p>

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
	<li><code>1 <= s.length <= 1000</code></li>
	<li><code>s</code> 由小写英文字母组成</li>
</ul>

{% endraw %}

### 相关话题
  [[栈](https://github.com/openset/leetcode/tree/master/tag/stack/README.md)]
  [[贪心](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[单调栈](https://github.com/openset/leetcode/tree/master/tag/monotonic-stack/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/smallest-subsequence-of-distinct-characters)
