---
layout: single
title:  "Ticker or Sleep"
date:   2019-11-30 18:30:00 +0800
categories: [Go]
tags: [Go, Guide]
permalink:  /ticker-or-sleep/
---

Go编程中，经常会遇到周期性处理任务的需求，下面以每秒打印当前时间为例介绍实现方式及区别

### 方法一（Ticker）

```go
func PrintNow() {
	t := time.NewTicker(time.Second)
	for {
		select {
		case <-t.C:
			fmt.Println(time.Now())
		}
	}
}
```

### 方法二（Sleep）

```go
func PrintNow() {
	for {
		time.Sleep(time.Second)
		fmt.Println(time.Now())
	}
}
```

以上2种方法都可以实现每秒钟打印一次当前时间，但是2种方式有很大区别。

cpu：方法一cpu占用大于方法二，因为方法一会有一个单独的协程用于定时向chan写入当前时间。

执行时间：方法一小于方法二，实际上方法二并不是每秒钟打印一次当前时间，
间隔时间其实还包含打印当前时间的执行时间。如果把`fmt.Println(time.Now())`改为
```go
func() {
	time.Sleep(500 * time.Millisecond)
	fmt.Println(time.Now())
}()
```
结果就很明显，方法一是每秒钟打印一次当前时间，方法二是每1.5秒打印一次当前时间

方法一是两个协程并发执行，方法二是一个协程串行执行
