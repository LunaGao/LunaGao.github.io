---
layout: post
title:  微课网站
project-type: company
date:   2014-09-30 22:08:32 +0800
startDate: 2014年08月20日
endDate: 2014年09月30日
role: 项目组长
categories: project
technologies: [Node.js, MongoDB]
platforms: [Web]
description: >
  针对珠海的微课分享平台。针对互联网时代的混合学习、移动学习、碎片化学习的新型学习方式而产生。
  当时开发时预估需要有手机平台，但后续因为个人原因离职，没有继续跟进此项目。
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
