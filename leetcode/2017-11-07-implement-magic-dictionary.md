---
layout:     single
title:      "实现一个魔法字典"
date:       2017-11-07 21:30:00 +0800
categories: [leetcode]
tags:       [trie, hash-table]
permalink:  /implement-magic-dictionary/
---

## 676. 实现一个魔法字典 (Medium)

<p>实现一个带有<code>buildDict</code>, 以及&nbsp;<code>search</code>方法的魔法字典。</p>

<p>对于<code>buildDict</code>方法，你将被给定一串不重复的单词来构建一个字典。</p>

<p>对于<code>search</code>方法，你将被给定一个单词，并且判定能否只将这个单词中<strong>一个</strong>字母换成另一个字母，使得所形成的新单词存在于你构建的字典中。</p>

<p><strong>示例 1:</strong></p>

<pre>
Input: buildDict([&quot;hello&quot;, &quot;leetcode&quot;]), Output: Null
Input: search(&quot;hello&quot;), Output: False
Input: search(&quot;hhllo&quot;), Output: True
Input: search(&quot;hell&quot;), Output: False
Input: search(&quot;leetcoded&quot;), Output: False
</pre>

<p><strong>注意:</strong></p>

<ol>
	<li>你可以假设所有输入都是小写字母&nbsp;<code>a-z</code>。</li>
	<li>为了便于竞赛，测试所用的数据量很小。你可以在竞赛结束后，考虑更高效的算法。</li>
	<li>请记住<strong>重置</strong>MagicDictionary类中声明的类变量，因为静态/类变量会在多个测试用例中保留。 请参阅<a href="http://leetcode.com/faq/#different-output">这里</a>了解更多详情。</li>
</ol>

### 相关话题
  [[字典树](https://github.com/openset/leetcode/tree/master/tag/trie/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]

### 相似题目
  1. [实现 Trie (前缀树)](/implement-trie-prefix-tree) (Medium)
  1. [词典中最长的单词](/longest-word-in-dictionary) (Easy)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/implement-magic-dictionary)