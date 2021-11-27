---
layout:     single
title:      "检查是否所有字符出现次数相同"
date:       2021-04-25 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, String, Counting]
permalink:  /problems/check-if-all-characters-have-equal-number-of-occurrences/
---

## 1941. 检查是否所有字符出现次数相同 (Easy)

{% raw %}

<p>给你一个字符串 <code>s</code> ，如果 <code>s</code> 是一个 <strong>好</strong> 字符串，请你返回 <code>true</code> ，否则请返回 <code>false</code> 。</p>

<p>如果 <code>s</code> 中出现过的 <strong>所有</strong> 字符的出现次数 <strong>相同</strong> ，那么我们称字符串 <code>s</code> 是 <strong>好</strong> 字符串。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre><b>输入：</b>s = "abacbc"
<b>输出：</b>true
<b>解释：</b>s 中出现过的字符为 'a'，'b' 和 'c' 。s 中所有字符均出现 2 次。
</pre>

<p><strong>示例 2：</strong></p>

<pre><b>输入：</b>s = "aaabb"
<b>输出：</b>false
<b>解释：</b>s 中出现过的字符为 'a' 和 'b' 。
'a' 出现了 3 次，'b' 出现了 2 次，两者出现次数不同。
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= s.length &lt;= 1000</code></li>
	<li><code>s</code> 只包含小写英文字母。</li>
</ul>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/awesee/leetcode/tree/master/tag/hash-table/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/master/tag/string/README.md)]
  [[计数](https://github.com/awesee/leetcode/tree/master/tag/counting/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/check-if-all-characters-have-equal-number-of-occurrences)