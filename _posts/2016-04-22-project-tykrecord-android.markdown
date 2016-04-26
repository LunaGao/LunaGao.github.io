---
layout: post
title:  篮球技术统计软件专业版
project-type: company
date:   2016-04-22 22:08:32 +0800
startDate: 2015年05月01日
endDate: 至今
role: 项目组长
categories: project
technologies: [Java, REST, Realm, GreenDao]
platforms: [Android]
description: >
  针对体育课App创建的平板篮球技术统计软件。用来代替传统的篮球比赛数据统计方式，使用平板记录，
  并可以实时分析数据结果，与体育课App数据共享。是体育课App的附属软件之一。
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
针对体育课App中的数据统计开发的一套记录软件。主要针对Android平板使用。

### 担任角色
在其中主要担任项目组长及主力开发人员···需求调研以及开发基本全部自己完成。部分简单界面由他人完成。

### 技术难点
主要在读取方面：

- 数据要求实时保存。
- 数据要求即时统计。

总结起来就是对于增改查方面的需求非常大。
所以在设计时对此方面有很多考虑因素，尝试过sqlite，后续使用了greenDao来提升速度。
但由于平板性能（公司没钱买好的），加入了多线程处理业务逻辑等。
在最大情况满足性能的同时保证代码的可维护性。
后续准备将greenDao替换为realm进一步提升性能。
