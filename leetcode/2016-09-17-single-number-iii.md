---
layout:     single
title:      "只出现一次的数字 III"
date:       2016-09-17 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Array]
permalink:  /problems/single-number-iii/
---

## 260. 只出现一次的数字 III (Medium)

{% raw %}

<p>给定一个整数数组 <code>nums</code>，其中恰好有两个元素只出现一次，其余所有元素均出现两次。 找出只出现一次的那两个元素。你可以按 <strong>任意顺序</strong> 返回答案。</p>

<p> </p>

<p><strong>进阶：</strong>你的算法应该具有线性时间复杂度。你能否仅使用常数空间复杂度来实现？</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums = [1,2,1,3,2,5]
<strong>输出：</strong>[3,5]
<strong>解释：</strong>[5, 3] 也是有效的答案。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums = [-1,0]
<strong>输出：</strong>[-1,0]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>nums = [0,1]
<strong>输出：</strong>[1,0]
</pre>

<p><strong>提示：</strong></p>

<ul>
	<li><code>2 <= nums.length <= 3 * 10<sup>4</sup></code></li>
	<li><code>-2<sup>31</sup> <= nums[i] <= 2<sup>31</sup> - 1</code></li>
	<li>除两个只出现一次的整数外，<code>nums</code> 中的其他数字都出现两次</li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]

### 相似题目
  1. [只出现一次的数字](/problems/single-number) (Easy)
  1. [只出现一次的数字 II](/problems/single-number-ii) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/single-number-iii)
