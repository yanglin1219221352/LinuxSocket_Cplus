﻿
# LinuxC++ 高并发网络编程【高性能静态网络服务器 一步步搭建过程】

编译环境：

	socket14(静态服务器)之前使用ubuntu18.04等环境均可

	socket14(静态服务器)使用ubuntu14.04 g++4.8 进行编译

该项目专注于Linux c++网络服务器的开发，通过学习能够了解到相关linux c++后台相关知识 提高c++开发能力

linux c++ 后台开发(高并发静态服务器的搭建)

从简单客户端到后台静态服务器的搭建

逐步深入了解select poll epoll网络模型 逐步了解其优缺点

常用epoll ET + NONBLOCKING 模式

在静态服务器中加入线程池服务 有助于提高高并发

socket13是实现的一个简单的静态库服务器 使用的是c语言写的，结构很简单 易于理解

c++实现：(在测试时需要指定访问的文件 或者 目录， 由于源代码中指定的目录是根据我的电脑设置的，如果需要测试需要在自己电脑上设置访问路径)

socket14可以在先学习socket13的基础上来学习
socket14中分为了6个版本，v0.6版本启动myserver时需要进入root权限
每个版本都较前一个版本有了更新 在socket13的基础上加入了线程池，定时器，请求任务队列，同时加入了RALL锁，智能指针，非拷贝赋值类；
将epoll 等用类进行封装，socket14是用c++语言实现的。

---------------------------------------------------------------------------

最新章节正在更新当中........