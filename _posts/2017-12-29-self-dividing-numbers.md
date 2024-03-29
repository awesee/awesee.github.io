---
layout:     single
title:      "自除数"
date:       2017-12-29 21:30:00 +0800
categories: [Leetcode]
tags:       [Math]
permalink:  /problems/self-dividing-numbers/
---

## 728. 自除数 (Easy)

{% raw %}

<p><em>自除数&nbsp;</em>是指可以被它包含的每一位数除尽的数。</p>

<p>例如，128 是一个自除数，因为&nbsp;<code>128 % 1 == 0</code>，<code>128 % 2 == 0</code>，<code>128 % 8 == 0</code>。</p>

<p>还有，自除数不允许包含 0 。</p>

<p>给定上边界和下边界数字，输出一个列表，列表的元素是边界（含边界）内所有的自除数。</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong> 
上边界left = 1, 下边界right = 22
<strong>输出：</strong> [1, 2, 3, 4, 5, 6, 7, 8, 9, 11, 12, 15, 22]
</pre>

<p><strong>注意：</strong></p>

<ul>
	<li>每个输入参数的边界满足&nbsp;<code>1 &lt;= left &lt;= right &lt;= 10000</code>。</li>
</ul>

{% endraw %}

### 相关话题
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]

### 相似题目
  1. [完美数](/problems/perfect-number) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/self-dividing-numbers)
