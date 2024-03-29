---
layout:     single
title:      "相似度为 K 的字符串"
date:       2018-05-04 21:30:00 +0800
categories: [Leetcode]
tags:       [Breadth-First Search, String]
permalink:  /problems/k-similar-strings/
---

## 854. 相似度为 K 的字符串 (Hard)

{% raw %}

<p>如果可以通过将 <code>A</code> 中的两个小写字母精确地交换位置 <code>K</code> 次得到与 <code>B</code> 相等的字符串，我们称字符串&nbsp;<code>A</code>&nbsp;和&nbsp;<code>B</code>&nbsp;的相似度为 <code>K</code>（<code>K</code>&nbsp;为非负整数）。</p>

<p>给定两个字母异位词&nbsp;<code>A</code>&nbsp;和&nbsp;<code>B</code>&nbsp;，返回 <code>A</code> 和 <code>B</code>&nbsp;的相似度 <code>K</code> 的最小值。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>A = &quot;ab&quot;, B = &quot;ba&quot;
<strong>输出：</strong>1
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>A = &quot;abc&quot;, B = &quot;bca&quot;
<strong>输出：</strong>2
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>A = &quot;abac&quot;, B = &quot;baca&quot;
<strong>输出：</strong>2
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>A = &quot;aabc&quot;, B = &quot;abca&quot;
<strong>输出：</strong>2</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= A.length == B.length &lt;= 20</code></li>
	<li><code>A</code>&nbsp;和&nbsp;<code>B</code>&nbsp;只包含集合&nbsp;<code>{&#39;a&#39;, &#39;b&#39;, &#39;c&#39;, &#39;d&#39;, &#39;e&#39;, &#39;f&#39;}</code>&nbsp;中的小写字母。</li>
</ol>

{% endraw %}

### 相关话题
  [[广度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/breadth-first-search/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

### 相似题目
  1. [情侣牵手](/problems/couples-holding-hands) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/k-similar-strings)
