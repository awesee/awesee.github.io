---
layout:     single
title:      "单词搜索 II"
date:       2016-07-31 21:30:00 +0800
categories: [Leetcode]
tags:       [Trie, Array, String, Backtracking, Matrix]
permalink:  /problems/word-search-ii/
---

## 212. 单词搜索 II (Hard)

{% raw %}

<p>给定一个 <code>m x n</code> 二维字符网格 <code>board</code><strong> </strong>和一个单词（字符串）列表 <code>words</code>，找出所有同时在二维网格和字典中出现的单词。</p>

<p>单词必须按照字母顺序，通过 <strong>相邻的单元格</strong> 内的字母构成，其中“相邻”单元格是那些水平相邻或垂直相邻的单元格。同一个单元格内的字母在一个单词中不允许被重复使用。</p>

<p> </p>

<p><strong>示例 1：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/11/07/search1.jpg" style="width: 322px; height: 322px;" />
<pre>
<strong>输入：</strong>board = [["o","a","a","n"],["e","t","a","e"],["i","h","k","r"],["i","f","l","v"]], words = ["oath","pea","eat","rain"]
<strong>输出：</strong>["eat","oath"]
</pre>

<p><strong>示例 2：</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2020/11/07/search2.jpg" style="width: 162px; height: 162px;" />
<pre>
<strong>输入：</strong>board = [["a","b"],["c","d"]], words = ["abcb"]
<strong>输出：</strong>[]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>m == board.length</code></li>
	<li><code>n == board[i].length</code></li>
	<li><code>1 <= m, n <= 12</code></li>
	<li><code>board[i][j]</code> 是一个小写英文字母</li>
	<li><code>1 <= words.length <= 3 * 10<sup>4</sup></code></li>
	<li><code>1 <= words[i].length <= 10</code></li>
	<li><code>words[i]</code> 由小写英文字母组成</li>
	<li><code>words</code> 中的所有字符串互不相同</li>
</ul>

{% endraw %}

### 相关话题
  [[字典树](https://github.com/openset/leetcode/tree/master/tag/trie/README.md)]
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[字符串](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[回溯](https://github.com/openset/leetcode/tree/master/tag/backtracking/README.md)]
  [[矩阵](https://github.com/openset/leetcode/tree/master/tag/matrix/README.md)]

### 相似题目
  1. [单词搜索](/problems/word-search) (Medium)
  1. [不同路径 III](/problems/unique-paths-iii) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/word-search-ii)
