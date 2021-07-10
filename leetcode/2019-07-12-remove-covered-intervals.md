---
layout:     single
title:      "删除被覆盖区间"
date:       2019-07-12 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Sorting]
permalink:  /problems/remove-covered-intervals/
---

## 1288. 删除被覆盖区间 (Medium)

{% raw %}

<p>给你一个区间列表，请你删除列表中被其他区间所覆盖的区间。</p>

<p>只有当&nbsp;<code>c &lt;= a</code>&nbsp;且&nbsp;<code>b &lt;= d</code>&nbsp;时，我们才认为区间&nbsp;<code>[a,b)</code> 被区间&nbsp;<code>[c,d)</code> 覆盖。</p>

<p>在完成所有删除操作后，请你返回列表中剩余区间的数目。</p>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre>
<strong>输入：</strong>intervals = [[1,4],[3,6],[2,8]]
<strong>输出：</strong>2
<strong>解释：</strong>区间 [3,6] 被区间 [2,8] 覆盖，所以它被删除了。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong>​​​​​​</p>

<ul>
	<li><code>1 &lt;= intervals.length &lt;= 1000</code></li>
	<li><code>0 &lt;= intervals[i][0] &lt;&nbsp;intervals[i][1] &lt;= 10^5</code></li>
	<li>对于所有的&nbsp;<code>i != j</code>：<code>intervals[i] != intervals[j]</code></li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[排序](https://github.com/openset/leetcode/tree/master/tag/sorting/README.md)]

---

## [解法](https://github.com/openset/leetcode/tree/master/problems/remove-covered-intervals)
