---
layout:     single
title:      "形成两个异或相等数组的三元组数目"
date:       2019-12-13 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Array, Hash Table, Math, Prefix Sum]
permalink:  /problems/count-triplets-that-can-form-two-arrays-of-equal-xor/
---

## 1442. 形成两个异或相等数组的三元组数目 (Medium)

{% raw %}

<p>给你一个整数数组 <code>arr</code> 。</p>

<p>现需要从数组中取三个下标 <code>i</code>、<code>j</code> 和 <code>k</code> ，其中 <code>(0 &lt;= i &lt; j &lt;= k &lt; arr.length)</code> 。</p>

<p><code>a</code> 和 <code>b</code> 定义如下：</p>

<ul>
	<li><code>a = arr[i] ^ arr[i + 1] ^ ... ^ arr[j - 1]</code></li>
	<li><code>b = arr[j] ^ arr[j + 1] ^ ... ^ arr[k]</code></li>
</ul>

<p>注意：<strong>^</strong> 表示 <strong>按位异或</strong> 操作。</p>

<p>请返回能够令 <code>a == b</code> 成立的三元组 (<code>i</code>, <code>j</code> , <code>k</code>) 的数目。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>arr = [2,3,1,6,7]
<strong>输出：</strong>4
<strong>解释：</strong>满足题意的三元组分别是 (0,1,2), (0,2,2), (2,3,4) 以及 (2,4,4)
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>arr = [1,1,1,1,1]
<strong>输出：</strong>10
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>arr = [2,3]
<strong>输出：</strong>0
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>arr = [1,3,5,7,9]
<strong>输出：</strong>3
</pre>

<p><strong>示例 5：</strong></p>

<pre><strong>输入：</strong>arr = [7,11,12,9,5,2,7,17,22]
<strong>输出：</strong>8
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= arr.length &lt;= 300</code></li>
	<li><code>1 &lt;= arr[i] &lt;= 10^8</code></li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/openset/leetcode/tree/master/tag/bit-manipulation/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
  [[前缀和](https://github.com/openset/leetcode/tree/master/tag/prefix-sum/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/count-triplets-that-can-form-two-arrays-of-equal-xor)
