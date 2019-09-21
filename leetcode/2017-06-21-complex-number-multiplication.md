---
layout:     single
title:      "复数乘法"
date:       2017-06-21 21:30:00 +0800
categories: [Leetcode]
tags:       [Math, String]
permalink:  /problems/complex-number-multiplication/
---

## 537. 复数乘法 (Medium)

{% raw %}

<p>给定两个表示<a href="https://baike.baidu.com/item/%E5%A4%8D%E6%95%B0/254365?fr=aladdin">复数</a>的字符串。</p>

<p>返回表示它们乘积的字符串。注意，根据定义 i<sup>2</sup> = -1 。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> &quot;1+1i&quot;, &quot;1+1i&quot;
<strong>输出:</strong> &quot;0+2i&quot;
<strong>解释:</strong> (1 + i) * (1 + i) = 1 + i<sup>2</sup> + 2 * i = 2i ，你需要将它转换为 0+2i 的形式。
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> &quot;1+-1i&quot;, &quot;1+-1i&quot;
<strong>输出:</strong> &quot;0+-2i&quot;
<strong>解释:</strong> (1 - i) * (1 - i) = 1 + i<sup>2</sup> - 2 * i = -2i ，你需要将它转换为 0+-2i 的形式。 
</pre>

<p><strong>注意:</strong></p>

<ol>
	<li>输入字符串不包含额外的空格。</li>
	<li>输入字符串将以&nbsp;<strong>a+bi</strong> 的形式给出，其中整数 <strong>a</strong> 和 <strong>b</strong> 的范围均在 [-100, 100] 之间。<strong>输出也应当符合这种形式</strong>。</li>
</ol>

{% endraw %}

### 相关话题
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/complex-number-multiplication)
