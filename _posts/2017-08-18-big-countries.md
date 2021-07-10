---
layout:     single
title:      "大的国家"
date:       2017-08-18 21:30:00 +0800
categories: [Leetcode]
tags:       [Database]
permalink:  /problems/big-countries/
---

## 595. 大的国家 (Easy)

{% raw %}

<p>这里有张 <code>World</code> 表</p>

<pre>
+-----------------+------------+------------+--------------+---------------+
| name            | continent  | area       | population   | gdp           |
+-----------------+------------+------------+--------------+---------------+
| Afghanistan     | Asia       | 652230     | 25500100     | 20343000      |
| Albania         | Europe     | 28748      | 2831741      | 12960000      |
| Algeria         | Africa     | 2381741    | 37100000     | 188681000     |
| Andorra         | Europe     | 468        | 78115        | 3712000       |
| Angola          | Africa     | 1246700    | 20609294     | 100990000     |
+-----------------+------------+------------+--------------+---------------+
</pre>

<p>如果一个国家的面积超过 300 万平方公里，或者人口超过 2500 万，那么这个国家就是大国家。</p>

<p>编写一个 SQL 查询，输出表中所有大国家的名称、人口和面积。</p>

<p>例如，根据上表，我们应该输出:</p>

<pre>
+--------------+-------------+--------------+
| name         | population  | area         |
+--------------+-------------+--------------+
| Afghanistan  | 25500100    | 652230       |
| Algeria      | 37100000    | 2381741      |
+--------------+-------------+--------------+
</pre>

{% endraw %}

### 相关话题
  [[数据库](https://github.com/openset/leetcode/tree/master/tag/database/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/big-countries)
