---
layout:     single
title:      "有效的字母异位词"
date:       2016-08-30 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, String, Sorting]
permalink:  /problems/valid-anagram/
---

## 242. 有效的字母异位词 (Easy)

{% raw %}

<p>给定两个字符串 <em>s</em> 和 <em>t</em> ，编写一个函数来判断 <em>t</em> 是否是 <em>s</em> 的字母异位词。</p>

<p> </p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> <em>s</em> = "anagram", <em>t</em> = "nagaram"
<strong>输出:</strong> true
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> <em>s</em> = "rat", <em>t</em> = "car"
<strong>输出: </strong>false</pre>

<p> </p>

<p><strong>提示:</strong></p>

<ul>
	<li><code>1 <= s.length, t.length <= 5 * 10<sup>4</sup></code></li>
	<li><code>s</code> 和 <code>t</code> 仅包含小写字母</li>
</ul>

<p> </p>

<p><strong>进阶: </strong>如果输入字符串包含 unicode 字符怎么办？你能否调整你的解法来应对这种情况？</p>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[排序](https://github.com/openset/leetcode/tree/master/tag/sorting/README.md)]

### 相似题目
  1. [字母异位词分组](/problems/group-anagrams) (Medium)
  1. [回文排列](/problems/palindrome-permutation) (Easy)
  1. [找到字符串中所有字母异位词](/problems/find-all-anagrams-in-a-string) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/valid-anagram)
