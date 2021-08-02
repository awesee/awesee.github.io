---
layout:     single
title:      "字母异位词分组"
date:       2016-02-19 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, String, Sorting]
permalink:  /problems/group-anagrams/
---

## 49. 字母异位词分组 (Medium)

{% raw %}

<p>给定一个字符串数组，将字母异位词组合在一起。可以按任意顺序返回结果列表。</p>

<p>字母异位词指字母相同，但排列不同的字符串。</p>

<p> </p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> strs = <code>["eat", "tea", "tan", "ate", "nat", "bat"]</code>
<strong>输出: </strong>[["bat"],["nat","tan"],["ate","eat","tea"]]</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> strs = <code>[""]</code>
<strong>输出: </strong>[[""]]
</pre>

<p><strong>示例 3:</strong></p>

<pre>
<strong>输入:</strong> strs = <code>["a"]</code>
<strong>输出: </strong>[["a"]]</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= strs.length <= 10<sup>4</sup></code></li>
	<li><code>0 <= strs[i].length <= 100</code></li>
	<li><code>strs[i]</code> 仅包含小写字母</li>
</ul>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[排序](https://github.com/openset/leetcode/tree/master/tag/sorting/README.md)]

### 相似题目
  1. [有效的字母异位词](/problems/valid-anagram) (Easy)
  1. [移位字符串分组](/problems/group-shifted-strings) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/group-anagrams)
