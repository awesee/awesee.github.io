---
layout:     single
title:      "推文计数"
date:       2019-09-10 21:30:00 +0800
categories: [Leetcode]
tags:       [Design, Hash Table, Binary Search, Ordered Set, Sorting]
permalink:  /problems/tweet-counts-per-frequency/
---

## 1348. 推文计数 (Medium)

{% raw %}

<p>请你实现一个能够支持以下两种方法的推文计数类&nbsp;<code>TweetCounts</code>：</p>

<p>1.<code> recordTweet(string tweetName, int time)</code></p>

<ul>
	<li>记录推文发布情况：用户&nbsp;<code>tweetName</code>&nbsp;在&nbsp;<code>time</code>（以 <strong>秒</strong>&nbsp;为单位）时刻发布了一条推文。</li>
</ul>

<p>2.<code> getTweetCountsPerFrequency(string freq, string tweetName, int startTime, int endTime)</code></p>

<ul>
	<li>返回从开始时间&nbsp;<code>startTime</code>（以 <strong>秒</strong> 为单位）到结束时间&nbsp;<code>endTime</code>（以 <strong>秒</strong> 为单位）内，每 <strong>分&nbsp;</strong><em><strong>minute</strong>，</em><strong>时&nbsp;<em>hour </em></strong>或者 <strong>日<em>&nbsp;day&nbsp;</em></strong>（取决于&nbsp;<code>freq</code>）内指定用户&nbsp;<code>tweetName</code>&nbsp;发布的推文总数。</li>
	<li><code>freq</code>&nbsp;的值始终为 <strong>分&nbsp;</strong><em><strong>minute</strong>，</em><strong>时</strong><em><strong> hour</strong>&nbsp;</em>或者<em>&nbsp;</em><strong>日</strong><em><strong> day</strong>&nbsp;</em>之一，表示获取指定用户&nbsp;<code>tweetName</code>&nbsp;发布推文次数的时间间隔。</li>
	<li>第一个时间间隔始终从 <code>startTime</code> 开始，因此时间间隔为&nbsp;<code>[startTime, startTime + delta*1&gt;, &nbsp;[startTime + delta*1, startTime + delta*2&gt;, [startTime + delta*2, startTime + delta*3&gt;, ... , [startTime + delta*i,&nbsp;<strong>min</strong>(startTime + delta*(i+1), endTime + 1)&gt;</code>，其中 <code>i</code> 和 <code>delta</code>（取决于 <code>freq</code>）都是非负整数。</li>
</ul>

<p>&nbsp;</p>

<p><strong>示例：</strong></p>

<pre><strong>输入：</strong>
[&quot;TweetCounts&quot;,&quot;recordTweet&quot;,&quot;recordTweet&quot;,&quot;recordTweet&quot;,&quot;getTweetCountsPerFrequency&quot;,&quot;getTweetCountsPerFrequency&quot;,&quot;recordTweet&quot;,&quot;getTweetCountsPerFrequency&quot;]
[[],[&quot;tweet3&quot;,0],[&quot;tweet3&quot;,60],[&quot;tweet3&quot;,10],[&quot;minute&quot;,&quot;tweet3&quot;,0,59],[&quot;minute&quot;,&quot;tweet3&quot;,0,60],[&quot;tweet3&quot;,120],[&quot;hour&quot;,&quot;tweet3&quot;,0,210]]

<strong>输出：</strong>
[null,null,null,null,[2],[2,1],null,[4]]

<strong>解释：</strong>
TweetCounts tweetCounts = new TweetCounts();
tweetCounts.recordTweet(&quot;tweet3&quot;, 0);
tweetCounts.recordTweet(&quot;tweet3&quot;, 60);
tweetCounts.recordTweet(&quot;tweet3&quot;, 10);                             //&nbsp;&quot;tweet3&quot;&nbsp;发布推文的时间分别是&nbsp;0,&nbsp;10&nbsp;和&nbsp;60 。
tweetCounts.getTweetCountsPerFrequency(&quot;minute&quot;, &quot;tweet3&quot;, 0, 59); //&nbsp;返回&nbsp;[2]。统计频率是每分钟（60 秒），因此只有一个有效时间间隔 [0,60&gt;&nbsp;-&nbsp;&gt;&nbsp;2&nbsp;条推文。
tweetCounts.getTweetCountsPerFrequency(&quot;minute&quot;, &quot;tweet3&quot;, 0, 60); //&nbsp;返回&nbsp;[2,1]。统计频率是每分钟（60 秒），因此有两个有效时间间隔&nbsp;<strong>1)</strong>&nbsp;[0,60&gt;&nbsp;-&nbsp;&gt;&nbsp;2&nbsp;条推文，和&nbsp;<strong>2)</strong>&nbsp;[60,61&gt;&nbsp;-&nbsp;&gt;&nbsp;1&nbsp;条推文。 
tweetCounts.recordTweet(&quot;tweet3&quot;, 120);                            // &quot;tweet3&quot;&nbsp;发布推文的时间分别是 0, 10, 60 和 120 。
tweetCounts.getTweetCountsPerFrequency(&quot;hour&quot;, &quot;tweet3&quot;, 0, 210);  //&nbsp;返回&nbsp;[4]。统计频率是每小时（3600 秒），因此只有一个有效时间间隔 [0,211&gt;&nbsp;-&nbsp;&gt;&nbsp;4&nbsp;条推文。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li>同时考虑&nbsp;<code>recordTweet</code>&nbsp;和&nbsp;<code>getTweetCountsPerFrequency</code>，最多有 <code>10000</code> 次操作。</li>
	<li><code>0 &lt;= time, startTime, endTime &lt;=&nbsp;10^9</code></li>
	<li><code>0 &lt;= endTime - startTime &lt;= 10^4</code></li>
</ul>

{% endraw %}

### 相关话题
  [[设计](https://github.com/awesee/leetcode/tree/main/tag/design/README.md)]
  [[哈希表](https://github.com/awesee/leetcode/tree/main/tag/hash-table/README.md)]
  [[二分查找](https://github.com/awesee/leetcode/tree/main/tag/binary-search/README.md)]
  [[有序集合](https://github.com/awesee/leetcode/tree/main/tag/ordered-set/README.md)]
  [[排序](https://github.com/awesee/leetcode/tree/main/tag/sorting/README.md)]

---

## [解法](https://github.com/awesee/leetcode/tree/main/problems/tweet-counts-per-frequency)
