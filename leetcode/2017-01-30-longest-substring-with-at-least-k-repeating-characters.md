---
layout:     single
title:      "至少有 K 个重复字符的最长子串"
date:       2017-01-30 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, String, Divide and Conquer, Sliding Window]
permalink:  /problems/longest-substring-with-at-least-k-repeating-characters/
---

## 395. 至少有 K 个重复字符的最长子串 (Medium)

{% raw %}

<p>给你一个字符串 <code>s</code> 和一个整数 <code>k</code> ，请你找出 <code>s</code> 中的最长子串， 要求该子串中的每一字符出现次数都不少于 <code>k</code> 。返回这一子串的长度。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>s = "aaabb", k = 3
<strong>输出：</strong>3
<strong>解释：</strong>最长子串为 "aaa" ，其中 'a' 重复了 3 次。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>s = "ababbc", k = 2
<strong>输出：</strong>5
<strong>解释：</strong>最长子串为 "ababb" ，其中 'a' 重复了 2 次， 'b' 重复了 3 次。</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= s.length <= 10<sup>4</sup></code></li>
	<li><code>s</code> 仅由小写英文字母组成</li>
	<li><code>1 <= k <= 10<sup>5</sup></code></li>
</ul>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[分治](https://github.com/openset/leetcode/tree/master/tag/divide-and-conquer/README.md)]
  [[滑动窗口](https://github.com/openset/leetcode/tree/master/tag/sliding-window/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/longest-substring-with-at-least-k-repeating-characters)
