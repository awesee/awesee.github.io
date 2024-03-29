---
layout:     single
title:      "数组的均值分割"
date:       2018-03-16 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Array, Math, Dynamic Programming, Bitmask]
permalink:  /problems/split-array-with-same-average/
---

## 805. 数组的均值分割 (Hard)

{% raw %}

<p>给定的整数数组 A ，我们要将 A数组 中的每个元素移动到 B数组 或者 C数组中。（B数组和C数组在开始的时候都为空）</p>

<p>返回<code>true</code> ，当且仅当在我们的完成这样的移动后，可使得B数组的平均值和C数组的平均值相等，并且B数组和C数组都不为空。</p>

<pre>
<strong>示例:</strong>
<strong>输入:</strong> 
[1,2,3,4,5,6,7,8]
<strong>输出:</strong> true
<strong>解释: </strong>我们可以将数组分割为 [1,4,5,8] 和 [2,3,6,7], 他们的平均值都是4.5。
</pre>

<p><strong>注意:</strong></p>

<ul>
	<li><code>A</code> 数组的长度范围为 <code>[1, 30]</code>.</li>
	<li><code>A[i]</code> 的数据范围为 <code>[0, 10000]</code>.</li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/master/tag/bit-manipulation/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/master/tag/array/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/master/tag/math/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/master/tag/dynamic-programming/README.md)]
  [[状态压缩](https://github.com/awesee/leetcode/tree/master/tag/bitmask/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/split-array-with-same-average)
