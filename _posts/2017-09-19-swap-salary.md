---
layout:     single
title:      "变更性别"
date:       2017-09-19 21:30:00 +0800
categories: [Leetcode]
tags:       [Database]
permalink:  /problems/swap-salary/
---

## 627. 变更性别 (Easy)

{% raw %}

<div class="original__bRMd">
<div>
<p><code>Salary</code> 表：</p>

<pre>
+-------------+----------+
| Column Name | Type     |
+-------------+----------+
| id          | int      |
| name        | varchar  |
| sex         | ENUM     |
| salary      | int      |
+-------------+----------+
id 是这个表的主键。
sex 这一列的值是 ENUM 类型，只能从 ('m', 'f') 中取。
本表包含公司雇员的信息。
</pre>

<p>&nbsp;</p>

<p>请你编写一个 SQL 查询来交换所有的 <code>'f'</code> 和 <code>'m'</code> （即，将所有 <code>'f'</code> 变为 <code>'m'</code> ，反之亦然），仅使用 <strong>单个 update 语句</strong> ，且不产生中间临时表。</p>

<p>注意，你必须仅使用一条 update 语句，且 <strong>不能</strong> 使用 select 语句。</p>

<p>查询结果如下例所示：</p>

<p>&nbsp;</p>

<pre>
Salary 表：
+----+------+-----+--------+
| id | name | sex | salary |
+----+------+-----+--------+
| 1  | A    | m   | 2500   |
| 2  | B    | f   | 1500   |
| 3  | C    | m   | 5500   |
| 4  | D    | f   | 500    |
+----+------+-----+--------+

Result 表：
+----+------+-----+--------+
| id | name | sex | salary |
+----+------+-----+--------+
| 1  | A    | f   | 2500   |
| 2  | B    | m   | 1500   |
| 3  | C    | f   | 5500   |
| 4  | D    | m   | 500    |
+----+------+-----+--------+
(1, A) 和 (3, C) 从 'm' 变为 'f' 。
(2, B) 和 (4, D) 从 'f' 变为 'm' 。
</pre>
</div>
</div>

{% endraw %}

### 相关话题
  [[数据库](https://github.com/awesee/leetcode/tree/main/tag/database/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/swap-salary)
