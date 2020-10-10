---
layout:     single
title:      "重复叠加字符串匹配"
date:       2017-11-17 21:30:00 +0800
categories: [Leetcode]
tags:       [String]
permalink:  /problems/repeated-string-match/
---

## 686. 重复叠加字符串匹配 (Medium)

{% raw %}

<p>给定两个字符串&nbsp;<code>a</code> 和 <code>b</code>，寻找重复叠加字符串 <code>a</code> 的最小次数，使得字符串 <code>b</code> 成为叠加后的字符串 <code>a</code> 的子串，如果不存在则返回 <code>-1</code>。</p>

<p><strong>注意：</strong>字符串 <code>&quot;abc&quot;</code>&nbsp;重复叠加 0 次是 <code>&quot;&quot;</code>，重复叠加 1 次是&nbsp;<code>&quot;abc&quot;</code>，重复叠加 2 次是&nbsp;<code>&quot;abcabc&quot;</code>。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>a = &quot;abcd&quot;, b = &quot;cdabcdab&quot;
<strong>输出：</strong>3
<strong>解释：</strong>a 重复叠加三遍后为 &quot;ab<strong>cdabcdab</strong>cd&quot;, 此时 b 是其子串。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>a = &quot;a&quot;, b = &quot;aa&quot;
<strong>输出：</strong>2
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>a = &quot;a&quot;, b = &quot;a&quot;
<strong>输出：</strong>1
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>a = &quot;abc&quot;, b = &quot;wxyz&quot;
<strong>输出：</strong>-1
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= a.length &lt;= 10<sup>4</sup></code></li>
	<li><code>1 &lt;= b.length &lt;= 10<sup>4</sup></code></li>
	<li><code>a</code> 和 <code>b</code> 由小写英文字母组成</li>
</ul>

{% endraw %}

### 相关话题
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### 相似题目
  1. [重复的子字符串](/problems/repeated-substring-pattern) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/repeated-string-match)
