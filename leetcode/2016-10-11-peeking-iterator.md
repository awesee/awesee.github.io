---
layout:     single
title:      "顶端迭代器"
date:       2016-10-11 21:30:00 +0800
categories: [Leetcode]
tags:       [Design]
permalink:  /peeking-iterator/
---

## 284. 顶端迭代器 (Medium)

{% raw %}

<p>给定一个迭代器类的接口，接口包含两个方法：&nbsp;<code>next()</code>&nbsp;和&nbsp;<code>hasNext()</code>。设计并实现一个支持&nbsp;<code>peek()</code>&nbsp;操作的顶端迭代器 -- 其本质就是把原本应由&nbsp;<code>next()</code>&nbsp;方法返回的元素&nbsp;<code>peek()</code>&nbsp;出来。</p>

<p><strong>示例:</strong></p>

<pre>假设迭代器被初始化为列表&nbsp;<strong><code>[1,2,3]</code></strong>。

调用&nbsp;<strong><code>next() </code></strong>返回 <strong>1</strong>，得到列表中的第一个元素。
现在调用&nbsp;<strong><code>peek()</code></strong>&nbsp;返回 <strong>2</strong>，下一个元素。在此之后调用&nbsp;<strong><code>next() </code></strong>仍然返回 <strong>2</strong>。
最后一次调用&nbsp;<strong><code>next()</code></strong>&nbsp;返回 <strong>3</strong>，末尾元素。在此之后调用&nbsp;<strong><code>hasNext()</code></strong>&nbsp;应该返回 <strong>false</strong>。
</pre>

<p><strong>进阶：</strong>你将如何拓展你的设计？使之变得通用化，从而适应所有的类型，而不只是整数型？</p>

{% endraw %}

### 相关话题
  [[设计](https://github.com/openset/leetcode/tree/master/tag/design/README.md)]

### 相似题目
  1. [二叉搜索树迭代器](/binary-search-tree-iterator) (Medium)
  1. [展开二维向量](/flatten-2d-vector) (Medium)
  1. [锯齿迭代器](/zigzag-iterator) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/peeking-iterator)
