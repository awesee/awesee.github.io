---
layout:     single
title:      "种花问题"
date:       2017-08-28 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Array]
permalink:  /problems/can-place-flowers/
---

## 605. 种花问题 (Easy)

{% raw %}

<p>假设有一个很长的花坛，一部分地块种植了花，另一部分却没有。可是，花不能种植在相邻的地块上，它们会争夺水源，两者都会死去。</p>

<p>给你一个整数数组  <code>flowerbed</code> 表示花坛，由若干 <code>0</code> 和 <code>1</code> 组成，其中 <code>0</code> 表示没种植花，<code>1</code> 表示种植了花。另有一个数 <code>n</code><strong> </strong>，能否在不打破种植规则的情况下种入 <code>n</code><strong> </strong>朵花？能则返回 <code>true</code> ，不能则返回 <code>false</code>。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>flowerbed = [1,0,0,0,1], n = 1
<strong>输出：</strong>true
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>flowerbed = [1,0,0,0,1], n = 2
<strong>输出：</strong>false
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= flowerbed.length <= 2 * 10<sup>4</sup></code></li>
	<li><code>flowerbed[i]</code> 为 <code>0</code> 或 <code>1</code></li>
	<li><code>flowerbed</code> 中不存在相邻的两朵花</li>
	<li><code>0 <= n <= flowerbed.length</code></li>
</ul>

{% endraw %}

### 相关话题
  [[贪心算法](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]

### 相似题目
  1. [提莫攻击](/problems/teemo-attacking) (Medium)
  1. [行星碰撞](/problems/asteroid-collision) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/can-place-flowers)
