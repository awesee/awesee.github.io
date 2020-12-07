---
layout:     single
title:      "情侣牵手"
date:       2018-02-04 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Union Find, Graph]
permalink:  /problems/couples-holding-hands/
---

## 765. 情侣牵手 (Hard)

{% raw %}

<p>N 对情侣坐在连续排列的 2N 个座位上，想要牵到对方的手。 计算最少交换座位的次数，以便每对情侣可以并肩坐在一起。 <em>一</em>次交换可选择任意两人，让他们站起来交换座位。</p>

<p>人和座位用&nbsp;<code>0</code>&nbsp;到&nbsp;<code>2N-1</code>&nbsp;的整数表示，情侣们按顺序编号，第一对是&nbsp;<code>(0, 1)</code>，第二对是&nbsp;<code>(2, 3)</code>，以此类推，最后一对是&nbsp;<code>(2N-2, 2N-1)</code>。</p>

<p>这些情侣的初始座位&nbsp;&nbsp;<code>row[i]</code>&nbsp;是由最初始坐在第 i 个座位上的人决定的。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> row = [0, 2, 1, 3]
<strong>输出:</strong> 1
<strong>解释:</strong> 我们只需要交换row[1]和row[2]的位置即可。
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> row = [3, 2, 0, 1]
<strong>输出:</strong> 0
<strong>解释:</strong> 无需交换座位，所有的情侣都已经可以手牵手了。
</pre>

<p><strong>说明:</strong></p>

<ol>
	<li><code>len(row)</code> 是偶数且数值在&nbsp;<code>[4, 60]</code>范围内。</li>
	<li>可以保证<code>row</code> 是序列&nbsp;<code>0...len(row)-1</code>&nbsp;的一个全排列。</li>
</ol>

{% endraw %}

### 相关话题
  [[贪心算法](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]
  [[并查集](https://github.com/openset/leetcode/tree/master/tag/union-find/README.md)]
  [[图](https://github.com/openset/leetcode/tree/master/tag/graph/README.md)]

### 相似题目
  1. [缺失的第一个正数](/problems/first-missing-positive) (Hard)
  1. [丢失的数字](/problems/missing-number) (Easy)
  1. [相似度为 K 的字符串](/problems/k-similar-strings) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/couples-holding-hands)
