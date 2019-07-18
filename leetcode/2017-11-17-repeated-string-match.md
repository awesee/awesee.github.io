---
layout:     single
title:      "重复叠加字符串匹配"
date:       2017-11-17 21:30:00 +0800
categories: [Leetcode]
tags:       [String]
permalink:  /repeated-string-match/
---

## 686. 重复叠加字符串匹配 (Easy)

{% raw %}

<p>给定两个字符串 A 和 B, 寻找重复叠加字符串A的最小次数，使得字符串B成为叠加后的字符串A的子串，如果不存在则返回 -1。</p>

<p>举个例子，A = &quot;abcd&quot;，B = &quot;cdabcdab&quot;。</p>

<p>答案为 3，&nbsp;因为 A 重复叠加三遍后为&nbsp;&ldquo;abcdabcdabcd&rdquo;，此时 B 是其子串；A 重复叠加两遍后为&quot;abcdabcd&quot;，B 并不是其子串。</p>

<p><strong>注意:</strong></p>

<p>&nbsp;<code>A</code>&nbsp;与&nbsp;<code>B</code>&nbsp;字符串的长度在1和10000区间范围内。</p>

{% endraw %}

### 相关话题
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### 相似题目
  1. [重复的子字符串](/repeated-substring-pattern) (Easy)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/repeated-string-match)
