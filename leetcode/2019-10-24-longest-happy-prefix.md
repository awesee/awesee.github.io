---
layout:     single
title:      "最长快乐前缀"
date:       2019-10-24 21:30:00 +0800
categories: [Leetcode]
tags:       [String, String Matching, Hash Function, Rolling Hash]
permalink:  /problems/longest-happy-prefix/
---

## 1392. 最长快乐前缀 (Hard)

{% raw %}

<p>「快乐前缀」是在原字符串中既是&nbsp;<strong>非空</strong> 前缀也是后缀（不包括原字符串自身）的字符串。</p>

<p>给你一个字符串 <code>s</code>，请你返回它的 <strong>最长快乐前缀</strong>。</p>

<p>如果不存在满足题意的前缀，则返回一个空字符串。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>s = &quot;level&quot;
<strong>输出：</strong>&quot;l&quot;
<strong>解释：</strong>不包括 s 自己，一共有 4 个前缀（&quot;l&quot;, &quot;le&quot;, &quot;lev&quot;, &quot;leve&quot;）和 4 个后缀（&quot;l&quot;, &quot;el&quot;, &quot;vel&quot;, &quot;evel&quot;）。最长的既是前缀也是后缀的字符串是 &quot;l&quot; 。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>s = &quot;ababab&quot;
<strong>输出：</strong>&quot;abab&quot;
<strong>解释：</strong>&quot;abab&quot; 是最长的既是前缀也是后缀的字符串。题目允许前后缀在原字符串中重叠。
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>s = &quot;leetcodeleet&quot;
<strong>输出：</strong>&quot;leet&quot;
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>s = &quot;a&quot;
<strong>输出：</strong>&quot;&quot;
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= s.length &lt;= 10^5</code></li>
	<li><code>s</code> 只含有小写英文字母</li>
</ul>

{% endraw %}

### 相关话题
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[字符串匹配](https://github.com/awesee/leetcode/tree/main/tag/string-matching/README.md)]
  [[哈希函数](https://github.com/awesee/leetcode/tree/main/tag/hash-function/README.md)]
  [[滚动哈希](https://github.com/awesee/leetcode/tree/main/tag/rolling-hash/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/longest-happy-prefix)
