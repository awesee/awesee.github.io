---
layout:     single
title:      "根据字符出现频率排序"
date:       2017-03-27 21:30:00 +0800
categories: [Leetcode]
tags:       [Hash Table, String, Bucket Sort, Counting, Sorting, Heap (Priority Queue)]
permalink:  /problems/sort-characters-by-frequency/
---

## 451. 根据字符出现频率排序 (Medium)

{% raw %}

<p>给定一个字符串，请将字符串里的字符按照出现的频率降序排列。</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong>
&quot;tree&quot;

<strong>输出:</strong>
&quot;eert&quot;

<strong>解释:
</strong>&#39;e&#39;出现两次，&#39;r&#39;和&#39;t&#39;都只出现一次。
因此&#39;e&#39;必须出现在&#39;r&#39;和&#39;t&#39;之前。此外，&quot;eetr&quot;也是一个有效的答案。
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong>
&quot;cccaaa&quot;

<strong>输出:</strong>
&quot;cccaaa&quot;

<strong>解释:
</strong>&#39;c&#39;和&#39;a&#39;都出现三次。此外，&quot;aaaccc&quot;也是有效的答案。
注意&quot;cacaca&quot;是不正确的，因为相同的字母必须放在一起。
</pre>

<p><strong>示例 3:</strong></p>

<pre>
<strong>输入:</strong>
&quot;Aabb&quot;

<strong>输出:</strong>
&quot;bbAa&quot;

<strong>解释:
</strong>此外，&quot;bbaA&quot;也是一个有效的答案，但&quot;Aabb&quot;是不正确的。
注意&#39;A&#39;和&#39;a&#39;被认为是两种不同的字符。
</pre>

{% endraw %}

### 相关话题
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[桶排序](https://github.com/awesee/leetcode/tree/main/tag/bucket-sort/README.md)]
  [[计数](https://github.com/awesee/leetcode/tree/main/tag/counting/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]
  [[堆（优先队列）](https://github.com/awesee/leetcode/tree/main/tag/heap-priority-queue/README.md)]

### 相似题目
  1. [前 K 个高频元素](/problems/top-k-frequent-elements) (Medium)
  1. [字符串中的第一个唯一字符](/problems/first-unique-character-in-a-string) (Easy)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/sort-characters-by-frequency)
