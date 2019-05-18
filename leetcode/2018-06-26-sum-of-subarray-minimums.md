---
layout:     single
title:      "子数组的最小值之和"
date:       2018-06-26 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Array]
permalink:  /sum-of-subarray-minimums/
---

## 907. 子数组的最小值之和 (Medium)

<p>给定一个整数数组 <code>A</code>，找到 <code>min(B)</code>&nbsp;的总和，其中 <code>B</code> 的范围为&nbsp;<code>A</code> 的每个（连续）子数组。</p>

<p>由于答案可能很大，因此<strong>返回答案模 <code>10^9 + 7</code></strong>。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>[3,1,2,4]
<strong>输出：</strong>17
<strong>解释：
子数组为 </strong>[3]，[1]，[2]，[4]，[3,1]，[1,2]，[2,4]，[3,1,2]，[1,2,4]，[3,1,2,4]。 
最小值为 3，1，2，4，1，1，2，1，1，1，和为 17。</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= A &lt;= 30000</code></li>
	<li><code>1 &lt;= A[i] &lt;= 30000</code></li>
</ol>

<p>&nbsp;</p>

### 相关话题
  [[栈](https://github.com/openset/leetcode/tree/master/tag/stack/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/sum-of-subarray-minimums)
