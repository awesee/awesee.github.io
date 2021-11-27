---
layout:     single
title:      "K 个不同整数的子数组"
date:       2018-09-19 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, Counting, Sliding Window]
permalink:  /problems/subarrays-with-k-different-integers/
---

## 992. K 个不同整数的子数组 (Hard)

{% raw %}

<p>给定一个正整数数组 <code>A</code>，如果 <code>A</code> 的某个子数组中不同整数的个数恰好为 <code>K</code>，则称 <code>A</code> 的这个连续、不一定不同的子数组为<em>好子数组</em>。</p>

<p>（例如，<code>[1,2,3,1,2]</code> 中有 <code>3</code> 个不同的整数：<code>1</code>，<code>2</code>，以及 <code>3</code>。）</p>

<p>返回 <code>A</code> 中<em>好子数组</em>的数目。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>A = [1,2,1,2,3], K = 2
<strong>输出：</strong>7
<strong>解释：</strong>恰好由 2 个不同整数组成的子数组：[1,2], [2,1], [1,2], [2,3], [1,2,1], [2,1,2], [1,2,1,2].
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>A = [1,2,1,3,4], K = 3
<strong>输出：</strong>3
<strong>解释：</strong>恰好由 3 个不同整数组成的子数组：[1,2,1,3], [2,1,3], [1,3,4].
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 <= A.length <= 20000</code></li>
	<li><code>1 <= A[i] <= A.length</code></li>
	<li><code>1 <= K <= A.length</code></li>
</ol>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[计数](https://github.com/awesee/leetcode/tree/main/tag/counting/README.md)]
  [[滑动窗口](https://github.com/awesee/leetcode/tree/main/tag/sliding-window/README.md)]

### 相似题目
  1. [无重复字符的最长子串](/problems/longest-substring-without-repeating-characters) (Medium)
  1. [至多包含两个不同字符的最长子串](/problems/longest-substring-with-at-most-two-distinct-characters) (Medium)
  1. [至多包含 K 个不同字符的最长子串](/problems/longest-substring-with-at-most-k-distinct-characters) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/subarrays-with-k-different-integers)
