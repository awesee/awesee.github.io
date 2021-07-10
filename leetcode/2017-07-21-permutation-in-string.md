---
layout:     single
title:      "字符串的排列"
date:       2017-07-21 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, Two Pointers, String, Sliding Window]
permalink:  /problems/permutation-in-string/
---

## 567. 字符串的排列 (Medium)

{% raw %}

<p>给定两个字符串 <code>s1</code> 和 <code>s2</code>，写一个函数来判断 <code>s2</code> 是否包含 <code>s1</code><strong> </strong>的排列。</p>

<p>换句话说，第一个字符串的排列之一是第二个字符串的 <strong>子串</strong> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入: </strong>s1 = "ab" s2 = "eidbaooo"
<strong>输出: </strong>True
<strong>解释:</strong> s2 包含 s1 的排列之一 ("ba").
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入: </strong>s1= "ab" s2 = "eidboaoo"
<strong>输出:</strong> False
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>输入的字符串只包含小写字母</li>
	<li>两个字符串的长度都在 <code>[1, 10,000]</code> 之间</li>
</ul>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[双指针](https://github.com/openset/leetcode/tree/master/tag/two-pointers/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[滑动窗口](https://github.com/openset/leetcode/tree/master/tag/sliding-window/README.md)]

### 相似题目
  1. [最小覆盖子串](/problems/minimum-window-substring) (Hard)
  1. [找到字符串中所有字母异位词](/problems/find-all-anagrams-in-a-string) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/permutation-in-string)
