---
layout: page
title: 用户
---

- [系统管理员](#系统管理员)
	- [租户](#租户)
	- [租户管理](#租户管理)
- [租户管理员](#租户管理员)
	- [客户](#客户)
	- [客户管理](#客户管理)
- [用户](#用户)

用户分为系统管理员，租户管理员和用户三种，分别对应系统结构里的系统，租户，客户三级。

## 系统管理员

只有系统管理员能够创建租户

![](https://raw.githubusercontent.com/haibaoiot/haibaoiot.github.io/master/images/UI-tenant.png)

### 租户

租户为独立的业务实体，即拥有生产设备的个人或组织。

### 租户管理

系统管理员还可在租户详细信息中添加多个不同的**租户管理员**账户

![IMG](https://raw.githubusercontent.com/haibaoiot/haibaoiot.github.io/master/images/ui-tenant-manage.png)

## 租户管理员

租户管理员能够执行以下操作：

1. 添加和管理设备，包括设备的添加、属性的修改、令牌的获取、设备的属性查看、设备的分配、报警信息的查看等。
2. 创建和管理客户。
3. 创建和管理仪表板
4. 配置规则和插件
5. 添加或修改组件库

### 客户

客户即具体的物联网使用实体，企业、个人或组织。

### 客户管理

客户管理包括客户里各个用户的账户管理、设备管理、仪表板管理等。

设备、仪表板只能分配给一个具体的客户，而一个客户可以有多个具体的使用用户。

例如，给某公司出售了使用物联网的十套在线溶解氧监测和控制装备，十套具体的设备、仪表板只能分配给该公司使用，而该公司名下，又有几个不同的用户，可正常通过物联网查看设备

![](https://raw.githubusercontent.com/haibaoiot/haibaoiot.github.io/master/images/ui-customer.png)


## 用户

用户即使用物联网的最终用户，只有查看权，无修改权限。

用户只能查看分配给自己的仪表板

![](https://raw.githubusercontent.com/haibaoiot/haibaoiot.github.io/master/images/home-user.png)