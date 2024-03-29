---
layout:     single
title:      "统计全 1 子矩形"
date:       2020-02-13 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Array, Dynamic Programming, Matrix, Monotonic Stack]
permalink:  /problems/count-submatrices-with-all-ones/
---

## 1504. 统计全 1 子矩形 (Medium)

{% raw %}

<p>给你一个只包含 0 和 1 的&nbsp;<code>rows * columns</code>&nbsp;矩阵&nbsp;<code>mat</code>&nbsp;，请你返回有多少个&nbsp;<strong>子矩形</strong>&nbsp;的元素全部都是 1 。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>mat = [[1,0,1],
&nbsp;           [1,1,0],
&nbsp;           [1,1,0]]
<strong>输出：</strong>13
<strong>解释：
</strong>有 <strong>6</strong>&nbsp;个 1x1 的矩形。
有 <strong>2</strong> 个 1x2 的矩形。
有 <strong>3</strong> 个 2x1 的矩形。
有 <strong>1</strong> 个 2x2 的矩形。
有 <strong>1</strong> 个 3x1 的矩形。
矩形数目总共 = 6 + 2 + 3 + 1 + 1 = <strong>13</strong>&nbsp;。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>mat = [[0,1,1,0],
&nbsp;           [0,1,1,1],
&nbsp;           [1,1,1,0]]
<strong>输出：</strong>24
<strong>解释：</strong>
有 <strong>8</strong> 个 1x1 的子矩形。
有 <strong>5</strong> 个 1x2 的子矩形。
有 <strong>2</strong> 个 1x3 的子矩形。
有 <strong>4</strong> 个 2x1 的子矩形。
有 <strong>2</strong> 个 2x2 的子矩形。
有 <strong>2</strong> 个 3x1 的子矩形。
有 <strong>1</strong> 个 3x2 的子矩形。
矩形数目总共 = 8 + 5 + 2 + 4 + 2 + 2 + 1 = <strong>24</strong><strong> 。</strong>
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>mat = [[1,1,1,1,1,1]]
<strong>输出：</strong>21
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>mat = [[1,0,1],[0,1,0],[1,0,1]]
<strong>输出：</strong>5
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= rows&nbsp;&lt;= 150</code></li>
	<li><code>1 &lt;= columns&nbsp;&lt;= 150</code></li>
	<li><code>0 &lt;= mat[i][j] &lt;= 1</code></li>
</ul>

{% endraw %}

### 相关话题
  [[栈](https://github.com/awesee/leetcode/tree/master/tag/stack/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/master/tag/array/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/master/tag/dynamic-programming/README.md)]
  [[矩阵](https://github.com/awesee/leetcode/tree/master/tag/matrix/README.md)]
  [[单调栈](https://github.com/awesee/leetcode/tree/master/tag/monotonic-stack/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/count-submatrices-with-all-ones)
