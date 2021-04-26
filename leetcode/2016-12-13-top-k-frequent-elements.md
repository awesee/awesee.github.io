---
layout:     single
title:      "前 K 个高频元素"
date:       2016-12-13 21:30:00 +0800
categories: [Leetcode]
tags:       [Heap, Hash Table]
permalink:  /problems/top-k-frequent-elements/
---

## 347. 前 K 个高频元素 (Medium)

{% raw %}

<p>给你一个整数数组 <code>nums</code> 和一个整数 <code>k</code> ，请你返回其中出现频率前 <code>k</code> 高的元素。你可以按 <strong>任意顺序</strong> 返回答案。</p>

<p> </p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入: </strong>nums = [1,1,1,2,2,3], k = 2
<strong>输出: </strong>[1,2]
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入: </strong>nums = [1], k = 1
<strong>输出: </strong>[1]</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 10<sup>5</sup></code></li>
	<li><code>k</code> 的取值范围是 <code>[1, 数组中不相同的元素的个数]</code></li>
	<li>题目数据保证答案唯一，换句话说，数组中前 <code>k</code> 个高频元素的集合是唯一的</li>
</ul>

<p> </p>

<p><strong>进阶：</strong>你所设计算法的时间复杂度 <strong>必须</strong> 优于 <code>O(n log n)</code> ，其中 <code>n</code><em> </em>是数组大小。</p>

{% endraw %}

### 相关话题
  [[堆](https://github.com/openset/leetcode/tree/master/tag/heap/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]

### 相似题目
  1. [统计词频](/problems/word-frequency) (Medium)
  1. [数组中的第K个最大元素](/problems/kth-largest-element-in-an-array) (Medium)
  1. [根据字符出现频率排序](/problems/sort-characters-by-frequency) (Medium)
  1. [分割数组为连续子序列](/problems/split-array-into-consecutive-subsequences) (Medium)
  1. [前K个高频单词](/problems/top-k-frequent-words) (Medium)
  1. [最接近原点的 K 个点](/problems/k-closest-points-to-origin) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/top-k-frequent-elements)
