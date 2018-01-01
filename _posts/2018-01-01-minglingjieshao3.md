---
layout: post
title: linux基本命令介绍（三）
date: 2018-1-1

---

当我们使用一个操作系统时，我们最常使用的操作时什么呢，我想应该是对文件的操作。对文件的操作主要有如下几类：

* 复制
* 移动
* 创建
* 删除

那么如何用命令行实现呢。下面将具体进行介绍。

## 复制文件或目录：cp

cp为复制命令，它有两种使用方法：

    cp item1 item2
    
这个名令将单个文件或目录item1复制到文件或目录item2中。

    cp item1... directory
    
这个命令是将多个文件或目录复制到统一目录下。

## 移动或重命名文件：mv

mv命令可以移动或重命名文件，这取决于你怎样使用它。他和cp用法相似。

    mv item1 item2
    
这个命令将item1移动或重命名为item2.

    mv item1... directory
    
这个命令把多个文件移动到同一目录下。

## 创建目录：mkdir

    mkdir directory...
    
可以同时创建多个目录。

## 删除文件或目录：rm

    rm item1...
    
可以同时删除多个文件或目录。