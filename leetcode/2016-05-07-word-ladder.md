---
layout:     single
title:      "单词接龙"
date:       2016-05-07 21:30:00 +0800
categories: [Leetcode]
tags:       [Breadth-First Search, Hash Table, String]
permalink:  /problems/word-ladder/
---

## 127. 单词接龙 (Hard)

{% raw %}

<p>字典 <code>wordList</code> 中从单词 <code>beginWord</code><em> </em>和 <code>endWord</code> 的 <strong>转换序列 </strong>是一个按下述规格形成的序列：</p>

<ul>
	<li>序列中第一个单词是 <code>beginWord</code> 。</li>
	<li>序列中最后一个单词是 <code>endWord</code> 。</li>
	<li>每次转换只能改变一个字母。</li>
	<li>转换过程中的中间单词必须是字典 <code>wordList</code> 中的单词。</li>
</ul>

<p>给你两个单词<em> </em><code>beginWord</code><em> </em>和 <code>endWord</code> 和一个字典 <code>wordList</code> ，找到从 <code>beginWord</code> 到 <code>endWord</code> 的 <strong>最短转换序列</strong> 中的 <strong>单词数目</strong> 。如果不存在这样的转换序列，返回 0。</p>
 

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>beginWord = "hit", endWord = "cog", wordList = ["hot","dot","dog","lot","log","cog"]
<strong>输出：</strong>5
<strong>解释：</strong>一个最短转换序列是 "hit" -> "hot" -> "dot" -> "dog" -> "cog", 返回它的长度 5。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>beginWord = "hit", endWord = "cog", wordList = ["hot","dot","dog","lot","log"]
<strong>输出：</strong>0
<strong>解释：</strong>endWord "cog" 不在字典中，所以无法进行转换。</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= beginWord.length <= 10</code></li>
	<li><code>endWord.length == beginWord.length</code></li>
	<li><code>1 <= wordList.length <= 5000</code></li>
	<li><code>wordList[i].length == beginWord.length</code></li>
	<li><code>beginWord</code>、<code>endWord</code> 和 <code>wordList[i]</code> 由小写英文字母组成</li>
	<li><code>beginWord != endWord</code></li>
	<li><code>wordList</code> 中的所有字符串 <strong>互不相同</strong></li>
</ul>

{% endraw %}

### 相关话题
  [[广度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/breadth-first-search/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

### 相似题目
  1. [单词接龙 II](/problems/word-ladder-ii) (Hard)
  1. [最小基因变化](/problems/minimum-genetic-mutation) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/word-ladder)
