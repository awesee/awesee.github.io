---
layout:     single
title:      "最小差值 II"
date:       2018-06-29 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Array, Math, Sorting]
permalink:  /problems/smallest-range-ii/
---

## 910. 最小差值 II (Medium)

{% raw %}

<p>给你一个整数数组 <code>A</code>，对于每个整数 <code>A[i]</code>，可以选择<strong> <code>x = -K</code> 或是 <code>x = K</code></strong> （<code><strong>K</strong></code> 总是非负整数），并将 <code>x</code> 加到 <code>A[i]</code> 中。</p>

<p>在此过程之后，得到数组 <code>B</code>。</p>

<p>返回 <code>B</code> 的最大值和 <code>B</code> 的最小值之间可能存在的最小差值。</p>

<p> </p>

<ol>
</ol>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>A = [1], K = 0
<strong>输出：</strong>0
<strong>解释：</strong>B = [1]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>A = [0,10], K = 2
<strong>输出：</strong>6
<strong>解释：</strong>B = [2,8]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>A = [1,3,6], K = 3
<strong>输出：</strong>3
<strong>解释：</strong>B = [4,6,3]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= A.length <= 10000</code></li>
	<li><code>0 <= A[i] <= 10000</code></li>
	<li><code>0 <= K <= 10000</code></li>
</ul>

{% endraw %}

### 相关话题
  [[贪心](https://github.com/awesee/leetcode/tree/main/tag/greedy/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/smallest-range-ii)
