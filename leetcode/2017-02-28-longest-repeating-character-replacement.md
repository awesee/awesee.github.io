---
layout:     single
title:      "替换后的最长重复字符"
date:       2017-02-28 21:30:00 +0800
categories: [Leetcode]
tags:       [Two Pointers, Sliding Window]
permalink:  /longest-repeating-character-replacement/
---

## 424. 替换后的最长重复字符 (Medium)

<p>给你一个仅由大写英文字母组成的字符串，你可以将任意位置上的字符替换成另外的字符，总共可最多替换&nbsp;<em>k&nbsp;</em>次。在执行上述操作后，找到包含重复字母的最长子串的长度。</p>

<p><strong>注意:</strong><br>
字符串长度 和 <em>k </em>不会超过&nbsp;10<sup>4</sup>。</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入:</strong>
s = &quot;ABAB&quot;, k = 2

<strong>输出:</strong>
4

<strong>解释:</strong>
用两个&#39;A&#39;替换为两个&#39;B&#39;,反之亦然。
</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入:</strong>
s = &quot;AABABBA&quot;, k = 1

<strong>输出:</strong>
4

<strong>解释:</strong>
将中间的一个&#39;A&#39;替换为&#39;B&#39;,字符串变为 &quot;AABBBBA&quot;。
子串 &quot;BBBB&quot; 有最长重复字母, 答案为 4。
</pre>

### 相关话题
  [[双指针](https://github.com/openset/leetcode/tree/master/tag/two-pointers/README.md)]
  [[Sliding Window](https://github.com/openset/leetcode/tree/master/tag/sliding-window/README.md)]

### 相似题目
  1. [至多包含 K 个不同字符的最长子串](/longest-substring-with-at-most-k-distinct-characters) (Hard)
  1. [最大连续1的个数 III](/max-consecutive-ones-iii) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/longest-repeating-character-replacement)
