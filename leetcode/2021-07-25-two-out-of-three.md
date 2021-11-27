---
layout:     single
title:      "至少在两个数组中出现的值"
date:       2021-07-25 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table]
permalink:  /problems/two-out-of-three/
---

## 2032. 至少在两个数组中出现的值 (Easy)

{% raw %}

给你三个整数数组 <code>nums1</code>、<code>nums2</code> 和 <code>nums3</code> ，请你构造并返回一个 <strong>与这三个数组都不同的</strong> 数组，且由 <strong>至少</strong> 在 <strong>两个</strong> 数组中出现的所有值组成<em>。</em>数组中的元素可以按 <strong>任意</strong> 顺序排列。
<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>nums1 = [1,1,3,2], nums2 = [2,3], nums3 = [3]
<strong>输出：</strong>[3,2]
<strong>解释：</strong>至少在两个数组中出现的所有值为：
- 3 ，在全部三个数组中都出现过。
- 2 ，在数组 nums1 和 nums2 中出现过。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>nums1 = [3,1], nums2 = [2,3], nums3 = [1,2]
<strong>输出：</strong>[2,3,1]
<strong>解释：</strong>至少在两个数组中出现的所有值为：
- 2 ，在数组 nums2 和 nums3 中出现过。
- 3 ，在数组 nums1 和 nums2 中出现过。
- 1 ，在数组 nums1 和 nums3 中出现过。
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>nums1 = [1,2,2], nums2 = [4,3,3], nums3 = [5]
<strong>输出：</strong>[]
<strong>解释：</strong>不存在至少在两个数组中出现的值。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= nums1.length, nums2.length, nums3.length &lt;= 100</code></li>
	<li><code>1 &lt;= nums1[i], nums2[j], nums3[k] &lt;= 100</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/master/tag/hash-table/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/two-out-of-three)
