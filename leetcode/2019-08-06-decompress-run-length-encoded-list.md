---
layout:     single
title:      "解压缩编码列表"
date:       2019-08-06 21:30:00 +0800
categories: [Leetcode]
tags:       [Array]
permalink:  /problems/decompress-run-length-encoded-list/
---

## 1313. 解压缩编码列表 (Easy)

{% raw %}

<p>给你一个以行程长度编码压缩的整数列表&nbsp;<code>nums</code>&nbsp;。</p>

<p>考虑每相邻两个元素 <code>[a, b] = [nums[2*i], nums[2*i+1]]</code>&nbsp;（其中&nbsp;<code>i &gt;= 0</code>&nbsp;），每一对都表示解压后有 <code>a</code>&nbsp;个值为&nbsp;<code>b</code>&nbsp;的元素。</p>

<p>请你返回解压后的列表。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>nums = [1,2,3,4]
<strong>输出：</strong>[2,4,4,4]
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>2 &lt;= nums.length &lt;= 100</code></li>
	<li><code>nums.length % 2 == 0</code></li>
	<li><code>1 &lt;= nums[i] &lt;= 100</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/decompress-run-length-encoded-list)
