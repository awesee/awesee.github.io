---
layout:     single
title:      "下一个更大元素 II"
date:       2017-05-18 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Array, Monotonic Stack]
permalink:  /problems/next-greater-element-ii/
---

## 503. 下一个更大元素 II (Medium)

{% raw %}

<p>给定一个循环数组（最后一个元素的下一个元素是数组的第一个元素），输出每个元素的下一个更大元素。数字 x 的下一个更大的元素是按数组遍历顺序，这个数字之后的第一个比它更大的数，这意味着你应该循环地搜索它的下一个更大的数。如果不存在，则输出 -1。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> [1,2,1]
<strong>输出:</strong> [2,-1,2]
<strong>解释:</strong> 第一个 1 的下一个更大的数是 2；
数字 2 找不到下一个更大的数； 
第二个 1 的下一个最大的数需要循环搜索，结果也是 2。
</pre>

<p><strong>注意:</strong> 输入数组的长度不会超过 10000。</p>

{% endraw %}

### 相关话题
  [[栈](https://github.com/awesee/leetcode/tree/main/tag/stack/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[单调栈](https://github.com/awesee/leetcode/tree/main/tag/monotonic-stack/README.md)]

### 相似题目
  1. [下一个更大元素 I](/problems/next-greater-element-i) (Easy)
  1. [下一个更大元素 III](/problems/next-greater-element-iii) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/next-greater-element-ii)
