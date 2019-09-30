---
layout:     single
title:      "递增的三元子序列"
date:       2016-11-30 21:30:00 +0800
categories: [Leetcode]
tags:       []
permalink:  /problems/increasing-triplet-subsequence/
---

## 334. 递增的三元子序列 (Medium)

{% raw %}

<p>给定一个未排序的数组，判断这个数组中是否存在长度为 3 的递增子序列。</p>

<p>数学表达式如下:</p>

<blockquote>如果存在这样的&nbsp;<em>i, j, k,&nbsp;</em>&nbsp;且满足&nbsp;0 &le; <em>i</em> &lt; <em>j</em> &lt; <em>k</em> &le; <em>n</em>-1，<br>
使得&nbsp;<em>arr[i]</em> &lt; <em>arr[j]</em> &lt; <em>arr[k] </em>，返回 true ;&nbsp;否则返回 false 。</blockquote>

<p><strong>说明:</strong> 要求算法的时间复杂度为 O(<em>n</em>)，空间复杂度为 O(<em>1</em>) 。</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入: </strong>[1,2,3,4,5]
<strong>输出: </strong>true
</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入: </strong>[5,4,3,2,1]
<strong>输出: </strong>false</pre>

{% endraw %}

### 相似题目
  1. [最长上升子序列](/problems/longest-increasing-subsequence) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/increasing-triplet-subsequence)
