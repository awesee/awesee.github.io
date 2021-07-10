---
layout:     single
title:      "组合总和 II"
date:       2016-02-10 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Backtracking]
permalink:  /problems/combination-sum-ii/
---

## 40. 组合总和 II (Medium)

{% raw %}

<p>给定一个数组 <code>candidates</code> 和一个目标数 <code>target</code> ，找出 <code>candidates</code> 中所有可以使数字和为 <code>target</code> 的组合。</p>

<p><code>candidates</code> 中的每个数字在每个组合中只能使用一次。</p>

<p><strong>注意：</strong>解集不能包含重复的组合。 </p>

<p> </p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> candidates = <code>[10,1,2,7,6,1,5]</code>, target = <code>8</code>,
<strong>输出:</strong>
[
[1,1,6],
[1,2,5],
[1,7],
[2,6]
]</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> candidates = [2,5,2,1,2], target = 5,
<strong>输出:</strong>
[
[1,2,2],
[5]
]</pre>

<p> </p>

<p><strong>提示:</strong></p>

<ul>
	<li><code>1 <= candidates.length <= 100</code></li>
	<li><code>1 <= candidates[i] <= 50</code></li>
	<li><code>1 <= target <= 30</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[回溯](https://github.com/openset/leetcode/tree/master/tag/backtracking/README.md)]

### 相似题目
  1. [组合总和](/problems/combination-sum) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/combination-sum-ii)
