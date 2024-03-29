---
layout:     single
title:      "路径交叉"
date:       2016-12-01 21:30:00 +0800
categories: [Leetcode]
tags:       [Geometry, Array, Math]
permalink:  /problems/self-crossing/
---

## 335. 路径交叉 (Hard)

{% raw %}

<p>给定一个含有&nbsp;<code>n</code>&nbsp;个正数的数组&nbsp;<em>x</em>。从点&nbsp;<code>(0,0)</code>&nbsp;开始，先向北移动&nbsp;<code>x[0]</code>&nbsp;米，然后向西移动&nbsp;<code>x[1]</code>&nbsp;米，向南移动&nbsp;<code>x[2]</code>&nbsp;米，向东移动&nbsp;<code>x[3]</code>&nbsp;米，持续移动。也就是说，每次移动后你的方位会发生逆时针变化。</p>

<p>编写一个&nbsp;<code>O(1)</code>&nbsp;空间复杂度的一趟扫描算法，判断你所经过的路径是否相交。</p>

<p>&nbsp;</p>

<p><strong>示例&nbsp;1:</strong></p>

<pre><strong>┌───┐
│ &nbsp; │
└───┼──&gt;
&nbsp; &nbsp; │

输入: </strong><code>[2,1,1,2]</code>
<strong>输出:</strong> true 
</pre>

<p><strong>示例&nbsp;2:</strong></p>

<pre><strong>┌──────┐
│ &nbsp; &nbsp; &nbsp;│
│
│
└────────────&gt;

输入: </strong><code>[1,2,3,4]</code>
<strong>输出: </strong>false 
</pre>

<p><strong>示例 3:</strong></p>

<pre><strong>┌───┐
│ &nbsp; │
└───┼&gt;

输入:</strong> <code>[1,1,1,1]</code>
<strong>输出:</strong> true 
</pre>

{% endraw %}

### 相关话题
  [[几何](https://github.com/awesee/leetcode/tree/main/tag/geometry/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/self-crossing)
