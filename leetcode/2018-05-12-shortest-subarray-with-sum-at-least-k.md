---
layout:     single
title:      "和至少为 K 的最短子数组"
date:       2018-05-12 21:30:00 +0800
categories: [Leetcode]
tags:       [Queue, Array, Binary Search, Prefix Sum, Sliding Window, Monotonic Queue, Heap (Priority Queue)]
permalink:  /problems/shortest-subarray-with-sum-at-least-k/
---

## 862. 和至少为 K 的最短子数组 (Hard)

{% raw %}

<p>返回 <code>A</code> 的最短的非空连续子数组的<strong>长度</strong>，该子数组的和至少为 <code>K</code> 。</p>

<p>如果没有和至少为&nbsp;<code>K</code>&nbsp;的非空子数组，返回&nbsp;<code>-1</code>&nbsp;。</p>

<p>&nbsp;</p>

<ol>
</ol>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>A = [1], K = 1
<strong>输出：</strong>1
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>A = [1,2], K = 4
<strong>输出：</strong>-1
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>A = [2,-1,2], K = 3
<strong>输出：</strong>3
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= A.length &lt;= 50000</code></li>
	<li><code>-10 ^ 5&nbsp;&lt;= A[i] &lt;= 10 ^ 5</code></li>
	<li><code>1 &lt;= K &lt;= 10 ^ 9</code></li>
</ol>

{% endraw %}

### 相关话题
  [[队列](https://github.com/awesee/leetcode/tree/main/tag/queue/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[前缀和](https://github.com/awesee/leetcode/tree/main/tag/prefix-sum/README.md)]
  [[滑动窗口](https://github.com/awesee/leetcode/tree/main/tag/sliding-window/README.md)]
  [[单调队列](https://github.com/awesee/leetcode/tree/main/tag/monotonic-queue/README.md)]
  [[堆（优先队列）](https://github.com/awesee/leetcode/tree/main/tag/heap-priority-queue/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/shortest-subarray-with-sum-at-least-k)
