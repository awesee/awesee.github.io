---
layout:     single
title:      "替换后的最长重复字符"
date:       2017-02-28 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, String, Sliding Window]
permalink:  /problems/longest-repeating-character-replacement/
---

## 424. 替换后的最长重复字符 (Medium)

{% raw %}

<p>给你一个仅由大写英文字母组成的字符串，你可以将任意位置上的字符替换成另外的字符，总共可最多替换 <em>k </em>次。在执行上述操作后，找到包含重复字母的最长子串的长度。</p>

<p><strong>注意：</strong>字符串长度 和 <em>k </em>不会超过 10<sup>4</sup>。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>s = "ABAB", k = 2
<strong>输出：</strong>4
<strong>解释：</strong>用两个'A'替换为两个'B',反之亦然。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>s = "AABABBA", k = 1
<strong>输出：</strong>4
<strong>解释：</strong>
将中间的一个'A'替换为'B',字符串变为 "AABBBBA"。
子串 "BBBB" 有最长重复字母, 答案为 4。
</pre>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/awesee/leetcode/tree/master/tag/hash-table/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/master/tag/string/README.md)]
  [[滑动窗口](https://github.com/awesee/leetcode/tree/master/tag/sliding-window/README.md)]

### 相似题目
  1. [至多包含 K 个不同字符的最长子串](/problems/longest-substring-with-at-most-k-distinct-characters) (Medium)
  1. [最大连续1的个数 III](/problems/max-consecutive-ones-iii) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/longest-repeating-character-replacement)
