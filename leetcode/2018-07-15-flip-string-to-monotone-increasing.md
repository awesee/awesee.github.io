---
layout:     single
title:      "将字符串翻转到单调递增"
date:       2018-07-15 21:30:00 +0800
categories: [Leetcode]
tags:       [String, Dynamic Programming]
permalink:  /problems/flip-string-to-monotone-increasing/
---

## 926. 将字符串翻转到单调递增 (Medium)

{% raw %}

<p>如果一个由 <code>'0'</code> 和 <code>'1'</code> 组成的字符串，是以一些 <code>'0'</code>（可能没有 <code>'0'</code>）后面跟着一些 <code>'1'</code>（也可能没有 <code>'1'</code>）的形式组成的，那么该字符串是<em>单调递增</em>的。</p>

<p>我们给出一个由字符 <code>'0'</code> 和 <code>'1'</code> 组成的字符串 <code>S</code>，我们可以将任何 <code>'0'</code> 翻转为 <code>'1'</code> 或者将 <code>'1'</code> 翻转为 <code>'0'</code>。</p>

<p>返回使 <code>S</code> 单调递增的最小翻转次数。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>"00110"
<strong>输出：</strong>1
<strong>解释：</strong>我们翻转最后一位得到 00111.
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>"010110"
<strong>输出：</strong>2
<strong>解释：</strong>我们翻转得到 011111，或者是 000111。
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>"00011000"
<strong>输出：</strong>2
<strong>解释：</strong>我们翻转得到 00000000。
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= S.length <= 20000</code></li>
	<li><code>S</code> 中只包含字符 <code>'0'</code> 和 <code>'1'</code></li>
</ul>

{% endraw %}

### 相关话题
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/flip-string-to-monotone-increasing)
