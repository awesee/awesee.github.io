---
layout:     single
title:      "用 Rand7() 实现 Rand10()"
date:       2017-04-15 21:30:00 +0800
categories: [Leetcode]
tags:       [Math, Rejection Sampling, Probability and Statistics, Randomized]
permalink:  /problems/implement-rand10-using-rand7/
---

## 470. 用 Rand7() 实现 Rand10() (Medium)

{% raw %}

<p>已有方法&nbsp;<code>rand7</code>&nbsp;可生成 1 到 7 范围内的均匀随机整数，试写一个方法&nbsp;<code>rand10</code>&nbsp;生成 1 到 10 范围内的均匀随机整数。</p>

<p>不要使用系统的&nbsp;<code>Math.random()</code>&nbsp;方法。</p>

<ol>
</ol>

<p>&nbsp;</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入: </strong>1
<strong>输出: </strong>[7]
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入: </strong>2
<strong>输出: </strong>[8,4]
</pre>

<p><strong>示例 3:</strong></p>

<pre>
<strong>输入: </strong>3
<strong>输出: </strong>[8,1,10]
</pre>

<p>&nbsp;</p>

<p><strong>提示:</strong></p>

<ol>
	<li><code>rand7</code>&nbsp;已定义。</li>
	<li>传入参数:&nbsp;<code>n</code>&nbsp;表示&nbsp;<code>rand10</code>&nbsp;的调用次数。</li>
</ol>

<p>&nbsp;</p>

<p><strong>进阶:</strong></p>

<ol>
	<li><code>rand7()</code>调用次数的&nbsp;<a href="https://en.wikipedia.org/wiki/Expected_value" target="_blank">期望值</a>&nbsp;是多少&nbsp;?</li>
	<li>你能否尽量少调用 <code>rand7()</code> ?</li>
</ol>

{% endraw %}

### 相关话题
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[拒绝采样](https://github.com/awesee/leetcode/tree/main/tag/rejection-sampling/README.md)]
  [[概率与统计](https://github.com/awesee/leetcode/tree/main/tag/probability-and-statistics/README.md)]
  [[随机化](https://github.com/awesee/leetcode/tree/main/tag/randomized/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/implement-rand10-using-rand7)
