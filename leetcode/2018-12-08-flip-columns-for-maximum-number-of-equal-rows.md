---
layout:     single
title:      "按列翻转得到最大值等行数"
date:       2018-12-08 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, Matrix]
permalink:  /problems/flip-columns-for-maximum-number-of-equal-rows/
---

## 1072. 按列翻转得到最大值等行数 (Medium)

{% raw %}

<p>给定由若干 0 和 1 组成的矩阵 <code>matrix</code>，从中选出任意数量的列并翻转其上的 <strong>每个 </strong>单元格。翻转后，单元格的值从 0 变成 1，或者从 1 变为 0 。</p>

<p>回经过一些翻转后，行与行之间所有值都相等的最大行数。</p>

<p> </p>

<ol>
</ol>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>[[0,1],[1,1]]
<strong>输出：</strong>1
<strong>解释：</strong>不进行翻转，有 1 行所有值都相等。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>[[0,1],[1,0]]
<strong>输出：</strong>2
<strong>解释：</strong>翻转第一列的值之后，这两行都由相等的值组成。
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>[[0,0,0],[0,0,1],[1,1,0]]
<strong>输出：</strong>2
<strong>解释：</strong>翻转前两列的值之后，后两行由相等的值组成。</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 <= matrix.length <= 300</code></li>
	<li><code>1 <= matrix[i].length <= 300</code></li>
	<li>所有 <code>matrix[i].length</code> 都相等</li>
	<li><code>matrix[i][j]</code> 为 <code>0</code> 或 <code>1</code></li>
</ol>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[矩阵](https://github.com/openset/leetcode/tree/master/tag/matrix/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/flip-columns-for-maximum-number-of-equal-rows)
