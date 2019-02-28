---
layout:     single
title:      "183. 从不订购的客户 (Easy)"
date:       2016-07-02 21:30:00 +0800
categories: [leetcode]
tags:       []
permalink:  /customers-who-never-order/
---

<p>某网站包含两个表，<code>Customers</code> 表和 <code>Orders</code> 表。编写一个 SQL 查询，找出所有从不订购任何东西的客户。</p>

<p><code>Customers</code> 表：</p>

<pre>+----+-------+
| Id | Name  |
+----+-------+
| 1  | Joe   |
| 2  | Henry |
| 3  | Sam   |
| 4  | Max   |
+----+-------+
</pre>

<p><code>Orders</code> 表：</p>

<pre>+----+------------+
| Id | CustomerId |
+----+------------+
| 1  | 3          |
| 2  | 1          |
+----+------------+
</pre>

<p>例如给定上述表格，你的查询应返回：</p>

<pre>+-----------+
| Customers |
+-----------+
| Henry     |
| Max       |
+-----------+
</pre>

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/customers-who-never-order)
