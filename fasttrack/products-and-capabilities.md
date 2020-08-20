---
title: 产品和功能
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Normal
ms.collection: FastTrack
description: 本主题包括 FastTrack 支持的工作负荷方案的详细信息以及我们开始之前所期预期的源环境。 根据你当前的设置，我们与你合作来创建修正计划，此计划可使你的源环境达到成功载入的最低要求。
ms.openlocfilehash: d25c1df8e628f14487952cacc86ccf8fb9dad8c1
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817697"
---
# <a name="products-and-capabilities"></a>产品和功能

## <a name="services-and-scenarios-supported-by-fasttrack"></a>FastTrack 支持的服务和方案

本主题包括 FastTrack 支持的工作负荷方案的详细信息以及我们开始之前所期预期的源环境预期。 根据你当前的设置，我们与你合作来创建修正计划，此计划可使你的源环境达到成功载入的最低要求。

FastTrack 提供指导，可帮助你首先完成所有 (的 Microsoft Online Services) 常见功能，然后载入每个符合条件的服务：

  - [常规](#general)
  - [Office 365](#office-365)
  - [企业移动性&安全性](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [应用保证](Win-10-app-assure.md)
  - [新版 Microsoft Edge](Win-10-microsoft-edge.md)

> [!NOTE]
> 若要了解 Office 365 US Government 的源环境预期，请参阅 [Office 365 US Government 的源环境预期](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)。
 
## <a name="general"></a>常规

<table>
<thead>
<tr class="header">
<th><strong>服务</strong></th>
<th><strong>FastTrack 指南详细信息</strong></th>
<th><strong>对源环境的预期</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>核心入门</strong></td>
<td>  我们提供核心载入的远程指南，涉及服务预配、租户和身份集成。 它还包括为载入服务（如 Exchange Online、SharePoint Online 和 Microsoft Teams）提供基础的步骤，包括有关 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">安全性、网络连接和合规性的讨论</a>。  
  在核心载入完成后，便可以开始载入一个或多个符合条件的服务。
</li>
</ul>  

<strong> 身份集成 </strong>

我们提供针对以下方面的远程指南：
<ul>
<li>准备本地 Active Directory 标识以同步到 Azure Active Directory (Azure AD) 包括安装和配置 Azure AD Connect (单林或多林) 以及许可 (包括基于组的许可) 。</li>
<li>创建云标识，包括批量导入和许可，包括使用基于组的许可。</li>
<li>为云选择并启用正确的云身份验证方法、密码哈希同步、直通身份验证或 Active Directory 联合身份验证服务 (AD FS) 。</li>
<li>为具有单个 Active Directory 林的客户启用 AD FS，并标识与 Azure AD Connect 工具同步。 这需要Windows Server 2012 R2 Active Directory 联合身份验证服务 2.0 或更高版本。</li>
<li>使用密码哈希同步或直通身份验证将身份验证从 AD FS 迁移到 Azure AD。</li>
<li>将预集成的应用 (如 Azure AD 库软件即服务 (SaaS) 应用) ）从 AD FS 迁移到 Azure AD 以进行单一登录 (SSO) 。</li>
<li>从 Azure AD 库中启用 SaaS 应用与 SSO 的集成。</li>
<li>为应用集成教程列表中列出的应用集成教程列表中所 <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">列的为</a> 预集成 SaaS 应用启用自动用户预配 (限于 Azure AD 库 SaaS 应用，并且仅限) 。  </li>
</td>

<td>  <strong>网络启用 </strong>  
  <br>作为 FastTrack 权益的一部分，我们建议你如何选择连接到云服务的最佳做法，以确保 Microsoft 365 的最高级别的性能。  
  
<strong>Active Directory 林</strong> 这些林功能林级别设置为 Windows Server 2003 前向，并配置以下：
<ul>
<li>  单个 Active Directory 林。  </li>
<li>  单一 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。  </li>
<li>  多个 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。  </li>
<li>  多个 Active Directory 帐户林，其中的一个林是一个含有 Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business 的集中式 Active Directory 帐户林。  </li>
<li>  多个 Active Directory 帐户林，每一个都有自己的 Exchange 组织。  </li>
<li>  完成租户配置以及与 Azure Active Directory 集成所需执行的任务（如需要）。   </li>
</ul>
  <strong>重要提示：</strong>  <ul>
<li>  对于多林 Active Directory 的情况，如果部署了 Lync 2010、Lync 2013 或 Skype for Business，就必须将其部署在与 Exchange 同在的同一个 Active Directory 林中。  </li>
<li>  在 Exchange 多混合配置中通过多个 Exchange 组织实施多个 Active Directory 林时，不支持源林之间的共享用户主体名称 (UPN) 命名空间。 Exchange 组织之间的主要 SMTP 命名空间也应该进行分隔。 有关详细信息，请参阅 <a href="https://go.microsoft.com/fwlink/?linkid=845444">具有多个 Active Directory 林的混合部署</a>。  </li>
<li>  对于所有的多林配置，Active Directory 联合身份验证 (AD FS) 配置不在范围中。 请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a> 联系以获取有关此帮助的帮助。  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 应用版</strong></td>
<td>  我们提供针对以下方面的远程部署指导：
<ul>
<li>  解决部署问题。  </li>
<li>  使用 Microsoft 365 管理中心和 Windows PowerShell 分配基于最终用户和设备的许可证。  </li>
<li>  使用即点即用从 Office 365 门户安装 Microsoft 365 应用版。  </li>
<li>  在 iOS 或 Android 设备上安装 Office Mobile 应用（如 Outlook Mobile、Word Mobile、Excel Mobile 和 PowerPoint Mobile）。  </li>
<li>  使用 Office 365 部署工具配置更新设置。  </li>
<li>  本地或云安装的选择和设置。  </li>
<li>  使用 Office 自定义工具或用于配置部署包的本地 XML 创建 Office 部署工具配置 XML。  </li>
<li>  使用 Microsoft Endpoint Configuration Manager 的部署，包括帮助创建 Microsoft Endpoint Configuration Manager 打包。  
  此外，如果你有使用早期版本的 Office 的宏或加载项，并且遇到了兼容性问题，我们提供了通过应用保证计划来随时修正兼容性问题的指南。 有关更多 <strong>详细信息，请参阅</strong> <a href="#windows-10">Windows 10 的"应用</a> 保证"部分。 </li>
</ul></td>
<td><ul>
<li>  如 Microsoft 365 和 Office 的系统要求中的定义 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">，联机客户端软件必须在最低级别</a>。  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>网络运行状况</strong></td>
<td>  我们提供了远程指南，使你从环境中获得并解释关键网络连接数据，说明贵组织的站点与 Microsoft 的网络连接原 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">则的对齐程度</a>。 这重点介绍的网络分数会直接影响迁移速度、用户体验、服务性能和可靠性。  
  我们还将指导你完成此数据突出显示的任何修正步骤，以帮助你改进你的网络分数。  </td>
<td><ul>
<li>  Microsoft 365 管理中心访问。  </li>
<li>  必须安装最新版本的 Microsoft 365 应用。  </li>
<li>  在<a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Microsoft 365 管理中心内，按网络性能建议启用的位置服务 (预览) 。 </a>  </li>
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
<th><strong>对源环境的预期</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  对于 Exchange Online，我们会全程指导你，直到你的组织可以使用电子邮件为止。 具体步骤取决于源环境和电子邮件迁移计划。  
  我们提供针对以下方面的远程指南：
<ul>
<li>  为 Office 365 中验证的所有启用邮件的域设置 Exchange Online Protection (EOP) 功能。  </li>
<li>  将邮件交换 (MX) Office 365。  </li>
<li>  设置 Office 365 ATP 功能（如果它是订阅服务的一部分）。 有关详细信息，请参阅此表 <strong>的 Office 365 高级威胁</strong> 防护部分。  </li>
<li>  为在 Office 365 中验证的所有已启用邮件的域设置数据丢失防护 (DLP) 功能，将其作为订阅服务的一部分。这可在 MX 记录指向 Office 365 后完成。</li>
<li>  为在 Office 365 中验证的所有已启用邮件的域设置 Office 365 邮件加密 (OME) ，将其作为订阅服务的一部分。这可在 MX 记录指向 Office 365 后完成。</li>
</ul>
  <strong>注意：</strong> 邮箱复制服务支持 (MRS) 尝试将信息权限管理 (IRM) 电子邮件从您的本地邮箱迁移到相应的 Exchange Online 邮箱。 可读取受保护内容迁移后的能力取决于客户映射和将 Active Directory Rights Managed Services (AD RMS) 模板复制到 Azure Rights Management Service (Azure RMS)。  
<ul>
<li>  配置防火墙端口。  </li>
<li>  根据需要设置 DNS，包括所需的自动发现、发件人策略框架 (SPF) 、域密钥识别邮件 (DKIM) 、基于域的邮件身份验证、报告和一致性 (DMARC) 和 MX 记录)  (。  </li>
<li>  设置源邮件环境和 Exchange Online 之间的电子邮件流（根据需要）。  </li>
<li>  执行从源邮件环境到 Office 365 的邮件迁移。  </li>
<li>  配置邮箱客户端（Outlook for Windows、Outlook 网页版以及 Outlook for iOS 和 Outlook for Android）。  </li>
</ul>
  <strong>数据迁移</strong>  <br>
有关使用 FastTrack 权益迁移到 Office 365 的信息，请参阅"<a href="https://review.docs.microsoft.com/fasttrack/data-migration">数据迁移"。</a>   
<td>  源环境必须具有以下最低级别之一：
<ul>
<li>  具有 Exchange Server 2003 前向的单个或多个 Exchange 组织。  </li>
<li>  一个支持 Internet 邮件访问协议 (IMAP) 的电子邮件环境。  </li>
<li>  单个 G 套件环境（仅限 Gmail、联系人和日历）。  </li>
<li>  若要了解多地理位置功能，请参阅 <a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online 中的多地理位置功能</a>。  </li>
</ul>
如 Microsoft 365 Office 的系统要求中的定义，在线客户端软件（如 Project for Office <a href="https://go.microsoft.com/fwlink/?LinkID=723597">365、Outlook</a>for Windows、Outlook for iOS 和 Outlook for Android、OneDrive for Business 同步客户端、Power BI Desktop 和 Skype for Business）必须处于最低级别。  </td>
</tr>
<tr class="even">
<td><strong>Microsoft 信息管控</strong></td>
<td>  我们提供针对以下方面的远程指南：
<ul>
<li>  信息管控。  </li>
<li>  保留标签和策略。  </li>
<li>  记录管理。  </li>
<li>  删除策略。  </li>
<li>  通信合规性。  </li>
<li>  内部风险管理。  </li>
<li>  高级电子数据展示。  </li>
</ul></td>
<td>除了"常规" <strong>中的核心载</strong> 入 <a href="#general">部分外</a>，不存在最低系统要求。</td>
</tr>
<tr class="odd">
<td><strong>Microsoft 信息保护</strong></td>
<td>  我们提供针对以下方面的远程指南：
<ul>
<li>  数据分类。  </li>
<li>  敏感信息类型。  </li>
<li>  创建敏感度标签。  </li>
<li>  应用敏感度标签。  </li>
<li>  统一标记。  </li>
<li>  可训实分类器。  </li>
<li>  使用内容资源管理器和活动资源管理器了解数据。  </li>
<li>  使用手动且自动 (的保留) 。  </li>
<li>  通过针对 Microsoft Teams 聊 (和) ，) DLP 密集防护功能策略。  </li>
</ul></td>
<td>除了"常规" <strong>中的核心载</strong> 入 <a href="#general">部分外</a>，不存在最低系统要求。</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  我们提供针对以下方面的远程指南：
<ul>
<li>  确认为支持 Teams 提供 Exchange Online、SharePoint Online、Office 365 组和 Azure AD 中的最低要求。  </li>
<li>  配置防火墙端口。  </li>
<li>  设置 DNS。  </li>
<li>  确认是否已在 Office 365 租户上启用 Teams。  </li>
<li>  启用或禁用用户许可证。  </li>
<li>  Teams 网络评估：
<ul>
<li>  端口和终结点检查。  </li>
<li>  连接质量检查。  </li>
<li>  带宽预估。  </li>
</ul>
<ul>
<li>  为 Teams Web 应用、Teams (Teams 桌面应用以及适用于 iOS 和 Android 的 Teams 应用) 。  </li>
</ul>
如果适用，我们还提供针对以下方面的指导：
<ul>
<li>  Microsoft Teams 会议室设备：  </li>
</ul>
<ul>
<li>  创建 Teams 设备目录中所列支持的电话和会议室设备所需的在 <a href="https://go.microsoft.com/fwlink/?linkid=2066478">线帐户</a>。  </li>
</ul>
<ul>
<li>  启用音频会议：  </li>
</ul>
<ul>
<li>  会议桥默认设置的组织设置。  </li>
<li>  向许可用户分配会议桥。  </li>
</ul>
<ul>
<li>  手机系统：
<ul>
<li>  组织设置云语音默认设置。  </li>
<li>  我们的可用市场 (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">计划指南) ：</a>
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
<li>  在适用于 Office 365 的 Azure AD 中启用标识。  </li>
<li>  对 SharePoint Online 启用的用户。  </li>
<li>  Exchange 邮箱存在 (Online 和本地存在于 Exchange 混合部署) 。  </li>
<li>  针对 Office 365 组启用。  </li>
</ul>
  <strong>注意：</strong>  如果未向用户分配和启用 SharePoint Online 许可证，则他们不会在 Office 365 中具有 OneDrive for Business 存储。 文件共享继续在"通道"中工作，但是如果 Office 365 中没有 OneDrive for Business 存储，用户将无法共享"聊天"中的文件。 Teams 不支持 SharePoint 本地环境。  <br>
  <strong>注意：</strong>  理想的状态是将所有用户的邮箱都托管在 Exchange Online 上。 将邮箱托管在本地的用户必须通过 Azure AD Connect 将其身份同步至 Office 365 目录。 对于这些 Exchange 混合客户，如果用户的邮箱托管在本地，则用户无法添加或配置连接器。  
  可以从中下载 Microsoft Teams Windows 和 Mac 桌面客户端的安装程序  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> 。  </td>
</tr>
<tr class="odd">
<td><strong>Office 365 高级威胁防护 (ATP)</strong></td>
<td>  我们提供针对以下方面的远程指南：
<ul>
<li>  启用安全链接、安全附件和防钓鱼。  </li>
<li>  配置自动化、调查和响应。  </li>
<li>  使用攻击模拟器。  </li>
<li>  报告和威胁分析。  </li>
</ul></td>
<td>除了"常规" <strong>中的核心载</strong> 入 <a href="#general">部分外</a>，不存在最低系统要求。</td>
</tr>
<tr class="even">
<td><strong>iOS 和 Android 版 Outlook</strong></td>
<td>  我们提供针对以下方面的远程指南：
<ul>
<li>  从 Apple App Store 和 Google Play 下载 Outlook for iOS 和 Outlook for Android。  </li>
<li>  配置帐户和访问 Exchange Online 邮箱。  </li>
<li>  通过 Outlook 移动版 (有关邮箱的详细信息，请参阅"在 Exchange Online 中保护 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Outlook for iOS</a>) 。  </li>
</ul></td>
<td><ul>
<li>  在适用于 Office 365 的 Azure AD 中启用标识。  </li>
<li>  配置了 Exchange Online 并分配了许可证。  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  我们提供针对以下方面的远程指南：
<ul>
<li>  分配 Power BI 许可证。  </li>
<li>  部署 Power BI Desktop 应用。  </li>
</ul></td>
<td>如 Power BI Desktop 等联机客户端软件必须在最低级别上，如 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系统要求中的定义</a>。</td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  我们提供针对以下方面的远程指南：
<ul>
<li>  验证 Project Online 依赖的基本 SharePoint 功能。  </li>
<li>  向你的租户添加 Project Online 服务（包括向用户添加订阅）。  </li>
<li>  设置企业资源池 (ERP)。  </li>
<li>  创建你的首个项目。  </li>
</ul></td>
<td>如 Project for Office 365 的联机客户端软件必须处于最低级别，如 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系统要求中所定义</a>。</td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional 和高级版</strong></td>
<td>  我们提供针对以下方面的远程指南：
<ul>
<li>  解决部署问题。  </li>
<li>  使用 Microsoft 365 管理中心和 Windows PowerShell 分配最终用户许可证。  </li>
<li>  使用即点即用从 Office 365 门户安装 Project Online 桌面客户端。  </li>
<li>  使用 Office 365 部署工具配置更新设置。  </li>
<li>  为 Project Online 桌面客户端 设置一个现场分发服务器，包括帮助创建 configuration.xml 文件以与 Office 365 部署工具一起使用。  </li>
<li>  将 Project Online 桌面客户端 连接到 Project Online Professional 或 Project Online 高级版。  </li>
</ul></td>
<td>如 Project for Office 365，在线客户端软件必须处于最低级别，如 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 和 Office 的系统要求中所定义的最低级别</a>。</td>
</tr>
<tr class="even">
<td><strong>SharePoint Online 和 OneDrive for Business</strong></td>
<td>  我们提供针对以下方面的远程指南：
<ul>
<li>  设置 DNS。  </li>
<li>  配置防火墙端口。  </li>
<li>  设置用户和许可证。  </li>
<li>为你的 SharePoint Online 管理员启用站点创建。</li>
<li>规划网站集。</li>
<li>保护内容安全和管理权限。</li>
<li>配置 SharePoint Online 功能。</li>
<li>  配置 SharePoint 混合功能，如混合搜索、混合网站、混合分类、内容类型、混合自助式网站创建（仅适用于 SharePoint Server 2013）、扩展的应用启动器、混合 OneDrive for Business 和 Extranet 网站。  </li>
<li>  你的迁移方法。  </li>
</ul>
根据您的 SharePoint 版本，还可为 OneDrive for Business 提供其他指南，例如：
<ul>
<li>  标识集成选项并查看本地和联机网络基础结构和带宽。  </li>
<li>  安装 SharePoint Online 2013 SP1 (（如果适用）) 、计划和实施同步和标识要求，并确定 OneDrive for Business 同步客户端。  </li>
<li>  计划并为所有用户或分阶段部署 (或分阶段开) 。  </li>
<li>  将许可证、将"我的网站"和个人文档库重定向到适用于 SharePoint Online 2013) 的 Office 365 (此设置访问群体以控制适用于 SharePoint Online 2013) 的 OneDrive (的访问。  </li>
<li>将已知文件夹重定向或移动到 OneDrive。</li>
<li>  部署 OneDrive for Business 客户端同步。  </li>
</ul>
  <strong>数据迁移</strong>  <br>
有关使用 FastTrack 权益迁移到 Office 365 的信息，请参阅"<a href="https://review.docs.microsoft.com/fasttrack/data-migration">数据迁移"。</a>
</ul></td>
<td><br><strong>对于 SharePoint 混合：</strong>  
<ul>
<li>  SharePoint 混合配置包含配置混合搜索、站点、分类、内容类型、OneDrive for Business（扩展的应用启动器）和从本地连接到单个目标 SharePoint Online 环境的 Extranet 网站和自助式网站创建。  </li>
</ul>
  <strong>注意：</strong> 自助式网站创建不包括运行 SharePoint 2013 的本地服务器的范围内。  
<ul>
<li>  要启用 SharePoint 混合，必须具有以下本地 SharePoint Server 环境之一：2013、2016 或 2019。  </li>
</ul>
  <strong>注意：</strong> 升级到 SharePoint Server 的环境中不在本范围内。 请 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">与 Microsoft</a> 合作伙伴联系以获取帮助。 有关详细信息，请参阅 <a href="https://go.microsoft.com/fwlink/?linkid=853548">SharePoint 混合功能的最低公用更新级别</a><em>。</em>  <br>
  <strong>注意：</strong> 若要了解多地理位置功能，请参阅 <a href="https://go.microsoft.com/fwlink/?linkid=831056">Office 365 中 OneDrive 和 SharePoint Online 中的多地理位置功能</a><em>。</em>  </td>
</tr>
<tr class="odd">
<td><strong>Skype for Business Online</strong></td>
<td>  我们提供针对以下方面的远程指南：
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
  如果适用，FastTrack 还会指导你完成：  </li>
<li>  配置会议室系统设备：
<ul>
<li>  创建受支持的会议室设备（列于 Skype for Business 解决方案目录的"会议室系统"选项卡中 <a href="https://go.microsoft.com/fwlink/?LinkId=615775">）所需的联机帐户</a>。  </li>
</ul></li>
<li>  配置混合和拆分域服务器。  </li>
<li>  配置音频会议：
<ul>
<li>  会议桥默认设置的组织设置。  </li>
<li>  向许可用户分配会议桥。  </li>
</ul></li>
<li>  配置电话系统默认设置：
<ul>
<li>  通话套餐：
<ul>
<li>  向许可证用户分配号码。  </li>
<li>  通过用户界面进行本地号码端口移植指南（最多 99 个）  </li>
<li>  超过 999 的本地号码端口服务请求支持  </li>
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
  <strong>对于混合 Skype for Business：</strong>  
<ul>
<li>  一个本地 Active Directory 林。  </li>
<li>  单个 Active Directory 帐户林前向和资源林（Exchange 和/或 Skype for Business）拓扑。  </li>
<li>  多个 Active Directory 帐户林，其中一个林是包含 Exchange 和/或 Skype for Business 的集中式 Active Directory 帐户林。  </li>
<li>  一个包括 Skype for Business 边缘服务器角色的 Skype for Business Server 2015 环境。  </li>
</ul>
  <strong>注意：</strong> 此额外的服务用于配置和验证拆分域 (混合) 任务，并不包括引入本地组件 (例如 (Lync 2013 管理工具、Lync 2013/Skype for Business Online 服务器或 Lync 2010、Lync 2013 或 Skype for Business 边缘服务器) 。  </td>
</tr>
<tr class="even">
<td><strong>Yammer 企业版</strong></td>
<td><ul>
我们提供了有关启用 Yammer Enterprise 服务的远程指南。  
</ul></td>
<td>如 Microsoft 365 和 Office 的系统要求中的定义 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">，联机客户端软件必须在最低级别</a>。</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>企业移动性&安全性

<table>
<thead>
</tr>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></td>
<td>  我们提供了用于为以下方案保护你的云身份的远程指南。  

 <br/>

<strong>安全底层基础结构</strong>  </ul>
<ul>
<li>  为标识配置和启用强身份验证，包括保护 Azure 多重身份验证 (MFA)  (云)  (云的) 、Microsoft Authenticator 应用以及 Azure MFA 和自助服务密码重置 (SSPR) 的) 。  </li>
<li>  对于非 Azure AD Premium 客户，我们提供了使用安全性默认值保护标识的指导。  </li>
<li>  对于 Azure AD Premium 客户，我们提供了通过条件访问来保护标识的安全指导。  </li>
<li>  通过 Azure AD 密码保护检测并阻止使用弱密码。  </li>
<li>  使用 Azure AD 应用程序代理保护本地 Web 应用的远程访问。  </li>
<li>  使用 Azure Identity Protection 实现基于风险的检测和修复。  </li>
<li>  启用自定义登录屏幕，包括徽标、文本和图像以进行自定义品牌打造。  </li>
<li>  使用 Azure AD B2B 与来宾用户安全共享应用和服务。  </li>
<li>  使用基于角色的访问控制 (RBAC) 管理对 Office 365 管理员的访问权限，并减少特权管理员帐户的数量。  </li>
<li>  配置加入的混合 Azure AD。  </li>
<li>  配置 Azure AD 加入。  </li>
</ul>
  
<strong>监视和报告</strong>  
<ul>
<li>  
  使用 Azure AD Connect Health 启用对 AD FS、Azure AD Connect 和域控制器的远程监视。  
  </li>
</ul>
  
<strong>治理</strong>  
<ul>
<li>  
  使用 Azure AD 权利管理功能，大规模管理 Azure AD 标识和访问生命周期。
  </li>
<li>  
  使用 Azure AD 访问评审管理 Azure AD 组成员身份、企业应用访问和角色分配。  
  </li>
<li>  
  审查 Azure AD 使用条款。  
  </li>
<li>  
  使用 Azure AD Privileged Identity Management 管理和控制特权管理员帐户的访问权限。  
  </li>
</ul>
  
<strong>自动化和效率 </strong>  
<ul>
<li>  
  启用 Azure AD SSPR。  
  </li>
<li>  允许用户使用 Azure AD 自助服务组管理功能创建和管理其自己的云安全或 Office 365 组。  </li>
<li>  使用 Azure AD 委派组管理管理管理管理企业应用的委派访问权限。  </li>
<li>  启用 Azure AD 动态组。  </li>
<li>  使用集合组织"我的应用"门户中的应用。  </li>
</ul></td>
<td>已为 Azure AD Premium 准备了本地 Active Directory 及其环境，其中包括对阻止与 Azure AD 和 Azure AD Premium 功能集成的已确定问题的修正。</td>
</tr>
<tr class="odd">
<td><strong>Azure 信息保护（P2 或 EMS E5）</strong></td>
<td>  我们提供有关如何：
<ul>
<li>  激活并配置租户。  </li>
<li>  创建和设置标签和策略。  </li>
<li>  向文档应用信息保护。  </li>
<li>  自动对在 Windows 上运行的 Office 应用（如Word、PowerPoint、Excel 和 Outlook）中的信息进行分类和标记，并使用 Azure 信息保护客户端。  </li>
<li>  使用带有 Azure 信息保护扫描程序的静态文件。  </li>
<li>  使用 Exchange Online 邮件流规则监视传输中的电子邮件。  </li>
</ul>
如果您要使用 Microsoft Azure 权限管理服务 (Azure RMS) 、Office 365 邮件加密 (OME) 和数据丢失防护 (DLP 服务来应用保护，还建议 () 。  </td>
<td>  你应该已经：
<ul>
<li>  使用 Azure AD。  </li>
<li>  如果其他操作系统范围 (则使用 Windows 或 iOS) 。  
  </ul>
<strong>注意</strong>：计算机和移动设备必须在支持 Azure <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">信息保护</a> 的操作系统上运行。  
<li>  具有主文件共享位置。  </li>
<strong>注意</strong>：必须具有 AD RMS 连接器，则需要混合部署。 
<li>  具有已批准的分类分类。  </li>
<li>  了解针对受保护密钥管理的任何法规限制。  </li>
</ul>
  
<strong>Azure 信息保护扫描程序</strong>  
  
你应该已经：  
<ul>
<li>  使用 Windows Server 2012 R2 或 Windows Server 2016。  </li>
<li>  具有 Internet 连接。  </li>
<li>  在本地Microsoft SQL Server远程实例中实现 2012 年前版本。  </li>
<li>  为本地 Active Directory 创建了服务帐户，并与 Azure AD 同步。  </li>
<li>  已下载AzInfoProtection.exe。  </li>
<li>  已为自动分类/保护配置了标签。  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  我们提供有关准备好使用 Intune 作为基于云的移动设备管理 (MDM) 和适用于应用和设备的移动应用管理 (MAM) 的指南。 具体步骤取决于你的源环境，并且基于你的移动设备和移动应用管理需求。 所包含的具体步骤如下：
<ul>
<li>  许可最终用户。  </li>
<li>  通过利用 Azure AD 域利用本地 Active Directory 或云标识来配置供 Intune () 标识。  </li>
<li>  将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。  </li>
<li>  根据管理需求配置 MDM 颁发机构，包括：
<ul>
<li>  如果 Intune 是唯一的 MDM 解决方案，将 Intune 设置为 MDM 颁发机构。  </li>
</ul></li>
<li>  为以下操作提供 MDM 指南:
<ul>
<li>  配置用于验证 MDM 管理策略的测试组。  </li>
<li>  配置 MDM 管理策略和服务，如：
<ul>
<li>  通过 Web 链接或深度链接为每个受支持的平台部署应用。  </li>
<li>  条件访问策略。  </li>
<li>  部署电子邮件、无线网络和 VPN) 配置文件，如果你的组织中具有现有证书颁发机构、无线网络或 VPN 基础结构。  </li>
<li>  设置 Microsoft Intune Exchange 连接器（如果适用）。  </li>
<li>  连接到 Intune 数据仓库。  </li>
<li>  将 Intune 与以下内容进行集成：
<ul>
<li>  Team Viewer for remote assistance (a Team Viewer subscription is required) .  </li>
<li>  必须提供 MTD (MTD) MTD (移动威胁防护) 。  </li>
<li>  必须使用电信费用管理 (未完成电信费用管理解决方案订阅) 。  </li>
<li>  必须有 Microsoft Defender ATP (Windows E5 或 Microsoft 365 E5) 。  </li>
</ul></li>
<li>  将每个受支持平台的设备注册到 Intune。  </li>
</ul></li>
</ul></li>
<li>  为以下操作提供应用保护指导：
<ul>
<li>  为每个受支持的平台配置应用保护策略。  </li>
<li>  为托管应用配置条件访问策略。  </li>
<li>  使用上面提到的 MAM 策略定向相应的用户组。  </li>
<li>  使用托管应用使用情况报告。  </li>
</ul></li>
<li>  提供从旧电脑管理到 Intune MDM 的迁移指南。  </li>
</ul>
  <strong>注意</strong>：2020 年 10 月 15 日以来不再支持旧电脑管理。  
</li>
</ul>
  
<strong>云附加</strong>  

  我们会指导你如何准备好使用 Intune 云附加现有 Configuration Manager 环境。 具体步骤取决于源环境。 这些步骤包括：  
<ul>
<li>  介绍使用 Intune 云附加 Configuration Manager 的好处。  </li>
<li>  许可最终用户。  </li>
<li>  通过利用本地 Active Directory 和云标识，配置供 Intune 使用的标识。  </li>
<li>  将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。  </li>
<li>  在配置管理器控制台中启用云附加。  </li>
<li>  提供设置混合 Azure AD 加入的指南。  </li>
<li>  提供有关为 MDM 自动注册设置 Azure AD 的指南。  </li>
<li>  提供有关如何设置云管理网关的指南。  </li>
<li>  配置要切换到 Intune 的受支持工作负载。  </li>
<li>  在 Intune 注册的设备中安装 Configuration Manager 客户端。  </li>
</ul> 

<strong>安全地部署适用于 iOS 和 Android 的 Outlook Mobile</strong> 我们可以提供指导，帮助您在组织中安全地部署适用于 iOS 和 Outlook Mobile for Android 的 Outlook 移动版，以确保你的用户安装了所有所需的应用。  
  使用 Intune 安全地部署 Outlook Mobile for iOS 和 Outlook Mobile for Android 的步骤取决于源环境。 其中可能包括：
<ul>
<li>  通过 Apple App Store 或 Google Play Store 下载 Outlook for iOS 和 Outlook for Android、Microsoft Authenticator 和 Intune 公司门户应用。  </li>
<li>  提供设置指南：
<ul>
<li>  Outlook for iOS 和 Outlook for Android、Microsoft Authenticator 和 Intune 公司门户的应用部署及 Intune。  </li>
<li>  应用保护策略。  </li>
<li>  条件访问策略。  </li>
<li>  应用程序配置策略。  </li>
</ul></li>
</ul>
  
  <strong>注意</strong>：FastTrack 不支持使用 Exchange 移动设备邮箱策略保护 Outlook for iOS 和 Outlook for Android。 请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a> 联系以获取有关此帮助的帮助。  
  </td>
<td>  在计划使用 Intune 部署无线网络和 VPN 配置文件时，IT 管理员需要确保现有证书颁发机构、无线网络和 VPN 基础结构已经在其生产环境中正常使用。  
  <strong>注意</strong>：FastTrack 服务权益不包括有关设置或配置证书颁发机构、无线网络、VPN 基础结构或 Intune 的 Apple MDM 推送证书的帮助。  

<strong>使用 Intune 云附加 Configuration Manager </strong>  

 通过云附加，IT 管理员负责准备本地环境。 这可能包括修复阻止你使用 Intune 云附加 Configuration Manager 环境的问题。  
  <strong>注意</strong>：FastTrack 服务权益不包括有关将配置管理器站点服务器或配置管理器客户端设置或升级到支持云附加所需的最低要求的帮助。 请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a> 联系以获取有关此帮助的帮助。

  <strong>Intune 与 Microsoft Defender 高级威胁防护 (ATP) 集成</strong> 
 
  <strong>注意</strong>：我们提供有关将 Intune 与 Microsoft Defender ATP 集成并根据其 Windows 10 风险级别评估创建设备合规性策略的帮助。 我们不提供有关执行许可、许可或激活的帮助。 请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a> 联系以获取有关此帮助的帮助。  
  
<strong>Windows Autopilot</strong> 
 
  IT 管理员负责通过让硬件供应商代表他们上载其硬件 ID 或自己将其上载到 Windows Autopilot 服务中来向其组织注册设备。  
  
<strong>使用 Intune 安全地部署 Outlook for iOS 和 Outlook for Android </strong>  
<ul>
<li>  在适用于 Office 365 的 Azure AD 中启用用户标识。  </li>
<li>  配置有已分配的用户许可证的 Exchange Online 或混合 Exchange。  </li>
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
<th><strong>对源环境的预期</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  我们会提供指导，帮助你从 Windows 8.1 Windows 7 专业版 专业版升级到 Windows 10 企业版。  
  我们提供针对以下方面的远程指南：
<ul>
<li>  了解 Windows 10 的意图。  </li>
<li>  评估你的源环境和要求 (确保 Microsoft Endpoint Configuration Manager 已升级到所需级别，才能支持 Windows 10) 。  </li>
<li>  使用 Microsoft Endpoint Configuration Manager 或 Microsoft 365 部署 Windows 10 企业版和 Microsoft 365 应用版。  </li>
<li>  推荐用于评估 Windows 10 应用的选项。  </li>
<li>  启用桌面分析的使用以及通过创建桌面分析部署计划的指南。  </li>
<li>  利用 Configuration Manager 中的 Office 365 准备仪表板，或使用独立准备情况 Toolkit for Office 并帮助部署 Microsoft 365 应用版，来评估 Microsoft 365 应用版兼容性。  </li>
<li>  评估新式管理策略，包括将 Configuration Manager 云附加到 Microsoft Intune，或将 Intune 部署为仅云管理解决方案。  </li>
<li>  以制表达源环境所需的修正清单，使您的源环境达到成功部署的最低要求。  </li>
<li>  如果现有设备满足所需的设备硬件要求，请为其提供升级指南以将它们与 Windows 10 企业版连接。  </li>
<li>  提供升级指南以支持现有部署运动。 FastTrack 推荐并提供有关就地升级到 Windows 10 的指南。 指南还可用于 Windows 干净图片安装和 Windows Autopilot 部署方案。  </li>
<li>  使用 Configuration Manager 部署 Microsoft 365 应用版作为 Windows 10 部署的一部分。   </li>
<li>  提供指导，以帮助你的组织使用现有 Configuration Manager 环境或 Microsoft 365 保持最新的 Windows 10 企业版和 Microsoft 365 应用版。  </li>
<li>  提供指导指导，通过将 Configuration Manager 云附加到 Intune 或在所需的情况下部署 Intune 独立 (启用现) 。  </li>
</ul>
  <strong>在以下内容范围内 </strong>  
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
<li>  源操作系统：Windows 7 企业版专业版、Windows 8.1 企业版或专业版。  </li>
<li>  设备：台式机、笔记本电脑或平板电脑设备。  </li>
<li>  目标操作系统：Windows 10 企业版。  </li>
</ul>
若要升级基础结构，必须满足以下要求：
<ul>
<li>  Microsoft Endpoint Configuration Manager。  </li>
<li>  Configuration Manager 版本必须受 Windows 10 目标版本支持。 有关详细信息，请参阅 Configuration Manager 中 Windows <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">10 支持处的 Configuration</a>Manager 支持表格。  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender 高级威胁防护 (ATP)</strong></td>
<td>  Microsoft Defender 高级威胁防护 (ATP) 是旨在帮助企业网络预防、检测、调查和响应高级威胁的平台。  
  我们提供针对以下方面的远程指南：
<ul>
<li>  部署技术来保护终结点安全。  </li>
<li>  配置终结点保护和设备限制配置文件。  </li>
<li>  评估 OS 版本和设备管理 (包括 Intune、Microsoft Endpoint Configuration Manager、组策略对象 (GPO) 和第三方配置) 以及 Windows Defender AV 服务或其他终结点安全软件的状态。  </li>
<li>  评估 Windows AV 服务或其他端点安全软件的状态。  </li>
<li>  评估限制网络流量的代理和防火墙。  </li>
<li>  通过说明如何使用板载终结点部署 ATP 代理配置文件来启用 Microsoft Defender ATP 服务。  </li>
<li>  部署指导、配置协助和教育以下方面：
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
<li>  查看模拟和教程 (方案、假恶意软件以及自动调查) 。  </li>
<li>  报告和威胁分析功能概述。  </li>
<li>  将 Office 365 ATP 与 Microsoft Defender ATP 集成。  </li>
<li>  在 Microsoft Defender 安全中心门户中执行演练。  </li>
<li>  下列操作系统：
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
  SAC 版本 1803 (Windows Server) 频道。  
  </li>
<li>  
  macOS 版本 10.13、10.14 和 10.15。  
  </li>
</ul>
</li>
</ul>
<strong>注意：</strong> 所有 Windows Server 版本都必须由 System Center Configuration Manager 2012 (版本 1012 R2、1511 或 1602) 或 Microsoft Endpoint Configuration Manager (版本 2002 或更高版本) 进行管理。 

</li>
</ul>

<strong>在以下内容范围内 </strong>  
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
  Linux。  
  </li>
<li>  
  Android 和 iOS (的) 。  
  </li>
</ul></li>
<li>  服务器载入和配置：
<ul>
<li>  
  配置代理服务器进行脱机通信。  
  </li>
<li>  
  在下层 Configuration Manager 实例和版本上配置 Configuration Manager 部署包。  
  </li>
<li>  
  将服务器载入 Azure 安全中心。  
  </li>
<li>  
  服务器不是由配置管理器管理。  
  </li>
</ul></li>
<li>  macOS 载入和配置：
<ul>
<li>  
  基于 Intune 的手动部署。  
  </li>
<li>  
  基于 JAMF 的部署。
  </li>
<li>  
  MDM 在 MDM () 的移动设备管理。  
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
  应用控件。  
  </li>
<li>  
  Exploit Protection。  
  </li>
<li>  
  网络防火墙。  
  </li>
</ul></li>
<li>  注册或配置 Microsoft 威胁专家。  </li>
<li>  配置或培训审查 API 或安全信息以及 SIEM 连接 () 管理。  </li>
<li>  注册或配置 Microsoft 威胁防护 (MTP)。  </li>
<li>  有关高级搜寻的培训或指导。  </li>
<li>  关于使用或创建 Kusto 查询的培训或指南。</li>
</li>
</ul>
联系 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a> 以获取有关这些服务的帮助。  
</ul></td>
<td></td>

</tbody>
</table>
