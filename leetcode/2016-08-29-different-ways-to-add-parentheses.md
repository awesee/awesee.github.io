---
layout:     single
title:      "为运算表达式设计优先级"
date:       2016-08-29 21:30:00 +0800
categories: [Leetcode]
tags:       [Recursion, Memoization, Math, String, Dynamic Programming]
permalink:  /problems/different-ways-to-add-parentheses/
---

## 241. 为运算表达式设计优先级 (Medium)

{% raw %}

<p>给定一个含有数字和运算符的字符串，为表达式添加括号，改变其运算优先级以求出不同的结果。你需要给出所有可能的组合的结果。有效的运算符号包含 <code>+</code>,&nbsp;<code>-</code>&nbsp;以及&nbsp;<code>*</code>&nbsp;。</p>

<p><strong>示例&nbsp;1:</strong></p>

<pre><strong>输入:</strong> <code>&quot;2-1-1&quot;</code>
<strong>输出:</strong> <code>[0, 2]</code>
<strong>解释: </strong>
((2-1)-1) = 0 
(2-(1-1)) = 2</pre>

<p><strong>示例&nbsp;2:</strong></p>

<pre><strong>输入: </strong><code>&quot;2*3-4*5&quot;</code>
<strong>输出:</strong> <code>[-34, -14, -10, -10, 10]</code>
<strong>解释: 
</strong>(2*(3-(4*5))) = -34 
((2*3)-(4*5)) = -14 
((2*(3-4))*5) = -10 
(2*((3-4)*5)) = -10 
(((2*3)-4)*5) = 10</pre>

{% endraw %}

### 相关话题
  [[递归](https://github.com/awesee/leetcode/tree/main/tag/recursion/README.md)]
  [[记忆化搜索](https://github.com/awesee/leetcode/tree/main/tag/memoization/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

### 相似题目
  1. [不同的二叉搜索树 II](/problems/unique-binary-search-trees-ii) (Medium)
  1. [基本计算器](/problems/basic-calculator) (Hard)
  1. [给表达式添加运算符](/problems/expression-add-operators) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/different-ways-to-add-parentheses)
