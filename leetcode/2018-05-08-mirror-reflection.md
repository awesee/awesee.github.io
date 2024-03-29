---
layout:     single
title:      "镜面反射"
date:       2018-05-08 21:30:00 +0800
categories: [Leetcode]
tags:       [Geometry, Math]
permalink:  /problems/mirror-reflection/
---

## 858. 镜面反射 (Medium)

{% raw %}

<p>有一个特殊的正方形房间，每面墙上都有一面镜子。除西南角以外，每个角落都放有一个接受器，编号为 <code>0</code>， <code>1</code>，以及 <code>2</code>。</p>

<p>正方形房间的墙壁长度为 <code>p</code>，一束激光从西南角射出，首先会与东墙相遇，入射点到接收器 <code>0</code> 的距离为 <code>q</code> 。</p>

<p>返回光线最先遇到的接收器的编号（保证光线最终会遇到一个接收器）。</p>

<p> </p>

<p><strong>示例：</strong></p>

<pre>
<strong>输入： </strong>p = 2, q = 1
<strong>输出： </strong>2
<strong>解释： </strong>这条光线在第一次被反射回左边的墙时就遇到了接收器 2 。
<img alt="" src="https://aliyun-lc-upload.oss-cn-hangzhou.aliyuncs.com/aliyun-lc-upload/uploads/2018/06/22/reflection.png" style="height: 217px; width: 218px;" /></pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= p <= 1000</code></li>
	<li><code>0 <= q <= p</code></li>
</ul>

{% endraw %}

### 相关话题
  [[几何](https://github.com/awesee/leetcode/tree/main/tag/geometry/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/mirror-reflection)
