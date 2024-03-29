---
layout:     single
title:      "最佳买卖股票时机含冷冻期"
date:       2016-11-05 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Dynamic Programming]
permalink:  /problems/best-time-to-buy-and-sell-stock-with-cooldown/
---

## 309. 最佳买卖股票时机含冷冻期 (Medium)

{% raw %}

<p>给定一个整数数组，其中第<em>&nbsp;i</em>&nbsp;个元素代表了第&nbsp;<em>i</em>&nbsp;天的股票价格 。​</p>

<p>设计一个算法计算出最大利润。在满足以下约束条件下，你可以尽可能地完成更多的交易（多次买卖一支股票）:</p>

<ul>
	<li>你不能同时参与多笔交易（你必须在再次购买前出售掉之前的股票）。</li>
	<li>卖出股票后，你无法在第二天买入股票 (即冷冻期为 1 天)。</li>
</ul>

<p><strong>示例:</strong></p>

<pre><strong>输入:</strong> [1,2,3,0,2]
<strong>输出: </strong>3 
<strong>解释:</strong> 对应的交易状态为: [买入, 卖出, 冷冻期, 买入, 卖出]</pre>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

### 相似题目
  1. [买卖股票的最佳时机](/problems/best-time-to-buy-and-sell-stock) (Easy)
  1. [买卖股票的最佳时机 II](/problems/best-time-to-buy-and-sell-stock-ii) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/best-time-to-buy-and-sell-stock-with-cooldown)
