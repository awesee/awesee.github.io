---
layout:     single
title:      "最长重复子串"
date:       2018-11-10 21:30:00 +0800
categories: [Leetcode]
tags:       [String, Binary Search, Suffix Array, Sliding Window, Hash Function, Rolling Hash]
permalink:  /problems/longest-duplicate-substring/
---

## 1044. 最长重复子串 (Hard)

{% raw %}

<p>给出一个字符串&nbsp;<code>S</code>，考虑其所有<strong>重复子串</strong>（<code>S</code> 的连续子串，出现两次或多次，可能会有重叠）。</p>

<p>返回<strong>任何</strong>具有最长可能长度的重复子串。（如果 <code>S</code>&nbsp;不含重复子串，那么答案为&nbsp;<code>&quot;&quot;</code>。）</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>&quot;banana&quot;
<strong>输出：</strong>&quot;ana&quot;
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>&quot;abcd&quot;
<strong>输出：</strong>&quot;&quot;
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>2 &lt;= S.length &lt;= 10^5</code></li>
	<li><code>S</code> 由小写英文字母组成。</li>
</ol>

{% endraw %}

### 相关话题
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[后缀数组](https://github.com/awesee/leetcode/tree/main/tag/suffix-array/README.md)]
  [[滑动窗口](https://github.com/awesee/leetcode/tree/main/tag/sliding-window/README.md)]
  [[哈希函数](https://github.com/awesee/leetcode/tree/main/tag/hash-function/README.md)]
  [[滚动哈希](https://github.com/awesee/leetcode/tree/main/tag/rolling-hash/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/longest-duplicate-substring)
