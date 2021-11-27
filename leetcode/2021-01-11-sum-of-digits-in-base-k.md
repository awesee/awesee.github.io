---
layout:     single
title:      "K 进制表示下的各位数字总和"
date:       2021-01-11 21:30:00 +0800
categories: [Leetcode]
tags:       [Math]
permalink:  /problems/sum-of-digits-in-base-k/
---

## 1837. K 进制表示下的各位数字总和 (Easy)

{% raw %}

<p>给你一个整数 <code>n</code>（<code>10</code> 进制）和一个基数 <code>k</code> ，请你将 <code>n</code> 从 <code>10</code> 进制表示转换为 <code>k</code> 进制表示，计算并返回转换后各位数字的 <strong>总和</strong> 。</p>

<p>转换后，各位数字应当视作是 <code>10</code> 进制数字，且它们的总和也应当按 <code>10</code> 进制表示返回。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>n = 34, k = 6
<strong>输出：</strong>9
<strong>解释：</strong>34 (10 进制) 在 6 进制下表示为 54 。5 + 4 = 9 。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>n = 10, k = 10
<strong>输出：</strong>1
<strong>解释：</strong>n 本身就是 10 进制。 1 + 0 = 1 。
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= n <= 100</code></li>
	<li><code>2 <= k <= 10</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数学](https://github.com/awesee/leetcode/tree/master/tag/math/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/sum-of-digits-in-base-k)
