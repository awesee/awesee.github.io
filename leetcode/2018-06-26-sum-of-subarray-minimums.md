---
layout:     single
title:      "子数组的最小值之和"
date:       2018-06-26 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Array, Dynamic Programming, Monotonic Stack]
permalink:  /problems/sum-of-subarray-minimums/
---

## 907. 子数组的最小值之和 (Medium)

{% raw %}

<p>给定一个整数数组 <code>arr</code>，找到 <code>min(b)</code> 的总和，其中 <code>b</code> 的范围为 <code>arr</code> 的每个（连续）子数组。</p>

<p>由于答案可能很大，因此<strong> 返回答案模 <code>10^9 + 7</code></strong> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>arr = [3,1,2,4]
<strong>输出：</strong>17
<strong>解释：
</strong>子数组为<strong> </strong>[3]，[1]，[2]，[4]，[3,1]，[1,2]，[2,4]，[3,1,2]，[1,2,4]，[3,1,2,4]。 
最小值为 3，1，2，4，1，1，2，1，1，1，和为 17。</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>arr = [11,81,94,43,3]
<strong>输出：</strong>444
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= arr.length <= 3 * 10<sup>4</sup></code></li>
	<li><code>1 <= arr[i] <= 3 * 10<sup>4</sup></code></li>
</ul>

<p> </p>

{% endraw %}

### 相关话题
  [[栈](https://github.com/openset/leetcode/tree/master/tag/stack/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]
  [[单调栈](https://github.com/openset/leetcode/tree/master/tag/monotonic-stack/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/sum-of-subarray-minimums)
