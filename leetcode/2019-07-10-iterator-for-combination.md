---
layout:     single
title:      "字母组合迭代器"
date:       2019-07-10 21:30:00 +0800
categories: [Leetcode]
tags:       [Design, String, Backtracking, Iterator]
permalink:  /problems/iterator-for-combination/
---

## 1286. 字母组合迭代器 (Medium)

{% raw %}

<p>请你设计一个迭代器类，包括以下内容：</p>

<ul>
	<li>一个构造函数，输入参数包括：一个&nbsp;<strong>有序且字符唯一&nbsp;</strong>的字符串&nbsp;<code>characters</code>（该字符串只包含小写英文字母）和一个数字&nbsp;<code>combinationLength</code>&nbsp;。</li>
	<li>函数&nbsp;<em>next()&nbsp;</em>，按&nbsp;<strong>字典序&nbsp;</strong>返回长度为&nbsp;<code>combinationLength</code> 的下一个字母组合。</li>
	<li>函数&nbsp;<em>hasNext()&nbsp;</em>，只有存在长度为&nbsp;<code>combinationLength</code> 的下一个字母组合时，才返回&nbsp;<code>True</code>；否则，返回 <code>False</code>。</li>
</ul>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre>CombinationIterator iterator = new CombinationIterator(&quot;abc&quot;, 2); // 创建迭代器 iterator

iterator.next(); // 返回 &quot;ab&quot;
iterator.hasNext(); // 返回 true
iterator.next(); // 返回 &quot;ac&quot;
iterator.hasNext(); // 返回 true
iterator.next(); // 返回 &quot;bc&quot;
iterator.hasNext(); // 返回 false
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= combinationLength &lt;=&nbsp;characters.length &lt;= 15</code></li>
	<li>每组测试数据最多包含&nbsp;<code>10^4</code>&nbsp;次函数调用。</li>
	<li>题目保证每次调用函数&nbsp;<code>next</code>&nbsp;时都存在下一个字母组合。</li>
</ul>

{% endraw %}

### 相关话题
  [[设计](https://github.com/awesee/leetcode/tree/main/tag/design/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[回溯](https://github.com/awesee/leetcode/tree/main/tag/backtracking/README.md)]
  [[迭代器](https://github.com/awesee/leetcode/tree/main/tag/iterator/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/iterator-for-combination)
