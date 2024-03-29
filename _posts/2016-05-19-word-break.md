---
layout:     single
title:      "单词拆分"
date:       2016-05-19 21:30:00 +0800
categories: [Leetcode]
tags:       [Trie, Memoization, Hash Table, String, Dynamic Programming]
permalink:  /problems/word-break/
---

## 139. 单词拆分 (Medium)

{% raw %}

<p>给你一个字符串 <code>s</code> 和一个字符串列表 <code>wordDict</code> 作为字典，判定&nbsp;<code>s</code> 是否可以由空格拆分为一个或多个在字典中出现的单词。</p>

<p><strong>说明：</strong>拆分时可以重复使用字典中的单词。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入:</strong> s = "leetcode", wordDict = ["leet", "code"]
<strong>输出:</strong> true
<strong>解释:</strong> 返回 true 因为 "leetcode" 可以被拆分成 "leet code"。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入:</strong> s = "applepenapple", wordDict = ["apple", "pen"]
<strong>输出:</strong> true
<strong>解释:</strong> 返回 true 因为 <code>"</code>applepenapple<code>"</code> 可以被拆分成 <code>"</code>apple pen apple<code>"</code>。
&nbsp;    注意你可以重复使用字典中的单词。
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入:</strong> s = "catsandog", wordDict = ["cats", "dog", "sand", "and", "cat"]
<strong>输出:</strong> false
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= s.length &lt;= 300</code></li>
	<li><code>1 &lt;= wordDict.length &lt;= 1000</code></li>
	<li><code>1 &lt;= wordDict[i].length &lt;= 20</code></li>
	<li><code>s</code> 和 <code>wordDict[i]</code> 仅有小写英文字母组成</li>
	<li><code>wordDict</code> 中的所有字符串 <strong>互不相同</strong></li>
</ul>

{% endraw %}

### 相关话题
  [[字典树](https://github.com/awesee/leetcode/tree/main/tag/trie/README.md)]
  [[记忆化搜索](https://github.com/awesee/leetcode/tree/main/tag/memoization/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

### 相似题目
  1. [单词拆分 II](/problems/word-break-ii) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/word-break)
