---
layout:     single
title:      "查找和最小的K对数字"
date:       2017-01-08 21:30:00 +0800
categories: [Leetcode]
tags:       [Heap]
permalink:  /find-k-pairs-with-smallest-sums/
---

## 373. 查找和最小的K对数字 (Medium)

<p>给定两个以升序排列的整形数组 <strong>nums1</strong> 和 <strong>nums2</strong>, 以及一个整数 <strong>k</strong>。</p>

<p>定义一对值&nbsp;<strong>(u,v)</strong>，其中第一个元素来自&nbsp;<strong>nums1</strong>，第二个元素来自 <strong>nums2</strong>。</p>

<p>找到和最小的 k 对数字&nbsp;<strong>(u<sub>1</sub>,v<sub>1</sub>), (u<sub>2</sub>,v<sub>2</sub>) ... (u<sub>k</sub>,v<sub>k</sub>)</strong>。</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入:</strong> nums1 = [1,7,11], nums2 = [2,4,6], k = 3
<strong>输出:</strong> [1,2],[1,4],[1,6]
<strong>解释: </strong>返回序列中的前 3 对数：
     [1,2],[1,4],[1,6],[7,2],[7,4],[11,2],[7,6],[11,4],[11,6]
</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入: </strong>nums1 = [1,1,2], nums2 = [1,2,3], k = 2
<strong>输出: </strong>[1,1],[1,1]
<strong>解释: </strong>返回序列中的前 2 对数：
&nbsp;    [1,1],[1,1],[1,2],[2,1],[1,2],[2,2],[1,3],[1,3],[2,3]
</pre>

<p><strong>示例 3:</strong></p>

<pre><strong>输入: </strong>nums1 = [1,2], nums2 = [3], k = 3 
<strong>输出:</strong> [1,3],[2,3]
<strong>解释: </strong>也可能序列中所有的数对都被返回:[1,3],[2,3]
</pre>

### 相关话题
  [[堆](https://github.com/openset/leetcode/tree/master/tag/heap/README.md)]

### 相似题目
  1. [有序矩阵中第K小的元素](/kth-smallest-element-in-a-sorted-matrix) (Medium)
  1. [找出第 k 小的距离对](/find-k-th-smallest-pair-distance) (Hard)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/find-k-pairs-with-smallest-sums)
