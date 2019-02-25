---
layout: single
title:  如何迅速判断一个数是不是2的幂、3的幂、4的幂
date:   2019-02-25 15:00:00 +0800
categories: [math]
tags: [math]
---

## 判断n是否为2的幂

2的0次幂为1，2的1次幂为2，2的2次幂为4......，对应的二进制表示为0b1，0b10，0b100......，任何整数乘以2，都相当于向左移动了一位。
这样，2的幂的特征就是二进制表示只有最高位为1，其他位均为0。那么，我们只要判断一个数的二进制表示只有一个1，那么它就是2的幂。

n为整数，则n & (n - 1)可以消除n二进制表示的最低位的1，这个方法可以用来统计一个数二进制中1的个数，当然也可以用来判断是否为2的幂。

Go语言实现如下：
```go
func isPowerOfTwo(n int) bool {
 return n > 0 && n&(n-1) == 0
}
```

## 判断n是否为4的幂

4的0次幂为1，4的1次幂为4，4的2次幂为16......，对应的二进制表示为0b1，0b100，0b10000......，
4的幂首先是2的幂，因为4^n = （2^2）^n，和判断n是否为2的幂唯一的不同是，4的幂的二进制表示中，1全在奇数位上。
所以进一步判断其与0x55555555按位与的结果，0x55555555是十六进制表示，换成二进制表示，可以发现，其奇数位上全是1，
那么相与结果应该为其本身，则是4的幂，否则不是。

Go语言实现如下：
```go
func isPowerOfFour(n int) bool {
	return n&(n-1) == 0 && n&0x55555555 > 0
}
```

## 判断n是否为3的幂

3的0次幂为1，3的1次幂为3，3的2次幂为9,3的3次幂为27......，
3的幂的特点是如果一个整数N是3的幂，那么其所有约数都是3的幂。那么，换一个角度，如果n小于N且是N的约数，那么其一定是3的幂。

int型数据最大值为2^31-1 = 2147483647 = 0x7fffffff，则int型数据中3的最大幂如下：
```go
// math.MaxInt32 = 2^31-1
max := math.Pow(3, math.Floor(math.Log(math.MaxInt32)/math.Log(3)))
fmt.Println(int(max))
// Output:
// 1162261467
```

Go语言实现如下：
```go
func isPowerOfFour(n int) bool {
	return n > 0 && 1162261467%n == 0
}
```