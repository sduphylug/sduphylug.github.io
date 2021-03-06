---
layout: post
title: linux基本命令介绍
date: 2017-12-17

---

本文主要来介绍一下一些linux最常用的简单命令，让大家对linux的特点有一个初步的了解。

## 本文目录：

* 1 date

* 2 cal

* 3 bc

## date

date用来显示主机现在的时间。主要有一下几种调用方式：

>date

>date +%Y/%m/%d

>date +%H:/%M

具体显示结果如下：

![date.png](https://raw.githubusercontent.com/sduphylug/sduphylug.github.io/master/_posts/_imag/date.png)

## cal

这个指令用来显示日历。主要有以下几种调用方式：

>cal

现实当前月份的日历。

![cal.png](https://raw.githubusercontent.com/sduphylug/sduphylug.github.io/master/_posts/_imag/cal.png)

>cal 年份

显示一年的日历。

![cal2.png](https://raw.githubusercontent.com/sduphylug/sduphylug.github.io/master/_posts/_imag/cal2.png)

>cal 月份 年份

显示具体某年某月的日历。

![cal3.png](https://raw.githubusercontent.com/sduphylug/sduphylug.github.io/master/_posts/_imag/cal3.png)

## bc

bc是一个简单的计算器。不仅可以进行整数的加（+）减（-）乘（*）除（/）和取余（%）运算还可以进行浮点数的运算。进入计算器的命令就是在终端键入bc并回车，
之后光标所在的位置就是输入算式的位置,输入算式回车即可计算，要想推出计算器键入quit回车即可。这个计算器默认保留小数点后0位，所以在进行类似于1/3等类似
的运算时会输出结果为0,所以需要输入一下命令来重置小数点保留的位数：

    scale = 某个数    //这个数就是你需要保留的位数

![bc1.png](https://raw.githubusercontent.com/sduphylug/sduphylug.github.io/master/_posts/_imag/bc1.png)

其实在bc调用时就可以通过添加一个 -l参数来改变小数点后的精确位，-l的作用之一是把小数点后的精确位设为20，之二是使得计算器能够计算一些简单的函数：

>s(x)   //正弦函数

>c(x)   //余弦函数

>l(x)   //以2为底的对数函数

>a(x)   //反正切函数

>e(x)   //e指数

>j(x)   //贝塞尔函数

![bc2.png](https://raw.githubusercontent.com/sduphylug/sduphylug.github.io/master/_posts/_imag/bc2.png)
