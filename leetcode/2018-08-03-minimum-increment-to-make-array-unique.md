---
layout:     single
title:      "使数组唯一的最小增量"
date:       2018-08-03 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Array, Counting, Sorting]
permalink:  /problems/minimum-increment-to-make-array-unique/
---

## 945. 使数组唯一的最小增量 (Medium)

{% raw %}

<p>给定整数数组 A，每次 <em>move</em> 操作将会选择任意&nbsp;<code>A[i]</code>，并将其递增&nbsp;<code>1</code>。</p>

<p>返回使 <code>A</code>&nbsp;中的每个值都是唯一的最少操作次数。</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入：</strong>[1,2,2]
<strong>输出：</strong>1
<strong>解释：</strong>经过一次 <em>move</em> 操作，数组将变为 [1, 2, 3]。</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入：</strong>[3,2,1,2,1,7]
<strong>输出：</strong>6
<strong>解释：</strong>经过 6 次 <em>move</em> 操作，数组将变为 [3, 4, 1, 2, 5, 7]。
可以看出 5 次或 5 次以下的 <em>move</em> 操作是不能让数组的每个值唯一的。
</pre>

<p><strong>提示：</strong></p>

<ol>
	<li><code>0 &lt;= A.length &lt;= 40000</code></li>
	<li><code>0 &lt;= A[i] &lt; 40000</code></li>
</ol>

{% endraw %}

### 相关话题
  [[贪心](https://github.com/awesee/leetcode/tree/main/tag/greedy/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[计数](https://github.com/awesee/leetcode/tree/main/tag/counting/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/minimum-increment-to-make-array-unique)
