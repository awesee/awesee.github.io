---
layout:     single
title:      "灯泡开关 III"
date:       2019-10-07 21:30:00 +0800
categories: [Leetcode]
tags:       [Array]
permalink:  /problems/bulb-switcher-iii/
---

## 1375. 灯泡开关 III (Medium)

{% raw %}

<p>房间中有 <code>n</code> 枚灯泡，编号从 <code>1</code> 到 <code>n</code>，自左向右排成一排。最初，所有的灯都是关着的。</p>

<p>在 <em>k</em>&nbsp; 时刻（ <em>k</em> 的取值范围是 <code>0</code> 到 <code>n - 1</code>），我们打开 <code>light[k]</code> 这个灯。</p>

<p>灯的颜色要想 <strong>变成蓝色</strong> 就必须同时满足下面两个条件：</p>

<ul>
	<li>灯处于打开状态。</li>
	<li>排在它之前（左侧）的所有灯也都处于打开状态。</li>
</ul>

<p>请返回能够让 <strong>所有开着的</strong> 灯都 <strong>变成蓝色</strong> 的时刻 <strong>数目 。</strong></p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<p><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/03/08/sample_2_1725.png" style="height: 254px; width: 575px;"></p>

<pre><strong>输入：</strong>light = [2,1,3,5,4]
<strong>输出：</strong>3
<strong>解释：</strong>所有开着的灯都变蓝的时刻分别是 1，2 和 4 。
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>light = [3,2,4,1,5]
<strong>输出：</strong>2
<strong>解释：</strong>所有开着的灯都变蓝的时刻分别是 3 和 4（index-0）。
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>light = [4,1,2,3]
<strong>输出：</strong>1
<strong>解释：</strong>所有开着的灯都变蓝的时刻是 3（index-0）。
第 4 个灯在时刻 3 变蓝。
</pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：</strong>light = [2,1,4,3,6,5]
<strong>输出：</strong>3
</pre>

<p><strong>示例 5：</strong></p>

<pre><strong>输入：</strong>light = [1,2,3,4,5,6]
<strong>输出：</strong>6
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>n ==&nbsp;light.length</code></li>
	<li><code>1 &lt;= n &lt;= 5 * 10^4</code></li>
	<li><code>light</code> 是 <code>[1, 2, ..., n]</code> 的一个排列。</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/bulb-switcher-iii)
