---
layout:     single
title:      "第 K 个最小的素数分数"
date:       2018-02-25 21:30:00 +0800
categories: [Leetcode]
tags:       [Heap, Binary Search]
permalink:  /problems/k-th-smallest-prime-fraction/
---

## 786. 第 K 个最小的素数分数 (Hard)

{% raw %}

<p>一个已排序好的表&nbsp;<code>A</code>，其包含 1 和其他一些素数.&nbsp; 当列表中的每一个 p&lt;q 时，我们可以构造一个分数 p/q 。</p>

<p>那么第&nbsp;<code>k</code>&nbsp;个最小的分数是多少呢?&nbsp; 以整数数组的形式返回你的答案, 这里&nbsp;<code>answer[0] = p</code>&nbsp;且&nbsp;<code>answer[1] = q</code>.</p>

<pre>
<strong>示例:</strong>
<strong>输入:</strong> A = [1, 2, 3, 5], K = 3
<strong>输出:</strong> [2, 5]
<strong>解释:</strong>
已构造好的分数,排序后如下所示:
1/5, 1/3, 2/5, 1/2, 3/5, 2/3.
很明显第三个最小的分数是 2/5.

<strong>输入:</strong> A = [1, 7], K = 1
<strong>输出:</strong> [1, 7]
</pre>

<p><strong>注意:</strong></p>

<ul>
	<li><code>A</code> 的取值范围在 <code>2</code> &mdash; <code>2000</code>.</li>
	<li>每个&nbsp;<code>A[i]</code> 的值在 <code>1</code> &mdash;<code>30000</code>.</li>
	<li><code>K</code> 取值范围为 <code>1</code> &mdash;<code>A.length * (A.length - 1) / 2</code></li>
</ul>

{% endraw %}

### 相关话题
  [[堆](https://github.com/openset/leetcode/tree/master/tag/heap/README.md)]
  [[二分查找](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]

### 相似题目
  1. [有序矩阵中第K小的元素](/problems/kth-smallest-element-in-a-sorted-matrix) (Medium)
  1. [乘法表中第k小的数](/problems/kth-smallest-number-in-multiplication-table) (Hard)
  1. [找出第 k 小的距离对](/problems/find-k-th-smallest-pair-distance) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/k-th-smallest-prime-fraction)
