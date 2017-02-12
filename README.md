# Awesome Kernel

## 简介

本项目的名字受到了[ awesome 系列项目](https://github.com/sindresorhus/awesome)的启发。

在我自己学习内核的过程中，遇到了很多问题，也找到了很多资料，这些资料大部分躺在我的网页收藏夹里，时间一长里面就杂乱不堪，长长的网址列表使我没有再去看第二眼的欲望，所以我打算将各种资料整理一下发到 GitHub，一是为了我自己查阅方便，二也是为了能够帮到同样有疑问的人。为了简洁起见也为了保护原作者的权利，所有资料都用超链接指向原文。

# 目录

* [内核社区](#内核社区)
* [内存管理子系统](#内存管理子系统)
	* [内存初始化](#内存初始化)
	* [内存映射](#内存映射)
	* [伙伴系统](#伙伴系统)
	* [内存分配](#内存分配)
	* [内存回收和页面交换](#内存回收和页面交换)
	* [反向映射](#反向映射)
	* [内存共享](#内存共享)
	* [其他资料](#其他资料)
* [其他子系统待添加]()

---

## 内核社区

[Kernel Newbies](http://kernelnewbies.org/)

[Linux Kernel Mailing List Archive](https://lkml.org/)

[Kernel Mailing List Information](http://vger.kernel.org/)

[OSDev Wiki](http://wiki.osdev.org/Main_Page)

## 内存管理子系统

### 内存初始化

[内核的 Bootmem 内存分配器](http://blog.csdn.net/zmxiangde_88/article/details/8041040)

### 内存映射

[Linux 的固定映射的线性地址](http://blog.csdn.net/jacksen1026/article/details/2565398)

### 伙伴系统

[浅析 Linux 内核内存管理之 Buddy System](http://blog.csdn.net/hsly_support/article/details/7483113)

[关于 Buddy（伙伴）算法的讨论](http://blog.csdn.net/zhongnanjun_3/article/details/21799209)

[浅析 armlinux-Buddy (伙伴)算法-释放合并回收函数__free_pages_ok()](http://blog.chinaunix.net/uid-20564848-id-72856.html)

### 内存分配

[Kernel 那些事儿之内存管理(5) --- 衣带渐宽终不悔（上）](http://richardguo.blog.51cto.com/9343720/1670302)

### 内存回收和页面交换

[Linux 内存页面定期换出](http://memorymyann.iteye.com/blog/208583)

[mm/vmscan.c 分析](http://blog.chinaunix.net/uid-10701701-id-91784.html)

[Linux 内存管理--内存回收](http://blog.csdn.net/wenwuge_topsec/article/details/9998417)

[Linux内存管理之页面回收](http://blog.csdn.net/bullbat/article/details/7311205)

### 反向映射

[Linux 2.6 内存反向映射机制 Reverse Mapping](http://www.cnblogs.com/visayafan/archive/2011/12/24/2300758.html)

[Linux 内存管理--内存回收](http://blog.csdn.net/wenwuge_topsec/article/details/9998417) - 关于匿名页的反向映射讲得很清晰

[Linux 内核 Priority Search Tree 详解](http://bbs.chinaunix.net/forum.php?mod=viewthread&tid=2308502&page=1) - 手绘的示意图，讲解很清晰

[PST 优先搜索树原理及在 Linux 内核中的应用浅析](http://www.cnki.com.cn/Article/CJFDTotal-DNBC201213018.htm) - 对 PST 的讲解清晰到可怕

[基数树原理及在 Linux 内核中的应用分析](http://www.cnki.com.cn/Article/CJFDTotal-DNBC201317009.htm)

[Linux 中的优先搜索树的实现](http://blog.csdn.net/dog250/article/details/5700317)

### 内存共享

[关于 Linux 内核 fork 后 cow (写时复制)的代码分析](http://www.oschina.net/question/234345_48023)

### 其他资料

[Some existing documentation on Linux Memory Management](https://landley.net/writing/memory-faq.txt)

[Understanding the Linux Virtual Memory Manager (by Mel Gorman)](https://www.kernel.org/doc/gorman/html/understand/)

---

# License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
