---
layout: post
title:  随随便便
project-type: personal
date:   2014-03-10 22:08:32 +0800
startDate: 2014年03月10日
endDate: 2014年04月30日
role: 开发者
categories: project
technologies: [Java]
platforms: [Android]
description: >
  主要用做随机生成硬币正反面、方位、列表选项、骰子。是选择困难症患者的福音~哈哈。
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
个人项目，独立完成。

### 技术难点
各种随机数的算法。

### 使用量
从2014年04日30起，截止2016年04月25日，下载量1272次。
数据来自[百度手机助手][baidu-web]。

### 下载地址
[百度手机助手][download]


[download]:http://shouji.baidu.com/game/4155776.html
[baidu-web]:http://shouji.baidu.com/game/4155776.html
