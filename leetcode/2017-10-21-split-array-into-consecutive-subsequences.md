---
layout:     single
title:      "分割数组为连续子序列"
date:       2017-10-21 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Array, Hash Table, Heap (Priority Queue)]
permalink:  /problems/split-array-into-consecutive-subsequences/
---

## 659. 分割数组为连续子序列 (Medium)

{% raw %}

<p>给你一个按升序排序的整数数组 <code>num</code>（可能包含重复数字），请你将它们分割成一个或多个长度至少为 3 的子序列，其中每个子序列都由连续整数组成。</p>

<p>如果可以完成上述分割，则返回 <code>true</code> ；否则，返回 <code>false</code> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入:</strong> [1,2,3,3,4,5]
<strong>输出:</strong> True
<strong>解释:</strong>
你可以分割出这样两个连续子序列 : 
1, 2, 3
3, 4, 5
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入:</strong> [1,2,3,3,4,4,5,5]
<strong>输出:</strong> True
<strong>解释:</strong>
你可以分割出这样两个连续子序列 : 
1, 2, 3, 4, 5
3, 4, 5
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入:</strong> [1,2,3,4,4,5]
<strong>输出:</strong> False
</pre>

<p> </p>

<p><b>提示：</b></p>

<ul>
	<li><code>1 <= nums.length <= 10000</code></li>
</ul>

{% endraw %}

### 相关话题
  [[贪心](https://github.com/awesee/leetcode/tree/main/tag/greedy/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[堆（优先队列）](https://github.com/awesee/leetcode/tree/main/tag/heap-priority-queue/README.md)]

### 相似题目
  1. [前 K 个高频元素](/problems/top-k-frequent-elements) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/split-array-into-consecutive-subsequences)
