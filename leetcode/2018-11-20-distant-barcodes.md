---
layout:     single
title:      "距离相等的条形码"
date:       2018-11-20 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Array, Hash Table, Counting, Sorting, Heap (Priority Queue)]
permalink:  /problems/distant-barcodes/
---

## 1054. 距离相等的条形码 (Medium)

{% raw %}

<p>在一个仓库里，有一排条形码，其中第 <code>i</code> 个条形码为&nbsp;<code>barcodes[i]</code>。</p>

<p>请你重新排列这些条形码，使其中两个相邻的条形码 <strong>不能</strong> 相等。 你可以返回任何满足该要求的答案，此题保证存在答案。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>[1,1,1,2,2,2]
<strong>输出：</strong>[2,1,2,1,2,1]
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>[1,1,1,1,2,2,3,3]
<strong>输出：</strong>[1,3,1,3,2,1,2,1]</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= barcodes.length &lt;= 10000</code></li>
	<li><code>1 &lt;= barcodes[i] &lt;= 10000</code></li>
</ol>

<p>&nbsp;</p>

{% endraw %}

### 相关话题
  [[贪心](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[计数](https://github.com/openset/leetcode/tree/master/tag/counting/README.md)]
  [[排序](https://github.com/openset/leetcode/tree/master/tag/sorting/README.md)]
  [[堆（优先队列）](https://github.com/openset/leetcode/tree/master/tag/heap-priority-queue/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/distant-barcodes)
