# QEMU-Tool-Box
A program that helps users use the QEMU command

一个帮助用户使用QEMU命令的程序

## 关于项目
使用C语言编写，历时几个月

其中包括：学习C语言->了解QEMU命令->编写程序 的时间（还有学业繁忙没有更新的时间）

项目使用了两种方法：`If-else`和`swich-case`（我在这里暂时称为sc版） 
由于其复杂，if-else用法已经废除，想去看看的话，也算了吧😂

## 项目开发
swich-case用法经历了两个时期：无函数->函数控制。

或许用词不是很标准，就是一开始的sc版的大部分代码是通过copy-paste来实现的。但是由于此类代码不好维护，以及可读性感觉不太好，于是定义了一个函数进行输出判断控制

这个项目其实并没有使用其他比较难的东西，只有输入、输出、判断，来来去去也就是scanf, printf, swich-case这三个

代码中或许有一些非常幼稚的想法，或许会有一些完全没有必要但是我还是使用了的方法来实现某个功能的

还请大佬纠错～～

## 编译项目

1. gcc in program's root dir
    ```bash
    gcc main.c
    ```


## 开发历程

2020.3 开始开发项目

2020.4 学习C语言中……

2020.5 完成基本的判断输出（if-else）

2020.6 废除if-else，转用swich-case语句

2020.7～10 上学学业繁忙，并没有顾及此项目了

2020.11 使用了函数控制，代码维护性增加

2020.12.6 建立GitHub仓库

2021.1.1 新增了hvf启动方式
