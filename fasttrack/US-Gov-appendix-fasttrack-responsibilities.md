---
title: Office 365 美国政府版的 FastTrack 责任
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 06/04/2019
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: FastTrack 专家在载入期间将承担以下责任。
ms.openlocfilehash: c646583e121bbf453da571253968461425f6d5ec
ms.sourcegitcommit: 0e76ab0f36619dee923201098936573be14b4560
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/03/2019
ms.locfileid: "34673663"
---
# <a name="fasttrack-responsibilities-for-office-365-us-government"></a>Office 365 美国政府版的 FastTrack 责任

FastTrack 专家在载入期间将承担以下责任。
  
## <a name="general"></a>概要

- 为你提供远程支持协助，帮助你成功完成开发和实施规划，以及阶段说明中所述的必要配置活动。
- 提供可用的文档和软件工具、管理控制台和脚本，以指导你减少或消除配置任务，并成功规划资源。 
    
## <a name="initiate-phase"></a>启动阶段

- 与你协作，了解你对服务的意图、组织目标和使用规划。 
- 与用户共同使用 Office 365 协作服务（如 Microsoft Teams），开始执行登录操作。 
- 定义您需要初始启用的符合条件的服务。 
    
## <a name="assess-phase"></a>评估阶段

- 进行一次成功的计划通话来为你提供成功用户采用的指导。  
- 提供管理概述。  
- 针对以下内容提供相关指导： 
  - 域名系统 (DNS)、网络和基础结构需求。  
  - 客户端需求（Internet 浏览器、客户端操作系统、移动设备和服务需求）。
  - 用户标识和设置。 
  - 将已购买且定义的符合条件的服务作为初始启用的一部分。
  - 成功推行服务采用和值。   
- 制定修正活动的日程表。
- 提供修正清单。   
- 访问现有的 SharePoint Server 2013 或 SharePoint Server 2016 基础结构，包括：  
  - SharePoint Online 混合的先决条件。  
  - SharePoint Online 混合功能的本地基础结构准备。  
  - 访问所需的 SharePoint Online 终结点。 
  - OneDrive for Business 混合的访问群体。    
- 访问现有的 Lync 或 Skype for Business Online 基础结构，其中包括：  
  - 支持的 Skype for Business 客户端部署策略。  
  - 对终结点的访问权限。  
  - 连接质量。  
  - 带宽预估。  
  - 支持拆分域服务器配置的先决条件。  
  - 准备将确定的用户迁移到 Skype for Business Online。  
- 评估邮件基础结构，其中包括：   
  - 整个邮件流和传递原则。  
  - 客户端访问（包括已发布的现有客户端访问终结点）。  
  - 源邮件环境的集成需求。 
- 如果使用 FastTrack 中心数据迁移服务并且如果您符合条件，则提供数据迁移。
    
## <a name="remediate-phase"></a>修正阶段

- 根据达成一致的日程表与你进行电话会议，以检查修正活动和成功计划的进度。   
- 引导用户运行评估工具，以发现和修正问题并解释结果。
    
## <a name="enable-phase"></a>启用阶段

针对以下内容提供相关指导： 
- 评估成功计划的进度并确定未来你需要的协助。    
- 激活您的 Office 365 租户。
- 配置 TCP/IP 协议和防火墙端口。   
- 为符合条件的服务配置 DNS。   
- 验证与 Office 365 的连接。   
- 将您的本地 Active Directory 与 Azure Active Directory 连接：   
  - 在你的 Active Directory 域服务 (AD DS) 和 Office 365 间安装目录同步服务器（如果需要）。   
  - 根据需要，使用 Azure Active Directory Connect 工具配置与 Office 365 (Azure Active Directory) 进行的密码同步（密码哈希）。  
  - 对于单林和多林环境：
      - 配置 Azure Active Directory 直通身份验证 (如果需要) (不适用于 GCC 高或 DoD 计划)。
      - 配置 Azure Active Directory 无缝单一登录 (SSO) (如果需要) (不适用于 GCC 高或 DoD 计划)。
    > [!NOTE]
    > 如果 Active Directory 林之间存在林信任且名称后缀路由配置正确，则支持为多林环境配置 Azure Active Directory 直通身份验证。可以在多个本地服务器上安装其他代理，提供登录请求所需的高可用性。有关详细信息，请参阅 [Azure Active Directory 直通身份验证：快速入门](https://go.microsoft.com/fwlink/?linkid=860094)和 [Azure Active Directory 无缝单一登录：快速入门](https://go.microsoft.com/fwlink/?linkid=860095)。[!NOTE]
    > 若要详细了解直通身份验证限制，请参阅 [Azure Active Directory 直通身份验证：当前限制](https://go.microsoft.com/fwlink/?linkid=860356)。[!NOTE]
    > 若要详细了解无缝 SSO 问题，请参阅[排除 Azure Active Directory 无缝单一登录故障](https://go.microsoft.com/fwlink/?linkid=841926)。 
- 对于单个林，当联合标识是目标时： 
  - 安装和配置 AD FS，以供在单个站点的容错配置中对 Office 365 进行本地域身份验证（如果需要）。  
  - 必要时，安装和配置 WAP，以将 AD FS 基础结构发布到 Internet。 
    > [!NOTE]
    > 对于所有多个林配置，AD FS 部署不在此范围内。 
- 测试 SSO 功能（如果已部署）。   
- 成功推动服务采用和价值。
    
## <a name="exchange-online"></a>Exchange Online

针对以下内容提供相关指导： 
- 创建或更新 DNS 记录。    
- 在源邮件系统和 Office 365 环境之间启用电子邮件路由。    
- 配置 Exchange Online Protection 功能（如果在你的订阅中可用，则包括 Exchange Online 高级威胁防护 功能）并验证你的 MX 记录指向所有已验证的启用邮件的域的 Office 365。   
- 在一个本地 Exchange 组织和 Office 365 之间*或*在多个本地 Exchange 组织和 Office 365 之间配置混合设置。 
- 使用 Exchange Online 设置统一消息 (UM) (UM 在 GCC DoD 计划中不可用)。 
    
有关数据迁移责任的详细信息，请参阅[数据迁移](O365-data-migration.md).。
  
## <a name="sharepoint-online"></a>SharePoint Online

针对以下内容提供相关指导：
- 设置用户（包括许可）。   
- 为你的 SharePoint Online 管理员启用站点创建。   
- 规划网站集。   
- 保护内容安全和管理权限。   
- 启用个人网站和社交功能。   
- 配置 SharePoint Online 功能。    
- 如果使用了 FastTrack 中心数据迁移服务或者你符合使用该服务的条件，则提供数据迁移。  
- 评估 SharePoint Online 混合所需的本地 SharePoint 场基础结构配置。    
- 使用工具和自动化执行以下操作： 
  - 配置本地云 Search Service 应用程序。    
  - 配置 SharePoint 本地和云环境间的信任。   
- 配置本地 SharePoint 站点以使用 SharePoint Online 混合功能。
    
## <a name="onedrive-for-business"></a>OneDrive for Business

针对以下内容提供相关指导： 
- 确定本地 SharePoint 版本和集成选项。    
- 确定同步和标识选项。   
- 选择推出选项：   
  - 实时推出。  
  - 分步推出（按顺序和分阶段）。   
- 准备用于 OneDrive for Business 部署的本地环境。  
  - 确定正确的 OneDrive for Business 同步客户端。 
  - 配置 DNS、网络端口和防火墙。   
- 分配最终用户许可证。   
- 设置由 SharePoint Online 访问群体来控制和管理谁能够获取 OneDrive for Business。    
- 将 OneDrive for Business 同步客户端部署到桌面。   
- 如何配置 SharePoint Online 混合 OneDrive for Business 重定向（仅 SharePoint 2013 和 SharePoint 2016）。  
- 数据迁移（如果使用 FastTrack 中心数据迁移服务并且如果你符合条件）。
    
## <a name="skype-for-business-online"></a>Skype for Business Online

针对以下内容提供相关指导：
- 为 Office 365 配置 Skype for Business 身份。   
- 可为 Office 365 启用联机会议、即时消息 (IM) 和状态功能。  
- 创建与受支持的会议室系统设备相关联的帐户（最多 10 个帐户）。    
- 配置拆分域服务器环境，以支持 Lync 混合或 Skype for Business Online 混合方案（如果适用）。   
- 启用音频会议：   
  - 会议桥默认设置的组织设置。   
  - 向许可用户分配会议桥。 
- 启用电话系统 (在 GCC 高或 DoD 计划中不可用):  
  - 启用电话系统和通话套餐载入（在可用市场中）。 
  - 向许可用户分配号码。  
  - 通过 UI 进行本地号码端口定位的指南（最多到 999）。  
  - 超过 999 的本地号码端口定位 SR 支持。  
- 启用 Skype for Business 会议广播 (在 GCC 高或 DoD 计划中不可用):  
  - 启用 Skype for Business 会议直播载入指南。  
  - 使用会议直播服务的联合身份验证组织设置。
    
## <a name="microsoft-teams"></a>Microsoft Teams

> [!NOTE]
> 以下项在 GCC High 或 DoD 计划中不可用。

针对以下内容提供相关指导：
- 确认最低要求。   
- 配置防火墙端口。  
- 设置 DNS。  
- 确认是否已在 Office 365 租户上启用 Microsoft Teams。   
- 启用或禁用用户许可证。  
- Microsoft Teams 客户端通讯组。    
- IT 专业人士和管理员功能。 
- 核心产品功能。  
- 客户成功模板。
    
## <a name="power-bi"></a>Power BI

针对以下内容提供相关指导：
- 审阅 Power BI 订阅计划。    
- 添加 Power BI 服务。    
- 下载 Power BI Desktop 应用。
    
## <a name="project-online"></a>Project Online

针对以下内容提供相关指导：  
- 审阅订阅计划。  
- 验证基本 SharePoint 功能。    
- 添加 Project Online 服务。  
- 将用户添加到 Project Online，包括 ERP 同步。  
- 通过创建项目，验证基本 Project Online 功能。
    
## <a name="yammer-enterprise"></a>Yammer Enterprise

提供有关将单个 Yammer Basic 网络转换为单个 Yammer Enterprise 网络的指导。

> [!NOTE]
> Yammer Enterprise 不是 Office 365 美国政府的一个组件, 但可以免费获取, 作为针对 GCC 中的 Office 365 许可的每个用户的独立提供。 此优惠目前仅限于在企业协议和企业订阅协议下购买 Office 365 GCC 的客户。 Yammer 在 GCC High 或 DoD 计划中不可用。
  
## <a name="office-365-proplus"></a>Office 365 专业增强版

针对以下内容提供相关指导：
- 解决部署问题。   
- 使用 [Microsoft 365 管理中心](https://go.microsoft.com/fwlink/?linkid=2032704)和 Windows PowerShell 分配最终用户许可证。  
- 使用即点即用从 Office 365 门户安装 Office 365 专业增强版。   
- 在你的 iOS、Android 或 Windows Mobile 设备上安装 Office Mobile 应用（如 Outlook Mobile、Word Mobile、Excel Mobile 和 PowerPoint Mobile）。   
- 使用 Office 2016 部署工具或组策略模板配置更新设置。   
- 为 Office 365 专业增强版设置一个现场分发服务器，包括帮助创建 configuration.xml 文件以与 Office 365 部署工具一起使用。   
- 使用 System Center Configuration Manager 的部署，包括帮助创建 System Center Configuration Manager 打包。

    


