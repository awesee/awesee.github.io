---
layout:     single
title:      "无重叠区间"
date:       2017-03-11 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Array, Dynamic Programming, Sorting]
permalink:  /problems/non-overlapping-intervals/
---

## 435. 无重叠区间 (Medium)

{% raw %}

<p>给定一个区间的集合，找到需要移除区间的最小数量，使剩余区间互不重叠。</p>

<p><strong>注意:</strong></p>

<ol>
	<li>可以认为区间的终点总是大于它的起点。</li>
	<li>区间 [1,2] 和 [2,3] 的边界相互&ldquo;接触&rdquo;，但没有相互重叠。</li>
</ol>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> [ [1,2], [2,3], [3,4], [1,3] ]

<strong>输出:</strong> 1

<strong>解释:</strong> 移除 [1,3] 后，剩下的区间没有重叠。
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> [ [1,2], [1,2], [1,2] ]

<strong>输出:</strong> 2

<strong>解释:</strong> 你需要移除两个 [1,2] 来使剩下的区间没有重叠。
</pre>

<p><strong>示例 3:</strong></p>

<pre>
<strong>输入:</strong> [ [1,2], [2,3] ]

<strong>输出:</strong> 0

<strong>解释:</strong> 你不需要移除任何区间，因为它们已经是无重叠的了。
</pre>

{% endraw %}

### 相关话题
  [[贪心](https://github.com/awesee/leetcode/tree/main/tag/greedy/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]

### 相似题目
  1. [用最少数量的箭引爆气球](/problems/minimum-number-of-arrows-to-burst-balloons) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/non-overlapping-intervals)
