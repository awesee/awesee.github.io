---
layout:     single
title:      "交换一次的先前排列"
date:       2018-11-19 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Array]
permalink:  /problems/previous-permutation-with-one-swap/
---

## 1053. 交换一次的先前排列 (Medium)

{% raw %}

<p>给你一个正整数的数组 <code>A</code>（其中的元素不一定完全不同），请你返回可在&nbsp;<strong>一次交换</strong>（交换两数字 <code>A[i]</code> 和 <code>A[j]</code> 的位置）后得到的、按字典序排列小于 <code>A</code> 的最大可能排列。</p>

<p>如果无法这么操作，就请返回原数组。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>[3,2,1]
<strong>输出：</strong>[3,1,2]
<strong>解释：</strong>
交换 2 和 1
</pre>

<p>&nbsp;</p>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>[1,1,5]
<strong>输出：</strong>[1,1,5]
<strong>解释： </strong>
这已经是最小排列
</pre>

<p>&nbsp;</p>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>[1,9,4,6,7]
<strong>输出：</strong>[1,7,4,6,9]
<strong>解释：</strong>
交换 9 和 7
</pre>

<p>&nbsp;</p>

<p><strong>示例&nbsp;4：</strong></p>

<pre><strong>输入：</strong>[3,1,1,3]
<strong>输出：</strong>[1,3,1,3]
<strong>解释：
</strong>交换 1 和 3
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= A.length &lt;= 10000</code></li>
	<li><code>1 &lt;= A[i] &lt;= 10000</code></li>
</ol>

{% endraw %}

### 相关话题
  [[贪心算法](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/previous-permutation-with-one-swap)
