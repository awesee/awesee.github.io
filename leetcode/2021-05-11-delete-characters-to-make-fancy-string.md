---
layout:     single
title:      "删除字符使字符串变好"
date:       2021-05-11 21:30:00 +0800
categories: [Leetcode]
tags:       [String]
permalink:  /problems/delete-characters-to-make-fancy-string/
---

## 1957. 删除字符使字符串变好 (Easy)

{% raw %}

<p>一个字符串如果没有 <strong>三个连续</strong>&nbsp;相同字符，那么它就是一个 <strong>好字符串</strong>&nbsp;。</p>

<p>给你一个字符串&nbsp;<code>s</code>&nbsp;，请你从 <code>s</code>&nbsp;删除&nbsp;<strong>最少</strong>&nbsp;的字符，使它变成一个 <strong>好字符串</strong> 。</p>

<p>请你返回删除后的字符串。题目数据保证答案总是 <strong>唯一的 </strong>。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<b>输入：</b>s = "le<strong>e</strong>etcode"
<b>输出：</b>"leetcode"
<strong>解释：</strong>
从第一组 'e' 里面删除一个 'e' ，得到 "leetcode" 。
没有连续三个相同字符，所以返回 "leetcode" 。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<b>输入：</b>s = "<strong>a</strong>aab<strong>aa</strong>aa"
<b>输出：</b>"aabaa"
<strong>解释：</strong>
从第一组 'a' 里面删除一个 'a' ，得到 "aabaaaa" 。
从第二组 'a' 里面删除两个 'a' ，得到 "aabaa" 。
没有连续三个相同字符，所以返回 "aabaa" 。
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<b>输入：</b>s = "aab"
<b>输出：</b>"aab"
<b>解释：</b>没有连续三个相同字符，所以返回 "aab" 。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= s.length &lt;= 10<sup>5</sup></code></li>
	<li><code>s</code>&nbsp;只包含小写英文字母。</li>
</ul>

{% endraw %}

### 相关话题
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/delete-characters-to-make-fancy-string)
