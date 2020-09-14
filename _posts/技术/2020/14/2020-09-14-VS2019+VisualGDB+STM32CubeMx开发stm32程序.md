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
1. 首先用 STM32CubeM 建立并配置好一个工程。（不会使用 STM32CubeM 请名自行搜索）【注意】在最后一步要选择 **Other Toolchains(GPDSC)**，其他按照一般步骤即可。
![wenxin][pictutr_01]



# ** Visual Studio 2019 的一些配置**




# ** Visual Studio 2019注意项**
1. 在使用 VS 建立工程之前，先要下载并安装 VS的一个插件 VisualGDB。

2. 新建一个工程。注意选择 Embedded Project wizard 
![wenxin][pictutr_02]

3. 注意选择正确的文件夹。
![wenxin][pictutr_03] 

4. 导入gpdsc文件。
![wenxin][pictutr_04]  

5. 选择合适的芯片。
![wenxin][pictutr_05]

6. 仿真配置。(配置完成后，点击finish即可)
![wenxin][pictutr_06]

7. 创建好的项目如下图。
![wenxin][pictutr_07]

8. 继续进行如下配置。
![wenxin][pictutr_08]

9. 
![wenxin][pictutr_09]

10. 
![wenxin][pictutr_10]

11. 配置完成后，点击右下角的 Apply 再点击 OK 即可。

12. 将你的单片机连接好，就可以下载程序了。

[pictutr_01]:https://github.com/wenxin919220/wenxin919220.github.io/blob/master/_posts/%E6%8A%80%E6%9C%AF/2020/14/2020-09-14-VS2019+VisualGDB+STM32CubeMx%E5%BC%80%E5%8F%91stm32%E7%A8%8B%E5%BA%8F_01.png?raw=true

[pictutr_02]:https://github.com/wenxin919220/wenxin919220.github.io/blob/master/_posts/%E6%8A%80%E6%9C%AF/2020/14/2020-09-14-VS2019+VisualGDB+STM32CubeMx%E5%BC%80%E5%8F%91stm32%E7%A8%8B%E5%BA%8F_02.png?raw=true

[pictutr_03]:https://github.com/wenxin919220/wenxin919220.github.io/blob/master/_posts/%E6%8A%80%E6%9C%AF/2020/14/2020-09-14-VS2019+VisualGDB+STM32CubeMx%E5%BC%80%E5%8F%91stm32%E7%A8%8B%E5%BA%8F_03.png?raw=true

[pictutr_04]:https://github.com/wenxin919220/wenxin919220.github.io/blob/master/_posts/%E6%8A%80%E6%9C%AF/2020/14/2020-09-14-VS2019+VisualGDB+STM32CubeMx%E5%BC%80%E5%8F%91stm32%E7%A8%8B%E5%BA%8F_04.png?raw=true

[pictutr_05]:https://github.com/wenxin919220/wenxin919220.github.io/blob/master/_posts/%E6%8A%80%E6%9C%AF/2020/14/2020-09-14-VS2019+VisualGDB+STM32CubeMx%E5%BC%80%E5%8F%91stm32%E7%A8%8B%E5%BA%8F_05.png?raw=true

[pictutr_06]:https://github.com/wenxin919220/wenxin919220.github.io/blob/master/_posts/%E6%8A%80%E6%9C%AF/2020/14/2020-09-14-VS2019+VisualGDB+STM32CubeMx%E5%BC%80%E5%8F%91stm32%E7%A8%8B%E5%BA%8F_06.png?raw=true

[pictutr_07]:https://github.com/wenxin919220/wenxin919220.github.io/blob/master/_posts/%E6%8A%80%E6%9C%AF/2020/14/2020-09-14-VS2019+VisualGDB+STM32CubeMx%E5%BC%80%E5%8F%91stm32%E7%A8%8B%E5%BA%8F_07.png?raw=true

[pictutr_08]:https://github.com/wenxin919220/wenxin919220.github.io/blob/master/_posts/%E6%8A%80%E6%9C%AF/2020/14/2020-09-14-VS2019+VisualGDB+STM32CubeMx%E5%BC%80%E5%8F%91stm32%E7%A8%8B%E5%BA%8F_08.png?raw=true

[pictutr_09]:https://github.com/wenxin919220/wenxin919220.github.io/blob/master/_posts/%E6%8A%80%E6%9C%AF/2020/14/2020-09-14-VS2019+VisualGDB+STM32CubeMx%E5%BC%80%E5%8F%91stm32%E7%A8%8B%E5%BA%8F_09.png?raw=true

[pictutr_10]:https://github.com/wenxin919220/wenxin919220.github.io/blob/master/_posts/%E6%8A%80%E6%9C%AF/2020/14/2020-09-14-VS2019+VisualGDB+STM32CubeMx%E5%BC%80%E5%8F%91stm32%E7%A8%8B%E5%BA%8F_10.png?raw=true













