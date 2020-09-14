---
layout: blog
istop: false
book: false              
road: false            
title: "VS2019+VisualGDB+STM32CubeMx开发stm32程序"
background: red
background-image: https://github.com/wenxin919220/wenxin919220.github.io/blob/master/_posts/%E6%8A%80%E6%9C%AF/2020/14/2020-09-14-VS2019+VisualGDB+STM32CubeMx%E5%BC%80%E5%8F%91stm32%E7%A8%8B%E5%BA%8F_00.png?raw=true
category: Markdown
date: 2020-09-01
tags:
- VS2019
- VisualGDB
- STM32CubeMx
- Stm32
---


# **简介**
在使用过“宇宙最强” IDE——Visual Studio 之后 ，大有“一入VS深似海，眼中唯此IDE”之感。在接触单片机后，对Keil大失所望
亦有“曾经沧海难为水”之叹！于是便萌生了用Visual Studio编写STM32程序的念头。果然兴趣是最好的老师，几经挫折，跨越险阻万难
之后，终于搭建好了开发环境，于此记录过程。

首先需要有以下3个工具：
1. Visual Studio 2019 （2017亦可）
2. VisualGDB （要能够支持Visual Studio 的版本）
   链接：<https://pan.baidu.com/s/1N8vGpmgM6gdL9Imrrhe7Ug>  提取码：1ppj
3. STM32CubeMx
下载及安装过程自行搜索。

# **STM32CubeMx注意项**
1. 首先建立并配置好工程。（不会使用 STM32CubeM 请名自行搜索）【注意】在最后一步要选择


02这是一张图片 ![wenxin][pictutr]


