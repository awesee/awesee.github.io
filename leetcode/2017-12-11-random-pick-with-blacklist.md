---
layout:     single
title:      "黑名单中的随机数"
date:       2017-12-11 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, Math, Binary Search, Sorting, Randomized]
permalink:  /problems/random-pick-with-blacklist/
---

## 710. 黑名单中的随机数 (Hard)

{% raw %}

<p>给定一个包含 <code>[0，n)</code> 中不重复整数的黑名单 <code>blacklist</code> ，写一个函数从 <code>[0, n)</code> 中返回一个<strong>不在</strong> <code>blacklist</code> 中的随机整数。</p>

<p>对它进行优化使其尽量少调用系统方法 <code>Math.random()</code> 。</p>

<p><strong>提示:</strong></p>

<ol>
	<li><code>1 <= n <= 1000000000</code></li>
	<li><code>0 <= blacklist.length < min(100000, N)</code></li>
	<li><code>[0, n)</code> 不包含 <code>n</code> ，详细参见 <a href="https://en.wikipedia.org/wiki/Interval_(mathematics)" target="_blank">interval notation</a> 。</li>
</ol>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：
</strong>["Solution","pick","pick","pick"]
[[1,[]],[],[],[]]
<strong>输出：</strong>[null,0,0,0]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：
</strong>["Solution","pick","pick","pick"]
[[2,[]],[],[],[]]
<strong>输出：</strong>[null,1,1,1]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：
</strong>["Solution","pick","pick","pick"]
[[3,[1]],[],[],[]]
<strong>输出：</strong>[null,0,0,2]
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入： 
</strong>["Solution","pick","pick","pick"]
[[4,[2]],[],[],[]]
<strong>输出：</strong>[null,1,3,1]
</pre>

<p><strong>输入语法说明：</strong></p>

<p>输入是两个列表：调用成员函数名和调用的参数。<code>Solution</code>的构造函数有两个参数，<code>n</code> 和黑名单 <code>blacklist</code>。<code>pick</code> 没有参数，输入参数是一个列表，即使参数为空，也会输入一个 <code>[]</code> 空列表。</p>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]
  [[随机化](https://github.com/awesee/leetcode/tree/main/tag/randomized/README.md)]

### 相似题目
  1. [随机数索引](/problems/random-pick-index) (Medium)
  1. [按权重随机选择](/problems/random-pick-with-weight) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/random-pick-with-blacklist)
