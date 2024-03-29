---
layout:     single
title:      "可以攻击国王的皇后"
date:       2019-05-07 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Matrix, Simulation]
permalink:  /problems/queens-that-can-attack-the-king/
---

## 1222. 可以攻击国王的皇后 (Medium)

{% raw %}

<p>在一个 <strong>8x8</strong> 的棋盘上，放置着若干「黑皇后」和一个「白国王」。</p>

<p>「黑皇后」在棋盘上的位置分布用整数坐标数组 <code>queens</code> 表示，「白国王」的坐标用数组 <code>king</code> 表示。</p>

<p>「黑皇后」的行棋规定是：横、直、斜都可以走，步数不受限制，但是，不能越子行棋。</p>

<p>请你返回可以直接攻击到「白国王」的所有「黑皇后」的坐标（任意顺序）。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<p><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/10/13/untitled-diagram.jpg" style="width: 250px;" /></p>

<pre>
<strong>输入：</strong>queens = [[0,1],[1,0],[4,0],[0,4],[3,3],[2,4]], king = [0,0]
<strong>输出：</strong>[[0,1],[1,0],[3,3]]
<strong>解释：</strong> 
[0,1] 的皇后可以攻击到国王，因为他们在同一行上。 
[1,0] 的皇后可以攻击到国王，因为他们在同一列上。 
[3,3] 的皇后可以攻击到国王，因为他们在同一条对角线上。 
[0,4] 的皇后无法攻击到国王，因为她被位于 [0,1] 的皇后挡住了。 
[4,0] 的皇后无法攻击到国王，因为她被位于 [1,0] 的皇后挡住了。 
[2,4] 的皇后无法攻击到国王，因为她和国王不在同一行/列/对角线上。
</pre>

<p><strong>示例 2：</strong></p>

<p><strong><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/10/13/untitled-diagram-1.jpg" style="height: 321px; width: 321px;" /></strong></p>

<pre>
<strong>输入：</strong>queens = [[0,0],[1,1],[2,2],[3,4],[3,5],[4,4],[4,5]], king = [3,3]
<strong>输出：</strong>[[2,2],[3,4],[4,4]]
</pre>

<p><strong>示例 3：</strong></p>

<p><strong><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/10/13/untitled-diagram-2.jpg" style="height: 321px; width: 321px;" /></strong></p>

<pre>
<strong>输入：</strong>queens = [[5,6],[7,7],[2,1],[0,7],[1,6],[5,1],[3,7],[0,3],[4,0],[1,2],[6,3],[5,0],[0,4],[2,2],[1,1],[6,4],[5,4],[0,0],[2,6],[4,5],[5,2],[1,4],[7,5],[2,3],[0,5],[4,2],[1,0],[2,7],[0,1],[4,6],[6,1],[0,6],[4,3],[1,7]], king = [3,4]
<strong>输出：</strong>[[2,3],[1,4],[1,6],[3,7],[4,3],[5,4],[4,5]]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= queens.length <= 63</code></li>
	<li><code>queens[i].length == 2</code></li>
	<li><code>0 <= queens[i][j] < 8</code></li>
	<li><code>king.length == 2</code></li>
	<li><code>0 <= king[0], king[1] < 8</code></li>
	<li>一个棋盘格上最多只能放置一枚棋子。</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[矩阵](https://github.com/awesee/leetcode/tree/main/tag/matrix/README.md)]
  [[模拟](https://github.com/awesee/leetcode/tree/main/tag/simulation/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/queens-that-can-attack-the-king)
