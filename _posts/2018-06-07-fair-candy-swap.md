---
layout:     single
title:      "公平的糖果棒交换"
date:       2018-06-07 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, Binary Search, Sorting]
permalink:  /problems/fair-candy-swap/
---

## 888. 公平的糖果棒交换 (Easy)

{% raw %}

<p>爱丽丝和鲍勃有不同大小的糖果棒：<code>A[i]</code> 是爱丽丝拥有的第 <code>i</code> 根糖果棒的大小，<code>B[j]</code> 是鲍勃拥有的第 <code>j</code> 根糖果棒的大小。</p>

<p>因为他们是朋友，所以他们想交换一根糖果棒，这样交换后，他们都有相同的糖果总量。<em>（一个人拥有的糖果总量是他们拥有的糖果棒大小的总和。）</em></p>

<p>返回一个整数数组 <code>ans</code>，其中 <code>ans[0]</code> 是爱丽丝必须交换的糖果棒的大小，<code>ans[1]</code> 是 Bob 必须交换的糖果棒的大小。</p>

<p>如果有多个答案，你可以返回其中任何一个。保证答案存在。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>A = [1,1], B = [2,2]
<strong>输出：</strong>[1,2]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>A = [1,2], B = [2,3]
<strong>输出：</strong>[1,2]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>A = [2], B = [1,3]
<strong>输出：</strong>[2,3]
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>A = [1,2,5], B = [2,4]
<strong>输出：</strong>[5,4]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= A.length <= 10000</code></li>
	<li><code>1 <= B.length <= 10000</code></li>
	<li><code>1 <= A[i] <= 100000</code></li>
	<li><code>1 <= B[i] <= 100000</code></li>
	<li>保证爱丽丝与鲍勃的糖果总量不同。</li>
	<li>答案肯定存在。</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/fair-candy-swap)
