---
layout:     single
title:      "直线上最多的点数"
date:       2016-05-29 21:30:00 +0800
categories: [Leetcode]
tags:       [Geometry, Hash Table, Math]
permalink:  /problems/max-points-on-a-line/
---

## 149. 直线上最多的点数 (Hard)

{% raw %}

<p>给你一个数组 <code>points</code> ，其中 <code>points[i] = [x<sub>i</sub>, y<sub>i</sub>]</code> 表示 <strong>X-Y</strong> 平面上的一个点。求最多有多少个点在同一条直线上。</p>

<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2021/02/25/plane1.jpg" style="width: 300px; height: 294px;" />
<pre>
<strong>输入：</strong>points = [[1,1],[2,2],[3,3]]
<strong>输出：</strong>3
</pre>

<p><strong>示例 2：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2021/02/25/plane2.jpg" style="width: 300px; height: 294px;" />
<pre>
<strong>输入：</strong>points = [[1,1],[3,2],[5,3],[4,1],[2,3],[1,4]]
<strong>输出：</strong>4
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= points.length <= 300</code></li>
	<li><code>points[i].length == 2</code></li>
	<li><code>-10<sup>4</sup> <= x<sub>i</sub>, y<sub>i</sub> <= 10<sup>4</sup></code></li>
	<li><code>points</code> 中的所有点 <strong>互不相同</strong></li>
</ul>

{% endraw %}

### 相关话题
  [[几何](https://github.com/awesee/leetcode/tree/main/tag/geometry/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]

### 相似题目
  1. [直线镜像](/problems/line-reflection) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/max-points-on-a-line)
