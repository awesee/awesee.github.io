---
layout:     single
title:      "匹配子序列的单词数"
date:       2018-03-03 21:30:00 +0800
categories: [Leetcode]
tags:       [Trie, Hash Table, String, Sorting]
permalink:  /problems/number-of-matching-subsequences/
---

## 792. 匹配子序列的单词数 (Medium)

{% raw %}

<p>给定字符串 <code>S</code> 和单词字典 <code>words</code>, 求&nbsp;<code>words[i]</code>&nbsp;中是&nbsp;<code>S</code>&nbsp;的子序列的单词个数。</p>

<pre>
<strong>示例:</strong>
<strong>输入:</strong> 
S = &quot;abcde&quot;
words = [&quot;a&quot;, &quot;bb&quot;, &quot;acd&quot;, &quot;ace&quot;]
<strong>输出:</strong> 3
<strong>解释:</strong> 有三个是&nbsp;S 的子序列的单词: &quot;a&quot;, &quot;acd&quot;, &quot;ace&quot;。
</pre>

<p><strong>注意:</strong></p>

<ul>
	<li>所有在<code>words</code>和&nbsp;<code>S</code>&nbsp;里的单词都只由小写字母组成。</li>
	<li><code>S</code> 的长度在&nbsp;<code>[1, 50000]</code>。</li>
	<li><code>words</code>&nbsp;的长度在&nbsp;<code>[1, 5000]</code>。</li>
	<li><code>words[i]</code>的长度在<code>[1, 50]</code>。</li>
</ul>

{% endraw %}

### 相关话题
  [[字典树](https://github.com/awesee/leetcode/tree/main/tag/trie/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]

### 相似题目
  1. [判断子序列](/problems/is-subsequence) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/number-of-matching-subsequences)
