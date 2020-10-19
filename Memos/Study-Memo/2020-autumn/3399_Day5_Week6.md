## 制造工程体验课程报告

姚昱臣 2019013399 Day4 Week5 10.12

***

关于树莓派与python



***树莓派的历史***

树莓派概述：Raspberry Pi（Ras Pi）：开源的硬件，基于linux系统。一款从教育目的开发的硬件系统，功能类似于电脑主机，可以有很多种玩法。

历史：源于Raspberry Pi基金会，2006年树莓派早期概念是基于Atmel ATmega644单片机

*树莓派的surprise*

​    1.支持linux，软件基础优

​    2.GPIO硬件模块，支持python的GPIO库

​    3.支持无线网卡

应用：智能家居（智能咖啡机，智能喂猫器等）



***树莓派的配置与相关网址***

今天使用的树莓派型号是3代B型。1.4GHz主频的基于ARM的处理器，1G的内存，配备16G的SD卡作为存储空间。有4个USB接口、两个miniHDMI接口、支持无线网卡等。充电通过microUSB接口。

树莓派官网          www.raspberrypi.org

 国内树莓派论坛  www.shumeipai.nxez.com

iCenter的树莓派   用户名：pi    密码：    raspberry



***树莓派的简单应用***

通过SSH（putty）远程登陆树莓派，并用VNCviewer图形化软件操作。

使用树莓派和面包板，拼接普通的电路实现一些简单控制。

讲解包括：GPIO各个引脚命名和简介；面包板电路连接方式简介

task1. 亮呼吸灯:使用一个二极管（+电阻），在树莓派中的python编译环境thonny上编简单程序实现

task2. 按键亮灯：实现按键亮灯

task3. 二进制加法器：实现亮灯（2个）的样式与按键的次数相符合



***python小游戏：乌龟赛跑***

使用python的turtle库，画一些可爱的图形hhh（乌龟赛跑）