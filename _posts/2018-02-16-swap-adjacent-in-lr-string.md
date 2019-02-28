---
layout:     single
title:      "在LR字符串中交换相邻字符"
date:       2018-02-16 21:30:00 +0800
categories: [leetcode]
tags:       [brainteaser]
permalink:  /swap-adjacent-in-lr-string/
---

## 777. 在LR字符串中交换相邻字符 (Medium)

<p>在一个由 <code>&#39;L&#39;</code> , <code>&#39;R&#39;</code> 和 <code>&#39;X&#39;</code> 三个字符组成的字符串（例如<code>&quot;RXXLRXRXL&quot;</code>）中进行移动操作。一次移动操作指用一个<code>&quot;LX&quot;</code>替换一个<code>&quot;XL&quot;</code>，或者用一个<code>&quot;XR&quot;</code>替换一个<code>&quot;RX&quot;</code>。现给定起始字符串<code>start</code>和结束字符串<code>end</code>，请编写代码，当且仅当存在一系列移动操作使得<code>start</code>可以转换成<code>end</code>时， 返回<code>True</code>。</p>

<p><strong>示例 :</strong></p>

<pre>
<strong>输入:</strong> start = &quot;RXXLRXRXL&quot;, end = &quot;XRLXXRRLX&quot;
<strong>输出:</strong> True
<strong>解释:</strong>
我们可以通过以下几步将start转换成end:
RXXLRXRXL -&gt;
XRXLRXRXL -&gt;
XRLXRXRXL -&gt;
XRLXXRRXL -&gt;
XRLXXRRLX
</pre>

<p><strong>注意:</strong></p>

<ol>
	<li><code>1 &lt;= len(start) = len(end) &lt;= 10000</code>。</li>
	<li><code>start</code>和<code>end</code>中的字符串仅限于<code>&#39;L&#39;</code>, <code>&#39;R&#39;</code>和<code>&#39;X&#39;</code>。</li>
</ol>

### 相关话题
  [[脑筋急转弯](https://github.com/openset/leetcode/tree/master/tag/brainteaser/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/swap-adjacent-in-lr-string)
