---
layout:     single
title:      "单词拆分 II"
date:       2016-05-20 21:30:00 +0800
categories: [Leetcode]
tags:       [Trie, Memoization, Hash Table, String, Dynamic Programming, Backtracking]
permalink:  /problems/word-break-ii/
---

## 140. 单词拆分 II (Hard)

{% raw %}

<p>给定一个<strong>非空</strong>字符串 <em>s</em> 和一个包含<strong>非空</strong>单词列表的字典 <em>wordDict</em>，在字符串中增加空格来构建一个句子，使得句子中所有的单词都在词典中。返回所有这些可能的句子。</p>

<p><strong>说明：</strong></p>

<ul>
	<li>分隔时可以重复使用字典中的单词。</li>
	<li>你可以假设字典中没有重复的单词。</li>
</ul>

<p><strong>示例 1：</strong></p>

<pre><strong>输入:
</strong>s = &quot;<code>catsanddog</code>&quot;
wordDict = <code>[&quot;cat&quot;, &quot;cats&quot;, &quot;and&quot;, &quot;sand&quot;, &quot;dog&quot;]</code>
<strong>输出:
</strong><code>[
&nbsp; &quot;cats and dog&quot;,
&nbsp; &quot;cat sand dog&quot;
]</code>
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入:
</strong>s = &quot;pineapplepenapple&quot;
wordDict = [&quot;apple&quot;, &quot;pen&quot;, &quot;applepen&quot;, &quot;pine&quot;, &quot;pineapple&quot;]
<strong>输出:
</strong>[
&nbsp; &quot;pine apple pen apple&quot;,
&nbsp; &quot;pineapple pen apple&quot;,
&nbsp; &quot;pine applepen apple&quot;
]
<strong>解释:</strong> 注意你可以重复使用字典中的单词。
</pre>

<p><strong>示例&nbsp;3：</strong></p>

<pre><strong>输入:
</strong>s = &quot;catsandog&quot;
wordDict = [&quot;cats&quot;, &quot;dog&quot;, &quot;sand&quot;, &quot;and&quot;, &quot;cat&quot;]
<strong>输出:
</strong>[]
</pre>

{% endraw %}

### 相关话题
  [[字典树](https://github.com/awesee/leetcode/tree/main/tag/trie/README.md)]
  [[记忆化搜索](https://github.com/awesee/leetcode/tree/main/tag/memoization/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[回溯](https://github.com/awesee/leetcode/tree/main/tag/backtracking/README.md)]

### 相似题目
  1. [单词拆分](/problems/word-break) (Medium)
  1. [连接词](/problems/concatenated-words) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/word-break-ii)
