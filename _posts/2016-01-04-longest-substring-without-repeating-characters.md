---
layout:     single
title:      "无重复字符的最长子串"
date:       2016-01-04 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, Two Pointers, String, Sliding Window]
permalink:  /problems/longest-substring-without-repeating-characters/
---

## 3. 无重复字符的最长子串 (Medium)

{% raw %}

<p>给定一个字符串，请你找出其中不含有重复字符的 <strong>最长子串 </strong>的长度。</p>

<p> </p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入: </strong>s = "abcabcbb"
<strong>输出: </strong>3 
<strong>解释:</strong> 因为无重复字符的最长子串是 <code>"abc"，所以其</code>长度为 3。
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入: </strong>s = "bbbbb"
<strong>输出: </strong>1
<strong>解释: </strong>因为无重复字符的最长子串是 <code>"b"</code>，所以其长度为 1。
</pre>

<p><strong>示例 3:</strong></p>

<pre>
<strong>输入: </strong>s = "pwwkew"
<strong>输出: </strong>3
<strong>解释: </strong>因为无重复字符的最长子串是 <code>"wke"</code>，所以其长度为 3。
     请注意，你的答案必须是 <strong>子串 </strong>的长度，<code>"pwke"</code> 是一个<em>子序列，</em>不是子串。
</pre>

<p><strong>示例 4:</strong></p>

<pre>
<strong>输入: </strong>s = ""
<strong>输出: </strong>0
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 <= s.length <= 5 * 10<sup>4</sup></code></li>
	<li><code>s</code> 由英文字母、数字、符号和空格组成</li>
</ul>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[双指针](https://github.com/openset/leetcode/tree/master/tag/two-pointers/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[Sliding Window](https://github.com/openset/leetcode/tree/master/tag/sliding-window/README.md)]

### 相似题目
  1. [至多包含两个不同字符的最长子串](/problems/longest-substring-with-at-most-two-distinct-characters) (Medium)
  1. [至多包含 K 个不同字符的最长子串](/problems/longest-substring-with-at-most-k-distinct-characters) (Medium)
  1. [K 个不同整数的子数组](/problems/subarrays-with-k-different-integers) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/longest-substring-without-repeating-characters)
