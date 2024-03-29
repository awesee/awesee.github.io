---
layout:     single
title:      "负二进制转换"
date:       2018-10-14 21:30:00 +0800
categories: [Leetcode]
tags:       [Math]
permalink:  /problems/convert-to-base-2/
---

## 1017. 负二进制转换 (Medium)

{% raw %}

<p>给出数字&nbsp;<code>N</code>，返回由若干&nbsp;<code>&quot;0&quot;</code>&nbsp;和&nbsp;<code>&quot;1&quot;</code>组成的字符串，该字符串为 <code>N</code>&nbsp;的<strong>负二进制（<code>base -2</code>）</strong>表示。</p>

<p>除非字符串就是&nbsp;<code>&quot;0&quot;</code>，否则返回的字符串中不能含有前导零。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>2
<strong>输出：</strong>&quot;110&quot;
<strong>解释：</strong>(-2) ^ 2 + (-2) ^ 1 = 2
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>3
<strong>输出：</strong>&quot;111&quot;
<strong>解释：</strong>(-2) ^ 2 + (-2) ^ 1 + (-2) ^ 0 = 3
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>4
<strong>输出：</strong>&quot;100&quot;
<strong>解释：</strong>(-2) ^ 2 = 4
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>0 &lt;= N &lt;= 10^9</code></li>
</ol>

{% endraw %}

### 相关话题
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]

### 相似题目
  1. [加密数字](/problems/encode-number) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/convert-to-base-2)
