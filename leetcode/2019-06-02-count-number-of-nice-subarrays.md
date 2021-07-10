---
layout:     single
title:      "统计「优美子数组」"
date:       2019-06-02 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, Math, Sliding Window]
permalink:  /problems/count-number-of-nice-subarrays/
---

## 1248. 统计「优美子数组」 (Medium)

{% raw %}

<p>给你一个整数数组&nbsp;<code>nums</code> 和一个整数 <code>k</code>。</p>

<p>如果某个 <strong>连续</strong> 子数组中恰好有 <code>k</code> 个奇数数字，我们就认为这个子数组是「<strong>优美子数组</strong>」。</p>

<p>请返回这个数组中「优美子数组」的数目。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>nums = [1,1,2,1,1], k = 3
<strong>输出：</strong>2
<strong>解释：</strong>包含 3 个奇数的子数组是 [1,1,2,1] 和 [1,2,1,1] 。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>nums = [2,4,6], k = 1
<strong>输出：</strong>0
<strong>解释：</strong>数列中不包含任何奇数，所以不存在优美子数组。
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>nums = [2,2,2,1,2,2,1,2,2,2], k = 2
<strong>输出：</strong>16
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= nums.length &lt;= 50000</code></li>
	<li><code>1 &lt;= nums[i] &lt;= 10^5</code></li>
	<li><code>1 &lt;= k &lt;= nums.length</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
  [[滑动窗口](https://github.com/openset/leetcode/tree/master/tag/sliding-window/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/count-number-of-nice-subarrays)
