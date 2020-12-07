---
layout:     single
title:      "灯泡开关"
date:       2016-11-15 21:30:00 +0800
categories: [Leetcode]
tags:       [Brainteaser, Math]
permalink:  /problems/bulb-switcher/
---

## 319. 灯泡开关 (Medium)

{% raw %}

<p>初始时有 <em>n </em>个灯泡关闭。</p>

<p>第 1 轮，你打开所有的灯泡。 第 2 轮，每两个灯泡你关闭一次。 第 3 轮，每三个灯泡切换一次开关（如果关闭则开启，如果开启则关闭）。</p>

<p>第 <em>i</em> 轮，每 <em>i </em>个灯泡切换一次开关。 对于第 <em>n </em>轮，你只切换最后一个灯泡的开关。</p>

<p>找出 <em>n </em>轮后有多少个亮着的灯泡。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<p><img alt="" src="https://assets.leetcode.com/uploads/2020/11/05/bulb.jpg" style="width: 421px; height: 321px;" /></p>

<pre>
<strong>输入：</strong>n =<strong> </strong>3
<strong>输出：</strong>1 
<strong>解释：</strong>
初始时, 灯泡状态 <strong>[关闭, 关闭, 关闭]</strong>.
第一轮后, 灯泡状态 <strong>[开启, 开启, 开启]</strong>.
第二轮后, 灯泡状态 <strong>[开启, 关闭, 开启]</strong>.
第三轮后, 灯泡状态 <strong>[开启, 关闭, 关闭]</strong>. 

你应该返回 1，因为只有一个灯泡还亮着。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>n = 0
<strong>输出：</strong>0
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>n = 1
<strong>输出：</strong>1
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 <= n <= 10<sup>9</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[脑筋急转弯](https://github.com/openset/leetcode/tree/master/tag/brainteaser/README.md)]
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

### 相似题目
  1. [灯泡开关 Ⅱ](/problems/bulb-switcher-ii) (Medium)
  1. [K 连续位的最小翻转次数](/problems/minimum-number-of-k-consecutive-bit-flips) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/bulb-switcher)
