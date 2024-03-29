---
layout:     single
title:      "数组的相对排序"
date:       2019-01-27 21:30:00 +0800
categories: [Leetcode]
tags:       [Array, Hash Table, Counting Sort, Sorting]
permalink:  /problems/relative-sort-array/
---

## 1122. 数组的相对排序 (Easy)

{% raw %}

<p>给你两个数组，<code>arr1</code> 和 <code>arr2</code>，</p>

<ul>
	<li><code>arr2</code> 中的元素各不相同</li>
	<li><code>arr2</code> 中的每个元素都出现在 <code>arr1</code> 中</li>
</ul>

<p>对 <code>arr1</code> 中的元素进行排序，使 <code>arr1</code> 中项的相对顺序和 <code>arr2</code> 中的相对顺序相同。未在 <code>arr2</code> 中出现过的元素需要按照升序放在 <code>arr1</code> 的末尾。</p>

<p> </p>

<p><strong>示例：</strong></p>

<pre>
<strong>输入：</strong>arr1 = [2,3,1,3,2,4,6,7,9,2,19], arr2 = [2,1,4,3,9,6]
<strong>输出：</strong>[2,2,2,1,4,3,3,9,6,7,19]
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= arr1.length, arr2.length <= 1000</code></li>
	<li><code>0 <= arr1[i], arr2[i] <= 1000</code></li>
	<li><code>arr2</code> 中的元素 <code>arr2[i]</code> 各不相同</li>
	<li><code>arr2</code> 中的每个元素 <code>arr2[i]</code> 都出现在 <code>arr1</code> 中</li>
</ul>

{% endraw %}

### 相关话题
  [[数组](https://github.com/awesee/leetcode/tree/main/tag/array/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[计数排序](https://github.com/awesee/leetcode/tree/main/tag/counting-sort/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/relative-sort-array)
