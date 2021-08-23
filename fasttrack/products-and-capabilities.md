---
title: 产品和功能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 8/18/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: 本主题包含有关应用程序支持的工作负荷FastTrack以及开始之前所需的源环境预期。 根据您的当前设置，我们将与用户一起制定修正计划，使源环境达到成功载入的最低要求。
ms.openlocfilehash: b885d646bb7159cc0fdfdfc05884293c98eeec92
ms.sourcegitcommit: 71ec2c25b514f3a21ed58ca3499af1576e8f2c8d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/18/2021
ms.locfileid: "58392402"
---
# <a name="products-and-capabilities"></a>产品和功能

## <a name="services-and-scenarios-supported-by-fasttrack"></a>支持的服务和FastTrack 

本主题包含有关应用程序支持的工作负荷FastTrack以及开始之前所需的源环境预期。 根据您的当前设置，我们将与用户一起制定修正计划，使源环境达到成功载入的最低要求。

FastTrack指南可帮助你首先获得所有 (通用的核心Microsoft Online Services) ，然后载入每个符合条件的服务：

  - [常规](#general)
  - [安全性和符合性](#security-and-compliance)
  - [Office 365](#office-365)
  - [企业移动性 + 安全性](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Windows 虚拟桌面](#windows-virtual-desktop)
  - [应用保证](#app-assure)
  - [Microsoft Edge](#microsoft-edge)

> [!NOTE]
> 若要了解 Office 365 US Government 的源环境预期，请参阅 [Office 365 US Government 的源环境预期](US-Gov-appendix-source-environment-expectations.md)。    
 
## <a name="general"></a>常规

<table>
<table style="width: 100%">
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>服务</th>
<th>FastTrack指南详细信息</th>
<th>源环境预期</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>核心入门</strong></td>
<td>  我们提供有关核心载入的远程指导，其中包括服务预配、租户和标识集成。 它还包括为载入服务（如 Exchange Online、SharePoint Online 和 Microsoft Teams）提供基础的步骤，包括有关安全性、网络连接和合规性<a href="/office365/enterprise/office-365-network-connectivity-principles">的讨论</a>。   

在核心载入完成后，便可以开始载入一个或多个符合条件的服务。
</li>
</ul>  

<strong> 标识集成 </strong>

我们提供针对：
<ul>
<li>准备本地 Active Directory 标识以同步到 Azure Active Directory (Azure AD) 包括安装和配置 Azure AD 连接 (单林或多林) 以及 (包括基于组的许可) 。</li>
<li>创建云标识，包括批量导入和许可，包括使用基于组的许可。</li>
<li>为云旅程选择和启用正确的身份验证方法、密码哈希同步、传递身份验证或 Active Directory 联合身份验证服务 (AD FS) 。</li>
<li> 选择无密码身份验证 (Fast Identity Online (FIDO) 2 或 Microsoft Authenticator App) ，为用户提供更方便的身份验证体验。</li>
<li>为具有单个 Active Directory 林和标识与 Azure AD 连接工具同步的客户启用 AD FS。 这需要Windows Server 2012 R2 Active Directory 联合身份验证服务 2.0 或更大。</li>
<li>使用密码哈希同步或传递身份验证将身份验证从 AD FS 迁移到 Azure AD。</li>
<li>将预集成应用 (如 Azure AD 库软件即服务 (SaaS) 应用) 从 AD FS 迁移到 Azure AD，实现单一登录 (SSO) 。</li>
<li>从 Azure AD 库启用 SaaS 应用与 SSO 的集成。</li>
<li>为预集成 SaaS 应用启用自动用户预配（如应用集成教程列表 <a href="/azure/active-directory/saas-apps/tutorial-list"> (仅限于 </a> Azure AD 库 SaaS 应用和仅) ）。  </li>

</td>

<td>  <strong>网络启用 </strong>  
  <br>作为该FastTrack的一部分，我们建议你采用连接到云服务的最佳实践，以确保实现最佳性能Microsoft 365。  
  
<strong>Active Directory 林</strong>它们的功能林级别设置为 Windows Server 2003 前向，具有以下林配置：
<ul>
<li>  单个 Active Directory 林。  </li>
<li>  单一 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。  </li>
<li>  多个 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。  </li>
<li>  多个 Active Directory 帐户林，其中的一个林是一个含有 Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business 的集中式 Active Directory 帐户林。  </li>
<li>  多个 Active Directory 帐户林，每一个都有自己的 Exchange 组织。  </li>
<li>  租户配置和集成所需的任务Azure Active Directory，如果需要。   </li>
</ul>
  <strong>重要</strong>  <ul>
<li>  对于多林 Active Directory 方案，如果部署了 Lync 2010、Lync 2013 或 Skype for Business，则必须将其部署在 Exchange 相同的 Active Directory 林中。  </li>
<li>  在 Exchange 多混合配置中实现具有多个 Exchange 组织的多个 Active Directory 林时，不支持源林之间的共享用户主体名称 (UPN) 命名空间。 Exchange 组织之间的主要 SMTP 命名空间也应该进行分隔。 有关详细信息，请参阅 <a href="https://go.microsoft.com/fwlink/?linkid=845444">具有多个 Active Directory 林的混合部署</a>。  </li>
<li>  对于所有多林配置，Active Directory 联合身份验证服务 (AD FS) 超出了范围。 请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> 以寻求帮助。  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft 365 应用版</strong></td>
<td>  我们提供针对：
<ul>
<li>  解决部署问题。  </li>
<li>  使用 Microsoft 365 管理中心和 Windows PowerShell 分配基于最终用户和设备的许可证。  </li>
<li>  使用即点即用从 Office 365 门户安装 Microsoft 365 应用版。  </li>
<li>  在 iOS 或 Android 设备上安装 Office Mobile 应用（如 Outlook Mobile、Word Mobile、Excel Mobile 和 PowerPoint Mobile）。  </li>
<li>  使用 Office 365 部署工具配置更新设置。  </li>
<li>  本地或云安装的选择和设置。  </li>
<li>  使用 Office 自定义工具或用于配置部署包的本地 XML 创建 Office 部署工具配置 XML。  </li>
<li>  使用 Microsoft Endpoint Configuration Manager 的部署，包括帮助创建 Microsoft Endpoint Configuration Manager 打包。  
  此外，如果你有与 Office 早期版本一起工作的宏或外接程序，并且你遇到兼容性问题，我们会指导通过应用保证计划免费修复兼容性问题。 有关详细信息，<strong>请参阅</strong><a href="#windows-10">Windows 10保证部分</a>。 </li>
</ul></td>
<td><ul>
<li>  联机客户端软件必须处于最低级别，如 system <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requirements for Microsoft 365 and Office .</a>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>网络运行状况</strong></td>
<td>  我们提供远程指导，以便从你的环境获取和解释关键网络连接数据，说明组织的网站如何与 Microsoft 的网络连接 <a href="/office365/enterprise/office-365-network-connectivity-principles">原则保持一致</a>。 这突出显示了直接影响迁移速度、用户体验、服务性能和可靠性的网络分数。  
  我们还将指导你完成此数据突出显示的任何修正步骤，以帮助你提高网络分数。  </td>
<td><ul>
<li>  Microsoft 365 管理居中访问。  </li>
<li>  需要最新版本的 Microsoft 365 应用。  </li>
<li>  根据 Microsoft 365 管理 Center 预览版中的网络性能 (<a href="/Office365/Enterprise/office-365-network-mac-perf-overview">启用</a>) 。  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a>安全性和合规性

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>服务</th>
<th>FastTrack指南详细信息</th>
<th>源环境预期</th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><strong>Azure Active Directory (Azure AD) 和 Azure AD Premium</strong></td>
<td>  我们针对以下方案提供用于保护云标识的远程指南。  

 <br/>

<strong>安全基础基础结构</strong>  </ul>
<ul>
<li>  为标识配置和启用强身份验证，包括使用 Azure 多重身份验证 (MFA)  (仅) 、Microsoft Authenticator 应用以及 Azure MFA 和自助服务密码重置联合注册 (SSPR) 进行保护。  </li>
<li> 部署 FIDO2 或 Microsoft Authenticator App。 </li>
<li>  对于非Azure AD Premium客户，提供了使用安全默认值保护标识的指南。  </li>
<li>  对于 Azure AD 高级客户，提供了使用条件访问保护标识的指南。  </li>
<li>  通过 Azure AD 密码保护检测并阻止使用弱密码。  </li>
<li>  使用 Azure AD 应用程序代理保护对本地 Web 应用的远程访问。  </li>
<li>  使用 Azure Identity Protection 启用基于风险的检测和修正。  </li>
<li>  启用自定义登录屏幕，包括徽标、文本和具有自定义品牌的图像。  </li>
<li>  使用 Azure AD B2B 安全地与来宾用户共享应用和服务。  </li>
<li>  使用基于角色Office 365的访问控制 (RBAC) 内置管理角色管理你的管理员的访问权限，并减少特权管理员帐户的数量。  </li>
<li>  配置混合 Azure AD 加入。  </li>
<li>  配置 Azure AD 加入。  </li>
</ul>
  
<strong>监视和报告</strong>  
<ul>
<li>  
  使用 Azure AD 连接 Health 为 AD FS、Azure AD 连接启用远程监视。  
  </li>
</ul>
  
<strong>治理</strong>  
<ul>
<li>  
  通过 Azure AD 权利管理大规模管理 Azure AD 标识和访问生命周期。
  </li>
<li>  
  使用 Azure AD 访问评审管理 Azure AD 组成员身份、企业应用访问权限和角色分配。  
  </li>
<li>  
  查看 Azure AD 使用条款。  
  </li>
<li>  
  使用 Azure AD 管理中心管理和控制对特权管理员Privileged Identity Management。  
  </li>
</ul>
  
<strong>自动化和效率 </strong>  
<ul>
<li>  
  启用 Azure AD SSPR。  
  </li>
<li>  允许用户使用 Azure AD 自助服务组管理创建和管理Office 365云安全组或用户组。  </li>
<li>  使用 Azure AD 委派组管理管理企业应用的委派访问权限。  </li>
<li>  启用 Azure AD 动态组。  </li>
<li>  使用集合在"我的应用程序"门户中组织应用。  </li>
</ul></td>
<td>本地 Active Directory 及其环境已针对 Azure AD Premium 做好准备，包括修复阻止与 Azure AD 和 Azure AD Premium集成的问题。</td>
</tr>
<tr class="odd">
<td><strong>Azure 信息保护 </strong></td>
<td>  有关 Azure 信息保护详细信息<strong>，请参阅Microsoft 信息保护</strong>中进一步的信息。

  </td>
<td>  
  <tr class="odd">
<td><strong>发现&响应</strong></td>
<td>  

<strong>高级电子数据展示</strong>
  
我们提供针对： 
<ul>
<li>  创建新案例。   </li>
<li>  将保管人置于保留状态。  </li>
<li>  执行搜索。 </li>
<li>  将搜索结果添加到审阅集。 </li>
<li>  对审阅集运行分析。  </li>
<li>  审阅和标记文档。  </li>
<li>  从审阅集导出数据。 </li>
<li>  导入非Office 365数据。 </li>
</ul>

<strong>仅在 E5</strong> (支持高级审核) 

我们提供针对：  
<ul>
<li> 启用高级审核。</li>
<li> 在 UI 和审核日志 PowerShell 命令中执行搜索。</li>
</ul>

<strong> 合规性管理器</strong>

我们提供针对：  

<ul> <li>查看角色类型。  </li>
<li> 添加和配置评估。</li>
<li> 通过实施改进操作来评估合规性并确定这对合规性分数的影响。</li>
<li> 查看内置控件映射和评估控件。</li>
<li> 在评估内生成报告。</li>
</ul>

<strong>以下内容超出范围 </strong> 
<ul>
<li> 自定义脚本或编码。</li>
<li> 电子数据展示 API。 </li>
<li> 数据连接器。 </li>
<li> 合规性边界和安全筛选器。</li>
<li> 数据调查。</li>
<li> 数据主体请求。</li>
<li> 设计、架构师和第三方文档审阅。</li>
<li> 遵守行业和区域法规和要求。</li>
<li> 合规性管理器中评估的建议改进措施的动手实施。</li>
</ul>
</td>
<td>除常规 <strong>中的核心</strong> 载入 <a href="#general">部分外</a>，没有最低系统要求。</td>
</tr>

<tr class="odd">
<td><strong>内部风险管理</strong></td>

<td>  我们提供针对：
<ul>
<li> 创建策略并查看设置。</li>
<li> 访问报告和警报。</li>
<li> 创建案例。</li>
<li> 创建通知模板。</li>
<li> 有关创建人力资源和人力资源 () 指南。</li>
</ul>

<strong> 通信合规性 </strong> 

我们提供针对： 
<ul>
<li> 创建策略并查看设置。</li>
<li> 访问报告和警报。</li>
<li> 创建通知模板。</li>
</ul>

<strong> 合规性管理器</strong>

我们提供针对：  

<ul> <li>查看角色类型。  </li>
<li> 添加和配置评估。</li>
<li> 通过实施改进操作来评估合规性并确定这对合规性分数的影响。</li>
<li> 查看内置控件映射和评估控件。</li>
<li> 在评估内生成报告。</li>
</ul>

<strong>以下内容超出范围 </strong> 
<ul>
<li> 创建和管理Power Automate流。</li>
<li> 数据连接器 (HR 连接器) 。 </li>
<li> 使用 RegEx (配置的) 正则表达式。</li>
<li> 设计、架构师和第三方文档审阅。</li>
<li> 信息屏障。</li>
<li> 特权访问管理。</li>
<li> 遵守行业和区域法规和要求。</li>
<li> 合规性管理器中评估的建议改进措施的动手实施。</li>
</ul></td>
<td>除常规 <strong>中的核心</strong> 载入 <a href="#general">部分外</a>，没有最低系统要求。</td>
</tr>
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender是一个统一的攻破前和入侵后企业防御套件，在本机协调跨终结点、标识、电子邮件和应用进行检测、预防、调查和响应，以提供对复杂攻击的集成保护。 我们提供针对： </p> 
<ul>
<li>  提供安全中心Microsoft 365概述。  </li>
<li>  查看跨产品事件，包括通过确保完整的攻击范围、受影响的资产和分组在一起的自动修正操作，重点关注关键方面。  </li>
<li>  演示Microsoft 365 Defender如何安排对资产、用户、设备和邮箱的调查，这些资产、用户、设备和邮箱可能由于自动自我修复而受到威胁。 </li>
<li>  解释并提供客户如何主动搜寻跨多个数据集影响您的电子邮件、数据、设备和帐户的入侵尝试和入侵活动的示例。   </li>
<li> 向客户展示他们如何使用 Microsoft 安全分数全面查看和改进安全状况。</li>
</ul>
<p><strong>以下内容超出范围</strong></p>
<ul>
<li> 客户补救活动的项目管理。 </li>
<li> 持续管理、威胁响应和修正。 </li>
<li> 部署指南或教育：：
<ul>
<li> 如何修正或解释各种警报类型和受监视的活动。 </li>
<li> 如何调查用户、计算机、横向移动路径或实体。 </li>
<li> 自定义威胁搜寻。  </li>
</ul>
</li>
<li> 支持<a href=" /fasttrack/us-gov-appendix-overview">GCC-High美国政府GCC-DoD (Office 365或) 。 </a></li>
<li> SIEM 或 API (安全) 事件管理。</li>
</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security 是云访问安全代理 (CASB) ，可提供丰富的可见性、控制数据传输和复杂分析，以识别和防御所有 Microsoft 和第三方云服务中的网络威胁。 我们提供针对：
<ul>
<li>  配置门户，包括：  </li>
<ul>
<li> 导入用户组。</li>
<li> 管理管理员访问权限和设置。  </li>
<li> 将部署范围确定为选择要监视或排除在监控范围中的某些用户组。</li>
<li> 如何设置 IP 范围和标记。</li>
<li> 使用徽标和自定义消息来个性化最终用户体验。</li>
</ul>
<li> 集成第一方服务，包括：
<ul>
<li> Microsoft Defender for Endpoint。</li>
<li> Microsoft Defender for Identity。</li>
<li> Azure AD 身份保护。</li>
<li> Azure 信息保护。</li>
</ul>
<li> 使用：</li>
<ul>
<li> 适用于终结点的 Microsoft Defender。</li>
<li> Zscaler。</li>
<li> iboss。</li>
</ul>
<li> 创建应用标记和类别。</li>
<li> 根据组织优先级自定义应用风险评分。</li>
<li> 批准和取消批准应用。</li>
<li> 查看云应用安全和云发现仪表板。</li>
<li> 使用 <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> 应用连接器</a> 连接特色应用。</li>
<li> 使用 Azure AD 和 Azure AD 内条件访问中的条件访问应用控制云应用安全应用。</li>
<li> 为特色应用部署条件访问应用控制。</li>
<li> 使用活动和文件日志。</li>
<li> 管理 OAuth 应用。</li>
<li> 查看和配置策略模板。</li>
<li> 为 CASB 的 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> 大用例提供配置帮助 (包括创建或更新多达 6 (6) 策略) 除外： </li>
<ul>
<li> 审核将 Internet 作为服务配置 (IaaS) 环境 (#18) 。</li>
<li> 监视用户活动，以抵御 IaaS 环境中 (#19) 。</li>
</ul>
<li> 了解事件门户中的Microsoft 365 Defender相关。</li>
</ul>
<p><strong>以下内容超出范围</strong></p>
<ul>
<li> 客户补救活动的项目管理。</li>
<li> 持续管理、威胁响应和修正。 </li>
<li> 讨论比较云应用安全 CASB 产品/服务。</li>
<li> 配置云应用安全以满足特定的合规性或法规要求。</li>
<li> 将服务部署到非测试生产环境。</li>
<li> 部署 Cloud App Discovery 作为概念证明。</li>
<li> 支持<a href=" /fasttrack/us-gov-appendix-overview">GCC-High或GCC-DoD (Office 365美国政府</a>) 。</li>
<li> 使用 Docker 或日志收集器为连续报告设置自动日志上载的基础结构、安装或部署。 </li>
<li> 创建云发现快照报告。</li>
<li> 使用阻止脚本阻止应用使用。</li>
<li> 连接自定义应用。</li>
<li> 为非特色应用载入和部署条件访问应用控制。</li>
<li> 与第三方标识提供程序 (ISP) DLP (和数据丢失) 集成。</li>
<li> 有关高级搜寻的培训或指导。</li>
<li> 自动调查和修正，包括 Microsoft Power Automate手册。</li>
<li> SIEM (或 API 集成) 安全信息和事件管理 (Azure Sentinel) 。</li>

</ul></td>
</tr>



<tr class="even">
<td><strong>Microsoft Defender for Endpoint</strong></td>
<td>  Microsoft Defender for Endpoint 是旨在帮助企业网络预防、检测、调查和响应高级威胁的平台。  
  我们提供针对：
<ul>
<li>  部署技术以确保终结点安全。  </li>
<li>  配置终结点保护和设备限制配置文件。  </li>
<li>  评估操作系统版本和设备管理 (包括 Intune、Microsoft Endpoint Configuration Manager、组策略对象 (GPO) 和第三方配置) 以及 Windows Defender AV 服务或其他终结点安全软件的状态。  </li>
<li>  评估你的 Windows AV 服务或其他终结点安全软件的状态。  </li>
<li>  评估限制网络流量的代理和防火墙。  </li>
<li>  通过说明如何使用受支持的管理方法之一为 (EDR) 部署 Defender for Endpoint 终结点检测和响应，从而启用 Microsoft Defender for Endpoint 服务。  </li>
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
  EDR。  
  </li>
<li>  
  自动调查和修复。  
  </li>
<li>  
  设备的安全分数。  
  </li>
<li> Microsoft Defender SmartScreen配置Microsoft Endpoint Manager。</li>
<li> 设备发现。</li>

</ul></li>
<li>  查看模拟和教程 (如实践方案、假恶意软件和自动调查) 。  </li>
<li>  报告和威胁分析功能的概述。  </li>
<li>  将 Microsoft Defender for Office 365与 Microsoft Defender for Endpoint 集成。  </li>
<li>  在 Microsoft Defender 安全中心门户中执行演练。  </li>
<li>  载入和配置以下操作系统：
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
  WindowsServer 2019 Core Edition。  
  </li>
<li>  
  WindowsServer Semi-Annual Channel (SAC) 版本 1803。  
  </li>
<li>  
  支持的 macOS 版本 (请参阅 <a href="/microsoft-365/security/defender-endpoint/microsoft-defender-endpoint-mac?view=o365-worldwide#system-requirements"> 系统要求 </a> ，详细了解) 。  
  </li>
</ul>
</li>
</ul>
<strong>注意：</strong>所有 Windows Server 版本都必须由最新版本的 System Center Configuration Manager 2012 (版本 1012 R2、1511 或 1602) 或 Microsoft Endpoint Configuration Manager (版本 2002 或) 。 

</li>
</ul>

<strong>以下内容超出范围 </strong>  
<ul>
<li>  客户补救活动的项目管理。  </li>
<li> 支持<a href=" /fasttrack/us-gov-appendix-overview">GCC-High或GCC-DoD (Office 365美国政府</a>) 。</li>
<li>  现场支持。  </li>
<li>  持续管理和威胁响应。  </li>
<li>  以下 Microsoft Defender 终结点代理的载入或配置：
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
  Android 和 iOS (移动设备) 。  
  </li>
<li> 虚拟桌面 (VDI)  (持久或非永久性) 。  </li>
</ul></li>
<li>  服务器载入和配置：
<ul>
<li>  
  为脱机通信配置代理服务器。  
  </li>
<li>  
  在下层 Configuration Manager 实例和版本上配置 Configuration Manager 部署包。  
  </li>
<li>  
  将服务器载入 Azure 安全中心。  
  </li>
<li>  
  未由 Configuration Manager 管理的服务器。  
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
  MDM 的其他移动设备 (MDM) 基于产品的部署。  
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
<li> 设备控件。</li>
<li>  
  Exploit Protection。  
  </li>
<li>  
  网络防火墙。  
  </li>



</ul></li>
<li> 帐户保护功能的配置或管理，例如： </li>
<ul>

<li> Windows Hello</li>
<li> Credential Guard</li>
</ul>
<li> BitLocker 的配置或管理。</li>
<li> 网络设备发现的配置或管理。 </li>
<li> 以下设备发现功能的配置或管理：</li>
<ul>
<li> 未在作用域内（如 Linux FastTrack (）的未托管) 。</li>
<li> 与第三方工具集成。</li>
<li> 设备发现排除项。</li>
<li> 初步网络协助。 </li>
<li> 网络问题疑难解答。</li>
</ul>
<li>  注册或配置 Microsoft 威胁专家。  </li>
<li>  查看 SIEM 连接中的 API 或安全信息 (或) 培训。  </li>
<li>  注册或配置Microsoft 365 Defender。  </li>
<li>  有关高级搜寻的培训或指导。  </li>
<li>  有关使用或创建 Kusto 查询的培训或指南。</li>
<li> 有关使用组策略对象进行 Defender SmartScreen 配置的培训或指南 (GPO) 、Windows 安全中心或 Microsoft Edge。</li>
</li>
</ul>
请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender for Identity </strong></td>
<td>  Microsoft Defender for Identity 是一种基于云的安全解决方案，可利用本地 Active Directory 信号来识别、检测和调查针对组织的高级威胁、已遭入侵标识和恶意内部行为。 我们提供针对：
<ul>
<li>  运行大小工具进行资源容量规划。 </li>
<li>   创建适用于标识的 Defender 实例。 </li>
<li>   将 Defender for Identity 连接到 Active Directory。 </li>

<li>  部署传感器以捕获和分析网络流量，Windows域控制器捕获和分析网络事件，包括： </li>
<ul> 
<li>  下载传感器程序包。 </li>
<li>  配置传感器。 </li>
<li>  以静默方式在域控制器上安装传感器。 </li>
<li>  将传感器部署到多林环境。 </li>
<li> 配置Windows事件收集器。</li>
</ul>
<li>  配置门户，包括： </li>
<ul>
<li> 将 Defender for Identity 与Microsoft Cloud App Security (云应用安全不需要集成许可) 。 </li>
<li> 配置实体标记。</li>
<li> 标记敏感帐户。 </li>
<li> 接收有关运行状况问题和安全警报的电子邮件通知。 </li>
<li> 配置警报排除项。  </li>
</ul>
<li> 提供有关： 的部署指南、配置帮助和教育：</li>
<ul>
<li> 了解身份安全状态评估报告。</li>
<li> 了解用户调查优先级分数和用户调查排名报告。</li>
<li> 了解非活动用户报告。</li>
<li> 有关遭到入侵的帐户的修正选项的说明。</li>
</ul>
<li>  推动从高级威胁分析 (ATA) 到 Defender for Identity。 </li>
</ul>
<p><strong>以下内容超出范围</strong></p>
<ul>

<li> 客户补救活动的项目管理。 </li>
<li> 持续管理、威胁响应和修正。  </li>
<li> 部署 Defender for Identity 作为概念证明。</li>
<li> 支持<a href=" /fasttrack/us-gov-appendix-overview">GCC-High美国政府GCC-DoD (Office 365或) 。 </a></li>
<li> 部署或执行以下 Defender for Identity 传感器活动： </li>
<ul>
<li> 手动容量规划。 </li>
<li> 运行审核工具。 </li>
<li> 部署独立传感器。 </li>
<li> 部署到 Active Directory 联合身份验证服务 (AD FS) 服务器。
<li> 使用网络接口卡部署传感器 (NIC) 适配器。 </li>
<li> 通过第三方工具部署传感器。 </li>
<li> 通过 Web 代理连接连接到 Defender for Identity 云服务。 </li>
</ul>
<li> 在 Active Directory (MSA) Microsoft 帐户。
<li> 创建和管理 honeytokens。 </li>
<li> 启用网络名称解析 (NNR) 。 </li>
<li> "已删除对象"容器的配置。</li>
<li> 部署指南或教育：： </li>
<ul>
<li> 修正或解释各种警报类型和受监视的活动。  </li>
<li> 调查用户、计算机、横向移动路径或实体。 </li>
<li> 威胁或高级搜寻。 </li>
<li> 事件响应。 </li>
</ul>
<li> 为 Defender for Identity 提供安全警报实验室教程。 </li>
<li> 当 Defender for Identity 检测到可疑活动时，通过指定传感器向 syslog 服务器发送安全警报，从而提供通知。  </li>
<li> Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines. </li>
<li> 配置 VPN 解决方案以将信息从 VPN 连接添加到用户配置文件页面。  </li>
<li> SIEM 或 API 集成 (安全) 事件管理 (包括 Azure Sentinel) 。 </li>
</ul></td>
<td><ul>
<li> 与 <a href="/defender-for-identity/prerequisites"> Microsoft Defender 的标识先决条件保持一致</a>。 </li>
<li>  已部署 Active Directory。  </li>
<li>  打算安装 Defender for Identity 传感器的域控制器具有到 Defender for Identity 云服务的 Internet 连接。  </li>
<ul>
<li> 防火墙和代理必须处于打开状态，以与 Defender for Identity 云服务通信 (*.atp.azure.com 端口 443 必须) 。</li>
</ul>
<li> 在下列其中一个上运行的域控制器：</li>
<ul>
<li> WindowsServer 2008 R2 SP1。</li>
<li> Windows Server 2012。</li>
<li> Windows Server 2012R2。</li>
<li> Windows Server 2016。</li>
<li> Windows带 KB4487044 的服务器 2019 (操作系统版本 17763.316 或更高版本) 。</li>
</ul>
<li> Microsoft .NET Framework 4.7 或更高版本。</li>
<li> 至少需要五 (5) GB 的磁盘空间，建议使用 10 GB。</li>
<li> 域控制器 (2) 2 个内核，6 (6) GB 的 RAM。</li>
</ul></td>
</tr>

<tr class="odd">
<td><strong>Microsoft Defender for Office 365</strong></td>
<td>  Microsoft Defender for Office 365 可保护你的组织免受电子邮件、链接 (URL) 和协作工具带来的恶意威胁。Defender for Office 365 包括：<ul>
<li> <a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#configure-microsoft-defender-for-office-365-policies"> 威胁防护策略</a>：定义威胁防护策略，为组织设置适当级别的保护。</li>
<li> <a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#view-microsoft-defender-for-office-365-reports">报告</a>：查看实时报告以监视 Defender Office 365性能。</li>
<li> <a href="/microsoft-365/security/office-365-security/defender-for-office-365?view=o365-worldwide#use-threat-investigation-and-response-capabilities">威胁调查和响应功能</a>：使用前沿工具调查、理解、模拟和阻止威胁。</li>
<li> <a href="/microsoft-365/security/office-365-security/office-365-air?view=o365-worldwide">自动化调查和响应功能</a>：节省时间和精力来调查和缓解威胁。</li>
</ul>

我们提供针对：  
<ul>
<li>  启用安全链接、安全附件和防钓鱼。  </li>
<li>  配置自动化、调查和响应。  </li>
<li>  使用攻击模拟器。  </li>
<li>  报告和威胁分析。  </li>
<li>  了解事件门户中的Microsoft 365 Defender相关。</li>
</ul>
<p><strong>以下内容超出范围</strong></p>
<ul>
<li> 客户补救活动的项目管理。</li>
<li> 持续管理、威胁响应和修正。</li>
<li> 支持<a href=" /fasttrack/us-gov-appendix-overview">GCC-High美国政府GCC-DoD (Office 365或) 。 </a></li>
<li> 将 Defender for Office 365与其他安全产品/服务进行比较的讨论。</li>
<li> 部署 Defender for Office 365作为概念证明。</li>
<li> 连接自定义应用。</li>
<li> 有关高级搜寻的培训或指导。</li>
<li> 自动调查和修正，包括 Microsoft Power Automate手册。</li>
<li> SIEM 或 API 集成 (安全) 事件管理 (包括 Azure Sentinel) 。</li>
</ul>
</td>
<td>除常规 <strong>中的核心</strong> 载入 <a href="#general">部分外</a>，没有最低系统要求。</td>
</tr>


<tr class="even">
<td><strong>Microsoft 信息管控</strong></td>

<td>  我们提供针对：
<ul>
<li>  创建和发布保留标签和策略 (仅在 E5) 。  
</li>
<li>  记录管理 (E5 服务中) 。  </li>
<ul><li>  查看文件计划创建。 </li>
<li>  创建和管理记录 (包括基于事件的记录) 。  </li>
<li>  正在审查处置。 </ul> </li>
</ul>

<strong> 合规性管理器</strong>

我们提供针对：  

<ul> <li>查看角色类型。  </li>
<li> 添加和配置评估。</li>
<li> 通过实施改进操作来评估合规性并确定这对合规性分数的影响。</li>
<li> 查看内置控件映射和评估控件。</li>
<li> 在评估内生成报告。</li>
</ul>

  <strong>以下内容超出范围 </strong>  
<ul>
<li> 开发记录管理文件计划。</li>
<li> 数据连接器。</li>
<li> 开发 SharePoint。</li>
<li> 自定义脚本和编码。</li>
<li> 设计、架构师和第三方文档审阅。</li>
<li> 支持 E3。</li>
<li> 遵守行业和区域法规和要求。</li>
<li> 合规性管理器中评估的建议改进措施的动手实施。</li>
</ul>

</td>
<td>除常规 <strong>中的核心</strong> 载入 <a href="#general">部分外</a>，没有最低系统要求。</td>
</tr>
<tr class="odd">
<td><strong>Microsoft 信息保护</strong></td>
<td>  我们提供针对：
<ul>
<li>  E3 (E5 支持的数据) 。  </li>
<li>  E3 和 E5 (支持敏感信息) 。  </li>
<li>  创建敏感度标签 (E3 和 E5 支持) 。  </li>
<li>  在 E3 和 E5 (支持应用敏感度) 。  </li>
<li>  E5 (中支持的可训练分类) 。  </li>
<li>  使用内容资源管理器和活动资源管理器了解数据 (E5 服务支持) 。  </li>
<li>  使用策略发布标签 (E5)  (支持手动和自动) 。  </li>
<li>  为 E5 () 支持Windows 10设备创建终结点数据丢失 (DLP) 。  </li>
<li>  为聊天和Microsoft Teams创建 DLP 策略。  </li>
</ul>

<strong> 合规性管理器</strong>

我们提供针对：  

<ul> <li>查看角色类型。  </li>
<li> 添加和配置评估。</li>
<li> 通过实施改进操作来评估合规性并确定这对合规性分数的影响。</li>
<li> 查看内置控件映射和评估控件。</li>
<li> 在评估内生成报告。</li>
</ul>

<strong> Azure 信息保护</strong>

我们提供针对：  
<ul>
<li>  激活和配置租户。  </li>
<li>  创建和设置 P1 和 P2 (支持的标签和) 。  </li>
<li>  对 P1 和 P2 (支持的文档应用信息) 。  </li>
<li>  自动对 Office 应用中的信息进行分类和标记 (如在 Windows 上运行的 Word、PowerPoint、Excel 和 Outlook) ，以及使用 P2) 中支持的 Azure 信息保护客户端 (。  </li>
<li>  使用 Azure 信息保护扫描程序发现和标记处于 (P1 和 P2) 。  </li>
<li>  使用 Exchange Online 邮件流规则监视传输中的电子邮件。  </li>
</ul>

  如果你希望使用 Microsoft Azure Rights Management Services (Azure RMS) 、Office 365 邮件加密 (OME) 和数据丢失防护 (DLP) ，我们还会提供指导。

<strong>以下内容超出范围 </strong>  
<ul>
<li>客户密钥。</li>
<li>RegEx (正则表达式) 敏感信息类型的开发。</li>
<li>创建或修改关键字词典。</li>
<li>自定义脚本和编码。</li>
<li> Azure Azure Azure。</li>
<li> 设计、架构师和第三方文档审阅。</li>
<li> 遵守行业和区域法规和要求。</li>
<li> 合规性管理器中评估的建议改进措施的动手实施。</li>
</ul>

<ul>

</td>
<td>除常规 <strong>中的核心</strong> 载入 <a href="#general">部分外</a>，除 Azure 信息保护外，没有最低系统要求。

<strong>Azure 信息保护</strong>

客户先决条件职责包括：  
<ul>
<li>  要扫描的文件共享位置的列表。  </li>
<li>  批准的分类分类。 </li>
<li> 了解有关密钥管理的任何法规限制或要求。  </li>
<li>  为本地 Active Directory 创建的已与 Azure AD 同步的服务帐户。 </li>
<li>  为分类和保护配置的标签。 </li>
<li> Azure 信息保护扫描程序的所有先决条件已就位。 有关详细信息，请参阅安装和部署 Azure 信息保护统一标签扫描 <a href="/azure/information-protection/deploy-aip-scanner-prereqs">程序的先决条件</a>。 </li>
<li>  确保用户设备正在运行受支持的操作系统，并且已安装必要的必备组件。 有关详细信息，请参阅以下内容。</li>
<ul>
<li> <a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">管理指南：为用户安装 Azure 信息保护统一标记客户端</a>   </li>
<li>  <a href="/azure/information-protection/rms-client/mobile-app-faq">什么是适用于 iOS 或 Android 的 Azure 信息保护应用？</a>  </li>
</ul>
<li> 安装和配置 Azure RMS 连接器和服务器，包括 Active Directory RMS (AD RMS) 连接器，实现混合支持。  </li>
<li> 设置和配置"自带密钥 (BYOK) 、双密钥加密 (DKE)  (仅统一标记客户端) "或"仅保留你自己的密钥 (HYOK)  (经典客户端) "（如果部署需要这些选项之一）。  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  我们提供远程指南，指导你准备好使用 Intune 作为基于云的移动设备管理 (MDM) 以及适用于应用和设备的移动应用管理 (MAM) 提供程序。 具体步骤取决于你的源环境，并且基于你的移动设备和移动应用管理需求。 所包含的具体步骤如下：
<ul>
<li>  许可最终用户。  </li>
<li>  通过利用本地 Active Directory 或 Azure AD (云标识配置由 Intune) 。  </li>
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
<li>  通过 Web 链接或深层链接针对每个受支持的平台部署应用。  </li>
<li>  条件访问策略。  </li>
<li>  如果组织中已有证书颁发机构、无线网络或 VPN 基础结构，则部署电子邮件、无线网络和 VPN 配置文件。  </li>
<li>  连接到 Intune 数据仓库。  </li>
<li>  将 Intune 与以下内容进行集成：
<ul>
<li>  需要团队查看器订阅 (远程协助团队查看器) 。  </li>
<li>  移动威胁 (MTD) MTD (需要 MTD 订阅) 。  </li>
<li>  需要电信费用管理解决方案 (电信费用管理解决方案订阅) 。  </li>

</ul></li>
<li>  将每个受支持平台的设备注册到 Intune。  </li>
</ul></li>
</ul></li>
<li>  提供有关应用保护的指南：
<ul>
<li>  为每个受支持的平台配置应用保护策略。  </li>
<li>  为托管应用配置条件访问策略。  </li>
<li>  使用前面提到的 MAM 策略面向相应的用户组。  </li>
<li>  使用托管应用使用情况报告。  </li>
</ul></li>
<li>  提供从旧版电脑管理到 Intune MDM 的迁移指南。  </li>
</ul>
 
</li>
</ul>
  
<strong>云附加</strong>  

  我们将指导你准备好使用 Intune 云附加现有 Configuration Manager 环境。 具体步骤取决于源环境。 这些步骤包括：  
<ul>
<li>  许可最终用户。  </li>
<li>  通过利用本地 Active Directory 和云标识，配置供 Intune 使用的标识。  </li>
<li>  将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。  </li>
<li>  提供设置混合 Azure AD 加入的指南。  </li>
<li>  提供有关为 MDM 自动注册设置 Azure AD 的指南。  </li>
<li>  提供有关在将云管理网关用作基于远程 Internet 的设备管理共同管理的解决方案时如何设置云管理网关的指南。  </li>
<li>  配置要切换到 Intune 的受支持工作负载。  </li>
<li>  在 Intune 注册的设备中安装 Configuration Manager 客户端。  </li>
</ul> 

<strong>安全地Outlook适用于 iOS 和 Android 的移动设备</strong>我们可以提供指导，帮助你在组织中Outlook适用于 iOS 和 Android 的移动设备，以确保用户已安装所有必需的应用。  
  使用 Intune 安全地部署适用于 iOS Outlook Android 移动版的步骤取决于你的源环境。 它可以包括：
<ul>
<li>  通过 Apple Outlook 或 Google Play Microsoft Authenticator下载适用于 iOS Microsoft Authenticator 和 Intune 公司门户 应用的应用。  </li>
<li>  提供有关设置的指导：
<ul>
<li>  适用于 iOS Outlook Android、Microsoft Authenticator 和 Intune 公司门户 Intune 的应用部署。  </li>
<li>  应用保护策略。  </li>
<li>  条件访问策略。  </li>
<li>  应用配置策略。  </li>
</ul></li>
</ul>  
  </td>
<td>  在规划使用 Intune 部署无线网络和 VPN 配置文件时，IT 管理员需要具有已在生产环境中工作的现有证书颁发机构、无线网络和 VPN 基础结构。  
  <strong>注意</strong>：FastTrack权益不包括帮助为 Intune 设置或配置证书颁发机构、无线网络、VPN 基础结构或 Apple MDM 推送证书。  
 
  <strong>注意</strong>：FastTrack 服务权益不包括有关将配置管理器站点服务器或配置管理器客户端设置或升级到支持云附加所需的最低要求的帮助。 请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> 以寻求帮助。

  <strong>Intune 与 Microsoft Defender for Endpoint 集成</strong> 
 
  <strong>注意</strong>：我们协助将 Intune 与 Microsoft Defender for Endpoint 集成，并基于其风险级别Windows 10创建设备合规性策略。 我们不提供有关购买、许可或激活的帮助。 请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> 以寻求帮助。  
  
<strong>Windows Autopilot</strong> 
 
  IT 管理员负责通过让硬件供应商代表他们上载其硬件 ID 或自己将其上载到 Windows Autopilot 服务中来向其组织注册设备。  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a>Office 365

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>服务</th>
<th>FastTrack指南详细信息</th>
<th>源环境预期</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  对于 Exchange Online，我们会全程指导你，直到你的组织可以使用电子邮件为止。 具体步骤取决于源环境和电子邮件迁移计划。  
  我们提供针对：
<ul>
<li>  为 Office 365 中验证的所有启用邮件的域设置 Exchange Online Protection (EOP) 功能。  </li>
<li>  将邮件交换 (MX) 记录指向Office 365。  </li>
<li>  如果 Microsoft Defender 是订阅Office 365的一部分，则设置 Microsoft Defender for Office 365 功能。 有关详细信息，请参阅此表<strong>的 Microsoft Defender Office 365</strong>部分。  </li>
<li>  为在 Office 365 中验证的所有已启用邮件的域设置数据丢失防护 (DLP) 功能，将其作为订阅服务的一部分。这可在 MX 记录指向 Office 365 后完成。</li>
<li>  为在 Office 365 中验证的所有已启用邮件的域设置 Office 365 邮件加密 (OME) ，将其作为订阅服务的一部分。这可在 MX 记录指向 Office 365 后完成。</li>
</ul>
  <strong>注意：</strong>邮箱复制服务 (MRS) 尝试将信息权限托管 (IRM) 电子邮件从本地邮箱迁移到相应的 Exchange Online 邮箱。 可读取受保护内容迁移后的能力取决于客户映射和将 Active Directory Rights Managed Services (AD RMS) 模板复制到 Azure Rights Management Service (Azure RMS)。  
<ul>
<li>  配置防火墙端口。  </li>
<li>  根据需要设置 DNS，包括所需的自动发现、发件人策略框架 (SPF) 、域密钥识别邮件 (DKIM) 、基于域的邮件身份验证、报告和一致性 (DMARC) 和 MX 记录 () 。  </li>
<li>  设置源邮件环境和 Exchange Online 之间的电子邮件流（根据需要）。  </li>
<li>  执行从源邮件环境到 Office 365 的邮件迁移。  </li>
<li>  配置邮箱客户端（Outlook for Windows、Outlook 网页版以及 Outlook for iOS 和 Outlook for Android）。  </li>
</ul>
  <strong>数据迁移</strong>  <br>
有关使用数据FastTrack数据迁移的Office 365，请参阅数据<a href="/fasttrack/data-migration">迁移</a>。   
<td>  源环境必须具有以下最低级别之一：
<ul>
<li>  具有 Exchange Server 2003 前向的单个或多个 Exchange 组织。  </li>
<li>  一个支持 Internet 邮件访问协议 (IMAP) 的电子邮件环境。  </li>
<li>  单个 G 套件环境（仅限 Gmail、联系人和日历）。  </li>
<li>  有关多地理位置功能的信息，请参阅多地理位置功能<a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online。</a>  </li>
</ul>
Project for Office 365、Outlook for Windows、Outlook for iOS 和 Android、OneDrive for Business 同步客户端、Power BI Desktop 和 Skype for Business 等联机客户端软件必须处于最低级别，如 Microsoft 365 Office 的系统<a href="https://go.microsoft.com/fwlink/?LinkID=723597">要求中的定义</a>。  </td>
</tr>

<td><strong>Microsoft Defender for Office 365</strong></td>
<td>  有关详细信息，请参阅安全与Office 365中的 Microsoft <strong>Defender</strong> <a href="/fasttrack/products-and-capabilities#security-and-compliance">for Office 365。</a>  
</td>
<td></td>
</tr>


<tr class="even">
<td><strong>Microsoft 信息管控</strong></td>
<td>  有关详细信息，请参阅安全与 <strong> 合规中的 Microsoft</strong> <a href="/fasttrack/products-and-capabilities#security-and-compliance">信息治理</a>。 

</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Microsoft 信息保护</strong></td>
<td>  
有关详细信息，请参阅安全Microsoft 信息保护<strong></strong><a href="/fasttrack/products-and-capabilities#security-and-compliance">中的"安全与合规"。</a>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  我们提供针对：
<ul>
<li>  确认支持 Exchange Online、SharePoint Online、Office 365 组和 Azure AD 的最低Teams。  </li>
<li>  配置防火墙端口。  </li>
<li>  设置 DNS。  </li>
<li>  确认是否已在 Office 365 租户上启用 Teams。  </li>
<li>  启用或禁用用户许可证。  </li>
<li>  网络评估Teams：
<ul>
<li>  端口和终结点检查。  </li>
<li>  连接质量检查。  </li>
<li>  带宽预估。  </li>
</ul>
<ul>
<li>  配置 Teams 应用策略 (Teams Web 应用、Teams 桌面应用和 Teams for iOS 和 Android 应用) 。  </li>
</ul>
如果适用，我们还提供有关：
<ul>
<li>  Microsoft Teams会议室设备：  </li>
<ul>
<li>  创建 <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams 设备目录</a>中所列支持的电话和会议室设备所需的在线帐户。  </li>
<li>  通过经认证的设备进行服务器端配置的Microsoft Teams 会议室协助。  </li>
<li>  启用音频会议：  </li>
<ul>
<li>  会议桥默认设置的组织设置。  </li>
<li>  向许可用户分配会议桥。  </li>
</ul>
<li>  电话系统：
<ul>
<li>  组织设置云语音默认设置。  </li>
<li>  通话套餐指南 (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">可用市场</a>) ：
<ul>
<li>  向许可用户分配号码。  </li>
<li>  通过用户界面 (UI) 进行本地号码端口定位的指南（最多到 999）。  </li>
<li>  超过 999 的本地号码端口定位服务请求 (SR) 支持。  </li>
</ul></li>
<li>  直接路由指南：
<ul>
<li>  针对合作伙伴托管方案或客户部署方案的直接路由设计（最多 10 个站点）的组织设置指南。  </li>
<li> 会话边界控制器 (SBC) 配置检查。 </li>

<li> 拨号计划配置的远程协助。 </li>

<li> 语音路由配置。</li>

<li> 媒体旁路和本地媒体优化。 </li>

</ul></li>
</ul></li>
<li>  启用 Teams 实时事件。  </li>
<li>  组织设置和集成到 Microsoft Stream。  </li>
<li>  转换Skype for Business Teams指南。  </li>
</ul></td>
<td><ul>
<li>  在 Azure AD 中为用户启用Office 365。  </li>
<li>  对 SharePoint Online 启用的用户。  </li>
<li>  Exchange混合配置 (中联机和本地Exchange邮箱) 。  </li>
<li>  针对 Office 365 组启用。  </li>
</ul>
  <strong>注意：</strong>如果未为用户分配和启用 SharePoint Online 许可证，他们将不会在 OneDrive for Business 中Office 365。 文件共享继续在频道中工作，但如果没有在频道中存储OneDrive for Business用户Office 365。 Teams不支持SharePoint本地部署。  <br>
  <strong>注意：</strong>理想的状态是所有用户的邮箱都位于Exchange Online。 拥有托管在本地的邮箱的用户必须通过 Azure AD Office 365同步到 连接。 对于这些Exchange混合客户，如果用户的邮箱位于本地，则用户无法添加或配置连接器。  
  可以从 <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> 下载 Microsoft Teams Windows 和 Mac 桌面客户端的安装程序。  </td>
</tr>

<tr class="even">
<td><strong>iOS 和 Android 版 Outlook</strong></td>
<td>  我们提供针对：
<ul>
<li>  从 Apple App Store 和 Google Play 下载 Outlook for iOS 和 Outlook for Android。  </li>
<li>  配置帐户和访问 Exchange Online 邮箱。  </li>
<li>  保护Outlook移动设备 (请参阅在 Exchange Online 中保护<a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">适用于 iOS Outlook Android</a>) 。  </li>
</ul></td>
<td><ul>
<li>  在 Azure AD 中为用户启用Office 365。  </li>
<li>  配置了 Exchange Online 并分配了许可证。  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  我们提供针对：
<ul>
<li>  分配 Power BI 许可证。  </li>
<li>  部署 Power BI Desktop 应用。  </li>
</ul></td>
<td>联机客户端软件（如 Power BI Desktop）必须处于最低级别，如 Microsoft 365<a href="https://go.microsoft.com/fwlink/?LinkID=723597">和 Office 的系统要求中定义</a>。</td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  我们提供针对：
<ul>
<li>  验证 Project Online 依赖的基本 SharePoint 功能。  </li>
<li>  向你的租户添加 Project Online 服务（包括向用户添加订阅）。  </li>
<li>  设置企业资源池 (ERP)。  </li>
<li>  创建你的首个项目。  </li>
</ul></td>
<td>联机客户端软件（如 Project for Office 365）必须处于最低级别，如 Microsoft 365 和 Office 的系统<a href="https://go.microsoft.com/fwlink/?LinkID=723597">要求中的定义</a>。</td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional 和 高级版</strong></td>
<td>  我们提供针对：
<ul>
<li>  解决部署问题。  </li>
<li>  使用 Microsoft 365 管理中心和 Windows PowerShell 分配最终用户许可证。  </li>
<li>  使用即点即用从 Office 365 门户安装 Project Online 桌面客户端。  </li>
<li>  使用 Office 365 部署工具配置更新设置。  </li>
<li>  为 Project Online 桌面客户端 设置一个现场分发服务器，包括帮助创建 configuration.xml 文件以与 Office 365 部署工具一起使用。  </li>
<li>  将 Project Online 桌面客户端 连接到 Project Online Professional 或 Project Online 高级版。  </li>
</ul></td>
<td>联机客户端软件（如 Project for Office 365）必须处于最低级别，如 Microsoft 365 和 Office 的系统<a href="https://go.microsoft.com/fwlink/?LinkID=723597">要求中的定义</a>。</td>
</tr>
<tr class="even">
<td><strong>SharePoint Online 和 OneDrive for Business</strong></td>
<td>  我们提供针对：
<ul>
<li>  设置 DNS。  </li>
<li>  配置防火墙端口。  </li>
<li>  设置用户和许可证。  </li>
<li>为你的 SharePoint Online 管理员启用站点创建。</li>
<li>规划网站集。</li>
<li>保护内容安全和管理权限。</li>
<li>配置 SharePoint Online 功能。</li>
<li>  配置 SharePoint 混合功能，如混合搜索、混合网站、混合分类、内容类型、混合自助式网站创建（仅适用于 SharePoint Server 2013）、扩展的应用启动器、混合 OneDrive for Business 和 Extranet 网站。  </li>
<li>  迁移方法。  </li>
</ul>
根据你的 OneDrive for Business 版本，SharePoint其他指南，例如：
<ul>
<li>  确定集成选项并查看本地和联机网络基础结构和带宽。  </li>
<li>  安装 SharePoint Online 2013 SP1 (（如果适用) ，规划和实现同步和标识要求，并确定OneDrive for Business客户端。  </li>
<li>  规划和实现针对所有用户的单个推出 (或分阶段推出) 。  </li>
<li>  分配许可证、将"我的网站"和个人文档库重定向到适用于 SharePoint Online 2013) 的 Office 365 (，设置访问群体以控制对适用于 SharePoint Online 2013) 的 OneDrive (的访问。  </li>
<li>将已知文件夹重定向或移动到OneDrive。</li>
<li>  部署OneDrive for Business客户端同步。  </li>
</ul>
  <strong>数据迁移</strong>  <br>
有关使用数据迁移FastTrack数据迁移的Office 365，请参阅数据<a href="/fasttrack/data-migration">迁移</a>。
</ul></td>
<td><br><strong>对于SharePoint混合：</strong>  
<ul>
<li>  SharePoint配置包括配置混合搜索、网站、分类、内容类型、OneDrive for Business、扩展的应用启动器、Extranet 网站以及从本地连接到单个目标 SharePoint Online 环境的自助式网站创建。  </li>
</ul>
  <strong>注意：</strong>在 2013 年 10 月运行本地服务器时，自助式网站创建SharePoint范围内。  
<ul>
<li>  若要SharePoint混合，您必须具有以下本地 SharePoint 服务器环境之一：2013、2016 或 2019。  </li>
</ul>
  <strong>注意：</strong>未将本地SharePoint环境升级到 SharePoint Server。 请联系 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a> 寻求帮助。 有关详细信息，请参阅混合<a href="https://go.microsoft.com/fwlink/?linkid=853548">功能的最低公共SharePoint级别</a><em>。</em>  <br>
  <strong>注意：</strong>有关多地理位置功能的信息，请参阅 OneDrive 和 SharePoint Online 中的多<a href="https://go.microsoft.com/fwlink/?linkid=831056">地理位置Office 365。</a><em></em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer 企业版</strong></td>
<td>
我们提供有关启用 Yammer Enterprise 服务的远程指导。  
</td>
<td>联机客户端软件必须处于最低级别，如 system <a href="https://go.microsoft.com/fwlink/?LinkID=723597">requirements for Microsoft 365 and Office .</a></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>企业移动性 + 安全性 

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>服务</th>
<th>FastTrack指南详细信息</th>
<th>源环境预期</th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) 和 Azure AD Premium</strong></td>
<td>  有关详细信息，请参阅安全与Azure Active Directory (<strong>中的 azure AD) 和 Azure AD Premium。</strong> <a href="/fasttrack/products-and-capabilities#security-and-compliance"></a></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Azure 信息保护 </strong></td>
<td>  有关 Azure 信息保护详细信息<strong>，请参阅Microsoft 信息保护</strong><a href="/fasttrack/products-and-capabilities#security-and-compliance">和合规性中的指南</a>。  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  有关详细信息，<strong>请参阅安全Microsoft Intune</strong><a href="/fasttrack/products-and-capabilities#security-and-compliance">中的"安全与合规"。</a>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>服务</th>
<th>FastTrack指南详细信息</th>
<th>源环境预期</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  我们提供有关从 Windows 7 专业版 Windows 8.1 Professional 升级到 Windows 10 企业版 的指南。  
  我们提供针对：
<ul>
<li>  了解Windows 10意图。  </li>
<li>  评估源环境和要求 (确保Microsoft Endpoint Configuration Manager升级到所需级别，以支持Windows 10部署) 。  </li>
<li>  使用 Windows 10 企业版 或 Microsoft 365 应用版 部署Microsoft Endpoint Configuration Manager和Microsoft 365。  </li>
<li>  建议你评估你的应用Windows 10选项。  </li>
<li>  通过创建桌面分析部署计划，支持使用桌面分析和指导。  </li>
<li>  Microsoft 365 应用版 Configuration Manager 中的 Office 365 准备情况仪表板或独立的准备情况 Toolkit for Office，以及帮助部署 Microsoft 365 应用版，从而Office兼容性评估。  </li>
<li>  创建修正清单，检查需要执行哪些操作，使源环境达到成功部署的最低要求。  </li>
<li>  为现有设备提供升级指南，Windows 10 企业版满足所需设备硬件要求时进行升级。  </li>
<li>  提供升级指南以支持现有部署运动。 FastTrack 推荐并提供有关就地升级到 Windows 10 的指南。 指南还可用于 Windows 干净图片安装和 Windows Autopilot 部署方案。  </li>
<li>  在Microsoft 365 应用版部署中，使用 Configuration Manager 部署Windows 10部署。   </li>
<li>  提供指导，帮助你的组织使用现有的 Configuration Manager Windows 10 企业版Microsoft 365 应用版保持最新状态Microsoft 365。  </li> 
</ul>
  
<strong>以下内容超出范围 </strong>  
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
请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。  </td>
<td>  要升级电脑，必须满足以下要求：
<ul>
<li>  源操作系统：Windows 7 企业版、Professional、Windows 8.1 企业版或Professional。  </li>
<li>  设备：台式机、笔记本或平板电脑外形。  </li>
<li>  目标操作系统：窗口 10 Enterprise。  </li>
</ul>
若要升级基础结构，必须满足以下要求：
<ul>
<li>  Microsoft Endpoint Configuration Manager。  </li>
<li>  配置管理器版本必须受目标Windows 10支持。 有关详细信息，请参阅 <a href="/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager 中的 Windows 10 支持</a>中的 Configuration Manager 支持表格。  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender for Endpoint</strong></td>
<td>  有关详细信息，请参阅安全与合规中的<strong>Microsoft Defender for Endpoint。</strong> <a href="/fasttrack/products-and-capabilities#security-and-compliance"></a></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Windows 虚拟桌面

<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>服务</th>
<th>FastTrack指南详细信息</th>
<th>源环境预期</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 虚拟桌面</strong></td>
<td><p>我们提供部署到虚拟桌面的部署指南Windows桌面 (桌面应用虚拟化服务) 。 Windows虚拟桌面利用Windows 10会话体验，并针对Microsoft 365 应用版Enterprise安全性和管理进行Microsoft 365。</p>
<p>我们提供针对：</p>
<ul>
<li>使用Windows 10 企业版部署Microsoft 365 应用版会话Enterprise部署多个会话：
<ul>
<li>Azure Marketplace 映像。</li>
<li>共享图像。</li>
<li>Office部署Toolkit (ODT) 。</li>
</ul></li>
<li>为Microsoft 365 应用版虚拟桌面中的 FSLogix 配置Windows。 对于 FSLogix：
<ul>
<li>部署代理。</li>
<li>配置配置文件和Office容器。</li>
<li>为用户配置内容排除和Microsoft 365 应用版。</li>
</ul></li>
<li>部署Microsoft Edge。</li>
<li>通过Microsoft Teams部署服务器。</li>
</ul>

<strong>以下内容超出范围</strong>
<ul>
<li>Project虚拟桌面基础结构部署Windows管理。</li>
<li>第三方应用虚拟化和部署。</li>
<li>为虚拟桌面Windows映像。</li>
<li>涉及 VMware 和 Citrix 的迁移和方案。</li>
<li>Linux 方案。</li>
<li>用户配置文件的转换或迁移。</li>
<li>Microsoft Endpoint Configuration Manager虚拟Microsoft Endpoint Manager桌面Windows配置 (包括修补和管理) 。 </li>
<li>Microsoft 365 Defender多Windows 10会话。</li>
</ul>
请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。</td>
<td>你应该已经拥有以下内容：
<ul>
<li><a href="/azure/virtual-desktop/overview#requirements">Windows虚拟桌面许可要求</a>。</li>
<li> 支持<a href="/azure/virtual-desktop/overview">Virtual Deskstop Windows基础结构</a>。 </li>
<ul>
<li><a href="/azure/virtual-desktop/store-fslogix-profile">存储 Virtual Deskstop 中的 FSLogix Windows容器。</a> </li>
</ul>
<li>Azure 网络：
<ul>
<li>使用 VNET (虚拟网络) 创建和子网。</li>
<li>防火墙和网络安全组。</li>
<li>VPN 和 ExpressRoute。</li>
<li>从本地路由到 Azure。</li>
<li>允许连接到虚拟桌面Windows防火墙规则。
</ul>
有关详细信息，请参阅支持的 <a href="/azure/virtual-desktop/overview#supported-remote-desktop-clients">远程桌面客户端</a>。
</ul>
<ul><li>Azure AD 常规设置：
<ul>
<li>标识 <i> 策略 (只能使用以下三个选项之一) ：</i>
<ul>
<li>Azure 中具有 Azure AD 连接 Active Directory。</li>
<li>通过 VPN 或 ExpressRoute 在本地连接 Azure AD 的 Active Directory。</li>
<li>Active Directory 域服务 (AD DS) 。</li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a>应用保证


<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>服务</th>
<th>FastTrack指南详细信息</th>
<th>源环境预期</th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>应用保证</strong></td>
<td>  应用保证是一项旨在解决应用兼容性Windows Microsoft 365 应用版的服务。 当你请求应用保证服务时，我们会与你在符合条件的订阅中一起解决有效的应用问题，无需额外付费。 我们还为在部署 Windows 365 云电脑、Windows 虚拟桌面和 Microsoft Edge 时面临兼容性问题的客户提供指导Microsoft Edge并尽一切努力解决兼容性问题。 我们为以下 Microsoft 产品上部署的应用提供修正帮助：
<ul>
<li>  <strong>Windows 10</strong> <strong>11 Windows 11</strong> (包括 ARM64 设备) 。</li>
<li> <strong>Microsoft 365 应用版</strong>。  </li>
<li>  <strong>Microsoft Edge -</strong>有关部署指南，请参阅<a href="/DeployEdge/microsoft-edge-channels">部署Microsoft Edge概述</a>。  </li>
<li>  <strong>Windows虚拟桌面</strong> -有关详细信息，请参阅什么是虚拟<a href="/azure/virtual-desktop/overview">Windows？</a>和Windows 10 企业版<a href="/azure/virtual-desktop/windows-10-multisession-faq">会话常见问题解答</a>。  </li>
<li> <strong>Windows 365</strong>云电脑 – 有关详细信息，请参阅引入混合个人计算的新纪元<a href="https://www.microsoft.com/microsoft-365/blog/2021/07/14/introducing-a-new-era-of-hybrid-personal-computing-the-windows-365-cloud-pc/">：Windows 365 云电脑</a>。 </li>
</ul>

<strong>以下内容超出范围 </strong>  
<ul>
<li>  应用清单和测试，以确定哪些功能在应用和Windows Microsoft 365 应用版。 有关此过程的更多指导，请访问<a href="https://go.microsoft.com/fwlink/?linkid=2080140">桌面部署中心</a>。 如果对深入升级就绪性评估感兴趣，请填写<a href="https://go.microsoft.com/fwlink/?linkid=2053818">新式桌面评估的客户请求</a>表单。</li>
<li>  研究第三方 ISV 应用，Windows兼容性和支持声明。 有关详细信息，请参阅<a href="/sccm/desktop-analytics/overview">桌面分析</a>。</li>
<li>仅限应用打包的服务。 但是，应用保证团队会打包我们已针对 Windows修正的应用，以确保它们可以部署到客户环境中。</li>
</ul>

<strong>客户职责包括</strong>  
<ul>
<li>  创建应用清单。</li>
<li>  在 Windows 和 Microsoft 365 应用版 上验证这些Microsoft 365 应用版。</li>
</ul>
<strong>注意：</strong>  Microsoft 无法对源代码进行更改。 但是，如果可提供应用的源代码，则应用保证团队可向应用开发人员提供指导。 


  请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。  </td>

</td>
<td><strong>Windows 和 Microsoft 365 应用版</strong>
<ul>
<li>  
  使用 Windows 7、Windows 8.1 和 Windows 10 的应用也可在 Windows 10 11 Windows工作。  
  </li>
<li> 在 Office 2010、Office 2013、Office 2016 和 Office 2019 上运行的应用也Microsoft 365 应用版。</li>
</ul>
<strong>Windows 365 云电脑</strong>
<ul>
<li> 使用 Windows 7、Windows 8.1 和 Windows 10 的应用也可在 Windows 365 云电脑上运行。</li>
</ul>
<strong>Windows ARM</strong>
<ul>
<li>  
使用 Windows 7、Windows 8.1 和 Windows 10 的应用也可在 ARM64 Windows 10 Windows 11 上运行。 
  </li>
</ul>
  <strong>注意：</strong> 
<ul>
<li> x64 (64 位) 预览版，适用于参与预览体验计划Windows<a href="https://insider.windows.com/">客户</a>。  </li>
<li>  
 对于使用 Windows 10 2004 (或更高版本) 的非 Windows 预览体验成员客户，ARM64 Photoshop 支持使用 OpenCL 和<a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL</a>兼容包。 
  </li>
<li>  
  预览体验Windows计划的客户可以下载预览体验成员版本的 OpenCL 和 OpenGL 兼容包，以与其他应用一同使用。    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  如果你的 Web 应用或网站在 Internet Explorer 11、受支持的 Google Chrome 版本或任何 Microsoft Edge 版本上工作，它们也将与 Microsoft Edge 一Microsoft Edge。  
  </li>
<li>  
  随着 Web 的不断发展，请务必查看此已发布的已知网站兼容性影响更改列表，以<a href="/microsoft-edge/web-platform/site-impacting-changes">Microsoft Edge。</a>  
  </li>
</ul>
  <strong>Windows虚拟桌面</strong>  
<ul>
<li>  
  在 Windows 7、Windows 8.1、Windows 10 或 Windows Server (上运行) 虚拟化应用也运行在： </li>
<ul>
<li>  
  Windows 10 企业版 11 Windows 和 Enterprise。
  </li>
<li>  
  Windows 10 企业版和 Windows 11 Enterprise多会话。
  </li>
</ul>
</ul>
  <strong>注意：Windows Enterprise</strong>会话兼容性排除和限制包括：
<ul>
<li>  
  硬件重定向受到限制。  
  </li>
<li>  
  A/V 密集型应用可能功能受限。  
  </li>
<li>  
  64 位 Windows 虚拟桌面不支持 16 位应用。  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a>Microsoft Edge


<table>
<colgroup>
<col span="1" style="width: 15%;">
<col span="1" style="width: 45%;">
<col span="1" style="width: 40%;">
</colgroup>
<thead>
<tr class="header">
<th>服务</th>
<th>FastTrack指南详细信息</th>
<th>源环境预期</th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Microsoft Edge</strong> </td>
<td>
我们提供远程部署和采用指南以及兼容性协助，用于： <ul> <li>使用 Microsoft Edge 或 Intune Windows 10 Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager 部署) 。  </li>
<li>  使用Microsoft Edge (或 Intune 应用配置以及应用策略配置) 。  </li>
<li>  清点可能需要在活动模式中使用Internet Explorer列表。  </li>
<li>  使用Internet Explorer站点列表启用Enterprise模式。  (有关详细信息，<a href="/fasttrack/process-and-expectations#engaging-fasttrack">请参阅使用</a>FastTrack。 此外，如果你有一个与 Internet Explorer 或 Google Chrome 一起工作的 Web 应用或网站，并且你遇到兼容性问题，我们会提供指导来解决问题，无需额外付费。 若要请求应用保证的兼容性支持，请登录到<a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack 门户</a>以启动服务活动。  </li>
<li> 适用于应用书签的边缘采用和配置Microsoft 搜索指南。</li>
</ul>

<strong>以下内容超出范围 </strong>  
<ul>
<li>客户的 Microsoft Edge 部署的项目管理。</li>
<li>  现场支持。</li>

</td>
<td></td>
</tr>
</tbody>
</table>
