---
layout:     single
title:      "圆形靶内的最大飞镖数量"
date:       2019-12-24 21:30:00 +0800
categories: [Leetcode]
tags:       [Geometry, Array, Math]
permalink:  /problems/maximum-number-of-darts-inside-of-a-circular-dartboard/
---

## 1453. 圆形靶内的最大飞镖数量 (Hard)

{% raw %}

<p>墙壁上挂着一个圆形的飞镖靶。现在请你蒙着眼睛向靶上投掷飞镖。</p>

<p>投掷到墙上的飞镖用二维平面上的点坐标数组表示。飞镖靶的半径为 <code>r</code> 。</p>

<p>请返回能够落在 <strong>任意</strong> 半径为 <code>r</code> 的圆形靶内或靶上的最大飞镖数。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<p><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/05/16/sample_1_1806.png" style="height: 159px; width: 186px;"></p>

<pre><strong>输入：</strong>points = [[-2,0],[2,0],[0,2],[0,-2]], r = 2
<strong>输出：</strong>4
<strong>解释：</strong>如果圆形的飞镖靶的圆心为 (0,0) ，半径为 2 ，所有的飞镖都落在靶上，此时落在靶上的飞镖数最大，值为 4 。
</pre>

<p><strong>示例 2：</strong></p>

<p><strong><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/05/16/sample_2_1806.png" style="height: 183px; width: 224px;"></strong></p>

<pre><strong>输入：</strong>points = [[-3,0],[3,0],[2,6],[5,4],[0,9],[7,8]], r = 5
<strong>输出：</strong>5
<strong>解释：</strong>如果圆形的飞镖靶的圆心为 (0,4) ，半径为 5 ，则除了 (7,8) 之外的飞镖都落在靶上，此时落在靶上的飞镖数最大，值为 5 。</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>points = [[-2,0],[2,0],[0,2],[0,-2]], r = 1
<strong>输出：</strong>1
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>points = [[1,2],[3,5],[1,-1],[2,3],[4,1],[1,3]], r = 2
<strong>输出：</strong>4
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= points.length &lt;= 100</code></li>
	<li><code>points[i].length == 2</code></li>
	<li><code>-10^4 &lt;= points[i][0], points[i][1] &lt;= 10^4</code></li>
	<li><code>1 &lt;= r &lt;= 5000</code></li>
</ul>

{% endraw %}

### 相关话题
  [[几何](https://github.com/awesee/leetcode/tree/main/tag/geometry/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/maximum-number-of-darts-inside-of-a-circular-dartboard)
