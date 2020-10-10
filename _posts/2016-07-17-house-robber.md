---
layout:     single
title:      "打家劫舍"
date:       2016-07-17 21:30:00 +0800
categories: [Leetcode]
tags:       [Dynamic Programming]
permalink:  /problems/house-robber/
---

## 198. 打家劫舍 (Easy)

{% raw %}

<p>你是一个专业的小偷，计划偷窃沿街的房屋。每间房内都藏有一定的现金，影响你偷窃的唯一制约因素就是相邻的房屋装有相互连通的防盗系统，<strong>如果两间相邻的房屋在同一晚上被小偷闯入，系统会自动报警</strong>。</p>

<p>给定一个代表每个房屋存放金额的非负整数数组，计算你<strong> 不触动警报装置的情况下 </strong>，一夜之内能够偷窃到的最高金额。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>[1,2,3,1]
<strong>输出：</strong>4
<strong>解释：</strong>偷窃 1 号房屋 (金额 = 1) ，然后偷窃 3 号房屋 (金额 = 3)。
&nbsp;    偷窃到的最高金额 = 1 + 3 = 4 。</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>[2,7,9,3,1]
<strong>输出：</strong>12
<strong>解释：</strong>偷窃 1 号房屋 (金额 = 2), 偷窃 3 号房屋 (金额 = 9)，接着偷窃 5 号房屋 (金额 = 1)。
&nbsp;    偷窃到的最高金额 = 2 + 9 + 1 = 12 。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 &lt;= nums.length &lt;= 100</code></li>
	<li><code>0 &lt;= nums[i] &lt;= 400</code></li>
</ul>

{% endraw %}

### 相关话题
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### 相似题目
  1. [乘积最大子数组](/problems/maximum-product-subarray) (Medium)
  1. [打家劫舍 II](/problems/house-robber-ii) (Medium)
  1. [粉刷房子](/problems/paint-house) (Medium)
  1. [栅栏涂色](/problems/paint-fence) (Easy)
  1. [打家劫舍 III](/problems/house-robber-iii) (Medium)
  1. [不含连续1的非负整数](/problems/non-negative-integers-without-consecutive-ones) (Hard)
  1. [金币路径](/problems/coin-path) (Hard)
  1. [删除与获得点数](/problems/delete-and-earn) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/house-robber)
