---
layout:     single
title:      "两个字符串的最小ASCII删除和"
date:       2017-12-13 21:30:00 +0800
categories: [Leetcode]
tags:       [String, Dynamic Programming]
permalink:  /problems/minimum-ascii-delete-sum-for-two-strings/
---

## 712. 两个字符串的最小ASCII删除和 (Medium)

{% raw %}

<p>给定两个字符串<code>s1, s2</code>，找到使两个字符串相等所需删除字符的ASCII值的最小和。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> s1 = &quot;sea&quot;, s2 = &quot;eat&quot;
<strong>输出:</strong> 231
<strong>解释:</strong> 在 &quot;sea&quot; 中删除 &quot;s&quot; 并将 &quot;s&quot; 的值(115)加入总和。
在 &quot;eat&quot; 中删除 &quot;t&quot; 并将 116 加入总和。
结束时，两个字符串相等，115 + 116 = 231 就是符合条件的最小和。
</pre>

<p><strong>示例&nbsp;2:</strong></p>

<pre>
<strong>输入:</strong> s1 = &quot;delete&quot;, s2 = &quot;leet&quot;
<strong>输出:</strong> 403
<strong>解释:</strong> 在 &quot;delete&quot; 中删除 &quot;dee&quot; 字符串变成 &quot;let&quot;，
将 100[d]+101[e]+101[e] 加入总和。在 &quot;leet&quot; 中删除 &quot;e&quot; 将 101[e] 加入总和。
结束时，两个字符串都等于 &quot;let&quot;，结果即为 100+101+101+101 = 403 。
如果改为将两个字符串转换为 &quot;lee&quot; 或 &quot;eet&quot;，我们会得到 433 或 417 的结果，比答案更大。
</pre>

<p><strong>注意:</strong></p>

<ul>
	<li><code>0 &lt; s1.length, s2.length &lt;= 1000</code>。</li>
	<li>所有字符串中的字符ASCII值在<code>[97, 122]</code>之间。</li>
</ul>

{% endraw %}

### 相关话题
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

### 相似题目
  1. [编辑距离](/problems/edit-distance) (Hard)
  1. [最长递增子序列](/problems/longest-increasing-subsequence) (Medium)
  1. [两个字符串的删除操作](/problems/delete-operation-for-two-strings) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/minimum-ascii-delete-sum-for-two-strings)
