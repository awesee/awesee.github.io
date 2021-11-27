---
layout:     single
title:      "O(1) 时间插入、删除和获取随机元素"
date:       2017-01-15 21:30:00 +0800
categories: [Leetcode]
tags:       [Design, Array, Hash Table, Math, Randomized]
permalink:  /problems/insert-delete-getrandom-o1/
---

## 380. O(1) 时间插入、删除和获取随机元素 (Medium)

{% raw %}

<p>设计一个支持在<em>平均&nbsp;</em>时间复杂度 <strong>O(1)</strong>&nbsp;下，执行以下操作的数据结构。</p>

<ol>
	<li><code>insert(val)</code>：当元素 val 不存在时，向集合中插入该项。</li>
	<li><code>remove(val)</code>：元素 val 存在时，从集合中移除该项。</li>
	<li><code>getRandom</code>：随机返回现有集合中的一项。每个元素应该有<strong>相同的概率</strong>被返回。</li>
</ol>

<p><strong>示例 :</strong></p>

<pre>
// 初始化一个空的集合。
RandomizedSet randomSet = new RandomizedSet();

// 向集合中插入 1 。返回 true 表示 1 被成功地插入。
randomSet.insert(1);

// 返回 false ，表示集合中不存在 2 。
randomSet.remove(2);

// 向集合中插入 2 。返回 true 。集合现在包含 [1,2] 。
randomSet.insert(2);

// getRandom 应随机返回 1 或 2 。
randomSet.getRandom();

// 从集合中移除 1 ，返回 true 。集合现在包含 [2] 。
randomSet.remove(1);

// 2 已在集合中，所以返回 false 。
randomSet.insert(2);

// 由于 2 是集合中唯一的数字，getRandom 总是返回 2 。
randomSet.getRandom();
</pre>

{% endraw %}

### 相关话题
  [[设计](https://github.com/awesee/leetcode/tree/main/tag/design/README.md)]
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[随机化](https://github.com/awesee/leetcode/tree/main/tag/randomized/README.md)]

### 相似题目
  1. [O(1) 时间插入、删除和获取随机元素 - 允许重复](/problems/insert-delete-getrandom-o1-duplicates-allowed) (Hard)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/insert-delete-getrandom-o1)
