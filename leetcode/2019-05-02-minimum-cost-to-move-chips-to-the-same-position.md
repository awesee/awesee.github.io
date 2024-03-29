---
layout:     single
title:      "玩筹码"
date:       2019-05-02 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Array, Math]
permalink:  /problems/minimum-cost-to-move-chips-to-the-same-position/
---

## 1217. 玩筹码 (Easy)

{% raw %}

<p>数轴上放置了一些筹码，每个筹码的位置存在数组&nbsp;<code>chips</code>&nbsp;当中。</p>

<p>你可以对 <strong>任何筹码</strong> 执行下面两种操作之一（<strong>不限操作次数</strong>，0 次也可以）：</p>

<ul>
	<li>将第 <code>i</code> 个筹码向左或者右移动 2 个单位，代价为 <strong>0</strong>。</li>
	<li>将第 <code>i</code> 个筹码向左或者右移动 1 个单位，代价为 <strong>1</strong>。</li>
</ul>

<p>最开始的时候，同一位置上也可能放着两个或者更多的筹码。</p>

<p>返回将所有筹码移动到同一位置（任意位置）上所需要的最小代价。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>chips = [1,2,3]
<strong>输出：</strong>1
<strong>解释：</strong>第二个筹码移动到位置三的代价是 1，第一个筹码移动到位置三的代价是 0，总代价为 1。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>chips = [2,2,2,3,3]
<strong>输出：</strong>2
<strong>解释：</strong>第四和第五个筹码移动到位置二的代价都是 1，所以最小总代价为 2。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= chips.length &lt;= 100</code></li>
	<li><code>1 &lt;= chips[i] &lt;= 10^9</code></li>
</ul>

{% endraw %}

### 相关话题
  [[贪心](https://github.com/awesee/leetcode/tree/main/tag/greedy/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/minimum-cost-to-move-chips-to-the-same-position)
