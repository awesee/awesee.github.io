---
layout:     single
title:      "接雨水 II"
date:       2017-02-11 21:30:00 +0800
categories: [Leetcode]
tags:       [Breadth-First Search, Array, Matrix, Heap (Priority Queue)]
permalink:  /problems/trapping-rain-water-ii/
---

## 407. 接雨水 II (Hard)

{% raw %}

<p>给你一个 <code>m x n</code>&nbsp;的矩阵，其中的值均为非负整数，代表二维高度图每个单元的高度，请计算图中形状最多能接多少体积的雨水。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre>给出如下 3x6 的高度图:
[
  [1,4,3,1,3,2],
  [3,2,1,3,2,4],
  [2,3,3,2,3,1]
]

返回 4 。
</pre>

<p><img src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2018/10/12/rainwater_empty.png" style="width: 500px;"></p>

<p>如上图所示，这是下雨前的高度图<code>[[1,4,3,1,3,2],[3,2,1,3,2,4],[2,3,3,2,3,1]]</code> 的状态。</p>

<p>&nbsp;</p>

<p><img src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2018/10/12/rainwater_fill.png" style="width: 500px;"></p>

<p>下雨后，雨水将会被存储在这些方块中。总的接雨水量是4。</p>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= m, n &lt;= 110</code></li>
	<li><code>0 &lt;= heightMap[i][j] &lt;= 20000</code></li>
</ul>

{% endraw %}

### 相关话题
  [[广度优先搜索](https://github.com/openset/leetcode/tree/master/tag/breadth-first-search/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[矩阵](https://github.com/openset/leetcode/tree/master/tag/matrix/README.md)]
  [[堆（优先队列）](https://github.com/openset/leetcode/tree/master/tag/heap-priority-queue/README.md)]

### 相似题目
  1. [接雨水](/problems/trapping-rain-water) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/trapping-rain-water-ii)
