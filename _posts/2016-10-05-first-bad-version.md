---
layout:     single
title:      "278. 第一个错误的版本 (Easy)"
date:       2016-10-05 21:30:00 +0800
categories: [leetcode]
tags:       [binary-search]
permalink:  /first-bad-version/
---

<p>你是产品经理，目前正在带领一个团队开发新的产品。不幸的是，你的产品的最新版本没有通过质量检测。由于每个版本都是基于之前的版本开发的，所以错误的版本之后的所有版本都是错的。</p>

<p>假设你有 <code>n</code> 个版本 <code>[1, 2, ..., n]</code>，你想找出导致之后所有版本出错的第一个错误的版本。</p>

<p>你可以通过调用&nbsp;<code>bool isBadVersion(version)</code>&nbsp;接口来判断版本号 <code>version</code> 是否在单元测试中出错。实现一个函数来查找第一个错误的版本。你应该尽量减少对调用 API 的次数。</p>

<p><strong>示例:</strong></p>

<pre>给定 n = 5，并且 version = 4 是第一个错误的版本。

<code>调用 isBadVersion(3) -&gt; false
调用 isBadVersion(5)&nbsp;-&gt; true
调用 isBadVersion(4)&nbsp;-&gt; true

所以，4 是第一个错误的版本。&nbsp;</code></pre>

### 相关话题
  [[二分查找](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]

### 相似题目
  1. [在排序数组中查找元素的第一个和最后一个位置](/find-first-and-last-position-of-element-in-sorted-array) (Medium)
  1. [搜索插入位置](/search-insert-position) (Easy)
  1. [猜数字大小](/guess-number-higher-or-lower) (Easy)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/first-bad-version)
