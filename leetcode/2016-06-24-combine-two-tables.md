---
layout:     single
title:      "组合两个表"
date:       2016-06-24 21:30:00 +0800
categories: [Leetcode]
tags:       [Database]
permalink:  /problems/combine-two-tables/
---

## 175. 组合两个表 (Easy)

{% raw %}

<p>表1: <code>Person</code></p>

<pre>+-------------+---------+
| 列名         | 类型     |
+-------------+---------+
| PersonId    | int     |
| FirstName   | varchar |
| LastName    | varchar |
+-------------+---------+
PersonId 是上表主键
</pre>

<p>表2: <code>Address</code></p>

<pre>+-------------+---------+
| 列名         | 类型    |
+-------------+---------+
| AddressId   | int     |
| PersonId    | int     |
| City        | varchar |
| State       | varchar |
+-------------+---------+
AddressId 是上表主键
</pre>

<p>&nbsp;</p>

<p>编写一个 SQL 查询，满足条件：无论 person 是否有地址信息，都需要基于上述两表提供&nbsp;person 的以下信息：</p>

<p>&nbsp;</p>

<pre>FirstName, LastName, City, State
</pre>

{% endraw %}

### 相关话题
  [[数据库](https://github.com/awesee/leetcode/tree/master/tag/database/README.md)]

### 相似题目
  1. [员工奖金](/problems/employee-bonus) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/combine-two-tables)
