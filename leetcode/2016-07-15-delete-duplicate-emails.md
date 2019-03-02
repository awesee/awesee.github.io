---
layout:     single
title:      "删除重复的电子邮箱"
date:       2016-07-15 21:30:00 +0800
categories: [leetcode]
tags:       []
permalink:  /delete-duplicate-emails/
---

## 196. 删除重复的电子邮箱 (Easy)

<p>编写一个 SQL 查询，来删除&nbsp;<code>Person</code>&nbsp;表中所有重复的电子邮箱，重复的邮箱里只保留&nbsp;<strong>Id&nbsp;</strong><em>最小&nbsp;</em>的那个。</p>

<pre>+----+------------------+
| Id | Email            |
+----+------------------+
| 1  | john@example.com |
| 2  | bob@example.com  |
| 3  | john@example.com |
+----+------------------+
Id 是这个表的主键。
</pre>

<p>例如，在运行你的查询语句之后，上面的 <code>Person</code> 表应返回以下几行:</p>

<pre>+----+------------------+
| Id | Email            |
+----+------------------+
| 1  | john@example.com |
| 2  | bob@example.com  |
+----+------------------+
</pre>

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/delete-duplicate-emails)
