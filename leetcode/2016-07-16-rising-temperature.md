---
layout:     single
title:      "上升的温度"
date:       2016-07-16 21:30:00 +0800
categories: [Leetcode]
tags:       []
permalink:  /problems/rising-temperature/
---

## 197. 上升的温度 (Easy)

{% raw %}

<p>给定一个 <code>Weather</code> 表，编写一个 SQL 查询，来查找与之前（昨天的）日期相比温度更高的所有日期的 Id。</p>

<pre>+---------+------------------+------------------+
| Id(INT) | RecordDate(DATE) | Temperature(INT) |
+---------+------------------+------------------+
|       1 |       2015-01-01 |               10 |
|       2 |       2015-01-02 |               25 |
|       3 |       2015-01-03 |               20 |
|       4 |       2015-01-04 |               30 |
+---------+------------------+------------------+</pre>

<p>例如，根据上述给定的 <code>Weather</code> 表格，返回如下 Id:</p>

<pre>+----+
| Id |
+----+
|  2 |
|  4 |
+----+</pre>

{% endraw %}

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/rising-temperature)
