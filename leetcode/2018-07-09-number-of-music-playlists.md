---
layout:     single
title:      "播放列表的数量"
date:       2018-07-09 21:30:00 +0800
categories: [Leetcode]
tags:       [Math, Dynamic Programming, Combinatorics]
permalink:  /problems/number-of-music-playlists/
---

## 920. 播放列表的数量 (Hard)

{% raw %}

<p>你的音乐播放器里有&nbsp;<code>N</code>&nbsp;首不同的歌，在旅途中，你的旅伴想要听 <code>L</code>&nbsp;首歌（不一定不同，即，允许歌曲重复）。请你为她按如下规则创建一个播放列表：</p>

<ul>
	<li>每首歌至少播放一次。</li>
	<li>一首歌只有在其他 <code>K</code> 首歌播放完之后才能再次播放。</li>
</ul>

<p>返回可以满足要求的播放列表的数量。<strong>由于答案可能非常大，请返回它模&nbsp;<code>10^9 + 7</code>&nbsp;的结果。</strong></p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre><strong>输入：</strong>N = 3, L = 3, K = 1
<strong>输出：</strong>6
<strong>解释：</strong>有 6 种可能的播放列表。[1, 2, 3]，[1, 3, 2]，[2, 1, 3]，[2, 3, 1]，[3, 1, 2]，[3, 2, 1].
</pre>

<p><strong>示例 2：</strong></p>

<pre><strong>输入：</strong>N = 2, L = 3, K = 0
<strong>输出：</strong>6
<strong>解释：</strong>有 6 种可能的播放列表。[1, 1, 2]，[1, 2, 1]，[2, 1, 1]，[2, 2, 1]，[2, 1, 2]，[1, 2, 2]
</pre>

<p><strong>示例 3：</strong></p>

<pre><strong>输入：</strong>N = 2, L = 3, K = 1
<strong>输出：</strong>2
<strong>解释：</strong>有 2 种可能的播放列表。[1, 2, 1]，[2, 1, 2]
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>0 &lt;= K &lt; N &lt;= L &lt;= 100</code></li>
</ol>

{% endraw %}

### 相关话题
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[动态规划](https://github.com/awesee/leetcode/tree/main/tag/dynamic-programming/README.md)]
  [[组合数学](https://github.com/awesee/leetcode/tree/main/tag/combinatorics/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/number-of-music-playlists)
