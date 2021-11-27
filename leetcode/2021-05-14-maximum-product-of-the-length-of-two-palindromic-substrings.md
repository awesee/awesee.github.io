---
layout:     single
title:      "两个回文子字符串长度的最大乘积"
date:       2021-05-14 21:30:00 +0800
categories: [Leetcode]
tags:       [String, Hash Function, Rolling Hash]
permalink:  /problems/maximum-product-of-the-length-of-two-palindromic-substrings/
---

## 1960. 两个回文子字符串长度的最大乘积 (Hard)

{% raw %}

<p>给你一个下标从 <strong>0</strong>&nbsp;开始的字符串&nbsp;<code>s</code>&nbsp;，你需要找到两个 <strong>不重叠</strong><strong>的回文&nbsp;</strong>子字符串，它们的长度都必须为 <strong>奇数</strong>&nbsp;，使得它们长度的乘积最大。</p>

<p>更正式地，你想要选择四个整数&nbsp;<code>i</code>&nbsp;，<code>j</code>&nbsp;，<code>k</code>&nbsp;，<code>l</code>&nbsp;，使得&nbsp;<code>0 &lt;= i &lt;= j &lt; k &lt;= l &lt; s.length</code>&nbsp;，且子字符串&nbsp;<code>s[i...j]</code> 和&nbsp;<code>s[k...l]</code>&nbsp;都是回文串且长度为奇数。<code>s[i...j]</code>&nbsp;表示下标从 <code>i</code>&nbsp;到 <code>j</code>&nbsp;且 <strong>包含</strong>&nbsp;两端下标的子字符串。</p>

<p>请你返回两个不重叠回文子字符串长度的 <strong>最大</strong>&nbsp;乘积。</p>

<p><strong>回文字符串</strong>&nbsp;指的是一个从前往后读和从后往前读一模一样的字符串。<strong>子字符串</strong>&nbsp;指的是一个字符串中一段连续字符。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<b>输入：</b>s = "ababbb"
<b>输出：</b>9
<b>解释：</b>子字符串 "aba" 和 "bbb" 为奇数长度的回文串。乘积为 3 * 3 = 9 。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<b>输入：</b>s = "zaaaxbbby"
<b>输出：</b>9
<b>解释：</b>子字符串 "aaa" 和 "bbb" 为奇数长度的回文串。乘积为 3 * 3 = 9 。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>2 &lt;= s.length &lt;= 10<sup>5</sup></code></li>
	<li><code>s</code>&nbsp;只包含小写英文字母。</li>
</ul>

{% endraw %}

### 相关话题
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[哈希函数](https://github.com/awesee/leetcode/tree/main/tag/hash-function/README.md)]
  [[滚动哈希](https://github.com/awesee/leetcode/tree/main/tag/rolling-hash/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/maximum-product-of-the-length-of-two-palindromic-substrings)
