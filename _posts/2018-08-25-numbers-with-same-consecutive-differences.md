---
layout:     single
title:      "967. 连续差相同的数字 (Medium)"
date:       2018-08-25 21:30:00 +0800
categories: [leetcode]
tags:       [dynamic-programming]
permalink:  /numbers-with-same-consecutive-differences/
---

<p>返回所有长度为 <code>N</code> 且满足其每两个连续位上的数字之间的差的绝对值为 <code>K</code>&nbsp;的<strong>非负整数</strong>。</p>

<p>请注意，<strong>除了</strong>数字 <code>0</code> 本身之外，答案中的每个数字都<strong>不能</strong>有前导零。例如，<code>01</code>&nbsp;因为有一个前导零，所以是无效的；但 <code>0</code>&nbsp;是有效的。</p>

<p>你可以按任何顺序返回答案。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>N = 3, K = 7
<strong>输出：</strong>[181,292,707,818,929]
<strong>解释：</strong>注意，070 不是一个有效的数字，因为它有前导零。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>N = 2, K = 1
<strong>输出：</strong>[10,12,21,23,32,34,43,45,54,56,65,67,76,78,87,89,98]</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= N &lt;= 9</code></li>
	<li><code>0 &lt;= K &lt;= 9</code></li>
</ol>

### 相关话题
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/numbers-with-same-consecutive-differences)
