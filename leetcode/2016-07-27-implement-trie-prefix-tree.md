---
layout:     single
title:      "实现 Trie (前缀树)"
date:       2016-07-27 21:30:00 +0800
categories: [Leetcode]
tags:       [Design, Trie]
permalink:  /problems/implement-trie-prefix-tree/
---

## 208. 实现 Trie (前缀树) (Medium)

{% raw %}

<p>实现一个 Trie (前缀树)，包含&nbsp;<code>insert</code>,&nbsp;<code>search</code>, 和&nbsp;<code>startsWith</code>&nbsp;这三个操作。</p>

<p><strong>示例:</strong></p>

<pre>Trie trie = new Trie();

trie.insert(&quot;apple&quot;);
trie.search(&quot;apple&quot;);   // 返回 true
trie.search(&quot;app&quot;);     // 返回 false
trie.startsWith(&quot;app&quot;); // 返回 true
trie.insert(&quot;app&quot;);   
trie.search(&quot;app&quot;);     // 返回 true</pre>

<p><strong>说明:</strong></p>

<ul>
	<li>你可以假设所有的输入都是由小写字母&nbsp;<code>a-z</code>&nbsp;构成的。</li>
	<li>保证所有输入均为非空字符串。</li>
</ul>

{% endraw %}

### 相关话题
  [[设计](https://github.com/openset/leetcode/tree/master/tag/design/README.md)]
  [[字典树](https://github.com/openset/leetcode/tree/master/tag/trie/README.md)]

### 相似题目
  1. [添加与搜索单词 - 数据结构设计](/problems/design-add-and-search-words-data-structure) (Medium)
  1. [设计搜索自动补全系统](/problems/design-search-autocomplete-system) (Hard)
  1. [单词替换](/problems/replace-words) (Medium)
  1. [实现一个魔法字典](/problems/implement-magic-dictionary) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/implement-trie-prefix-tree)
