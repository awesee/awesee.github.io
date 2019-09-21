---
layout:     single
title:      "由斜杠划分区域"
date:       2018-08-17 21:30:00 +0800
categories: [Leetcode]
tags:       [Depth-first Search, Union Find, Graph]
permalink:  /problems/regions-cut-by-slashes/
---

## 959. 由斜杠划分区域 (Medium)

{% raw %}

<p>在由 1 x 1 方格组成的 N x N 网格&nbsp;<code>grid</code> 中，每个 1 x 1&nbsp;方块由 <code>/</code>、<code>\</code> 或空格构成。这些字符会将方块划分为一些共边的区域。</p>

<p>（请注意，反斜杠字符是转义的，因此 <code>\</code> 用 <code>&quot;\\&quot;</code>&nbsp;表示。）。</p>

<p>返回区域的数目。</p>

<p>&nbsp;</p>

<ol>
</ol>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：
</strong>[
&nbsp; &quot; /&quot;,
&nbsp; &quot;/ &quot;
]
<strong>输出：</strong>2
<strong>解释：</strong>2x2 网格如下：
<img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2018/12/15/1.png"></pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：
</strong>[
&nbsp; &quot; /&quot;,
&nbsp; &quot;  &quot;
]
<strong>输出：</strong>1
<strong>解释：</strong>2x2 网格如下：
<img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2018/12/15/2.png"></pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：
</strong>[
&nbsp; &quot;\\/&quot;,
&nbsp; &quot;/\\&quot;
]
<strong>输出：</strong>4
<strong>解释：</strong>（回想一下，因为 \ 字符是转义的，所以 &quot;\\/&quot; 表示 \/，而 &quot;/\\&quot; 表示 /\。）
2x2 网格如下：
<img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2018/12/15/3.png"></pre>

<p><strong>示例 4：</strong></p>

<pre><strong>输入：
</strong>[
&nbsp; &quot;/\\&quot;,
&nbsp; &quot;\\/&quot;
]
<strong>输出：</strong>5
<strong>解释：</strong>（回想一下，因为 \ 字符是转义的，所以 &quot;/\\&quot; 表示 /\，而 &quot;\\/&quot; 表示 \/。）
2x2 网格如下：
<img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2018/12/15/4.png"></pre>

<p><strong>示例 5：</strong></p>

<pre><strong>输入：
</strong>[
&nbsp; &quot;//&quot;,
&nbsp; &quot;/ &quot;
]
<strong>输出：</strong>3
<strong>解释：</strong>2x2 网格如下：
<img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2018/12/15/5.png">
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= grid.length == grid[0].length &lt;= 30</code></li>
	<li><code>grid[i][j]</code> 是&nbsp;<code>&#39;/&#39;</code>、<code>&#39;\&#39;</code>、或&nbsp;<code>&#39; &#39;</code>。</li>
</ol>

{% endraw %}

### 相关话题
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[并查集](https://github.com/openset/leetcode/tree/master/tag/union-find/README.md)]
  [[图](https://github.com/openset/leetcode/tree/master/tag/graph/README.md)]

---

## [答案](https://github.com/openset/leetcode/tree/master/problems/regions-cut-by-slashes)
