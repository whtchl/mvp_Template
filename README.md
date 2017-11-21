# mvp_Template

mvp_template 是一个MVP框架的快速开发框架。

这里的有三个demo使用了这个框架：一个是szx2，一个是znpos，一个是pad(这个内容是空的)。

mvpbeam是mvp框架

server是访问网络的。用的是okhttp，retrofit

hardware是不同硬件设备的

config是配置文件

common是公共包

model中模型模块

szx2（znpos，pad）是activity和presenter组成

========================================

用到的包bufferknife，rxandroid

==========================================

结构

<img src="https://raw.githubusercontent.com/whtchl/mvp_Template/master/art/1.png"/>

======================================

hardware（应为是不同厂家提供的demo）和 UI通讯是没有用到上面的框架。他们之间通讯是用的是broadcast。后期改为用eventbus
 
