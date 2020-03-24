---
layout:     single
title:      "扁平化嵌套列表迭代器"
date:       2016-12-07 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Design]
permalink:  /problems/flatten-nested-list-iterator/
---

## 341. 扁平化嵌套列表迭代器 (Medium)

{% raw %}

<p>给你一个嵌套的整型列表。请你设计一个迭代器，使其能够遍历这个整型列表中的所有整数。</p>

<p>列表中的每一项或者为一个整数，或者是另一个列表。其中列表的元素也可能是整数或是其他列表。</p>

<p>&nbsp;</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入: </strong>[[1,1],2,[1,1]]
<strong>输出: </strong>[1,1,2,1,1]
<strong>解释: </strong>通过重复调用&nbsp;<em>next </em>直到&nbsp;<em>hasNex</em>t 返回 false，<em>next&nbsp;</em>返回的元素的顺序应该是: <code>[1,1,2,1,1]</code>。</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入: </strong>[1,[4,[6]]]
<strong>输出: </strong>[1,4,6]
<strong>解释: </strong>通过重复调用&nbsp;<em>next&nbsp;</em>直到&nbsp;<em>hasNex</em>t 返回 false，<em>next&nbsp;</em>返回的元素的顺序应该是: <code>[1,4,6]</code>。
</pre>

{% endraw %}

### 相关话题
  [[栈](https://github.com/openset/leetcode/tree/master/tag/stack/README.md)]
  [[设计](https://github.com/openset/leetcode/tree/master/tag/design/README.md)]

### 相似题目
  1. [展开二维向量](/problems/flatten-2d-vector) (Medium)
  1. [锯齿迭代器](/problems/zigzag-iterator) (Medium)
  1. [迷你语法分析器](/problems/mini-parser) (Medium)
  1. [数组嵌套](/problems/array-nesting) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/flatten-nested-list-iterator)
