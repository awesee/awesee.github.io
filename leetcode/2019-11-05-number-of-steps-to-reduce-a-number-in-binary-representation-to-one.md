---
layout:     single
title:      "将二进制表示减到 1 的步骤数"
date:       2019-11-05 21:30:00 +0800
categories: [Leetcode]
tags:       [Bit Manipulation, String]
permalink:  /problems/number-of-steps-to-reduce-a-number-in-binary-representation-to-one/
---

## 1404. 将二进制表示减到 1 的步骤数 (Medium)

{% raw %}

<p>给你一个以二进制形式表示的数字 <code>s</code> 。请你返回按下述规则将其减少到 1 所需要的步骤数：</p>

<ul>
	<li>
	<p>如果当前数字为偶数，则将其除以 2 。</p>
	</li>
	<li>
	<p>如果当前数字为奇数，则将其加上 1 。</p>
	</li>
</ul>

<p>题目保证你总是可以按上述规则将测试用例变为 1 。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>s = &quot;1101&quot;
<strong>输出：</strong>6
<strong>解释：</strong>&quot;1101&quot; 表示十进制数 13 。
Step 1) 13 是奇数，加 1 得到 14&nbsp;
Step 2) 14 是偶数，除 2 得到 7
Step 3) 7  是奇数，加 1 得到 8
Step 4) 8  是偶数，除 2 得到 4&nbsp; 
Step 5) 4  是偶数，除 2 得到 2&nbsp;
Step 6) 2  是偶数，除 2 得到 1&nbsp; 
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>s = &quot;10&quot;
<strong>输出：</strong>1
<strong>解释：</strong>&quot;10&quot; 表示十进制数 2 。
Step 1) 2 是偶数，除 2 得到 1 
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>s = &quot;1&quot;
<strong>输出：</strong>0
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= s.length&nbsp;&lt;= 500</code></li>
	<li><code>s</code> 由字符 <code>&#39;0&#39;</code> 或 <code>&#39;1&#39;</code> 组成。</li>
	<li><code>s[0] == &#39;1&#39;</code></li>
</ul>

{% endraw %}

### 相关话题
  [[位运算](https://github.com/awesee/leetcode/tree/main/tag/bit-manipulation/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/number-of-steps-to-reduce-a-number-in-binary-representation-to-one)
