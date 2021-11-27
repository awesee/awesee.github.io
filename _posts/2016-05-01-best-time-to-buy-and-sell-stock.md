---
layout:     single
title:      "买卖股票的最佳时机"
date:       2016-05-01 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Dynamic Programming]
permalink:  /problems/best-time-to-buy-and-sell-stock/
---

## 121. 买卖股票的最佳时机 (Easy)

{% raw %}

<p>给定一个数组 <code>prices</code> ，它的第 <code>i</code> 个元素 <code>prices[i]</code> 表示一支给定股票第 <code>i</code> 天的价格。</p>

<p>你只能选择 <strong>某一天</strong> 买入这只股票，并选择在 <strong>未来的某一个不同的日子</strong> 卖出该股票。设计一个算法来计算你所能获取的最大利润。</p>

<p>返回你可以从这笔交易中获取的最大利润。如果你不能获取任何利润，返回 <code>0</code> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>[7,1,5,3,6,4]
<strong>输出：</strong>5
<strong>解释：</strong>在第 2 天（股票价格 = 1）的时候买入，在第 5 天（股票价格 = 6）的时候卖出，最大利润 = 6-1 = 5 。
     注意利润不能是 7-1 = 6, 因为卖出价格需要大于买入价格；同时，你不能在买入前卖出股票。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>prices = [7,6,4,3,1]
<strong>输出：</strong>0
<strong>解释：</strong>在这种情况下, 没有交易完成, 所以最大利润为 0。
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= prices.length <= 10<sup>5</sup></code></li>
	<li><code>0 <= prices[i] <= 10<sup>4</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

### 相似题目
  1. [最大子序和](/problems/maximum-subarray) (Easy)
  1. [买卖股票的最佳时机 II](/problems/best-time-to-buy-and-sell-stock-ii) (Easy)
  1. [买卖股票的最佳时机 III](/problems/best-time-to-buy-and-sell-stock-iii) (Hard)
  1. [买卖股票的最佳时机 IV](/problems/best-time-to-buy-and-sell-stock-iv) (Hard)
  1. [最佳买卖股票时机含冷冻期](/problems/best-time-to-buy-and-sell-stock-with-cooldown) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/best-time-to-buy-and-sell-stock)
