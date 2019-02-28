---
layout:     single
title:      "315. 计算右侧小于当前元素的个数 (Hard)"
date:       2016-11-11 21:30:00 +0800
categories: [leetcode]
tags:       [binary-indexed-tree, segment-tree, binary-search-tree, divide-and-conquer]
permalink:  /count-of-smaller-numbers-after-self/
---

<p>给定一个整数数组 <em>nums</em>，按要求返回一个新数组&nbsp;<em>counts</em>。数组 <em>counts</em> 有该性质： <code>counts[i]</code> 的值是&nbsp; <code>nums[i]</code> 右侧小于&nbsp;<code>nums[i]</code> 的元素的数量。</p>

<p><strong>示例:</strong></p>

<pre><strong>输入:</strong> [5,2,6,1]
<strong>输出:</strong> <code>[2,1,1,0] 
<strong>解释:</strong></code>
5 的右侧有 <strong>2 </strong>个更小的元素 (2 和 1).
2 的右侧仅有 <strong>1 </strong>个更小的元素 (1).
6 的右侧有 <strong>1 </strong>个更小的元素 (1).
1 的右侧有 <strong>0 </strong>个更小的元素.
</pre>

### 相关话题
  [[树状数组](https://github.com/openset/leetcode/tree/master/tag/binary-indexed-tree/README.md)]
  [[线段树](https://github.com/openset/leetcode/tree/master/tag/segment-tree/README.md)]
  [[二叉搜索树](https://github.com/openset/leetcode/tree/master/tag/binary-search-tree/README.md)]
  [[分治算法](https://github.com/openset/leetcode/tree/master/tag/divide-and-conquer/README.md)]

### 相似题目
  1. [区间和的个数](/count-of-range-sum) (Hard)
  1. [根据身高重建队列](/queue-reconstruction-by-height) (Medium)
  1. [翻转对](/reverse-pairs) (Hard)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/count-of-smaller-numbers-after-self)
