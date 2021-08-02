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

<p>给定一个<strong>无重复元素</strong>的正整数数组 <code>candidates</code> 和一个正整数 <code>target</code> ，找出 <code>candidates</code> 中所有可以使数字和为目标数 <code>target</code> 的唯一组合。</p>

<p><code>candidates</code> 中的数字可以无限制重复被选取。如果至少一个所选数字数量不同，则两种组合是唯一的。 </p>

<p>对于给定的输入，保证和为 <code>target</code> 的唯一组合数少于 <code>150</code> 个。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入: </strong>candidates = <code>[2,3,6,7], </code>target = <code>7</code>
<strong>输出: </strong>[[7],[2,2,3]]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入: </strong>candidates = [2,3,5]<code>, </code>target = 8
<strong>输出: </strong>[[2,2,2,2],[2,3,3],[3,5]]</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入: </strong>candidates = <code>[2], </code>target = 1
<strong>输出: </strong>[]
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入: </strong>candidates = <code>[1], </code>target = <code>1</code>
<strong>输出: </strong>[[1]]
</pre>

<p><strong>示例 5：</strong></p>

<pre>
<strong>输入: </strong>candidates = <code>[1], </code>target = <code>2</code>
<strong>输出: </strong>[[1,1]]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= candidates.length <= 30</code></li>
	<li><code>1 <= candidates[i] <= 200</code></li>
	<li><code>candidate</code> 中的每个元素都是独一无二的。</li>
	<li><code>1 <= target <= 500</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[回溯](https://github.com/openset/leetcode/tree/master/tag/backtracking/README.md)]

### 相似题目
  1. [电话号码的字母组合](/problems/letter-combinations-of-a-phone-number) (Medium)
  1. [组合总和 II](/problems/combination-sum-ii) (Medium)
  1. [组合](/problems/combinations) (Medium)
  1. [组合总和 III](/problems/combination-sum-iii) (Medium)
  1. [因子的组合](/problems/factor-combinations) (Medium)
  1. [组合总和 Ⅳ](/problems/combination-sum-iv) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/combination-sum)
