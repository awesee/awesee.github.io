---
layout:     single
title:      "查找和替换模式"
date:       2018-06-09 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, String]
permalink:  /problems/find-and-replace-pattern/
---

## 890. 查找和替换模式 (Medium)

{% raw %}

<p>你有一个单词列表&nbsp;<code>words</code>&nbsp;和一个模式&nbsp;&nbsp;<code>pattern</code>，你想知道 <code>words</code> 中的哪些单词与模式匹配。</p>

<p>如果存在字母的排列 <code>p</code>&nbsp;，使得将模式中的每个字母 <code>x</code> 替换为 <code>p(x)</code> 之后，我们就得到了所需的单词，那么单词与模式是匹配的。</p>

<p><em>（回想一下，字母的排列是从字母到字母的双射：每个字母映射到另一个字母，没有两个字母映射到同一个字母。）</em></p>

<p>返回 <code>words</code> 中与给定模式匹配的单词列表。</p>

<p>你可以按任何顺序返回答案。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>words = [&quot;abc&quot;,&quot;deq&quot;,&quot;mee&quot;,&quot;aqq&quot;,&quot;dkd&quot;,&quot;ccc&quot;], pattern = &quot;abb&quot;
<strong>输出：</strong>[&quot;mee&quot;,&quot;aqq&quot;]
<strong>解释：
</strong>&quot;mee&quot; 与模式匹配，因为存在排列 {a -&gt; m, b -&gt; e, ...}。
&quot;ccc&quot; 与模式不匹配，因为 {a -&gt; c, b -&gt; c, ...} 不是排列。
因为 a 和 b 映射到同一个字母。</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= words.length &lt;= 50</code></li>
	<li><code>1 &lt;= pattern.length = words[i].length&nbsp;&lt;= 20</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/find-and-replace-pattern)
