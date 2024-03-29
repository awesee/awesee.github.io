---
layout:     single
title:      "K个逆序对数组"
date:       2017-09-21 21:30:00 +0800
categories: [Leetcode]
tags:       [Dynamic Programming]
permalink:  /problems/k-inverse-pairs-array/
---

## 629. K个逆序对数组 (Hard)

{% raw %}

<p>给出两个整数&nbsp;<code>n</code>&nbsp;和&nbsp;<code>k</code>，找出所有包含从&nbsp;<code>1</code>&nbsp;到&nbsp;<code>n</code>&nbsp;的数字，且恰好拥有&nbsp;<code>k</code>&nbsp;个逆序对的不同的数组的个数。</p>

<p>逆序对的定义如下：对于数组的第<code>i</code>个和第&nbsp;<code>j</code>个元素，如果满<code>i</code>&nbsp;&lt;&nbsp;<code>j</code>且&nbsp;<code>a[i]</code>&nbsp;&gt;&nbsp;<code>a[j]</code>，则其为一个逆序对；否则不是。</p>

<p>由于答案可能很大，只需要返回 答案 mod 10<sup>9</sup>&nbsp;+ 7 的值。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> n = 3, k = 0
<strong>输出:</strong> 1
<strong>解释:</strong> 
只有数组 [1,2,3] 包含了从1到3的整数并且正好拥有 0 个逆序对。
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> n = 3, k = 1
<strong>输出:</strong> 2
<strong>解释:</strong> 
数组 [1,3,2] 和 [2,1,3] 都有 1 个逆序对。
</pre>

<p><strong>说明:</strong></p>

<ol>
	<li>&nbsp;<code>n</code>&nbsp;的范围是 [1, 1000] 并且 <code>k</code> 的范围是 [0, 1000]。</li>
</ol>

{% endraw %}

### 相关话题
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/k-inverse-pairs-array)
