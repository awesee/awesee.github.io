---
layout:     single
title:      "找两个和为目标值且不重叠的子数组"
date:       2020-01-17 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, Binary Search, Dynamic Programming, Sliding Window]
permalink:  /problems/find-two-non-overlapping-sub-arrays-each-with-target-sum/
---

## 1477. 找两个和为目标值且不重叠的子数组 (Medium)

{% raw %}

<p>给你一个整数数组&nbsp;<code>arr</code> 和一个整数值&nbsp;<code>target</code>&nbsp;。</p>

<p>请你在 <code>arr</code>&nbsp;中找 <strong>两个互不重叠的子数组</strong>&nbsp;且它们的和都等于&nbsp;<code>target</code>&nbsp;。可能会有多种方案，请你返回满足要求的两个子数组长度和的 <strong>最小值</strong> 。</p>

<p>请返回满足要求的最小长度和，如果无法找到这样的两个子数组，请返回 <strong>-1</strong>&nbsp;。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>arr = [3,2,2,4,3], target = 3
<strong>输出：</strong>2
<strong>解释：</strong>只有两个子数组和为 3 （[3] 和 [3]）。它们的长度和为 2 。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>arr = [7,3,4,7], target = 7
<strong>输出：</strong>2
<strong>解释：</strong>尽管我们有 3 个互不重叠的子数组和为 7 （[7], [3,4] 和 [7]），但我们会选择第一个和第三个子数组，因为它们的长度和 2 是最小值。
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>arr = [4,3,2,6,2,3,4], target = 6
<strong>输出：</strong>-1
<strong>解释：</strong>我们只有一个和为 6 的子数组。
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>arr = [5,5,4,4,5], target = 3
<strong>输出：</strong>-1
<strong>解释：</strong>我们无法找到和为 3 的子数组。
</pre>

<p><strong>示例 5：</strong></p>

<pre><strong>输入：</strong>arr = [3,1,1,1,5,1,2,1], target = 3
<strong>输出：</strong>3
<strong>解释：</strong>注意子数组 [1,2] 和 [2,1] 不能成为一个方案因为它们重叠了。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= arr.length &lt;= 10^5</code></li>
	<li><code>1 &lt;= arr[i] &lt;= 1000</code></li>
	<li><code>1 &lt;= target &lt;= 10^8</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[滑动窗口](https://github.com/awesee/leetcode/tree/main/tag/sliding-window/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/find-two-non-overlapping-sub-arrays-each-with-target-sum)
