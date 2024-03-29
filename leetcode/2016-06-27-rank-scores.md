---
layout:     single
title:      "分数排名"
date:       2016-06-27 21:30:00 +0800
categories: [Leetcode]
tags:       [Database]
permalink:  /problems/rank-scores/
---

## 178. 分数排名 (Medium)

{% raw %}

<p>编写一个 SQL 查询来实现分数排名。</p>

<p>如果两个分数相同，则两个分数排名（Rank）相同。请注意，平分后的下一个名次应该是下一个连续的整数值。换句话说，名次之间不应该有&ldquo;间隔&rdquo;。</p>

<pre>+----+-------+
| Id | Score |
+----+-------+
| 1  | 3.50  |
| 2  | 3.65  |
| 3  | 4.00  |
| 4  | 3.85  |
| 5  | 4.00  |
| 6  | 3.65  |
+----+-------+
</pre>

<p>例如，根据上述给定的&nbsp;<code>Scores</code> 表，你的查询应该返回（按分数从高到低排列）：</p>

<pre>+-------+------+
| Score | Rank |
+-------+------+
| 4.00  | 1    |
| 4.00  | 1    |
| 3.85  | 2    |
|&nbsp;3.65  | 3    |
| 3.65  | 3    |
| 3.50  | 4    |
+-------+------+
</pre>

<p><strong>重要提示：</strong>对于 MySQL 解决方案，如果要转义用作列名的保留字，可以在关键字之前和之后使用撇号。例如 <strong>`Rank`</strong></p>

{% endraw %}

### 相关话题
  [[数据库](https://github.com/awesee/leetcode/tree/main/tag/database/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/rank-scores)
