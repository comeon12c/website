+++
title = "仪表盘配置"
weight = 6
description = "仪表盘配置用于预置用户可见的仪表盘卡片"
+++

# 仪表盘配置

仪表盘用于显示主要概览信息。根据不同层级、不同组织或项目、不同用户，仪表盘会展现不一样的信息。仪表盘配置可用于配置用户仪表盘的可见卡片。

- **菜单层次**：全局层
- **菜单路径**：平台设置 > 仪表盘配置
- **默认角色**：平台管理员

## 仪表盘配置列表

仪表盘由一系列不同内容得卡片组成。这些卡片的列表信息如下：

- 卡片名称：卡片的名称 ，用以对卡片的说明。
- 编码：卡片的编码，是卡片的标识，具有唯一性。
- 图标：卡片左上角显示的图标，一般与卡片的主要内容相符合。
- 标题：卡片的标题，一般以卡片的主要内容命名。
- 层级：卡片的层级，卡片分为项目层、组织层、无层级三种情况。为项目项目层时，卡片只在进入项目后显示；为组织层时，卡片只在进入组织后显示；无层级时，卡片将在所有仪表盘界面显示。
- 状态：状态有启用和停用两种。当启用状态为启用时，用户可以在主页看到此卡片；当启用状态为停用时，用户不能在主页看到此卡片。


## 修改卡片

- 点击列表中`修改`→![修改](/docs/user-guide/system-configuration/platform/image/update.png) 进行自设目录的修改编辑。

- 卡片的编码、层级不可以修改。卡片的标题、图标、描述可以进行修改。

- 是否开启`角色控制`。
当您选择开启角色控制，选择对应的卡片角色。比如您选择平台管理员角色，那么只有拥有平台管理员角色的用户才能看到此卡片。
当您选择关闭角色控制，那么所有用户都可以看到此卡片。

- 点击保存完成修改。


## 启用/停用仪表盘

- 停用仪表盘：点击列表中`停用`→![停用按钮](/docs/user-guide/system-configuration/platform/image/stop_button.png)，仪表盘状态变为停用状态。仪表盘的启用状态为启用时，可进行停用仪表盘的操作。停用仪表盘后，仪表盘的启用状态变为停用，用户将不能在主页看到此仪表盘。
- 启用组织：点击列表中`启用`→![启用按钮](/docs/user-guide/system-configuration/platform/image/start_button.png)，组织状态为启用状态。组织的启用状态为停用时，可进行启用组织的操作。启用组织后，组织的启用状态变为启用，可进入该组织进行组织的用户管理、项目管理等操作。

## 更多操作
- [菜单配置](../menu_configuration)
- [角色管理](../role)
- [Root用户设置](../rootuser)
