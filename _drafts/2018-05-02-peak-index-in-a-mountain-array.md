---
layout:     single
title:      "山脉数组的峰顶索引"
date:       2018-05-02 21:30:00 +0800
categories: [leetcode]
tags:       [binary-search]
permalink:  /peak-index-in-a-mountain-array/
---

## 852. 山脉数组的峰顶索引 (Easy)

<p>我们把符合下列属性的数组&nbsp;<code>A</code>&nbsp;称作山脉：</p>

<ul>
	<li><code>A.length &gt;= 3</code></li>
	<li>存在 <code>0 &lt; i&nbsp;&lt; A.length - 1</code> 使得<code>A[0] &lt; A[1] &lt; ... A[i-1] &lt; A[i] &gt; A[i+1] &gt; ... &gt; A[A.length - 1]</code></li>
</ul>

<p>给定一个确定为山脉的数组，返回任何满足&nbsp;<code>A[0] &lt; A[1] &lt; ... A[i-1] &lt; A[i] &gt; A[i+1] &gt; ... &gt; A[A.length - 1]</code>&nbsp;的 <code>i</code>&nbsp;的值。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>[0,1,0]
<strong>输出：</strong>1
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>[0,2,1,0]
<strong>输出：</strong>1</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>3 &lt;= A.length &lt;= 10000</code></li>
	<li>0 &lt;= A[i] &lt;= 10^6</li>
	<li>A 是如上定义的山脉</li>
</ol>

<p>&nbsp;</p>

### 相关话题
  [[二分查找](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]

### 相似题目
  1. [寻找峰值](/find-peak-element) (Medium)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/peak-index-in-a-mountain-array)