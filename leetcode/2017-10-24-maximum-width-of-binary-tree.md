---
layout:     single
title:      "二叉树最大宽度"
date:       2017-10-24 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, Breadth-First Search, Binary Tree]
permalink:  /problems/maximum-width-of-binary-tree/
---

## 662. 二叉树最大宽度 (Medium)

{% raw %}

<p>给定一个二叉树，编写一个函数来获取这个树的最大宽度。树的宽度是所有层中的最大宽度。这个二叉树与<strong>满二叉树（full binary tree）</strong>结构相同，但一些节点为空。</p>

<p>每一层的宽度被定义为两个端点（该层最左和最右的非空节点，两端点间的<code>null</code>节点也计入长度）之间的长度。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> 

           1
         /   \
        3     2
       / \     \  
      5   3     9 

<strong>输出:</strong> 4
<strong>解释:</strong> 最大值出现在树的第 3 层，宽度为 4 (5,3,null,9)。
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> 

          1
         /  
        3    
       / \       
      5   3     

<strong>输出:</strong> 2
<strong>解释:</strong> 最大值出现在树的第 3 层，宽度为 2 (5,3)。
</pre>

<p><strong>示例&nbsp;3:</strong></p>

<pre>
<strong>输入:</strong> 

          1
         / \
        3   2 
       /        
      5      

<strong>输出:</strong> 2
<strong>解释:</strong> 最大值出现在树的第 2 层，宽度为 2 (3,2)。
</pre>

<p><strong>示例 4:</strong></p>

<pre>
<strong>输入:</strong> 

          1
         / \
        3   2
       /     \  
      5       9 
     /         \
    6           7
<strong>输出:</strong> 8
<strong>解释:</strong> 最大值出现在树的第 4 层，宽度为 8 (6,null,null,null,null,null,null,7)。
</pre>

<p><strong>注意:</strong> 答案在32位有符号整数的表示范围内。</p>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/breadth-first-search/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/maximum-width-of-binary-tree)
