---
layout:     single
title:      "合并二叉树"
date:       2017-09-09 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree]
permalink:  /problems/merge-two-binary-trees/
---

## 617. 合并二叉树 (Easy)

{% raw %}

<p>给定两个二叉树，想象当你将它们中的一个覆盖到另一个上时，两个二叉树的一些节点便会重叠。</p>

<p>你需要将他们合并为一个新的二叉树。合并的规则是如果两个节点重叠，那么将他们的值相加作为节点合并后的新值，否则<strong>不为&nbsp;</strong>NULL 的节点将直接作为新二叉树的节点。</p>

<p><strong>示例&nbsp;1:</strong></p>

<pre>
<strong>输入:</strong> 
	Tree 1                     Tree 2                  
          1                         2                             
         / \                       / \                            
        3   2                     1   3                        
       /                           \   \                      
      5                             4   7                  
<strong>输出:</strong> 
合并后的树:
	     3
	    / \
	   4   5
	  / \   \ 
	 5   4   7
</pre>

<p><strong>注意:</strong>&nbsp;合并必须从两个树的根节点开始。</p>

{% endraw %}

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/merge-two-binary-trees)