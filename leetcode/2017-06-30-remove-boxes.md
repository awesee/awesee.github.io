---
layout:     single
title:      "移除盒子"
date:       2017-06-30 21:30:00 +0800
categories: [Leetcode]
tags:       [Memoization, Array, Dynamic Programming]
permalink:  /problems/remove-boxes/
---

## 546. 移除盒子 (Hard)

{% raw %}

<p>给出一些不同颜色的盒子，盒子的颜色由数字表示，即不同的数字表示不同的颜色。</p>

<p>你将经过若干轮操作去去掉盒子，直到所有的盒子都去掉为止。每一轮你可以移除具有相同颜色的连续 <code>k</code> 个盒子（<code>k >= 1</code>），这样一轮之后你将得到 <code>k * k</code> 个积分。</p>

<p>当你将所有盒子都去掉之后，求你能获得的最大积分和。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>boxes = [1,3,2,2,2,3,4,3,1]
<strong>输出：</strong>23
<strong>解释：</strong>
[1, 3, 2, 2, 2, 3, 4, 3, 1] 
----> [1, 3, 3, 4, 3, 1] (3*3=9 分) 
----> [1, 3, 3, 3, 1] (1*1=1 分) 
----> [1, 1] (3*3=9 分) 
----> [] (2*2=4 分)
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>boxes = [1,1,1]
<strong>输出：</strong>9
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>boxes = [1]
<strong>输出：</strong>1
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= boxes.length <= 100</code></li>
	<li><code>1 <= boxes[i] <= 100</code></li>
</ul>

{% endraw %}

### 相关话题
  [[记忆化搜索](https://github.com/awesee/leetcode/tree/main/tag/memoization/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

### 相似题目
  1. [奇怪的打印机](/problems/strange-printer) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/remove-boxes)
