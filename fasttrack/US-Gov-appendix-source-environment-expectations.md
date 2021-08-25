---
title: 美国政府的源Office 365预期
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 8/25/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: FastTrack 中心权益可以指导你设置与源环境的集成级别（例如，如果在源环境中你已经拥有想要移动到 Office 365 的服务）。
ms.openlocfilehash: 16805cfed345741c33aaa37bc6c2a377fede9c8a
ms.sourcegitcommit: 7ad41bd0aac5b3e2a0b3843d507b3eff0615941b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/25/2021
ms.locfileid: "58517532"
---
# <a name="source-environment-expectations-for-office-365-us-government"></a>美国政府的源Office 365预期

FastTrack 中心权益可以指导你设置与源环境的集成级别（例如，如果在源环境中你已经拥有想要移动到 Office 365 的服务）。
  
> [!NOTE]
> 如果必须集成，对于相应的应用程序，源环境必须处于最低级别。 
  
下表展示了对您的现有源环境的载入预期。

|**活动**|**对源环境的预期**|
|:-----|:-----|
|核心载入 | 将林功能级别设置为 Windows Server 2003 前向的 Active Directory 林，具有以下林配置：  <br/>      单个 Active Directory 林。  <br/>    单一 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。  <br/>  多个 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。  <br/>  多个 Active Directory 帐户林，其中的一个林是一个含有 Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business 的集中式 Active Directory 帐户林。  <br/>  多个 Active Directory 帐户林，每一个都有自己的 Exchange 组织。 <br/> <br/> **注意**  *对于多林 Active Directory 的情况，如果部署了 Lync 2010、Lync 2013 或 Skype for Business，就必须将其部署在与 Exchange 同在的那个 Active Directory 林中。*   <br/>  <br/>      **注意**  *在 Exchange 多混合配置中实施带有多个 Exchange 组织的多个 ActiveDirectory 林时，不支持源林之间的共享用户主体名称 (UPN) 命名空间。Exchange 组织之间的主要 SMTP 命名空间也应该进行分隔。有关详细信息，请参阅 [具有多个 Active Directory 林的混合部署](https://go.microsoft.com/fwlink/?linkid=845444)。*     <br/>   <br/>   **注意**  *对于所有的多林配置，AD FS 部署超出了 FastTrack 中心权益的范围。*           |
|Exchange Online 载入 | 您的环境必须具有以下最低级别之一：  <br/>  具有 Exchange Server 2003 前向的单个或多个 Exchange 组织。  <br/>  一个支持 Internet 邮件访问协议 (IMAP) 的电子邮件环境。  <br/>  单个 G 套件环境（仅限 Gmail、联系人和日历）。             |
|SharePoint Online 和 OneDrive for Business 载入  | **SharePoint 混合**  <br/>  SharePoint 混合 配置包含配置混合搜索、站点、分类、内容类型、OneDrive for Business（扩展的应用启动器）和从本地连接到单个目标 SharePoint Online 环境的 Extranet 网站和自助式网站创建。若要启用 SharePoint 混合，必须具有以下本地 SharePoint Server 环境之一：  <br/> <br/> **_SharePoint Server 2013_*_ <br/> 2017 年 6 月公开更新 (PU) 混合内容类型。有关详细信息，请参阅配置混合 [SharePoint和混合内容类型](https://go.microsoft.com/fwlink/?linkid=853547)。 适用于自助式网站创建配置的 2017 年 3 月 <br/> PU。只有 SharePoint Server 2013 才支持混合自助式网站创建。有关详细信息，请参阅混合 [自助式网站创建](https://go.microsoft.com/fwlink/?linkid=846015)。 <br/>使用混合分类的 2016 年 11 月 PU 前向。有关详细信息，请参阅规划混合 [SharePoint分类](https://go.microsoft.com/fwlink/?linkid=844867)。 <br/>适用于所有其他混合配置方案的 2016 年 7 月 PU 前向。 <br/> <br/> _* 注意***SharePoint Server 2013 仅支持 SharePoint Server 2013 混合方案。这些方案在 SharePoint Foundation 2013 中不受支持。*    <br/>   <br/>    ***SharePoint Server 2016** _  <br/>  适用于混合内容类型的 2017 年 6 月 PU。有关详细信息，请参阅[配置混合 SharePoint 分类和混合内容类型](https://go.microsoft.com/fwlink/?linkid=853547)。<br/>  具有混合分类的 2016 年 11 月 PU（功能包 1）。有关详细信息，请参阅[规划混合 SharePoint 分类](https://go.microsoft.com/fwlink/?linkid=844867)。<br/>  适用于所有其他混合配置方案的 2016 年 7 月 PU 前向。  <br/><br/> _ *   *Note Upgrade of on-premises SharePoint environments to SharePoint Server 2013 or SharePoint Server 2016 isn't provided by the FastTrack Center Benefit.有关详细信息，请参阅混合 [功能的最低公共SharePoint级别](https://go.microsoft.com/fwlink/?linkid=853548)。*             |
|Skype for Business Online 载入  | **网络评估**  <br/>  端口和终结点检查。  <br/>  连接质量检查。  <br/>  带宽预估。  <br/><br/>  **Lync 混合**  <br/>  一个本地 Active Directory 林。  <br/>  使用 Lync 2013 管理工具或 Skype for Business 2015 管理工具和 Lync 2010 边缘服务器角色的 Lync 2010 Server 环境。  <br/>  一个 Lync 2013 Server 环境和 Lync 2013 边缘服务器角色。  <br/><br/>  **Skype for Business Online 混合**  <br/>  一个本地 Active Directory 林。  <br/>  单个 Active Directory 帐户林前向和资源林（Exchange 和/或 Skype for Business）拓扑。  <br/>  多个 Active Directory 帐户林，其中一个林是包含 Exchange 和/或 Skype for Business 的集中式 Active Directory 帐户林。  <br/>  一个包括 Skype for Business 边缘服务器角色的 Skype for Business Server 2015 环境。  <br/><br/> **注意**  *此额外的服务用于配置和验证拆分域（混合）任务，并不包括引入本地组件（例如，Lync 2013 管理工具或 Lync 2013/Skype for Business Online 服务器或 Lync 2010、Lync 2013 或 Skype for Business 边缘服务器）。*    <br/><br/>        **会议室设备**  <br/>  创建受支持的会议室设备（列于 [Skype for Business 解决方案目录](https://go.microsoft.com/fwlink/?LinkId=615775)的"会议室系统"选项卡中）所需的联机帐户。  <br/><br/>  **启用音频会议**  <br/>  会议桥默认设置的组织设置。  <br/>  向许可用户分配会议桥。  <br/><br/>  **仅电话系统美国 (和通话套餐指南– 不适用于GCC高或 DoD 计划)**  <br/>  组织设置云语音默认设置。  <br/>  向许可用户分配号码。  <br/>  通过用户界面 (UI) 进行本地号码端口定位的指南（最多到 999）。  <br/>  超过 999 的本地号码端口定位服务请求 (SR) 支持。  <br/><br/>  **启用Skype for Business会议直播指南载入 (在高级GCC DoD 计划中不可用)**  <br/>  使用会议直播服务的联合身份验证组织设置。   |
|Microsoft Teams 载入  | 在 Azure AD Azure Active Directory (中) 标识Office 365。  <br/>  对 SharePoint Online 启用的用户。  <br/>  Exchange混合配置 (联机和本地Exchange邮箱) 。  <br/>  针对 Office 365 组启用。<br/>  <br/> **请注意***FastTrack根据各个环境中功能的可用性帮助范围。有关每个环境中当前可用的功能的列表，请参阅 <a href="/office365/servicedescriptions/teams-service-description#feature-availability">功能可用性</a>。* <br/> <br/> **注意** 如果未为用户分配和启用 SharePoint Online 许可证，他们将不会OneDrive for Business *存储空间Office 365。文件共享继续在频道中工作，但如果没有在频道中存储的 OneDrive for Business，用户Office 365。Teams不支持SharePoint本地部署。*     <br/> <br/>       **Note***The ideal state is for all users to have their mailboxes homed on Exchange Online.拥有托管在本地的邮箱的用户必须通过 Azure AD Office 365同步到 连接。对于Exchange，如果用户的邮箱位于本地，则用户无法添加或配置连接器。可以从 下载 Microsoft Teams Windows 和 Mac 桌面客户端的安装程序 <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> 。*          |
| 服务载入，包括：  <br/>  *<br/>Exchange OnlineSharePointOnline <br/> OneDrive for Business Skype for Business Online Microsoft Teams Power BI Project Online Yammer <br/> <br/> <br/> <br/> <br/> <br/> Microsoft 365 应用版                              <br/>*   |如 [Office 的系统要求](https://go.microsoft.com/fwlink/?LinkID=723597)所定义，在线客户端软件（如 Project for Office 365、Outlook 客户端、OneDrive for Business 同步客户端、Power BI Desktop 和 Skype for Business）必须处于最低级别。  <br/> 可以从 [https://go.microsoft.com/fwlink/?linkid=839411](https://go.microsoft.com/fwlink/?linkid=839411) 下载 Microsoft Teams Windows 和 Mac 桌面客户端的安装程序。   |
