---
layout:     single
title:      "数据流中的第 K 大元素"
date:       2017-12-04 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Design, Binary Search Tree, Binary Tree, Data Stream, Heap (Priority Queue)]
permalink:  /problems/kth-largest-element-in-a-stream/
---

## 703. 数据流中的第 K 大元素 (Easy)

{% raw %}

<p>设计一个找到数据流中第 <code>k</code> 大元素的类（class）。注意是排序后的第 <code>k</code> 大元素，不是第 <code>k</code> 个不同的元素。</p>

<p>请实现 <code>KthLargest</code> 类：</p>

<ul>
	<li><code>KthLargest(int k, int[] nums)</code> 使用整数 <code>k</code> 和整数流 <code>nums</code> 初始化对象。</li>
	<li><code>int add(int val)</code> 将 <code>val</code> 插入数据流 <code>nums</code> 后，返回当前数据流中第 <code>k</code> 大的元素。</li>
</ul>

<p> </p>

<p><strong>示例：</strong></p>

<pre>
<strong>输入：</strong>
["KthLargest", "add", "add", "add", "add", "add"]
[[3, [4, 5, 8, 2]], [3], [5], [10], [9], [4]]
<strong>输出：</strong>
[null, 4, 5, 5, 8, 8]

<strong>解释：</strong>
KthLargest kthLargest = new KthLargest(3, [4, 5, 8, 2]);
kthLargest.add(3);   // return 4
kthLargest.add(5);   // return 5
kthLargest.add(10);  // return 5
kthLargest.add(9);   // return 8
kthLargest.add(4);   // return 8
</pre>

<p> </p>
<strong>提示：</strong>

<ul>
	<li><code>1 <= k <= 10<sup>4</sup></code></li>
	<li><code>0 <= nums.length <= 10<sup>4</sup></code></li>
	<li><code>-10<sup>4</sup> <= nums[i] <= 10<sup>4</sup></code></li>
	<li><code>-10<sup>4</sup> <= val <= 10<sup>4</sup></code></li>
	<li>最多调用 <code>add</code> 方法 <code>10<sup>4</sup></code> 次</li>
	<li>题目数据保证，在查找第 <code>k</code> 大元素时，数组中至少有 <code>k</code> 个元素</li>
</ul>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[设计](https://github.com/awesee/leetcode/tree/main/tag/design/README.md)]
  [[二叉搜索树](https://github.com/awesee/leetcode/tree/main/tag/binary-search-tree/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]
  [[数据流](https://github.com/awesee/leetcode/tree/main/tag/data-stream/README.md)]
  [[堆（优先队列）](https://github.com/awesee/leetcode/tree/main/tag/heap-priority-queue/README.md)]

### 相似题目
  1. [数组中的第K个最大元素](/problems/kth-largest-element-in-an-array) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/kth-largest-element-in-a-stream)
