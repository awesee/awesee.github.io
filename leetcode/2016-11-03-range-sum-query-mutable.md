---
layout:     single
title:      "区域和检索 - 数组可修改"
date:       2016-11-03 21:30:00 +0800
categories: [Leetcode]
tags:       [Binary Indexed Tree, Segment Tree]
permalink:  /problems/range-sum-query-mutable/
---

## 307. 区域和检索 - 数组可修改 (Medium)

{% raw %}

<p>给定一个整数数组 &nbsp;<em>nums</em>，求出数组从索引&nbsp;<em>i&nbsp;</em>到&nbsp;<em>j&nbsp;&nbsp;</em>(<em>i</em>&nbsp;&le;&nbsp;<em>j</em>) 范围内元素的总和，包含&nbsp;<em>i,&nbsp; j&nbsp;</em>两点。</p>

<p><em>update(i, val)</em> 函数可以通过将下标为&nbsp;<em>i&nbsp;</em>的数值更新为&nbsp;<em>val</em>，从而对数列进行修改。</p>

<p><strong>示例:</strong></p>

<pre>Given nums = [1, 3, 5]

sumRange(0, 2) -&gt; 9
update(1, 2)
sumRange(0, 2) -&gt; 8
</pre>

<p><strong>说明:</strong></p>

<ol>
	<li>数组仅可以在&nbsp;<em>update&nbsp;</em>函数下进行修改。</li>
	<li>你可以假设 <em>update</em> 函数与 <em>sumRange</em> 函数的调用次数是均匀分布的。</li>
</ol>

{% endraw %}

### 相关话题
  [[树状数组](https://github.com/openset/leetcode/tree/master/tag/binary-indexed-tree/README.md)]
  [[线段树](https://github.com/openset/leetcode/tree/master/tag/segment-tree/README.md)]

### 相似题目
  1. [区域和检索 - 数组不可变](/problems/range-sum-query-immutable) (Easy)
  1. [二维区域和检索 - 可变](/problems/range-sum-query-2d-mutable) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/range-sum-query-mutable)
