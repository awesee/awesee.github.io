---
layout:     single
title:      "删除重复的电子邮箱"
date:       2016-07-15 21:30:00 +0800
categories: [Leetcode]
tags:       [Database]
permalink:  /problems/delete-duplicate-emails/
---

## 196. 删除重复的电子邮箱 (Easy)

{% raw %}

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

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li>执行 SQL 之后，输出是整个 <code>Person</code>&nbsp;表。</li>
	<li>使用 <code>delete</code> 语句。</li>
</ul>

{% endraw %}

### 相关话题
  [[数据库](https://github.com/awesee/leetcode/tree/main/tag/database/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/delete-duplicate-emails)
