---
layout:     single
title:      "两地调度"
date:       2018-10-26 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy]
permalink:  /problems/two-city-scheduling/
---

## 1029. 两地调度 (Easy)

{% raw %}

<p>公司计划面试 <code>2N</code> 人。第 <code>i</code> 人飞往 <code>A</code> 市的费用为 <code>costs[i][0]</code>，飞往 <code>B</code> 市的费用为 <code>costs[i][1]</code>。</p>

<p>返回将每个人都飞到某座城市的最低费用，要求每个城市都有 <code>N</code> 人抵达<strong>。</strong></p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>[[10,20],[30,200],[400,50],[30,20]]
<strong>输出：</strong>110
<strong>解释：</strong>
第一个人去 A 市，费用为 10。
第二个人去 A 市，费用为 30。
第三个人去 B 市，费用为 50。
第四个人去 B 市，费用为 20。

最低总费用为 10 + 30 + 50 + 20 = 110，每个城市都有一半的人在面试。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ol>
	<li><code>1 &lt;= costs.length &lt;= 100</code></li>
	<li><code>costs.length</code> 为偶数</li>
	<li><code>1 &lt;= costs[i][0], costs[i][1] &lt;= 1000</code></li>
</ol>

{% endraw %}

### 相关话题
  [[贪心算法](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/two-city-scheduling)
