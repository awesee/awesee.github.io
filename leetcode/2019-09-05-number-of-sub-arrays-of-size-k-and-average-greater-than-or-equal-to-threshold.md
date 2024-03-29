---
layout:     single
title:      "大小为 K 且平均值大于等于阈值的子数组数目"
date:       2019-09-05 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Sliding Window]
permalink:  /problems/number-of-sub-arrays-of-size-k-and-average-greater-than-or-equal-to-threshold/
---

## 1343. 大小为 K 且平均值大于等于阈值的子数组数目 (Medium)

{% raw %}

<p>给你一个整数数组&nbsp;<code>arr</code>&nbsp;和两个整数 <code>k</code>&nbsp;和 <code>threshold</code>&nbsp;。</p>

<p>请你返回长度为 <code>k</code>&nbsp;且平均值大于等于&nbsp;<code>threshold</code>&nbsp;的子数组数目。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>arr = [2,2,2,2,5,5,5,8], k = 3, threshold = 4
<strong>输出：</strong>3
<strong>解释：</strong>子数组 [2,5,5],[5,5,5] 和 [5,5,8] 的平均值分别为 4，5 和 6 。其他长度为 3 的子数组的平均值都小于 4 （threshold 的值)。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>arr = [1,1,1,1,1], k = 1, threshold = 0
<strong>输出：</strong>5
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>arr = [11,13,17,23,29,31,7,5,2,3], k = 3, threshold = 5
<strong>输出：</strong>6
<strong>解释：</strong>前 6 个长度为 3 的子数组平均值都大于 5 。注意平均值不是整数。
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>arr = [7,7,7,7,7,7,7], k = 7, threshold = 7
<strong>输出：</strong>1
</pre>

<p><strong>示例 5：</strong></p>

<pre><strong>输入：</strong>arr = [4,4,4,4], k = 4, threshold = 1
<strong>输出：</strong>1
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= arr.length &lt;= 10^5</code></li>
	<li><code>1 &lt;= arr[i] &lt;= 10^4</code></li>
	<li><code>1 &lt;= k &lt;= arr.length</code></li>
	<li><code>0 &lt;= threshold &lt;= 10^4</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[滑动窗口](https://github.com/awesee/leetcode/tree/main/tag/sliding-window/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/number-of-sub-arrays-of-size-k-and-average-greater-than-or-equal-to-threshold)
