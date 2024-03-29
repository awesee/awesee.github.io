---
layout:     single
title:      "向下取整数对和"
date:       2021-02-05 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Math, Binary Search, Prefix Sum]
permalink:  /problems/sum-of-floored-pairs/
---

## 1862. 向下取整数对和 (Hard)

{% raw %}

<p>给你一个整数数组 <code>nums</code> ，请你返回所有下标对 <code>0 &lt;= i, j &lt; nums.length</code> 的 <code>floor(nums[i] / nums[j])</code> 结果之和。由于答案可能会很大，请你返回答案对<code>10<sup>9</sup> + 7</code> <strong>取余</strong> 的结果。</p>

<p>函数 <code>floor()</code> 返回输入数字的整数部分。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre><b>输入：</b>nums = [2,5,9]
<b>输出：</b>10
<strong>解释：</strong>
floor(2 / 5) = floor(2 / 9) = floor(5 / 9) = 0
floor(2 / 2) = floor(5 / 5) = floor(9 / 9) = 1
floor(5 / 2) = 2
floor(9 / 2) = 4
floor(9 / 5) = 1
我们计算每一个数对商向下取整的结果并求和得到 10 。
</pre>

<p><strong>示例 2：</strong></p>

<pre><b>输入：</b>nums = [7,7,7,7,7,7,7]
<b>输出：</b>49
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= nums.length &lt;= 10<sup>5</sup></code></li>
	<li><code>1 &lt;= nums[i] &lt;= 10<sup>5</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[前缀和](https://github.com/awesee/leetcode/tree/main/tag/prefix-sum/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/sum-of-floored-pairs)
