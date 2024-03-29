---
layout:     single
title:      "最长数对链"
date:       2017-10-08 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Array, Dynamic Programming, Sorting]
permalink:  /problems/maximum-length-of-pair-chain/
---

## 646. 最长数对链 (Medium)

{% raw %}

<p>给出 <code>n</code> 个数对。 在每一个数对中，第一个数字总是比第二个数字小。</p>

<p>现在，我们定义一种跟随关系，当且仅当 <code>b < c</code> 时，数对<code>(c, d)</code> 才可以跟在 <code>(a, b)</code> 后面。我们用这种形式来构造一个数对链。</p>

<p>给定一个数对集合，找出能够形成的最长数对链的长度。你不需要用到所有的数对，你可以以任何顺序选择其中的一些数对来构造。</p>

<p> </p>

<p><strong>示例：</strong></p>

<pre>
<strong>输入：</strong>[[1,2], [2,3], [3,4]]
<strong>输出：</strong>2
<strong>解释：</strong>最长的数对链是 [1,2] -> [3,4]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>给出数对的个数在 <code>[1, 1000]</code> 范围内。</li>
</ul>

{% endraw %}

### 相关话题
  [[贪心](https://github.com/awesee/leetcode/tree/main/tag/greedy/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]

### 相似题目
  1. [最长递增子序列](/problems/longest-increasing-subsequence) (Medium)
  1. [递增子序列](/problems/increasing-subsequences) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/maximum-length-of-pair-chain)
