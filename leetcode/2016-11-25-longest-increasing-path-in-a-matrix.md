---
layout:     single
title:      "矩阵中的最长递增路径"
date:       2016-11-25 21:30:00 +0800
categories: [leetcode]
tags:       [Depth-first Search, Topological Sort, Memoization]
permalink:  /longest-increasing-path-in-a-matrix/
---

## 329. 矩阵中的最长递增路径 (Hard)

<p>给定一个整数矩阵，找出最长递增路径的长度。</p>

<p>对于每个单元格，你可以往上，下，左，右四个方向移动。 你不能在对角线方向上移动或移动到边界外（即不允许环绕）。</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入: </strong>nums = 
[
  [<strong>9</strong>,9,4],
  [<strong>6</strong>,6,8],
  [<strong>2</strong>,<strong>1</strong>,1]
] 
<strong>输出:</strong> 4 
<strong>解释:</strong> 最长递增路径为&nbsp;<code>[1, 2, 6, 9]</code>。</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入:</strong> nums = 
[
  [<strong>3</strong>,<strong>4</strong>,<strong>5</strong>],
  [3,2,<strong>6</strong>],
  [2,2,1]
] 
<strong>输出: </strong>4 
<strong>解释: </strong>最长递增路径是&nbsp;<code>[3, 4, 5, 6]</code>。注意不允许在对角线方向上移动。
</pre>

### 相关话题
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[拓扑排序](https://github.com/openset/leetcode/tree/master/tag/topological-sort/README.md)]
  [[记忆化](https://github.com/openset/leetcode/tree/master/tag/memoization/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/longest-increasing-path-in-a-matrix)
