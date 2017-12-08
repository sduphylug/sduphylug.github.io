---
layout: post
title: linux使用交流会
date: 2017-12-08
---
# linux使用交流会
距离上次新安装系统已经过去一星期了,在今天(12.08)小组成员们又汇聚一堂,交流ubuntu 17.10 的使用情况。

1. 首先，老用户们先查看了上周新装系统的运行状况。确认运行正常。
2. 接下来，成员们又讨论交流了ubuntu上的一些常用软件，并向新用户介绍了常用的安装程序的方法。

几个常用的软件及其安装方法：
* ### [git](https://git-scm.com/)
>Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
</br>
>`Git是一款免费、开源的分布式版本控制系统，用于敏捷高效地处理任何或小或大的项目。`

安装方法（Ubuntu）：
``` shell
sudo apt update
sudo apt install git
```
安装过程中需要输入密码。
* ### [gcc](https://gcc.gnu.org/)

gcc是一个著名的编译器。
安装方法（Ubuntu）：
``` shell
sudo apt update
sudo apt install git
```
简单介绍一下使用方法：
``` shell
nano hello.c
```
``` C
#include <stdio.h>
int main()
{
    printf("%s\n","hello world!");
    return 0;
}
```
保存退出后退出
``` shell
gcc hello.c -o hello
./hello
```
输出：
``` shell
hello world!
```
此次活动的图片：

![图片正在加载中](https://raw.githubusercontent.com/sduphylug/sduphylug.github.io/master/_posts/_imag/223.jpg)