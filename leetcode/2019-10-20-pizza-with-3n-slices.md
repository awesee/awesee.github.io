---
layout:     single
title:      "3n 块披萨"
date:       2019-10-20 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Array, Dynamic Programming, Heap (Priority Queue)]
permalink:  /problems/pizza-with-3n-slices/
---

## 1388. 3n 块披萨 (Hard)

{% raw %}

<p>给你一个披萨，它由 3n 块不同大小的部分组成，现在你和你的朋友们需要按照如下规则来分披萨：</p>

<ul>
	<li>你挑选 <strong>任意</strong>&nbsp;一块披萨。</li>
	<li>Alice 将会挑选你所选择的披萨逆时针方向的下一块披萨。</li>
	<li>Bob 将会挑选你所选择的披萨顺时针方向的下一块披萨。</li>
	<li>重复上述过程直到没有披萨剩下。</li>
</ul>

<p>每一块披萨的大小按顺时针方向由循环数组 <code>slices</code>&nbsp;表示。</p>

<p>请你返回你可以获得的披萨大小总和的最大值。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<p><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/03/21/sample_3_1723.png" style="height: 240px; width: 475px;"></p>

<pre><strong>输入：</strong>slices = [1,2,3,4,5,6]
<strong>输出：</strong>10
<strong>解释：</strong>选择大小为 4 的披萨，Alice 和 Bob 分别挑选大小为 3 和 5 的披萨。然后你选择大小为 6 的披萨，Alice 和 Bob 分别挑选大小为 2 和 1 的披萨。你获得的披萨总大小为 4 + 6 = 10 。
</pre>

<p><strong>示例 2：</strong></p>

<p><strong><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/03/21/sample_4_1723.png" style="height: 250px; width: 475px;"></strong></p>

<pre><strong>输入：</strong>slices = [8,9,8,6,1,1]
<strong>输出：</strong>16
<strong>解释：</strong>两轮都选大小为 8 的披萨。如果你选择大小为 9 的披萨，你的朋友们就会选择大小为 8 的披萨，这种情况下你的总和不是最大的。
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>slices = [4,1,2,5,8,3,1,9,7]
<strong>输出：</strong>21
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>slices = [3,1,2]
<strong>输出：</strong>3
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= slices.length &lt;= 500</code></li>
	<li><code>slices.length % 3 == 0</code></li>
	<li><code>1 &lt;= slices[i] &lt;= 1000</code></li>
</ul>

{% endraw %}

### 相关话题
  [[贪心](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]
  [[堆（优先队列）](https://github.com/openset/leetcode/tree/master/tag/heap-priority-queue/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/pizza-with-3n-slices)
