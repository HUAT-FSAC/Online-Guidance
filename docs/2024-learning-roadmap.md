---
layout: default
title: 2024 预备队员无人系统部队员学习计划
nav_order: 6
---

# 2024 预备队员无人系统部队员学习计划

欢迎来到 HUAT FSAC 无人系统部👏，在这里开始你的第一步学习吧。  


## 1. 基础环境配置

首先我们从接触全新的系统环境开始,在虚拟机平台上安装Ubuntu,熟悉基本的命令行接口(CLI)操作。同时,学习浏览器、集成开发环境(IDE)的安装以及代理的使用。熟练使用命令行是后续工作的基础。

### 1.1 Linux（Ubuntu）系统的安装

#### VMWare

一部分网上资源较多，推荐参考<https://cloud.tencent.com/developer/article/2062275>的指南。


{: .highlight }
> - Ubuntu 系统要求/建议安装为 Ubuntu LTS 18.04，避免影响后续操作；
> - VMWare Workstation 的版本并不严格要求，16/17/18都是可以的；
> - 我们提供 Ubuntu 镜像的网盘下载（快于官方网站）[链接🔗](https://www.123pan.com/s/Cff7Vv-mQ6nH.html) 
> - 你可以在[这里](https://www.vmware.com/go/getworkstation-win)下载 VMWare 虚拟机最新版本

#### 🌟 WSL2（推荐）

如果你的电脑系统为 Windows 11 或 Windows 10 较新版本，可以考虑使用 Windows Subsystem for Linux 来创建虚拟机。

相比 VMWare 它具有以下优势：
- 无需 2.xG 的镜像文件
- 启动快
- 安装/卸载方便
- 与 Windows 融合度高
- ...

你可以自行参考以下链接来进行 WSL2 Ubuntu 18.04 的安装

[1] <https://zhuanlan.zhihu.com/p/377263437>  
[2] <https://sspai.com/post/74167>  
[3] <https://zhuanlan.zhihu.com/p/348813745>  
[4] <https://blog.csdn.net/qq401195092/article/details/133717025>  
[5] <https://blog.csdn.net/microsoft_mos/article/details/123627295>  

### 1.2 Linux 命令行操作

尽管现代 Linux 操作系统大多都搭配的方便易用的 GUI 图形界面，但是对于开发来说快速便捷的 CLI 指令依然是必不可少的得力助手。

#### 我应该在哪里输入命令？

在你已经启动了的 Ubuntu 系统桌面上：

- 按下键盘上的 ctrl 和 alt 和 T 键；
- 按下 windows 键并输入 terminal 最后按回车键；

就会打开 Ubuntu 的命令行窗口，从这里输入你的命令就好。

#### 什么是命令，有哪些，我要怎么学习？

由于能力限制，我们无法在这里直接讲述开发中最常见的 Linux 命令及如何学习/使用他们。但是可以把[这份教程](https://www.freecodecamp.org/chinese/news/command-line-for-beginners/)推荐给你。

{: .note }
另外我们也支持你自己在搜索引擎上搜索不同的命令或者在虚拟机上亲手看看他们如何工作，毕竟**耐心与兴趣**是最能保持你对代码开发的热情的。

## 2. 编程语言基础概念

接下来学习并熟悉C/C++基础语言框架,掌握基础代码查错技巧,深入学习cmake并理解其运行机制。C++是ROS主要使用的编程语言,对其有基本的了解非常重要。

## 3. git使用

学习理解并尝试使用git进行代码管理。在团队协作中,使用git管理代码是必不可少的技能。

## 4. ROS架构熟悉

1. 安装ROS Melodic并成功运行ros turtle_sim。
2. 创建ROS工作空间，包括创建包和编译运行hello_world程序。
3. 通过这上面步骤，熟悉ROS的基本架构，包括ROS节点及其通信机制。

## 5. Github使用 

注册并加入HUAT-FSAC组织,可以获得团队协作资源。

## 6. FSSim

最后尝试运行FSSim,实际操作一个机器人仿真环境,为后续真实机器人做准备。

通过以上学习步骤，你将逐步掌握机器人操作系统ROS的基础知识，为后续的进阶学习奠定坚实基础。实践是提升技能的关键，因此请在学习的同时多进行练习，以加深对所学知识的理解。
