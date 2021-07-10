---
layout:     single
title:      "可能的二分法"
date:       2018-06-05 21:30:00 +0800
categories: [Leetcode]
tags:       [Depth-First Search, Breadth-First Search, Union Find, Graph]
permalink:  /problems/possible-bipartition/
---

## 886. 可能的二分法 (Medium)

{% raw %}

<p>给定一组 <code>N</code> 人（编号为 <code>1, 2, ..., N</code>）， 我们想把每个人分进<strong>任意</strong>大小的两组。</p>

<p>每个人都可能不喜欢其他人，那么他们不应该属于同一组。</p>

<p>形式上，如果 <code>dislikes[i] = [a, b]</code>，表示不允许将编号为 <code>a</code> 和 <code>b</code> 的人归入同一组。</p>

<p>当可以用这种方法将所有人分进两组时，返回 <code>true</code>；否则返回 <code>false</code>。</p>

<p> </p>

<ol>
</ol>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>N = 4, dislikes = [[1,2],[1,3],[2,4]]
<strong>输出：</strong>true
<strong>解释：</strong>group1 [1,4], group2 [2,3]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>N = 3, dislikes = [[1,2],[1,3],[2,3]]
<strong>输出：</strong>false
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>N = 5, dislikes = [[1,2],[2,3],[3,4],[4,5],[1,5]]
<strong>输出：</strong>false
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= N <= 2000</code></li>
	<li><code>0 <= dislikes.length <= 10000</code></li>
	<li><code>dislikes[i].length == 2</code></li>
	<li><code>1 <= dislikes[i][j] <= N</code></li>
	<li><code>dislikes[i][0] < dislikes[i][1]</code></li>
	<li>对于 <code>dislikes[i] == dislikes[j]</code> 不存在 <code>i != j</code></li>
</ul>

{% endraw %}

### 相关话题
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/openset/leetcode/tree/master/tag/breadth-first-search/README.md)]
  [[并查集](https://github.com/openset/leetcode/tree/master/tag/union-find/README.md)]
  [[图](https://github.com/openset/leetcode/tree/master/tag/graph/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/possible-bipartition)
