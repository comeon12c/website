﻿+++
title = "知识管理"
description = "便捷的项目协作平台和强大的项目内容管理平台"
weight = 2
+++

## 使用 Choerodon 知识管理

欢迎使用 Choerodon 猪齿鱼知识管理用户手册，知识管理服务是一个轻量级的强大Wiki平台，允许用户根据自己的特定需求自定义Wiki，为企业、IT团队提供方便的项目协作平台和强大的项目内容管理平台，集中式管理产品相关内容等，例如需求收集、架构设计、功能设计、开发规范、命名规范、会议记录、计划安排等。

![enter description here](/docs/user-guide/wiki/image/wiki.png)

如果您是项目成员和项目管理员，这些文档将对您有用。本节将围绕Wiki管理各个功能进行详细的介绍，包括 **空间**、**页面**、**权限**、**系统管理**，将涵盖您使用Choerodon猪齿鱼Wiki过程中所有可能进行的操作。


## 基本概念

### **WiKi**

Wiki是一种内容管理系统，具有编辑、导航、链接和创建页面、搜索等功能。优势在于其灵活性以及添加和链接新页面的便利性。

出于其灵活性和易用性，Wiki可用于解决以下情况：

- 知识沉淀——沉淀软件开发过程中的需求、设计、规范等知识文档。

- 项目协同——有效管理项目中的计划安排，会议记录等，加强项目成员之间的合作。

- 产品文档——便捷地编写软件产品的概念说明、用户手册、快速入门等产品文档。

- 培训教材——方便地编写软件功能使用等培训材料，甚至视频教程等。

### **空间**

空间相当于一个分组，页面隶属于空间之下。空间和页面有两个主要属性，名称（name）和标题（titile），Name是唯一标识，用做相互关联。Title是页面或空间的显示标题，用作显示。

### **页面**

页面是Wiki中的基本内容单元，如果当前用户有权限时，可以在任何Wiki页面上执行以下操作：

- 编辑页面
    - 使用WYSIWYG编辑器：这是一个富文本编辑器，允许您轻松修改Wiki页面的内容
    - 使用Wiki编辑器：适用于习惯于使用标记语法编写的用户
- 使用“更多操作”菜单打印并导出页面
    - 用户可以显示当前页面的打印预览
    - 每个页面都可以采用以下格式导出：HTML，PDF，RTF（适用于MS Office）和XAR（XWiki Archive）
- 观看页面
    - 用户可以选择将当前页面添加到他的监视列表中
    - 每当页面被修改时，他都会收到一封电子邮件通知

### **模块**

模块是Wiki提供的页面和空间的编辑模板，模板有多种类型可供选择，包括：会议报告、表单和敏捷会议记录等。

## 快速开始

 - 如果您是第一次使用接触Wiki知识管理，在学习阅读本章节之前，请阅读[快速入门手册](../../quick-start/)。
 - 如果您对wiki知识管理已经非常熟悉，请使用文档搜索功能，查找您需要了解的内容。

## 前置条件

 - wiki知识管理是基于项目的，在使用Choerodon知识管理之前，需要先了解和学习[Choerodon的项目管理](../../quick-start/admin/project)。
 - 系统用户必须具有`项目所有者`，或者`项目成员`角色，才能是使用知识管理服务。所以，在使用知识管理之前，您需要为您的用户分配`项目所有者`，或者`项目成员`角色。关于权限管理，请参阅[项目角色分配](.././system-configuration/project/role-assignment/)。


## 权限了解
1.`项目管理员`拥有以下权限：

| 模块 | 操作    |
| -------- | ----- |
| 空间        | 收藏、分享、管理(主要设置访问该空间以及子页面的权限)、复制、移动、删除、导出、邮件分享      |
| 页面        | 创建、编辑、评论、收藏、分享、管理(主要设置访问该页面以及子页面的权限)、复制、移动、删除、导出、显示注释、邮件分享     |
|管理权限设置  | 查看、评论、编辑、删除、脚本运行、管理员 |
|页面外观设置|  主题、面板编辑、显示 |

2.`普通成员`拥有以下权限：

| 模块 | 操作    |
| -------- | ----- |
| 空间        | 收藏、分享、复制、导出、邮件分享      |
| 页面        | 创建、编辑、评论、收藏、分享、复制、删除(自己创建的页面可以删除)、导出、显示注释、邮件分享     |

  > 注：`普通成员`对页面查看、评论、编辑、删除、脚本运行和管理员的权限，是可以由`项目管理员`或者更高的权限在管理里面进行设置的。

## 视频介绍

{{< tutorial wiki overview>}}

## 功能概述

以下将围绕知识管理各个功能的使用进行详细的介绍，包括  **空间**、**页面**、**权限**、**系统管理**。

- [**空间**](./space) ：空间相当于一个分组，可以包含很多个页面。

- [**页面**](./page) ：页面是Wiki中的基本内容单元，作为内容的承载。

- [**权限**](./hierarchy) ：管理员可以针对不同小组和用户配置每个空间和页面的权限。

- [**系统管理**](./system-management) ：对Wiki系统的功能，权限，用户等进行自定义设置。