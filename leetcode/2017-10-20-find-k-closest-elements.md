---
layout:     single
title:      "找到 K 个最接近的元素"
date:       2017-10-20 21:30:00 +0800
categories: [Leetcode]
tags:       [Binary Search]
permalink:  /problems/find-k-closest-elements/
---

## 658. 找到 K 个最接近的元素 (Medium)

{% raw %}

<p>给定一个排序好的数组，两个整数 <code>k</code> 和 <code>x</code>，从数组中找到最靠近 <code>x</code>（两数之差最小）的 <code>k</code> 个数。返回的结果必须要是按升序排好的。如果有两个数与 <code>x</code> 的差值一样，优先选择数值较小的那个数。</p>

<p><strong>示例&nbsp;1:</strong></p>

<pre>
<strong>输入:</strong> [1,2,3,4,5], k=4, x=3
<strong>输出:</strong> [1,2,3,4]
</pre>

<p>&nbsp;</p>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> [1,2,3,4,5], k=4, x=-1
<strong>输出:</strong> [1,2,3,4]
</pre>

<p>&nbsp;</p>

<p><strong>说明:</strong></p>

<ol>
	<li>k 的值为正数，且总是小于给定排序数组的长度。</li>
	<li>数组不为空，且长度不超过 10<sup>4</sup></li>
	<li>数组里的每个元素与&nbsp;x 的绝对值不超过 10<sup>4</sup></li>
</ol>

<p>&nbsp;</p>

<p><strong>更新(2017/9/19):</strong><br />
这个参数 <em>arr</em> 已经被改变为一个<strong>整数数组</strong>（而不是整数列表）。<strong><em>&nbsp;请重新加载代码定义以获取最新更改。</em></strong></p>

{% endraw %}

### 相关话题
  [[二分查找](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]

### 相似题目
  1. [猜数字大小](/problems/guess-number-higher-or-lower) (Easy)
  1. [猜数字大小 II](/problems/guess-number-higher-or-lower-ii) (Medium)
  1. [找出第 k 小的距离对](/problems/find-k-th-smallest-pair-distance) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/find-k-closest-elements)
