---
layout:     single
title:      "飞机座位分配概率"
date:       2019-05-12 21:30:00 +0800
categories: [Leetcode]
tags:       [Brainteaser, Math, Dynamic Programming]
permalink:  /problems/airplane-seat-assignment-probability/
---

## 1227. 飞机座位分配概率 (Medium)

{% raw %}

<p>有 <code>n</code> 位乘客即将登机，飞机正好有 <code>n</code> 个座位。第一位乘客的票丢了，他随便选了一个座位坐下。</p>

<p>剩下的乘客将会：</p>

<ul>
	<li>
	<p>如果他们自己的座位还空着，就坐到自己的座位上，</p>
	</li>
	<li>当他们自己的座位被占用时，随机选择其他座位</li>
</ul>

<p>第 <code>n</code>&nbsp;位乘客坐在自己的座位上的概率是多少？</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>n = 1
<strong>输出：</strong>1.00000
<strong>解释：</strong>第一个人只会坐在自己的位置上。</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入:</strong> n = 2
<strong>输出:</strong> 0.50000
<strong>解释：</strong>在第一个人选好座位坐下后，第二个人坐在自己的座位上的概率是 0.5。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= n &lt;= 10^5</code></li>
</ul>

{% endraw %}

### 相关话题
  [[脑筋急转弯](https://github.com/openset/leetcode/tree/master/tag/brainteaser/README.md)]
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/airplane-seat-assignment-probability)
