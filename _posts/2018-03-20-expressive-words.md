---
layout:     single
title:      "809. 情感丰富的文字 (Medium)"
date:       2018-03-20 21:30:00 +0800
categories: [leetcode]
tags:       [string]
permalink:  /expressive-words/
---

<p>有时候人们会用额外的字母来表示额外的情感，比如 &quot;hello&quot; -&gt; &quot;heeellooo&quot;, &quot;hi&quot; -&gt; &quot;hiii&quot;。我们将连续的相同的字母分组，并且相邻组的字母都不相同。我们将一个拥有三个或以上字母的组定义为扩张状态（extended），如第一个例子中的 &quot;e&quot; 和&quot; o&quot; 以及第二个例子中的 &quot;i&quot;。 此外，&quot;abbcccaaaa&quot; 将有分组&nbsp;&quot;a&quot; , &quot;bb&quot; , &quot;ccc&quot; , &quot;dddd&quot;；其中 &quot;ccc&quot; 和 &quot;aaaa&quot; 处于扩张状态。</p>

<p>对于一个给定的字符串 S ，如果另一个单词能够通过将一些字母组扩张从而使其和 S 相同，我们将这个单词定义为可扩张的（stretchy）。我们允许选择一个字母组（如包含字母&nbsp;<code>c</code>&nbsp;），然后往其中添加相同的字母&nbsp;<code>c</code>&nbsp;使其长度达到 3 或以上。注意，我们不能将一个只包含一个字母的字母组，如 &quot;h&quot;，扩张到一个包含两个字母的组，如 &quot;hh&quot;；所有的扩张必须使该字母组变成扩张状态（至少包含三个字母）。</p>

<p>输入一组单词，输出其中可扩张的单词数量。</p>

<pre>
<strong>示例：</strong>
<strong>输入：</strong> 
S = &quot;heeellooo&quot;
words = [&quot;hello&quot;, &quot;hi&quot;, &quot;helo&quot;]
<strong>输出：</strong>1
<strong>解释</strong>：
我们能通过扩张&quot;hello&quot;的&quot;e&quot;和&quot;o&quot;来得到&quot;heeellooo&quot;。
我们不能通过扩张&quot;helo&quot;来得到&quot;heeellooo&quot;因为&quot;ll&quot;不处于扩张状态。
</pre>

<p><strong>说明：</strong></p>

<ul>
	<li><code>0 &lt;= len(S) &lt;= 100</code>。</li>
	<li><code>0 &lt;= len(words) &lt;= 100</code>。</li>
	<li><code>0 &lt;= len(words[i]) &lt;= 100</code>。</li>
	<li><code>S</code>&nbsp;和所有在&nbsp;<code>words</code>&nbsp;中的单词都只由小写字母组成。</li>
</ul>

### 相关话题
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/expressive-words)
