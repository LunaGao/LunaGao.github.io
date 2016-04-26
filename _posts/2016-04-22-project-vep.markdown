---
layout: post
title:  珠海职教平台
project-type: company
date:   2014-06-06 22:08:32 +0800
startDate: 2014年04月01日
endDate: 2014年09月02日
role: 程序员
categories: project
technologies: [.net, Java, Object-C]
platforms: [Web, Android, iOS]
description: >
  珠海职教平台。主要为珠海市职业教育学生毕业后寻找工作开发。其中涉及发布岗位，发布课程，用户登录等功能。
  涉及有网页端和移动端两大块。
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
在整个项目中负责移动端iOS开发以及服务器端的接口开发。
