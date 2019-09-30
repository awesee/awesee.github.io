---
layout:     single
title:      "二叉树的序列化与反序列化"
date:       2016-10-24 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Design]
permalink:  /problems/serialize-and-deserialize-binary-tree/
---

## 297. 二叉树的序列化与反序列化 (Hard)

{% raw %}

<p>序列化是将一个数据结构或者对象转换为连续的比特位的操作，进而可以将转换后的数据存储在一个文件或者内存中，同时也可以通过网络传输到另一个计算机环境，采取相反方式重构得到原数据。</p>

<p>请设计一个算法来实现二叉树的序列化与反序列化。这里不限定你的序列 / 反序列化算法执行逻辑，你只需要保证一个二叉树可以被序列化为一个字符串并且将这个字符串反序列化为原始的树结构。</p>

<p><strong>示例:&nbsp;</strong></p>

<pre>你可以将以下二叉树：

    1
   / \
  2   3
     / \
    4   5

序列化为 <code>&quot;[1,2,3,null,null,4,5]&quot;</code></pre>

<p><strong>提示:&nbsp;</strong>这与 LeetCode 目前使用的方式一致，详情请参阅&nbsp;<a href="/faq/#binary-tree">LeetCode 序列化二叉树的格式</a>。你并非必须采取这种方式，你也可以采用其他的方法解决这个问题。</p>

<p><strong>说明:&nbsp;</strong>不要使用类的成员 / 全局 / 静态变量来存储状态，你的序列化和反序列化算法应该是无状态的。</p>

{% endraw %}

### 相关话题
  [[树](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[设计](https://github.com/openset/leetcode/tree/master/tag/design/README.md)]

### 相似题目
  1. [字符串的编码与解码](/problems/encode-and-decode-strings) (Medium)
  1. [序列化和反序列化二叉搜索树](/problems/serialize-and-deserialize-bst) (Medium)
  1. [寻找重复的子树](/problems/find-duplicate-subtrees) (Medium)
  1. [序列化和反序列化 N 叉树](/problems/serialize-and-deserialize-n-ary-tree) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/serialize-and-deserialize-binary-tree)
