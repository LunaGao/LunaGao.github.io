---
layout: post
title:  飞康温度检测
project-type: company
date:   2015-09-22 22:08:32 +0800
startDate: 2015年09月22日
endDate: 2016年05月20日
role: 项目组长
categories: project
technologies: [Object-C, Java, BlueTooth, LeanCloud]
platforms: [Android, iOS]
description: >
  飞康温度检测。与硬件相连接，获取硬件上的温度数据。
---
***

#### 使用技术
> {% for technology in page.technologies %} __{{technology}}__ __,__{% endfor %}

#### 平台
> {% for platform in page.platforms %} __{{platform}}__ __,__ {% endfor %}

#### 项目时间
> __{{page.startDate}}__ - __{{page.endDate}}__

#### 角色
> __{{page.role}}__

#### 项目类型
> {% if page.project-type == "company" %}__公司项目__{% else %}__个人项目__{% endif %}

***

### 简介
{{page.description}}

### 担任角色
在其中主要担任项目组长，安排开发工作和界面设计，和需求方进行需求沟通。并解决一些技术难点。

### 技术难点
主要在蓝牙连接和端口方面：

- 硬件需要经常轮询进行连接获取数据。

### 总结经验
凡是设计到 __软硬件联调__ 的项目，开发周期要 __3倍__ ，必要时 __4倍__ 或者 __5倍__ 都可以···
