---
layout:     single
title:      "122. 买卖股票的最佳时机 II (Easy)"
date:       2016-05-02 21:30:00 +0800
categories: [leetcode]
tags:       [greedy, array]
permalink:  /best-time-to-buy-and-sell-stock-ii/
---

<p>给定一个数组，它的第&nbsp;<em>i</em> 个元素是一支给定股票第 <em>i</em> 天的价格。</p>

<p>设计一个算法来计算你所能获取的最大利润。你可以尽可能地完成更多的交易（多次买卖一支股票）。</p>

<p><strong>注意：</strong>你不能同时参与多笔交易（你必须在再次购买前出售掉之前的股票）。</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入:</strong> [7,1,5,3,6,4]
<strong>输出:</strong> 7
<strong>解释:</strong> 在第 2 天（股票价格 = 1）的时候买入，在第 3 天（股票价格 = 5）的时候卖出, 这笔交易所能获得利润 = 5-1 = 4 。
&nbsp;    随后，在第 4 天（股票价格 = 3）的时候买入，在第 5 天（股票价格 = 6）的时候卖出, 这笔交易所能获得利润 = 6-3 = 3 。
</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入:</strong> [1,2,3,4,5]
<strong>输出:</strong> 4
<strong>解释:</strong> 在第 1 天（股票价格 = 1）的时候买入，在第 5 天 （股票价格 = 5）的时候卖出, 这笔交易所能获得利润 = 5-1 = 4 。
&nbsp;    注意你不能在第 1 天和第 2 天接连购买股票，之后再将它们卖出。
&nbsp;    因为这样属于同时参与了多笔交易，你必须在再次购买前出售掉之前的股票。
</pre>

<p><strong>示例&nbsp;3:</strong></p>

<pre><strong>输入:</strong> [7,6,4,3,1]
<strong>输出:</strong> 0
<strong>解释:</strong> 在这种情况下, 没有交易完成, 所以最大利润为 0。</pre>

### 相关话题
  [[贪心算法](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]

### 相似题目
  1. [买卖股票的最佳时机](/best-time-to-buy-and-sell-stock) (Easy)
  1. [买卖股票的最佳时机 III](/best-time-to-buy-and-sell-stock-iii) (Hard)
  1. [买卖股票的最佳时机 IV](/best-time-to-buy-and-sell-stock-iv) (Hard)
  1. [最佳买卖股票时机含冷冻期](/best-time-to-buy-and-sell-stock-with-cooldown) (Medium)
  1. [买卖股票的最佳时机含手续费](/best-time-to-buy-and-sell-stock-with-transaction-fee) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/best-time-to-buy-and-sell-stock-ii)
