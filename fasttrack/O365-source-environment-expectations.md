---
title: 对源环境的预期
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 09/04/2019
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack 中心权益可以指导你设置与源环境的集成级别（例如，如果在源环境中你已经拥有想要移动到 Office 365 的服务）。
ms.openlocfilehash: f67acdbf0c0eba71306777bf4673b456d0f7d268
ms.sourcegitcommit: df949b40ade215de00f74771ffadf0d3be0de797
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/03/2019
ms.locfileid: "36712154"
---
# <a name="source-environment-expectations"></a>对源环境的预期

FastTrack 中心权益可以指导你设置与源环境的集成级别（例如，如果在源环境中你已经拥有想要移动到 Office 365 的服务）。
  
> [!NOTE]
> 如果必须集成，对于相应的应用程序，源环境必须处于最低级别。 
  
下表列出了对现有源环境的上手预期。\*

|**活动**|**对源环境的预期**|
|:-----|:-----|
|**核心入门** | 将林功能级别设置为 Windows Server 2003 前向的 Active Directory 林，具有以下林配置：  <br/>      单个 Active Directory 林。  <br/>    单一 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。  <br/>  多个 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。  <br/>  多个 Active Directory 帐户林，其中的一个林是一个含有 Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business 的集中式 Active Directory 帐户林。  <br/>  多个 Active Directory 帐户林，每一个都有自己的 Exchange 组织。 <br/> <br/> **注意**  *对于多林 Active Directory 的情况，如果部署了 Lync 2010、Lync 2013 或 Skype for Business，就必须将其部署在与 Exchange 同在的那个 Active Directory 林中。*   <br/>  <br/>      **注意**  *在 Exchange 多混合配置中实施带有多个 Exchange 组织的多个 ActiveDirectory 林时，不支持源林之间的共享用户主体名称 (UPN) 命名空间。Exchange 组织之间的主要 SMTP 命名空间也应该进行分隔。有关详细信息，请参阅[具有多个 Active Directory 林的混合部署](https://go.microsoft.com/fwlink/?linkid=845444)。*     <br/>   <br/>   **注意**  *对于所有的多林配置，AD FS 部署超出了 FastTrack 中心权益的范围。*           |
|**Exchange Online 入门** | 您的环境必须具有以下最低级别之一：  <br/>  具有 Exchange Server 2003 前向的单个或多个 Exchange 组织。  <br/>  一个 IBM Domino 7.0.3 前向环境（ [附录 A：从 IBM Domino 迁移到 Exchange Online](O365-from-ibm-domino-to-exchange-online.md)）。  <br/>  一个支持 Internet 邮件访问协议 (IMAP) 的电子邮件环境。  <br/>  单个 G 套件环境（仅限 Gmail、联系人和日历）。  <br/>  一个 Novell GroupWise 7.0.4 前向环境。  <br/><br/> **注意**  *若要了解多地理位置功能的信息，请参阅 [Exchange Online 中的多地理位置功能](https://go.microsoft.com/fwlink/?linkid=872776)。*           |
|**SharePoint Online 和 OneDrive for Business 入门**  | **SharePoint 混合**  <br/>  SharePoint 混合 配置包含配置混合搜索、站点、分类、内容类型、OneDrive for Business（扩展的应用启动器）和从本地连接到单个目标 SharePoint Online 环境的 Extranet 网站和自助式网站创建。若要启用 SharePoint 混合，必须具有以下本地 SharePoint Server 环境之一：  <br/> <br/> ***SharePoint Server 2013***  <br/>  适用于混合内容类型的 2017 年 6 月公开更新 (PU)。有关详细信息，请参阅[配置混合 SharePoint 分类和混合内容类型](https://go.microsoft.com/fwlink/?linkid=853547)。<br/>  适用于自助式网站创建配置的 2017 年 3 月 PU。仅 SharePoint Server 2013 支持混合自助式网站创建。有关详细信息，请参阅 [Hybrid self-service site creation](https://go.microsoft.com/fwlink/?linkid=846015)（混合自助式网站创建）。  <br/>  具有混合分类的 2016 年 11 月 PU 前向。有关详细信息，请参阅[规划混合 SharePoint 分类](https://go.microsoft.com/fwlink/?linkid=844867)。<br/>  适用于所有其他混合配置方案的 2016 年 7 月 PU 前向。  <br/><br/> **注意**  *仅 SharePoint Server 2013 支持 SharePoint Server 2013 混合方案。这些方案在 SharePoint Foundation 2013 中不受支持。*  <br/>   <br/>    ***SharePoint Server 2016***  <br/>  适用于混合内容类型的 2017 年 6 月 PU。有关详细信息，请参阅[配置混合 SharePoint 分类和混合内容类型](https://go.microsoft.com/fwlink/?linkid=853547)。<br/>  具有混合分类的 2016 年 11 月 PU（功能包 1）。有关详细信息，请参阅[规划混合 SharePoint 分类](https://go.microsoft.com/fwlink/?linkid=844867)。<br/>  适用于所有其他混合配置方案的 2016 年 7 月 PU 前向。  <br/><br/> **注意**  *FastTrack 中心 权益不支持将本地 SharePoint 环境升级到 SharePoint Server 2013 或 SharePoint Server 2016。有关详细信息，请参阅[适用于 SharePoint 混合功能的最小公共更新级别](https://go.microsoft.com/fwlink/?linkid=853548)。*   <br/><br/>        **注意**  *若要了解多地理位置功能的信息，请参阅 [Office 365 中的 OneDrive 和 SharePoint Online 多地理位置功能](https://go.microsoft.com/fwlink/?linkid=831056)。*           |
|**Microsoft Teams 入门**  | 在适用于 Office 365 的 Azure Active Directory 中启用标识。  <br/>  对 SharePoint Online 启用的用户。  <br/>  Exchange 邮箱已存在，联机和/或本地（在 Exchange 混合配置中）。  <br/>  针对 Office 365 组启用。  <br/><br/> **注意**  *如果未为用户分配和启用 SharePoint Online 许可证，他们将不会在 Office 365 中拥有 OneDrive for Business 存储。文件共享将继续在频道中工作，但用户无法在 Office 365 中没有 OneDrive for Business 存储的聊天中共享文件。Microsoft Teams 不支持本地 SharePoint。*   <br/> <br/>       **注意**  *理想的状态是将所有用户的邮箱都托管在 ExchangeOnline 上。将邮箱托管在本地的用户必须通过 Azure Active Directory Connect 将其身份同步至 Office 365 目录。对于这些 Exchange 混合客户，如果用户的邮箱托管在本地，则用户无法添加或配置连接器。*  <br> <br>**网络评估**  <br/>  端口和终结点检查。  <br/>  连接质量检查。  <br/>  带宽预估。  <br/><br/>    **会议室设备**  <br/>  创建 [Teams 设备目录](https://go.microsoft.com/fwlink/?linkid=2066478)中所列支持的电话和会议室设备所需的在线帐户。  <br/><br/>  **启用直接路由**  <br/> 单个站点的合作伙伴托管方案或客户部署方案的直接路由设计的组织设置指南。 <br/><br/> **启用音频会议**  <br/>  会议桥默认设置的组织设置。  <br/>  向许可用户分配会议桥。  <br/><br/>  **启用电话系统和通话套餐指南（[可用市场](https://go.microsoft.com/fwlink/?linkid=2066478)）**  <br/>  组织设置云语音默认设置。  <br/>  向许可用户分配号码。  <br/>  通过用户界面 (UI) 进行本地号码端口定位的指南（最多到 999）。  <br/>  超过 999 的本地号码端口定位服务请求 (SR) 支持。  <br/><br/> **启用 Teams 实时事件** <br> 组织设置和集成到 Microsoft Stream。 
|**Skype for Business Online 入门**  | **网络评估**  <br/>  端口和终结点检查。  <br/>  连接质量检查。  <br/>  带宽预估。  <br/><br/>  **Lync 混合**  <br/>  一个本地 Active Directory 林。  <br/>  使用 Lync 2013 管理工具或 Skype for Business 2015 管理工具和 Lync 2010 边缘服务器角色的 Lync 2010 Server 环境。  <br/>  一个 Lync 2013 Server 环境和 Lync 2013 边缘服务器角色。  <br/><br/>  **Skype for Business Online 混合**  <br/>  一个本地 Active Directory 林。  <br/>  单个 Active Directory 帐户林前向和资源林（Exchange 和/或 Skype for Business）拓扑。  <br/>  多个 Active Directory 帐户林，其中一个林是包含 Exchange 和/或 Skype for Business 的集中式 Active Directory 帐户林。  <br/>  一个包括 Skype for Business 边缘服务器角色的 Skype for Business Server 2015 环境。  <br/><br/> **注意**  *此额外的服务用于配置和验证拆分域（混合）任务，并不包括引入本地组件（例如，Lync 2013 管理工具或 Lync 2013/Skype for Business Online 服务器或 Lync 2010、Lync 2013 或 Skype for Business 边缘服务器）。*    <br/><br/>        **会议室设备**  <br/>  创建受支持的会议室设备（列于 [Skype for Business 解决方案目录](https://go.microsoft.com/fwlink/?LinkId=615775)的"会议室系统"选项卡中）所需的联机帐户。  <br/><br/>  **启用音频会议**  <br/>  会议桥默认设置的组织设置。  <br/>  向许可用户分配会议桥。  <br/><br/>  **启用电话系统和通话套餐指南（仅限美国）**  <br/>  组织设置云语音默认设置。  <br/>  向许可用户分配号码。  <br/>  通过用户界面 (UI) 进行本地号码端口定位的指南（最多到 999）。  <br/>  超过 999 的本地号码端口定位服务请求 (SR) 支持。  <br/><br/>  **启用 Skype for Business 会议直播指南载入**  <br/>  使用会议直播服务的联合身份验证组织设置。   |
|**Microsoft StaffHub 入门**  | 在适用于 Office 365 的 Azure Active Directory 中启用标识。  <br/><br/> **注意**  *Microsoft StaffHub 默认处于启用状态。*|
|**Outlook for iOS 和 Outlook for Android**  | 在适用于 Office 365 的 Azure Active Directory 中启用标识。  <br/>配置了 Exchange Online 并分配了许可证。 |
| **服务载入**，具体包括：  <br/>  *Exchange Online  <br/>  SharePoint Online  <br/>  OneDrive for Business  <br/> Microsoft Teams  <br/> Skype for Business Online  <br/>    Power BI  <br/>  Project Online  <br/>  Yammer  <br/>  Office 365 专业增强版  <br/>  Microsoft StaffHub <br/> Outlook for iOS 和 Outlook for Android*   |如 [Office 的系统要求](https://go.microsoft.com/fwlink/?LinkID=723597)所定义，在线客户端软件（如 Project for Office 365、Outlook for Windows、Outlook for iOS 和 Outlook for Android、OneDrive for Business 同步客户端、Power BI Desktop 和 Skype for Business）必须处于最低级别。  <br/> 可以从 [https://go.microsoft.com/fwlink/?linkid=839411](https://go.microsoft.com/fwlink/?linkid=839411) 下载 Microsoft Teams Windows 和 Mac 桌面客户端的安装程序。   |
   
\*若要了解 Office 365 US Government 的源环境预期，请参阅 [Office 365 US Government 的源环境预期](US-Gov-appendix-source-environment-expectations.md)。
  

