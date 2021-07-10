---
layout:     single
title:      "添加与搜索单词 - 数据结构设计"
date:       2016-07-30 21:30:00 +0800
categories: [Leetcode]
tags:       [Depth-First Search, Design, Trie, String]
permalink:  /problems/design-add-and-search-words-data-structure/
---

## 211. 添加与搜索单词 - 数据结构设计 (Medium)

{% raw %}

<p>请你设计一个数据结构，支持 添加新单词 和 查找字符串是否与任何先前添加的字符串匹配 。</p>

<p>实现词典类 <code>WordDictionary</code> ：</p>

<ul>
	<li><code>WordDictionary()</code> 初始化词典对象</li>
	<li><code>void addWord(word)</code> 将 <code>word</code> 添加到数据结构中，之后可以对它进行匹配</li>
	<li><code>bool search(word)</code> 如果数据结构中存在字符串与 <code>word</code> 匹配，则返回 <code>true</code> ；否则，返回  <code>false</code> 。<code>word</code> 中可能包含一些 <code>'.'</code> ，每个 <code>.</code> 都可以表示任何一个字母。</li>
</ul>

<p> </p>

<p><strong>示例：</strong></p>

<pre>
<strong>输入：</strong>
["WordDictionary","addWord","addWord","addWord","search","search","search","search"]
[[],["bad"],["dad"],["mad"],["pad"],["bad"],[".ad"],["b.."]]
<strong>输出：</strong>
[null,null,null,null,false,true,true,true]

<strong>解释：</strong>
WordDictionary wordDictionary = new WordDictionary();
wordDictionary.addWord("bad");
wordDictionary.addWord("dad");
wordDictionary.addWord("mad");
wordDictionary.search("pad"); // return False
wordDictionary.search("bad"); // return True
wordDictionary.search(".ad"); // return True
wordDictionary.search("b.."); // return True
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= word.length <= 500</code></li>
	<li><code>addWord</code> 中的 <code>word</code> 由小写英文字母组成</li>
	<li><code>search</code> 中的 <code>word</code> 由 '.' 或小写英文字母组成</li>
	<li>最多调用 <code>50000</code> 次 <code>addWord</code> 和 <code>search</code></li>
</ul>

{% endraw %}

### 相关话题
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[设计](https://github.com/openset/leetcode/tree/master/tag/design/README.md)]
  [[字典树](https://github.com/openset/leetcode/tree/master/tag/trie/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### 相似题目
  1. [实现 Trie (前缀树)](/problems/implement-trie-prefix-tree) (Medium)
  1. [前缀和后缀搜索](/problems/prefix-and-suffix-search) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/design-add-and-search-words-data-structure)
