---
layout:     single
title:      "打家劫舍 III"
date:       2016-12-03 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Dynamic Programming, Binary Tree]
permalink:  /problems/house-robber-iii/
---

## 337. 打家劫舍 III (Medium)

{% raw %}

<p>在上次打劫完一条街道之后和一圈房屋后，小偷又发现了一个新的可行窃的地区。这个地区只有一个入口，我们称之为&ldquo;根&rdquo;。 除了&ldquo;根&rdquo;之外，每栋房子有且只有一个&ldquo;父&ldquo;房子与之相连。一番侦察之后，聪明的小偷意识到&ldquo;这个地方的所有房屋的排列类似于一棵二叉树&rdquo;。 如果两个直接相连的房子在同一天晚上被打劫，房屋将自动报警。</p>

<p>计算在不触动警报的情况下，小偷一晚能够盗取的最高金额。</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入: </strong>[3,2,3,null,3,null,1]

     <strong>3</strong>
    / \
   2   3
    \   \ 
     <strong>3</strong>   <strong>1</strong>

<strong>输出:</strong> 7 
<strong>解释:</strong>&nbsp;小偷一晚能够盗取的最高金额 = 3 + 3 + 1 = <strong>7</strong>.</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入: </strong>[3,4,5,1,3,null,1]

&nbsp;    3
    / \
   <strong>4</strong>   <strong>5</strong>
  / \   \ 
 1   3   1

<strong>输出:</strong> 9
<strong>解释:</strong>&nbsp;小偷一晚能够盗取的最高金额&nbsp;= <strong>4</strong> + <strong>5</strong> = <strong>9</strong>.
</pre>

{% endraw %}

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]
  [[二叉树](https://github.com/openset/leetcode/tree/master/tag/binary-tree/README.md)]

### 相似题目
  1. [打家劫舍](/problems/house-robber) (Medium)
  1. [打家劫舍 II](/problems/house-robber-ii) (Medium)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/house-robber-iii)
