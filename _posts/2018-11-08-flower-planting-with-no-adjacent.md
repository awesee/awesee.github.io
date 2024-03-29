---
layout:     single
title:      "不邻接植花"
date:       2018-11-08 21:30:00 +0800
categories: [Leetcode]
tags:       [Depth-First Search, Breadth-First Search, Graph]
permalink:  /problems/flower-planting-with-no-adjacent/
---

## 1042. 不邻接植花 (Medium)

{% raw %}

<p>有 <code>n</code> 个花园，按从 <code>1</code> 到 <code>n</code> 标记。另有数组 <code>paths</code> ，其中 <code>paths[i] = [x<sub>i</sub>, y<sub>i</sub>]</code> 描述了花园 <code>x<sub>i</sub></code> 到花园 <code>y<sub>i</sub></code> 的双向路径。在每个花园中，你打算种下四种花之一。</p>

<p>另外，所有花园 <strong>最多</strong> 有 3 条路径可以进入或离开.</p>

<p>你需要为每个花园选择一种花，使得通过路径相连的任何两个花园中的花的种类互不相同。</p>

<p>以数组形式返回 <strong>任一</strong> 可行的方案作为答案 <code>answer</code>，其中 <code>answer[i]</code> 为在第 <code>(i+1)</code> 个花园中种植的花的种类。花的种类用  1、2、3、4 表示。保证存在答案。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>n = 3, paths = [[1,2],[2,3],[3,1]]
<strong>输出：</strong>[1,2,3]
<strong>解释：</strong>
花园 1 和 2 花的种类不同。
花园 2 和 3 花的种类不同。
花园 3 和 1 花的种类不同。
因此，[1,2,3] 是一个满足题意的答案。其他满足题意的答案有 [1,2,4]、[1,4,2] 和 [3,2,1]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>n = 4, paths = [[1,2],[3,4]]
<strong>输出：</strong>[1,2,1,2]
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<strong>输入：</strong>n = 4, paths = [[1,2],[2,3],[3,4],[4,1],[1,3],[2,4]]
<strong>输出：</strong>[1,2,3,4]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= n <= 10<sup>4</sup></code></li>
	<li><code>0 <= paths.length <= 2 * 10<sup>4</sup></code></li>
	<li><code>paths[i].length == 2</code></li>
	<li><code>1 <= x<sub>i</sub>, y<sub>i</sub> <= n</code></li>
	<li><code>x<sub>i</sub> != y<sub>i</sub></code></li>
	<li>每个花园 <strong>最多</strong> 有 3 条路径可以进入或离开</li>
</ul>

{% endraw %}

### 相关话题
  [[深度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/depth-first-search/README.md)]
  [[广度优先搜索](https://github.com/awesee/leetcode/tree/main/tag/breadth-first-search/README.md)]
  [[图](https://github.com/awesee/leetcode/tree/main/tag/graph/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/flower-planting-with-no-adjacent)
