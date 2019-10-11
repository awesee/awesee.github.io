---
layout:     single
title:      "一年中的第几天"
date:       2019-02-28 21:30:00 +0800
categories: [Leetcode]
tags:       [Math]
permalink:  /problems/day-of-the-year/
---

## 1154. 一年中的第几天 (Easy)

{% raw %}

<p>给你一个按 <code>YYYY-MM-DD</code> 格式表示日期的字符串&nbsp;<code>date</code>，请你计算并返回该日期是当年的第几天。</p>

<p>通常情况下，我们认为 1 月 1 日是每年的第 1 天，1 月 2 日是每年的第 2 天，依此类推。每个月的天数与现行公元纪年法（格里高利历）一致。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>date = &quot;2019-01-09&quot;
<strong>输出：</strong>9
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>date = &quot;2019-02-10&quot;
<strong>输出：</strong>41
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>date = &quot;2003-03-01&quot;
<strong>输出：</strong>60
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>date = &quot;2004-03-01&quot;
<strong>输出：</strong>61</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>date.length == 10</code></li>
	<li><code>date[4] == date[7] == &#39;-&#39;</code>，其他的&nbsp;<code>date[i]</code>&nbsp;都是数字。</li>
	<li><code>date</code> 表示的范围从 1900 年 1 月 1 日至 2019 年 12 月 31 日。</li>
</ul>

{% endraw %}

### 相关话题
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/day-of-the-year)
