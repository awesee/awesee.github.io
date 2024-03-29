---
layout:     single
title:      "俄罗斯套娃信封问题"
date:       2016-12-20 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Binary Search, Dynamic Programming, Sorting]
permalink:  /problems/russian-doll-envelopes/
---

## 354. 俄罗斯套娃信封问题 (Hard)

{% raw %}

<p>给你一个二维整数数组 <code>envelopes</code> ，其中 <code>envelopes[i] = [w<sub>i</sub>, h<sub>i</sub>]</code> ，表示第 <code>i</code> 个信封的宽度和高度。</p>

<p>当另一个信封的宽度和高度都比这个信封大的时候，这个信封就可以放进另一个信封里，如同俄罗斯套娃一样。</p>

<p>请计算 <strong>最多能有多少个</strong> 信封能组成一组“俄罗斯套娃”信封（即可以把一个信封放到另一个信封里面）。</p>

<p><strong>注意</strong>：不允许旋转信封。</p>
 

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>envelopes = [[5,4],[6,4],[6,7],[2,3]]
<strong>输出：</strong>3
<strong>解释：</strong>最多信封的个数为 <code>3, 组合为: </code>[2,3] => [5,4] => [6,7]。</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>envelopes = [[1,1],[1,1],[1,1]]
<strong>输出：</strong>1
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= envelopes.length <= 5000</code></li>
	<li><code>envelopes[i].length == 2</code></li>
	<li><code>1 <= w<sub>i</sub>, h<sub>i</sub> <= 10<sup>4</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]

### 相似题目
  1. [最长递增子序列](/problems/longest-increasing-subsequence) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/russian-doll-envelopes)
