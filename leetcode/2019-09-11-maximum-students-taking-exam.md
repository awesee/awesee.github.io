---
layout:     single
title:      "参加考试的最大学生数"
date:       2019-09-11 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Array, Dynamic Programming, Bitmask, Matrix]
permalink:  /problems/maximum-students-taking-exam/
---

## 1349. 参加考试的最大学生数 (Hard)

{% raw %}

<p>给你一个&nbsp;<code>m&nbsp;* n</code>&nbsp;的矩阵 <code>seats</code>&nbsp;表示教室中的座位分布。如果座位是坏的（不可用），就用&nbsp;<code>&#39;#&#39;</code>&nbsp;表示；否则，用&nbsp;<code>&#39;.&#39;</code>&nbsp;表示。</p>

<p>学生可以看到左侧、右侧、左上、右上这四个方向上紧邻他的学生的答卷，但是看不到直接坐在他前面或者后面的学生的答卷。请你计算并返回该考场可以容纳的一起参加考试且无法作弊的最大学生人数。</p>

<p>学生必须坐在状况良好的座位上。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<p><img src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/02/09/image.png" style="height: 197px; width: 339px;"></p>

<pre><strong>输入：</strong>seats = [[&quot;#&quot;,&quot;.&quot;,&quot;#&quot;,&quot;#&quot;,&quot;.&quot;,&quot;#&quot;],
&nbsp;             [&quot;.&quot;,&quot;#&quot;,&quot;#&quot;,&quot;#&quot;,&quot;#&quot;,&quot;.&quot;],
&nbsp;             [&quot;#&quot;,&quot;.&quot;,&quot;#&quot;,&quot;#&quot;,&quot;.&quot;,&quot;#&quot;]]
<strong>输出：</strong>4
<strong>解释：</strong>教师可以让 4 个学生坐在可用的座位上，这样他们就无法在考试中作弊。 
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>seats = [[&quot;.&quot;,&quot;#&quot;],
&nbsp;             [&quot;#&quot;,&quot;#&quot;],
&nbsp;             [&quot;#&quot;,&quot;.&quot;],
&nbsp;             [&quot;#&quot;,&quot;#&quot;],
&nbsp;             [&quot;.&quot;,&quot;#&quot;]]
<strong>输出：</strong>3
<strong>解释：</strong>让所有学生坐在可用的座位上。
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>seats = [[&quot;#&quot;,&quot;.&quot;,&quot;<strong>.</strong>&quot;,&quot;.&quot;,&quot;#&quot;],
&nbsp;             [&quot;<strong>.</strong>&quot;,&quot;#&quot;,&quot;<strong>.</strong>&quot;,&quot;#&quot;,&quot;<strong>.</strong>&quot;],
&nbsp;             [&quot;<strong>.</strong>&quot;,&quot;.&quot;,&quot;#&quot;,&quot;.&quot;,&quot;<strong>.</strong>&quot;],
&nbsp;             [&quot;<strong>.</strong>&quot;,&quot;#&quot;,&quot;<strong>.</strong>&quot;,&quot;#&quot;,&quot;<strong>.</strong>&quot;],
&nbsp;             [&quot;#&quot;,&quot;.&quot;,&quot;<strong>.</strong>&quot;,&quot;.&quot;,&quot;#&quot;]]
<strong>输出：</strong>10
<strong>解释：</strong>让学生坐在第 1、3 和 5 列的可用座位上。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>seats</code>&nbsp;只包含字符&nbsp;<code>&#39;.&#39;&nbsp;和</code><code>&#39;#&#39;</code></li>
	<li><code>m ==&nbsp;seats.length</code></li>
	<li><code>n ==&nbsp;seats[i].length</code></li>
	<li><code>1 &lt;= m &lt;= 8</code></li>
	<li><code>1 &lt;= n &lt;= 8</code></li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[状态压缩](https://github.com/awesee/leetcode/tree/main/tag/bitmask/README.md)]
  [[矩阵](https://github.com/awesee/leetcode/tree/main/tag/matrix/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/maximum-students-taking-exam)
