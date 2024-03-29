---
layout:     single
title:      "预测赢家"
date:       2017-05-01 21:30:00 +0800
categories: [Leetcode]
tags:       [Recursion, Array, Math, Dynamic Programming, Game Theory]
permalink:  /problems/predict-the-winner/
---

## 486. 预测赢家 (Medium)

{% raw %}

<p>给定一个表示分数的非负整数数组。 玩家 1 从数组任意一端拿取一个分数，随后玩家 2 继续从剩余数组任意一端拿取分数，然后玩家 1 拿，&hellip;&hellip; 。每次一个玩家只能拿取一个分数，分数被拿取之后不再可取。直到没有剩余分数可取时游戏结束。最终获得分数总和最多的玩家获胜。</p>

<p>给定一个表示分数的数组，预测玩家1是否会成为赢家。你可以假设每个玩家的玩法都会使他的分数最大化。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>[1, 5, 2]
<strong>输出：</strong>False
<strong>解释：</strong>一开始，玩家1可以从1和2中进行选择。
如果他选择 2（或者 1 ），那么玩家 2 可以从 1（或者 2 ）和 5 中进行选择。如果玩家 2 选择了 5 ，那么玩家 1 则只剩下 1（或者 2 ）可选。
所以，玩家 1 的最终分数为 1 + 2 = 3，而玩家 2 为 5 。
因此，玩家 1 永远不会成为赢家，返回 False 。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>[1, 5, 233, 7]
<strong>输出：</strong>True
<strong>解释：</strong>玩家 1 一开始选择 1 。然后玩家 2 必须从 5 和 7 中进行选择。无论玩家 2 选择了哪个，玩家 1 都可以选择 233 。
     最终，玩家 1（234 分）比玩家 2（12 分）获得更多的分数，所以返回 True，表示玩家 1 可以成为赢家。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li>1 &lt;= 给定的数组长度&nbsp;&lt;= 20.</li>
	<li>数组里所有分数都为非负数且不会大于 10000000 。</li>
	<li>如果最终两个玩家的分数相等，那么玩家 1 仍为赢家。</li>
</ul>

{% endraw %}

### 相关话题
  [[递归](https://github.com/awesee/leetcode/tree/main/tag/recursion/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[博弈](https://github.com/awesee/leetcode/tree/main/tag/game-theory/README.md)]

### 相似题目
  1. [我能赢吗](/problems/can-i-win) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/predict-the-winner)
