---
layout:     single
title:      "能否连接形成数组"
date:       2020-06-28 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table]
permalink:  /problems/check-array-formation-through-concatenation/
---

## 1640. 能否连接形成数组 (Easy)

{% raw %}

<p>给你一个整数数组 <code>arr</code> ，数组中的每个整数 <strong>互不相同</strong> 。另有一个由整数数组构成的数组 <code>pieces</code>，其中的整数也 <strong>互不相同</strong> 。请你以 <strong>任意顺序</strong> 连接 <code>pieces</code> 中的数组以形成 <code>arr</code> 。但是，<strong>不允许</strong> 对每个数组 <code>pieces[i]</code> 中的整数重新排序。</p>

<p>如果可以连接<em> </em><code>pieces</code> 中的数组形成 <code>arr</code> ，返回 <code>true</code> ；否则，返回 <code>false</code> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>arr = [85], pieces = [[85]]
<strong>输出：</strong>true
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>arr = [15,88], pieces = [[88],[15]]
<strong>输出：</strong>true
<strong>解释：</strong>依次连接 <code>[15]</code> 和 <code>[88]</code>
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>arr = [49,18,16], pieces = [[16,18,49]]
<strong>输出：</strong>false
<strong>解释：</strong>即便数字相符，也不能重新排列 pieces[0]
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>arr = [91,4,64,78], pieces = [[78],[4,64],[91]]
<strong>输出：</strong>true
<strong>解释：</strong>依次连接 <code>[91]</code>、<code>[4,64]</code> 和 <code>[78]</code></pre>

<p><strong>示例 5：</strong></p>

<pre>
<strong>输入：</strong>arr = [1,3,5,7], pieces = [[2,4,6,8]]
<strong>输出：</strong>false
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= pieces.length <= arr.length <= 100</code></li>
	<li><code>sum(pieces[i].length) == arr.length</code></li>
	<li><code>1 <= pieces[i].length <= arr.length</code></li>
	<li><code>1 <= arr[i], pieces[i][j] <= 100</code></li>
	<li><code>arr</code> 中的整数 <strong>互不相同</strong></li>
	<li><code>pieces</code> 中的整数 <strong>互不相同</strong>（也就是说，如果将 <code>pieces</code> 扁平化成一维数组，数组中的所有整数互不相同）</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/check-array-formation-through-concatenation)
