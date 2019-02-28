---
layout:     single
title:      "493. 翻转对 (Hard)"
date:       2017-05-08 21:30:00 +0800
categories: [leetcode]
tags:       [binary-indexed-tree, segment-tree, binary-search-tree, divide-and-conquer]
permalink:  /reverse-pairs/
---

<p>给定一个数组&nbsp;<code>nums</code>&nbsp;，如果&nbsp;<code>i &lt; j</code>&nbsp;且&nbsp;<code>nums[i] &gt; 2*nums[j]</code>&nbsp;我们就将&nbsp;<code>(i, j)</code>&nbsp;称作一个<strong><em>重要翻转对</em></strong>。</p>

<p>你需要返回给定数组中的重要翻转对的数量。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入</strong>: [1,3,2,3,1]
<strong>输出</strong>: 2
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入</strong>: [2,4,3,5,1]
<strong>输出</strong>: 3
</pre>

<p><strong>注意:</strong></p>

<ol>
	<li>给定数组的长度不会超过<code>50000</code>。</li>
	<li>输入数组中的所有数字都在32位整数的表示范围内。</li>
</ol>

### 相关话题
  [[树状数组](https://github.com/openset/leetcode/tree/master/tag/binary-indexed-tree/README.md)]
  [[线段树](https://github.com/openset/leetcode/tree/master/tag/segment-tree/README.md)]
  [[二叉搜索树](https://github.com/openset/leetcode/tree/master/tag/binary-search-tree/README.md)]
  [[分治算法](https://github.com/openset/leetcode/tree/master/tag/divide-and-conquer/README.md)]

### 相似题目
  1. [计算右侧小于当前元素的个数](/count-of-smaller-numbers-after-self) (Hard)
  1. [区间和的个数](/count-of-range-sum) (Hard)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/reverse-pairs)
