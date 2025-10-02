---
title: gflags
date: 2021-03-11 07:40:22
tags:
excerpt: Google gflags命令行参数解析库使用指南，包括flag定义、参数解析、命令行设置、默认值修改等核心功能的使用方法。
---
主要介绍google gflags使用

# 常见用法
## 定义flag
一般.cc中定义flag，.h进行声明，其他包含该.h的文件就可以使用.cc定义的flag变量。
## flag与参数解析
```
gflags::ParseCommandLineFlags(&argc, &argv, true); 
```
告诉程序处理命令行传入参数。最后一个参数为remove_flags，值为true，会移除相应flag和对应值并且修改argc值，argv只保留命令行参数；值为false，会保持argc不变，会调整argv中存储的内容顺序，flag放命令行参数前面。
## 命令行设置flag
## 更改flag默认值
## 