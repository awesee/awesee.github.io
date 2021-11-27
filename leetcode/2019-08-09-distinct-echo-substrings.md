---
layout:     single
title:      "不同的循环子字符串"
date:       2019-08-09 21:30:00 +0800
categories: [Leetcode]
tags:       [Trie, String, Dynamic Programming, Sliding Window, Hash Function, Rolling Hash]
permalink:  /problems/distinct-echo-substrings/
---

## 1316. 不同的循环子字符串 (Hard)

{% raw %}

<p>给你一个字符串&nbsp;<code>text</code> ，请你返回满足下述条件的&nbsp;<strong>不同</strong> 非空子字符串的数目：</p>

<ul>
	<li>可以写成某个字符串与其自身相连接的形式（即，可以写为 <code>a&nbsp;+ a</code>，其中 <code>a</code> 是某个字符串）。</li>
</ul>

<p>例如，<code>abcabc</code>&nbsp;就是&nbsp;<code>abc</code>&nbsp;和它自身连接形成的。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>text = &quot;abcabcabc&quot;
<strong>输出：</strong>3
<strong>解释：</strong>3 个子字符串分别为 &quot;abcabc&quot;，&quot;bcabca&quot; 和 &quot;cabcab&quot; 。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>text = &quot;leetcodeleetcode&quot;
<strong>输出：</strong>2
<strong>解释：</strong>2 个子字符串为 &quot;ee&quot; 和 &quot;leetcodeleetcode&quot; 。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= text.length &lt;= 2000</code></li>
	<li><code>text</code>&nbsp;只包含小写英文字母。</li>
</ul>

{% endraw %}

### 相关话题
  [[字典树](https://github.com/awesee/leetcode/tree/main/tag/trie/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[滑动窗口](https://github.com/awesee/leetcode/tree/main/tag/sliding-window/README.md)]
  [[哈希函数](https://github.com/awesee/leetcode/tree/main/tag/hash-function/README.md)]
  [[滚动哈希](https://github.com/awesee/leetcode/tree/main/tag/rolling-hash/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/distinct-echo-substrings)
