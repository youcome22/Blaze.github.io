---
title: IDEA配置与使用
date: 2025-02-19
updated:
tags: development tool
categories: Tools
keywords:
description:
top_img: 
comments: true
cover: 
toc:
toc_number:
toc_style_simple:
copyright:
copyright_author: blaze
copyright_author_href:
copyright_url:
copyright_info: 
mathjax:
katex:
aplayer:
highlight_shrink:
aside:
abcjs:
noticeOutdate:
---



# IDEA

## IDEA介绍

1.IDEA 全称 Intellij IDEA

2.在业界被公认为最好的Java开发工具

3.IDEA是 JetBrains 公司的产品，总部位于捷克首都布拉格

4.除了支持Java开发，还支持HTML、CSS、PHP、MySql、Python等



## Eclipse介绍

1.Eclipse 是一个开放源代码的、基于Java的可扩展开发平台

2.最初由IBM公司耗资3000万美金开发的下一代IDE开发环境

3.2001年11月贡献给开源社区

4.Ecilips是目前最优秀的Java开发IDE之一



## IDEA常用快捷键

1.删除当前行，默认Ctrl+Y，可配置为Ctrl+D

2.复制当前行，配置为Ctrl + Alt + 向下光标

3.补全代码 Alt+ /

4.添加注释和取消注释 Ctrl + /

5.导入改行需要的类，先配置auto import ，然后使用Alt + Enter

6.快速格式化代码 Ctrl + Alt + L

7.快速运行，自行定义 Ctrl + R

8.生成构造器/构造法方法 Alt + insert

9.查看一个类的层级关系 Ctrl + H 

10.将光标放在一个方法上，输入Ctrl + B ，可以定位到方法

11.自动分配变量名，通过后面+ .var



## 断点调试（Debug）

断点调试是指在程序的某一行设置一个断点，调试时，程序运行到这一行就会停住，然后你可以一步一步往下调试，调试过程中可以看各个变量当前的值，出错的话，调试到出错的代码行即显示错误，停下，继而分析找到Bug

断点调试可以帮助我们查看 Java 底层源代码的执行过程，提高开发者 Java 水平



### 断点调试快捷键

在Setting --> Build,Execution,Deployment --> Debugger --> Stepping , 取消勾选 java.*，javax.*

F7 (Step Into)：跳入方法内

F8 (Step Over)：逐行执行代码

shift + F8 (Step Out)：跳出方法

F9 (resume)：执行到下一个断点

alt + shift + F7  (force step into)：强制进入方法 

