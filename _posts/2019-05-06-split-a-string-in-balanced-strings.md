---
layout:     single
title:      "分割平衡字符串"
date:       2019-05-06 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, String]
permalink:  /problems/split-a-string-in-balanced-strings/
---

## 1221. 分割平衡字符串 (Easy)

{% raw %}

<p>在一个「平衡字符串」中，&#39;L&#39; 和 &#39;R&#39; 字符的数量是相同的。</p>

<p>给出一个平衡字符串&nbsp;<code>s</code>，请你将它分割成尽可能多的平衡字符串。</p>

<p>返回可以通过分割得到的平衡字符串的最大数量<strong>。</strong></p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>s = &quot;RLRRLLRLRL&quot;
<strong>输出：</strong>4
<strong>解释：</strong>s 可以分割为 &quot;RL&quot;, &quot;RRLL&quot;, &quot;RL&quot;, &quot;RL&quot;, 每个子字符串中都包含相同数量的 &#39;L&#39; 和 &#39;R&#39;。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>s = &quot;RLLLLRRRLR&quot;
<strong>输出：</strong>3
<strong>解释：</strong>s 可以分割为 &quot;RL&quot;, &quot;LLLRRR&quot;, &quot;LR&quot;, 每个子字符串中都包含相同数量的 &#39;L&#39; 和 &#39;R&#39;。
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>s = &quot;LLLLRRRR&quot;
<strong>输出：</strong>1
<strong>解释：</strong>s 只能保持原样 &quot;LLLLRRRR&quot;.
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= s.length &lt;= 1000</code></li>
	<li><code>s[i] = &#39;L&#39; 或 &#39;R&#39;</code></li>
	<li>分割得到的每个字符串都必须是平衡字符串。</li>
</ul>

{% endraw %}

### 相关话题
  [[贪心算法](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/split-a-string-in-balanced-strings)
