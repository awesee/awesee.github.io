---
layout:     single
title:      "从不订购的客户"
date:       2016-07-02 21:30:00 +0800
categories: [Leetcode]
tags:       [Database]
permalink:  /problems/customers-who-never-order/
---

## 183. 从不订购的客户 (Easy)

{% raw %}

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

{% endraw %}

### 相关话题
  [[数据库](https://github.com/awesee/leetcode/tree/main/tag/database/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/customers-who-never-order)
