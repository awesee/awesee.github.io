---
layout:     single
title:      "回文对"
date:       2016-12-02 21:30:00 +0800
categories: [Leetcode]
tags:       [Trie, Array, Hash Table, String]
permalink:  /problems/palindrome-pairs/
---

## 336. 回文对 (Hard)

{% raw %}

<p>给定一组<strong> 互不相同</strong> 的单词， 找出所有<strong> 不同<em> </em></strong>的索引对 <code>(i, j)</code>，使得列表中的两个单词， <code>words[i] + words[j]</code> ，可拼接成回文串。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>words = ["abcd","dcba","lls","s","sssll"]
<strong>输出：</strong>[[0,1],[1,0],[3,2],[2,4]] 
<strong>解释：</strong>可拼接成的回文串为 <code>["dcbaabcd","abcddcba","slls","llssssll"]</code>
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>words = ["bat","tab","cat"]
<strong>输出：</strong>[[0,1],[1,0]] 
<strong>解释：</strong>可拼接成的回文串为 <code>["battab","tabbat"]</code></pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>words = ["a",""]
<strong>输出：</strong>[[0,1],[1,0]]
</pre>
 

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= words.length <= 5000</code></li>
	<li><code>0 <= words[i].length <= 300</code></li>
	<li><code>words[i]</code> 由小写英文字母组成</li>
</ul>

{% endraw %}

### 相关话题
  [[字典树](https://github.com/awesee/leetcode/tree/main/tag/trie/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

### 相似题目
  1. [最长回文子串](/problems/longest-palindromic-substring) (Medium)
  1. [最短回文串](/problems/shortest-palindrome) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/palindrome-pairs)
