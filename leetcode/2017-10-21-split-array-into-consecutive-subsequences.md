---
layout:     single
title:      "分割数组为连续子序列"
date:       2017-10-21 21:30:00 +0800
categories: [Leetcode]
tags:       [Heap, Greedy]
permalink:  /problems/split-array-into-consecutive-subsequences/
---

## 659. 分割数组为连续子序列 (Medium)

{% raw %}

<p>给你一个按升序排序的整数数组 <code>num</code>（可能包含重复数字），请你将它们分割成一个或多个子序列，其中每个子序列都由连续整数组成且长度至少为 3 。</p>

<p>如果可以完成上述分割，则返回 <code>true</code> ；否则，返回 <code>false</code> 。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入:</strong> [1,2,3,3,4,5]
<strong>输出:</strong> True
<strong>解释:</strong>
你可以分割出这样两个连续子序列 : 
1, 2, 3
3, 4, 5
</pre>

<p>&nbsp;</p>

<p><strong>示例 2：</strong></p>

<pre><strong>输入:</strong> [1,2,3,3,4,4,5,5]
<strong>输出:</strong> True
<strong>解释:</strong>
你可以分割出这样两个连续子序列 : 
1, 2, 3, 4, 5
3, 4, 5
</pre>

<p>&nbsp;</p>

<p><strong>示例 3：</strong></p>

<pre><strong>输入:</strong> [1,2,3,4,4,5]
<strong>输出:</strong> False
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li>输入的数组长度范围为 [1, 10000]</li>
</ol>

<p>&nbsp;</p>

{% endraw %}

### 相关话题
  [[堆](https://github.com/openset/leetcode/tree/master/tag/heap/README.md)]
  [[贪心算法](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]

### 相似题目
  1. [前 K 个高频元素](/problems/top-k-frequent-elements) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/split-array-into-consecutive-subsequences)
