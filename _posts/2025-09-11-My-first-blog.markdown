---
layout: post
title:  "第一篇，markdown语法实验"
date:   2025-09-10 17:48:27 +0800
categories: jekyll update
---

# 一级标题

* 列表
* 列表

<br>
表格：

<br>

| Device          | ACRN | Crosvm | ID In virtio spec | Frontend  Upstream          | Description                                                  |
| --------------- | :----: | :------: | :-------------------------: | ------------------------------------------------------------ | ------------------------------------------------------------ |
| virtio-block    | Y    | Y      | 2     | Yes                         | Basic read/write block device.                               |
| virtio-net      | Y    | Y      | 1     | Yes                         | Device to interface the host and guest networks.             |
| virtio-rng      | Y    | Y      | 4     | Yes                         | Entropy source used to seed guest OS's entropy pool.         |
| virtio-vsock    | N    | Y      | 19    | Yes                         | Enabled VSOCKs for host/guest communication.                 |
| virtio-wayland  | N    | Y      | N     | No (Chrome OS kernel)       | Allowed guest to use host Wayland socket.                    |
| virtio-balloon  | N    | Y      | 5     | Yes                         | Dynamic guest RAM allocation.                                |
| virtio-9p       | N    | Y      | 9     | Yes                         | Sharing host files with the guest as network filesystem.     |
| virtio-gpu      | N    | Y      | 16    | Yes                         | A display virtualization solution.                           |
| virtio-tpm      | N    | Y      | N     | No (Chrome OS kernel)       | Trusted Platform Module.                                     |
| virtio-fs       | N    | Y      | 26    | Yes (merged in v5.4)        | Sharing host files with the guest   as local filesystem.     |
| virtio-pmem     | N    | Y      | 27    | Yes                         | A fake persistent memory(nvdimm) in guest which allows to bypass  the guest page cache. |
| virtio-input    | Y    | Y      | 18    | Yes                         | Input device.                                                |
| virtio-console  | Y    | N      | 3     | Yes                         | Console over virtio transport.                               |
| virtio-audio    | Y    | N      | 25    | No (acrn-kernel)            | Audio device.                                                |
| virtio-gpio     | Y    | N      | N     | No (acrn-kernel)            | gpio sharing over virtio.                                    |
| virtio-i2c      | Y    | N      | N     | No (acrn-kernel)            | i2c devices.                                                 |
| virito-rpmb     | Y    | N      | 28    | No (acrn-kernel)            | Replay Protected Memory Block.                               |
| virtio-mei      | Y    | N      | N     | No (acrn-kernel)            | Intel Management Engine Interface.                           |
| virtio-ipu      | Y    | N      | N     | No (acrn-kernel)            | Imaging Processing Unit.                                     |
| virtio-hyperdma | Y    | N      | N     | No (acrn-kernel)            | Hyper DMA buffer.                                            |
| virtio-hdpc     | Y    | N      | N     | No												  | High-bandwidth Digital Content Protection.                   |
| virtio-coreu    | Y    | N      | N     | No                          | PAVP ( Protected Audio Video Path) session management.       |

<br>


## 二级标题
<br>
图片：
<br>

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
