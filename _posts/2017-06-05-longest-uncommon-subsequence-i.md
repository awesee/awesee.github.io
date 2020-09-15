---
layout:     single
title:      "最长特殊序列 Ⅰ"
date:       2017-06-05 21:30:00 +0800
categories: [Leetcode]
tags:       [Brainteaser, String]
permalink:  /problems/longest-uncommon-subsequence-i/
---

## 521. 最长特殊序列 Ⅰ (Easy)

{% raw %}

<p>给你两个字符串，请你从这两个字符串中找出最长的特殊序列。</p>

<p>「最长特殊序列」定义如下：该序列为某字符串独有的最长子序列（即不能是其他字符串的子序列）。</p>

<p><strong>子序列</strong> 可以通过删去字符串中的某些字符实现，但不能改变剩余字符的相对顺序。空序列为所有字符串的子序列，任何字符串为其自身的子序列。</p>

<p>输入为两个字符串，输出最长特殊序列的长度。如果不存在，则返回 -1。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入:</strong> &quot;aba&quot;, &quot;cdc&quot;
<strong>输出:</strong> 3
<strong>解释:</strong> 最长特殊序列可为 &quot;aba&quot; (或 &quot;cdc&quot;)，两者均为自身的子序列且不是对方的子序列。</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>a = &quot;aaa&quot;, b = &quot;bbb&quot;
<strong>输出：</strong>3
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>a = &quot;aaa&quot;, b = &quot;aaa&quot;
<strong>输出：</strong>-1
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li>两个字符串长度均处于区间&nbsp;<code>[1 - 100]</code> 。</li>
	<li>字符串中的字符仅含有&nbsp;<code>&#39;a&#39;~&#39;z&#39;</code> 。</li>
</ol>

{% endraw %}

### 相关话题
  [[脑筋急转弯](https://github.com/openset/leetcode/tree/master/tag/brainteaser/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### 相似题目
  1. [最长特殊序列 II](/problems/longest-uncommon-subsequence-ii) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/longest-uncommon-subsequence-i)
