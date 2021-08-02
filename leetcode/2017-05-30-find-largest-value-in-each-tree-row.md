---
layout:     single
title:      "在每个树行中找最大值"
date:       2017-05-30 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Breadth-First Search, Binary Tree]
permalink:  /problems/find-largest-value-in-each-tree-row/
---

## 515. 在每个树行中找最大值 (Medium)

{% raw %}

<p>给定一棵二叉树的根节点 <code>root</code> ，请找出该二叉树中每一层的最大值。</p>

<p> </p>

<p><strong>示例1：</strong></p>

<pre>
<strong>输入: </strong>root = [1,3,2,5,3,null,9]
<strong>输出: </strong>[1,3,9]
<strong>解释:</strong>
          1
         / \
        3   2
       / \   \  
      5   3   9 
</pre>

<p><strong>示例2：</strong></p>

<pre>
<strong>输入: </strong>root = [1,2,3]
<strong>输出: </strong>[1,3]
<strong>解释:</strong>
          1
         / \
        2   3
</pre>

<p><strong>示例3：</strong></p>

<pre>
<strong>输入: </strong>root = [1]
<strong>输出: </strong>[1]
</pre>

<p><strong>示例4：</strong></p>

<pre>
<strong>输入: </strong>root = [1,null,2]
<strong>输出: </strong>[1,2]
<strong>解释:</strong>      
           1 
            \
             2     
</pre>

<p><strong>示例5：</strong></p>

<pre>
<strong>输入: </strong>root = []
<strong>输出: </strong>[]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li>二叉树的节点个数的范围是 <code>[0,10<sup>4</sup>]</code></li>
	<li><meta charset="UTF-8" /><code>-2<sup>31</sup> <= Node.val <= 2<sup>31</sup> - 1</code></li>
</ul>

{% endraw %}

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/openset/leetcode/tree/master/tag/breadth-first-search/README.md)]
  [[二叉树](https://github.com/openset/leetcode/tree/master/tag/binary-tree/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/find-largest-value-in-each-tree-row)
