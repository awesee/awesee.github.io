---
layout:     single
title:      "连接词"
date:       2017-04-17 21:30:00 +0800
categories: [Leetcode]
tags:       [Depth-First Search, Trie, String, Dynamic Programming]
permalink:  /problems/concatenated-words/
---

## 472. 连接词 (Hard)

{% raw %}

<p>给定一个 <strong>不含重复 </strong>单词的字符串数组 <code>words</code> ，编写一个程序，返回 <code>words</code> 中的所有 <strong>连接词</strong> 。</p>

<p><strong>连接词</strong> 的定义为：一个字符串完全是由至少两个给定数组中的单词组成的。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>words = ["cat","cats","catsdogcats","dog","dogcatsdog","hippopotamuses","rat","ratcatdogcat"]
<strong>输出：</strong>["catsdogcats","dogcatsdog","ratcatdogcat"]
<strong>解释：</strong>"catsdogcats"由"cats", "dog" 和 "cats"组成; 
     "dogcatsdog"由"dog", "cats"和"dog"组成; 
     "ratcatdogcat"由"rat", "cat", "dog"和"cat"组成。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>words = ["cat","dog","catdog"]
<strong>输出：</strong>["catdog"]</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= words.length <= 10<sup>4</sup></code></li>
	<li><code>0 <= words[i].length <= 1000</code></li>
	<li><code>words[i]</code> 仅由小写字母组成</li>
	<li><code>0 <= sum(words[i].length) <= 6 * 10<sup>5</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[字典树](https://github.com/awesee/leetcode/tree/main/tag/trie/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

### 相似题目
  1. [单词拆分 II](/problems/word-break-ii) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/concatenated-words)
