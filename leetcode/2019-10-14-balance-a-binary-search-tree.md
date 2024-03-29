---
layout:     single
title:      "将二叉搜索树变平衡"
date:       2019-10-14 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, Tree, Depth-First Search, Binary Search Tree, Divide and Conquer, Binary Tree]
permalink:  /problems/balance-a-binary-search-tree/
---

## 1382. 将二叉搜索树变平衡 (Medium)

{% raw %}

<p>给你一棵二叉搜索树，请你返回一棵&nbsp;<strong>平衡后</strong>&nbsp;的二叉搜索树，新生成的树应该与原来的树有着相同的节点值。</p>

<p>如果一棵二叉搜索树中，每个节点的两棵子树高度差不超过 1 ，我们就称这棵二叉搜索树是&nbsp;<strong>平衡的</strong> 。</p>

<p>如果有多种构造方法，请你返回任意一种。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<p><strong><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/03/15/1515_ex1.png" style="height: 248px; width: 250px;"><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2020/03/15/1515_ex1_out.png" style="height: 200px; width: 200px;"></strong></p>

<pre><strong>输入：</strong>root = [1,null,2,null,3,null,4,null,null]
<strong>输出：</strong>[2,1,3,null,null,null,4]
<strong>解释：</strong>这不是唯一的正确答案，[3,1,4,null,2,null,null] 也是一个可行的构造方案。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li>树节点的数目在&nbsp;<code>1</code>&nbsp;到&nbsp;<code>10^4</code>&nbsp;之间。</li>
	<li>树节点的值互不相同，且在&nbsp;<code>1</code>&nbsp;到&nbsp;<code>10^5</code> 之间。</li>
</ul>

{% endraw %}

### 相关话题
  [[贪心](https://github.com/awesee/leetcode/tree/main/tag/greedy/README.md)]
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[二叉搜索树](https://github.com/awesee/leetcode/tree/main/tag/binary-search-tree/README.md)]
  [[分治](https://github.com/awesee/leetcode/tree/main/tag/divide-and-conquer/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/balance-a-binary-search-tree)
