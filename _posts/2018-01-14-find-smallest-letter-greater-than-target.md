---
layout:     single
title:      "寻找比目标字母大的最小字母"
date:       2018-01-14 21:30:00 +0800
categories: [Leetcode]
tags:       [Binary Search]
permalink:  /problems/find-smallest-letter-greater-than-target/
---

## 744. 寻找比目标字母大的最小字母 (Easy)

{% raw %}

<p>给定一个只包含小写字母的有序数组<code>letters</code>&nbsp;和一个目标字母&nbsp;<code>target</code>，寻找有序数组里面比目标字母大的最小字母。</p>

<p>数组里字母的顺序是循环的。举个例子，如果目标字母<code>target = &#39;z&#39;</code> 并且有序数组为&nbsp;<code>letters = [&#39;a&#39;, &#39;b&#39;]</code>，则答案返回&nbsp;<code>&#39;a&#39;</code>。</p>

<p><strong>示例:</strong></p>

<pre>
<strong>输入:</strong>
letters = [&quot;c&quot;, &quot;f&quot;, &quot;j&quot;]
target = &quot;a&quot;
<strong>输出:</strong> &quot;c&quot;

<strong>输入:</strong>
letters = [&quot;c&quot;, &quot;f&quot;, &quot;j&quot;]
target = &quot;c&quot;
<strong>输出:</strong> &quot;f&quot;

<strong>输入:</strong>
letters = [&quot;c&quot;, &quot;f&quot;, &quot;j&quot;]
target = &quot;d&quot;
<strong>输出:</strong> &quot;f&quot;

<strong>输入:</strong>
letters = [&quot;c&quot;, &quot;f&quot;, &quot;j&quot;]
target = &quot;g&quot;
<strong>输出:</strong> &quot;j&quot;

<strong>输入:</strong>
letters = [&quot;c&quot;, &quot;f&quot;, &quot;j&quot;]
target = &quot;j&quot;
<strong>输出:</strong> &quot;c&quot;

<strong>输入:</strong>
letters = [&quot;c&quot;, &quot;f&quot;, &quot;j&quot;]
target = &quot;k&quot;
<strong>输出:</strong> &quot;c&quot;
</pre>

<p><strong>注:</strong></p>

<ol>
	<li><code>letters</code>长度范围在<code>[2, 10000]</code>区间内。</li>
	<li><code>letters</code> 仅由小写字母组成，最少包含两个不同的字母。</li>
	<li>目标字母<code>target</code> 是一个小写字母。</li>
</ol>

{% endraw %}

### 相关话题
  [[二分查找](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/find-smallest-letter-greater-than-target)