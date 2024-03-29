---
layout:     single
title:      "矩形重叠"
date:       2018-04-16 21:30:00 +0800
categories: [Leetcode]
tags:       [Geometry, Math]
permalink:  /problems/rectangle-overlap/
---

## 836. 矩形重叠 (Easy)

{% raw %}

<p>矩形以列表 <code>[x1, y1, x2, y2]</code> 的形式表示，其中 <code>(x1, y1)</code> 为左下角的坐标，<code>(x2, y2)</code> 是右上角的坐标。矩形的上下边平行于 x 轴，左右边平行于 y 轴。</p>

<p>如果相交的面积为 <strong>正</strong> ，则称两矩形重叠。需要明确的是，只在角或边接触的两个矩形不构成重叠。</p>

<p>给出两个矩形 <code>rec1</code> 和 <code>rec2</code> 。如果它们重叠，返回 <code>true</code>；否则，返回 <code>false</code> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>rec1 = [0,0,2,2], rec2 = [1,1,3,3]
<strong>输出：</strong>true
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>rec1 = [0,0,1,1], rec2 = [1,0,2,1]
<strong>输出：</strong>false
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>rec1 = [0,0,1,1], rec2 = [2,2,3,3]
<strong>输出：</strong>false
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>rect1.length == 4</code></li>
	<li><code>rect2.length == 4</code></li>
	<li><code>-10<sup>9</sup> <= rec1[i], rec2[i] <= 10<sup>9</sup></code></li>
	<li><code>rec1[0] <= rec1[2]</code> 且 <code>rec1[1] <= rec1[3]</code></li>
	<li><code>rec2[0] <= rec2[2]</code> 且 <code>rec2[1] <= rec2[3]</code></li>
</ul>

{% endraw %}

### 相关话题
  [[几何](https://github.com/awesee/leetcode/tree/main/tag/geometry/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]

### 相似题目
  1. [矩形面积](/problems/rectangle-area) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/rectangle-overlap)
