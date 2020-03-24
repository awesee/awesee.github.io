---
layout:     single
title:      "课程表"
date:       2016-07-26 21:30:00 +0800
categories: [Leetcode]
tags:       [Depth-first Search, Breadth-first Search, Graph, Topological Sort]
permalink:  /problems/course-schedule/
---

## 207. 课程表 (Medium)

{% raw %}

<p>你这个学期必须选修 <code>numCourse</code> 门课程，记为&nbsp;<code>0</code>&nbsp;到&nbsp;<code>numCourse-1</code> 。</p>

<p>在选修某些课程之前需要一些先修课程。&nbsp;例如，想要学习课程 0 ，你需要先完成课程 1 ，我们用一个匹配来表示他们：<code>[0,1]</code></p>

<p>给定课程总量以及它们的先决条件，请你判断是否可能完成所有课程的学习？</p>

<p>&nbsp;</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入:</strong> 2, [[1,0]] 
<strong>输出: </strong>true
<strong>解释:</strong>&nbsp;总共有 2 门课程。学习课程 1 之前，你需要完成课程 0。所以这是可能的。</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入:</strong> 2, [[1,0],[0,1]]
<strong>输出: </strong>false
<strong>解释:</strong>&nbsp;总共有 2 门课程。学习课程 1 之前，你需要先完成​课程 0；并且学习课程 0 之前，你还应先完成课程 1。这是不可能的。</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li>输入的先决条件是由 <strong>边缘列表</strong> 表示的图形，而不是 邻接矩阵 。详情请参见<a href="http://blog.csdn.net/woaidapaopao/article/details/51732947" target="_blank">图的表示法</a>。</li>
	<li>你可以假定输入的先决条件中没有重复的边。</li>
	<li><code>1 &lt;=&nbsp;numCourses &lt;= 10^5</code></li>
</ol>

{% endraw %}

### 相关话题
  [[深度优先搜索](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/openset/leetcode/tree/master/tag/breadth-first-search/README.md)]
  [[图](https://github.com/openset/leetcode/tree/master/tag/graph/README.md)]
  [[拓扑排序](https://github.com/openset/leetcode/tree/master/tag/topological-sort/README.md)]

### 相似题目
  1. [课程表 II](/problems/course-schedule-ii) (Medium)
  1. [以图判树](/problems/graph-valid-tree) (Medium)
  1. [最小高度树](/problems/minimum-height-trees) (Medium)
  1. [课程表 III](/problems/course-schedule-iii) (Hard)

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/course-schedule)
