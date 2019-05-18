---
layout:     single
title:      "将数据流变为多个不相交区间"
date:       2016-12-18 21:30:00 +0800
categories: [Leetcode]
tags:       [Binary Search, Ordered Map]
permalink:  /data-stream-as-disjoint-intervals/
---

## 352. 将数据流变为多个不相交区间 (Hard)

<p>给定一个非负整数的数据流输入 a<sub>1</sub>，a<sub>2</sub>，&hellip;，a<sub>n，</sub>&hellip;，将到目前为止看到的数字总结为不相交的区间列表。</p>

<p>例如，假设数据流中的整数为 1，3，7，2，6，&hellip;，每次的总结为：</p>

<pre>[1, 1]
[1, 1], [3, 3]
[1, 1], [3, 3], [7, 7]
[1, 3], [7, 7]
[1, 3], [6, 7]
</pre>

<p>&nbsp;</p>

<p><strong>进阶：</strong><br>
如果有很多合并，并且与数据流的大小相比，不相交区间的数量很小，该怎么办?</p>

<p><strong>提示：</strong><br>
特别感谢 <a href="https://discuss.leetcode.com/user/yunhong">@yunhong</a> 提供了本问题和其测试用例。</p>

### 相关话题
  [[二分查找](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]
  [[Ordered Map](https://github.com/openset/leetcode/tree/master/tag/ordered-map/README.md)]

### 相似题目
  1. [汇总区间](/summary-ranges) (Medium)
  1. [寻找右区间](/find-right-interval) (Medium)
  1. [Range 模块](/range-module) (Hard)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/data-stream-as-disjoint-intervals)
