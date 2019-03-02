---
layout:     single
title:      "二进制手表"
date:       2017-02-05 21:30:00 +0800
categories: [leetcode]
tags:       [bit-manipulation, backtracking]
permalink:  /binary-watch/
---

## 401. 二进制手表 (Easy)

<p>二进制手表顶部有 4 个 LED 代表<strong>小时（0-11）</strong>，底部的 6 个 LED 代表<strong>分钟（0-59）</strong>。</p>

<p>每个 LED 代表一个 0 或 1，最低位在右侧。</p>

<p><img src="https://upload.wikimedia.org/wikipedia/commons/8/8b/Binary_clock_samui_moon.jpg" style="height:300px" /></p>

<p>例如，上面的二进制手表读取 &ldquo;3:25&rdquo;。</p>

<p>给定一个非负整数 <em>n&nbsp;</em>代表当前 LED 亮着的数量，返回所有可能的时间。</p>

<p><strong>案例:</strong></p>

<pre>
输入: n = 1
返回: [&quot;1:00&quot;, &quot;2:00&quot;, &quot;4:00&quot;, &quot;8:00&quot;, &quot;0:01&quot;, &quot;0:02&quot;, &quot;0:04&quot;, &quot;0:08&quot;, &quot;0:16&quot;, &quot;0:32&quot;]</pre>

<p>&nbsp;</p>

<p><strong>注意事项:</strong></p>

<ul>
	<li>输出的顺序没有要求。</li>
	<li>小时不会以零开头，比如 &ldquo;01:00&rdquo;&nbsp;是不允许的，应为 &ldquo;1:00&rdquo;。</li>
	<li>分钟必须由两位数组成，可能会以零开头，比如 &ldquo;10:2&rdquo;&nbsp;是无效的，应为 &ldquo;10:02&rdquo;。</li>
</ul>

### 相关话题
  [[位运算](https://github.com/openset/leetcode/tree/master/tag/bit-manipulation/README.md)]
  [[回溯算法](https://github.com/openset/leetcode/tree/master/tag/backtracking/README.md)]

### 相似题目
  1. [电话号码的字母组合](/letter-combinations-of-a-phone-number) (Medium)
  1. [位1的个数](/number-of-1-bits) (Easy)

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/binary-watch)
