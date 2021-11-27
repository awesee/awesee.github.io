---
layout:     single
title:      "编辑距离"
date:       2016-03-13 21:30:00 +0800
categories: [Leetcode]
tags:       [String, Dynamic Programming]
permalink:  /problems/edit-distance/
---

## 72. 编辑距离 (Hard)

{% raw %}

<p>给你两个单词 <code>word1</code> 和 <code>word2</code>，请你计算出将 <code>word1</code> 转换成 <code>word2</code><em> </em>所使用的最少操作数 。</p>

<p>你可以对一个单词进行如下三种操作：</p>

<ul>
	<li>插入一个字符</li>
	<li>删除一个字符</li>
	<li>替换一个字符</li>
</ul>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>word1 = "horse", word2 = "ros"
<strong>输出：</strong>3
<strong>解释：</strong>
horse -> rorse (将 'h' 替换为 'r')
rorse -> rose (删除 'r')
rose -> ros (删除 'e')
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>word1 = "intention", word2 = "execution"
<strong>输出：</strong>5
<strong>解释：</strong>
intention -> inention (删除 't')
inention -> enention (将 'i' 替换为 'e')
enention -> exention (将 'n' 替换为 'x')
exention -> exection (将 'n' 替换为 'c')
exection -> execution (插入 'u')
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 <= word1.length, word2.length <= 500</code></li>
	<li><code>word1</code> 和 <code>word2</code> 由小写英文字母组成</li>
</ul>

{% endraw %}

### 相关话题
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

### 相似题目
  1. [相隔为 1 的编辑距离](/problems/one-edit-distance) (Medium)
  1. [两个字符串的删除操作](/problems/delete-operation-for-two-strings) (Medium)
  1. [两个字符串的最小ASCII删除和](/problems/minimum-ascii-delete-sum-for-two-strings) (Medium)
  1. [不相交的线](/problems/uncrossed-lines) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/edit-distance)
