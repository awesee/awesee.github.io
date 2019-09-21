---
layout:     single
title:      "键值映射"
date:       2017-11-08 21:30:00 +0800
categories: [Leetcode]
tags:       [Trie]
permalink:  /problems/map-sum-pairs/
---

## 677. 键值映射 (Medium)

{% raw %}

<p>实现一个 MapSum 类里的两个方法，<code>insert</code>&nbsp;和&nbsp;<code>sum</code>。</p>

<p>对于方法&nbsp;<code>insert</code>，你将得到一对（字符串，整数）的键值对。字符串表示键，整数表示值。如果键已经存在，那么原来的键值对将被替代成新的键值对。</p>

<p>对于方法 <code>sum</code>，你将得到一个表示前缀的字符串，你需要返回所有以该前缀开头的键的值的总和。</p>

<p><strong>示例 1:</strong></p>

<pre>输入: insert(&quot;apple&quot;, 3), 输出: Null
输入: sum(&quot;ap&quot;), 输出: 3
输入: insert(&quot;app&quot;, 2), 输出: Null
输入: sum(&quot;ap&quot;), 输出: 5
</pre>

{% endraw %}

### 相关话题
  [[字典树](https://github.com/openset/leetcode/tree/master/tag/trie/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/map-sum-pairs)
