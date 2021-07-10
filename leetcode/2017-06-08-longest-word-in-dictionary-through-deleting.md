---
layout:     single
title:      "通过删除字母匹配到字典里最长单词"
date:       2017-06-08 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Two Pointers, String, Sorting]
permalink:  /problems/longest-word-in-dictionary-through-deleting/
---

## 524. 通过删除字母匹配到字典里最长单词 (Medium)

{% raw %}

<p>给你一个字符串 <code>s</code> 和一个字符串数组 <code>dictionary</code> 作为字典，找出并返回字典中最长的字符串，该字符串可以通过删除 <code>s</code> 中的某些字符得到。</p>

<p>如果答案不止一个，返回长度最长且字典序最小的字符串。如果答案不存在，则返回空字符串。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>s = "abpcplea", dictionary = ["ale","apple","monkey","plea"]
<strong>输出：</strong>"apple"
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>s = "abpcplea", dictionary = ["a","b","c"]
<strong>输出：</strong>"a"
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= s.length <= 1000</code></li>
	<li><code>1 <= dictionary.length <= 1000</code></li>
	<li><code>1 <= dictionary[i].length <= 1000</code></li>
	<li><code>s</code> 和 <code>dictionary[i]</code> 仅由小写英文字母组成</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[双指针](https://github.com/openset/leetcode/tree/master/tag/two-pointers/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[排序](https://github.com/openset/leetcode/tree/master/tag/sorting/README.md)]

### 相似题目
  1. [词典中最长的单词](/problems/longest-word-in-dictionary) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/longest-word-in-dictionary-through-deleting)
