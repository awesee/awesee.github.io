---
layout:     single
title:      "最短无序连续子数组"
date:       2017-08-04 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Greedy, Array, Two Pointers, Sorting, Monotonic Stack]
permalink:  /problems/shortest-unsorted-continuous-subarray/
---

## 581. 最短无序连续子数组 (Medium)

{% raw %}

<p>给你一个整数数组 <code>nums</code> ，你需要找出一个 <strong>连续子数组</strong> ，如果对这个子数组进行升序排序，那么整个数组都会变为升序排序。</p>

<p>请你找出符合题意的 <strong>最短</strong> 子数组，并输出它的长度。</p>

<p> </p>

<div class="original__bRMd">
<div>
<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [2,6,4,8,10,9,15]
<strong>输出：</strong>5
<strong>解释：</strong>你只需要对 [6, 4, 8, 10, 9] 进行升序排序，那么整个表都会变为升序排序。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [1,2,3,4]
<strong>输出：</strong>0
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>nums = [1]
<strong>输出：</strong>0
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 10<sup>4</sup></code></li>
	<li><code>-10<sup>5</sup> <= nums[i] <= 10<sup>5</sup></code></li>
</ul>

<p> </p>

<p><strong>进阶：</strong>你可以设计一个时间复杂度为 <code>O(n)</code> 的解决方案吗？</p>
</div>
</div>

{% endraw %}

### 相关话题
  [[栈](https://github.com/awesee/leetcode/tree/main/tag/stack/README.md)]
  [[贪心](https://github.com/awesee/leetcode/tree/main/tag/greedy/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]
  [[单调栈](https://github.com/awesee/leetcode/tree/main/tag/monotonic-stack/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/shortest-unsorted-continuous-subarray)
