---
layout:     single
title:      "插入区间"
date:       2016-02-27 21:30:00 +0800
categories: [Leetcode]
tags:       [Sort, Array]
permalink:  /problems/insert-interval/
---

## 57. 插入区间 (Hard)

{% raw %}

<p>给出一个<em>无重叠的 ，</em>按照区间起始端点排序的区间列表。</p>

<p>在列表中插入一个新的区间，你需要确保列表中的区间仍然有序且不重叠（如果有必要的话，可以合并区间）。</p>

<p><strong>示例&nbsp;1:</strong></p>

<pre><strong>输入:</strong> intervals = [[1,3],[6,9]], newInterval = [2,5]
<strong>输出:</strong> [[1,5],[6,9]]
</pre>

<p><strong>示例&nbsp;2:</strong></p>

<pre><strong>输入:</strong> intervals = <code>[[1,2],[3,5],[6,7],[8,10],[12,16]]</code>, newInterval = <code>[4,8]</code>
<strong>输出:</strong> [[1,2],[3,10],[12,16]]
<strong>解释:</strong> 这是因为新的区间 <code>[4,8]</code> 与 <code>[3,5],[6,7],[8,10]</code>&nbsp;重叠。
</pre>

{% endraw %}

### 相关话题
  [[排序](https://github.com/openset/leetcode/tree/master/tag/sort/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]

### 相似题目
  1. [合并区间](/problems/merge-intervals) (Medium)
  1. [Range 模块](/problems/range-module) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/insert-interval)
