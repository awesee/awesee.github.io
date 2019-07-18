---
layout:     single
title:      "最接近原点的 K 个点"
date:       2018-08-31 21:30:00 +0800
categories: [Leetcode]
tags:       [Heap, Sort, Divide and Conquer]
permalink:  /k-closest-points-to-origin/
---

## 973. 最接近原点的 K 个点 (Medium)

<p>我们有一个由平面上的点组成的列表 <code>points</code>。需要从中找出 <code>K</code> 个距离原点 <code>(0, 0)</code> 最近的点。</p>

<p>（这里，平面上两点之间的距离是欧几里德距离。）</p>

<p>你可以按任何顺序返回答案。除了点坐标的顺序之外，答案确保是唯一的。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>points = [[1,3],[-2,2]], K = 1
<strong>输出：</strong>[[-2,2]]
<strong>解释： </strong>
(1, 3) 和原点之间的距离为 sqrt(10)，
(-2, 2) 和原点之间的距离为 sqrt(8)，
由于 sqrt(8) &lt; sqrt(10)，(-2, 2) 离原点更近。
我们只需要距离原点最近的 K = 1 个点，所以答案就是 [[-2,2]]。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>points = [[3,3],[5,-1],[-2,4]], K = 2
<strong>输出：</strong>[[3,3],[-2,4]]
（答案 [[-2,4],[3,3]] 也会被接受。）
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= K &lt;= points.length &lt;= 10000</code></li>
	<li><code>-10000 &lt; points[i][0] &lt; 10000</code></li>
	<li><code>-10000 &lt; points[i][1] &lt; 10000</code></li>
</ol>

### 相关话题
  [[堆](https://github.com/openset/leetcode/tree/master/tag/heap/README.md)]
  [[排序](https://github.com/openset/leetcode/tree/master/tag/sort/README.md)]
  [[分治算法](https://github.com/openset/leetcode/tree/master/tag/divide-and-conquer/README.md)]

### 相似题目
  1. [数组中的第K个最大元素](/kth-largest-element-in-an-array) (Medium)
  1. [前 K 个高频元素](/top-k-frequent-elements) (Medium)
  1. [前K个高频单词](/top-k-frequent-words) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/k-closest-points-to-origin)
