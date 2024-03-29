---
layout:     single
title:      "计数二进制子串"
date:       2017-11-27 21:30:00 +0800
categories: [Leetcode]
tags:       [Two Pointers, String]
permalink:  /problems/count-binary-substrings/
---

## 696. 计数二进制子串 (Easy)

{% raw %}

<p>给定一个字符串 <code>s</code>，计算具有相同数量 0 和 1 的非空（连续）子字符串的数量，并且这些子字符串中的所有 0 和所有 1 都是连续的。</p>

<p>重复出现的子串要计算它们出现的次数。</p>

<p> </p>

<p><strong>示例 1 :</strong></p>

<pre>
<strong>输入:</strong> "00110011"
<strong>输出:</strong> 6
<strong>解释:</strong> 有6个子串具有相同数量的连续1和0：“0011”，“01”，“1100”，“10”，“0011” 和 “01”。

请注意，一些重复出现的子串要计算它们出现的次数。

另外，“00110011”不是有效的子串，因为所有的0（和1）没有组合在一起。
</pre>

<p><strong>示例 2 :</strong></p>

<pre>
<strong>输入:</strong> "10101"
<strong>输出:</strong> 4
<strong>解释:</strong> 有4个子串：“10”，“01”，“10”，“01”，它们具有相同数量的连续1和0。
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>s.length</code> 在1到50,000之间。</li>
	<li><code>s</code> 只包含“0”或“1”字符。</li>
</ul>

{% endraw %}

### 相关话题
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

### 相似题目
  1. [字符串的编码与解码](/problems/encode-and-decode-strings) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/count-binary-substrings)
