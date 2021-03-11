---
layout:     single
title:      "两数相加"
date:       2016-01-03 21:30:00 +0800
categories: [Leetcode]
tags:       [Recursion, Linked List, Math]
permalink:  /problems/add-two-numbers/
---

## 2. 两数相加 (Medium)

{% raw %}

<p>给你两个 <strong>非空</strong> 的链表，表示两个非负的整数。它们每位数字都是按照 <strong>逆序</strong> 的方式存储的，并且每个节点只能存储 <strong>一位</strong> 数字。</p>

<p>请你将两个数相加，并以相同形式返回一个表示和的链表。</p>

<p>你可以假设除了数字 0 之外，这两个数都不会以 0 开头。</p>

<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2021/01/02/addtwonumber1.jpg" style="width: 483px; height: 342px;" />
<pre>
<strong>输入：</strong>l1 = [2,4,3], l2 = [5,6,4]
<strong>输出：</strong>[7,0,8]
<strong>解释：</strong>342 + 465 = 807.
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>l1 = [0], l2 = [0]
<strong>输出：</strong>[0]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>l1 = [9,9,9,9,9,9,9], l2 = [9,9,9,9]
<strong>输出：</strong>[8,9,9,9,0,0,0,1]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>每个链表中的节点数在范围 <code>[1, 100]</code> 内</li>
	<li><code>0 <= Node.val <= 9</code></li>
	<li>题目数据保证列表表示的数字不含前导零</li>
</ul>

{% endraw %}

### 相关话题
  [[递归](https://github.com/openset/leetcode/tree/master/tag/recursion/README.md)]
  [[链表](https://github.com/openset/leetcode/tree/master/tag/linked-list/README.md)]
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

### 相似题目
  1. [字符串相乘](/problems/multiply-strings) (Medium)
  1. [二进制求和](/problems/add-binary) (Easy)
  1. [两整数之和](/problems/sum-of-two-integers) (Medium)
  1. [字符串相加](/problems/add-strings) (Easy)
  1. [两数相加 II](/problems/add-two-numbers-ii) (Medium)
  1. [数组形式的整数加法](/problems/add-to-array-form-of-integer) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/add-two-numbers)
