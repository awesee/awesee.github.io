---
layout:     single
title:      "亲密字符串"
date:       2018-05-09 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, String]
permalink:  /problems/buddy-strings/
---

## 859. 亲密字符串 (Easy)

{% raw %}

<p>给定两个由小写字母构成的字符串 <code>A</code> 和 <code>B</code> ，只要我们可以通过交换 <code>A</code> 中的两个字母得到与 <code>B</code> 相等的结果，就返回 <code>true</code> ；否则返回 <code>false</code> 。</p>

<p>交换字母的定义是取两个下标 <code>i</code> 和 <code>j</code> （下标从 <code>0</code> 开始），只要 <code>i!=j</code> 就交换 <code>A[i]</code> 和 <code>A[j]</code> 处的字符。例如，在 <code>"abcd"</code> 中交换下标 <code>0</code> 和下标 <code>2</code> 的元素可以生成 <code>"cbad"</code> 。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入： </strong>A = "ab", B = "ba"
<strong>输出： </strong>true<strong>
解释： </strong>你可以交换 A[0] = 'a' 和 A[1] = 'b' 生成 "ba"，此时 A 和 B 相等。</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入： </strong>A = "ab", B = "ab"
<strong>输出： </strong>false
<strong>解释： </strong>你只能交换 A[0] = 'a' 和 A[1] = 'b' 生成 "ba"，此时 A 和 B 不相等。
</pre>

<p><strong>示例 3:</strong></p>

<pre>
<strong>输入： </strong>A = "aa", B = "aa"
<strong>输出： </strong>true
<strong>解释： </strong>你可以交换 A[0] = 'a' 和 A[1] = 'a' 生成 "aa"，此时 A 和 B 相等。</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入： </strong>A = "aaaaaaabc", B = "aaaaaaacb"
<strong>输出： </strong>true
</pre>

<p><strong>示例 5：</strong></p>

<pre>
<strong>输入： </strong>A = "", B = "aa"
<strong>输出： </strong>false
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>0 <= A.length <= 20000</code></li>
	<li><code>0 <= B.length <= 20000</code></li>
	<li><code>A</code> 和 <code>B</code> 仅由小写字母构成。</li>
</ol>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/buddy-strings)
