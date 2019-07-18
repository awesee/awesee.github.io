---
layout:     single
title:      "前缀和后缀搜索"
date:       2018-01-15 21:30:00 +0800
categories: [Leetcode]
tags:       [Trie]
permalink:  /prefix-and-suffix-search/
---

## 745. 前缀和后缀搜索 (Hard)

{% raw %}

<p>给定多个&nbsp;<code>words</code>，<code>words[i]</code>&nbsp;的权重为&nbsp;<code>i</code>&nbsp;。</p>

<p>设计一个类&nbsp;<code>WordFilter</code>&nbsp;实现函数<code>WordFilter.f(String prefix, String suffix)</code>。这个函数将返回具有前缀&nbsp;<code>prefix</code>&nbsp;和后缀<code>suffix</code>&nbsp;的词的最大权重。如果没有这样的词，返回 -1。</p>

<p><strong>例子:</strong></p>

<pre>
<strong>输入:</strong>
WordFilter([&quot;apple&quot;])
WordFilter.f(&quot;a&quot;, &quot;e&quot;) // 返回 0
WordFilter.f(&quot;b&quot;, &quot;&quot;) // 返回 -1
</pre>

<p><strong>注意:</strong></p>

<ol>
	<li><code>words</code>的长度在<code>[1, 15000]</code>之间。</li>
	<li>对于每个测试用例，最多会有<code>words.length</code>次对<code>WordFilter.f</code>的调用。</li>
	<li><code>words[i]</code>的长度在<code>[1, 10]</code>之间。</li>
	<li><code>prefix, suffix</code>的长度在<code>[0, 10]</code>之前。</li>
	<li><code>words[i]</code>和<code>prefix, suffix</code>只包含小写字母。</li>
</ol>

{% endraw %}

### 相关话题
  [[字典树](https://github.com/openset/leetcode/tree/master/tag/trie/README.md)]

### 相似题目
  1. [添加与搜索单词 - 数据结构设计](/add-and-search-word-data-structure-design) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/prefix-and-suffix-search)
