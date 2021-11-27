---
layout:     single
title:      "第N高的薪水"
date:       2016-06-26 21:30:00 +0800
categories: [Leetcode]
tags:       [Database]
permalink:  /problems/nth-highest-salary/
---

## 177. 第N高的薪水 (Medium)

{% raw %}

<p>编写一个 SQL 查询，获取 <code>Employee</code> 表中第&nbsp;<em>n&nbsp;</em>高的薪水（Salary）。</p>

<pre>+----+--------+
| Id | Salary |
+----+--------+
| 1  | 100    |
| 2  | 200    |
| 3  | 300    |
+----+--------+
</pre>

<p>例如上述&nbsp;<code>Employee</code>&nbsp;表，<em>n = 2&nbsp;</em>时，应返回第二高的薪水&nbsp;<code>200</code>。如果不存在第&nbsp;<em>n&nbsp;</em>高的薪水，那么查询应返回&nbsp;<code>null</code>。</p>

<pre>+------------------------+
| getNthHighestSalary(2) |
+------------------------+
| 200                    |
+------------------------+
</pre>

{% endraw %}

### 相关话题
  [[数据库](https://github.com/awesee/leetcode/tree/main/tag/database/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/nth-highest-salary)
