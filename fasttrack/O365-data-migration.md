---
title: 数据迁移
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack Specialists provide guidance on steps for data migration to Office 365. This is available for all eligible customers with Office 365 services for Exchange Online, OneDrive for Business, and SharePoint Online.
ms.openlocfilehash: 7780af3d5edcdbdf21acba1d421bf379967305fa
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011306"
---
# <a name="data-migration"></a>数据迁移

你可能有你想要迁移到 Office 365 的源环境中的数据。

**对于带150-499 许可证的 Office 365 租户：** 我们通过结合使用工具和文档提供指导，以便您的迁移顺利而有效地进行。 

**对于带 500 或更多的许可证的 Office 365 租户\*:** 数据迁移服务可用于 Exchange Online、SharePoint Online 和 OneDrive for Business。 你的 FastTrack 好处包括为你提供源环境集成和迁移数据的指导。
  
\*If you purchased or renewed a commercial plan prior to 9/1/2017, 150 seats is the minimum seat requirement throughout your current subscription period in order to receive the migration benefit. For education plans, only paid faculty and staff licenses are eligible for migration services. 
  
> [!NOTE]
> Data migrated through the FastTrack services may be transferred to, stored, and processed anywhere that Microsoft maintains facilities (except as otherwise provided for your particular FastTrack engagement). The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements. 
  
> [!NOTE]
> 未预料到的问题（包括但不限于源环境中无法读取或已损坏的项）可能会阻止某些项迁移。 
  
> [!NOTE]
> 迁移协助有以下语言版本：繁体中文和简体中文（仅限国语资源）、英语、法语、德语、意大利语、日语、葡萄牙语（巴西）和西班牙语。 
  
> [!NOTE]
> 如果集成是必需的，则对于相应的应用程序而言，您的源环境必须处于最低级别。 
  
> [!NOTE]
> 2020 年 3 月新增功能，Microsoft 将提供 6 个月的 [Office 365 E1](https://docs.microsoft.com/microsoftteams/e1-trial-license) 和 [Office 365 G1](https://docs.microsoft.com/microsoftteams/g1-trial-license) 试用版许可证协助客户远程工作和学习，应对新型冠状病毒肺炎（COVID-19）的爆发。 从 2020 年 3 月到 2020 年 8月，FastTrack 破例针对这些试用版证书超过 500 （含）的租户以及针对 [Office 365 A1](https://www.microsoft.com/microsoft-365/academic/compare-office-365-education-plans?activetab=tab:primaryr1) 学生版提供数据迁移服务。 Microsoft保留随时取消，更改或暂停此优惠的权利，恕不另行通知。

下表描述了对您的现有源环境的迁移预期。
  

|**活动**|**对源环境的预期**|
|:-----|:-----|
|**Exchange Online 迁移**  <br/> | Microsoft migrates any combination of the source environments listed below, each one at a time. We can migrate the onboarded messaging system using the FastTrack Center or if it's passed the FastTrack Center checks. This includes:  <br/>  如果每个组织中均实施了基于 Exchange 2010 的混合前向，并且 Exchange 邮件系统是 2003 前向，则单个或多个 Active Directory 林将具有单个或多个 Exchange 组织。  <br/>  一个支持 IMAP 的电子邮件环境。  <br/>  G 套件环境（仅限 Gmail、联系人和日历）。 <br/> <br/> **注意***：在迁移之前，必须完成 Exchange Online 载入。* <br/> <br/> **注意***：FastTrack 仅迁移到活动 Office 365 邮箱。* <br/> <br/> **注意***：有关本地 Exchange 依赖项的信息，请参阅[混合部署先决条件](https://go.microsoft.com/fwlink/?LinkId=787528)。* <br/><br/> **注意***：在迁移多个源邮件环境（如多个 Exchange 组织或多个 Domino 域）时，这些迁移会依序执行。*| 
|**SharePoint Online 迁移**  <br/> | 文件共享（支持 SMB 2.0 前向的设备上的服务器消息块 (SMB) 文件共享）。 <br/> 单个 G 套件环境（仅限 Google 云端硬盘）。<br/>  Box（Starter、Business、Enterprise）。  <br/> 用于 Teams的 Dropbox（标准版和高级版）<br/> |
|**OneDrive for Business 迁移**  <br/> | 文件共享（SMB 文件在支持 SMB 2.0 前向的设备上共享）。  <br/>  单个 G 套件环境（仅限 Google 云端硬盘）。  <br/>  Box（Starter、Business、Enterprise）。 <br/> 用于 Teams的 Dropbox（标准版和高级版）<br/><br/> **注意***：FastTrack 仅迁移到活动 Office 365 驱动器。*|
   
## <a name="migration-to-exchange-online"></a>到 Exchange Online 的迁移
''
### <a name="enable-to-migrate"></a>启用迁移
  
如果使用 Microsoft 迁移电子邮件，我们会指导如何启用 Exchange Online 和源环境进行迁移。 我们执行的启用步骤可能因源环境而异。 我们通过综合使用工具和文档，以及执行适用可行的配置任务，提供具体指导。 然后，我们会根据适用的参数来迁移邮箱、监视作业并提供状态报告。
Microsoft 可能需要你的邮件系统的相应访问权限及其他权限才能执行迁移活动。
  
### <a name="migration-policy-and-steps"></a>迁移策略和步骤
  
> [!NOTE]
> 迁移时间段也称为迁移批处理。

#### <a name="commercial-and-uk-government"></a>商业和英国政府

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>美国政府/DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.
    
 ### <a name="end-state"></a>结束状态
  
完成迁移批处理后的预期结束状态包括：
- 源环境中经过适当安排且符合条件的源邮箱中的数据迁移到 Office 365 中。 
- Microsoft 提供的迁移批处理的迁移后报告。
    
完成所有迁移后的预期结束状态包括：
- 符合条件的源邮箱中的数据迁移到 Office 365 中，如下表所定义。
- 要迁移的数据类型视源环境而定，如下表所述。
    
> [!NOTE]
> All source environments need to be on the latest service packs (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment at the end of the Enable phase. Data migration services are subject to external factors beyond Microsoft's control, like changes to third-party application programming interfaces (APIs), which could result in changes to, delays in, or suspension of these services. For the duration of the FastTrack services, data you make available to Microsoft is accessible from and stored anywhere that Microsoft and its suppliers maintain facilities. 
  
|||||
|:-----|:-----|:-----|:-----|
|**源环境**|**迁移类型**|**将从源邮箱迁移的内容**|**不会迁移的内容**|
|**Exchange 2003 及更高版本**|直接转换| 电子邮件 <br/> 邮箱规则 <br/> 代理 <br/> 邮箱联系人 <br/> 日历 <br/> 任务 <br/> 权限管理的电子邮件 <br/> 加密电子邮件| 公用文件夹 <br/> 个人联系人 <br/> 启用邮件的用户 <br/> 被阻止的用户或非活动用户 <br/> 签名 <br/> 邮箱转储程序 <br/>  超出邮件大小限制的所有电子邮件 <br/> 存档数据 <br/> 已损坏的项目 <br/>  非活动邮箱 |
|**Exchange 2003 和 Exchange 2007**|暂存| 电子邮件 <br/> 邮箱规则 <br/> 代理 <br/> 邮箱联系人 <br/> 日历 <br/> 任务 <br/> 权限管理的电子邮件 <br/> 加密电子邮件| 公用文件夹 <br/> 个人联系人 <br/> 启用邮件的用户 <br/> 被阻止的用户或非活动用户 <br/> 签名 <br/> 邮箱转储程序 <br/> 超出邮件大小限制的所有电子邮件 <br/> 存档数据 <br/> 已损坏的项目 <br/> 非活动邮箱 |
|**Exchange 2010、Exchange 2013、Exchange 2016和 Exchange 2019** <br/><br/> **注意***：有关本地 Exchange 依赖项的信息，请参阅[混合部署先决条件](https://go.microsoft.com/fwlink/?LinkId=787528)。*           |使用混合部署进行的迁移| 电子邮件 <br/> 邮箱规则 <br/> 代理 <br/> 邮箱联系人 <br/> 日历 <br/> 任务 <br/> 签名 <br/> 与用户的邮箱一起迁移的个人存档 <br/> 可恢复的项目 <br/> 权限管理的电子邮件 <br/> 加密电子邮件| 公用文件夹 <br/> 超出邮件大小限制的所有电子邮件 <br/> 日记存档或任何第三方存档解决方案 <br/> 被阻止的用户或非活动用户 <br/> 来自个人存储表 (PST) 文件的存档数据 <br/> 已损坏的项目 <br/> 非活动邮箱 |
|**G 套件环境（仅限 Gmail、联系人和日历）** <br/> <br/> **注意**：*G 套件环境必须启用 Google API 和 Google 管理 SDK，才能扩展功能。* <br/>          |直接转换或暂存| 电子邮件 <br/> 邮箱联系人\*  <br/> 日历 <br/> 标签 <br/> \*每个联系人最多可迁移 3 个电子邮件地址| Rules <br/> 代理 <br/> 签名 <br/> 任务 <br/> 超出邮件大小限制的所有电子邮件或附件 <br/> 被阻止的用户或非活动用户 <br/> 来自 PST 文件或任何第三方存档解决方案（例如 Google Vault）的存档数据 <br/> 权限管理或加密电子邮件 <br/> 已损坏的项目 <br/> Google Hangouts\*\* <br/> Google 组 <br/> 资源邮箱 <br/> 非活动邮箱 <br/> 假期设置和自动答复设置 <br/> 共享日历、云附件、Google Hangout 链接和事件颜色 <br/>\*\*迁移另存为标签的环聊对话 |
|**IMAP4 源 (如 Domino, GroupWise, and Zimbra)** |使用本机 IMAP4 工具进行迁移| 电子邮件 | 规则 <br/> 代理 <br/> 通讯组列表 <br/> 外部联系人 <br/> 启用邮件的用户 <br/> 被阻止的用户或非活动用户 <br/> 邮箱联系人 <br/> 日历 <br/> 签名 <br/> 任务 <br/> 超出邮件大小限制的所有电子邮件 <br/> 存档数据 <br/> 加密电子邮件 <br/> 已损坏的项目 <br/> 非活动邮箱 |
   
> [!NOTE]
> If distribution lists (MailEnabledGroup objects) and external contacts (MailEnabledContact objects) are in the on-premises Active Directory, they can be synchronized using Azure AD Connect. However, they aren't a part of mailbox data migration. For more information, see the **Identity integration** example in [Core](O365-onboarding-and-migration.md#core). 
  
FastTrack 专家在迁移过程中执行以下操作：
- 提供用于计划邮箱迁移的标准模板。
- 为 FastTrack 专家提供必需权限的相关信息。 
- 收集采用预定格式的预定邮箱迁移计划。
- 在将邮箱报告为迁移失败之前，在迁移批量处理期间最多尝试迁移一个邮箱两次。
- 对于基于 Exchange 和 IMAP4 的源环境，最多迁移用户邮箱存储空间上限 85% 的邮箱内容（例如，如果邮箱存储空间上限是 50 GB，那么 Microsoft 最多迁移 50 GB 存储空间上限 85% 的内容）。 
- 除非使用直接转换迁移，否则在源邮件环境和 Office 365 Exchange Online 之间启用 SMTP 邮件路由共存。
- 提供迁移后报告。
- Provide post-migration assistance for critical issues. The following issues are considered critical:
  - 在迁移期间丢失数据。
  - 在迁移期间源环境变得不可用。
  - 迁移活动导致源环境中出现问题。
    
在迁移过程中执行以下操作：
- 使用 FastTrack 中心完成 Exchange Online 载入或通过所需的检查。
- 处理与最终用户的所有通信。  
- 根据 Office 365 准则安装客户端软件的相应级别。 有关详细信息，请参阅[现代工作场所](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)。 
- 验证源邮件环境和 Office 365 Exchange Online 之间的 SMTP 邮件路由共存（如适用）。
- 就每个迁移事件提供采用所定义方法的计划和包含要迁移的特定邮箱的列表。
- 在迁移批处理前至少提前 24 小时从计划中删除邮箱。 
- 计划 24 小时内的平均目标邮箱数量，如下表所示。
    
|||
|:-----|:-----|
|**符合条件的迁移邮箱数量** <br/> |**24 小时内的平均邮箱数量下限** <br/> |
|150-1000  <br/> |总数的 25%  <br/> |
|1001-5000  <br/> |总数的 20%  <br/> |
|5001-10000  <br/> |总数的 15%  <br/> |
|\>10000  <br/> |1500  <br/> |
   
   > [!NOTE]
   > These numbers are based on best practice. However, the number of mailboxes that migrate per day will vary based on environment, readiness, and business constraints. Microsoft can't guarantee the speed of mailbox migration. 
  
- 计划在迁移批处理中至少迁移 35 个邮箱。 
- 解决预迁移故障问题（如果适用）。  
- 向 FastTrack 专家授予对源环境的访问权限及其他权限，以方便专家执行迁移活动。 
- 在 Office 365 中采购和/或提供已授权的管理帐户，以执行迁移活动（如果合适）。 
- 针对客户端迁移问题提供支持，并在必要时运行迁移后操作。 
- Migrate client-side data if desired. This includes, but is not limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.   
- 将邮箱大小减小到目标 Office 365 邮箱限制的 85% 以下（如果适用）。   
- 处理迁移后报告中的操作，包括未移动的邮箱。  
- 解决迁移后故障问题，然后重新计划邮箱（如果适用）。   
- Engage in post-migration assistance for critical issues. The following issues are considered critical:
  - 在迁移期间丢失数据。
  - 在迁移期间源环境变得不可用。
  - 迁移活动导致源环境中出现问题。
    
You need to follow the standard migration process and engage with Microsoft appropriately. This includes providing access and permissions to source and Office 365 environments, providing migration schedules, correcting any causes for migration errors, and so on. You also need to engage with end users for communications, mailbox migration schedule, and handling end user migration-related issues.
  
> [!NOTE]
> Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
  
## <a name="migration-to-sharepoint-online"></a>到 SharePoint Online 的迁移

### <a name="enable-to-migrate"></a>启用迁移
  
If you use Microsoft to migrate your data, we provide guidance to enable both SharePoint Online and the source environment for migration. Depending on the source, we may perform various Enable steps. We provide guidance for you by using a combination of tools and documentation and by performing configuration tasks where applicable and feasible.
  
需要向 Microsoft 提供执行某些活动所需的相应访问权限和许可。
  
### <a name="migration-policy-and-steps"></a>迁移策略和步骤
  
> [!NOTE]
> 迁移时间段也称为迁移批处理。

#### <a name="commercial-and-uk-government"></a>商业和英国政府

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>美国政府/DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.

- 所有迁移都需满足 [SharePoint Online 和 OneDrive for Business 软件边界和限制](https://go.microsoft.com/fwlink/?LinkID=616612)中所述的 SharePoint Online 配额。   
- 整个迁移的数据量将限定在您享有的整体 SharePoint Online 存储配额（包括您可能单独购买的其他存储空间）的 75% 的范围内。
    
 ### <a name="end-state"></a>结束状态
  
完成迁移批处理后的预期结束状态包括： 
- 源环境中经过适当安排且符合条件的源中的数据将被迁移到 SharePoint Online 中。   
- Microsoft 提供的迁移批处理的迁移后报告。
    
完成所有迁移后的预期结束状态包括： 
- 符合条件的源中的数据迁移到 Office 365 中，如下表所定义。  
- 要迁移的数据类型视源环境而定，如下表所述：
    
|||||
|:-----|:-----|:-----|:-----|
|**源环境** <br/> |**迁移类型** <br/> |**迁移内容** <br/> |**不会迁移的内容** <br/> |
|**任何支持 SMB 2.0 及更高版本的文件共享设备**  <br/> |单通道或多通道  <br/> | 文档  <br/>  文件和文件夹结构  <br/>  用户级别的文件和文件夹权限\*  <br/>  组级别的文件和文件夹权限\*  <br/>  小于 15GB 的文件  <br/>  基本文档和文件夹元数据：  <br/>  创建日期  <br/>  修改日期  <br/>  创建者  <br/>  上次修改者  <br/><br/> \**必须配置目录同步。只迁移对 Windows 文件资源管理器公开的 NTFS 权限。不会迁移文件共享设备上直接托管的权限。如果数据存储在 SMB 2.0 设备上，只会迁移 SMB 协议公开的与 NTFS 等同的权限。* <br/> | 所有权历史记录和旧版本  <br/>  内容中嵌入的 URL 的转换后对象  <br/>  旧版本  <br/>  Windows 文件和文件夹属性（如只读和隐藏）  <br/>  非 Windows 新技术文件系统 (NTFS) 和 NTFS 高级权限和特殊设置：  <br/>  显式拒绝权限（在迁移后删除的权限、从属于并行权限的内容或父文件夹上的权限）  <br/>  NTFS 审核配置  <br/>  文件分类基础结构 (FCI) 提供的附加文件元数据  <br/>  无法访问或已损坏的文档  <br/>  隐藏的共享  <br/>  共享（如在共享级别授予的权限）  <br/>  超出当前 [SharePoint Online 限制和局限](https://go.microsoft.com/fwlink/?linkid=846724)的文件或文件夹 <br/> |
|**单个 G 套件环境（仅限 Google 云端硬盘）**  <br/> |单通道或多通道  <br/> | <br/>  Google 文档、工作表和幻灯片（文件转换为等同的 Office 格式），包括超过10 MB的 <br/>  文件和文件夹结构  <br/>  用户级别文件夹权限  <br/>  组级别文件夹权限 <br/>  小于 15GB 的文件  <br/> 基本文档和文件夹元数据： <br/> 创建日期  <br/>  修改日期  <br/>  创建者  <br/>  最后一次修改者  <br/> 共享驱动器 （文件夹和文件） <br/>  要迁移的 Google 云端硬盘帐户所拥有的共享内容（若与用户或组显式共享的话）\*  <br/><br/> \**使用 Google 云端硬盘管理员确定外部帐户。指示最终用户在迁移后重新共享其内容。* <br/> | 所有权历史记录、旧版本和注释 <br/>  文件和文件夹说明、文件夹颜色  <br/>  用户级别文件权限  <br/>  组级别文件权限  <br/>  高级元数据  <br/>  文件锁定属性  <br/>  内容中嵌入的 URL 的转换后对象  <br/>  放入回收站的项  <br/>  无法访问或已损坏的文档  <br/>  被阻止的用户或非活动用户  <br/>  Google 相册、Forms、地图和其他已连接应用  <br/>  Google 绘图  <br/>  组织外部的共享内容  <br/> 不属于Google 云端硬盘帐户的内容被迁移 <br/>外部用户的权限和基本元数据  <br/> 共享驱动器权限\* <br/> 超出当前 [SharePoint Online 限制和局限](https://go.microsoft.com/fwlink/?linkid=846724)的文件或文件夹 <br/> <br/> \**使用 Google 云端硬盘管理员确定外部帐户。指示最终用户在迁移后重新共享其内容。* <br/>|
|**Box（Starter、Business、Enterprise）**  <br/> |单通道或多通道  <br/> | 文档  <br/>  文件和文件夹结构  <br/>  用户级别文件夹权限  <br/>  组级别文件夹权限  <br/>  小于 15GB 的文件  <br/>  基本文档和文件夹元数据：  <br/>  创建日期  <br/>  修改日期  <br/>  创建者  <br/>  最后一次修改者  <br/>  要迁移的 Box 帐户所拥有的共享内容（若与用户或组显式共享的话）\*  <br/><br/> \**使用 Box 报告确定外部帐户。指示最终用户在迁移后重新共享其内容。* <br/> | 所有权历史记录、旧版本和注释 <br/>  用户级别文件权限  <br/>  组级别文件权限  <br/>  文件和文件夹说明  <br/>  Box 标记和高级元数据  <br/>  文件锁定属性  <br/>  内容中嵌入的 URL 的转换后对象  <br/>  放入回收站的项  <br/>  无法访问或已损坏的文档  <br/>  被阻止的用户或非活动用户  <br/>  Box 备注（未经转换将无法迁移）  <br/>  Box 应用、书签、收藏夹和工作流  <br/>  已迁移的 Box 帐户不拥有的内容（共享文件夹）  <br/>  外部用户的权限和基本元数据\*  <br/>  超出当前 [SharePoint Online 限制和局限](https://go.microsoft.com/fwlink/?linkid=846724)的文件或文件夹 <br/> <br/>\**使用 Google 云端硬盘管理员识别共享驱动器成员身份。指示最终用户在迁移之前，在目标上配置成员资格设置。* |
|**用于 Teams的 Dropbox（标准版和高级版）**  <br/> |单通道或多通道  <br/> | 文档  <br/>  文件和文件夹结构  <br/>  用户级别文件夹权限  <br/>  组级别文件夹权限  <br/>  小于 15GB 的文件  <br/>  基本文档和文件夹元数据：  <br/>  创建日期  <br/>  修改日期  <br/>  创建者  <br/>  最后一次修改者  <br/> 共享团队文件夹和内容 <br/>  要迁移的 Dropbox 帐户所拥有的共享内容（若与用户或组显式共享的话）\*  <br/> <br/> \**使用 Dropbox 报告确定外部帐户。指示最终用户在迁移后重新共享其内容。* <br/> | 所有权历史记录、旧版本和注释 <br/>  文件和文件夹说明 <br/>  用户级别文件权限  <br/>  组级别文件权限    <br/> 高级元数据  <br/>  文件锁定属性  <br/>  内容中嵌入的 URL 的转换后对象  <br/>  放入回收站的项  <br/>  无法访问或已损坏的文档  <br/>  已卸载的 Dropbox 文件夹 <br/>  已删除或已断开连接的用户 <br/>  Dropbox Paper 文件、Dropbox Showcase 和 Dropbox Space  <br/> Dropbox 应用及收藏夹（已固定或加星标） <br/> 已迁移的 Dropbox 帐户不拥有的内容  <br/>  外部用户的权限和基本元数据\*  <br/>  超出当前 [SharePoint Online 限制和局限](https://go.microsoft.com/fwlink/?linkid=846724)的文件或文件夹 <br/> <br/> \**使用 Dropbox 报告确定外部帐户。指示最终用户在迁移后重新共享其内容。* <br/> |
   
FastTrack 专家在迁移过程中执行以下操作： 
- 执行迁移演练研究，其中涉及所选迁移方案的过程和方法。
- 提供该方案的评估和迁移工具的先决条件（如果适用）。   
- 为迁移团队提供访问源和目标环境以进行评估和迁移的先决条件。 
- 提供评估工具以执行目标源环境评估，或提供有关如何使用本机源平台函数创建评估报表的说明。   
- 协助部署和运行评估工具和迁移工具（如果适用）。   
- 配置迁移基础结构以准备内容迁移（如果适用）。    
- 执行有限的测试迁移，以验证迁移基础结构和必需的先决条件。   
- 将开箱即用目标 SharePoint Online 网站设置为迁移的一部分。    
- 在快速迁移前执行试点迁移。   
- 提供所选方案的迁移计划的指导。 
- 根据由客户提供并经 FastTrack 资源验证的迁移计划执行快速迁移波。   
- 在每个迁移窗口后提供迁移结果。   
- 参与快速迁移问题分类并提供可能的修正方案的指导。   
- 为每个快速迁移窗口提供最终迁移报表。   
- 在迁移完成后最多五天时的用户验收测试中提供迁移后协助。
    
在迁移过程中执行以下操作： 
- Provide project resources recommended for assessment and migration activities. These include: 
  - 项目管理。 
  - 用户验收测试 (UAT)。  
  - 负责源和目标内容平台的管理员。  
- 提供有关评估和迁移活动的基础结构先决条件（如果需要）。  
- 向 FastTrack 专家授予对源环境和目标环境的访问权限及其他权限，以方便专家执行迁移活动（如果需要）。
    > [!NOTE]
    > Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
- 提供支持评估和迁移的先决条件并执行所需的活动。   
- 安装由 FastTrack 提供的评估工具并完成评估数据收集活动（如果适用）。   
- 安装由 FastTrack 提供的迁移软件本地部署（如果适用）。   
- 完成由 FastTrack 提供的修正报告中所述的修正活动（如果适用）。  
- 提供使用 FastTrack 模板和指南的迁移计划。   
- 进行迁移质量保证和用户验收测试。   
- 执行迁移后迁移修正（如果适用）。
- 计划并实施更改管理和最终用户通信（如果适用）。   
- 管理和配置成功完成评估和迁移活动所需的源系统和设备的任何更改。
- 需至少提前三 (3) 天就每个迁移事件提供采用所定义方法的计划和包含要迁移的特定用户数据的列表。
- 在迁移批处理前至少提前 24 小时从计划中删除用户数据。 这应与最终的迁移批处理对应。
> [!NOTE]
> Microsoft 无法保证文件迁移速度。
    
## <a name="migration-to-onedrive-for-business"></a>迁移到 OneDrive for Business

 ### <a name="enable-to-migrate"></a>启用迁移
  
If you use Microsoft to migrate your data, we provide guidance to enable both OneDrive for Business and the source environment for migration. Depending on the source, we may perform various Enable steps. We help you with some activities by using a combination of tools, documentation, and guidance, and by performing configuration tasks where applicable and feasible.
  
You may need to provide appropriate access and permissions to Microsoft to perform some activities. If you don't provide access and/or permissions, you need to perform certain defined tasks yourself with guidance from Microsoft. 
  
### <a name="migration-policy-and-steps"></a>迁移策略和步骤
  
> [!NOTE]
> 迁移时间段也称为迁移批处理。

#### <a name="commercial-and-uk-government"></a>商业和英国政府

Migrations are done on a standardized prescheduled 24 hours a day, seven (7) business days a week (24x7) basis in predefined migration time slots. There are three migration batches per migration day.

#### <a name="us-governmentdod"></a>美国政府/DOD

Migrations are done on standardized prescheduled 24 hours a day, five (5) business days a week (24x5) basis in predefined migration time slots. There are three migration batches per migration day. There are five migration days in a week from Monday 2:00AM Coordinated Universal Time (UTC) to Friday midnight UTC. This means that the last scheduled migration is Friday 8:00 PM UTC.
    
- 所有迁移都需要对源环境的相应访问权限和许可。   
- 所有迁移都需满足 [SharePoint Online 和 OneDrive for Business：软件边界和限制](https://go.microsoft.com/fwlink/?LinkId=698855)中所述的 OneDrive for Business 配额。
    
 ### <a name="end-state"></a>结束状态
  
完成迁移批处理后的预期结束状态包括：  
- 在源环境中正确计划且符合条件的源中的数据将迁移到 OneDrive for Business 中。  
- Microsoft 提供的迁移批处理的迁移后报告。
    
完成所有迁移后的预期结束状态包括：
- 符合条件的源中的数据迁移到 Office 365 中，如下表所定义。  
- 要迁移的数据类型视源环境而定，如下表所述。
    
|||||
|:-----|:-----|:-----|:-----|
|**源环境**|**迁移类型**|**迁移内容**|**不会迁移的内容**|
|**任何支持 SMB 2.0 及更高版本的文件共享设备**  <br/> |单通道或多通道  <br/> | 文档  <br/>  文件和文件夹结构  <br/>  用户级别的文件和文件夹权限\*  <br/>  组级别的文件和文件夹权限\*  <br/>  小于 15GB 的文件  <br/>  基本文档和文件夹元数据：  <br/>  创建日期  <br/>  修改日期  <br/>  创建者  <br/>  上次修改者  <br/> <br/>\**必须配置目录同步。只迁移对 Windows 文件资源管理器公开的 NTFS 权限。不会迁移文件共享设备上直接托管的权限。如果数据存储在 SMB 2.0 设备上，只会迁移 SMB 协议公开的与 NTFS 等同的权限。* <br/> | 所有权历史记录和旧版本  <br/>  内容中嵌入的 URL 的转换后对象  <br/>  旧版本  <br/>  Windows 文件和文件夹属性（如只读和隐藏）  <br/>  非 Windows 新技术文件系统 (NTFS) 和 NTFS 高级权限和特殊设置：  <br/>  显式拒绝权限（在迁移后删除的权限、从属于并行权限的内容或父文件夹上的权限）  <br/>  NTFS 审核配置  <br/>  FCI 提供的附加文件元数据  <br/>  无法访问或已损坏的文档  <br/>  隐藏的共享  <br/>  共享（如在共享级别授予的权限）  <br/>  超出当前 [SharePoint Online 限制和局限](https://go.microsoft.com/fwlink/?linkid=846724)的文件或文件夹 <br/> |
|**单个 G 套件环境（仅限 Google 云端硬盘）**  <br/> |单通道或多通道  <br/> | Google 文档、工作表和幻灯片（文件包括超过10 MB的，转换为等同的 Office 格式）  <br/>  文件和文件夹结构  <br/>  用户级别文件夹权限  <br/>  组级别文件夹权限  <br/>  小于 15GB 的文件  <br/>  基本文档和文件夹元数据：  <br/>  创建日期  <br/>  修改日期  <br/>  创建者  <br/>  最后一次修改者  <br/> 共享驱动器 （文件夹和文件） <br/> 要迁移的 Google 云端硬盘帐户所拥有的共享内容（若与用户或组显式共享的话）\* <br/> <br/>\**使用 Google 云端硬盘管理员确定外部帐户。指示最终用户在迁移后重新共享其内容。* <br/> | 所有权历史记录、旧版本和注释  <br/>  文件和文件夹说明、文件夹颜色  <br/>   用户级别文件权限  <br/>  组级别文件权限  <br/> 高级元数据 <br/>  文件锁定属性 <br/> 内容中嵌入的 URL 的转换后对象  <br/> 放入回收站的项 <br/> 无法访问或已损坏的文档 <br/> 被阻止的用户或非活动用户 <br/> Google 照片 <br/> Forms、地图和其他已连接应用 <br/> Google 绘图 <br/> 组织外部的共享内容 <br/> 不属于Google 云端硬盘帐户的内容被迁移 <br/> 外部用户的权限和基本元数据<br/> 共享驱动器成员权限\*<br/> 超出当前 [SharePoint Online 限制和局限](https://go.microsoft.com/fwlink/?linkid=846724)的文件或文件夹 <br/><br/> \**使用 Google 云端硬盘管理员识别共享驱动器成员身份。指示指定的最终用户在迁移之前，在目标上配置成员资格设置。* <br/> |
|**Box（Starter、Business、Enterprise）**  <br/> |单通道或多通道  <br/> | 文档  <br/>  文件和文件夹结构  <br/>  用户级别文件夹权限  <br/>  组级别文件夹权限  <br/>  小于 15GB 的文件  <br/>  基本文档和文件夹元数据：  <br/>  创建日期  <br/>  修改日期  <br/>  创建者  <br/>  最后一次修改者  <br/>  要迁移的 Box 帐户所拥有的共享内容（若与用户或组显式共享的话）\*  <br/><br/> \**使用 Box 报告确定外部帐户。指示最终用户在迁移后重新共享其内容。* <br/> | 所有权历史记录、旧版本和注释  <br/>  文件和文件夹说明  <br/>  用户级别文件权限  <br/>  组级别文件权限  <br/>  Box 标记和高级元数据  <br/>  文件锁定属性  <br/>  内容中嵌入的 URL 的转换后对象  <br/>  放入回收站的项  <br/>  无法访问或已损坏的文档  <br/>  被阻止的用户或非活动用户  <br/>  Box 备注（未经转换将无法迁移）  <br/>  Box 应用、书签、收藏夹和工作流  <br/>  已迁移的 Box 帐户不拥有的内容（共享文件夹）  <br/>  外部用户的权限和基本元数据\*  <br/>  超出当前 [SharePoint Online 限制和局限](https://go.microsoft.com/fwlink/?linkid=846724)的文件或文件夹 <br/> |
|**用于 Teams的 Dropbox（标准版和高级版）**  <br/> |单通道或多通道  <br/> | 文档  <br/>  文件和文件夹结构  <br/>  用户级别文件夹权限  <br/>  组级别文件夹权限  <br/>  小于 15GB 的文件  <br/>  基本文档和文件夹元数据：  <br/>  创建日期  <br/>  修改日期  <br/>  创建者  <br/>  最后一次修改者  <br/> 共享团队文件夹和内容 <br/> 要迁移的 Dropbox 帐户所拥有的共享内容（若与用户或组显式共享的话）\*  <br/> <br/> \**使用 Dropbox 报告确定外部帐户。指示最终用户在迁移后重新共享其内容。* <br/> | 所有权历史记录、旧版本和注释 <br/>  文件和文件夹说明 <br/>  用户级别文件权限  <br/>  组级别文件权限    <br/> 高级元数据  <br/>  文件锁定属性  <br/>  内容中嵌入的 URL 的转换后对象  <br/>  放入回收站的项  <br/>  无法访问或已损坏的文档  <br/>  已卸载的 Dropbox 文件夹 <br/>  已删除或已断开连接的用户 <br/>  Dropbox Paper 文件、Dropbox Showcase 和 Dropbox Space  <br/> Dropbox 应用及收藏夹（已固定或加星标） <br/> 已迁移的 Dropbox 帐户不拥有的内容  <br/>  外部用户的权限和基本元数据\*  <br/>  超出当前 [SharePoint Online 限制和局限](https://go.microsoft.com/fwlink/?linkid=846724)的文件或文件夹 <br/> <br/> \**使用 Dropbox 报告确定外部帐户。指示最终用户在迁移后重新共享其内容。* <br/> |
   
FastTrack 专家在迁移过程中执行以下操作：  
- 执行迁移演练研究，其中涉及所选迁移方案的过程和方法。   
- 提供该方案的评估和迁移工具的先决条件（如果适用）。  
- 为迁移团队提供访问源和目标环境以进行评估和迁移的先决条件。   
- 提供评估工具以执行目标源环境评估，或提供有关如何使用本机源平台函数创建评估报表的说明。    
- 协助部署和运行评估工具和迁移工具（如果适用）。   
- 配置迁移基础结构以准备内容迁移（如果适用）。    
- 执行有限的测试迁移，以验证迁移基础结构和必需的先决条件。    
- 将开箱即用目标 OneDrive for Business 网站设置为迁移的一部分。    
- 在快速迁移前执行试点迁移。
- 提供所选方案的迁移计划的指导。   
- 根据由客户提供并经 FastTrack 资源验证的迁移计划执行快速迁移波。   
- 在每个迁移窗口后提供迁移结果。   
- 参与快速迁移问题分类并提供可能的修正方案的指导。 
- 为每个快速迁移窗口提供最终迁移报表。   
- 在迁移完成后最多五天时的用户验收测试中提供迁移后协助。
   
在迁移过程中执行以下操作：
- Provide project resources recommended for assessment and migration activities. These include:
  - 项目管理。
  - UAT。
  - 负责源和目标内容平台的管理员。
- 提供有关评估和迁移活动的基础结构先决条件（如果需要）。   
- 向 FastTrack 专家授予对源环境和目标环境的访问权限及其他权限，以方便专家执行迁移活动（如果需要）。  
    > [!NOTE]
    > Migrations only use accounts that adhere to security requirements defined during onboarding. If you don't use such accounts, you may experience migration delays. 
- 安装由 FastTrack 提供的评估工具并完成评估数据收集活动（如果适用）。
- 安装由 FastTrack 提供的迁移软件本地部署（如果适用）。  
- 完成由 FastTrack 提供的修正报告中所述的修正活动（如果适用）。   
- 提供使用 FastTrack 模板和指南的迁移计划。 
- 就每个迁移事件提供采用所定义方法的计划和包含要迁移的特定用户数据的列表。
- Drop user data from the schedule until 24 hours in advance of the migration batch. This should correspond to the final migration batch.
- 进行迁移质量保证和用户验收测试。   
- 执行迁移后迁移修正（如果适用）。  
- 计划并实施更改管理和最终用户通信（如果适用）。  
- 管理和配置成功完成评估和迁移活动所需的源系统和设备的任何更改。
    
> [!NOTE]
> Microsoft 无法保证文件迁移速度。 


