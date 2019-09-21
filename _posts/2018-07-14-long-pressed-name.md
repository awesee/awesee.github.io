---
layout:     single
title:      "长按键入"
date:       2018-07-14 21:30:00 +0800
categories: [Leetcode]
tags:       [Two Pointers, String]
permalink:  /problems/long-pressed-name/
---

## 925. 长按键入 (Easy)

{% raw %}

<p>你的朋友正在使用键盘输入他的名字&nbsp;<code>name</code>。偶尔，在键入字符&nbsp;<code>c</code>&nbsp;时，按键可能会被<em>长按</em>，而字符可能被输入 1 次或多次。</p>

<p>你将会检查键盘输入的字符&nbsp;<code>typed</code>。如果它对应的可能是你的朋友的名字（其中一些字符可能被长按），那么就返回&nbsp;<code>True</code>。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>name = &quot;alex&quot;, typed = &quot;aaleex&quot;
<strong>输出：</strong>true
<strong>解释：</strong>&#39;alex&#39; 中的 &#39;a&#39; 和 &#39;e&#39; 被长按。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>name = &quot;saeed&quot;, typed = &quot;ssaaedd&quot;
<strong>输出：</strong>false
<strong>解释：</strong>&#39;e&#39; 一定需要被键入两次，但在 typed 的输出中不是这样。
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>name = &quot;leelee&quot;, typed = &quot;lleeelee&quot;
<strong>输出：</strong>true
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>name = &quot;laiden&quot;, typed = &quot;laiden&quot;
<strong>输出：</strong>true
<strong>解释：</strong>长按名字中的字符并不是必要的。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>name.length &lt;= 1000</code></li>
	<li><code>typed.length &lt;= 1000</code></li>
	<li><code>name</code> 和&nbsp;<code>typed</code>&nbsp;的字符都是小写字母。</li>
</ol>

<p>&nbsp;</p>

<p>&nbsp;</p>

{% endraw %}

### 相关话题
  [[双指针](https://github.com/openset/leetcode/tree/master/tag/two-pointers/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/long-pressed-name)
