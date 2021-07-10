---
layout:     single
title:      "非重叠矩形中的随机点"
date:       2017-05-12 21:30:00 +0800
categories: [Leetcode]
tags:       [Reservoir Sampling, Math, Binary Search, Ordered Set, Prefix Sum, Randomized]
permalink:  /problems/random-point-in-non-overlapping-rectangles/
---

## 497. 非重叠矩形中的随机点 (Medium)

{% raw %}

<p>给定一个非重叠轴对齐矩形的列表 <code>rects</code>，写一个函数 <code>pick</code> 随机均匀地选取矩形覆盖的空间中的整数点。</p>

<p>提示：</p>

<ol>
	<li><strong>整数点</strong>是具有整数坐标的点。</li>
	<li>矩形周边上的点包含在矩形覆盖的空间中。</li>
	<li>第 <code>i</code> 个矩形 <code>rects [i] = [x1，y1，x2，y2]</code>，其中&nbsp;<code>[x1，y1]</code> 是左下角的整数坐标，<code>[x2，y2]</code> 是右上角的整数坐标。</li>
	<li>每个矩形的长度和宽度不超过 2000。</li>
	<li><code>1 &lt;= rects.length&nbsp;&lt;= 100</code></li>
	<li><code>pick</code> 以整数坐标数组&nbsp;<code>[p_x, p_y]</code>&nbsp;的形式返回一个点。</li>
	<li><code>pick</code> 最多被调用10000次。</li>
</ol>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入: 
</strong>[&quot;Solution&quot;,&quot;pick&quot;,&quot;pick&quot;,&quot;pick&quot;]
[[[[1,1,5,5]]],[],[],[]]
<strong>输出: 
</strong>[null,[4,1],[4,1],[3,3]]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入: 
</strong>[&quot;Solution&quot;,&quot;pick&quot;,&quot;pick&quot;,&quot;pick&quot;,&quot;pick&quot;,&quot;pick&quot;]
[[[[-2,-2,-1,-1],[1,0,3,0]]],[],[],[],[],[]]
<strong>输出: 
</strong>[null,[-1,-2],[2,0],[-2,-1],[3,0],[-2,-2]]</pre>

<p>&nbsp;</p>

<p><strong>输入语法的说明：</strong></p>

<p>输入是两个列表：调用的子例程及其参数。<code>Solution</code> 的构造函数有一个参数，即矩形数组 <code>rects</code>。<code>pick</code> 没有参数。参数总是用列表包装的，即使没有也是如此。</p>

<p>&nbsp;</p>

{% endraw %}

### 相关话题
  [[水塘抽样](https://github.com/openset/leetcode/tree/master/tag/reservoir-sampling/README.md)]
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
  [[二分查找](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]
  [[有序集合](https://github.com/openset/leetcode/tree/master/tag/ordered-set/README.md)]
  [[前缀和](https://github.com/openset/leetcode/tree/master/tag/prefix-sum/README.md)]
  [[随机化](https://github.com/openset/leetcode/tree/master/tag/randomized/README.md)]

### 相似题目
  1. [按权重随机选择](/problems/random-pick-with-weight) (Medium)
  1. [在圆内随机生成点](/problems/generate-random-point-in-a-circle) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/random-point-in-non-overlapping-rectangles)
