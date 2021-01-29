---
layout:     single
title:      "戳气球"
date:       2016-11-08 21:30:00 +0800
categories: [Leetcode]
tags:       [Divide and Conquer, Dynamic Programming]
permalink:  /problems/burst-balloons/
---

## 312. 戳气球 (Hard)

{% raw %}

<p>有 <code>n</code> 个气球，编号为<code>0</code> 到 <code>n - 1</code>，每个气球上都标有一个数字，这些数字存在数组 <code>nums</code> 中。</p>

<p>现在要求你戳破所有的气球。戳破第 <code>i</code> 个气球，你可以获得 <code>nums[i - 1] * nums[i] * nums[i + 1]</code> 枚硬币。 这里的 <code>i - 1</code> 和 <code>i + 1</code> 代表和 <code>i</code> 相邻的两个气球的序号。如果 <code>i - 1</code>或 <code>i + 1</code> 超出了数组的边界，那么就当它是一个数字为 <code>1</code> 的气球。</p>

<p>求所能获得硬币的最大数量。</p>

<p> </p>
<strong>示例 1：</strong>

<pre>
<strong>输入：</strong>nums = [3,1,5,8]
<strong>输出：</strong>167
<strong>解释：</strong>
nums = [3,1,5,8] --> [3,5,8] --> [3,8] --> [8] --> []
coins =  3*1*5    +   3*5*8   +  1*3*8  + 1*8*1 = 167</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [1,5]
<strong>输出：</strong>10
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>n == nums.length</code></li>
	<li><code>1 <= n <= 500</code></li>
	<li><code>0 <= nums[i] <= 100</code></li>
</ul>

{% endraw %}

### 相关话题
  [[分治算法](https://github.com/openset/leetcode/tree/master/tag/divide-and-conquer/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### 相似题目
  1. [合并石头的最低成本](/problems/minimum-cost-to-merge-stones) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/burst-balloons)
