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

<p><strong><a href="https://baike.baidu.com/item/字典树/9825209?fr=aladdin" target="_blank">Trie</a></strong>（发音类似 "try"）或者说 <strong>前缀树</strong> 是一种树形数据结构，用于高效地存储和检索字符串数据集中的键。这一数据结构有相当多的应用情景，例如自动补完和拼写检查。</p>

<p>请你实现 Trie 类：</p>

<ul>
	<li><code>Trie()</code> 初始化前缀树对象。</li>
	<li><code>void insert(String word)</code> 向前缀树中插入字符串 <code>word</code> 。</li>
	<li><code>boolean search(String word)</code> 如果字符串 <code>word</code> 在前缀树中，返回 <code>true</code>（即，在检索之前已经插入）；否则，返回 <code>false</code> 。</li>
	<li><code>boolean startsWith(String prefix)</code> 如果之前已经插入的字符串 <code>word</code> 的前缀之一为 <code>prefix</code> ，返回 <code>true</code> ；否则，返回 <code>false</code> 。</li>
</ul>

<p> </p>

<p><strong>示例：</strong></p>

<pre>
<strong>输入</strong>
["Trie", "insert", "search", "search", "startsWith", "insert", "search"]
[[], ["apple"], ["apple"], ["app"], ["app"], ["app"], ["app"]]
<strong>输出</strong>
[null, null, true, false, true, null, true]

<strong>解释</strong>
Trie trie = new Trie();
trie.insert("apple");
trie.search("apple");   // 返回 True
trie.search("app");     // 返回 False
trie.startsWith("app"); // 返回 True
trie.insert("app");
trie.search("app");     // 返回 True
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= word.length, prefix.length <= 2000</code></li>
	<li><code>word</code> 和 <code>prefix</code> 仅由小写英文字母组成</li>
	<li><code>insert</code>、<code>search</code> 和 <code>startsWith</code> 调用次数 <strong>总计</strong> 不超过 <code>3 * 10<sup>4</sup></code> 次</li>
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
