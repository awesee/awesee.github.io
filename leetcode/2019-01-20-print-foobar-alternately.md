---
layout:     single
title:      "交替打印FooBar"
date:       2019-01-20 21:30:00 +0800
categories: [Leetcode]
tags:       [Concurrency]
permalink:  /problems/print-foobar-alternately/
---

## 1115. 交替打印FooBar (Medium)

{% raw %}

<p>我们提供一个类：</p>

<pre>
class FooBar {
  public void foo() {
&nbsp; &nbsp; for (int i = 0; i &lt; n; i++) {
&nbsp; &nbsp; &nbsp; print(&quot;foo&quot;);
&nbsp;   }
  }

  public void bar() {
&nbsp; &nbsp; for (int i = 0; i &lt; n; i++) {
&nbsp; &nbsp; &nbsp; print(&quot;bar&quot;);
&nbsp; &nbsp; }
  }
}
</pre>

<p>两个不同的线程将会共用一个 <code>FooBar</code>&nbsp;实例。其中一个线程将会调用&nbsp;<code>foo()</code>&nbsp;方法，另一个线程将会调用&nbsp;<code>bar()</code>&nbsp;方法。</p>

<p>请设计修改程序，以确保 &quot;foobar&quot; 被输出 n 次。</p>

<p>&nbsp;</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> n = 1
<strong>输出:</strong> &quot;foobar&quot;
<strong>解释:</strong> 这里有两个线程被异步启动。其中一个调用 foo() 方法, 另一个调用 bar() 方法，&quot;foobar&quot; 将被输出一次。
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> n = 2
<strong>输出:</strong> &quot;foobarfoobar&quot;
<strong>解释:</strong> &quot;foobar&quot; 将被输出两次。
</pre>

{% endraw %}

### 相关话题
  [[多线程](https://github.com/awesee/leetcode/tree/main/tag/concurrency/README.md)]

### 相似题目
  1. [按序打印](/problems/print-in-order) (Easy)
  1. [打印零与奇偶数](/problems/print-zero-even-odd) (Medium)

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/print-foobar-alternately)
