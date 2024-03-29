---
layout:     single
title:      "数组中两个数的最大异或值"
date:       2017-02-25 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Trie, Array, Hash Table]
permalink:  /problems/maximum-xor-of-two-numbers-in-an-array/
---

## 421. 数组中两个数的最大异或值 (Medium)

{% raw %}

<p>给你一个整数数组 <code>nums</code> ，返回<em> </em><code>nums[i] XOR nums[j]</code> 的最大运算结果，其中 <code>0 ≤ i ≤ j < n</code> 。</p>

<p><strong>进阶：</strong>你可以在 <code>O(n)</code> 的时间解决这个问题吗？</p>

<p> </p>

<div class="original__bRMd">
<div>
<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [3,10,5,25,2,8]
<strong>输出：</strong>28
<strong>解释：</strong>最大运算结果是 5 XOR 25 = 28.</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [0]
<strong>输出：</strong>0
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>nums = [2,4]
<strong>输出：</strong>6
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>nums = [8,10,2]
<strong>输出：</strong>10
</pre>

<p><strong>示例 5：</strong></p>

<pre>
<strong>输入：</strong>nums = [14,70,53,83,49,91,36,80,92,51,66,70]
<strong>输出：</strong>127
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 2 * 10<sup>4</sup></code></li>
	<li><code>0 <= nums[i] <= 2<sup>31</sup> - 1</code></li>
</ul>
</div>
</div>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[字典树](https://github.com/awesee/leetcode/tree/main/tag/trie/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/maximum-xor-of-two-numbers-in-an-array)
