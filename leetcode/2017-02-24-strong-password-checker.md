---
layout:     single
title:      "强密码检验器"
date:       2017-02-24 21:30:00 +0800
categories: [Leetcode]
tags:       [Greedy, String, Heap (Priority Queue)]
permalink:  /problems/strong-password-checker/
---

## 420. 强密码检验器 (Hard)

{% raw %}

<p>一个强密码应满足以下所有条件：</p>

<ol>
	<li>由至少6个，至多20个字符组成。</li>
	<li>至少包含一个小写字母，一个大写字母，和一个数字。</li>
	<li>同一字符<strong>不能</strong>连续出现三次 (比如 &quot;...aaa...&quot; 是不允许的, 但是&nbsp;&quot;...aa...a...&quot; 是可以的)。</li>
</ol>

<p>编写函数&nbsp;strongPasswordChecker(s)，s 代表输入字符串，如果 s 已经符合强密码条件，则返回0；否则返回要将 s 修改为满足强密码条件的字符串所需要进行修改的<strong>最小</strong>步数。</p>

<p>插入、删除、替换任一字符都算作一次修改。</p>

{% endraw %}

### 相关话题
  [[贪心](https://github.com/awesee/leetcode/tree/main/tag/greedy/README.md)]
  [[字符串](https://github.com/awesee/leetcode/tree/main/tag/string/README.md)]
  [[堆（优先队列）](https://github.com/awesee/leetcode/tree/main/tag/heap-priority-queue/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/strong-password-checker)
