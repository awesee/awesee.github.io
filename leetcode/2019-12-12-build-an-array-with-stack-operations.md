---
layout:     single
title:      "用栈操作构建数组"
date:       2019-12-12 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, Array, Simulation]
permalink:  /problems/build-an-array-with-stack-operations/
---

## 1441. 用栈操作构建数组 (Easy)

{% raw %}

<p>给你一个目标数组 <code>target</code> 和一个整数 <code>n</code>。每次迭代，需要从  <code>list = {1,2,3..., n}</code> 中依序读取一个数字。</p>

<p>请使用下述操作来构建目标数组 <code>target</code> ：</p>

<ul>
	<li><strong>Push</strong>：从 <code>list</code> 中读取一个新元素， 并将其推入数组中。</li>
	<li><strong>Pop</strong>：删除数组中的最后一个元素。</li>
	<li>如果目标数组构建完成，就停止读取更多元素。</li>
</ul>

<p>题目数据保证目标数组严格递增，并且只包含 <code>1</code> 到 <code>n</code> 之间的数字。</p>

<p>请返回构建目标数组所用的操作序列。</p>

<p>题目数据保证答案是唯一的。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>target = [1,3], n = 3
<strong>输出：</strong>["Push","Push","Pop","Push"]
<strong>解释： 
</strong>读取 1 并自动推入数组 -> [1]
读取 2 并自动推入数组，然后删除它 -> [1]
读取 3 并自动推入数组 -> [1,3]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>target = [1,2,3], n = 3
<strong>输出：</strong>["Push","Push","Push"]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>target = [1,2], n = 4
<strong>输出：</strong>["Push","Push"]
<strong>解释：</strong>只需要读取前 2 个数字就可以停止。
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>target = [2,3,4], n = 4
<strong>输出：</strong>["Push","Pop","Push","Push","Push"]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= target.length <= 100</code></li>
	<li><code>1 <= target[i] <= 100</code></li>
	<li><code>1 <= n <= 100</code></li>
	<li><code>target</code> 是严格递增的</li>
</ul>

{% endraw %}

### 相关话题
  [[栈](https://github.com/awesee/leetcode/tree/main/tag/stack/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[模拟](https://github.com/awesee/leetcode/tree/main/tag/simulation/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/build-an-array-with-stack-operations)
