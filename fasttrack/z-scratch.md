---
title: 安全性和合规性
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: O365-seccomp
localization_priority: None
ms.collection: FastTrack
description: 适用于 Microsoft 服务的 FastTrack 指南详细信息。
ms.openlocfilehash: 000a81c51729deba8d3f5c4d88a0baa918dcd048
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996235"
---
# <a name="security-and-compliance"></a>安全性和合规性

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
<td><strong>Microsoft 365 Defender</strong></td>

<td> <p> Microsoft 365 Defender 是一个统一的攻破前和入侵后企业防御套件，在本机协调跨终结点、标识、电子邮件和应用进行检测、预防、调查和响应，以提供针对复杂攻击的集成保护。 我们提供针对： </p> 
<ul>
<li>  提供 Microsoft 365 安全中心概述。  </li>
<li>  查看跨产品事件，包括通过确保完整的攻击范围、受影响的资产和分组在一起的自动修正操作，重点关注关键方面。  </li>
<li>  演示 Microsoft 365 Defender 如何协调对资产、用户、设备和邮箱的调查，这些资产、用户、设备和邮箱可能由于自动自我修复而受到威胁。 </li>
<li>  解释并提供客户如何主动搜寻跨多个数据集影响您的电子邮件、数据、设备和帐户的入侵尝试和入侵活动的示例。   </li>
<li> 向客户展示他们如何使用 Microsoft 安全分数全面查看和改进安全状况。</li>
</ul>
<p><strong>以下内容超出范围</strong></p>
<ul>
<li> 客户补救活动的项目管理。 </li>
<li> 持续管理、威胁响应和修正。 </li>
<li> 部署指南或教育：：
<ul>
<li> 如何修正或解释各种警报类型和监视的活动。 </li>
<li> 如何调查用户、计算机、横向移动路径或实体。 </li>
<li> 自定义威胁搜寻。  </li>
</ul>
</li>
<li> SIEM 或 API (安全) 事件管理。</li>
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security 是一款云访问安全代理 (CASB) ，可提供丰富的可见性、控制数据传输和复杂分析，以识别和防御所有 Microsoft 和第三方云服务中的网络威胁。 我们提供针对：
<ul>
<li>  配置门户，包括：  </li>
<ul>
<li> 导入用户组。</li>
<li> 管理管理员访问权限和设置。  </li>
<li> 将部署范围确定为选择要监视或排除在监控范围中的某些用户组。</li>
<li> 设置 IP 范围和标记。</li>
<li> 使用徽标和自定义消息来个性化最终用户体验。</li>
</ul>
<li> 设置云发现以提供卷影 IT，使用：</li>
<ul>
<li> 适用于终结点的 Microsoft Defender。</li>
<li> Zscaler。</li>
<li> iboss。</li>
</ul>
<li> 使用 <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-gove">应用连接器</a> 连接特色应用。</li>
<li> 在条件访问和云应用安全门户中设置条件访问应用控制，以应用实时会话控件。</li>
<li> 部署 Cloud App Security 和 Cloud Discovery 仪表板。</li>
<li> 根据组织优先级自定义应用风险评分。</li>
<li> 创建应用标记和类别。</li>
<li> 批准和取消批准应用。</li>
<li> 使用活动和文件日志。</li>
<li> 管理 OAuth 应用。</li>
<li> 了解 Microsoft 365 Defender 门户中的事件关联。</li>
<li> 为 CASB 的 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> 大用例提供配置帮助 (包括创建或更新多达 6 (6) 策略，) 除外： </li>
<ul>
<li> 审核将 Internet 作为服务配置 (IaaS) 环境 (#18) 。</li>
<li> 监视用户活动，以抵御 IaaS 环境中 (#19) 。</li>
</ul>
</ul>
<p><strong>以下内容超出范围</strong></p>
<ul>
<li> 客户补救活动的项目管理。</li>
<li> 持续管理、威胁响应和修正。 </li>
<li> 使用 Docker 或日志收集器为连续报告设置自动日志上载的基础结构、安装或部署。 有关详细信息 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">，请参阅 CASB 的前 20</a> 个用例。</li>
<li> 创建云发现快照报告。</li>
<li> 使用阻止脚本阻止应用使用。</li>
<li> 连接自定义应用。</li>
<li> 与第三方标识提供程序 (DLP) 提供程序的 ISP (数据丢失) 集成。</li>
<li> 有关高级搜寻的培训或指导。</li>
<li> 自动调查和修正，包括 Microsoft Power Automate 手册。</li>
<li> SIEM 或 API 集成 (安全) 事件管理 (包括 Azure Sentinel) 。</li>
<li> 部署 Cloud App Security 作为概念证明。</li>
</ul></td>
</tr>



<tr class="odd">
<td><strong>Microsoft Defender 高级威胁防护 (ATP)</strong></td>
<td>  Microsoft Defender 高级威胁防护 (ATP) 是旨在帮助企业网络预防、检测、调查和响应高级威胁的平台。  
  我们提供针对：
<ul>
<li>  部署技术以确保终结点安全。  </li>
<li>  配置终结点保护和设备限制配置文件。  </li>
<li>  评估操作系统版本和设备管理 (包括 Intune、Microsoft Endpoint Configuration Manager、组策略对象 (GPO) 和第三方配置) 以及 Windows Defender AV 服务或其他终结点安全软件的状态。  </li>
<li>  评估 Windows AV 服务或其他终结点安全软件的状态。  </li>
<li>  评估限制网络流量的代理和防火墙。  </li>
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
<li>  查看模拟和教程 (如实践方案、虚假恶意软件和自动调查) 。  </li>
<li>  报告和威胁分析功能的概述。  </li>
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
  Windows Server Semi-Annual Channel (SAC) 版本 1803。  
  </li>
<li>  
  macOS 版本 10.13、10.14 和 10.15。  
  </li>
</ul>
</li>
</ul>
<strong>注意：</strong> 所有 Windows Server 版本都必须由最新版本的 System Center Configuration Manager 2012 (版本 1012 R2、1511 或 1602) 或 Microsoft Endpoint Configuration Manager (版本 2002 或) 管理。 

</li>
</ul>

<strong>以下内容超出范围 </strong>  
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
  Android 和 iOS (移动设备) 。  
  </li>
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
  手动基于 Intune 的部署。  
  </li>
<li>  
  基于 JAMF 的部署。
  </li>
<li>  
  MDM 的其他移动设备 () 基于产品的部署。  
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
<li>  查看 SIEM 连接中的 API 或安全信息 (或) 培训。  </li>
<li>  注册或配置 Microsoft 威胁防护 (MTP)。  </li>
<li>  有关高级搜寻的培训或指导。  </li>
<li>  有关使用或创建 Kusto 查询的培训或指南。</li>
</li>
</ul>
请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Microsoft Defender for Identity </strong></td>
<td>  Microsoft Defender for Identity 是一种基于云的安全解决方案，可利用本地 Active Directory 信号来识别、检测和调查针对组织的高级威胁、已遭入侵标识和恶意内部行为。 我们提供针对：
<ul>
<li>   创建适用于标识的 Defender 实例。 </li>
<li>   将 Defender for Identity 连接到 Active Directory。 </li>
<li>   评估你的环境在域控制器上部署 Defender for Identity 传感器的准备情况，包括：</li>   
<ul> 
<li>  运行大小工具进行资源容量规划。 </li>
<li>  运行审核工具来评估域控制器与传感器的兼容性。 </li>
</ul>
<li>  部署传感器以直接从域控制器捕获和分析网络流量和 Windows 事件，包括： </li>
<ul> 
<li>  下载传感器程序包。 </li>
<li>  配置传感器。 </li>
<li>  以静默方式在域控制器上安装传感器。 </li>
<li>  将传感器部署到多林环境。 </li>
</ul>
<li>  不需要将 Defender for Identity 与 Microsoft Cloud App Security (Cloud App Security 许可集成) 。 </li>
<li>  提供有关： 的部署指南、配置帮助和教育： </li>
<ul>
<li> 调整环境以减少"噪音"。  </li>
<li>  了解身份安全状态评估报告。 </li>
<li>  了解用户调查优先级分数和用户调查排名报告。 </li>
<li> 了解非活动用户报告。  </li>
<li> 在遭到入侵的帐户上提供修正选项。  </li>
</ul>
<li>  推动从高级威胁分析 (ATA) 到 Defender for Identity。 </li>
</ul>
<p><strong>以下内容超出范围</strong></p>
<ul>

<li> 客户补救活动的项目管理。 </li>
<li> 持续管理、威胁响应和修正。  </li>
<li> 部署 Defender for Identity 传感器，包括： </li>
<ul>
<li> 手动容量规划。 </li>
<li> 以独立容量部署传感器。 </li>
<li> 使用网络接口卡部署传感器 (NIC) 适配器。 </li>
<li> 通过第三方工具部署传感器。 </li>
<li> 通过 Web 代理连接连接到 Defender for Identity 云服务。 </li>
</ul>
<li> 创建和管理 honeytokens。 </li>
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
<li> 部署 Defender for Identity 传感器作为概念证明。</li>
</ul></td>
<td><ul>
<li>  已部署 Active Directory。  </li>
<li>  打算安装 Defender for Identity 传感器的域控制器具有到 Defender for Identity 云服务的 Internet 连接。  </li>
<ul>
<li> 防火墙和代理必须处于打开状态，以与 Defender for Identity 云服务通信 (*.atp.azure.com 端口 443 必须) 。</li>
</ul>
<li> 在下列其中一个上运行的域控制器：</li>
<ul>
<li> Windows Server 2008 R2 SP1。</li>
<li> Windows Server 2012。</li>
<li> Windows Server 2012 R2。</li>
<li> Windows Server 2016。</li>
<li> Windows Server 2019 和 KB4487044 (操作系统版本 17763.316) 。</li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><strong>Microsoft 信息管控</strong></td>
<td>  我们提供针对：
<ul>
<li>  保留标签和策略。  </li>
<li>  记录管理。  </li>
<li>  删除策略。  </li>
<li>  通信合规性。  </li>
<li>  内部风险管理。  </li>
<li>  高级电子数据展示。  </li>
</ul>

  <strong>以下内容超出范围 </strong>  
<ul>
<li> 开发记录管理文件计划。</li>
<li> 数据连接器。</li>
<li> 信息屏障。</li>
<li> 特权访问管理。</li>
<li> 在 SharePoint 中开发信息体系结构。</li>
<li> 自定义脚本和编码。</li>
</td>
<td>除常规 <strong>中的核心</strong> 载入 <a href="products-and-capabilities.md#general">部分外</a>，没有最低系统要求。</td>
</tr>
<tr class="odd">
<td><strong>Microsoft 信息保护</strong></td>
<td>  我们提供针对：
<ul>
<li>  数据分类。  </li>
<li>  敏感信息类型。  </li>
<li>  创建敏感度标签。  </li>
<li>  应用敏感度标签。  </li>
<li>  统一标记。  </li>
<li>  可训练的分类器。  </li>
<li>  通过内容浏览器和活动浏览器了解你的数据。  </li>
<li>  使用策略来发布标签（手动和自动）。  </li>
<li>  创建针对 Microsoft Teams 聊天和频道的数据丢失防护 (DLP) 策略。  </li>
<li>  为 Windows 10 设备创建终结点 DLP 策略。  </li>
</ul>

<strong>以下内容超出范围 </strong>  
<ul>
<li>客户密钥。</li>
<li>RegEx (正则表达式) 敏感信息类型的开发。</li>
<li>创建或修改关键字词典。</li>
<li>自定义脚本和编码。</li>
</ul>
<strong>注意：</strong>有关详细信息，请参阅<strong>Azure Information Protection</strong> in Enterprise <a href="products-and-capabilities.md#enterprise-mobility--security">Mobility + Security。</a>
<ul>

</td>
<td>除常规 <strong>中的核心</strong> 载入 <a href="products-and-capabilities.md#general">部分外</a>，没有最低系统要求。</td>
</tr>

<tr class="odd">
<td><strong>Office 365 高级威胁防护 (ATP)</strong></td>
<td>  我们提供针对：
<ul>
<li>  启用安全链接、安全附件和防钓鱼。  </li>
<li>  配置自动化、调查和响应。  </li>
<li>  使用攻击模拟器。  </li>
<li>  报告和威胁分析。  </li>
</ul></td>
<td>除常规 <strong>中的核心</strong> 载入 <a href="products-and-capabilities.md#general">部分外</a>，没有最低系统要求。</td>
</tr>


<tr class="odd">
<td><strong>发现&响应</strong></td>
<td>  

<strong>高级电子数据展示</strong>
  
<ul>
<li>  启用安全链接、安全附件和防钓鱼。  </li>
<li>  配置自动化、调查和响应。  </li>
<li>  使用攻击模拟器。  </li>
<li>  报告和威胁分析。  </li>
</ul>

<strong>仅在 E5</strong> (支持高级审核) 

我们提供针对： 
<ul>
<li> 启用高级审核。</li>
<li> 使用 UI 和审核日志审核 PowerShell 命令执行搜索。</li>
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
<td>除常规 <strong>中的核心</strong> 载入 <a href="products-and-capabilities.md#general">部分外</a>，没有最低系统要求。</td>
</tr>
<tr class="odd">
<td><strong>预览体验成员威胁管理</strong></td>

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
<li> 创建和管理 Power Automate 流。</li>
<li> 数据连接器 (HR 连接器) 。 </li>
<li> 使用 RegEx (配置的) 正则表达式。</li>
<li> 设计、架构师和第三方文档审阅。</li>
<li> 信息屏障。</li>
<li> 特权访问管理。</li>
<li> 遵守行业和区域法规和要求。</li>
<li> 合规性管理器中评估的建议改进措施的动手实施。</li>
</ul></td>
<td>除常规 <strong>中的核心</strong> 载入 <a href="products-and-capabilities.md#general">部分外</a>，没有最低系统要求。</td>
</tr>


</tbody>
</table>












</tbody>
</table>


<table>
<thead>
<TABLE  CELLPADDING="2" CELLSPACING="2" WIDTH="100%">
<tr class="header">
<TD width 15%><strong>服务</strong></TD>
<TD width 50%><strong>FastTrack 指南详细信息</strong></TD>
<TD width 25%><strong>源环境预期</strong></TD>
<TR>
</thead>
<tbody>


</tr>
</tbody>
</table>