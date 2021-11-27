---
layout:     single
title:      "赎金信"
date:       2017-01-18 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, String, Counting]
permalink:  /problems/ransom-note/
---

## 383. 赎金信 (Easy)

{% raw %}

<p>给定一个赎金信 (<code>ransom</code>) 字符串和一个杂志(<code>magazine</code>)字符串，判断第一个字符串 <code>ransom</code> 能不能由第二个字符串 <code>magazines</code> 里面的字符构成。如果可以构成，返回 <code>true</code> ；否则返回 <code>false</code>。</p>

<p>(题目说明：为了不暴露赎金信字迹，要从杂志上搜索各个需要的字母，组成单词来表达意思。杂志字符串中的每个字符只能在赎金信字符串中使用一次。)</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>ransomNote = "a", magazine = "b"
<strong>输出：</strong>false
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>ransomNote = "aa", magazine = "ab"
<strong>输出：</strong>false
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>ransomNote = "aa", magazine = "aab"
<strong>输出：</strong>true
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>你可以假设两个字符串均只含有小写字母。</li>
</ul>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[计数](https://github.com/awesee/leetcode/tree/main/tag/counting/README.md)]

### 相似题目
  1. [贴纸拼词](/problems/stickers-to-spell-word) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/ransom-note)
