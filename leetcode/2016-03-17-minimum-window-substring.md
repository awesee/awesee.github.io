---
layout:     single
title:      "最小覆盖子串"
date:       2016-03-17 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, String, Sliding Window]
permalink:  /problems/minimum-window-substring/
---

## 76. 最小覆盖子串 (Hard)

{% raw %}

<p>给你一个字符串 <code>s</code> 、一个字符串 <code>t</code> 。返回 <code>s</code> 中涵盖 <code>t</code> 所有字符的最小子串。如果 <code>s</code> 中不存在涵盖 <code>t</code> 所有字符的子串，则返回空字符串 <code>""</code> 。</p>

<p> </p>

<p><strong>注意：</strong></p>

<ul>
	<li>对于 <code>t</code> 中重复字符，我们寻找的子字符串中该字符数量必须不少于 <code>t</code> 中该字符数量。</li>
	<li>如果 <code>s</code> 中存在这样的子串，我们保证它是唯一的答案。</li>
</ul>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>s = "ADOBECODEBANC", t = "ABC"
<strong>输出：</strong>"BANC"
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>s = "a", t = "a"
<strong>输出：</strong>"a"
</pre>

<p><strong>示例 3:</strong></p>

<pre>
<strong>输入:</strong> s = "a", t = "aa"
<strong>输出:</strong> ""
<strong>解释:</strong> t 中两个字符 'a' 均应包含在 s 的子串中，
因此没有符合条件的子字符串，返回空字符串。</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= s.length, t.length <= 10<sup>5</sup></code></li>
	<li><code>s</code> 和 <code>t</code> 由英文字母组成</li>
</ul>

<p> </p>
<strong>进阶：</strong>你能设计一个在 <code>o(n)</code> 时间内解决此问题的算法吗？

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[滑动窗口](https://github.com/openset/leetcode/tree/master/tag/sliding-window/README.md)]

### 相似题目
  1. [串联所有单词的子串](/problems/substring-with-concatenation-of-all-words) (Hard)
  1. [长度最小的子数组](/problems/minimum-size-subarray-sum) (Medium)
  1. [滑动窗口最大值](/problems/sliding-window-maximum) (Hard)
  1. [字符串的排列](/problems/permutation-in-string) (Medium)
  1. [最小窗口子序列](/problems/minimum-window-subsequence) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/minimum-window-substring)
