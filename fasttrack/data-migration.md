---
title: 数据迁移
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 8/18/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack 可以帮助你将源环境中的邮件和文件数据迁移到 Office 365（Exchange Online、SharePoint Online 和 OneDrive for Business）。 我们提供的帮助类型取决于你的 Office 365 许可证数量。
ms.openlocfilehash: b046873cfca76ad29105e09e0a3f9355434ec95f
ms.sourcegitcommit: 71ec2c25b514f3a21ed58ca3499af1576e8f2c8d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/18/2021
ms.locfileid: "58392365"
---
# <a name="data-migration"></a>数据迁移

FastTrack 可以帮助你将源环境中的邮件和文件数据迁移到 Office 365（Exchange Online、SharePoint Online 和 OneDrive for Business）。

我们提供的帮助类型取决于你的 Office 365 许可证数量：

  - **对于具有 150-499 个许可证的 Office 365 租户**：FastTrack 仅提供迁移指南；你负责执行数据迁移。 我们将指导你阅读文档，以帮助你计划和使用免费工具来执行自助服务迁移。
  - **对于具有 500 个或更多许可证的 Office 365 租户**：FastTrack 提供迁移指南和数据迁移服务。 我们提供指导，以帮助你计划迁移、配置源环境和 Office 365 租户，并利用我们的数据迁移服务来迁移数据。 你可以创建和安排迁移事件。 我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。

> [!NOTE]
> 如果你在 2017 年 9 月 1 日之前购买或续订了商业计划，则只需 150 个许可证即可获得数据迁移服务的资格。 对于教育计划，只有付费教职员工许可证才有资格获得数据迁移服务。

### <a name="considerations"></a>注意事项

  - 你的源环境必须满足特定的期望才能将数据迁移到 Office 365。 有关 Exchange、SharePoint 和 OneDrive for Business 的源环境期望的更多信息，请参阅[产品和功能](products-and-capabilities.md)。
  - 我们需要对你的源环境和 Office 365 租户具有适当的访问权限和权限才能提供数据迁移服务。
  - 我们的数据迁移服务并非为满足特殊法律或法规要求的数据而设计或以此为目的。 我们迁移数据时，可将其传输到我们维护设施的任何位置、从中进行存储和处理（除非为你的 FastTrack 迁移项目提供了其他位置）。
  - 我们无法保证邮件或文件的迁移速度。
  - 不可预见的问题（例如源环境中不可读或损坏的项）可能会阻止我们迁移某些数据项。
  - 我们无法控制的外部因素（例如对第三方应用程序编程接口 (API) 的更改）可能会导致我们的数据迁移服务发生更改、延迟或暂停。

### <a name="migration-service-availability"></a>迁移服务可用性

  - **对于商业和英国政府客户：** 我们每周七 (7) 天，每天 24 小时 (24x7) 提供数据迁移服务。
  - **对于美国政府/DOD 客户：** 我们每周五 (5) 天，每天 24 小时 (24x5) 提供数据迁移服务。

## <a name="migration-to-exchange-online"></a>到 Exchange Online 的迁移

当你选择使用 FastTrack 将电子邮件迁移到 Exchange Online 时，我们将提供迁移指南和数据迁移服务。 我们提供指导，以帮助你计划迁移、配置源环境和 Exchange Online，并利用我们的数据迁移服务来迁移邮箱。 你可以创建和安排迁移事件。 我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。 迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源邮箱中的的邮件已迁移到 Exchange Online。

### <a name="considerations"></a>注意事项

  - 迁移前，必须完成 Exchange Online 的FastTrack 核心载入；
      - 如果你自行执行载入，则必须通过必需的检查和先决条件。 有关详细信息，请参阅[产品和功能](products-and-capabilities.md)。
  - FastTrack 仅迁移到活动的 Office 365 邮箱。
  - 如果要从本地 Exchange 环境迁移，则必须满足特定要求。 有关详细信息，请参阅[配置混合部署先决条件](https://go.microsoft.com/fwlink/?LinkId=787528)。
  - 每个源环境都必须处于源环境中相应产品的最新服务包 (SP) 和汇总更新 (RU)/累积更新 (CU) 级别。
  - 位于本地 Active Directory 中的通讯组列表（*MailEnabledGroup* 对象）和外部联系人（*MailEnabledContact* 对象）不是邮箱数据迁移的一部分。 但是，你可以使用 Azure Active Directory (Azure AD) Connect 将它们同步。 

## <a name="source-environments"></a>源环境

我们的数据迁移服务从以下源环境迁移数据：

  - 具有单个或多个 Exchange 组织的单个或多个 Active Directory 林（每个 Exchange 邮件系统均须为 Exchange 2010 或更高版本）。
  - 一个支持 IMAP 的电子邮件环境。
  - G 套件环境（仅限 Gmail、联系人和日历）

下表显示了特定于每个源环境的迁移详细信息：

<table>
<thead>
<tr class="header">
<th><strong>源环境</strong></th>
<th><strong>迁移类型</strong></th>
<th><strong>迁移内容</strong></th>
<th><strong>不迁移的内容</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong><br />
<br />
<strong>注意：</strong>有关本地部署Exchange，请参阅混合<a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">部署先决条件</span></a>。</td>
<td>使用混合部署进行的迁移</td>
<td><ul>
<li>电子邮件</li>
<li>服务器端邮箱规则</li>
<li>代理</li>
<li>邮箱联系人 </li>
<li> 日历 </li>
<li> 任务 </li>
<li> 权限管理的电子邮件 </li>
<li> 加密电子邮件 </li>
<li> 签名 </li>
<li> 与用户的邮箱一起迁移的个人存档 </li>
<li> 可恢复的项目 </li>
</ul></td>
<td><ul>
<li> 公用文件夹 </li>
<li> 超出邮件大小限制的所有电子邮件 </li>
<li> 日记存档或任何第三方存档解决方案 </li>
<li> 被阻止的用户或非活动用户 </li>
<li> 来自个人存储表 (PST) 文件的存档数据 </li>
<li> 已损坏的项目 </li>
<li> 非活动邮箱 </li>
<li> 客户端邮箱规则</li>
</ul></td>
</tr>
<tr class="even">
<td><strong>G 套件环境（仅限 Gmail、联系人和日历）</strong><br />
<br />
<strong>注意：</strong> G 套件环境必须满足执行 G 套件迁移 <a href="/exchange/mailbox-migration/perform-g-suite-migration">中所述的先决条件</a>。</td>
<td>直接转换或暂存</td>
<td><ul>
<li> 电子邮件 </li>
<li> 邮箱联系人（每个联系人最多迁移 3 个电子邮件地址） </li>
<li> 日历 </li>
<li> 标签 </li>
</ul></td>
<td><ul>
<li> 规则 </li>
<li> 代理 </li>
<li> 签名 </li>
<li> 任务 </li>
<li> 超出邮件大小限制的所有电子邮件或附件 </li>
<li> 被阻止的用户或非活动用户 </li>
<li> 来自 PST 文件或任何第三方存档解决方案（例如 Google Vault）的存档数据 </li>
<li> 权限管理或加密电子邮件 </li>
<li> 已损坏的项目 </li>
<li> Google Hangout** </li>
<li> Google 组 </li>
<li> 资源邮箱 </li>
<li> 非活动邮箱 </li>
<li> 假期设置和自动答复设置 </li>
<li> 共享日历、云附件、Google Hangout 链接和事件颜色 </li>
</ul>
**迁移另存为标签的环聊对话。 </td>
</tr>
<tr class="odd">
<td><strong>IMAP4 源（如 Domino、GroupWise 或 Zimbra）</strong></td>
<td>使用本机 IMAP4 工具进行迁移</td>
<td><li>电子邮件 </li></td>
<td><ul>
<li> 规则 </li>
<li> 代理 </li>
<li> 通讯组列表 </li>
<li> 外部联系人 </li>
<li> 启用邮件的用户 </li>
<li> 被阻止的用户或非活动用户 </li>
<li> 邮箱联系人 </li>
<li> 日历 </li>
<li> 签名 </li>
<li> 任务 </li>
<li> 超出邮件大小限制的所有电子邮件 </li>
<li> 存档数据 </li>
<li> 加密电子邮件 </li>
<li> 已损坏的项目 </li>
<li> 非活动邮箱 </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a>FastTrack迁移Exchange Online职责

我们的 FastTrack 专家在迁移项目期间执行标准活动。 有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。

我们的 FastTrack 专家还执行以下特定于 Exchange 迁移的活动：

  -  提供指导以帮助你在源环境和 Exchange Online 之间启用 SMTP 邮件路由共存（如果适用）。

### <a name="your-responsibilities"></a>你的责任

你在迁移项目期间执行标准活动。 有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。

此外，你还将执行以下特定于 Exchange 迁移的活动：

  - 完成 Exchange Online 的FastTrack 核心载入。 如果你自行执行载入，则必须通过必需的检查和先决条件。 有关详细信息，请参阅[产品和功能](products-and-capabilities.md)。
  -  根据 Office 365 准则安装客户端软件的相应级别。 有关详细信息，请参阅[新式工作区](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)。
  -  如果要从本地 Exchange 环境迁移，需满足特定要求。 有关详细信息，请参阅[配置混合部署先决条件](https://go.microsoft.com/fwlink/?LinkId=787528)。
  -  确保每个源环境都位于最新服务包 (SP) 和汇总 (RU)/累积更新 (CU) 级别（如果适用）。
  -  配置和验证源环境和 Exchange Online 之间的 SMTP 邮件路由共存（如果适用）。
  -  确保源邮箱大小不超过目标邮箱配额。 根据源平台的不同，可能需要将源数据限制为目标邮箱配额的 85%。
  -  根据需要迁移客户端数据。 这包括但不限于本地通讯簿、本地 PST 文件中的数据、Outlook 规则和本地 Outlook 设置。
  -  帮助最终用户修正客户端迁移问题。

## <a name="migration-to-sharepoint-online"></a>到 SharePoint Online 的迁移

当你选择使用 FastTrack 将文件迁移到 SharePoint Online 时，我们将提供迁移指南和数据迁移服务。 我们提供指导，以帮助你计划迁移、配置源环境和 SharePoint Online，并利用我们的数据迁移服务来迁移文件。 你可以创建和安排迁移事件。 我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。 迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源中的的文件已迁移到 SharePoint Online。

### <a name="considerations"></a>注意事项

 - 所有迁移均受 SharePoint Online 配额的限制。 有关详细信息<a href="https://go.microsoft.com/fwlink/?LinkId=698855">，SharePoint</a>限制。 
  - 建议将迁移总量限制在你享有的整体 SharePoint Online 存储配额（包括你可能单独购买的其他存储）的 75% 以内。

### <a name="source-environment-details"></a>源环境详细信息

我们的数据迁移服务从以下源环境迁移数据：

  - 文件共享（支持 SMB 2.0 前向的设备上的服务器消息块 (SMB) 文件共享）。
  - 单个 G 套件环境（仅限 Google Drive）。
  - Box（Starter、Business、Enterprise）。
  - 用于 Teams的 Dropbox（标准版和高级版）

下表显示了特定于每个源环境的迁移详细信息：

<table>
<thead>
<tr class="header">
<th><strong>源环境</strong></th>
<th><strong>迁移类型</strong></th>
<th><strong>迁移内容</strong></th>
 <th><strong>不迁移的内容</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>任何支持 SMB 2.0 及更高版本的文件共享设备</strong></td>
<td>单通道或多通道</td>
<td><ul>
<li> 文档 </li>
<li> 文件和文件夹结构 </li>
<li> 用户级别的文件和文件夹权限* </li>
<li> 组级别的文件和文件夹权限* </li>
<li> 小于 15GB 的文件 </li>
<li> 基本文档和文件夹元数据：
<ul>
<li> 创建日期 </li>
<li> 修改日期 </li>
<li> 创建者 </li>
<li> 最后一次修改者 </li>
</ul></li>
</ul>
*必须配置目录同步。 只迁移对 Windows 文件资源管理器公开的 NTFS 权限。 不会迁移文件共享设备上直接托管的权限。 如果数据存储在 SMB 2.0 设备上，只会迁移 SMB 协议公开的与 NTFS 等同的权限。</td>
<td><ul>
<li> 所有权历史记录和旧版本 </li>
<li> 内容中嵌入的 URL 的转换后对象 </li>
<li> 旧版本 </li>
<li> Windows 文件和文件夹属性（如只读和隐藏） </li>
<li> 非 Windows 新技术文件系统 (NTFS) 和 NTFS 高级权限和特殊设置： </li>
<li> 显式拒绝权限（在迁移后删除的权限、从属于并行权限的内容或父文件夹上的权限） </li>
<li> NTFS 审核配置 </li>
<li> 文件分类基础结构 (FCI) 提供的附加文件元数据 </li>
<li> 无法访问或已损坏的文档 </li>
<li> 隐藏的共享 </li>
<li> 共享（如在共享级别授予的权限） </li>
<li> 超出当前联机限制<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint的文件或文件夹</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>单个 G 套件环境（仅限 Google 云端硬盘）</strong></td>
<td>单通道或多通道</td>
<td><ul>
<li> Google 文档、工作表和幻灯片（文件转换为等同的 Office 格式），包括超过10 MB的 </li>
<li> 文件和文件夹结构 </li>
<li> 用户级别文件夹权限 </li>
<li> 组级别文件夹权限 </li>
<li> 小于 15GB 的文件 </li>
<li> 基本文档和文件夹元数据：
<ul>
<li> 创建日期 </li>
<li> 修改日期 </li>
<li> 创建者 </li>
<li> 最后一次修改者 </li>
</ul></li>
<li> 共享驱动器 （文件夹和文件） </li>
<li> 属于 Google 云端硬盘帐户的共享内容会被迁移 </li>
</ul></td>
<td><ul>
<li> 所有权历史记录、旧版本和注释 </li>
<li> 文件和文件夹说明、文件夹颜色 </li>
<li> 用户级别文件权限 </li>
<li> 组级别文件权限 </li>
<li> 高级元数据 </li>
<li> 文件锁定属性 </li>
<li> 内容中嵌入的 URL 的转换后对象 </li>
<li> 放入回收站的项 </li>
<li> 无法访问或已损坏的文档 </li>
<li> 被阻止的用户或非活动用户 </li>
<li> Google 相册、Forms、地图和其他已连接应用 </li>
<li> Google 绘图 </li>
<li> 组织外部的共享内容 </li>
<li> 不属于Google 云端硬盘帐户的内容被迁移 </li>
<li> 外部用户的权限和基本元数据（<strong>注意</strong>：使用 Google 云端硬盘管理报告确定与外部用户共享的内容。 指示最终用户在迁移后与外部用户重新共享内容。） </li>
<li> 共享驱动器成员资格权限（<strong>注意</strong>：使用 Google 云端硬盘管理报告来标识共享驱动器成员资格。 指示最终用户迁移前在目标上配置这些成员资格设置。） </li>
<li> 标记为受限或不可复制的文件 </li>
<li> 超出当前联机SharePoint<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">限制的文件或文件夹</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box（Starter、Business、Enterprise）</strong></td>
<td>单通道或多通道</td>
<td><ul>
<li> 文档 </li>
<li> 文件和文件夹结构 </li>
<li> 用户级别文件夹权限 </li>
<li> 组级别文件夹权限 </li>
<li> 小于 15GB 的文件 </li>
<li> 基本文档和文件夹元数据：
<ul>
<li> 创建日期 </li>
<li> 修改日期 </li>
<li> 创建者 </li>
<li> 最后一次修改者 </li>
</ul></li>
<li> 属于 Box 帐户的共享内容会被迁移 </li>
<li> 转换为 Word (格式的方框)  </li>
</ul></td>
<td><ul>
<li> 所有权历史记录、旧版本和注释 </li>
<li> 文件和文件夹说明 </li>
<li> 用户级别文件权限 </li>
<li> 组级别文件权限 </li>
<li> Box 标记和高级元数据 </li>
<li> 文件锁定属性 </li>
<li> 内容中嵌入的 URL 的转换后对象 </li>
<li> 放入回收站的项 </li>
<li> 无法访问或已损坏的文档 </li>
<li> 被阻止的用户或非活动用户 </li>
<li> Box 应用、书签、收藏夹和工作流 </li>
<li> 不属于已迁移 Box 帐户的内容 </li>
<li> 外部用户的权限和基本元数据（<strong>注意</strong>：使用 Box 报告确定与外部用户共享的内容。 指示最终用户在迁移后与外部用户重新共享内容。） </li>
<li> 超出当前联机SharePoint<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">限制的文件或文件夹</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>用于 Teams的 Dropbox（标准版和高级版）</strong></td>
<td>单通道或多通道</td>
<td><ul>
<li> 文档 </li>
<li> 文件和文件夹结构 </li>
<li> 用户级别文件夹权限 </li>
<li> 组级别文件夹权限 </li>
<li> 小于 15GB 的文件 </li>
<li> 基本文档和文件夹元数据：
<ul>
<li> 创建日期 </li>
<li> 修改日期 </li>
<li> 创建者 </li>
<li> 最后一次修改者 </li>
</ul></li>
<li> 共享团队文件夹和内容 </li>
<li> 属于 Dropbox 帐户的共享内容会被迁移 </li>
</ul></td>
<td><ul>
<li> 所有权历史记录、旧版本和注释 </li>
<li> 文件和文件夹说明 </li>
<li> 用户级别文件权限 </li>
<li> 组级别文件权限 </li>
<li> 高级元数据 </li>
<li> 文件锁定属性 </li>
<li> 内容中嵌入的 URL 的转换后对象 </li>
<li> 放入回收站的项 </li>
<li> 无法访问或已损坏的文档 </li>
<li> 已卸载的 Dropbox 文件夹 </li>
<li> 已删除或已断开连接的用户 </li>
<li> Dropbox Paper 文件、Dropbox Showcase 和 Dropbox Space </li>
<li> Dropbox 应用及收藏夹（已固定或加星标） </li>
<li> 已迁移的 Dropbox 帐户不拥有的内容 </li>
<li> 外部用户的权限和基本元数据（<strong>注意</strong>：使用 Dropbox 报告确定与外部用户共享的内容。 指示最终用户在迁移后与外部用户重新共享内容） </li>
<li> 超出当前联机SharePoint<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">限制的文件或文件夹</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a>FastTrack Online SharePoint迁移的责任

我们的 FastTrack 专家在迁移项目期间执行标准活动。 有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息

### <a name="your-responsibilities"></a>你的责任

你在迁移项目期间执行标准活动。 有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息

此外，你还将执行以下特定于 SharePoint Online 迁移的活动：

  - 预置将作为迁移事件目标的所有 SharePoint 团队网站。

## <a name="migration-to-onedrive-for-business"></a>到 OneDrive for Business 的迁移

当你选择使用 FastTrack 将文件迁移到 OneDrive for Business 时，我们将提供迁移指南和数据迁移服务。 我们提供指导，以帮助你计划迁移、配置源环境和 OneDrive for Business，并利用我们的数据迁移服务来迁移文件。 你可以创建和安排迁移事件。 我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。 迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源中的的文件已迁移到 OneDrive for Business。

### <a name="considerations"></a>注意事项

  - 所有迁移均受 SharePoint Online 配额的限制。 有关详细信息<a href="https://go.microsoft.com/fwlink/?LinkId=698855">，SharePoint</a>限制。 
  - 建议将迁移数据总量限制在你享有的整体 SharePoint Online 存储配额（包括你可能单独购买的其他存储）的 75% 以内。
  - FastTrack 仅迁移到活动的 OneDrive for Business 驱动器。

### <a name="source-environment-details"></a>源环境详细信息

我们的数据迁移服务从以下源环境迁移数据：

  - 文件共享（SMB 文件在支持 SMB 2.0 前向的设备上共享）。
  - 单个 G 套件环境（仅限 Google 云端硬盘）。
  - Box（Starter、Business、Enterprise）。
  - 用于 Teams的 Dropbox（标准版和高级版）

下表显示了特定于每个源环境的迁移详细信息：

<table>
<thead>
<tr class="header">
 <th><strong>源环境</strong></th>
 <th><strong>迁移类型</strong></th>
 <th><strong>迁移内容</strong></th>
 <th><strong>不迁移的内容</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>任何支持 SMB 2.0 及更高版本的文件共享设备</strong></td>
<td>单通道或多通道</td>
<td><ul>
<li> 文档 </li>
<li> 文件和文件夹结构 </li>
<li> 用户级别的文件和文件夹权限* </li>
<li> 组级别的文件和文件夹权限* </li>
<li> 小于 15GB 的文件 </li>
<li> 基本文档和文件夹元数据：
<ul>
<li> 创建日期 </li>
<li> 修改日期 </li>
<li> 创建者 </li>
<li> 最后一次修改者 </li>
</ul></li>
</ul>
<br>
*必须配置目录同步。 只迁移对 Windows 文件资源管理器公开的 NTFS 权限。 不会迁移文件共享设备上直接托管的权限。 如果数据存储在 SMB 2.0 设备上，只会迁移 SMB 协议公开的与 NTFS 等同的权限。 </td>
<td><ul>
<li> 所有权历史记录和旧版本 </li>
<li> 内容中嵌入的 URL 的转换后对象 </li>
<li> 旧版本 </li>
<li> Windows 文件和文件夹属性（如只读和隐藏） </li>
<li> 非 Windows 新技术文件系统 (NTFS) 和 NTFS 高级权限和特殊设置： </li>
<li> 显式拒绝权限（在迁移后删除的权限、从属于并行权限的内容或父文件夹上的权限） </li>
<li> NTFS 审核配置 </li>
<li> 文件分类基础结构 (FCI) 提供的附加文件元数据 </li>
<li> 无法访问或已损坏的文档 </li>
<li> 隐藏的共享 </li>
<li> 共享（如在共享级别授予的权限） </li>
<li> 超出当前联机SharePoint<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">限制的文件或文件夹</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>单个 G 套件环境（仅限 Google 云端硬盘）</strong></td>
<td>单通道或多通道</td>
<td><ul>
<li> Google 文档、工作表和幻灯片（文件包括超过10 MB的，转换为等同的 Office 格式） </li>
<li> 文件和文件夹结构 </li>
<li> 用户级别文件夹权限 </li>
<li> 组级别文件夹权限 </li>
<li> 小于 15GB 的文件 </li>
<li> 基本文档和文件夹元数据：
<ul>
<li> 创建日期 </li>
<li> 修改日期 </li>
<li> 创建者 </li>
<li> 最后一次修改者 </li>
</ul></li>
<li> 共享驱动器 （文件夹和文件） </li>
<li> 属于 Google 云端硬盘帐户的共享内容会被迁移 </li>
</ul></td>
<td><ul>
<li> 所有权历史记录、旧版本和注释 </li>
<li> 文件和文件夹说明、文件夹颜色 </li>
<li> 用户级别文件权限 </li>
<li> 组级别文件权限 </li>
<li> 高级元数据 </li>
<li> 文件锁定属性 </li>
<li> 内容中嵌入的 URL 的转换后对象 </li>
<li> 放入回收站的项 </li>
<li> 无法访问或已损坏的文档 </li>
<li> 被阻止的用户或非活动用户 </li>
<li> Google 相册、Forms、地图和其他已连接应用 </li>
<li> Google 绘图 </li>
<li> 组织外部的共享内容 </li>
<li> 不属于Google 云端硬盘帐户的内容被迁移 </li>
<li> 外部用户的权限和基本元数据（<strong>注意</strong>：使用 Google 云端硬盘管理报告确定与外部用户共享的内容。 指示最终用户在迁移后与外部用户重新共享内容。） </li>
<li> 共享驱动器成员资格权限（<strong>注意</strong>：使用 Google 云端硬盘管理报告来标识共享驱动器成员资格。 指示最终用户迁移前在目标上配置这些成员资格设置。） </li>
<li> 超出当前联机SharePoint<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">限制的文件或文件夹</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box（Starter、Business、Enterprise）</strong></td>
<td>单通道或多通道</td>
<td><ul>
<li> 文档 </li>
<li> 文件和文件夹结构 </li>
<li> 用户级别文件夹权限 </li>
<li> 组级别文件夹权限 </li>
<li> 小于 15GB 的文件 </li>
<li> 基本文档和文件夹元数据：
<ul>
<li> 创建日期 </li>
<li> 修改日期 </li>
<li> 创建者 </li>
<li> 最后一次修改者 </li>
</ul></li>
<li> 属于 Box 帐户的共享内容会被迁移 </li>
</ul></td>
<td><ul>
<li> 所有权历史记录、旧版本和注释 </li>
<li> 文件和文件夹说明 </li>
<li> 用户级别文件权限 </li>
<li> 组级别文件权限 </li>
<li> Box 标记和高级元数据 </li>
<li> 文件锁定属性 </li>
<li> 内容中嵌入的 URL 的转换后对象 </li>
<li> 放入回收站的项 </li>
<li> 无法访问或已损坏的文档 </li>
<li> 被阻止的用户或非活动用户 </li>
<li> Box 应用、书签、收藏夹和工作流 </li>
<li> 不属于已迁移 Box 帐户的内容 </li>
<li> 外部用户的权限和基本元数据（<strong>注意</strong>：使用 Box 报告确定与外部用户共享的内容。 指示最终用户在迁移后与外部用户重新共享内容。） </li>
<li> 超出当前联机SharePoint<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">限制的文件或文件夹</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>用于 Teams的 Dropbox（标准版和高级版）</strong></td>
<td>单通道或多通道</td>
<td><ul>
<li> 文档 </li>
<li> 文件和文件夹结构 </li>
<li> 用户级别文件夹权限 </li>
<li> 组级别文件夹权限 </li>
<li> 小于 15GB 的文件 </li>
<li> 基本文档和文件夹元数据：
<ul>
<li> 创建日期 </li>
<li> 修改日期 </li>
<li> 创建者 </li>
<li> 最后一次修改者 </li>
</ul></li>
<li> 共享团队文件夹和内容 </li>
<li> 属于 Dropbox 帐户的共享内容会被迁移 </li>
</ul></td>
<td><ul>
<li> 所有权历史记录、旧版本和注释 </li>
<li> 文件和文件夹说明 </li>
<li> 用户级别文件权限 </li>
<li> 组级别文件权限 </li>
<li> 高级元数据 </li>
<li> 文件锁定属性 </li>
<li> 内容中嵌入的 URL 的转换后对象 </li>
<li> 放入回收站的项 </li>
<li> 无法访问或已损坏的文档 </li>
<li> 已卸载的 Dropbox 文件夹 </li>
<li> 已删除或已断开连接的用户 </li>
<li> Dropbox Paper 文件、Dropbox Showcase 和 Dropbox Space </li>
<li> Dropbox 应用及收藏夹（已固定或加星标） </li>
<li> 已迁移的 Dropbox 帐户不拥有的内容 </li>
<li> 外部用户的权限和基本元数据（<strong>注意</strong>：使用 Dropbox 报告确定与外部用户共享的内容。 指示最终用户在迁移后与外部用户重新共享内容。） </li>
<li> 超出当前联机SharePoint<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">限制的文件或文件夹</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a>FastTrack迁移OneDrive for Business责任

我们的 FastTrack 专家在迁移项目期间执行标准活动。 有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。

### <a name="your-responsibilities"></a>你的责任

你在迁移项目期间执行标准活动。 有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。

此外，你还将执行以下特定于 OneDrive for Business 迁移的活动：

  - 预置将作为迁移事件目标的所有 OneDrive for Business 网站。

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a>迁移到 Microsoft Teams 组Microsoft 365组

当你选择使用 FastTrack 将文件迁移到 Microsoft Teams Microsoft 365 组时，我们提供迁移指导和数据迁移服务。 我们提供的指南可帮助你规划迁移、配置源环境和Teams Microsoft 365组，以及利用我们的数据迁移服务迁移文件。 你可以创建和安排迁移事件。 我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。 迁移事件完成后，可以预期源环境的适当计划源和符合条件的源中的文件已迁移到 Teams 和 Microsoft 365 组。 Teams频道Microsoft 365组必须先由客户预配，然后才能将数据迁移到这些目标类型。 Teams组Microsoft 365组会影响对文件目标位置的权限。 Teams组Microsoft 365组，以允许协作。 用户Teams或Microsoft 365组确定迁移到目标时谁有权访问这些文件。 FastTrack迁移期间不会将最终用户或组添加到任何Teams或Microsoft 365组权限。

### <a name="considerations"></a>注意事项

- 所有迁移均受 SharePoint Online 配额的限制。 有关详细信息<a href="https://go.microsoft.com/fwlink/?LinkId=698855">，SharePoint</a>限制。 
- 建议将迁移总量限制在你享有的整体 SharePoint Online 存储配额（包括你可能单独购买的其他存储）的 75% 以内。 


### <a name="source-environment-details"></a>源环境详细信息

我们的数据迁移服务从以下源环境迁移数据： 

- 文件共享（支持 SMB 2.0 前向的设备上的服务器消息块 (SMB) 文件共享）。
-  单个 G 套件环境（仅限 Google Drive）。 
- Box（Starter、Business、Enterprise）。 
- 用于 Teams的 Dropbox（标准版和高级版） 

下表显示了特定于每个源环境的迁移详细信息：

<table>
<thead>
<tr class="header">
 <th><strong>源环境</strong></th>
 <th><strong>迁移类型</strong></th>
 <th><strong>迁移内容</strong></th>
 <th><strong>不迁移的内容</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>任何支持 SMB 2.0 及更高版本的文件共享设备</strong></td>
<td>单通道或多通道</td>
<td><ul>
<li> 文档 </li>
<li> 文件和文件夹结构 </li>
<li> 用户级别的文件和文件夹权限* </li>
<li> 组级别的文件和文件夹权限* </li>
<li> 小于 15GB 的文件 </li>
<li> 基本文档和文件夹元数据：
<ul>
<li> 创建日期 </li>
<li> 修改日期 </li>
<li> 创建者 </li>
<li> 最后一次修改者 </li>
</ul></li>
</ul>
<br>
*必须配置目录同步。 只迁移对 Windows 文件资源管理器公开的 NTFS 权限。 不会迁移文件共享设备上直接托管的权限。 如果数据存储在 SMB 2.0 设备上，只会迁移 SMB 协议公开的与 NTFS 等同的权限。 权限受组和/或Microsoft 365频道Microsoft Teams影响。 如果目标为Microsoft 365或Microsoft Teams，组或频道将确定迁移文件的最终权限配置文件。 建议不要迁移迁移到组或 Microsoft 365 频道Microsoft Teams权限。</td>
<td><ul>
<li> 所有权历史记录和旧版本 </li>
<li> 内容中嵌入的 URL 的转换后对象 </li>
<li> 旧版本 </li>
<li> Windows 文件和文件夹属性（如只读和隐藏） </li>
<li> 非 Windows 新技术文件系统 (NTFS) 和 NTFS 高级权限和特殊设置： </li>
<li> 显式拒绝权限（在迁移后删除的权限、从属于并行权限的内容或父文件夹上的权限） </li>
<li> NTFS 审核配置 </li>
<li> 文件分类基础结构 (FCI) 提供的附加文件元数据 </li>
<li> 无法访问或已损坏的文档 </li>
<li> 隐藏的共享 </li>
<li> 共享（如在共享级别授予的权限） </li>
<li> 超出当前联机SharePoint<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">限制的文件或文件夹</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>单个 G 套件环境（仅限 Google 云端硬盘）</strong></td>
<td>单通道或多通道</td>
<td><ul>
<li> Google 文档、工作表和幻灯片（文件包括超过10 MB的，转换为等同的 Office 格式） </li>
<li> 文件和文件夹结构 </li>
<li> 用户级别文件夹权限* </li>
<li> 组级别文件夹权限* </li>
<li> 小于 15GB 的文件 </li>
<li> 基本文档和文件夹元数据：
<ul>
<li> 创建日期 </li>
<li> 修改日期 </li>
<li> 创建者 </li>
<li> 最后一次修改者 </li>
</ul></li>
<li> 共享驱动器 （文件夹和文件） </li>
<li> 属于 Google 云端硬盘帐户的共享内容会被迁移 </li>
</ul>
<br>
*权限受组和/Microsoft 365频道Microsoft Teams影响。 如果目标为组或Microsoft 365组Microsoft Teams，则组或频道将确定迁移文件的最终权限配置文件。 建议不要迁移迁移到组或Microsoft 365组Microsoft Teams权限。 
</td>
<td><ul>
<li> 所有权历史记录、旧版本和注释 </li>
<li> 文件和文件夹说明、文件夹颜色 </li>
<li> 用户级别文件权限 </li>
<li> 组级别文件权限 </li>
<li> 高级元数据 </li>
<li> 文件锁定属性 </li>
<li> 内容中嵌入的 URL 的转换后对象 </li>
<li> 放入回收站的项 </li>
<li> 无法访问或已损坏的文档 </li>
<li> 被阻止的用户或非活动用户 </li>
<li> Google 相册、Forms、地图和其他已连接应用 </li>
<li> Google 绘图 </li>
<li> 组织外部的共享内容 </li>
<li> 不属于Google 云端硬盘帐户的内容被迁移 </li>
<li> 外部用户的权限和基本元数据（<strong>注意</strong>：使用 Google 云端硬盘管理报告确定与外部用户共享的内容。 指示最终用户在迁移后与外部用户重新共享内容。） </li>
<li> 共享驱动器成员资格权限（<strong>注意</strong>：使用 Google 云端硬盘管理报告来标识共享驱动器成员资格。 指示最终用户迁移前在目标上配置这些成员资格设置。） </li>
<li> 超出当前联机SharePoint<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">限制的文件或文件夹</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box（Starter、Business、Enterprise）</strong></td>
<td>单通道或多通道</td>
<td><ul>
<li> 文档 </li>
<li> 文件和文件夹结构 </li>
<li> 用户级别文件夹权限* </li>
<li> 组级别文件夹权限* </li>
<li> 小于 15GB 的文件 </li>
<li> 基本文档和文件夹元数据：
<ul>
<li> 创建日期 </li>
<li> 修改日期 </li>
<li> 创建者 </li>
<li> 最后一次修改者 </li>
</ul></li>
<li> 属于 Box 帐户的共享内容会被迁移 </li>
<li> 转换为 Word (格式的方框)  </li>
</ul>
<br>
*权限受组和/Microsoft 365频道Microsoft Teams影响。 如果目标为组或Microsoft 365组Microsoft Teams，则组或频道将确定迁移文件的最终权限配置文件。 建议不要迁移迁移到组或Microsoft 365组Microsoft Teams权限。 </td>
<td><ul>
<li> 所有权历史记录、旧版本和注释 </li>
<li> 文件和文件夹说明 </li>
<li> 用户级别文件权限 </li>
<li> 组级别文件权限 </li>
<li> Box 标记和高级元数据 </li>
<li> 文件锁定属性 </li>
<li> 内容中嵌入的 URL 的转换后对象 </li>
<li> 放入回收站的项 </li>
<li> 无法访问或已损坏的文档 </li>
<li> 被阻止的用户或非活动用户 </li>
<li> Box 应用、书签、收藏夹和工作流 </li>
<li> 不属于已迁移 Box 帐户的内容 </li>
<li> 外部用户的权限和基本元数据（<strong>注意</strong>：使用 Box 报告确定与外部用户共享的内容。 指示最终用户在迁移后与外部用户重新共享内容。） </li>
<li> 超出当前联机SharePoint<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">限制的文件或文件夹</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>用于 Teams的 Dropbox（标准版和高级版）</strong></td>
<td>单通道或多通道</td>
<td><ul>
<li> 文档 </li>
<li> 文件和文件夹结构 </li>
<li> 用户级别文件夹权限* </li>
<li> 组级别文件夹权限* </li>
<li> 小于 15GB 的文件 </li>
<li> 基本文档和文件夹元数据：
<ul>
<li> 创建日期 </li>
<li> 修改日期 </li>
<li> 创建者 </li>
<li> 最后一次修改者 </li>
</ul></li>
<li> 共享团队文件夹和内容 </li>
<li> 属于 Dropbox 帐户的共享内容会被迁移 </li>
</ul>
<br>
*权限受组和/Microsoft 365频道Microsoft Teams影响。 如果目标为组或Microsoft 365组Microsoft Teams，则组或频道将确定迁移文件的最终权限配置文件。 建议不要迁移迁移到组或Microsoft 365组Microsoft Teams权限。
</td>
<td><ul>
<li> 所有权历史记录、旧版本和注释 </li>
<li> 文件和文件夹说明 </li>
<li> 用户级别文件权限 </li>
<li> 组级别文件权限 </li>
<li> 高级元数据 </li>
<li> 文件锁定属性 </li>
<li> 内容中嵌入的 URL 的转换后对象 </li>
<li> 放入回收站的项 </li>
<li> 无法访问或已损坏的文档 </li>
<li> 已卸载的 Dropbox 文件夹 </li>
<li> 已删除或已断开连接的用户 </li>
<li> Dropbox Paper 文件、Dropbox Showcase 和 Dropbox Space </li>
<li> Dropbox 应用及收藏夹（已固定或加星标） </li>
<li> 已迁移的 Dropbox 帐户不拥有的内容 </li>
<li> 外部用户的权限和基本元数据（<strong>注意</strong>：使用 Dropbox 报告确定与外部用户共享的内容。 指示最终用户在迁移后与外部用户重新共享内容。） </li>
<li> 超出当前联机SharePoint<a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">限制的文件或文件夹</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a>FastTrack组迁移Microsoft Teams Microsoft 365迁移的责任

我们的 FastTrack 专家在迁移项目期间执行标准活动。 有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。

### <a name="your-responsibilities"></a>你的责任 

你在迁移项目期间执行标准活动。 有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。
还可以执行以下特定于组迁移Microsoft Teams Microsoft 365活动： 

- 根据Microsoft Teams事件Microsoft 365所有组和组。

> [!NOTE]
>FastTrack预配频道或Microsoft Teams组Microsoft 365预配。 FastTrack向频道或组添加最终用户Microsoft Teams组Microsoft 365组。 在将数据迁移到目标之前，必须将最终用户或组添加到所有 Microsoft Teams 频道和 Microsoft 365 组，以便这些最终用户能够访问新迁移的文档