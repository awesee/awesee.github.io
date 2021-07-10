---
layout:     single
title:      "电话号码的字母组合"
date:       2016-01-18 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, String, Backtracking]
permalink:  /problems/letter-combinations-of-a-phone-number/
---

## 17. 电话号码的字母组合 (Medium)

{% raw %}

<p>给定一个仅包含数字 <code>2-9</code> 的字符串，返回所有它能表示的字母组合。答案可以按 <strong>任意顺序</strong> 返回。</p>

<p>给出数字到字母的映射如下（与电话按键相同）。注意 1 不对应任何字母。</p>

<p><img src="https://assets.leetcode-cn.com/aliyun-lc-upload/original_images/17_telephone_keypad.png" style="width: 200px;" /></p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>digits = "23"
<strong>输出：</strong>["ad","ae","af","bd","be","bf","cd","ce","cf"]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>digits = ""
<strong>输出：</strong>[]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>digits = "2"
<strong>输出：</strong>["a","b","c"]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>0 <= digits.length <= 4</code></li>
	<li><code>digits[i]</code> 是范围 <code>['2', '9']</code> 的一个数字。</li>
</ul>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[回溯](https://github.com/openset/leetcode/tree/master/tag/backtracking/README.md)]

### 相似题目
  1. [括号生成](/problems/generate-parentheses) (Medium)
  1. [组合总和](/problems/combination-sum) (Medium)
  1. [二进制手表](/problems/binary-watch) (Easy)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/letter-combinations-of-a-phone-number)
