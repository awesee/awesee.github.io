---
layout:     single
title:      "绝对值表达式的最大值"
date:       2019-02-05 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Math]
permalink:  /problems/maximum-of-absolute-value-expression/
---

## 1131. 绝对值表达式的最大值 (Medium)

{% raw %}

<p>给你两个长度相等的整数数组，返回下面表达式的最大值：</p>

<p><code>|arr1[i] - arr1[j]| + |arr2[i] - arr2[j]| + |i - j|</code></p>

<p>其中下标 <code>i</code>，<code>j</code> 满足&nbsp;<code>0 &lt;= i, j &lt; arr1.length</code>。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>arr1 = [1,2,3,4], arr2 = [-1,4,5,6]
<strong>输出：</strong>13
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>arr1 = [1,-2,-5,0,10], arr2 = [0,-2,-1,-7,-4]
<strong>输出：</strong>20</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>2 &lt;= arr1.length == arr2.length &lt;= 40000</code></li>
	<li><code>-10^6 &lt;= arr1[i], arr2[i] &lt;= 10^6</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/maximum-of-absolute-value-expression)
