---
layout:     single
title:      "根据二叉树创建字符串"
date:       2017-08-29 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Depth-First Search, String, Binary Tree]
permalink:  /problems/construct-string-from-binary-tree/
---

## 606. 根据二叉树创建字符串 (Easy)

{% raw %}

<p>你需要采用前序遍历的方式，将一个二叉树转换成一个由括号和整数组成的字符串。</p>

<p>空节点则用一对空括号 &quot;()&quot; 表示。而且你需要省略所有不影响字符串与原始二叉树之间的一对一映射关系的空括号对。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> 二叉树: [1,2,3,4]
       1
     /   \
    2     3
   /    
  4     

<strong>输出:</strong> &quot;1(2(4))(3)&quot;

<strong>解释:</strong> 原本将是&ldquo;1(2(4)())(3())&rdquo;，
在你省略所有不必要的空括号对之后，
它将是&ldquo;1(2(4))(3)&rdquo;。
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> 二叉树: [1,2,3,null,4]
       1
     /   \
    2     3
     \  
      4 

<strong>输出:</strong> &quot;1(2()(4))(3)&quot;

<strong>解释:</strong> 和第一个示例相似，
除了我们不能省略第一个对括号来中断输入和输出之间的一对一映射关系。
</pre>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/master/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/master/tag/string/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/master/tag/binary-tree/README.md)]

### 相似题目
  1. [从字符串生成二叉树](/problems/construct-binary-tree-from-string) (Medium)
  1. [寻找重复的子树](/problems/find-duplicate-subtrees) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/master/problems/construct-string-from-binary-tree)
