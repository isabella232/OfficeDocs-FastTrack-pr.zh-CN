---
title: 附录 B：FastTrack 中心的其他权益
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 09/04/2018
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Priority
ms.assetid: 880b4cf1-e778-4725-af25-7fb6fe10c504
description: 为 Exchange Online 租户购买至少 20,000 个许可证的客户有资格享受 FastTrack 中心附加服务。有关详细信息，请参阅“符合条件的服务和计划”。
ms.openlocfilehash: 98449dcc6576576996424d8a6160d6891a87d83c
ms.sourcegitcommit: 7b319c33a4f1062b508e941643e4f1f135309a98
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/19/2018
ms.locfileid: "24021684"
---
# <a name="appendix-b---fasttrack-center-additional-benefit"></a>附录 B - FastTrack 中心的附加权益

为 Exchange Online 租户购买至少 20,000 个许可证的客户有资格享受 FastTrack 中心附加服务。有关详细信息，请参阅[符合条件的服务和计划](eligible-services-and-plans.md)。 
  
## <a name="onboarding-and-migration-phases"></a>载入和迁移阶段

## <a name="core"></a>核心

核心载入服务附加服务包括地域冗余 Active Directory 联合身份验证服务 (AD FS) 的配置指导和此服务的 AD FS 客户端访问策略。 
  
## <a name="exchange-online"></a>Exchange Online

对于 Exchange Online，我们提供以下项目的配置指导：
- 使用 Exchange Online 设置统一消息 (UM)。
- 配置 Exchange Online 和旧版本地公用文件夹之间的共存。
- 启用邮件的应用程序集成。 
- 邮件迁移计划和分组。
    
## <a name="skype-for-business-online"></a>Skype for Business Online

对于 Skype for Business Online，我们为本地 Lync 和 Skype for Business 用户提供到 Skype for Business Online 的迁移指导。
  
## <a name="office-365-proplus"></a>Office 365 专业增强版

对于 Office 365 ProPlus，我们提供以下指导： 
- 根据 Microsoft 最佳做法进行评估和计划，重点是让环境准备好执行初始部署和更新管理。 
- 使用 Office 部署工具开发部署配置和更新设置。 
- 使用 System Center Configuration Manager 进行部署打包。  
- 部署并配置 Office 遥测来指导你针对应用程序兼容性评估业务关键型 Office 文档和解决方案的使用情况。
    
## <a name="fasttrack-responsibilities"></a>FastTrack 责任

FastTrack 专家在载入期间承担以下责任。这些责任可能会补充或取代 [FastTrack 责任](fasttrack-responsibilities.md)中定义的活动。
  
## <a name="general"></a>常规

- 为你提供远程支持协助，帮助你成功完成规划开发和实施，以及[载入和迁移阶段](#onboarding-and-migration-phases)中所述的必要配置活动。
    
## <a name="assess-phase"></a>评估阶段

- 进行一次成功的计划通话来为成功用户采用提供指导。 
- 评估你的环境以支持地域冗余的 AD FS 配置。  
- 进行一个评估，以确定 AD FS 客户端访问的要求。
    
## <a name="enable-phase"></a>启用阶段

### <a name="geo-redundant-ad-fs-guidance"></a>异地冗余 AD FS 指南

- 为跨越两 (2) 个数据中心的异地冗余 AD FS 拓扑提供标准的参考体系结构设计。标准的体系结构可提供：
  - 针对作用域内的服务提供联合身份验证，以获取 FastTrack 中心权益。 
  - 单一站点弹性。  
  - 高可用性和故障转移。  
  - 调整大小指导。 
- 提供有关将 Windows 内部数据库和 SQL Server 用作 AD FS 服务器场的数据库实例的指导。   
- 验证已对作用域中的每个林建立联合身份验证。  
- 确认针对最多 10 个用户具有联合身份验证功能。
    
> [!NOTE]
> 对于具有多个 Active Directory 林配置的附加服务合格客户，AD FS 部署位于作用域中。 
  
### <a name="ad-fs-client-access-policy-guidance"></a>AD FS 客户端访问策略指南

- 检查保护 Office 365 资源安全所需的策略和配置。  
- 提供指导和帮助以便为支持方案边界内标识的客户端访问方案配置 AD FS 客户端访问策略。有关详细信息，请参阅 [Limiting Access to Office 365 Services Based on the Location of the Client](https://go.microsoft.com/fwlink/?LinkID=525689)（根据客户端位置限制对 Office 365 服务的访问权限）。 
- 对于配置最多 10 个用户的标识访问方案，通过修改客户端访问策略验证联合身份验证功能。
    
## <a name="exchange-online"></a>Exchange Online

### <a name="exchange-unified-messaging-guidance"></a>Exchange 统一消息指南

- 提供 Exchange Online 所需配置指导以启用多达 10 个： 
  - UM 拨号计划。   
  - UM 邮箱策略。 
  - 自动助理。  
- 为本地 Lync 或 Skype for Business 环境配置提供指导以启用 UM，主要针对：  
  - Exchange Online托管的策略。  
  - Exchange Online托管的语音邮件策略。 
  - UM 自动助理联系人和 Outlook 语音邮件将用户重定向到 Exchange Online。 
  - 协助创建联合身份验证所需的服务位置 (SRV) 记录。
> [!NOTE]
> 可以用受支持的 UM IP 网关和会话边界控制器 (SBC) 配置 UM。有关详细信息，请参阅 [电话系统与 UM 集成](https://go.microsoft.com/fwlink/?LinkID=809293)。 
  
### <a name="public-folder-coexistence-guidance"></a>公用文件夹共存指南

- 提供有关单个公用文件夹树共存的指导，包括：  
  - 在 Exchange 2007、Exchange 2010 和 Exchange 2013 中准备公用文件夹。 
  - 将 Exchange 2007、Exchange 2010 和 Exchange 2013 公用文件夹层次结构与 Exchange Online 同步时需要的 Windows PowerShell cmdlet。  
  - 可将公用文件夹访问重定向到本地公用文件夹的 Exchange Online 配置。  
  - 对从 Exchange Online 到单个 Exchange 2007、Exchange 2010 或 Exchange 2013 本地环境的公用文件夹的访问权限配置。  
  - 协助对 Exchange Online 中的最多 10 个用户的公用文件夹环境的访问验证。
    
### <a name="mail-enabled-application-integration-guidance"></a>启用邮件的应用程序集成指南

- 针对以下各项提供指导模板：  
  - 批量邮件应用程序。  
  - 通过 Exchange 路由电子邮件的应用程序。  
  - 使用 Exchange 邮箱的应用程序。  
  - 需要在 Exchange 服务器上安装第三方或自定义组件的应用程序。
    
### <a name="mailbox-migration-planning-and-grouping"></a>邮箱迁移计划和分组

- 在创建迁移计划方面提供指导，其中包括：  
  - 对用户和资源进行批量分组。
  - 通过迁移批处理协调所需软件程序包的部署。   
  - 指导创建面向最终用户的通信计划。 
  - 协调迁移批处理的大小、错误率，以及预期的支持协助。 
- 提供相关指导，以根据客户给定的相关信息，按类型、业务职能和委派访问权限对用户和资源邮箱进行批量分组。
    
## <a name="skype-for-business-online"></a>Skype for Business Online

- 提供有关在 Skype for Business 混合部署中批量迁移用户（保留用户的联系人列表）的指南。
    
## <a name="office-365-proplus"></a>Office 365 专业增强版

- 为以下操作提供指导和帮助：  
  - 根据 Microsoft 最佳做法，评估和计划初始部署和更新管理。
  - 部署和配置 Office 遥测。 
  - 使用组策略为 Office 2013 及更高版本的客户端启用遥测日志记录。 
  - 为以前的 Office 客户端（Office 2003、Office 2007、和 Office 2010）部署 Office 遥测代理。 
  - 部署遥测处理器。 
    > [!NOTE]
    > 此操作需要一个文件共享位置来存储遥测数据以及需要一个运行 SQL Server 2005 及更高版本的服务器来提交处理的数据。 
  
## <a name="your-responsibilities"></a>你的责任

你在载入期间将承担以下责任。这些是对[你的责任](your-responsibilities.md)部分中定义的责任的补充。 
  
- 根据项目计划分配和管理资源。  
- 及时采取措施以缓解风险并解决客户、合作伙伴项目经理和 FastTrack 经理提出的问题。   
- 查看状态报告，并采取相应的措施。   
- 为运营发起人或负责人分配运营指导委员会的决策权。  
- 分配一名执行发起人与 Microsoft 执行发起人合作。  
- 成立每月指导委员会会议。
    

  

