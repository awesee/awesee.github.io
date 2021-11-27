---
layout:     single
title:      "分数到小数"
date:       2016-06-15 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, Math, String]
permalink:  /problems/fraction-to-recurring-decimal/
---

## 166. 分数到小数 (Medium)

{% raw %}

<p>给定两个整数，分别表示分数的分子 <code>numerator</code> 和分母 <code>denominator</code>，以 <strong>字符串形式返回小数</strong> 。</p>

<p>如果小数部分为循环小数，则将循环的部分括在括号内。</p>

<p class="MachineTrans-lang-zh-CN">如果存在多个答案，只需返回 <strong>任意一个</strong> 。</p>

<p class="MachineTrans-lang-zh-CN">对于所有给定的输入，<strong>保证</strong> 答案字符串的长度小于 <code>10<sup>4</sup></code> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>numerator = 1, denominator = 2
<strong>输出：</strong>"0.5"
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>numerator = 2, denominator = 1
<strong>输出：</strong>"2"
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>numerator = 2, denominator = 3
<strong>输出：</strong>"0.(6)"
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>numerator = 4, denominator = 333
<strong>输出：</strong>"0.(012)"
</pre>

<p><strong>示例 5：</strong></p>

<pre>
<strong>输入：</strong>numerator = 1, denominator = 5
<strong>输出：</strong>"0.2"
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>-2<sup>31</sup> <= numerator, denominator <= 2<sup>31</sup> - 1</code></li>
	<li><code>denominator != 0</code></li>
</ul>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/fraction-to-recurring-decimal)
