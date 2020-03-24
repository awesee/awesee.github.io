---
layout:     single
title:      "方阵中战斗力最弱的 K 行"
date:       2019-08-30 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Binary Search]
permalink:  /problems/the-k-weakest-rows-in-a-matrix/
---

## 1337. 方阵中战斗力最弱的 K 行 (Easy)

{% raw %}

<p>给你一个大小为&nbsp;<code>m&nbsp;* n</code>&nbsp;的方阵&nbsp;<code>mat</code>，方阵由若干军人和平民组成，分别用 0 和 1 表示。</p>

<p>请你返回方阵中战斗力最弱的&nbsp;<code>k</code>&nbsp;行的索引，按从最弱到最强排序。</p>

<p>如果第&nbsp;<em><strong>i</strong></em>&nbsp;行的军人数量少于第&nbsp;<em><strong>j</strong></em>&nbsp;行，或者两行军人数量相同但<em><strong> i</strong></em> 小于 <em><strong>j</strong></em>，那么我们认为第<em><strong> i </strong></em>行的战斗力比第<em><strong> j </strong></em>行弱。</p>

<p>军人 <strong>总是</strong> 排在一行中的靠前位置，也就是说 1 总是出现在 0 之前。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>mat = 
[[1,1,0,0,0],
 [1,1,1,1,0],
 [1,0,0,0,0],
 [1,1,0,0,0],
 [1,1,1,1,1]], 
k = 3
<strong>输出：</strong>[2,0,3]
<strong>解释：</strong>
每行中的军人数目：
行 0 -&gt; 2 
行 1 -&gt; 4 
行 2 -&gt; 1 
行 3 -&gt; 2 
行 4 -&gt; 5 
从最弱到最强对这些行排序后得到 [2,0,3,1,4]
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>mat = 
[[1,0,0,0],
&nbsp;[1,1,1,1],
&nbsp;[1,0,0,0],
&nbsp;[1,0,0,0]], 
k = 2
<strong>输出：</strong>[0,2]
<strong>解释：</strong> 
每行中的军人数目：
行 0 -&gt; 1 
行 1 -&gt; 4 
行 2 -&gt; 1 
行 3 -&gt; 1 
从最弱到最强对这些行排序后得到 [0,2,3,1]
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>m == mat.length</code></li>
	<li><code>n == mat[i].length</code></li>
	<li><code>2 &lt;= n, m &lt;= 100</code></li>
	<li><code>1 &lt;= k &lt;= m</code></li>
	<li><code>matrix[i][j]</code> 不是 0 就是 1</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[二分查找](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/the-k-weakest-rows-in-a-matrix)
