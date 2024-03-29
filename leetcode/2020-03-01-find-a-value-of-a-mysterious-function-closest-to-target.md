---
layout:     single
title:      "找到最接近目标值的函数值"
date:       2020-03-01 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Segment Tree, Array, Binary Search]
permalink:  /problems/find-a-value-of-a-mysterious-function-closest-to-target/
---

## 1521. 找到最接近目标值的函数值 (Hard)

{% raw %}

<p><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/07/19/change.png" style="height: 312px; width: 635px;"></p>

<p>Winston 构造了一个如上所示的函数&nbsp;<code>func</code>&nbsp;。他有一个整数数组&nbsp;<code>arr</code>&nbsp;和一个整数&nbsp;<code>target</code>&nbsp;，他想找到让&nbsp;<code>|func(arr, l, r) - target|</code>&nbsp;最小的 <code>l</code>&nbsp;和 <code>r</code>&nbsp;。</p>

<p>请你返回&nbsp;<code>|func(arr, l, r) - target|</code>&nbsp;的最小值。</p>

<p>请注意，&nbsp;<code>func</code> 的输入参数&nbsp;<code>l</code> 和&nbsp;<code>r</code>&nbsp;需要满足&nbsp;<code>0 &lt;= l, r &lt; arr.length</code>&nbsp;。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>arr = [9,12,3,7,15], target = 5
<strong>输出：</strong>2
<strong>解释：</strong>所有可能的 [l,r] 数对包括 [[0,0],[1,1],[2,2],[3,3],[4,4],[0,1],[1,2],[2,3],[3,4],[0,2],[1,3],[2,4],[0,3],[1,4],[0,4]]， Winston 得到的相应结果为 [9,12,3,7,15,8,0,3,7,0,0,3,0,0,0] 。最接近 5 的值是 7 和 3，所以最小差值为 2 。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>arr = [1000000,1000000,1000000], target = 1
<strong>输出：</strong>999999
<strong>解释：</strong>Winston 输入函数的所有可能 [l,r] 数对得到的函数值都为 1000000 ，所以最小差值为 999999 。
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>arr = [1,2,4,8,16], target = 0
<strong>输出：</strong>0
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= arr.length &lt;= 10^5</code></li>
	<li><code>1 &lt;= arr[i] &lt;= 10^6</code></li>
	<li><code>0 &lt;= target &lt;= 10^7</code></li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[线段树](https://github.com/awesee/leetcode/tree/main/tag/segment-tree/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/find-a-value-of-a-mysterious-function-closest-to-target)
