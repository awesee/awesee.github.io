---
layout:     single
title:      "整数替换"
date:       2017-02-01 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Memoization, Dynamic Programming]
permalink:  /problems/integer-replacement/
---

## 397. 整数替换 (Medium)

{% raw %}

<p>给定一个正整数 <code>n</code> ，你可以做如下操作：</p>

<ol>
	<li>如果 <code>n</code><em> </em>是偶数，则用 <code>n / 2</code>替换 <code>n</code><em> </em>。</li>
	<li>如果 <code>n</code><em> </em>是奇数，则可以用 <code>n + 1</code>或<code>n - 1</code>替换 <code>n</code> 。</li>
</ol>

<p><code>n</code><em> </em>变为 <code>1</code> 所需的最小替换次数是多少？</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>n = 8
<strong>输出：</strong>3
<strong>解释：</strong>8 -> 4 -> 2 -> 1
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>n = 7
<strong>输出：</strong>4
<strong>解释：</strong>7 -> 8 -> 4 -> 2 -> 1
或 7 -> 6 -> 3 -> 2 -> 1
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>n = 4
<strong>输出：</strong>2
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= n <= 2<sup>31</sup> - 1</code></li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[记忆化搜索](https://github.com/awesee/leetcode/tree/main/tag/memoization/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/integer-replacement)
