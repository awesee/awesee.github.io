---
layout:     single
title:      "72. 编辑距离 (Hard)"
date:       2016-03-13 21:30:00 +0800
categories: [leetcode]
tags:       [string, dynamic-programming]
permalink:  /edit-distance/
---

<p>给定两个单词&nbsp;<em>word1</em> 和&nbsp;<em>word2</em>，计算出将&nbsp;<em>word1</em>&nbsp;转换成&nbsp;<em>word2 </em>所使用的最少操作数&nbsp;。</p>

<p>你可以对一个单词进行如下三种操作：</p>

<ol>
	<li>插入一个字符</li>
	<li>删除一个字符</li>
	<li>替换一个字符</li>
</ol>

<p><strong>示例&nbsp;1:</strong></p>

<pre><strong>输入:</strong> word1 = &quot;horse&quot;, word2 = &quot;ros&quot;
<strong>输出:</strong> 3
<strong>解释:</strong> 
horse -&gt; rorse (将 &#39;h&#39; 替换为 &#39;r&#39;)
rorse -&gt; rose (删除 &#39;r&#39;)
rose -&gt; ros (删除 &#39;e&#39;)
</pre>

<p><strong>示例&nbsp;2:</strong></p>

<pre><strong>输入:</strong> word1 = &quot;intention&quot;, word2 = &quot;execution&quot;
<strong>输出:</strong> 5
<strong>解释:</strong> 
intention -&gt; inention (删除 &#39;t&#39;)
inention -&gt; enention (将 &#39;i&#39; 替换为 &#39;e&#39;)
enention -&gt; exention (将 &#39;n&#39; 替换为 &#39;x&#39;)
exention -&gt; exection (将 &#39;n&#39; 替换为 &#39;c&#39;)
exection -&gt; execution (插入 &#39;u&#39;)
</pre>

### 相关话题
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### 相似题目
  1. [One Edit Distance](/one-edit-distance) (Medium)
  1. [两个字符串的删除操作](/delete-operation-for-two-strings) (Medium)
  1. [两个字符串的最小ASCII删除和](/minimum-ascii-delete-sum-for-two-strings) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/edit-distance)
