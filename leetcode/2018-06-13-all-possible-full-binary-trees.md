---
layout:     single
title:      "所有可能的满二叉树"
date:       2018-06-13 21:30:00 +0800
categories: [Leetcode]
tags:       [Tree, Recursion, Memoization, Dynamic Programming, Binary Tree]
permalink:  /problems/all-possible-full-binary-trees/
---

## 894. 所有可能的满二叉树 (Medium)

{% raw %}

<p><em>满二叉树</em>是一类二叉树，其中每个结点恰好有 0 或 2 个子结点。</p>

<p>返回包含 <code>N</code> 个结点的所有可能满二叉树的列表。 答案的每个元素都是一个可能树的根结点。</p>

<p>答案中每个树的每个<code>结点</code>都<strong>必须</strong>有 <code>node.val=0</code>。</p>

<p>你可以按任何顺序返回树的最终列表。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>7
<strong>输出：</strong>[[0,0,0,null,null,0,0,null,null,0,0],[0,0,0,null,null,0,0,0,0],[0,0,0,0,0,0,0],[0,0,0,0,0,null,null,null,null,0,0],[0,0,0,0,0,null,null,0,0]]
<strong>解释：</strong>
<img alt="" src="https://aliyun-lc-upload.oss-cn-hangzhou.aliyuncs.com/aliyun-lc-upload/uploads/2018/08/24/fivetrees.png" style="height: 400px; width: 700px;">
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= N &lt;= 20</code></li>
</ul>

{% endraw %}

### 相关话题
  [[树](https://github.com/awesee/leetcode/tree/main/tag/tree/README.md)]
  [[递归](https://github.com/awesee/leetcode/tree/main/tag/recursion/README.md)]
  [[记忆化搜索](https://github.com/awesee/leetcode/tree/main/tag/memoization/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[二叉树](https://github.com/awesee/leetcode/tree/main/tag/binary-tree/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/all-possible-full-binary-trees)
