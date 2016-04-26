---
layout: post
title:  合同管理系统
project-type: company
date:   2014-07-10 22:08:32 +0800
startDate: 2014年07月10日
endDate: 2014年10月30日
role: 开发组长
categories: project
technologies: [.net, SQLServer]
platforms: [Web]
description: >
  主要客户为香港地铁（深圳），针对其所有签署的合同、财务的整个管理平台。
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
整个项目中在担任开发组长，主要负责需求调研、开发任务分配和进度管理。
