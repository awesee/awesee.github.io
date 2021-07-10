---
layout:     single
title:      "最短回文串"
date:       2016-08-02 21:30:00 +0800
categories: [Leetcode]
tags:       [String, String Matching, Hash Function, Rolling Hash]
permalink:  /problems/shortest-palindrome/
---

## 214. 最短回文串 (Hard)

{% raw %}

<p>给定一个字符串 <em><strong>s</strong></em>，你可以通过在字符串前面添加字符将其转换为回文串。找到并返回可以用这种方式转换的最短回文串。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>s = "aacecaaa"
<strong>输出：</strong>"aaacecaaa"
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>s = "abcd"
<strong>输出：</strong>"dcbabcd"
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 <= s.length <= 5 * 10<sup>4</sup></code></li>
	<li><code>s</code> 仅由小写英文字母组成</li>
</ul>

{% endraw %}

### 相关话题
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[字符串匹配](https://github.com/openset/leetcode/tree/master/tag/string-matching/README.md)]
  [[哈希函数](https://github.com/openset/leetcode/tree/master/tag/hash-function/README.md)]
  [[滚动哈希](https://github.com/openset/leetcode/tree/master/tag/rolling-hash/README.md)]

### 相似题目
  1. [最长回文子串](/problems/longest-palindromic-substring) (Medium)
  1. [实现 strStr()](/problems/implement-strstr) (Easy)
  1. [回文对](/problems/palindrome-pairs) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/shortest-palindrome)
