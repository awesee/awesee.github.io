---
layout:     single
title:      "岛屿的最大面积"
date:       2017-11-26 21:30:00 +0800
categories: [Leetcode]
tags:       [Depth-first Search, Array]
permalink:  /problems/max-area-of-island/
---

## 695. 岛屿的最大面积 (Medium)

{% raw %}

<p>给定一个包含了一些 <code>0</code> 和 <code>1</code> 的非空二维数组&nbsp;<code>grid</code> 。</p>

<p>一个&nbsp;<strong>岛屿</strong>&nbsp;是由一些相邻的&nbsp;<code>1</code>&nbsp;(代表土地) 构成的组合，这里的「相邻」要求两个 <code>1</code> 必须在水平或者竖直方向上相邻。你可以假设&nbsp;<code>grid</code> 的四个边缘都被 <code>0</code>（代表水）包围着。</p>

<p>找到给定的二维数组中最大的岛屿面积。(如果没有岛屿，则返回面积为 <code>0</code> 。)</p>

<p>&nbsp;</p>

<p><strong>示例 1:</strong></p>

<pre>[[0,0,1,0,0,0,0,1,0,0,0,0,0],
 [0,0,0,0,0,0,0,1,1,1,0,0,0],
 [0,1,1,0,1,0,0,0,0,0,0,0,0],
 [0,1,0,0,1,1,0,0,<strong>1</strong>,0,<strong>1</strong>,0,0],
 [0,1,0,0,1,1,0,0,<strong>1</strong>,<strong>1</strong>,<strong>1</strong>,0,0],
 [0,0,0,0,0,0,0,0,0,0,<strong>1</strong>,0,0],
 [0,0,0,0,0,0,0,1,1,1,0,0,0],
 [0,0,0,0,0,0,0,1,1,0,0,0,0]]
</pre>

<p>对于上面这个给定矩阵应返回&nbsp;<code>6</code>。注意答案不应该是 <code>11</code> ，因为岛屿只能包含水平或垂直的四个方向的 <code>1</code> 。</p>

<p><strong>示例 2:</strong></p>

<pre>[[0,0,0,0,0,0,0,0]]</pre>

<p>对于上面这个给定的矩阵, 返回&nbsp;<code>0</code>。</p>

<p>&nbsp;</p>

<p><strong>注意:&nbsp;</strong>给定的矩阵<code>grid</code>&nbsp;的长度和宽度都不超过 50。</p>

{% endraw %}

### 相关话题
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]

### 相似题目
  1. [岛屿数量](/problems/number-of-islands) (Medium)
  1. [岛屿的周长](/problems/island-perimeter) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/max-area-of-island)
