---
layout:     single
title:      "随机数索引"
date:       2017-02-02 21:30:00 +0800
categories: [Leetcode]
tags:       [Reservoir Sampling, Hash Table, Math, Randomized]
permalink:  /problems/random-pick-index/
---

## 398. 随机数索引 (Medium)

{% raw %}

<p>给定一个可能含有重复元素的整数数组，要求随机输出给定的数字的索引。 您可以假设给定的数字一定存在于数组中。</p>

<p><strong>注意：</strong><br />
数组大小可能非常大。 使用太多额外空间的解决方案将不会通过测试。</p>

<p><strong>示例:</strong></p>

<pre>
int[] nums = new int[] {1,2,3,3,3};
Solution solution = new Solution(nums);

// pick(3) 应该返回索引 2,3 或者 4。每个索引的返回概率应该相等。
solution.pick(3);

// pick(1) 应该返回 0。因为只有nums[0]等于1。
solution.pick(1);
</pre>

{% endraw %}

### 相关话题
  [[水塘抽样](https://github.com/awesee/leetcode/tree/main/tag/reservoir-sampling/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[数学](https://github.com/awesee/leetcode/tree/main/tag/math/README.md)]
  [[随机化](https://github.com/awesee/leetcode/tree/main/tag/randomized/README.md)]

### 相似题目
  1. [链表随机节点](/problems/linked-list-random-node) (Medium)
  1. [黑名单中的随机数](/problems/random-pick-with-blacklist) (Hard)
  1. [按权重随机选择](/problems/random-pick-with-weight) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/random-pick-index)
