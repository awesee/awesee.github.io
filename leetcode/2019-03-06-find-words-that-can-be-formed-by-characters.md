---
layout:     single
title:      "拼写单词"
date:       2019-03-06 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, String]
permalink:  /problems/find-words-that-can-be-formed-by-characters/
---

## 1160. 拼写单词 (Easy)

{% raw %}

<p>给你一份『词汇表』（字符串数组）&nbsp;<code>words</code>&nbsp;和一张『字母表』（字符串）&nbsp;<code>chars</code>。</p>

<p>假如你可以用&nbsp;<code>chars</code>&nbsp;中的『字母』（字符）拼写出 <code>words</code>&nbsp;中的某个『单词』（字符串），那么我们就认为你掌握了这个单词。</p>

<p>注意：每次拼写（指拼写词汇表中的一个单词）时，<code>chars</code> 中的每个字母都只能用一次。</p>

<p>返回词汇表&nbsp;<code>words</code>&nbsp;中你掌握的所有单词的 <strong>长度之和</strong>。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>words = [&quot;cat&quot;,&quot;bt&quot;,&quot;hat&quot;,&quot;tree&quot;], chars = &quot;atach&quot;
<strong>输出：</strong>6
<strong>解释： </strong>
可以形成字符串 &quot;cat&quot; 和 &quot;hat&quot;，所以答案是 3 + 3 = 6。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>words = [&quot;hello&quot;,&quot;world&quot;,&quot;leetcode&quot;], chars = &quot;welldonehoneyr&quot;
<strong>输出：</strong>10
<strong>解释：</strong>
可以形成字符串 &quot;hello&quot; 和 &quot;world&quot;，所以答案是 5 + 5 = 10。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= words.length &lt;= 1000</code></li>
	<li><code>1 &lt;= words[i].length, chars.length&nbsp;&lt;= 100</code></li>
	<li>所有字符串中都仅包含小写英文字母</li>
</ol>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/find-words-that-can-be-formed-by-characters)
