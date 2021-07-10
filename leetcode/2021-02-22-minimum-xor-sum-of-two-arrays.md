---
layout:     single
title:      "两个数组最小的异或值之和"
date:       2021-02-22 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Array, Dynamic Programming, Bitmask]
permalink:  /problems/minimum-xor-sum-of-two-arrays/
---

## 1879. 两个数组最小的异或值之和 (Hard)

{% raw %}

<p>给你两个整数数组 <code>nums1</code> 和 <code>nums2</code> ，它们长度都为 <code>n</code> 。</p>

<p>两个数组的 <strong>异或值之和</strong> 为 <code>(nums1[0] XOR nums2[0]) + (nums1[1] XOR nums2[1]) + ... + (nums1[n - 1] XOR nums2[n - 1])</code> （<strong>下标从 0 开始</strong>）。</p>

<ul>
	<li>比方说，<code>[1,2,3]</code> 和 <code>[3,2,1]</code> 的 <strong>异或值之和</strong> 等于 <code>(1 XOR 3) + (2 XOR 2) + (3 XOR 1) = 2 + 0 + 2 = 4</code> 。</li>
</ul>

<p>请你将 <code>nums2</code> 中的元素重新排列，使得 <strong>异或值之和</strong> <strong>最小</strong> 。</p>

<p>请你返回重新排列之后的 <strong>异或值之和</strong> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre><b>输入：</b>nums1 = [1,2], nums2 = [2,3]
<b>输出：</b>2
<b>解释：</b>将 <code>nums2</code> 重新排列得到 <code>[3,2] 。</code>
异或值之和为 (1 XOR 3) + (2 XOR 2) = 2 + 0 = 2 。</pre>

<p><strong>示例 2：</strong></p>

<pre><b>输入：</b>nums1 = [1,0,3], nums2 = [5,3,4]
<b>输出：</b>8
<b>解释：</b>将 <code>nums2 重新排列得到</code> <code>[5,4,3] 。</code>
异或值之和为 (1 XOR 5) + (0 XOR 4) + (3 XOR 3) = 4 + 4 + 0 = 8 。
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>n == nums1.length</code></li>
	<li><code>n == nums2.length</code></li>
	<li><code>1 &lt;= n &lt;= 14</code></li>
	<li><code>0 &lt;= nums1[i], nums2[i] &lt;= 10<sup>7</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/openset/leetcode/tree/master/tag/bit-manipulation/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]
  [[状态压缩](https://github.com/openset/leetcode/tree/master/tag/bitmask/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/minimum-xor-sum-of-two-arrays)
