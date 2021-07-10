---
layout:     single
title:      "不同整数的最少数目"
date:       2020-01-21 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Array, Hash Table, Counting, Sorting]
permalink:  /problems/least-number-of-unique-integers-after-k-removals/
---

## 1481. 不同整数的最少数目 (Medium)

{% raw %}

<p>给你一个整数数组 <code>arr</code> 和一个整数 <code>k</code> 。现需要从数组中恰好移除 <code>k</code> 个元素，请找出移除后数组中不同整数的最少数目。</p>

<ol>
</ol>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>arr = [5,5,4], k = 1
<strong>输出：</strong>1
<strong>解释：</strong>移除 1 个 4 ，数组中只剩下 5 一种整数。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>arr = [4,3,1,1,3,3,2], k = 3
<strong>输出：</strong>2
<strong>解释：</strong>先移除 4、2 ，然后再移除两个 1 中的任意 1 个或者三个 3 中的任意 1 个，最后剩下 1 和 3 两种整数。</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= arr.length&nbsp;&lt;= 10^5</code></li>
	<li><code>1 &lt;= arr[i] &lt;= 10^9</code></li>
	<li><code>0 &lt;= k&nbsp;&lt;= arr.length</code></li>
</ul>

{% endraw %}

### 相关话题
  [[贪心](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[计数](https://github.com/openset/leetcode/tree/master/tag/counting/README.md)]
  [[排序](https://github.com/openset/leetcode/tree/master/tag/sorting/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/least-number-of-unique-integers-after-k-removals)
