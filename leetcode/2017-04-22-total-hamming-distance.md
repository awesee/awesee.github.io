---
layout:     single
title:      "汉明距离总和"
date:       2017-04-22 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Array, Math]
permalink:  /problems/total-hamming-distance/
---

## 477. 汉明距离总和 (Medium)

{% raw %}

<p>两个整数的 <a href="https://baike.baidu.com/item/%E6%B1%89%E6%98%8E%E8%B7%9D%E7%A6%BB/475174?fr=aladdin">汉明距离</a> 指的是这两个数字的二进制数对应位不同的数量。</p>

<p>给你一个整数数组 <code>nums</code>，请你计算并返回 <code>nums</code> 中任意两个数之间汉明距离的总和。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [4,14,2]
<strong>输出：</strong>6
<strong>解释：</strong>在二进制表示中，4 表示为 0100 ，14 表示为 1110 ，2表示为 0010 。（这样表示是为了体现后四位之间关系）
所以答案为：
HammingDistance(4, 14) + HammingDistance(4, 2) + HammingDistance(14, 2) = 2 + 2 + 2 = 6
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [4,14,4]
<strong>输出：</strong>4
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 10<sup>5</sup></code></li>
	<li><code>0 <= nums[i] <= 10<sup>9</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/openset/leetcode/tree/master/tag/bit-manipulation/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

### 相似题目
  1. [汉明距离](/problems/hamming-distance) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/total-hamming-distance)
