---
layout:     single
title:      "组合总和"
date:       2016-02-09 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Backtracking]
permalink:  /problems/combination-sum/
---

## 39. 组合总和 (Medium)

{% raw %}

<p>给定一个<strong>无重复元素</strong>的数组&nbsp;<code>candidates</code>&nbsp;和一个目标数&nbsp;<code>target</code>&nbsp;，找出&nbsp;<code>candidates</code>&nbsp;中所有可以使数字和为&nbsp;<code>target</code>&nbsp;的组合。</p>

<p><code>candidates</code>&nbsp;中的数字可以无限制重复被选取。</p>

<p><strong>说明：</strong></p>

<ul>
	<li>所有数字（包括&nbsp;<code>target</code>）都是正整数。</li>
	<li>解集不能包含重复的组合。&nbsp;</li>
</ul>

<p><strong>示例&nbsp;1：</strong></p>

<pre><strong>输入：</strong>candidates = <code>[2,3,6,7], </code>target = <code>7</code>,
<strong>所求解集为：</strong>
[
  [7],
  [2,2,3]
]
</pre>

<p><strong>示例&nbsp;2：</strong></p>

<pre><strong>输入：</strong>candidates = [2,3,5]<code>, </code>target = 8,
<strong>所求解集为：</strong>
[
&nbsp; [2,2,2,2],
&nbsp; [2,3,3],
&nbsp; [3,5]
]</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= candidates.length &lt;= 30</code></li>
	<li><code>1 &lt;= candidates[i] &lt;= 200</code></li>
	<li><code>candidate</code> 中的每个元素都是独一无二的。</li>
	<li><code>1 &lt;= target &lt;= 500</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[回溯算法](https://github.com/openset/leetcode/tree/master/tag/backtracking/README.md)]

### 相似题目
  1. [电话号码的字母组合](/problems/letter-combinations-of-a-phone-number) (Medium)
  1. [组合总和 II](/problems/combination-sum-ii) (Medium)
  1. [组合](/problems/combinations) (Medium)
  1. [组合总和 III](/problems/combination-sum-iii) (Medium)
  1. [因子的组合](/problems/factor-combinations) (Medium)
  1. [组合总和 Ⅳ](/problems/combination-sum-iv) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/combination-sum)
