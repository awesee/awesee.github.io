---
layout:     single
title:      "满足条件的子序列数目"
date:       2020-02-07 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Two Pointers, Binary Search, Sorting]
permalink:  /problems/number-of-subsequences-that-satisfy-the-given-sum-condition/
---

## 1498. 满足条件的子序列数目 (Medium)

{% raw %}

<p>给你一个整数数组 <code>nums</code> 和一个整数 <code>target</code> 。</p>

<p>请你统计并返回 <code>nums</code> 中能满足其最小元素与最大元素的 <strong>和</strong> 小于或等于 <code>target</code> 的 <strong>非空</strong> 子序列的数目。</p>

<p>由于答案可能很大，请将结果对 10^9 + 7 取余后返回。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>nums = [3,5,6,7], target = 9
<strong>输出：</strong>4
<strong>解释：</strong>有 4 个子序列满足该条件。
[3] -&gt; 最小元素 + 最大元素 &lt;= target (3 + 3 &lt;= 9)
[3,5] -&gt; (3 + 5 &lt;= 9)
[3,5,6] -&gt; (3 + 6 &lt;= 9)
[3,6] -&gt; (3 + 6 &lt;= 9)
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>nums = [3,3,6,8], target = 10
<strong>输出：</strong>6
<strong>解释：</strong>有 6 个子序列满足该条件。（nums 中可以有重复数字）
[3] , [3] , [3,3], [3,6] , [3,6] , [3,3,6]</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>nums = [2,3,3,4,6,7], target = 12
<strong>输出：</strong>61
<strong>解释：</strong>共有 63 个非空子序列，其中 2 个不满足条件（[6,7], [7]）
有效序列总数为（63 - 2 = 61）
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>nums = [5,2,4,1,7,6,8], target = 16
<strong>输出：</strong>127
<strong>解释：</strong>所有非空子序列都满足条件 (2^7 - 1) = 127</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= nums.length &lt;= 10^5</code></li>
	<li><code>1 &lt;= nums[i] &lt;= 10^6</code></li>
	<li><code>1 &lt;= target &lt;= 10^6</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/number-of-subsequences-that-satisfy-the-given-sum-condition)
