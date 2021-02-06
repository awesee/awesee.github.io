---
layout:     single
title:      "快乐数"
date:       2016-07-21 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, Math]
permalink:  /problems/happy-number/
---

## 202. 快乐数 (Easy)

{% raw %}

<p>编写一个算法来判断一个数 <code>n</code> 是不是快乐数。</p>

<p>「快乐数」定义为：</p>

<ul>
	<li>对于一个正整数，每一次将该数替换为它每个位置上的数字的平方和。</li>
	<li>然后重复这个过程直到这个数变为 1，也可能是 <strong>无限循环</strong> 但始终变不到 1。</li>
	<li>如果 <strong>可以变为</strong>  1，那么这个数就是快乐数。</li>
</ul>

<p>如果 <code>n</code> 是快乐数就返回 <code>true</code> ；不是，则返回 <code>false</code> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>19
<strong>输出：</strong>true
<strong>解释：
</strong>1<sup>2</sup> + 9<sup>2</sup> = 82
8<sup>2</sup> + 2<sup>2</sup> = 68
6<sup>2</sup> + 8<sup>2</sup> = 100
1<sup>2</sup> + 0<sup>2</sup> + 0<sup>2</sup> = 1
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>n = 2
<strong>输出：</strong>false
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= n <= 2<sup>31</sup> - 1</code></li>
</ul>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

### 相似题目
  1. [环形链表](/problems/linked-list-cycle) (Easy)
  1. [各位相加](/problems/add-digits) (Easy)
  1. [丑数](/problems/ugly-number) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/happy-number)
