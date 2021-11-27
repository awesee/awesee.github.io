---
layout:     single
title:      "找不同"
date:       2017-01-24 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, Hash Table, String, Sorting]
permalink:  /problems/find-the-difference/
---

## 389. 找不同 (Easy)

{% raw %}

<p>给定两个字符串 <em><strong>s</strong></em> 和 <em><strong>t</strong></em>，它们只包含小写字母。</p>

<p>字符串&nbsp;<strong><em>t</em></strong>&nbsp;由字符串&nbsp;<strong><em>s</em></strong>&nbsp;随机重排，然后在随机位置添加一个字母。</p>

<p>请找出在 <em><strong>t</strong></em> 中被添加的字母。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>s = &quot;abcd&quot;, t = &quot;abcde&quot;
<strong>输出：</strong>&quot;e&quot;
<strong>解释：</strong>&#39;e&#39; 是那个被添加的字母。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>s = &quot;&quot;, t = &quot;y&quot;
<strong>输出：</strong>&quot;y&quot;
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>s = &quot;a&quot;, t = &quot;aa&quot;
<strong>输出：</strong>&quot;a&quot;
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>s = &quot;ae&quot;, t = &quot;aea&quot;
<strong>输出：</strong>&quot;a&quot;
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 &lt;= s.length &lt;= 1000</code></li>
	<li><code>t.length == s.length + 1</code></li>
	<li><code>s</code> 和 <code>t</code> 只包含小写字母</li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]

### 相似题目
  1. [只出现一次的数字](/problems/single-number) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/find-the-difference)
