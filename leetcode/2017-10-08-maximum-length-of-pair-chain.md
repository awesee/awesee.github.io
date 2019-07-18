---
layout:     single
title:      "最长数对链"
date:       2017-10-08 21:30:00 +0800
categories: [Leetcode]
tags:       [Dynamic Programming]
permalink:  /maximum-length-of-pair-chain/
---

## 646. 最长数对链 (Medium)

{% raw %}

<p>给出&nbsp;<code>n</code>&nbsp;个数对。&nbsp;在每一个数对中，第一个数字总是比第二个数字小。</p>

<p>现在，我们定义一种跟随关系，当且仅当&nbsp;<code>b &lt; c</code>&nbsp;时，数对<code>(c, d)</code>&nbsp;才可以跟在&nbsp;<code>(a, b)</code>&nbsp;后面。我们用这种形式来构造一个数对链。</p>

<p>给定一个对数集合，找出能够形成的最长数对链的长度。你不需要用到所有的数对，你可以以任何顺序选择其中的一些数对来构造。</p>

<p><strong>示例 :</strong></p>

<pre>
<strong>输入:</strong> [[1,2], [2,3], [3,4]]
<strong>输出:</strong> 2
<strong>解释:</strong> 最长的数对链是 [1,2] -&gt; [3,4]
</pre>

<p><strong>注意：</strong></p>

<ol>
	<li>给出数对的个数在&nbsp;[1, 1000] 范围内。</li>
</ol>

{% endraw %}

### 相关话题
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### 相似题目
  1. [最长上升子序列](/longest-increasing-subsequence) (Medium)
  1. [递增子序列](/increasing-subsequences) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/maximum-length-of-pair-chain)
