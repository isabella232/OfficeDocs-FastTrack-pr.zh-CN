---
title: 产品和功能
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Priority
ms.collection: FastTrack
description: 本主题包括 FastTrack 支持的工作负载方案的详细信息，以及我们可以开始之前所需的源环境预期。 根据您的当前设置，我们与您合作，创建一个补救计划，使源环境最大限度地满足成功的加入。
ms.openlocfilehash: 1b1ffa5812905630723b5d8a23196fbbc18a9c32
ms.sourcegitcommit: 1b2242be54dd0d000c6384f45f18e1951c31998b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/18/2020
ms.locfileid: "46800964"
---
# <a name="products-and-capabilities"></a>产品和功能

## <a name="services-and-scenarios-supported-by-fasttrack"></a>FastTrack 支持的服务和方案

本主题包括 FastTrack 支持的工作负载方案的详细信息，以及我们可以开始之前所需的源环境预期。 根据您的当前设置，我们与您合作，创建一个补救计划，使源环境最大限度地满足成功的加入。

FastTrack 提供的指导可帮助您首先了解 (所有 Microsoft Online Services 通用的核心功能) 然后加入每个符合条件的服务：

  - [常规](#general)
  - [Office 365](#office-365)
  - [企业移动性 & 安全性](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [应用保证](Win-10-app-assure.md)
  - [新版 Microsoft Edge](Win-10-microsoft-edge.md)

> [!NOTE]
> 有关 Office 365 美国政府版的源环境预期的信息，请参阅 [适用于 office 365 美国政府的源环境期望值](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)。
 
## <a name="general"></a>常规

<table>
<thead>
<tr class="header">
<th><strong>服务</strong></th>
<th><strong>FastTrack 指南详细信息</strong></th>
<th><strong>源环境预期</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>核心入门</strong></td>
<td>  我们提供了有关核心载入的远程指导，其中涉及服务设置、租户和身份集成。 它还包括为 Exchange Online、SharePoint Online 和 Microsoft 团队提供提供服务的基础的步骤，包括 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">有关安全性、网络连接性和合规性的讨论</a>。  
  在核心载入完成后，便可以开始载入一个或多个符合条件的服务。
</li>
</ul>  

<strong> 身份集成 </strong>

我们为以下内容提供了远程指导：
<ul>
<li>准备本地 Active Directory 标识以同步到 Azure Active Directory (Azure AD) 包括安装和配置 Azure AD Connect (单个或多个林) 和许可 (包括基于组的许可) 。</li>
<li>创建包括批量导入和许可的云标识，包括使用基于组的许可。</li>
<li>为你的云旅程选择和启用正确的身份验证方法、密码哈希同步、传递身份验证或 Active Directory 联合身份验证服务 (AD FS) 。</li>
<li>为具有单个 Active Directory 林且标识与 Azure AD Connect 工具同步的客户启用 AD FS。 这需要 Windows Server 2012 R2 Active Directory 联合身份验证服务2.0 或更高版本。</li>
<li>使用密码哈希同步或传递身份验证将身份验证从 AD FS 迁移到 Azure AD。</li>
<li>迁移预先集成的应用程序 (如 Azure AD 画廊 (SaaS) 应用) 从 AD FS 迁移到 Azure AD for single sign-on (SSO) 。</li>
<li>从 Azure AD 库启用 SaaS 应用集成和 SSO。</li>
<li>启用 " <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">应用集成" 教程列表</a> 中列出的预集成 SaaS 应用程序的自动用户预配 (仅限于 Azure AD 库 SaaS 应用程序和出站设置) 。  </li>
</td>

<td>  <strong>网络启用 </strong>  
  <br>作为 FastTrack 权益的一部分，我们建议你作为连接云服务的最佳实践，以确保 Microsoft 365 的最高级别的性能。  
  
<strong>Active Directory 林</strong> 这些功能林级别将设置为 Windows Server 2003 前向，具有以下林配置：
<ul>
<li>  单个 Active Directory 林。  </li>
<li>  单一 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。  </li>
<li>  多个 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。  </li>
<li>  多个 Active Directory 帐户林，其中的一个林是一个含有 Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business 的集中式 Active Directory 帐户林。  </li>
<li>  多个 Active Directory 帐户林，每一个都有自己的 Exchange 组织。  </li>
<li>  必要时，租户配置和与 Azure Active Directory 集成所需的任务。   </li>
</ul>
  <strong>重要</strong>  <ul>
<li>  对于多林 Active Directory 方案，如果已部署 Lync 2010、Lync 2013 或 Skype for Business，则必须将其部署在与 Exchange 相同的 Active Directory 林中。  </li>
<li>  在 Exchange 多混合配置中实施具有多个 Exchange 组织的多个 Active Directory 林时，共享用户主体名称 (UPN) 命名空间不支持源林之间的命名空间。 Exchange 组织之间的主要 SMTP 命名空间也应该进行分隔。 有关详细信息，请参阅 <a href="https://go.microsoft.com/fwlink/?linkid=845444">具有多个 Active Directory 林的混合部署</a>。  </li>
<li>  对于所有的多林配置，Active Directory 联合身份验证服务 (AD FS) 部署超出范围。 有关此方面的帮助，请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a> 联系。  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 应用版</strong></td>
<td>  我们为以下内容提供了远程部署指导：
<ul>
<li>  解决部署问题。  </li>
<li>  使用 Microsoft 365 管理中心和 Windows PowerShell 分配基于最终用户和设备的许可证。  </li>
<li>  使用即点即用从 Office 365 门户安装 Microsoft 365 应用版。  </li>
<li>  在 iOS 或 Android 设备上安装 Office Mobile 应用（如 Outlook Mobile、Word Mobile、Excel Mobile 和 PowerPoint Mobile）。  </li>
<li>  使用 Office 365 部署工具配置更新设置。  </li>
<li>  本地或云安装的选择和设置。  </li>
<li>  使用 Office 自定义工具或用于配置部署包的本地 XML 创建 Office 部署工具配置 XML。  </li>
<li>  使用 Microsoft Endpoint Configuration Manager 的部署，包括帮助创建 Microsoft Endpoint Configuration Manager 打包。  
  此外，如果您有一个宏或外接程序在以前版本的 Office 中运行，并且您遇到兼容性问题，我们通过应用程序确保计划来提供通过无需额外成本来修正兼容性问题的指导。 有关详细信息，请参阅 <strong>应用程序确保</strong> <a href="#windows-10">Windows 10</a> 的一部分。 </li>
</ul></td>
<td><ul>
<li>  联机客户端软件必须至少是在 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系统要求</a>中定义的最低级别。  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>网络运行状况</strong></td>
<td>  我们提供了有关从您的环境中获取和解释关键网络连接数据的远程指导，这些数据显示了贵组织的网站与 Microsoft 的 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">网络连接原则的</a>协调方式。 这会突出显示你的网络分数，这会直接影响迁移速度、用户体验、服务性能和可靠性。  
  我们还将指导你完成此数据突出显示的任何补救步骤，以帮助你提高网络分数。  </td>
<td><ul>
<li>  Microsoft 365 管理中心访问。  </li>
<li>  需要最新版本的 Microsoft 365 应用。  </li>
<li>  根据 <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 管理中心中的网络性能建议启用 Location 服务 (preview) </a>。  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

<table>
<thead>
<tr class="header">
<th><strong>服务</strong></th>
<th><strong>FastTrack 指南详细信息</strong></th>
<th><strong>源环境预期</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  对于 Exchange Online，我们会全程指导你，直到你的组织可以使用电子邮件为止。 具体步骤取决于您的源环境和您的电子邮件迁移计划。  
  我们为以下内容提供了远程指导：
<ul>
<li>  为 Office 365 中验证的所有启用邮件的域设置 Exchange Online Protection (EOP) 功能。  </li>
<li>  将邮件交换 (MX) 记录指向 Office 365。  </li>
<li>  设置 Office 365 ATP 功能（如果它是订阅服务的一部分）。 有关详细信息，请参阅此表中的 <strong>Office 365 高级威胁防护</strong> 部分。  </li>
<li>  为在 Office 365 中验证的所有已启用邮件的域设置数据丢失防护 (DLP) 功能，将其作为订阅服务的一部分。这可在 MX 记录指向 Office 365 后完成。</li>
<li>  为在 Office 365 中验证的所有已启用邮件的域设置 Office 365 邮件加密 (OME) ，将其作为订阅服务的一部分。这可在 MX 记录指向 Office 365 后完成。</li>
</ul>
  <strong>注意：</strong> 邮箱复制服务 (MRS) 尝试将 (IRM) 电子邮件从本地邮箱迁移到相应的 Exchange Online 邮箱的信息。 可读取受保护内容迁移后的能力取决于客户映射和将 Active Directory Rights Managed Services (AD RMS) 模板复制到 Azure Rights Management Service (Azure RMS)。  
<ul>
<li>  配置防火墙端口。  </li>
<li>  设置 DNS，包括所需的自动发现、发件人策略框架 (SPF) 、域密钥识别邮件 (DKIM) 、基于域的邮件身份验证、报告和一致性 (DMARC) 和 MX 记录 () 和 MX 记录。  </li>
<li>  设置源邮件环境和 Exchange Online 之间的电子邮件流（根据需要）。  </li>
<li>  执行从源邮件环境到 Office 365 的邮件迁移。  </li>
<li>  配置邮箱客户端（Outlook for Windows、Outlook 网页版以及 Outlook for iOS 和 Outlook for Android）。  </li>
</ul>
  <strong>数据迁移</strong>  <br>
有关使用 FastTrack 的数据迁移到 Office 365 的好处的信息，请参阅 <a href="https://review.docs.microsoft.com/fasttrack/data-migration">数据迁移</a>。   
<td>  源环境必须具有以下最低级别之一：
<ul>
<li>  具有 Exchange Server 2003 前向的单个或多个 Exchange 组织。  </li>
<li>  一个支持 Internet 邮件访问协议 (IMAP) 的电子邮件环境。  </li>
<li>  单个 G 套件环境（仅限 Gmail、联系人和日历）。  </li>
<li>  有关多地理位置功能的信息，请参阅 <a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online 中的多地理位置功能</a>。  </li>
</ul>
Online 客户端软件（如 Project for Office 365、Outlook for Windows、Outlook for iOS 和 Outlook for iOS、OneDrive for business 同步客户端、Power BI Desktop 和 Skype for Business）的最低级别必须为 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office 的系统要求</a>中定义的最低级别。  </td>
</tr>
<tr class="even">
<td><strong>Microsoft 信息管控</strong></td>
<td>  我们为以下内容提供了远程指导：
<ul>
<li>  信息管控。  </li>
<li>  保留标签和策略。  </li>
<li>  记录管理。  </li>
<li>  删除策略。  </li>
<li>  通信合规性。  </li>
<li>  内幕风险管理。  </li>
<li>  高级电子数据展示。  </li>
</ul></td>
<td>除了 <strong>核心载入</strong> 部分 <a href="#general">之外，没有</a>最低的系统要求。</td>
</tr>
<tr class="odd">
<td><strong>Microsoft 信息保护</strong></td>
<td>  我们为以下内容提供了远程指导：
<ul>
<li>  数据分类。  </li>
<li>  敏感信息类型。  </li>
<li>  创建敏感度标签。  </li>
<li>  应用敏感度标签。  </li>
<li>  统一标记。  </li>
<li>  Trainable 类元。  </li>
<li>  使用内容浏览器和活动资源管理器了解数据。  </li>
<li>  使用策略发布标签 (手动和自动) 。  </li>
<li>  为 Microsoft 团队聊天和频道创建数据丢失防护 (DLP) 策略。  </li>
</ul></td>
<td>除了 <strong>核心载入</strong> 部分 <a href="#general">之外，没有</a>最低的系统要求。</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  我们为以下内容提供了远程指导：
<ul>
<li>  确认 Exchange Online、SharePoint Online、Office 365 组和 Azure AD 中的最低要求以支持团队。  </li>
<li>  配置防火墙端口。  </li>
<li>  设置 DNS。  </li>
<li>  确认是否已在 Office 365 租户上启用 Teams。  </li>
<li>  启用或禁用用户许可证。  </li>
<li>  针对团队的网络评估：
<ul>
<li>  端口和终结点检查。  </li>
<li>  连接质量检查。  </li>
<li>  带宽预估。  </li>
</ul>
<ul>
<li>  配置团队应用程序策略 (团队 web app、团队桌面应用程序和适用于 iOS 和 Android 应用程序的团队) 。  </li>
</ul>
如果适用，我们还为以下内容提供指导：
<ul>
<li>  Microsoft 团队聊天室设备：  </li>
</ul>
<ul>
<li>  创建在 <a href="https://go.microsoft.com/fwlink/?linkid=2066478">团队设备目录</a>中列出的受支持电话和会议室设备所需的联机帐户。  </li>
</ul>
<ul>
<li>  启用音频会议：  </li>
</ul>
<ul>
<li>  会议桥默认设置的组织设置。  </li>
<li>  向许可用户分配会议桥。  </li>
</ul>
<ul>
<li>  电话系统：
<ul>
<li>  组织设置云语音默认设置。  </li>
<li>   (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">可用市场</a>) 的通话套餐指南：
<ul>
<li>  向许可用户分配号码。  </li>
<li>  通过用户界面 (UI) 进行本地号码端口定位的指南（最多到 999）。  </li>
<li>  超过 999 的本地号码端口定位服务请求 (SR) 支持。  </li>
</ul></li>
<li>  直接路由指南：
<ul>
<li>  单个站点的合作伙伴托管方案或客户部署方案的直接路由设计的组织设置指南。  </li>
</ul></li>
</ul></li>
<li>  启用 Teams 实时事件。  </li>
<li>  组织设置和集成到 Microsoft Stream。  </li>
</ul></td>
<td><ul>
<li>  Azure AD for Office 365 中启用的标识。  </li>
<li>  对 SharePoint Online 启用的用户。  </li>
<li>  Exchange 邮箱在 Exchange 混合配置) 中 (联机和本地提供。  </li>
<li>  针对 Office 365 组启用。  </li>
</ul>
  <strong>注意：</strong>  如果没有为用户分配和启用 SharePoint Online 许可证，则在 Office 365 中不会有 OneDrive for business 存储。 文件共享在频道中继续工作，但用户无法在 Office 365 中共享无 OneDrive for business 存储的聊天文件。 团队不支持本地 SharePoint。  <br>
  <strong>注意：</strong>  理想的状态是让所有用户将其邮箱驻留在 Exchange Online 上。 邮箱驻留在本地的用户必须将其标识同步到通过 Azure AD Connect 的 Office 365 目录。 对于这些 Exchange 混合客户，如果用户的邮箱在本地，则用户无法添加或配置连接器。  
  可以从下载 Microsoft 团队窗口和 Mac 桌面客户端的安装程序  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> 。  </td>
</tr>
<tr class="odd">
<td><strong>Office 365 高级威胁防护 (ATP)</strong></td>
<td>  我们为以下内容提供了远程指导：
<ul>
<li>  启用安全链接、安全附件和防钓鱼。  </li>
<li>  配置自动化、调查和响应。  </li>
<li>  使用攻击模拟器。  </li>
<li>  报告和威胁分析。  </li>
</ul></td>
<td>除了 <strong>核心载入</strong> 部分 <a href="#general">之外，没有</a>最低的系统要求。</td>
</tr>
<tr class="even">
<td><strong>iOS 和 Android 版 Outlook</strong></td>
<td>  我们为以下内容提供了远程指导：
<ul>
<li>  从 Apple App Store 和 Google Play 下载 Outlook for iOS 和 Outlook for Android。  </li>
<li>  配置帐户和访问 Exchange Online 邮箱。  </li>
<li>  保护 Outlook mobile (请参阅 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">在 Exchange Online 中保护适用于 iOS 和 Android 的 outlook</a> ，了解详细信息) 。  </li>
</ul></td>
<td><ul>
<li>  Azure AD for Office 365 中启用的标识。  </li>
<li>  配置了 Exchange Online 并分配了许可证。  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  我们为以下内容提供了远程指导：
<ul>
<li>  分配 Power BI 许可证。  </li>
<li>  部署 Power BI Desktop 应用。  </li>
</ul></td>
<td>Online 客户端软件（如 Power BI Desktop）的最低级别必须为 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系统要求</a>中定义的最低级别。</td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  我们为以下内容提供了远程指导：
<ul>
<li>  验证 Project Online 依赖的基本 SharePoint 功能。  </li>
<li>  向你的租户添加 Project Online 服务（包括向用户添加订阅）。  </li>
<li>  设置企业资源池 (ERP)。  </li>
<li>  创建你的首个项目。  </li>
</ul></td>
<td>Online 客户端软件（如 Project for Office 365）的最低级别必须为 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系统要求</a>中定义的最低级别。</td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional 和 Premium</strong></td>
<td>  我们为以下内容提供了远程指导：
<ul>
<li>  解决部署问题。  </li>
<li>  使用 Microsoft 365 管理中心和 Windows PowerShell 分配最终用户许可证。  </li>
<li>  使用即点即用从 Office 365 门户安装 Project Online 桌面客户端。  </li>
<li>  使用 Office 365 部署工具配置更新设置。  </li>
<li>  为 Project Online 桌面客户端 设置一个现场分发服务器，包括帮助创建 configuration.xml 文件以与 Office 365 部署工具一起使用。  </li>
<li>  将 Project Online 桌面客户端 连接到 Project Online Professional 或 Project Online 高级版。  </li>
</ul></td>
<td>Online 客户端软件（如 Project for Office 365）的最低级别必须为 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系统要求</a>中定义的最低级别。</td>
</tr>
<tr class="even">
<td><strong>SharePoint Online 和 OneDrive for Business</strong></td>
<td>  我们为以下内容提供了远程指导：
<ul>
<li>  设置 DNS。  </li>
<li>  配置防火墙端口。  </li>
<li>  设置用户和许可证。  </li>
<li>为你的 SharePoint Online 管理员启用站点创建。</li>
<li>规划网站集。</li>
<li>保护内容安全和管理权限。</li>
<li>配置 SharePoint Online 功能。</li>
<li>  配置 SharePoint 混合功能，如混合搜索、混合网站、混合分类、内容类型、混合自助式网站创建（仅适用于 SharePoint Server 2013）、扩展的应用启动器、混合 OneDrive for Business 和 Extranet 网站。  </li>
<li>  您的迁移方法。  </li>
</ul>
为 OneDrive for business 提供了其他指南，具体取决于你的 SharePoint 版本，如下所示：
<ul>
<li>  确定集成选项并查看内部部署和联机网络基础结构和带宽。  </li>
<li>  安装 SharePoint Online 2013 SP1 (（如果适用）) 、规划和实施同步和标识要求以及确定 OneDrive for Business 同步客户端。  </li>
<li>  为所有用户规划和实现单个部署 (或分阶段部署) 。  </li>
<li>  分配许可证、将 "我的网站" 和个人文档库重定向到 Office 365 (适用于 SharePoint Online 2013) ，设置访问群体，以控制对适用于 SharePoint Online 2013) 的 OneDrive (的访问权限。  </li>
<li>将已知文件夹重定向或移动到 OneDrive。</li>
<li>  部署 OneDrive for Business 客户端同步。  </li>
</ul>
  <strong>数据迁移</strong>  <br>
有关使用 FastTrack 的数据迁移到 Office 365 的好处的信息，请参阅 <a href="https://review.docs.microsoft.com/fasttrack/data-migration">数据迁移</a>。
</ul></td>
<td><br><strong>对于 SharePoint 混合：</strong>  
<ul>
<li>  SharePoint 混合配置包括配置混合搜索、网站、分类、内容类型、OneDrive for Business、扩展的应用启动器、extranet 网站以及从本地到单个目标 SharePoint Online 环境的自助式网站创建。  </li>
</ul>
  <strong>注意：</strong> 自助式网站创建与运行 SharePoint 2013 的本地服务器不在作用域中。  
<ul>
<li>  若要启用 SharePoint 混合，您必须具有以下本地 SharePoint Server 环境之一：2013、2016或2019。  </li>
</ul>
  <strong>注意：</strong> 将本地 SharePoint 环境升级到 SharePoint Server 不在作用域内。 请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a> 联系以获取帮助。 有关详细信息，请参阅 <a href="https://go.microsoft.com/fwlink/?linkid=853548">SharePoint 混合功能的最小公共更新级别</a><em>。</em>  <br>
  <strong>注意：</strong> 有关多地理位置功能的信息，请参阅 <a href="https://go.microsoft.com/fwlink/?linkid=831056">Office 365 中的 OneDrive 和 SharePoint Online 中的多地理位置功能</a><em>。</em>  </td>
</tr>
<tr class="odd">
<td><strong>Skype for Business Online</strong></td>
<td>  我们为以下内容提供了远程指导：
<ul>
<li>  配置防火墙端口。  </li>

<li>  设置 DNS。  </li>
<li>  网络评估：
<ul>
<li>  端口和终结点检查。  </li>
<li>  连接质量检查。  </li>
<li>  带宽预估。  </li>
</ul></li>
<li>  创建任何聊天室系统设备的帐户。  </li>
<li>  部署支持的 Skype for Business Online 客户端。  </li>
<li>  在本地 Lync 2010、Lync 2013 或 Skype for Business 2015 服务器环境与 Skype for Business Online 租户（如果适用）、通话套餐、Skype 会议直播、电话系统和通话套餐（在可用市场中）之间建立拆分域服务器配置。  
  如果适用，FastTrack 还将指导您完成以下操作：  </li>
<li>  配置会议室系统设备：
<ul>
<li>  在 <a href="https://go.microsoft.com/fwlink/?LinkId=615775">Skype For business 解决方案目录</a>中的 "会议室系统" 选项卡上列出的受支持的会议室设备所需的联机帐户的创建。  </li>
</ul></li>
<li>  配置混合和拆分域服务器。  </li>
<li>  配置音频会议：
<ul>
<li>  会议桥默认设置的组织设置。  </li>
<li>  向许可用户分配会议桥。  </li>
</ul></li>
<li>  配置电话系统的默认设置：
<ul>
<li>  通话套餐：
<ul>
<li>  向许可用户分配号码。  </li>
<li>  通过用户界面的本地号码移植指南，最多99  </li>
<li>  本地号码移植服务请求支持超过999  </li>
</ul></li>
</ul></li>
<li>  配置 Skype for Business 会议直播：
<ul>
<li>  使用会议直播服务的联合身份验证组织设置。  </li>
</ul></li>
</ul></td>
<td>  <strong>对于 Lync 混合：</strong>  
<ul>
<li>  一个本地 Active Directory 林。  </li>
<li>  使用 Lync 2013 管理工具或 Skype for Business 2015 管理工具和 Lync 2010 边缘服务器角色的 Lync 2010 Server 环境。  </li>
<li>  一个 Lync 2013 Server 环境和 Lync 2013 边缘服务器角色。  </li>
</ul>
  <strong>对于 Skype for Business 混合：</strong>  
<ul>
<li>  一个本地 Active Directory 林。  </li>
<li>  单个 Active Directory 帐户林前向和资源林（Exchange 和/或 Skype for Business）拓扑。  </li>
<li>  多个 Active Directory 帐户林，其中一个林是包含 Exchange 和/或 Skype for Business 的集中式 Active Directory 帐户林。  </li>
<li>  一个包括 Skype for Business 边缘服务器角色的 Skype for Business Server 2015 环境。  </li>
</ul>
  <strong>注意：</strong> 此额外服务用于配置和验证拆分的域 (混合) 任务，不包括引入本地组件 (例如，Lync 2013 管理工具或 Lync 2013/Skype for business Online 服务器，或 Lync 2010、Lync 2013 或 Skype for Business 边缘服务器) 。  </td>
</tr>
<tr class="even">
<td><strong>Yammer 企业版</strong></td>
<td><ul>
我们提供了有关启用 Yammer Enterprise 服务的远程指南。  
</ul></td>
<td>联机客户端软件必须至少是在 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系统要求</a>中定义的最低级别。</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>企业移动性 & 安全性

<table>
<thead>
</tr>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) 和 Azure AD Premium</strong></td>
<td>  我们为以下方案提供了保护云身份的远程指导。  

 <br/>

<strong>安全基础结构</strong>  </ul>
<ul>
<li>  为你的身份配置和启用强身份验证，包括使用 Azure 多重身份验证 (MFA)  (云仅) 、Microsoft 身份验证器应用，以及对 Azure MFA 和自助服务密码重置 (SSPR) 进行组合注册。  </li>
<li>  对于非 Azure AD 高级客户，提供的指导旨在使用安全默认值保护你的身份。  </li>
<li>  对于 Azure AD premium 客户，提供了指导以通过条件访问来保护你的身份。  </li>
<li>  检测并阻止使用具有 Azure AD 密码保护的弱密码。  </li>
<li>  使用 Azure AD 应用程序代理保护对本地 web 应用的远程访问。  </li>
<li>  启用基于风险的检测和修正和 Azure 身份保护。  </li>
<li>  启用自定义的登录屏幕，包括徽标、文本和具有自定义品牌的图像。  </li>
<li>  使用 Azure AD B2B 与来宾用户安全地共享应用程序和服务。  </li>
<li>  使用基于角色的访问控制管理 Office 365 管理员的访问权限 (RBAC) 内置管理角色，并减少特权管理员帐户的数量。  </li>
<li>  配置混合 Azure AD 加入。  </li>
<li>  配置 Azure AD 加入。  </li>
</ul>
  
<strong>监视和报告</strong>  
<ul>
<li>  
  为 AD FS、Azure AD Connect 和具有 Azure AD Connect Health 的域控制器启用远程监控。  
  </li>
</ul>
  
<strong>各</strong>  
<ul>
<li>  
  使用 Azure AD 权限管理来管理 Azure AD 标识和访问生命周期（按规模扩展）。
  </li>
<li>  
  使用 Azure AD access 审核管理 Azure AD 组成员身份、企业应用访问和角色分配。  
  </li>
<li>  
  查看 Azure AD 使用条款。  
  </li>
<li>  
  使用 Azure AD 特权标识管理管理和 controling 权限的管理员帐户。  
  </li>
</ul>
  
<strong>自动化和效率 </strong>  
<ul>
<li>  
  启用 Azure AD SSPR。  
  </li>
<li>  允许用户使用 Azure AD 自助服务组管理创建和管理其自己的云安全性或 Office 365 组。  </li>
<li>  管理对使用 Azure AD 委派组管理的企业应用程序的委派访问权限。  </li>
<li>  启用 Azure AD 动态组。  </li>
<li>  使用集合在我的应用程序门户中组织应用程序。  </li>
</ul></td>
<td>已为 Azure AD Premium 准备好了本地 Active Directory 及其环境，包括修正了阻止与 Azure AD 和 Azure AD 高级功能集成的已识别问题。</td>
</tr>
<tr class="odd">
<td><strong>Azure 信息保护（P2 或 EMS E5）</strong></td>
<td>  我们提供有关如何执行以下操作的指导：
<ul>
<li>  激活并配置租户。  </li>
<li>  创建和设置标签和策略。  </li>
<li>  向文档应用信息保护。  </li>
<li>  自动对在 Windows 上运行的 Office 应用（如Word、PowerPoint、Excel 和 Outlook）中的信息进行分类和标记，并使用 Azure 信息保护客户端。  </li>
<li>  使用带有 Azure 信息保护扫描程序的静态文件。  </li>
<li>  使用 Exchange Online 邮件流规则监视传输中的电子邮件。  </li>
</ul>
如果您想要使用 Microsoft Azure 权限管理服务 (Azure RMS) 、Office 365 邮件加密 (OME) 和数据丢失防护 (DLP) 来应用保护，则还提供指导。  </td>
<td>  您应该已经：
<ul>
<li>  使用 Azure AD。  </li>
<li>  使用 Windows 或 iOS (其他操作系统不在作用域) 。  
  </ul>
<strong>注意</strong>：计算机和移动设备必须在支持 Azure 信息保护的 <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">操作系统</a> 上运行。  
<li>  具有您的主文件共享位置。  </li>
<strong>注意</strong>：混合支持需要 AD RMS 连接器。 
<li>  具有已批准的分类分类。  </li>
<li>  了解对受保护密钥管理的任何法规限制。  </li>
</ul>
  
<strong>Azure 信息保护扫描程序</strong>  
  
您应该已经：  
<ul>
<li>  使用 Windows Server 2012 R2 或 Windows Server 2016。  </li>
<li>  具有 internet 连接。  </li>
<li>  在本地或远程实例中安装 Microsoft SQL Server 2012。  </li>
<li>  拥有为本地 Active Directory 创建的服务帐户，并已与 Azure AD 同步。  </li>
<li>  已下载 AzInfoProtection.exe。  </li>
<li>  将标签配置为自动分类/保护。  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  我们提供有关准备将 Intune 用作基于云的移动设备管理 (MDM) 和移动应用管理 (MAM) 提供程序的指南，以供您的应用和设备使用。 具体步骤取决于你的源环境，并且基于你的移动设备和移动应用管理需求。 所包含的具体步骤如下：
<ul>
<li>  许可最终用户。  </li>
<li>  通过利用本地 Active Directory 或云标识 (Azure AD) 配置要由 Intune 使用的标识。  </li>
<li>  将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。  </li>
<li>  根据您的管理需求配置您的 MDM 颁发机构，包括：
<ul>
<li>  如果 Intune 是唯一的 MDM 解决方案，将 Intune 设置为 MDM 颁发机构。  </li>
</ul></li>
<li>  为以下操作提供 MDM 指南:
<ul>
<li>  配置用于验证 MDM 管理策略的测试组。  </li>
<li>  配置 MDM 管理策略和服务，如：
<ul>
<li>  通过 web 链接或深层链接针对每个受支持的平台的应用程序部署。  </li>
<li>  条件访问策略。  </li>
<li>  如果您的组织中有现有的证书颁发机构、无线网络或 VPN 基础结构，则将电子邮件、无线网络和 VPN 的部署) 配置文件。  </li>
<li>  设置 Microsoft Intune Exchange 连接器（如果适用）。  </li>
<li>  连接到 Intune 数据仓库。  </li>
<li>  将 Intune 与以下内容进行集成：
<ul>
<li>  团队查看器获取远程协助 (需要) 团队查看器订阅。  </li>
<li>  移动威胁防护 (MTD) 合作伙伴解决方案 (需要) 的 MTD 订阅。  </li>
<li>  需要) 电信费用管理解决方案 (电信费用管理解决方案订阅。  </li>
<li>  Microsoft Defender ATP (Windows E5 或 Microsoft 365 E5 许可证是) 所必需的。  </li>
</ul></li>
<li>  将每个受支持平台的设备注册到 Intune。  </li>
</ul></li>
</ul></li>
<li>  提供应用程序保护指导：
<ul>
<li>  为每个受支持的平台配置应用保护策略。  </li>
<li>  为托管应用程序配置条件访问策略。  </li>
<li>  将相应的用户组设定为前面提到的 MAM 策略。  </li>
<li>  使用托管-应用使用情况报告。  </li>
</ul></li>
<li>  提供从旧版 PC 管理到 Intune MDM 的迁移指南。  </li>
</ul>
  <strong>注意</strong>：旧电脑管理不再受支持，从2020年10月15日起。  
</li>
</ul>
  
<strong>云附加</strong>  

  我们将指导您完成使用 Intune 将现有的 Configuration Manager 环境附加到云的准备工作。 具体步骤取决于源环境。 这些步骤包括：  
<ul>
<li>  介绍使用 Intune 云附加 Configuration Manager 的好处。  </li>
<li>  许可最终用户。  </li>
<li>  通过利用本地 Active Directory 和云标识，配置供 Intune 使用的标识。  </li>
<li>  将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。  </li>
<li>  在配置管理器控制台中启用云附加。  </li>
<li>  提供有关设置混合 Azure AD join 的指导。  </li>
<li>  提供有关设置适用于 MDM 自动注册的 Azure AD 的指导。  </li>
<li>  提供有关如何设置云管理网关的指南。  </li>
<li>  配置要切换到 Intune 的受支持工作负载。  </li>
<li>  在 Intune 注册的设备中安装 Configuration Manager 客户端。  </li>
</ul> 

<strong>安全部署适用于 iOS 和 Android 的 Outlook mobile</strong> 我们可以提供指导来帮助您在组织中安全地部署适用于 iOS 和 Android 的 Outlook mobile，以确保您的用户安装了所有必需的应用程序。  
  使用 Intune 安全部署 Outlook mobile for iOS 和 Outlook Android 的步骤取决于您的源环境。 它可以包括：
<ul>
<li>  通过 Apple App Store 或 Google Play 商店下载 Outlook for iOS 和 Android、Microsoft 身份验证者和 Intune 公司门户应用。  </li>
<li>  提供有关设置的指导：
<ul>
<li>  使用 Intune 的 Outlook for iOS 和 Android、Microsoft 身份验证者和 Intune 公司门户应用部署。  </li>
<li>  应用保护策略。  </li>
<li>  条件访问策略。  </li>
<li>  应用配置策略。  </li>
</ul></li>
</ul>
  
  <strong>注意</strong>： FastTrack 不支持使用 Exchange 移动设备邮箱策略保护适用于 IOS 和 Android 的 Outlook。 有关此方面的帮助，请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a> 联系。  
  </td>
<td>  在计划使用 Intune 部署无线网络和 VPN 配置文件时，IT 管理员需要具有已在其生产环境中工作的现有证书颁发机构、无线网络和 VPN 基础结构。  
  <strong>注意</strong>： FastTrack 服务权益不包括为 Intune 设置或配置证书颁发机构、无线网络、VPN 基础结构或 Apple MDM 推送证书的帮助。  

<strong>使用 Intune 云附加 Configuration Manager </strong>  

 使用云附加，IT 管理员负责准备本地环境。 这可能包括对阻止你使用 Intune 将 Configuration Manager 环境附加到云的问题的补救措施。  
  <strong>注意</strong>：FastTrack 服务权益不包括有关将配置管理器站点服务器或配置管理器客户端设置或升级到支持云附加所需的最低要求的帮助。 有关此方面的帮助，请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a> 联系。

  <strong>Intune 与 Microsoft Defender 高级威胁防护 (ATP) 集成</strong> 
 
  <strong>注意</strong>：我们提供了有关将 Intune 与 MICROSOFT Defender ATP 集成以及根据其 Windows 10 风险级别评估创建设备合规性策略的帮助。 我们不提供有关购买、许可或激活的帮助。 有关此方面的帮助，请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a> 联系。  
  
<strong>Windows Autopilot</strong> 
 
  IT 管理员负责通过让硬件供应商代表他们上载其硬件 ID 或自己将其上载到 Windows Autopilot 服务中来向其组织注册设备。  
  
<strong>使用 Intune 安全地部署 Outlook for iOS 和 Android </strong>  
<ul>
<li>  在 Azure AD for Office 365 中启用的用户标识。  </li>
<li>  使用分配了用户许可证的 Exchange Online 或混合 Exchange 配置。  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<thead>
<tr class="header">
<th><strong>服务</strong></th>
<th><strong>FastTrack 指南详细信息</strong></th>
<th><strong>源环境预期</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  我们提供的指导可帮助您从 Windows 7 Professional 和 Windows 8.1 专业版升级到 Windows 10 企业版。  
  我们为以下内容提供了远程指导：
<ul>
<li>  了解你的 Windows 10 意图。  </li>
<li>  评估源环境和要求 (确保 Microsoft 终结点配置管理器升级到所需的级别，以支持 Windows 10 部署) 。  </li>
<li>  使用 Microsoft 终结点配置管理器或 Microsoft 365 部署 Windows 10 企业版和 Microsoft 365 应用。  </li>
<li>  推荐用于评估 Windows 10 应用程序的选项。  </li>
<li>  启用桌面分析和指南创建桌面分析部署计划的使用。  </li>
<li>  Microsoft 365 应用兼容性评估，具体方法是利用配置管理器中的 Office 365 准备情况仪表板，或使用独立准备工具包 for Office 以及部署 Microsoft 365 应用程序的相关帮助。  </li>
<li>  评估新式管理策略，包括使用 Microsoft Intune 的云附加配置管理器或将 Intune 部署为唯一的云管理解决方案。  </li>
<li>  根据您需要执行的操作来创建修补程序清单，以使源环境达到成功部署的最低要求。  </li>
<li>  将现有设备的升级指南提供给 Windows 10 企业版，如果它们满足所需的设备硬件要求。  </li>
<li>  提供用于支持现有部署活动的升级指南。 FastTrack 推荐并提供有关就地升级到 Windows 10 的指南。 指南还可用于 Windows 干净图片安装和 Windows Autopilot 部署方案。  </li>
<li>  在 Windows 10 部署中使用 Configuration Manager 部署 Microsoft 365 应用。   </li>
<li>  提供指导，帮助您的组织使用现有的配置管理器环境或 Microsoft 365 保持最新的 Windows 10 企业版和 Microsoft 365 应用。  </li>
<li>  提供指导以通过云将配置管理器附加到 Intune 或部署 Intune 独立 (（必要的) ）来启用新式管理。  </li>
</ul>
  <strong>以下项超出范围 </strong>  
<ul>
<li>  将 Configuration Manager 升级到当前分支。  </li>
<li>  创建适用于 Windows 10 部署的自定义映像。  </li>
<li>  创建和支持 Windows 10 部署的部署脚本。  </li>
<li>  将 Windows 10 系统从 BIOS 转换为统一可扩展固件接口 (UEFI)。  </li>
<li>  启用 Windows 10 安全功能。  </li>
<li>  配置用于启动前执行环境 (PXE) 启动的 Windows 部署服务 (WDS)。  </li>
<li>  使用 Microsoft 部署工具包 (MDT) 捕获和部署 Windows 10 映像。  </li>
<li>  使用用户状态迁移工具 (USMT)。  </li>
</ul>
联系 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a> 以获取有关这些服务的帮助。  </td>
<td>  要升级电脑，必须满足以下要求：
<ul>
<li>  源 OS： Windows 7 企业版或专业版、Windows 8.1 企业版或专业版。  </li>
<li>  设备：桌面、笔记本或平板电脑外形规格。  </li>
<li>  目标 OS： Window 10 企业版。  </li>
</ul>
若要升级基础结构，必须满足以下要求：
<ul>
<li>  Microsoft 终结点配置管理器。  </li>
<li>  Configuration Manager 版本必须受 Windows 10 目标版本支持。 有关详细信息，请参阅 configuration manager <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">中的 Windows 10 支持</a>下的 configuration manager 支持表格。  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender 高级威胁防护 (ATP) </strong></td>
<td>  Microsoft Defender 高级威胁防护 (ATP) 是旨在帮助企业网络预防、检测、调查和响应高级威胁的平台。  
  我们为以下内容提供了远程指导：
<ul>
<li>  部署用于保护终结点的技术。  </li>
<li>  配置 endpoint protection 和设备限制配置文件。  </li>
<li>  评估 OS 版本和设备管理 (包括 Intune、Microsoft 终结点配置管理器、组策略对象 (Gpo) 和第三方配置) 以及 Windows Defender AV 服务或其他终结点安全软件的状态。  </li>
<li>  评估 Windows AV 服务或其他 endpoint security 软件的状态。  </li>
<li>  评估代理和防火墙限制网络流量。  </li>
<li>  通过说明如何使用板载终结点部署 ATP 代理配置文件来启用 Microsoft Defender ATP 服务。  </li>
<li>  部署指南、配置帮助和教育：
<ul>
<li>  
  威胁和漏洞管理。  
  </li>
<li>  
  攻击面减少。  
  </li>
<li>  
  新一代保护。  
  </li>
<li>  
  终结点检测和响应。  
  </li>
<li>  
  自动调查和修复。  
  </li>
<li>  
  安全功能分数。  
  </li>
</ul></li>
<li>  查看模拟和教程 (如实践方案、假恶意软件和自动调查) 。  </li>
<li>  报告和威胁分析功能概述。  </li>
<li>  将 Office 365 ATP 与 Microsoft Defender ATP 集成。  </li>
<li>  在 Microsoft Defender 安全中心门户中执行演练。  </li>
<li>  以下操作系统：
<ul>
<li>  
  Windows 10。  
  </li>
<li>  
  Windows Server 2016。  
  </li>
<li>  
  Windows Server 2019。  
  </li>
<li>  
  Windows Server 2019 Core Edition。  
  </li>
<li>  
  Windows Server 半年频道 (SAC) 版本1803。  
  </li>
<li>  
  macOS 版本10.13、10.14 和10.15。  
  </li>
</ul>
</li>
</ul>
<strong>注意：</strong> 所有 Windows Server 版本必须由 System Center Configuration Manager 2012 (版本 1012 R2、1511或 1602) 或 Microsoft 终结点配置管理器 (版本2002或更高版本的) 进行管理。 

</li>
</ul>

<strong>以下项超出范围 </strong>  
<ul>
<li>  客户补救活动的项目管理。  </li>
<li>  现场支持。  </li>
<li>  持续管理和威胁响应。  </li>
<li>  以下 Microsoft Defender ATP 代理的加入或配置：
<ul>
<li>  
  Windows Server 2008。  
  </li>
<li>  
  Windows Server 2012。  
  </li>
<li>  
  Linux.  
  </li>
<li>  
   (Android 和 iOS) 的移动设备。  
  </li>
</ul></li>
<li>  服务器的载入和配置：
<ul>
<li>  
  配置用于脱机通信的代理服务器。  
  </li>
<li>  
  在下层配置管理器实例和版本上配置 Configuration Manager 部署包。  
  </li>
<li>  
  将服务器载入 Azure 安全中心。  
  </li>
<li>  
  不受 Configuration Manager 管理的服务器。  
  </li>
</ul></li>
<li>  macOS 载入和配置：
<ul>
<li>  
  手动基于 Intune 的部署。  
  </li>
<li>  
  基于 JAMF 的部署。
  </li>
<li>  
  其他移动设备管理 (MDM) 基于产品的部署。  
  </li>
<li>  
  手动部署。  
  </li>
</ul></li>
<li>  配置以下攻击面减少功能：
<ul>
<li>  
  基于硬件的隔离。  
  </li>
<li>  
  应用程序控制。  
  </li>
<li>  
  Exploit Protection。  
  </li>
<li>  
  网络防火墙。  
  </li>
</ul></li>
<li>  注册或配置 Microsoft 威胁专家。  </li>
<li>  配置或培训检查 API 或安全信息和事件管理 (SIEM) 连接。  </li>
<li>  注册或配置 Microsoft 威胁防护 (MTP)。  </li>
<li>  有关高级搜寻的培训或指导。  </li>
<li>  涉及使用或创建 Kusto 查询的培训或指导。</li>
</li>
</ul>
联系 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a> 以获取有关这些服务的帮助。  
</ul></td>
<td></td>

</tbody>
</table>
