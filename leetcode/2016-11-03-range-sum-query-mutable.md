---
layout:     single
title:      "区域和检索 - 数组可修改"
date:       2016-11-03 21:30:00 +0800
categories: [Leetcode]
tags:       [Design, Binary Indexed Tree, Segment Tree, Array]
permalink:  /problems/range-sum-query-mutable/
---

## 307. 区域和检索 - 数组可修改 (Medium)

{% raw %}

<p>给你一个数组 <code>nums</code> ，请你完成两类查询，其中一类查询要求更新数组下标对应的值，另一类查询要求返回数组中某个范围内元素的总和。</p>

<p>实现 <code>NumArray</code> 类：</p>

<div class="original__bRMd">
<div>
<ul>
	<li><code>NumArray(int[] nums)</code> 用整数数组 <code>nums</code> 初始化对象</li>
	<li><code>void update(int index, int val)</code> 将 <code>nums[index]</code> 的值更新为 <code>val</code></li>
	<li><code>int sumRange(int left, int right)</code> 返回子数组 <code>nums[left, right]</code> 的总和（即，<code>nums[left] + nums[left + 1], ..., nums[right]</code>）</li>
</ul>

<p> </p>

<p><strong>示例：</strong></p>

<pre>
<strong>输入</strong>：
["NumArray", "sumRange", "update", "sumRange"]
[[[1, 3, 5]], [0, 2], [1, 2], [0, 2]]
<strong>输出</strong>：
[null, 9, null, 8]

<strong>解释</strong>：
NumArray numArray = new NumArray([1, 3, 5]);
numArray.sumRange(0, 2); // 返回 9 ，sum([1,3,5]) = 9
numArray.update(1, 2);   // nums = [1,2,5]
numArray.sumRange(0, 2); // 返回 8 ，sum([1,2,5]) = 8
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= nums.length <= 3 * 10<sup>4</sup></code></li>
	<li><code>-100 <= nums[i] <= 100</code></li>
	<li><code>0 <= index < nums.length</code></li>
	<li><code>-100 <= val <= 100</code></li>
	<li><code>0 <= left <= right < nums.length</code></li>
	<li>最多调用 <code>3 * 10<sup>4</sup></code> 次 <code>update</code> 和 <code>sumRange</code> 方法</li>
</ul>
</div>
</div>

{% endraw %}

### 相关话题
  [[设计](https://github.com/awesee/leetcode/tree/main/tag/design/README.md)]
  [[树状数组](https://github.com/awesee/leetcode/tree/main/tag/binary-indexed-tree/README.md)]
  [[线段树](https://github.com/awesee/leetcode/tree/main/tag/segment-tree/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]

### 相似题目
  1. [区域和检索 - 数组不可变](/problems/range-sum-query-immutable) (Easy)
  1. [二维区域和检索 - 可变](/problems/range-sum-query-2d-mutable) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/range-sum-query-mutable)
