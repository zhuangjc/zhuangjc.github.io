---
layout: post
title:  "第一篇，markdown语法实验"
date:   2025-09-10 17:48:27 +0800
categories: jekyll update
---

# 一级标题

* 列表
* 列表



1. test![](..\assets\images\2025-09-11-My-first-blog\2025-09-11-15-07-08-image.png)

2. testttt

<br>
表格：

| Device       | ACRN | Crosvm | ID In virtio spec | Frontend  Upstream | Description                                          |
| ------------ |:----:|:------:|:-----------------:| ------------------ | ---------------------------------------------------- |
| virtio-block | Y    | Y      | 2                 | Yes                | Basic read/write block device.                       |
| virtio-net   | Y    | Y      | 1                 | Yes                | Device to interface the host and guest networks.     |
| virtio-rng   | Y    | Y      | 4                 | Yes                | Entropy source used to seed guest OS's entropy pool. |
| virtio-vsock | N    | Y      | 19                | Yes                | Enabled VSOCKs for host/guest communication.         |

<br>

## 二级标题

![另一种图片插入方式](../assets/images/first-blog/cat_old.png)

<div align="center"><img src="/assets/images/cat.png"/></div>
<p align="center">一只大老虎</p>
<br>

代码段

```c
void it_it_c_func(void)
{
  return;
}
```

<br>
1. 列表
2. 列表

<br>

引用：[菜菜的阿庄][caizhuang]

[caizhuang]: https://blog.csdn.net/qq_28499879
