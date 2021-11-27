---
layout:     single
title:      "接雨水"
date:       2016-02-12 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Array, Two Pointers, Dynamic Programming, Monotonic Stack]
permalink:  /problems/trapping-rain-water/
---

## 42. 接雨水 (Hard)

{% raw %}

<p>给定 <em>n</em> 个非负整数表示每个宽度为 1 的柱子的高度图，计算按此排列的柱子，下雨之后能接多少雨水。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<p><img src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2018/10/22/rainwatertrap.png" style="height: 161px; width: 412px;" /></p>

<pre>
<strong>输入：</strong>height = [0,1,0,2,1,0,1,3,2,1,2,1]
<strong>输出：</strong>6
<strong>解释：</strong>上面是由数组 [0,1,0,2,1,0,1,3,2,1,2,1] 表示的高度图，在这种情况下，可以接 6 个单位的雨水（蓝色部分表示雨水）。 
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>height = [4,2,0,3,2,5]
<strong>输出：</strong>9
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>n == height.length</code></li>
	<li><code>0 <= n <= 3 * 10<sup>4</sup></code></li>
	<li><code>0 <= height[i] <= 10<sup>5</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[栈](https://github.com/awesee/leetcode/tree/main/tag/stack/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[单调栈](https://github.com/awesee/leetcode/tree/main/tag/monotonic-stack/README.md)]

### 相似题目
  1. [盛最多水的容器](/problems/container-with-most-water) (Medium)
  1. [除自身以外数组的乘积](/problems/product-of-array-except-self) (Medium)
  1. [接雨水 II](/problems/trapping-rain-water-ii) (Hard)
  1. [倒水](/problems/pour-water) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/trapping-rain-water)
