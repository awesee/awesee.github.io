---
layout:     single
title:      "最长字符串链"
date:       2018-11-14 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, Two Pointers, String, Dynamic Programming]
permalink:  /problems/longest-string-chain/
---

## 1048. 最长字符串链 (Medium)

{% raw %}

<p>给出一个单词列表，其中每个单词都由小写英文字母组成。</p>

<p>如果我们可以在&nbsp;<code>word1</code>&nbsp;的任何地方添加一个字母使其变成&nbsp;<code>word2</code>，那么我们认为&nbsp;<code>word1</code>&nbsp;是&nbsp;<code>word2</code>&nbsp;的前身。例如，<code>&quot;abc&quot;</code>&nbsp;是&nbsp;<code>&quot;abac&quot;</code>&nbsp;的前身。</p>

<p><strong>词链</strong>是单词&nbsp;<code>[word_1, word_2, ..., word_k]</code>&nbsp;组成的序列，<code>k &gt;= 1</code>，其中&nbsp;<code>word_1</code>&nbsp;是&nbsp;<code>word_2</code>&nbsp;的前身，<code>word_2</code>&nbsp;是&nbsp;<code>word_3</code>&nbsp;的前身，依此类推。</p>

<p>从给定单词列表 <code>words</code> 中选择单词组成词链，返回词链的最长可能长度。<br>
&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>[&quot;a&quot;,&quot;b&quot;,&quot;ba&quot;,&quot;bca&quot;,&quot;bda&quot;,&quot;bdca&quot;]
<strong>输出：</strong>4
<strong>解释：</strong>最长单词链之一为 &quot;a&quot;,&quot;ba&quot;,&quot;bda&quot;,&quot;bdca&quot;。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= words.length &lt;= 1000</code></li>
	<li><code>1 &lt;= words[i].length &lt;= 16</code></li>
	<li><code>words[i]</code>&nbsp;仅由小写英文字母组成。</li>
</ol>

<p>&nbsp;</p>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/longest-string-chain)
