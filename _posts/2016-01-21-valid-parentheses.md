---
layout:     single
title:      "有效的括号"
date:       2016-01-21 21:30:00 +0800
categories: [Leetcode]
tags:       [Stack, String]
permalink:  /problems/valid-parentheses/
---

## 20. 有效的括号 (Easy)

{% raw %}

<p>给定一个只包括 <code>'('</code>，<code>')'</code>，<code>'{'</code>，<code>'}'</code>，<code>'['</code>，<code>']'</code> 的字符串 <code>s</code> ，判断字符串是否有效。</p>

<p>有效字符串需满足：</p>

<ol>
	<li>左括号必须用相同类型的右括号闭合。</li>
	<li>左括号必须以正确的顺序闭合。</li>
</ol>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>s = "()"
<strong>输出：</strong>true
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>s = "()[]{}"
<strong>输出：</strong>true
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>s = "(]"
<strong>输出：</strong>false
</pre>

<p><strong>示例 4：</strong></p>

<pre>
<strong>输入：</strong>s = "([)]"
<strong>输出：</strong>false
</pre>

<p><strong>示例 5：</strong></p>

<pre>
<strong>输入：</strong>s = "{[]}"
<strong>输出：</strong>true</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= s.length <= 10<sup>4</sup></code></li>
	<li><code>s</code> 仅由括号 <code>'()[]{}'</code> 组成</li>
</ul>

{% endraw %}

### 相关话题
  [[栈](https://github.com/awesee/leetcode/tree/main/tag/stack/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

### 相似题目
  1. [括号生成](/problems/generate-parentheses) (Medium)
  1. [最长有效括号](/problems/longest-valid-parentheses) (Hard)
  1. [删除无效的括号](/problems/remove-invalid-parentheses) (Hard)
  1. [检查替换后的词是否有效](/problems/check-if-word-is-valid-after-substitutions) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/valid-parentheses)
