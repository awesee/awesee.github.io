---
layout:     single
title:      "最大整除子集"
date:       2017-01-03 21:30:00 +0800
categories: [Leetcode]
tags:       [Math, Dynamic Programming]
permalink:  /problems/largest-divisible-subset/
---

## 368. 最大整除子集 (Medium)

{% raw %}

<p>给出一个由<strong>无重复的</strong>正整数组成的集合，找出其中最大的整除子集，子集中任意一对 (S<sub>i，</sub>S<sub>j</sub>) 都要满足：S<sub>i</sub> % S<sub>j</sub> = 0 或 S<sub>j</sub> % S<sub>i</sub> = 0。</p>

<p>如果有多个目标子集，返回其中任何一个均可。</p>

<p>&nbsp;</p>

<p><strong>示例 1:</strong></p>

<pre><strong>输入:</strong> [1,2,3]
<strong>输出:</strong> [1,2] (当然, [1,3] 也正确)
</pre>

<p><strong>示例 2:</strong></p>

<pre><strong>输入:</strong> [1,2,4,8]
<strong>输出:</strong> [1,2,4,8]
</pre>

{% endraw %}

### 相关话题
  [[数学](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
  [[动态规划](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/largest-divisible-subset)
