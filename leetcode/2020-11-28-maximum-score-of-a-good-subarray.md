---
layout:     single
title:      "好子数组的最大分数"
date:       2020-11-28 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Array, Two Pointers, Binary Search, Monotonic Stack]
permalink:  /problems/maximum-score-of-a-good-subarray/
---

## 1793. 好子数组的最大分数 (Hard)

{% raw %}

<p>给你一个整数数组 <code>nums</code> <strong>（下标从 0 开始）</strong>和一个整数 <code>k</code> 。</p>

<p>一个子数组 <code>(i, j)</code> 的 <strong>分数</strong> 定义为 <code>min(nums[i], nums[i+1], ..., nums[j]) * (j - i + 1)</code> 。一个 <strong>好</strong> 子数组的两个端点下标需要满足 <code>i &lt;= k &lt;= j</code> 。</p>

<p>请你返回 <strong>好</strong> 子数组的最大可能 <strong>分数</strong> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre><b>输入：</b>nums = [1,4,3,7,4,5], k = 3
<b>输出：</b>15
<b>解释：</b>最优子数组的左右端点下标是 (1, 5) ，分数为 min(4,3,7,4,5) * (5-1+1) = 3 * 5 = 15 。
</pre>

<p><strong>示例 2：</strong></p>

<pre><b>输入：</b>nums = [5,5,4,5,4,1,1,1], k = 0
<b>输出：</b>20
<b>解释：</b>最优子数组的左右端点下标是 (0, 4) ，分数为 min(5,5,4,5,4) * (4-0+1) = 4 * 5 = 20 。
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= nums.length &lt;= 10<sup>5</sup></code></li>
	<li><code>1 &lt;= nums[i] &lt;= 2 * 10<sup>4</sup></code></li>
	<li><code>0 &lt;= k &lt; nums.length</code></li>
</ul>

{% endraw %}

### 相关话题
  [[栈](https://github.com/awesee/leetcode/tree/main/tag/stack/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[单调栈](https://github.com/awesee/leetcode/tree/main/tag/monotonic-stack/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/maximum-score-of-a-good-subarray)
