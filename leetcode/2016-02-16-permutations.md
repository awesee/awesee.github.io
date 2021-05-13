---
layout:     single
title:      "全排列"
date:       2016-02-16 21:30:00 +0800
categories: [Leetcode]
tags:       [Backtracking]
permalink:  /problems/permutations/
---

## 46. 全排列 (Medium)

{% raw %}

<p>给定一个不含重复数字的数组 <code>nums</code> ，返回其 <strong>所有可能的全排列</strong> 。你可以 <strong>按任意顺序</strong> 返回答案。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [1,2,3]
<strong>输出：</strong>[[1,2,3],[1,3,2],[2,1,3],[2,3,1],[3,1,2],[3,2,1]]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [0,1]
<strong>输出：</strong>[[0,1],[1,0]]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>nums = [1]
<strong>输出：</strong>[[1]]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 6</code></li>
	<li><code>-10 <= nums[i] <= 10</code></li>
	<li><code>nums</code> 中的所有整数 <strong>互不相同</strong></li>
</ul>

{% endraw %}

### 相关话题
  [[回溯算法](https://github.com/openset/leetcode/tree/master/tag/backtracking/README.md)]

### 相似题目
  1. [下一个排列](/problems/next-permutation) (Medium)
  1. [全排列 II](/problems/permutations-ii) (Medium)
  1. [排列序列](/problems/permutation-sequence) (Hard)
  1. [组合](/problems/combinations) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/permutations)
