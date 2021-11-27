---
layout:     single
title:      "数组中的 k-diff 数对"
date:       2017-06-16 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, Two Pointers, Binary Search, Sorting]
permalink:  /problems/k-diff-pairs-in-an-array/
---

## 532. 数组中的 k-diff 数对 (Medium)

{% raw %}

<p>给定一个整数数组和一个整数 <code><strong>k</strong></code>，你需要在数组里找到<strong> 不同的 </strong>k-diff 数对，并返回不同的 <strong>k-diff 数对</strong> 的数目。</p>

<p>这里将 <strong>k-diff</strong> 数对定义为一个整数对 <code>(nums[i], nums[j])</code>，并满足下述全部条件：</p>

<ul>
	<li><code>0 <= i < j < nums.length</code></li>
	<li><code>|nums[i] - nums[j]| == k</code></li>
</ul>

<p><strong>注意</strong>，<code>|val|</code> 表示 <code>val</code> 的绝对值。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [3, 1, 4, 1, 5], k = 2
<strong>输出：</strong>2
<strong>解释：</strong>数组中有两个 2-diff 数对, (1, 3) 和 (3, 5)。
尽管数组中有两个1，但我们只应返回不同的数对的数量。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [1, 2, 3, 4, 5], k = 1
<strong>输出：</strong>4
<strong>解释：</strong>数组中有四个 1-diff 数对, (1, 2), (2, 3), (3, 4) 和 (4, 5)。
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>nums = [1, 3, 1, 5, 4], k = 0
<strong>输出：</strong>1
<strong>解释：</strong>数组中只有一个 0-diff 数对，(1, 1)。
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>nums = [1,2,4,4,3,3,0,9,2,3], k = 3
<strong>输出：</strong>2
</pre>

<p><strong>示例 5：</strong></p>

<pre>
<strong>输入：</strong>nums = [-1,-2,-3], k = 1
<strong>输出：</strong>2
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 10<sup>4</sup></code></li>
	<li><code>-10<sup>7</sup> <= nums[i] <= 10<sup>7</sup></code></li>
	<li><code>0 <= k <= 10<sup>7</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]

### 相似题目
  1. [二叉搜索树的最小绝对差](/problems/minimum-absolute-difference-in-bst) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/k-diff-pairs-in-an-array)
