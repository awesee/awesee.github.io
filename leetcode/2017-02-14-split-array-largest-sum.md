---
layout:     single
title:      "分割数组的最大值"
date:       2017-02-14 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Array, Binary Search, Dynamic Programming]
permalink:  /problems/split-array-largest-sum/
---

## 410. 分割数组的最大值 (Hard)

{% raw %}

<p>给定一个非负整数数组 <code>nums</code> 和一个整数 <code>m</code> ，你需要将这个数组分成 <code>m</code><em> </em>个非空的连续子数组。</p>

<p>设计一个算法使得这 <code>m</code><em> </em>个子数组各自和的最大值最小。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [7,2,5,10,8], m = 2
<strong>输出：</strong>18
<strong>解释：</strong>
一共有四种方法将 nums 分割为 2 个子数组。 其中最好的方式是将其分为 [7,2,5] 和 [10,8] 。
因为此时这两个子数组各自的和的最大值为18，在所有情况中最小。</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [1,2,3,4,5], m = 2
<strong>输出：</strong>9
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>nums = [1,4,4], m = 3
<strong>输出：</strong>4
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 1000</code></li>
	<li><code>0 <= nums[i] <= 10<sup>6</sup></code></li>
	<li><code>1 <= m <= min(50, nums.length)</code></li>
</ul>

{% endraw %}

### 相关话题
  [[贪心](https://github.com/awesee/leetcode/tree/main/tag/greedy/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/split-array-largest-sum)
