---
layout:     single
title:      "判断路径是否相交"
date:       2020-02-05 21:30:00 +0800
categories: [Leetcode]
tags:       [String]
permalink:  /problems/path-crossing/
---

## 1496. 判断路径是否相交 (Easy)

{% raw %}

<p>给你一个字符串 <code>path</code>，其中 <code>path[i]</code> 的值可以是 <code>&#39;N&#39;</code>、<code>&#39;S&#39;</code>、<code>&#39;E&#39;</code> 或者 <code>&#39;W&#39;</code>，分别表示向北、向南、向东、向西移动一个单位。</p>

<p>机器人从二维平面上的原点 <code>(0, 0)</code> 处开始出发，按 <code>path</code> 所指示的路径行走。</p>

<p>如果路径在任何位置上出现相交的情况，也就是走到之前已经走过的位置，请返回 <code>True</code> ；否则，返回 <code>False</code> 。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<p><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/06/28/screen-shot-2020-06-10-at-123929-pm.png" style="height: 224px; width: 250px;"></p>

<pre><strong>输入：</strong>path = &quot;NES&quot;
<strong>输出：</strong>false 
<strong>解释：</strong>该路径没有在任何位置相交。</pre>

<p><strong>示例 2：</strong></p>

<p><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/06/28/screen-shot-2020-06-10-at-123843-pm.png" style="height: 212px; width: 250px;"></p>

<pre><strong>输入：</strong>path = &quot;NESWW&quot;
<strong>输出：</strong>true
<strong>解释：</strong>该路径经过原点两次。</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= path.length &lt;= 10^4</code></li>
	<li><code>path</code> 仅由 <code>{&#39;N&#39;, &#39;S&#39;, &#39;E&#39;, &#39;W}</code> 中的字符组成</li>
</ul>

{% endraw %}

### 相关话题
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/path-crossing)
