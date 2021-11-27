---
layout:     single
title:      "数组中的最长山脉"
date:       2018-04-25 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Two Pointers, Dynamic Programming, Enumeration]
permalink:  /problems/longest-mountain-in-array/
---

## 845. 数组中的最长山脉 (Medium)

{% raw %}

<p>我们把数组 A 中符合下列属性的任意连续子数组 B 称为 &ldquo;<em>山脉&rdquo;</em>：</p>

<ul>
	<li><code>B.length &gt;= 3</code></li>
	<li>存在 <code>0 &lt; i&nbsp;&lt; B.length - 1</code> 使得 <code>B[0] &lt; B[1] &lt; ... B[i-1] &lt; B[i] &gt; B[i+1] &gt; ... &gt; B[B.length - 1]</code></li>
</ul>

<p>（注意：B 可以是 A 的任意子数组，包括整个数组 A。）</p>

<p>给出一个整数数组 <code>A</code>，返回最长 <em>&ldquo;山脉&rdquo;</em>&nbsp;的长度。</p>

<p>如果不含有 &ldquo;<em>山脉&rdquo;&nbsp;</em>则返回 <code>0</code>。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>[2,1,4,7,3,2,5]
<strong>输出：</strong>5
<strong>解释：</strong>最长的 &ldquo;山脉&rdquo; 是 [1,4,7,3,2]，长度为 5。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>[2,2,2]
<strong>输出：</strong>0
<strong>解释：</strong>不含 &ldquo;山脉&rdquo;。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>0 &lt;= A.length &lt;= 10000</code></li>
	<li><code>0 &lt;= A[i] &lt;= 10000</code></li>
</ol>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[双指针](https://github.com/awesee/leetcode/tree/main/tag/two-pointers/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[枚举](https://github.com/awesee/leetcode/tree/main/tag/enumeration/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/longest-mountain-in-array)
