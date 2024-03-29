---
layout:     single
title:      "矩形面积 II"
date:       2018-04-30 21:30:00 +0800
categories: [Leetcode]
tags:       [Segment Tree, Array, Ordered Set, Line Sweep]
permalink:  /problems/rectangle-area-ii/
---

## 850. 矩形面积 II (Hard)

{% raw %}

<p>我们给出了一个（轴对齐的）矩形列表&nbsp;<code>rectangles</code>&nbsp;。 对于&nbsp;<code>rectangle[i] = [x1, y1, x2, y2]</code>，其中（x1，y1）是矩形&nbsp;<code>i</code>&nbsp;左下角的坐标，（x2，y2）是该矩形右上角的坐标。</p>

<p>找出平面中所有矩形叠加覆盖后的总面积。 由于答案可能太大，<strong>请返回它对 10 ^ 9 + 7 取模的结果</strong>。</p>

<p><img alt="" src="https://s3-lc-upload.s3.amazonaws.com/uploads/2018/06/06/rectangle_area_ii_pic.png" style="height: 360px; width: 480px;"></p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>[[0,0,2,2],[1,0,2,3],[1,0,3,1]]
<strong>输出：</strong>6
<strong>解释：</strong>如图所示。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>[[0,0,1000000000,1000000000]]
<strong>输出：</strong>49
<strong>解释：</strong>答案是 10^18 对 (10^9 + 7) 取模的结果， 即 (10^9)^2 &rarr; (-7)^2 = 49 。
</pre>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= rectangles.length &lt;= 200</code></li>
	<li><code>rectanges[i].length = 4</code></li>
	<li><code>0 &lt;= rectangles[i][j] &lt;= 10^9</code></li>
	<li>矩形叠加覆盖后的总面积不会超越&nbsp;<code>2^63 - 1</code>&nbsp;，这意味着可以用一个&nbsp;64 位有符号整数来保存面积结果。</li>
</ul>

{% endraw %}

### 相关话题
  [[线段树](https://github.com/awesee/leetcode/tree/main/tag/segment-tree/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[有序集合](https://github.com/awesee/leetcode/tree/main/tag/ordered-set/README.md)]
  [[扫描线](https://github.com/awesee/leetcode/tree/main/tag/line-sweep/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/rectangle-area-ii)
