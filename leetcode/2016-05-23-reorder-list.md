---
layout:     single
title:      "重排链表"
date:       2016-05-23 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Recursion, Linked List, Two Pointers]
permalink:  /problems/reorder-list/
---

## 143. 重排链表 (Medium)

{% raw %}

<p>给定一个单链表 <code>L</code><em> </em>的头节点 <code>head</code> ，单链表 <code>L</code> 表示为：</p>

<p><code> L<sub>0 </sub>→ L<sub>1 </sub>→ … → L<sub>n-1 </sub>→ L<sub>n </sub></code><br />
请将其重新排列后变为：</p>

<p><code>L<sub>0 </sub>→ L<sub>n </sub>→ L<sub>1 </sub>→ L<sub>n-1 </sub>→ L<sub>2 </sub>→ L<sub>n-2 </sub>→ …</code></p>

<p>不能只是单纯的改变节点内部的值，而是需要实际的进行节点交换。</p>

<p> </p>

<p><strong>示例 1:</strong></p>

<p><img alt="" src="https://pic.leetcode-cn.com/1626420311-PkUiGI-image.png" style="width: 240px; " /></p>

<pre>
<strong>输入: </strong>head = [1,2,3,4]
<strong>输出: </strong>[1,4,2,3]</pre>

<p><strong>示例 2:</strong></p>

<p><img alt="" src="https://pic.leetcode-cn.com/1626420320-YUiulT-image.png" style="width: 320px; " /></p>

<pre>
<strong>输入: </strong>head = [1,2,3,4,5]
<strong>输出: </strong>[1,5,2,4,3]</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>链表的长度范围为 <code>[1, 5 * 10<sup>4</sup>]</code></li>
	<li><code>1 <= node.val <= 1000</code></li>
</ul>

{% endraw %}

### 相关话题
  [[栈](https://github.com/openset/leetcode/tree/master/tag/stack/README.md)]
  [[递归](https://github.com/openset/leetcode/tree/master/tag/recursion/README.md)]
  [[链表](https://github.com/openset/leetcode/tree/master/tag/linked-list/README.md)]
  [[双指针](https://github.com/openset/leetcode/tree/master/tag/two-pointers/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/reorder-list)
