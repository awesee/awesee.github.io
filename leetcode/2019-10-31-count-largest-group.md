---
layout:     single
title:      "统计最大组的数目"
date:       2019-10-31 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, Math]
permalink:  /problems/count-largest-group/
---

## 1399. 统计最大组的数目 (Easy)

{% raw %}

<p>给你一个整数 <code>n</code>&nbsp;。请你先求出从 <code>1</code>&nbsp;到 <code>n</code> 的每个整数 10 进制表示下的数位和（每一位上的数字相加），然后把数位和相等的数字放到同一个组中。</p>

<p>请你统计每个组中的数字数目，并返回数字数目并列最多的组有多少个。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>n = 13
<strong>输出：</strong>4
<strong>解释：</strong>总共有 9 个组，将 1 到 13 按数位求和后这些组分别是：
[1,10]，[2,11]，[3,12]，[4,13]，[5]，[6]，[7]，[8]，[9]。总共有 4 个组拥有的数字并列最多。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>n = 2
<strong>输出：</strong>2
<strong>解释：</strong>总共有 2 个大小为 1 的组 [1]，[2]。
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>n = 15
<strong>输出：</strong>6
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>n = 24
<strong>输出：</strong>5
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= n &lt;= 10^4</code></li>
</ul>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/count-largest-group)
