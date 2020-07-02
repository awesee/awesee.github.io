---
layout:     single
title:      "迷你语法分析器"
date:       2017-01-20 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, String]
permalink:  /problems/mini-parser/
---

## 385. 迷你语法分析器 (Medium)

{% raw %}

<p>给定一个用字符串表示的整数的嵌套列表，实现一个解析它的语法分析器。</p>

<p>列表中的每个元素只可能是整数或整数嵌套列表</p>

<p><strong>提示：</strong>你可以假定这些字符串都是格式良好的：</p>

<ul>
	<li>字符串非空</li>
	<li>字符串不包含空格</li>
	<li>字符串只包含数字<code>0-9</code>、<code>[</code>、<code>-</code>、<code>,</code>、<code>]</code></li>
</ul>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>给定 s = &quot;324&quot;,

你应该返回一个 NestedInteger 对象，其中只包含整数值 324。
</pre>

<p><strong>示例 2：</strong></p>

<pre>给定 s = &quot;[123,[456,[789]]]&quot;,

返回一个 NestedInteger 对象包含一个有两个元素的嵌套列表：

1. 一个 integer 包含值 123
2. 一个包含两个元素的嵌套列表：
    i.  一个 integer 包含值 456
    ii. 一个包含一个元素的嵌套列表
         a. 一个 integer 包含值 789
</pre>

{% endraw %}

### 相关话题
  [[栈](https://github.com/openset/leetcode/tree/master/tag/stack/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### 相似题目
  1. [扁平化嵌套列表迭代器](/problems/flatten-nested-list-iterator) (Medium)
  1. [三元表达式解析器](/problems/ternary-expression-parser) (Medium)
  1. [删除注释](/problems/remove-comments) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/mini-parser)
