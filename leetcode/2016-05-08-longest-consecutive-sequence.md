---
layout:     single
title:      "最长连续序列"
date:       2016-05-08 21:30:00 +0800
categories: [Leetcode]
tags:       [Union Find, Array, Hash Table]
permalink:  /problems/longest-consecutive-sequence/
---

## 128. 最长连续序列 (Medium)

{% raw %}

<p>给定一个未排序的整数数组 <code>nums</code> ，找出数字连续的最长序列（不要求序列元素在原数组中连续）的长度。</p>

<p> </p>

<p><strong>进阶：</strong>你可以设计并实现时间复杂度为 <code>O(n)</code><em> </em>的解决方案吗？</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [100,4,200,1,3,2]
<strong>输出：</strong>4
<strong>解释：</strong>最长数字连续序列是 <code>[1, 2, 3, 4]。它的长度为 4。</code></pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [0,3,7,2,5,8,4,6,0,1]
<strong>输出：</strong>9
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 <= nums.length <= 10<sup>4</sup></code></li>
	<li><code>-10<sup>9</sup> <= nums[i] <= 10<sup>9</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[并查集](https://github.com/openset/leetcode/tree/master/tag/union-find/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]

### 相似题目
  1. [二叉树最长连续序列](/problems/binary-tree-longest-consecutive-sequence) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/longest-consecutive-sequence)
