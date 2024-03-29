---
layout:     single
title:      "元素和小于等于阈值的正方形的最大边长"
date:       2019-07-16 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Binary Search, Matrix, Prefix Sum]
permalink:  /problems/maximum-side-length-of-a-square-with-sum-less-than-or-equal-to-threshold/
---

## 1292. 元素和小于等于阈值的正方形的最大边长 (Medium)

{% raw %}

<p>给你一个大小为 <code>m x n</code> 的矩阵 <code>mat</code> 和一个整数阈值 <code>threshold</code>。</p>

<p>请你返回元素总和小于或等于阈值的正方形区域的最大边长；如果没有这样的正方形区域，则返回 <strong>0 </strong>。<br />
 </p>

<p><strong>示例 1：</strong></p>

<p><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/12/15/e1.png" style="height: 186px; width: 335px;" /></p>

<pre>
<strong>输入：</strong>mat = [[1,1,3,2,4,3,2],[1,1,3,2,4,3,2],[1,1,3,2,4,3,2]], threshold = 4
<strong>输出：</strong>2
<strong>解释：</strong>总和小于或等于 4 的正方形的最大边长为 2，如图所示。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>mat = [[2,2,2,2,2],[2,2,2,2,2],[2,2,2,2,2],[2,2,2,2,2],[2,2,2,2,2]], threshold = 1
<strong>输出：</strong>0
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>mat = [[1,1,1,1],[1,0,0,0],[1,0,0,0],[1,0,0,0]], threshold = 6
<strong>输出：</strong>3
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>mat = [[18,70],[61,1],[25,85],[14,40],[11,96],[97,96],[63,45]], threshold = 40184
<strong>输出：</strong>2
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= m, n <= 300</code></li>
	<li><code>m == mat.length</code></li>
	<li><code>n == mat[i].length</code></li>
	<li><code>0 <= mat[i][j] <= 10000</code></li>
	<li><code>0 <= threshold <= 10^5</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[矩阵](https://github.com/awesee/leetcode/tree/main/tag/matrix/README.md)]
  [[前缀和](https://github.com/awesee/leetcode/tree/main/tag/prefix-sum/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/maximum-side-length-of-a-square-with-sum-less-than-or-equal-to-threshold)
