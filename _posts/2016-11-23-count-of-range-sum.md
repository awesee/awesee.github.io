---
layout:     single
title:      "327. 区间和的个数 (Hard)"
date:       2016-11-23 21:30:00 +0800
categories: [leetcode]
tags:       [binary-search-tree, divide-and-conquer]
permalink:  /count-of-range-sum/
---

<p>给定一个整数数组&nbsp;<code>nums</code>，返回区间和在&nbsp;<code>[lower, upper]</code>&nbsp;之间的个数，包含&nbsp;<code>lower</code>&nbsp;和&nbsp;<code>upper</code>。<br>
区间和&nbsp;<code>S(i, j)</code>&nbsp;表示在&nbsp;<code>nums</code>&nbsp;中，位置从&nbsp;<code>i</code>&nbsp;到&nbsp;<code>j</code>&nbsp;的元素之和，包含&nbsp;<code>i</code>&nbsp;和&nbsp;<code>j</code>&nbsp;(<code>i</code> &le; <code>j</code>)。</p>

<p><strong>说明:</strong><br>
最直观的算法复杂度是&nbsp;<em>O</em>(<em>n</em><sup>2</sup>) ，请在此基础上优化你的算法。</p>

<p><strong>示例:</strong></p>

<pre><strong>输入: </strong><em>nums</em> = <code>[-2,5,-1]</code>, <em>lower</em> = <code>-2</code>, <em>upper</em> = <code>2</code>,
<strong>输出: </strong>3 
<strong>解释: </strong>3个区间分别是: <code>[0,0]</code>, <code>[2,2]</code>, <code>[0,2]，</code>它们表示的和分别为: <code>-2, -1, 2。</code>
</pre>

### 相关话题
  [[二叉搜索树](https://github.com/openset/leetcode/tree/master/tag/binary-search-tree/README.md)]
  [[分治算法](https://github.com/openset/leetcode/tree/master/tag/divide-and-conquer/README.md)]

### 相似题目
  1. [计算右侧小于当前元素的个数](/count-of-smaller-numbers-after-self) (Hard)
  1. [翻转对](/reverse-pairs) (Hard)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/count-of-range-sum)
