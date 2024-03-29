---
layout:     single
title:      "带因子的二叉树"
date:       2018-04-03 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, Dynamic Programming]
permalink:  /problems/binary-trees-with-factors/
---

## 823. 带因子的二叉树 (Medium)

{% raw %}

<p>给出一个含有不重复整数元素的数组，每个整数均大于 1。</p>

<p>我们用这些整数来构建二叉树，每个整数可以使用任意次数。</p>

<p>其中：每个非叶结点的值应等于它的两个子结点的值的乘积。</p>

<p>满足条件的二叉树一共有多少个？返回的结果应<strong>模除 10 ** 9 + 7</strong>。</p>

<p>&nbsp;</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> <code>A = [2, 4]</code>
<strong>输出:</strong> 3
<strong>解释:</strong> 我们可以得到这些二叉树: <code>[2], [4], [4, 2, 2]</code></pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> <code>A = [2, 4, 5, 10]</code>
<strong>输出:</strong> <code>7</code>
<strong>解释:</strong> 我们可以得到这些二叉树: <code>[2], [4], [5], [10], [4, 2, 2], [10, 2, 5], [10, 5, 2]</code>.</pre>

<p>&nbsp;</p>

<p><strong>提示:</strong></p>

<ol>
	<li><code>1 &lt;= A.length &lt;=&nbsp;1000.</code></li>
	<li><code>2 &lt;=&nbsp;A[i]&nbsp;&lt;=&nbsp;10 ^ 9</code>.</li>
</ol>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/binary-trees-with-factors)
