---
layout:     single
title:      "计算右侧小于当前元素的个数"
date:       2016-11-11 21:30:00 +0800
categories: [Leetcode]
tags:       [Binary Indexed Tree, Segment Tree, Array, Binary Search, Divide and Conquer, Ordered Set, Merge Sort]
permalink:  /problems/count-of-smaller-numbers-after-self/
---

## 315. 计算右侧小于当前元素的个数 (Hard)

{% raw %}

<p>给定一个整数数组 <em>nums</em>，按要求返回一个新数组&nbsp;<em>counts</em>。数组 <em>counts</em> 有该性质： <code>counts[i]</code> 的值是&nbsp; <code>nums[i]</code> 右侧小于&nbsp;<code>nums[i]</code> 的元素的数量。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>nums = [5,2,6,1]
<strong>输出：</strong><code>[2,1,1,0] 
<strong>解释：</strong></code>
5 的右侧有 <strong>2 </strong>个更小的元素 (2 和 1)
2 的右侧仅有 <strong>1 </strong>个更小的元素 (1)
6 的右侧有 <strong>1 </strong>个更小的元素 (1)
1 的右侧有 <strong>0 </strong>个更小的元素
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 &lt;= nums.length &lt;= 10^5</code></li>
	<li><code>-10^4&nbsp;&lt;= nums[i] &lt;= 10^4</code></li>
</ul>

{% endraw %}

### 相关话题
  [[树状数组](https://github.com/awesee/leetcode/tree/main/tag/binary-indexed-tree/README.md)]
  [[线段树](https://github.com/awesee/leetcode/tree/main/tag/segment-tree/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[分治](https://github.com/awesee/leetcode/tree/main/tag/divide-and-conquer/README.md)]
  [[有序集合](https://github.com/awesee/leetcode/tree/main/tag/ordered-set/README.md)]
  [[归并排序](https://github.com/awesee/leetcode/tree/main/tag/merge-sort/README.md)]

### 相似题目
  1. [区间和的个数](/problems/count-of-range-sum) (Hard)
  1. [根据身高重建队列](/problems/queue-reconstruction-by-height) (Medium)
  1. [翻转对](/problems/reverse-pairs) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/count-of-smaller-numbers-after-self)
