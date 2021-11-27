---
layout:     single
title:      "Excel 表列序号"
date:       2016-06-20 21:30:00 +0800
categories: [Leetcode]
tags:       [Math, String]
permalink:  /problems/excel-sheet-column-number/
---

## 171. Excel 表列序号 (Easy)

{% raw %}

<p>给你一个字符串&nbsp;<code>columnTitle</code> ，表示 Excel 表格中的列名称。返回该列名称对应的列序号。</p>

<p>&nbsp;</p>

<p>例如，</p>

<pre>
    A -&gt; 1
    B -&gt; 2
    C -&gt; 3
    ...
    Z -&gt; 26
    AA -&gt; 27
    AB -&gt; 28 
    ...
</pre>

<p>&nbsp;</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> columnTitle = "A"
<strong>输出:</strong> 1
</pre>

<p><strong>示例&nbsp;2:</strong></p>

<pre>
<strong>输入: </strong>columnTitle = "AB"
<strong>输出:</strong> 28
</pre>

<p><strong>示例&nbsp;3:</strong></p>

<pre>
<strong>输入: </strong>columnTitle = "ZY"
<strong>输出:</strong> 701</pre>

<p><strong>示例 4:</strong></p>

<pre>
<strong>输入: </strong>columnTitle = "FXSHRXW"
<strong>输出: </strong>2147483647
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= columnTitle.length &lt;= 7</code></li>
	<li><code>columnTitle</code> 仅由大写英文组成</li>
	<li><code>columnTitle</code> 在范围 <code>["A", "FXSHRXW"]</code> 内</li>
</ul>

{% endraw %}

### 相关话题
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

### 相似题目
  1. [Excel表列名称](/problems/excel-sheet-column-title) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/excel-sheet-column-number)
