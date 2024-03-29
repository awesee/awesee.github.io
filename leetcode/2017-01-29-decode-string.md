---
layout:     single
title:      "字符串解码"
date:       2017-01-29 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Recursion, String]
permalink:  /problems/decode-string/
---

## 394. 字符串解码 (Medium)

{% raw %}

<p>给定一个经过编码的字符串，返回它解码后的字符串。</p>

<p>编码规则为: <code>k[encoded_string]</code>，表示其中方括号内部的 <em>encoded_string</em> 正好重复 <em>k</em> 次。注意 <em>k</em> 保证为正整数。</p>

<p>你可以认为输入字符串总是有效的；输入字符串中没有额外的空格，且输入的方括号总是符合格式要求的。</p>

<p>此外，你可以认为原始数据不包含数字，所有的数字只表示重复的次数 <em>k</em> ，例如不会出现像&nbsp;<code>3a</code>&nbsp;或&nbsp;<code>2[4]</code>&nbsp;的输入。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>s = &quot;3[a]2[bc]&quot;
<strong>输出：</strong>&quot;aaabcbc&quot;
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>s = &quot;3[a2[c]]&quot;
<strong>输出：</strong>&quot;accaccacc&quot;
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>s = &quot;2[abc]3[cd]ef&quot;
<strong>输出：</strong>&quot;abcabccdcdcdef&quot;
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>s = &quot;abc3[cd]xyz&quot;
<strong>输出：</strong>&quot;abccdcdcdxyz&quot;
</pre>

{% endraw %}

### 相关话题
  [[栈](https://github.com/awesee/leetcode/tree/main/tag/stack/README.md)]
  [[递归](https://github.com/awesee/leetcode/tree/main/tag/recursion/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

### 相似题目
  1. [编码最短长度的字符串](/problems/encode-string-with-shortest-length) (Hard)
  1. [原子的数量](/problems/number-of-atoms) (Hard)
  1. [花括号展开](/problems/brace-expansion) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/decode-string)
