---
layout:     single
title:      "重复的DNA序列"
date:       2016-07-06 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Hash Table, String, Sliding Window, Hash Function, Rolling Hash]
permalink:  /problems/repeated-dna-sequences/
---

## 187. 重复的DNA序列 (Medium)

{% raw %}

<p>所有 DNA 都由一系列缩写为 <code>'A'</code>，<code>'C'</code>，<code>'G'</code> 和 <code>'T'</code> 的核苷酸组成，例如：<code>"ACGAATTCCG"</code>。在研究 DNA 时，识别 DNA 中的重复序列有时会对研究非常有帮助。</p>

<p>编写一个函数来找出所有目标子串，目标子串的长度为 10，且在 DNA 字符串 <code>s</code> 中出现次数超过一次。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>s = "AAAAACCCCCAAAAACCCCCCAAAAAGGGTTT"
<strong>输出：</strong>["AAAAACCCCC","CCCCCAAAAA"]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>s = "AAAAAAAAAAAAA"
<strong>输出：</strong>["AAAAAAAAAA"]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 <= s.length <= 10<sup>5</sup></code></li>
	<li><code>s[i]</code> 为 <code>'A'</code>、<code>'C'</code>、<code>'G'</code> 或 <code>'T'</code></li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/openset/leetcode/tree/master/tag/bit-manipulation/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[滑动窗口](https://github.com/openset/leetcode/tree/master/tag/sliding-window/README.md)]
  [[哈希函数](https://github.com/openset/leetcode/tree/master/tag/hash-function/README.md)]
  [[滚动哈希](https://github.com/openset/leetcode/tree/master/tag/rolling-hash/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/repeated-dna-sequences)
