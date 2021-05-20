---
title: 产品和功能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 5/19/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: 本主题包含有关 FastTrack 支持的工作负荷方案的详细信息，以及开始之前所需的源环境预期。 根据您的当前设置，我们将与用户一起制定修正计划，使源环境达到成功载入的最低要求。
ms.openlocfilehash: f3d10392b3d5f5712ae2b40c0af36a4ddc953682
ms.sourcegitcommit: 48c1a68ecf668b849037beb05b5490c6b922e833
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/19/2021
ms.locfileid: "52570550"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="41ef8-104">产品和功能</span><span class="sxs-lookup"><span data-stu-id="41ef8-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="41ef8-105">FastTrack 支持的服务和方案</span><span class="sxs-lookup"><span data-stu-id="41ef8-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="41ef8-106">本主题包含有关 FastTrack 支持的工作负荷方案的详细信息，以及开始之前所需的源环境预期。</span><span class="sxs-lookup"><span data-stu-id="41ef8-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="41ef8-107">根据您的当前设置，我们将与用户一起制定修正计划，使源环境达到成功载入的最低要求。</span><span class="sxs-lookup"><span data-stu-id="41ef8-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="41ef8-108">FastTrack 提供指导，帮助你首先获得所有 (通用的核心功能，Microsoft Online Services) 载入每个符合条件的服务：</span><span class="sxs-lookup"><span data-stu-id="41ef8-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="41ef8-109">常规</span><span class="sxs-lookup"><span data-stu-id="41ef8-109">General</span></span>](#general)
  - [<span data-ttu-id="41ef8-110">安全性和符合性</span><span class="sxs-lookup"><span data-stu-id="41ef8-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="41ef8-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="41ef8-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="41ef8-112">企业移动性 + 安全性</span><span class="sxs-lookup"><span data-stu-id="41ef8-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="41ef8-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="41ef8-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="41ef8-114">Windows 虚拟桌面</span><span class="sxs-lookup"><span data-stu-id="41ef8-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="41ef8-115">应用保证</span><span class="sxs-lookup"><span data-stu-id="41ef8-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="41ef8-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="41ef8-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="41ef8-117">若要了解 Office 365 US Government 的源环境预期，请参阅 [Office 365 US Government 的源环境预期](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)。</span><span class="sxs-lookup"><span data-stu-id="41ef8-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="41ef8-118">常规</span><span class="sxs-lookup"><span data-stu-id="41ef8-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="41ef8-119"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="41ef8-120"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="41ef8-121"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="41ef8-122"><strong>核心入门</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-123">我们提供有关核心载入的远程指导，其中包括服务预配、租户和标识集成。</span><span class="sxs-lookup"><span data-stu-id="41ef8-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="41ef8-124">它还包括为载入服务（如 Exchange Online、SharePoint Online 和 Microsoft Teams）提供基础的步骤，包括有关安全性、网络连接和合规性<a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">的讨论</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="41ef8-125">在核心载入完成后，便可以开始载入一个或多个符合条件的服务。</span><span class="sxs-lookup"><span data-stu-id="41ef8-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="41ef8-126"></li>
</ul>  

<strong> 标识集成 </strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="41ef8-127">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="41ef8-128">准备本地 Active Directory 标识以同步到 Azure Active Directory (Azure AD) 包括安装和配置 Azure AD 连接 (单林或多林) 以及许可 (包括基于组的许可) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="41ef8-129">创建云标识，包括批量导入和许可，包括使用基于组的许可。</span><span class="sxs-lookup"><span data-stu-id="41ef8-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="41ef8-130">为云旅程选择和启用正确的身份验证方法、密码哈希同步、传递身份验证或 Active Directory 联合身份验证服务 (AD FS) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li> <span data-ttu-id="41ef8-131">通过 Fast Identity Online (Fast Identity Online (FIDO) 2 或 Microsoft Authenticator App) 选择和启用更方便的身份验证体验。</span><span class="sxs-lookup"><span data-stu-id="41ef8-131">Choosing and enabling a more convenient authentication experience for your users with passwordless authentication (Fast Identity Online (FIDO)2 or Microsoft Authenticator App).</span></span></li>
<li><span data-ttu-id="41ef8-132">为具有单个 Active Directory 林和标识与 Azure AD 连接工具同步的客户启用 AD FS。</span><span class="sxs-lookup"><span data-stu-id="41ef8-132">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="41ef8-133">这需要Windows Server 2012 R2 Active Directory 联合身份验证服务 2.0 或更大。</span><span class="sxs-lookup"><span data-stu-id="41ef8-133">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="41ef8-134">使用密码哈希同步或传递身份验证将身份验证从 AD FS 迁移到 Azure AD。</span><span class="sxs-lookup"><span data-stu-id="41ef8-134">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="41ef8-135">将预集成应用 (如 Azure AD 库软件即服务 (SaaS) 应用) 从 AD FS 迁移到 Azure AD，实现单一登录 (SSO) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-135">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="41ef8-136">从 Azure AD 库启用 SaaS 应用与 SSO 的集成。</span><span class="sxs-lookup"><span data-stu-id="41ef8-136">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="41ef8-137">为预集成 SaaS 应用启用自动用户预配（如应用集成教程列表 <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list"> (仅限</a> Azure AD 库 SaaS 应用和仅) 出站预配）。</span><span class="sxs-lookup"><span data-stu-id="41ef8-137">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="41ef8-138"><strong>网络启用 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="41ef8-138"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="41ef8-139">作为 FastTrack 权益的一部分，我们建议你采用连接到云服务的最佳实践，以确保实现最佳性能Microsoft 365。</span><span class="sxs-lookup"><span data-stu-id="41ef8-139">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="41ef8-140"><strong>Active Directory 林</strong>它们的功能林级别设置为 Windows Server 2003 前向，具有以下林配置：</span><span class="sxs-lookup"><span data-stu-id="41ef8-140"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-141">单个 Active Directory 林。</span><span class="sxs-lookup"><span data-stu-id="41ef8-141">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-142">单一 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。</span><span class="sxs-lookup"><span data-stu-id="41ef8-142">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-143">多个 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。</span><span class="sxs-lookup"><span data-stu-id="41ef8-143">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-144">多个 Active Directory 帐户林，其中的一个林是一个含有 Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business 的集中式 Active Directory 帐户林。</span><span class="sxs-lookup"><span data-stu-id="41ef8-144">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-145">多个 Active Directory 帐户林，每一个都有自己的 Exchange 组织。</span><span class="sxs-lookup"><span data-stu-id="41ef8-145">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-146">租户配置和与租户集成Azure Active Directory（如果需要）。</span><span class="sxs-lookup"><span data-stu-id="41ef8-146">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="41ef8-147">
  <strong>重要</strong>  </span><span class="sxs-lookup"><span data-stu-id="41ef8-147">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="41ef8-148">对于多林 Active Directory 方案，如果部署了 Lync 2010、Lync 2013 或 Skype for Business，则必须将其部署在与 Exchange 相同的 Active Directory 林中。</span><span class="sxs-lookup"><span data-stu-id="41ef8-148">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-149">在 Exchange 多混合配置中实现具有多个 Exchange 组织的多个 Active Directory 林时，不支持在源林之间共享用户主体名称 (UPN) 命名空间。</span><span class="sxs-lookup"><span data-stu-id="41ef8-149">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="41ef8-150">Exchange 组织之间的主要 SMTP 命名空间也应该进行分隔。</span><span class="sxs-lookup"><span data-stu-id="41ef8-150">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="41ef8-151">有关详细信息，请参阅 <a href="https://go.microsoft.com/fwlink/?linkid=845444">具有多个 Active Directory 林的混合部署</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-151">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-152">对于所有多林配置，Active Directory 联合身份验证 (AD FS) 超出了范围。</span><span class="sxs-lookup"><span data-stu-id="41ef8-152">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="41ef8-153">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> 以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="41ef8-153">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="41ef8-154"><strong>Microsoft 365 应用版</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-154"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-155">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-155">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-156">解决部署问题。</span><span class="sxs-lookup"><span data-stu-id="41ef8-156">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-157">使用 Microsoft 365 管理中心和 Windows PowerShell 分配基于最终用户和设备的许可证。</span><span class="sxs-lookup"><span data-stu-id="41ef8-157">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-158">使用即点即用从 Office 365 门户安装 Microsoft 365 应用版。</span><span class="sxs-lookup"><span data-stu-id="41ef8-158">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-159">在 iOS 或 Android 设备上安装 Office Mobile 应用（如 Outlook Mobile、Word Mobile、Excel Mobile 和 PowerPoint Mobile）。</span><span class="sxs-lookup"><span data-stu-id="41ef8-159">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-160">使用 Office 365 部署工具配置更新设置。</span><span class="sxs-lookup"><span data-stu-id="41ef8-160">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-161">本地或云安装的选择和设置。</span><span class="sxs-lookup"><span data-stu-id="41ef8-161">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-162">使用 Office 自定义工具或用于配置部署包的本地 XML 创建 Office 部署工具配置 XML。</span><span class="sxs-lookup"><span data-stu-id="41ef8-162">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-163">使用 Microsoft Endpoint Configuration Manager 的部署，包括帮助创建 Microsoft Endpoint Configuration Manager 打包。</span><span class="sxs-lookup"><span data-stu-id="41ef8-163">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="41ef8-164">此外，如果你有使用 Office 早期版本的宏或外接程序，并且你遇到兼容性问题，我们会指导通过应用保证计划免费修复兼容性问题。</span><span class="sxs-lookup"><span data-stu-id="41ef8-164">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="41ef8-165">有关详细信息，<strong>请参阅</strong><a href="#windows-10">Windows 10保证部分</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-165">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="41ef8-166">联机客户端软件必须处于最低级别，如 Microsoft 365 和 Office 的系统<a href="https://go.microsoft.com/fwlink/?LinkID=723597">要求中定义</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-166">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="41ef8-167"><strong>网络运行状况</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-167"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-168">我们提供远程指导，以便从你的环境获取和解释关键网络连接数据，说明组织的网站如何与 Microsoft 的网络连接 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">原则保持一致</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-168">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="41ef8-169">这突出显示了直接影响迁移速度、用户体验、服务性能和可靠性的网络分数。</span><span class="sxs-lookup"><span data-stu-id="41ef8-169">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="41ef8-170">我们还将指导你完成此数据突出显示的任何修正步骤，以帮助你提高网络分数。</span><span class="sxs-lookup"><span data-stu-id="41ef8-170">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="41ef8-171">Microsoft 365管理中心访问权限。</span><span class="sxs-lookup"><span data-stu-id="41ef8-171">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-172">需要最新版本的 Microsoft 365 应用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-172">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-173">根据管理中心（预览版）中的网络性能Microsoft 365<a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">启用 (服务) 。 </a></span><span class="sxs-lookup"><span data-stu-id="41ef8-173">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="41ef8-174">安全性和合规性</span><span class="sxs-lookup"><span data-stu-id="41ef8-174">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="41ef8-175"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-175"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="41ef8-176"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-176"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="41ef8-177"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-177"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="41ef8-178"><strong>Azure Active Directory (Azure AD) 和 Azure AD 高级版</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-178"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-179">我们针对以下方案提供用于保护云标识的远程指南。</span><span class="sxs-lookup"><span data-stu-id="41ef8-179">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="41ef8-180">

<strong>安全基础基础结构</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="41ef8-180">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="41ef8-181">为标识配置和启用强身份验证，包括使用 Azure 多重身份验证 (MFA)  (云仅) 、Microsoft Authenticator 应用以及 Azure MFA 和自助服务密码重置联合注册 (SSPR) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-181">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li> <span data-ttu-id="41ef8-182">部署 FIDO2 或 Microsoft Authenticator App。</span><span class="sxs-lookup"><span data-stu-id="41ef8-182">Deploying FIDO2 or Microsoft Authenticator App.</span></span> </li>
<li>  <span data-ttu-id="41ef8-183">对于非 Azure AD 高级版，提供了使用安全默认值保护标识的指南。</span><span class="sxs-lookup"><span data-stu-id="41ef8-183">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-184">对于 Azure AD 高级客户，提供了使用条件访问保护标识的指南。</span><span class="sxs-lookup"><span data-stu-id="41ef8-184">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-185">通过 Azure AD 密码保护检测和阻止使用弱密码。</span><span class="sxs-lookup"><span data-stu-id="41ef8-185">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-186">使用 Azure AD 应用程序代理保护对本地 Web 应用的远程访问。</span><span class="sxs-lookup"><span data-stu-id="41ef8-186">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-187">使用 Azure Identity Protection 启用基于风险的检测和修正。</span><span class="sxs-lookup"><span data-stu-id="41ef8-187">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-188">启用自定义登录屏幕，包括徽标、文本和具有自定义品牌的图像。</span><span class="sxs-lookup"><span data-stu-id="41ef8-188">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-189">使用 Azure AD B2B 安全地与来宾用户共享应用和服务。</span><span class="sxs-lookup"><span data-stu-id="41ef8-189">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-190">使用基于角色的访问控制 (RBAC) 内置管理角色管理 Office 365 管理员的访问权限，并减少特权管理员帐户的数量。</span><span class="sxs-lookup"><span data-stu-id="41ef8-190">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-191">配置混合 Azure AD 加入。</span><span class="sxs-lookup"><span data-stu-id="41ef8-191">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-192">配置 Azure AD 加入。</span><span class="sxs-lookup"><span data-stu-id="41ef8-192">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="41ef8-193">
  
<strong>监视和报告</strong>  
</span><span class="sxs-lookup"><span data-stu-id="41ef8-193">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="41ef8-194">使用 Azure AD 连接 Health 为 AD FS、Azure AD 连接启用远程监视。</span><span class="sxs-lookup"><span data-stu-id="41ef8-194">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="41ef8-195">
  
<strong>治理</strong>  
</span><span class="sxs-lookup"><span data-stu-id="41ef8-195">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="41ef8-196">通过 Azure AD 权利管理大规模管理 Azure AD 标识和访问生命周期。</span><span class="sxs-lookup"><span data-stu-id="41ef8-196">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="41ef8-197">使用 Azure AD 访问评审管理 Azure AD 组成员身份、企业应用访问权限和角色分配。</span><span class="sxs-lookup"><span data-stu-id="41ef8-197">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-198">查看 Azure AD 使用条款。</span><span class="sxs-lookup"><span data-stu-id="41ef8-198">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-199">使用 Azure AD 管理中心管理和控制对特权Privileged Identity Management。</span><span class="sxs-lookup"><span data-stu-id="41ef8-199">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="41ef8-200">
  
<strong>自动化和效率 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="41ef8-200">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="41ef8-201">启用 Azure AD SSPR。</span><span class="sxs-lookup"><span data-stu-id="41ef8-201">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="41ef8-202">允许用户使用 Azure AD 自助服务组管理创建和管理Office 365云安全组或组。</span><span class="sxs-lookup"><span data-stu-id="41ef8-202">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-203">使用 Azure AD 委派组管理管理企业应用的委派访问权限。</span><span class="sxs-lookup"><span data-stu-id="41ef8-203">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-204">启用 Azure AD 动态组。</span><span class="sxs-lookup"><span data-stu-id="41ef8-204">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-205">使用集合在"我的应用程序"门户中组织应用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-205">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="41ef8-206">本地 Active Directory 及其环境已针对 Azure AD 高级版做好准备，包括修复阻止与 Azure AD 和 Azure AD 高级版集成的问题。</span><span class="sxs-lookup"><span data-stu-id="41ef8-206">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="41ef8-207"><strong>Azure 信息保护 </strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-207"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="41ef8-208">有关 Azure 信息保护详细信息，请参阅 <strong>此表中的 Microsoft 信息</strong> 保护。</span><span class="sxs-lookup"><span data-stu-id="41ef8-208">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="41ef8-209"><strong>发现&响应</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-209"><strong>Discover & Respond</strong></span></span></td>
<td>  

<span data-ttu-id="41ef8-210"><strong>高级电子数据展示</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-210"><strong>Advanced eDiscovery</strong></span></span>
  
<span data-ttu-id="41ef8-211">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-211">We provide remote guidance for:</span></span> 
<ul>
<li>  <span data-ttu-id="41ef8-212">创建新案例。</span><span class="sxs-lookup"><span data-stu-id="41ef8-212">Creating a new case.</span></span>   </li>
<li>  <span data-ttu-id="41ef8-213">将保管人置于保留状态。</span><span class="sxs-lookup"><span data-stu-id="41ef8-213">Putting custodians on hold.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-214">执行搜索。</span><span class="sxs-lookup"><span data-stu-id="41ef8-214">Performing searches.</span></span> </li>
<li>  <span data-ttu-id="41ef8-215">将搜索结果添加到审阅集。</span><span class="sxs-lookup"><span data-stu-id="41ef8-215">Adding search results to a review set.</span></span> </li>
<li>  <span data-ttu-id="41ef8-216">对审阅集运行分析。</span><span class="sxs-lookup"><span data-stu-id="41ef8-216">Running analytics on a review set.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-217">审阅和标记文档。</span><span class="sxs-lookup"><span data-stu-id="41ef8-217">Reviewing and tagging documents.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-218">从审阅集导出数据。</span><span class="sxs-lookup"><span data-stu-id="41ef8-218">Exporting data from the review set.</span></span> </li>
<li>  <span data-ttu-id="41ef8-219">导入非Office 365数据。</span><span class="sxs-lookup"><span data-stu-id="41ef8-219">Importing non-Office 365 data.</span></span> </li>
</ul>

<span data-ttu-id="41ef8-220"><strong>仅在 E5</strong> (支持高级审核) </span><span class="sxs-lookup"><span data-stu-id="41ef8-220"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="41ef8-221">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-221">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="41ef8-222">启用高级审核。</span><span class="sxs-lookup"><span data-stu-id="41ef8-222">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="41ef8-223">使用 UI 和审核日志审核 PowerShell 命令执行搜索。</span><span class="sxs-lookup"><span data-stu-id="41ef8-223">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="41ef8-224">

<strong> 合规性管理器</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-224">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="41ef8-225">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-225">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="41ef8-226">查看角色类型。</span><span class="sxs-lookup"><span data-stu-id="41ef8-226">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="41ef8-227">添加和配置评估。</span><span class="sxs-lookup"><span data-stu-id="41ef8-227">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="41ef8-228">通过实施改进操作来评估合规性并确定这对合规性分数的影响。</span><span class="sxs-lookup"><span data-stu-id="41ef8-228">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="41ef8-229">查看内置控件映射和评估控件。</span><span class="sxs-lookup"><span data-stu-id="41ef8-229">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="41ef8-230">在评估内生成报告。</span><span class="sxs-lookup"><span data-stu-id="41ef8-230">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="41ef8-231">

<strong>以下内容超出范围 </strong> 
</span><span class="sxs-lookup"><span data-stu-id="41ef8-231">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="41ef8-232">自定义脚本或编码。</span><span class="sxs-lookup"><span data-stu-id="41ef8-232">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="41ef8-233">电子数据展示 API。</span><span class="sxs-lookup"><span data-stu-id="41ef8-233">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="41ef8-234">数据连接器。</span><span class="sxs-lookup"><span data-stu-id="41ef8-234">Data connectors.</span></span> </li>
<li> <span data-ttu-id="41ef8-235">合规性边界和安全筛选器。</span><span class="sxs-lookup"><span data-stu-id="41ef8-235">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="41ef8-236">数据调查。</span><span class="sxs-lookup"><span data-stu-id="41ef8-236">Data investigations.</span></span></li>
<li> <span data-ttu-id="41ef8-237">数据主体请求。</span><span class="sxs-lookup"><span data-stu-id="41ef8-237">Data subject requests.</span></span></li>
<li> <span data-ttu-id="41ef8-238">设计、架构师和第三方文档审阅。</span><span class="sxs-lookup"><span data-stu-id="41ef8-238">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="41ef8-239">遵守行业和区域法规和要求。</span><span class="sxs-lookup"><span data-stu-id="41ef8-239">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="41ef8-240">合规性管理器中评估的建议改进措施的动手实施。</span><span class="sxs-lookup"><span data-stu-id="41ef8-240">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="41ef8-241">除常规 <strong>中的核心</strong> 载入 <a href="#general">部分外</a>，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="41ef8-241">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="41ef8-242"><strong>内部风险管理</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-242"><strong>Insider Risk Management</strong></span></span></td>

<td>  <span data-ttu-id="41ef8-243">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-243">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="41ef8-244">创建策略并查看设置。</span><span class="sxs-lookup"><span data-stu-id="41ef8-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="41ef8-245">访问报告和警报。</span><span class="sxs-lookup"><span data-stu-id="41ef8-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="41ef8-246">创建案例。</span><span class="sxs-lookup"><span data-stu-id="41ef8-246">Creating cases.</span></span></li>
<li> <span data-ttu-id="41ef8-247">创建通知模板。</span><span class="sxs-lookup"><span data-stu-id="41ef8-247">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="41ef8-248">有关创建人力资源和人力资源 () 指南。</span><span class="sxs-lookup"><span data-stu-id="41ef8-248">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="41ef8-249">

<strong> 通信合规性 </strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-249">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="41ef8-250">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-250">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="41ef8-251">创建策略并查看设置。</span><span class="sxs-lookup"><span data-stu-id="41ef8-251">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="41ef8-252">访问报告和警报。</span><span class="sxs-lookup"><span data-stu-id="41ef8-252">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="41ef8-253">创建通知模板。</span><span class="sxs-lookup"><span data-stu-id="41ef8-253">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="41ef8-254">

<strong> 合规性管理器</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-254">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="41ef8-255">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-255">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="41ef8-256">查看角色类型。</span><span class="sxs-lookup"><span data-stu-id="41ef8-256">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="41ef8-257">添加和配置评估。</span><span class="sxs-lookup"><span data-stu-id="41ef8-257">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="41ef8-258">通过实施改进操作来评估合规性并确定这对合规性分数的影响。</span><span class="sxs-lookup"><span data-stu-id="41ef8-258">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="41ef8-259">查看内置控件映射和评估控件。</span><span class="sxs-lookup"><span data-stu-id="41ef8-259">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="41ef8-260">在评估内生成报告。</span><span class="sxs-lookup"><span data-stu-id="41ef8-260">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="41ef8-261">

<strong>以下内容超出范围 </strong> 
</span><span class="sxs-lookup"><span data-stu-id="41ef8-261">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="41ef8-262">创建和管理Power Automate流。</span><span class="sxs-lookup"><span data-stu-id="41ef8-262">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="41ef8-263">数据连接器 (HR 连接器) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-263">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="41ef8-264">使用 RegEx (配置的) 正则表达式。</span><span class="sxs-lookup"><span data-stu-id="41ef8-264">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="41ef8-265">设计、架构师和第三方文档审阅。</span><span class="sxs-lookup"><span data-stu-id="41ef8-265">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="41ef8-266">信息屏障。</span><span class="sxs-lookup"><span data-stu-id="41ef8-266">Information barriers.</span></span></li>
<li> <span data-ttu-id="41ef8-267">特权访问管理。</span><span class="sxs-lookup"><span data-stu-id="41ef8-267">Privileged access management.</span></span></li>
<li> <span data-ttu-id="41ef8-268">遵守行业和区域法规和要求。</span><span class="sxs-lookup"><span data-stu-id="41ef8-268">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="41ef8-269">合规性管理器中评估的建议改进措施的动手实施。</span><span class="sxs-lookup"><span data-stu-id="41ef8-269">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="41ef8-270">除常规 <strong>中的核心</strong> 载入 <a href="#general">部分外</a>，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="41ef8-270">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="41ef8-271"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-271"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="41ef8-272">Microsoft 365Defender 是一个统一的攻破前和入侵后企业防御套件，在本机协调跨终结点、标识、电子邮件和应用进行检测、预防、调查和响应，以提供针对复杂攻击的集成保护。</span><span class="sxs-lookup"><span data-stu-id="41ef8-272">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="41ef8-273">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-273">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="41ef8-274">提供安全中心Microsoft 365概述。</span><span class="sxs-lookup"><span data-stu-id="41ef8-274">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-275">查看跨产品事件，包括通过确保完整的攻击范围、受影响的资产和分组在一起的自动修正操作，重点关注关键方面。</span><span class="sxs-lookup"><span data-stu-id="41ef8-275">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-276">演示 Microsoft 365 Defender 如何安排对资产、用户、设备和邮箱的调查，这些资产、用户、设备和邮箱可能由于自动自我修复而受到威胁。</span><span class="sxs-lookup"><span data-stu-id="41ef8-276">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="41ef8-277">解释并提供客户如何主动搜寻跨多个数据集影响您的电子邮件、数据、设备和帐户的入侵尝试和入侵活动的示例。</span><span class="sxs-lookup"><span data-stu-id="41ef8-277">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="41ef8-278">向客户展示他们如何使用 Microsoft 安全分数全面查看和改进安全状况。</span><span class="sxs-lookup"><span data-stu-id="41ef8-278">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="41ef8-279"><strong>以下内容超出范围</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-279"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="41ef8-280">客户补救活动的项目管理。</span><span class="sxs-lookup"><span data-stu-id="41ef8-280">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="41ef8-281">持续管理、威胁响应和修正。</span><span class="sxs-lookup"><span data-stu-id="41ef8-281">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="41ef8-282">部署指南或教育：：</span><span class="sxs-lookup"><span data-stu-id="41ef8-282">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="41ef8-283">如何修正或解释各种警报类型和监视的活动。</span><span class="sxs-lookup"><span data-stu-id="41ef8-283">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="41ef8-284">如何调查用户、计算机、横向移动路径或实体。</span><span class="sxs-lookup"><span data-stu-id="41ef8-284">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="41ef8-285">自定义威胁搜寻。</span><span class="sxs-lookup"><span data-stu-id="41ef8-285">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="41ef8-286">SIEM 或 API (安全) 事件管理。</span><span class="sxs-lookup"><span data-stu-id="41ef8-286">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="41ef8-287"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-287"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-288">Microsoft Cloud App Security 是云访问安全代理 (CASB) ，可提供丰富的可见性、控制数据传输和复杂分析，以识别和防御所有 Microsoft 和第三方云服务中的网络威胁。</span><span class="sxs-lookup"><span data-stu-id="41ef8-288">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="41ef8-289">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-289">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-290">配置门户，包括：</span><span class="sxs-lookup"><span data-stu-id="41ef8-290">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="41ef8-291">导入用户组。</span><span class="sxs-lookup"><span data-stu-id="41ef8-291">Importing user groups.</span></span></li>
<li> <span data-ttu-id="41ef8-292">管理管理员访问权限和设置。</span><span class="sxs-lookup"><span data-stu-id="41ef8-292">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="41ef8-293">将部署范围确定为选择要监视或排除在监控范围中的某些用户组。</span><span class="sxs-lookup"><span data-stu-id="41ef8-293">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="41ef8-294">设置 IP 范围和标记。</span><span class="sxs-lookup"><span data-stu-id="41ef8-294">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="41ef8-295">使用徽标和自定义消息来个性化最终用户体验。</span><span class="sxs-lookup"><span data-stu-id="41ef8-295">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="41ef8-296">设置云发现以提供卷影 IT，使用：</span><span class="sxs-lookup"><span data-stu-id="41ef8-296">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="41ef8-297">适用于终结点的 Microsoft Defender。</span><span class="sxs-lookup"><span data-stu-id="41ef8-297">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="41ef8-298">Zscaler。</span><span class="sxs-lookup"><span data-stu-id="41ef8-298">Zscaler.</span></span></li>
<li> <span data-ttu-id="41ef8-299">iboss。</span><span class="sxs-lookup"><span data-stu-id="41ef8-299">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="41ef8-300">使用 <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">应用连接器</a> 连接特色应用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-300">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="41ef8-301">在条件访问和访问门户中设置云应用安全访问应用控件，以应用实时会话控件。</span><span class="sxs-lookup"><span data-stu-id="41ef8-301">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="41ef8-302">部署云应用安全和云发现仪表板。</span><span class="sxs-lookup"><span data-stu-id="41ef8-302">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="41ef8-303">根据组织优先级自定义应用风险评分。</span><span class="sxs-lookup"><span data-stu-id="41ef8-303">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="41ef8-304">创建应用标记和类别。</span><span class="sxs-lookup"><span data-stu-id="41ef8-304">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="41ef8-305">批准和取消批准应用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-305">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="41ef8-306">使用活动和文件日志。</span><span class="sxs-lookup"><span data-stu-id="41ef8-306">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="41ef8-307">管理 OAuth 应用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-307">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="41ef8-308">了解 defender 门户中Microsoft 365相关。</span><span class="sxs-lookup"><span data-stu-id="41ef8-308">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="41ef8-309">为 CASB 的 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20</a> 大用例提供配置帮助 (包括创建或更新多达 6 (6) 策略，) 除外：</span><span class="sxs-lookup"><span data-stu-id="41ef8-309">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="41ef8-310">审核将 Internet 作为服务配置 (IaaS) 环境 (#18) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-310">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="41ef8-311">监视用户活动，以抵御 IaaS 环境中 (#19) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-311">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="41ef8-312"><strong>以下内容超出范围</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-312"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="41ef8-313">客户补救活动的项目管理。</span><span class="sxs-lookup"><span data-stu-id="41ef8-313">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="41ef8-314">持续管理、威胁响应和修正。</span><span class="sxs-lookup"><span data-stu-id="41ef8-314">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="41ef8-315">使用 Docker 或日志收集器为连续报告设置自动日志上载的基础结构、安装或部署。</span><span class="sxs-lookup"><span data-stu-id="41ef8-315">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="41ef8-316">有关详细信息 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">，请参阅 CASB 的前 20</a> 个用例。</span><span class="sxs-lookup"><span data-stu-id="41ef8-316">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="41ef8-317">创建云发现快照报告。</span><span class="sxs-lookup"><span data-stu-id="41ef8-317">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="41ef8-318">使用阻止脚本阻止应用使用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-318">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="41ef8-319">连接自定义应用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-319">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="41ef8-320">与第三方标识提供程序 (DLP) 提供程序的 ISP (数据丢失) 集成。</span><span class="sxs-lookup"><span data-stu-id="41ef8-320">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="41ef8-321">有关高级搜寻的培训或指导。</span><span class="sxs-lookup"><span data-stu-id="41ef8-321">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="41ef8-322">自动调查和修正，包括 Microsoft Power Automate手册。</span><span class="sxs-lookup"><span data-stu-id="41ef8-322">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="41ef8-323">SIEM 或 API 集成 (安全) 事件管理 (包括 Azure Sentinel) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-323">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="41ef8-324">部署 Cloud App Discovery 作为概念证明。</span><span class="sxs-lookup"><span data-stu-id="41ef8-324">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="41ef8-325"><strong>Microsoft Defender for Endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-325"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-326">Microsoft Defender for Endpoint 是旨在帮助企业网络预防、检测、调查和响应高级威胁的平台。</span><span class="sxs-lookup"><span data-stu-id="41ef8-326">Microsoft Defender for Endpoint is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="41ef8-327">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-327">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-328">部署技术以确保终结点安全。</span><span class="sxs-lookup"><span data-stu-id="41ef8-328">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-329">配置终结点保护和设备限制配置文件。</span><span class="sxs-lookup"><span data-stu-id="41ef8-329">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-330">评估操作系统版本和设备管理 (包括 Intune、Microsoft Endpoint Configuration Manager、组策略对象 (GPO) 和第三方配置) 以及 Windows Defender AV 服务或其他终结点安全软件的状态。</span><span class="sxs-lookup"><span data-stu-id="41ef8-330">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-331">评估你的 Windows AV 服务或其他终结点安全软件的状态。</span><span class="sxs-lookup"><span data-stu-id="41ef8-331">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-332">评估限制网络流量的代理和防火墙。</span><span class="sxs-lookup"><span data-stu-id="41ef8-332">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-333">通过说明如何使用载入终结点部署 Defender for Endpoint 代理配置文件，启用 Microsoft Defender for Endpoint 服务。</span><span class="sxs-lookup"><span data-stu-id="41ef8-333">Enabling the Microsoft Defender for Endpoint service by explaining how to deploy a Defender for Endpoint agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-334">部署指南、配置帮助和教育：</span><span class="sxs-lookup"><span data-stu-id="41ef8-334">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="41ef8-335">威胁和漏洞管理。</span><span class="sxs-lookup"><span data-stu-id="41ef8-335">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-336">攻击面减少。</span><span class="sxs-lookup"><span data-stu-id="41ef8-336">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-337">新一代保护。</span><span class="sxs-lookup"><span data-stu-id="41ef8-337">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-338">终结点检测和响应。</span><span class="sxs-lookup"><span data-stu-id="41ef8-338">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-339">自动调查和修复。</span><span class="sxs-lookup"><span data-stu-id="41ef8-339">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-340">安全功能分数。</span><span class="sxs-lookup"><span data-stu-id="41ef8-340">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="41ef8-341">查看模拟和教程 (如实践方案、虚假恶意软件和自动调查) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-341">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-342">报告和威胁分析功能的概述。</span><span class="sxs-lookup"><span data-stu-id="41ef8-342">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-343">将 Microsoft Defender for Office 365与 Microsoft Defender for Endpoint 集成。</span><span class="sxs-lookup"><span data-stu-id="41ef8-343">Integrating Microsoft Defender for Office 365 with Microsoft Defender for Endpoint.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-344">在 Microsoft Defender 安全中心门户中执行演练。</span><span class="sxs-lookup"><span data-stu-id="41ef8-344">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-345">以下操作系统：</span><span class="sxs-lookup"><span data-stu-id="41ef8-345">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="41ef8-346">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="41ef8-346">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-347">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="41ef8-347">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-348">WindowsServer 2019。</span><span class="sxs-lookup"><span data-stu-id="41ef8-348">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-349">WindowsServer 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="41ef8-349">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-350">WindowsServer Semi-Annual Channel (SAC) 版本 1803。</span><span class="sxs-lookup"><span data-stu-id="41ef8-350">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-351">macOS 版本 10.13、10.14 和 10.15。</span><span class="sxs-lookup"><span data-stu-id="41ef8-351">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="41ef8-352">
<strong>注意：</strong>所有 Windows Server 版本都必须由 System Center Configuration Manager 2012 (版本 1012 R2、1511 或 1602) 或 Microsoft Endpoint Configuration Manager (版本 2002 或) ) 的最新版本管理。</span><span class="sxs-lookup"><span data-stu-id="41ef8-352">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="41ef8-353"></li>
</ul>

<strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="41ef8-353"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="41ef8-354">客户补救活动的项目管理。</span><span class="sxs-lookup"><span data-stu-id="41ef8-354">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-355">现场支持。</span><span class="sxs-lookup"><span data-stu-id="41ef8-355">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-356">持续管理和威胁响应。</span><span class="sxs-lookup"><span data-stu-id="41ef8-356">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-357">以下 Microsoft Defender 终结点代理的载入或配置：</span><span class="sxs-lookup"><span data-stu-id="41ef8-357">Onboarding or configuration for the following Microsoft Defender for Endpoint agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="41ef8-358">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="41ef8-358">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-359">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="41ef8-359">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-360">Linux。</span><span class="sxs-lookup"><span data-stu-id="41ef8-360">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-361">Android 和 iOS (移动设备) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-361">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="41ef8-362">虚拟桌面基础结构 (VDI)  (持久或非永久性) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-362">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="41ef8-363">服务器载入和配置：</span><span class="sxs-lookup"><span data-stu-id="41ef8-363">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="41ef8-364">为脱机通信配置代理服务器。</span><span class="sxs-lookup"><span data-stu-id="41ef8-364">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-365">在下层 Configuration Manager 实例和版本上配置 Configuration Manager 部署包。</span><span class="sxs-lookup"><span data-stu-id="41ef8-365">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-366">将服务器载入 Azure 安全中心。</span><span class="sxs-lookup"><span data-stu-id="41ef8-366">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-367">未由 Configuration Manager 管理的服务器。</span><span class="sxs-lookup"><span data-stu-id="41ef8-367">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="41ef8-368">macOS 载入和配置：</span><span class="sxs-lookup"><span data-stu-id="41ef8-368">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="41ef8-369">手动基于 Intune 的部署。</span><span class="sxs-lookup"><span data-stu-id="41ef8-369">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-370">基于 JAMF 的部署。</span><span class="sxs-lookup"><span data-stu-id="41ef8-370">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="41ef8-371">MDM 的其他移动设备 () 基于产品的部署。</span><span class="sxs-lookup"><span data-stu-id="41ef8-371">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-372">手动部署。</span><span class="sxs-lookup"><span data-stu-id="41ef8-372">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="41ef8-373">配置以下攻击面减少功能：</span><span class="sxs-lookup"><span data-stu-id="41ef8-373">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="41ef8-374">基于硬件的隔离。</span><span class="sxs-lookup"><span data-stu-id="41ef8-374">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-375">应用控件。</span><span class="sxs-lookup"><span data-stu-id="41ef8-375">App control.</span></span>  
  </li>
<li> <span data-ttu-id="41ef8-376">设备控件。</span><span class="sxs-lookup"><span data-stu-id="41ef8-376">Device control.</span></span></li>
<li>  
  <span data-ttu-id="41ef8-377">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="41ef8-377">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-378">网络防火墙。</span><span class="sxs-lookup"><span data-stu-id="41ef8-378">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="41ef8-379">帐户保护功能的配置或管理，例如：</span><span class="sxs-lookup"><span data-stu-id="41ef8-379">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="41ef8-380">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="41ef8-380">Windows Hello</span></span></li>
<li> <span data-ttu-id="41ef8-381">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="41ef8-381">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="41ef8-382">配置或管理BitLocker。</span><span class="sxs-lookup"><span data-stu-id="41ef8-382">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="41ef8-383">注册或配置 Microsoft 威胁专家。</span><span class="sxs-lookup"><span data-stu-id="41ef8-383">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-384">查看 SIEM 连接中的 API 或安全信息 (或) 培训。</span><span class="sxs-lookup"><span data-stu-id="41ef8-384">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-385">注册或配置 Microsoft 威胁防护 (MTP)。</span><span class="sxs-lookup"><span data-stu-id="41ef8-385">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-386">有关高级搜寻的培训或指导。</span><span class="sxs-lookup"><span data-stu-id="41ef8-386">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-387">有关使用或创建 Kusto 查询的培训或指南。</span><span class="sxs-lookup"><span data-stu-id="41ef8-387">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="41ef8-388">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="41ef8-388">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="41ef8-389"><strong>Microsoft Defender for Identity </strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-389"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="41ef8-390">Microsoft Defender for Identity 是一种基于云的安全解决方案，可利用本地 Active Directory 信号来识别、检测和调查针对组织的高级威胁、已遭入侵标识和恶意内部行为。</span><span class="sxs-lookup"><span data-stu-id="41ef8-390">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="41ef8-391">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-391">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="41ef8-392">创建适用于标识的 Defender 实例。</span><span class="sxs-lookup"><span data-stu-id="41ef8-392">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="41ef8-393">将 Defender for Identity 连接到 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="41ef8-393">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="41ef8-394">评估你的环境在域控制器上部署 Defender for Identity 传感器的准备情况，包括：</span><span class="sxs-lookup"><span data-stu-id="41ef8-394">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="41ef8-395">运行大小工具进行资源容量规划。</span><span class="sxs-lookup"><span data-stu-id="41ef8-395">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="41ef8-396">运行审核工具来评估域控制器与传感器的兼容性。</span><span class="sxs-lookup"><span data-stu-id="41ef8-396">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="41ef8-397">部署传感器以捕获和分析网络流量，并Windows域控制器捕获和分析网络事件，包括：</span><span class="sxs-lookup"><span data-stu-id="41ef8-397">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="41ef8-398">下载传感器程序包。</span><span class="sxs-lookup"><span data-stu-id="41ef8-398">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="41ef8-399">配置传感器。</span><span class="sxs-lookup"><span data-stu-id="41ef8-399">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="41ef8-400">以静默方式在域控制器上安装传感器。</span><span class="sxs-lookup"><span data-stu-id="41ef8-400">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="41ef8-401">将传感器部署到多林环境。</span><span class="sxs-lookup"><span data-stu-id="41ef8-401">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="41ef8-402">将 Defender for Identity 与Microsoft Cloud App Security (云应用安全不需要集成许可) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-402">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="41ef8-403">提供有关： 的部署指南、配置帮助和教育：</span><span class="sxs-lookup"><span data-stu-id="41ef8-403">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="41ef8-404">调整环境以减少"噪音"。</span><span class="sxs-lookup"><span data-stu-id="41ef8-404">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="41ef8-405">了解身份安全状态评估报告。</span><span class="sxs-lookup"><span data-stu-id="41ef8-405">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="41ef8-406">了解用户调查优先级分数和用户调查排名报告。</span><span class="sxs-lookup"><span data-stu-id="41ef8-406">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="41ef8-407">了解非活动用户报告。</span><span class="sxs-lookup"><span data-stu-id="41ef8-407">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="41ef8-408">在遭到入侵的帐户上提供修正选项。</span><span class="sxs-lookup"><span data-stu-id="41ef8-408">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="41ef8-409">推动从高级威胁分析 (ATA) 到 Defender for Identity。</span><span class="sxs-lookup"><span data-stu-id="41ef8-409">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="41ef8-410"><strong>以下内容超出范围</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-410"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="41ef8-411">客户补救活动的项目管理。</span><span class="sxs-lookup"><span data-stu-id="41ef8-411">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="41ef8-412">持续管理、威胁响应和修正。</span><span class="sxs-lookup"><span data-stu-id="41ef8-412">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="41ef8-413">部署 Defender for Identity 传感器，包括：</span><span class="sxs-lookup"><span data-stu-id="41ef8-413">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="41ef8-414">手动容量规划。</span><span class="sxs-lookup"><span data-stu-id="41ef8-414">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="41ef8-415">以独立容量部署传感器。</span><span class="sxs-lookup"><span data-stu-id="41ef8-415">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="41ef8-416">使用网络接口卡部署传感器 (NIC) 适配器。</span><span class="sxs-lookup"><span data-stu-id="41ef8-416">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="41ef8-417">通过第三方工具部署传感器。</span><span class="sxs-lookup"><span data-stu-id="41ef8-417">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="41ef8-418">通过 Web 代理连接连接到 Defender for Identity 云服务。</span><span class="sxs-lookup"><span data-stu-id="41ef8-418">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="41ef8-419">创建和管理 honeytokens。</span><span class="sxs-lookup"><span data-stu-id="41ef8-419">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="41ef8-420">部署指南或教育：：</span><span class="sxs-lookup"><span data-stu-id="41ef8-420">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="41ef8-421">修正或解释各种警报类型和受监视的活动。</span><span class="sxs-lookup"><span data-stu-id="41ef8-421">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="41ef8-422">调查用户、计算机、横向移动路径或实体。</span><span class="sxs-lookup"><span data-stu-id="41ef8-422">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="41ef8-423">威胁或高级搜寻。</span><span class="sxs-lookup"><span data-stu-id="41ef8-423">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="41ef8-424">事件响应。</span><span class="sxs-lookup"><span data-stu-id="41ef8-424">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="41ef8-425">为 Defender for Identity 提供安全警报实验室教程。</span><span class="sxs-lookup"><span data-stu-id="41ef8-425">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="41ef8-426">当 Defender for Identity 检测到可疑活动时，通过指定传感器向 syslog 服务器发送安全警报，从而提供通知。</span><span class="sxs-lookup"><span data-stu-id="41ef8-426">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="41ef8-427">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span><span class="sxs-lookup"><span data-stu-id="41ef8-427">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="41ef8-428">配置 VPN 解决方案以将信息从 VPN 连接添加到用户配置文件页面。</span><span class="sxs-lookup"><span data-stu-id="41ef8-428">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="41ef8-429">SIEM 或 API 集成 (安全) 事件管理 (包括 Azure Sentinel) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-429">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="41ef8-430">部署 Defender for Identity 传感器作为概念证明。</span><span class="sxs-lookup"><span data-stu-id="41ef8-430">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="41ef8-431">已部署 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="41ef8-431">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-432">打算安装 Defender for Identity 传感器的域控制器具有到 Defender for Identity 云服务的 Internet 连接。</span><span class="sxs-lookup"><span data-stu-id="41ef8-432">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="41ef8-433">防火墙和代理必须处于打开状态，以与 Defender for Identity 云服务通信 (\*.atp.azure.com 端口 443 必须) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-433">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="41ef8-434">在下列其中一个上运行的域控制器：</span><span class="sxs-lookup"><span data-stu-id="41ef8-434">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="41ef8-435">WindowsServer 2008 R2 SP1。</span><span class="sxs-lookup"><span data-stu-id="41ef8-435">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="41ef8-436">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="41ef8-436">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="41ef8-437">Windows Server 2012R2。</span><span class="sxs-lookup"><span data-stu-id="41ef8-437">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="41ef8-438">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="41ef8-438">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="41ef8-439">Windows带 KB4487044 的服务器 2019 (操作系统版本 17763.316) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-439">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="41ef8-440"><strong>Microsoft Defender for Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-440"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-441">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-441">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-442">启用安全链接、安全附件和防钓鱼。</span><span class="sxs-lookup"><span data-stu-id="41ef8-442">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-443">配置自动化、调查和响应。</span><span class="sxs-lookup"><span data-stu-id="41ef8-443">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-444">使用攻击模拟器。</span><span class="sxs-lookup"><span data-stu-id="41ef8-444">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-445">报告和威胁分析。</span><span class="sxs-lookup"><span data-stu-id="41ef8-445">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="41ef8-446">除常规 <strong>中的核心</strong> 载入 <a href="#general">部分外</a>，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="41ef8-446">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>


<tr class="even">
<td><span data-ttu-id="41ef8-447"><strong>Microsoft 信息管控</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-447"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="41ef8-448">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-448">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-449">创建和发布保留标签和策略 (仅在 E5) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-449">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="41ef8-450">记录管理 (仅在 E5 记录) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-450">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="41ef8-451">查看文件计划创建。</span><span class="sxs-lookup"><span data-stu-id="41ef8-451">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="41ef8-452">创建和管理记录 (包括基于事件的记录) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-452">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-453">正在审查处置。</span><span class="sxs-lookup"><span data-stu-id="41ef8-453">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="41ef8-454">

<strong> 合规性管理器</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-454">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="41ef8-455">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-455">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="41ef8-456">查看角色类型。</span><span class="sxs-lookup"><span data-stu-id="41ef8-456">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="41ef8-457">添加和配置评估。</span><span class="sxs-lookup"><span data-stu-id="41ef8-457">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="41ef8-458">通过实施改进操作来评估合规性并确定这对合规性分数的影响。</span><span class="sxs-lookup"><span data-stu-id="41ef8-458">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="41ef8-459">查看内置控件映射和评估控件。</span><span class="sxs-lookup"><span data-stu-id="41ef8-459">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="41ef8-460">在评估内生成报告。</span><span class="sxs-lookup"><span data-stu-id="41ef8-460">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="41ef8-461">

  <strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="41ef8-461">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="41ef8-462">开发记录管理文件计划。</span><span class="sxs-lookup"><span data-stu-id="41ef8-462">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="41ef8-463">数据连接器。</span><span class="sxs-lookup"><span data-stu-id="41ef8-463">Data connectors.</span></span></li>
<li> <span data-ttu-id="41ef8-464">开发 SharePoint 中的信息体系结构。</span><span class="sxs-lookup"><span data-stu-id="41ef8-464">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="41ef8-465">自定义脚本和编码。</span><span class="sxs-lookup"><span data-stu-id="41ef8-465">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="41ef8-466">设计、架构师和第三方文档审阅。</span><span class="sxs-lookup"><span data-stu-id="41ef8-466">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="41ef8-467">支持 E3。</span><span class="sxs-lookup"><span data-stu-id="41ef8-467">Support for E3.</span></span></li>
<li> <span data-ttu-id="41ef8-468">遵守行业和区域法规和要求。</span><span class="sxs-lookup"><span data-stu-id="41ef8-468">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="41ef8-469">合规性管理器中评估的建议改进措施的动手实施。</span><span class="sxs-lookup"><span data-stu-id="41ef8-469">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="41ef8-470">除常规 <strong>中的核心</strong> 载入 <a href="#general">部分外</a>，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="41ef8-470">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="41ef8-471"><strong>Microsoft 信息保护</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-471"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-472">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-472">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-473">E3 (E5 支持的数据) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-473">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-474">E3 和 E5 (支持敏感信息) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-474">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-475">创建敏感度标签 (E3 和 E5 支持) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-475">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-476">在 E3 和 E5 (支持应用敏感度) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-476">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-477">E5 (支持的可训练分类) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-477">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-478">使用内容资源管理器和活动资源管理器了解数据 (E5 服务支持) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-478">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-479">使用策略发布标签 (E5)  (支持手动和自动) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-479">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-480">为 E5 (支持) 终结点Windows 10创建终结点数据丢失 (DLP) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-480">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-481">为聊天和Microsoft Teams创建 DLP 策略。</span><span class="sxs-lookup"><span data-stu-id="41ef8-481">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="41ef8-482">

<strong> 合规性管理器</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-482">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="41ef8-483">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-483">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="41ef8-484">查看角色类型。</span><span class="sxs-lookup"><span data-stu-id="41ef8-484">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="41ef8-485">添加和配置评估。</span><span class="sxs-lookup"><span data-stu-id="41ef8-485">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="41ef8-486">通过实施改进操作来评估合规性并确定这对合规性分数的影响。</span><span class="sxs-lookup"><span data-stu-id="41ef8-486">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="41ef8-487">查看内置控件映射和评估控件。</span><span class="sxs-lookup"><span data-stu-id="41ef8-487">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="41ef8-488">在评估内生成报告。</span><span class="sxs-lookup"><span data-stu-id="41ef8-488">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="41ef8-489">

<strong> Azure 信息保护</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-489">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="41ef8-490">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-490">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="41ef8-491">激活和配置租户。</span><span class="sxs-lookup"><span data-stu-id="41ef8-491">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-492">创建和设置 P1 和 P2 (支持的标签和) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-492">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-493">对 P1 和 P2 (支持的文档应用信息) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-493">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-494">自动分类和标记 Office 应用中的信息 (如在 Windows 上运行的 Word、PowerPoint、Excel 和 Outlook) ，以及使用 P2) 中支持的 Azure 信息保护客户端 (。</span><span class="sxs-lookup"><span data-stu-id="41ef8-494">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-495">使用 Azure 信息保护扫描程序发现和标记处于 (P1 和 P2) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-495">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-496">使用 Exchange Online 邮件流规则监视传输中的电子邮件。</span><span class="sxs-lookup"><span data-stu-id="41ef8-496">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="41ef8-497">如果你希望使用 Microsoft Azure Rights Management Services (Azure RMS) 、Office 365 邮件加密 (OME)  (和数据丢失防护) 应用保护，我们还会提供指导。</span><span class="sxs-lookup"><span data-stu-id="41ef8-497">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="41ef8-498"><strong>以下内容超出范围 </strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-498"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="41ef8-499">客户密钥。</span><span class="sxs-lookup"><span data-stu-id="41ef8-499">Customer key.</span></span></li>
<li><span data-ttu-id="41ef8-500">RegEx (正则表达式) 敏感信息类型的开发。</span><span class="sxs-lookup"><span data-stu-id="41ef8-500">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="41ef8-501">创建或修改关键字词典。</span><span class="sxs-lookup"><span data-stu-id="41ef8-501">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="41ef8-502">自定义脚本和编码。</span><span class="sxs-lookup"><span data-stu-id="41ef8-502">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="41ef8-503">Azure Azure Azure。</span><span class="sxs-lookup"><span data-stu-id="41ef8-503">Azure Purview.</span></span></li>
<li> <span data-ttu-id="41ef8-504">设计、架构师和第三方文档审阅。</span><span class="sxs-lookup"><span data-stu-id="41ef8-504">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="41ef8-505">遵守行业和区域法规和要求。</span><span class="sxs-lookup"><span data-stu-id="41ef8-505">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="41ef8-506">合规性管理器中评估的建议改进措施的动手实施。</span><span class="sxs-lookup"><span data-stu-id="41ef8-506">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="41ef8-507">除常规 <strong>中的核心</strong> 载入 <a href="#general">部分外</a>，除 Azure 信息保护外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="41ef8-507">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="41ef8-508"><strong>Azure 信息保护</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-508"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="41ef8-509">客户先决条件职责包括：</span><span class="sxs-lookup"><span data-stu-id="41ef8-509">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="41ef8-510">要扫描的文件共享位置的列表。</span><span class="sxs-lookup"><span data-stu-id="41ef8-510">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-511">批准的分类分类。</span><span class="sxs-lookup"><span data-stu-id="41ef8-511">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="41ef8-512">了解有关密钥管理的任何法规限制或要求。</span><span class="sxs-lookup"><span data-stu-id="41ef8-512">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-513">为本地 Active Directory 创建的已与 Azure AD 同步的服务帐户。</span><span class="sxs-lookup"><span data-stu-id="41ef8-513">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="41ef8-514">为分类和保护配置的标签。</span><span class="sxs-lookup"><span data-stu-id="41ef8-514">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="41ef8-515">Azure 信息保护扫描程序的所有先决条件都已到位。</span><span class="sxs-lookup"><span data-stu-id="41ef8-515">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="41ef8-516">有关详细信息，请参阅安装和部署 Azure 信息保护统一标签扫描 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">程序的先决条件</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-516">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="41ef8-517">确保用户设备正在运行受支持的操作系统，并且已安装必要的必备组件。</span><span class="sxs-lookup"><span data-stu-id="41ef8-517">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="41ef8-518">有关详细信息，请参阅以下内容。</span><span class="sxs-lookup"><span data-stu-id="41ef8-518">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="41ef8-519"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理指南：为用户安装 Azure 信息保护统一标记客户端</a>   </span><span class="sxs-lookup"><span data-stu-id="41ef8-519"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="41ef8-520"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">什么是适用于 iOS 或 Android 的 Azure 信息保护应用？</a>  </span><span class="sxs-lookup"><span data-stu-id="41ef8-520"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="41ef8-521">安装和配置 Azure RMS 连接器和服务器，包括 Active Directory RMS (AD RMS) 连接器，实现混合支持。</span><span class="sxs-lookup"><span data-stu-id="41ef8-521">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="41ef8-522">设置和配置自带密钥 (BYOK) 、双密钥加密 (DKE)  (统一标记客户端仅) 或仅保留你自己的密钥 (HYOK)  (经典客户端) （如果部署需要这些选项之一）。</span><span class="sxs-lookup"><span data-stu-id="41ef8-522">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="41ef8-523"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-523"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-524">我们提供有关准备好使用 Intune 作为基于云的移动设备管理 (MDM) 和移动应用管理 (MAM) 提供程序的远程指导。</span><span class="sxs-lookup"><span data-stu-id="41ef8-524">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="41ef8-525">具体步骤取决于你的源环境，并且基于你的移动设备和移动应用管理需求。</span><span class="sxs-lookup"><span data-stu-id="41ef8-525">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="41ef8-526">所包含的具体步骤如下：</span><span class="sxs-lookup"><span data-stu-id="41ef8-526">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-527">许可最终用户。</span><span class="sxs-lookup"><span data-stu-id="41ef8-527">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-528">通过利用本地 Active Directory 或 Azure AD (云标识配置由 Intune) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-528">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-529">将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。</span><span class="sxs-lookup"><span data-stu-id="41ef8-529">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-530">根据管理需求配置 MDM 颁发机构，包括：</span><span class="sxs-lookup"><span data-stu-id="41ef8-530">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-531">如果 Intune 是唯一的 MDM 解决方案，将 Intune 设置为 MDM 颁发机构。</span><span class="sxs-lookup"><span data-stu-id="41ef8-531">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="41ef8-532">为以下操作提供 MDM 指南:</span><span class="sxs-lookup"><span data-stu-id="41ef8-532">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-533">配置用于验证 MDM 管理策略的测试组。</span><span class="sxs-lookup"><span data-stu-id="41ef8-533">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-534">配置 MDM 管理策略和服务，如：</span><span class="sxs-lookup"><span data-stu-id="41ef8-534">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-535">通过 Web 链接或深层链接针对每个受支持的平台部署应用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-535">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-536">条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="41ef8-536">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-537">如果组织中已有证书颁发机构、无线网络或 VPN 基础结构，则部署电子邮件、无线网络和 VPN 配置文件。</span><span class="sxs-lookup"><span data-stu-id="41ef8-537">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-538">连接到 Intune 数据仓库。</span><span class="sxs-lookup"><span data-stu-id="41ef8-538">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-539">将 Intune 与以下内容进行集成：</span><span class="sxs-lookup"><span data-stu-id="41ef8-539">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-540">需要团队查看器订阅 (远程协助团队查看器) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-540">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-541">移动威胁 (MTD) MTD (需要 MTD 订阅) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-541">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-542">需要电信费用管理解决方案 (电信费用管理解决方案订阅) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-542">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="41ef8-543">将每个受支持平台的设备注册到 Intune。</span><span class="sxs-lookup"><span data-stu-id="41ef8-543">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="41ef8-544">提供有关应用保护的指南：</span><span class="sxs-lookup"><span data-stu-id="41ef8-544">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-545">为每个受支持的平台配置应用保护策略。</span><span class="sxs-lookup"><span data-stu-id="41ef8-545">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-546">为托管应用配置条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="41ef8-546">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-547">使用前面提到的 MAM 策略面向相应的用户组。</span><span class="sxs-lookup"><span data-stu-id="41ef8-547">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-548">使用托管应用使用情况报告。</span><span class="sxs-lookup"><span data-stu-id="41ef8-548">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="41ef8-549">提供从旧版电脑管理到 Intune MDM 的迁移指南。</span><span class="sxs-lookup"><span data-stu-id="41ef8-549">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="41ef8-550">
 
</li>
</ul>
  
<strong>云附加</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-550">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="41ef8-551">我们将指导你准备好使用 Intune 云附加现有 Configuration Manager 环境。</span><span class="sxs-lookup"><span data-stu-id="41ef8-551">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="41ef8-552">具体步骤取决于源环境。</span><span class="sxs-lookup"><span data-stu-id="41ef8-552">The exact steps depend on your source environment.</span></span> <span data-ttu-id="41ef8-553">这些步骤包括：</span><span class="sxs-lookup"><span data-stu-id="41ef8-553">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="41ef8-554">许可最终用户。</span><span class="sxs-lookup"><span data-stu-id="41ef8-554">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-555">通过利用本地 Active Directory 和云标识，配置供 Intune 使用的标识。</span><span class="sxs-lookup"><span data-stu-id="41ef8-555">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-556">将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。</span><span class="sxs-lookup"><span data-stu-id="41ef8-556">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-557">提供设置混合 Azure AD 加入的指南。</span><span class="sxs-lookup"><span data-stu-id="41ef8-557">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-558">提供有关为 MDM 自动注册设置 Azure AD 的指南。</span><span class="sxs-lookup"><span data-stu-id="41ef8-558">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-559">提供有关在将云管理网关用作基于远程 Internet 的设备管理共同管理的解决方案时如何设置云管理网关的指南。</span><span class="sxs-lookup"><span data-stu-id="41ef8-559">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-560">配置要切换到 Intune 的受支持工作负载。</span><span class="sxs-lookup"><span data-stu-id="41ef8-560">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-561">在 Intune 注册的设备中安装 Configuration Manager 客户端。</span><span class="sxs-lookup"><span data-stu-id="41ef8-561">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="41ef8-562"><strong>安全地Outlook适用于 iOS 和 Android 的移动设备</strong>我们可以提供指导，帮助你在组织中安全地Outlook iOS 和 Android 移动版，以确保用户已安装所有必需的应用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-562"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="41ef8-563">使用 Intune 安全地部署适用于 iOS Outlook Android 移动版的步骤取决于你的源环境。</span><span class="sxs-lookup"><span data-stu-id="41ef8-563">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="41ef8-564">它可以包括：</span><span class="sxs-lookup"><span data-stu-id="41ef8-564">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-565">通过 Apple Outlook 或 Google Play Intune 公司门户下载适用于 iOS 和 Android、Microsoft Authenticator 和 Intune 公司门户 应用的应用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-565">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-566">提供有关设置的指导：</span><span class="sxs-lookup"><span data-stu-id="41ef8-566">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-567">适用于 iOS Outlook Android、Microsoft Authenticator 和 Intune 公司门户 Intune 的应用部署。</span><span class="sxs-lookup"><span data-stu-id="41ef8-567">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-568">应用保护策略。</span><span class="sxs-lookup"><span data-stu-id="41ef8-568">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-569">条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="41ef8-569">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-570">应用配置策略。</span><span class="sxs-lookup"><span data-stu-id="41ef8-570">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="41ef8-571">在规划使用 Intune 部署无线网络和 VPN 配置文件时，IT 管理员需要具有已在生产环境中工作的现有证书颁发机构、无线网络和 VPN 基础结构。</span><span class="sxs-lookup"><span data-stu-id="41ef8-571">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="41ef8-572"><strong>注意</strong>：FastTrack 服务权益不包括有关为 Intune 设置或配置证书颁发机构、无线网络、VPN 基础结构或 Apple MDM 推送证书的帮助。</span><span class="sxs-lookup"><span data-stu-id="41ef8-572"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="41ef8-573"><strong>注意</strong>：FastTrack 服务权益不包括有关将配置管理器站点服务器或配置管理器客户端设置或升级到支持云附加所需的最低要求的帮助。</span><span class="sxs-lookup"><span data-stu-id="41ef8-573"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="41ef8-574">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> 以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="41ef8-574">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="41ef8-575"><strong>Intune 与 Microsoft Defender for Endpoint 集成</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-575"><strong>Intune integrated with Microsoft Defender for Endpoint</strong></span></span> 
 
  <span data-ttu-id="41ef8-576"><strong>注意</strong>：我们协助将 Intune 与 Microsoft Defender for Endpoint 集成，并基于其风险级别评估Windows 10设备合规性策略。</span><span class="sxs-lookup"><span data-stu-id="41ef8-576"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender for Endpoint and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="41ef8-577">我们不提供有关购买、许可或激活的帮助。</span><span class="sxs-lookup"><span data-stu-id="41ef8-577">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="41ef8-578">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> 以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="41ef8-578">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="41ef8-579"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-579"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="41ef8-580">IT 管理员负责通过让硬件供应商代表他们上载其硬件 ID 或自己将其上载到 Windows Autopilot 服务中来向其组织注册设备。</span><span class="sxs-lookup"><span data-stu-id="41ef8-580">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="41ef8-581">Office 365</span><span class="sxs-lookup"><span data-stu-id="41ef8-581">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="41ef8-582"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-582"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="41ef8-583"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-583"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="41ef8-584"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-584"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="41ef8-585"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-585"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-586">对于 Exchange Online，我们会全程指导你，直到你的组织可以使用电子邮件为止。</span><span class="sxs-lookup"><span data-stu-id="41ef8-586">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="41ef8-587">具体步骤取决于源环境和电子邮件迁移计划。</span><span class="sxs-lookup"><span data-stu-id="41ef8-587">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="41ef8-588">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-588">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-589">为 Office 365 中验证的所有启用邮件的域设置 Exchange Online Protection (EOP) 功能。</span><span class="sxs-lookup"><span data-stu-id="41ef8-589">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-590">将邮件交换 (MX 记录) 指向Office 365。</span><span class="sxs-lookup"><span data-stu-id="41ef8-590">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-591">如果 Microsoft Defender 是订阅Office 365一部分，则设置 Microsoft Defender for Office 365 功能。</span><span class="sxs-lookup"><span data-stu-id="41ef8-591">Setting up the Microsoft Defender for Office 365 feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="41ef8-592">有关详细信息，请参阅此表<strong>的 Microsoft Defender Office 365</strong>部分。</span><span class="sxs-lookup"><span data-stu-id="41ef8-592">For more information, see the <strong>Microsoft Defender for Office 365</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-p127">为在 Office 365 中验证的所有已启用邮件的域设置数据丢失防护 (DLP) 功能，将其作为订阅服务的一部分。这可在 MX 记录指向 Office 365 后完成。</span><span class="sxs-lookup"><span data-stu-id="41ef8-p127">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="41ef8-p128">为在 Office 365 中验证的所有已启用邮件的域设置 Office 365 邮件加密 (OME) ，将其作为订阅服务的一部分。这可在 MX 记录指向 Office 365 后完成。</span><span class="sxs-lookup"><span data-stu-id="41ef8-p128">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="41ef8-597">
  <strong>注意：</strong>邮箱复制服务 (MRS) 尝试将信息权限托管 (IRM) 电子邮件从本地邮箱迁移到相应的 Exchange Online 邮箱。</span><span class="sxs-lookup"><span data-stu-id="41ef8-597">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="41ef8-598">可读取受保护内容迁移后的能力取决于客户映射和将 Active Directory Rights Managed Services (AD RMS) 模板复制到 Azure Rights Management Service (Azure RMS)。</span><span class="sxs-lookup"><span data-stu-id="41ef8-598">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="41ef8-599">配置防火墙端口。</span><span class="sxs-lookup"><span data-stu-id="41ef8-599">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-600">根据需要设置 DNS，包括所需的自动发现、发件人策略框架 (SPF) 、域密钥识别邮件 (DKIM) 、基于域的邮件身份验证、报告和一致性 (DMARC) 和 MX 记录 () 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-600">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-601">设置源邮件环境和 Exchange Online 之间的电子邮件流（根据需要）。</span><span class="sxs-lookup"><span data-stu-id="41ef8-601">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-602">执行从源邮件环境到 Office 365 的邮件迁移。</span><span class="sxs-lookup"><span data-stu-id="41ef8-602">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-603">配置邮箱客户端（Outlook for Windows、Outlook 网页版以及 Outlook for iOS 和 Outlook for Android）。</span><span class="sxs-lookup"><span data-stu-id="41ef8-603">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="41ef8-604">
  <strong>数据迁移</strong>  </span><span class="sxs-lookup"><span data-stu-id="41ef8-604">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="41ef8-605">有关使用 FastTrack 权益将数据迁移到 Office 365 的信息，请参阅数据<a href="https://docs.microsoft.com/fasttrack/data-migration">迁移</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-605">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="41ef8-606">源环境必须具有以下最低级别之一：</span><span class="sxs-lookup"><span data-stu-id="41ef8-606">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-607">具有 Exchange Server 2003 前向的单个或多个 Exchange 组织。</span><span class="sxs-lookup"><span data-stu-id="41ef8-607">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-608">一个支持 Internet 邮件访问协议 (IMAP) 的电子邮件环境。</span><span class="sxs-lookup"><span data-stu-id="41ef8-608">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-609">单个 G 套件环境（仅限 Gmail、联系人和日历）。</span><span class="sxs-lookup"><span data-stu-id="41ef8-609">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-610">有关多地理位置功能的信息，请参阅多地理位置功能<a href="https://go.microsoft.com/fwlink/?linkid=872776">Exchange Online。</a></span><span class="sxs-lookup"><span data-stu-id="41ef8-610">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="41ef8-611">Project for Office 365、Outlook for Windows、Outlook for iOS 和 Android、OneDrive for Business 同步客户端、Power BI Desktop 和 Skype for Business 等联机客户端软件必须处于最低级别，如 Microsoft 365 Office 的系统<a href="https://go.microsoft.com/fwlink/?LinkID=723597">要求</a>中的定义。</span><span class="sxs-lookup"><span data-stu-id="41ef8-611">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>

<td><span data-ttu-id="41ef8-612"><strong>Microsoft Defender for Office 365</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-612"><strong>Microsoft Defender for Office 365</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-613">有关详细信息，请参阅安全与Office 365中的 Microsoft <strong>Defender</strong> <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">for Office 365。</a></span><span class="sxs-lookup"><span data-stu-id="41ef8-613">For more information, see <strong>Microsoft Defender for Office 365</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>  
</td>
<td></td>
</tr>


<tr class="even">
<td><span data-ttu-id="41ef8-614"><strong>Microsoft 信息管控</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-614"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-615">有关详细信息，请参阅安全与 <strong> 合规中的 Microsoft</strong> <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">信息治理</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-615">For more information, see <strong> Microsoft Information Governance</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span> 

</td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="41ef8-616"><strong>Microsoft 信息保护</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-616"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  
<span data-ttu-id="41ef8-617">有关详细信息，请参阅安全与 <strong>合规 </strong> 中的 Microsoft <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">信息保护</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-617">For more information, see <strong>Microsoft Information Protection </strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>

</td>
<td>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="41ef8-618"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-618"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-619">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-619">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-620">确认支持 Exchange Online、SharePoint Online、Office 365 组和 Azure AD 的最低Teams。</span><span class="sxs-lookup"><span data-stu-id="41ef8-620">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-621">配置防火墙端口。</span><span class="sxs-lookup"><span data-stu-id="41ef8-621">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-622">设置 DNS。</span><span class="sxs-lookup"><span data-stu-id="41ef8-622">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-623">确认是否已在 Office 365 租户上启用 Teams。</span><span class="sxs-lookup"><span data-stu-id="41ef8-623">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-624">启用或禁用用户许可证。</span><span class="sxs-lookup"><span data-stu-id="41ef8-624">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-625">网络评估Teams：</span><span class="sxs-lookup"><span data-stu-id="41ef8-625">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-626">端口和终结点检查。</span><span class="sxs-lookup"><span data-stu-id="41ef8-626">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-627">连接质量检查。</span><span class="sxs-lookup"><span data-stu-id="41ef8-627">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-628">带宽预估。</span><span class="sxs-lookup"><span data-stu-id="41ef8-628">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="41ef8-629">为 Teams Web (Teams、Teams 桌面应用和 Teams for iOS 和 Android 应用配置) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-629">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="41ef8-630">如果适用，我们还提供有关：</span><span class="sxs-lookup"><span data-stu-id="41ef8-630">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-631">Microsoft Teams会议室设备：</span><span class="sxs-lookup"><span data-stu-id="41ef8-631">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="41ef8-632">创建 <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams 设备目录</a>中所列支持的电话和会议室设备所需的在线帐户。</span><span class="sxs-lookup"><span data-stu-id="41ef8-632">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-633">远程协助通过认证的设备进行Microsoft Teams 会议室配置。</span><span class="sxs-lookup"><span data-stu-id="41ef8-633">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-634">启用音频会议：</span><span class="sxs-lookup"><span data-stu-id="41ef8-634">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="41ef8-635">会议桥默认设置的组织设置。</span><span class="sxs-lookup"><span data-stu-id="41ef8-635">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-636">向许可用户分配会议桥。</span><span class="sxs-lookup"><span data-stu-id="41ef8-636">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="41ef8-637">电话系统：</span><span class="sxs-lookup"><span data-stu-id="41ef8-637">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-638">组织设置云语音默认设置。</span><span class="sxs-lookup"><span data-stu-id="41ef8-638">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-639">通话套餐指南 (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">可用市场) ：</a></span><span class="sxs-lookup"><span data-stu-id="41ef8-639">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-640">向许可用户分配号码。</span><span class="sxs-lookup"><span data-stu-id="41ef8-640">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-641">通过用户界面 (UI) 进行本地号码端口定位的指南（最多到 999）。</span><span class="sxs-lookup"><span data-stu-id="41ef8-641">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-642">超过 999 的本地号码端口定位服务请求 (SR) 支持。</span><span class="sxs-lookup"><span data-stu-id="41ef8-642">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="41ef8-643">直接路由指南：</span><span class="sxs-lookup"><span data-stu-id="41ef8-643">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-644">针对合作伙伴托管方案或客户部署方案的直接路由设计（最多 10 个站点）的组织设置指南。</span><span class="sxs-lookup"><span data-stu-id="41ef8-644">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="41ef8-645">会话边界控制器 (SBC) 配置检查。</span><span class="sxs-lookup"><span data-stu-id="41ef8-645">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="41ef8-646">拨号计划配置的远程协助。</span><span class="sxs-lookup"><span data-stu-id="41ef8-646">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="41ef8-647">语音路由配置。</span><span class="sxs-lookup"><span data-stu-id="41ef8-647">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="41ef8-648">媒体旁路和本地媒体优化。</span><span class="sxs-lookup"><span data-stu-id="41ef8-648">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="41ef8-649">启用 Teams 实时事件。</span><span class="sxs-lookup"><span data-stu-id="41ef8-649">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-650">组织设置和集成到 Microsoft Stream。</span><span class="sxs-lookup"><span data-stu-id="41ef8-650">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-651">转换Skype for Business Teams指南。</span><span class="sxs-lookup"><span data-stu-id="41ef8-651">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="41ef8-652">在 Azure AD 中为用户启用Office 365。</span><span class="sxs-lookup"><span data-stu-id="41ef8-652">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-653">对 SharePoint Online 启用的用户。</span><span class="sxs-lookup"><span data-stu-id="41ef8-653">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-654">Exchange混合配置 (中联机和本地Exchange邮箱) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-654">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-655">针对 Office 365 组启用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-655">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="41ef8-656">
  <strong>注意：</strong>如果未为用户分配和启用 SharePoint Online 许可证，他们将不会OneDrive for Business存储空间Office 365。</span><span class="sxs-lookup"><span data-stu-id="41ef8-656">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="41ef8-657">文件共享继续在频道中工作，但如果没有在频道中存储的 OneDrive for Business，用户Office 365。</span><span class="sxs-lookup"><span data-stu-id="41ef8-657">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="41ef8-658">Teams不支持SharePoint本地部署。</span><span class="sxs-lookup"><span data-stu-id="41ef8-658">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="41ef8-659">
  <strong>注意：</strong>理想的状态是所有用户的邮箱都位于Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="41ef8-659">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="41ef8-660">拥有托管在本地的邮箱的用户必须通过 Azure AD Office 365其标识同步到 连接。</span><span class="sxs-lookup"><span data-stu-id="41ef8-660">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="41ef8-661">对于这些Exchange，如果用户的邮箱位于本地，则用户无法添加或配置连接器。</span><span class="sxs-lookup"><span data-stu-id="41ef8-661">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="41ef8-662">可以从 <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> 下载 Microsoft Teams Windows 和 Mac 桌面客户端的安装程序。</span><span class="sxs-lookup"><span data-stu-id="41ef8-662">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>

<tr class="even">
<td><span data-ttu-id="41ef8-663"><strong>iOS 和 Android 版 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-663"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-664">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-664">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-665">从 Apple App Store 和 Google Play 下载 Outlook for iOS 和 Outlook for Android。</span><span class="sxs-lookup"><span data-stu-id="41ef8-665">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-666">配置帐户和访问 Exchange Online 邮箱。</span><span class="sxs-lookup"><span data-stu-id="41ef8-666">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-667">保护Outlook移动设备 (请参阅在 Exchange Online 中保护<a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">适用于 iOS Outlook Android</a>) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-667">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="41ef8-668">在 Azure AD 中为用户启用Office 365。</span><span class="sxs-lookup"><span data-stu-id="41ef8-668">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-669">配置了 Exchange Online 并分配了许可证。</span><span class="sxs-lookup"><span data-stu-id="41ef8-669">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="41ef8-670"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-670"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-671">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-671">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-672">分配 Power BI 许可证。</span><span class="sxs-lookup"><span data-stu-id="41ef8-672">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-673">部署 Power BI Desktop 应用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-673">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="41ef8-674">联机客户端软件（如 Power BI Desktop）必须处于最低级别，如 Microsoft 365 和 Office 的系统<a href="https://go.microsoft.com/fwlink/?LinkID=723597">要求中的定义</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-674">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="41ef8-675"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-675"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-676">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-676">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-677">验证 Project Online 依赖的基本 SharePoint 功能。</span><span class="sxs-lookup"><span data-stu-id="41ef8-677">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-678">向你的租户添加 Project Online 服务（包括向用户添加订阅）。</span><span class="sxs-lookup"><span data-stu-id="41ef8-678">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-679">设置企业资源池 (ERP)。</span><span class="sxs-lookup"><span data-stu-id="41ef8-679">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-680">创建你的首个项目。</span><span class="sxs-lookup"><span data-stu-id="41ef8-680">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="41ef8-681">联机客户端软件（如 Project for Office 365）必须处于最低级别，如 Microsoft 365 和 Office 的系统<a href="https://go.microsoft.com/fwlink/?LinkID=723597">要求中的定义</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-681">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="41ef8-682"><strong>Project Online Professional 和 高级版</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-682"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-683">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-683">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-684">解决部署问题。</span><span class="sxs-lookup"><span data-stu-id="41ef8-684">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-685">使用 Microsoft 365 管理中心和 Windows PowerShell 分配最终用户许可证。</span><span class="sxs-lookup"><span data-stu-id="41ef8-685">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-686">使用即点即用从 Office 365 门户安装 Project Online 桌面客户端。</span><span class="sxs-lookup"><span data-stu-id="41ef8-686">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-687">使用 Office 365 部署工具配置更新设置。</span><span class="sxs-lookup"><span data-stu-id="41ef8-687">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-688">为 Project Online 桌面客户端 设置一个现场分发服务器，包括帮助创建 configuration.xml 文件以与 Office 365 部署工具一起使用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-688">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-689">将 Project Online 桌面客户端 连接到 Project Online Professional 或 Project Online 高级版。</span><span class="sxs-lookup"><span data-stu-id="41ef8-689">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="41ef8-690">联机客户端软件（如 Project for Office 365）必须处于最低级别，如 Microsoft 365 和 Office 的系统<a href="https://go.microsoft.com/fwlink/?LinkID=723597">要求中的定义</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-690">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="41ef8-691"><strong>SharePoint Online 和 OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-691"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-692">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-692">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-693">设置 DNS。</span><span class="sxs-lookup"><span data-stu-id="41ef8-693">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-694">配置防火墙端口。</span><span class="sxs-lookup"><span data-stu-id="41ef8-694">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-695">设置用户和许可证。</span><span class="sxs-lookup"><span data-stu-id="41ef8-695">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="41ef8-696">为你的 SharePoint Online 管理员启用站点创建。</span><span class="sxs-lookup"><span data-stu-id="41ef8-696">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="41ef8-697">规划网站集。</span><span class="sxs-lookup"><span data-stu-id="41ef8-697">Planning site collections.</span></span></li>
<li><span data-ttu-id="41ef8-698">保护内容安全和管理权限。</span><span class="sxs-lookup"><span data-stu-id="41ef8-698">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="41ef8-699">配置 SharePoint Online 功能。</span><span class="sxs-lookup"><span data-stu-id="41ef8-699">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="41ef8-700">配置 SharePoint 混合功能，如混合搜索、混合网站、混合分类、内容类型、混合自助式网站创建（仅适用于 SharePoint Server 2013）、扩展的应用启动器、混合 OneDrive for Business 和 Extranet 网站。</span><span class="sxs-lookup"><span data-stu-id="41ef8-700">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-701">迁移方法。</span><span class="sxs-lookup"><span data-stu-id="41ef8-701">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="41ef8-702">根据你的 OneDrive for Business 版本，SharePoint其他指南，例如：</span><span class="sxs-lookup"><span data-stu-id="41ef8-702">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-703">确定集成选项并查看本地和联机网络基础结构和带宽。</span><span class="sxs-lookup"><span data-stu-id="41ef8-703">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-704">安装 SharePoint Online 2013 SP1 (（如果适用) ，规划和实现同步和标识要求，并确定 OneDrive for Business 客户端。</span><span class="sxs-lookup"><span data-stu-id="41ef8-704">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-705">规划和实现针对所有用户的单个推出 (或分阶段推出) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-705">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-706">分配许可证、将"我的网站"和个人文档库重定向到适用于 SharePoint Online 2013) 的 Office 365 (，设置访问群体以控制对适用于 SharePoint Online 2013) 的 OneDrive (的访问。</span><span class="sxs-lookup"><span data-stu-id="41ef8-706">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="41ef8-707">将已知文件夹重定向或移动到OneDrive。</span><span class="sxs-lookup"><span data-stu-id="41ef8-707">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="41ef8-708">部署OneDrive for Business客户端同步。</span><span class="sxs-lookup"><span data-stu-id="41ef8-708">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="41ef8-709">
  <strong>数据迁移</strong>  </span><span class="sxs-lookup"><span data-stu-id="41ef8-709">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="41ef8-710">有关使用 FastTrack 权益将数据迁移到 Office 365 的信息，请参阅数据<a href="https://docs.microsoft.com/fasttrack/data-migration">迁移</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-710">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="41ef8-711"><strong>对于SharePoint混合：</strong>  
</span><span class="sxs-lookup"><span data-stu-id="41ef8-711"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="41ef8-712">SharePoint配置包括配置混合搜索、网站、分类、内容类型、OneDrive for Business、扩展的应用启动器、Extranet 网站以及从本地连接到单个目标 SharePoint Online 环境的自助式网站创建。</span><span class="sxs-lookup"><span data-stu-id="41ef8-712">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="41ef8-713">
  <strong>注意：</strong>在 2013 年 10 月运行本地服务器时，自助式网站创建SharePoint范围内。</span><span class="sxs-lookup"><span data-stu-id="41ef8-713">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="41ef8-714">若要SharePoint混合环境，您必须具有以下本地 SharePoint Server 环境之一：2013、2016 或 2019。</span><span class="sxs-lookup"><span data-stu-id="41ef8-714">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="41ef8-715">
  <strong>注意：</strong>未将本地SharePoint环境升级到 SharePoint Server。</span><span class="sxs-lookup"><span data-stu-id="41ef8-715">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="41ef8-716">请联系 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴</a> 寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="41ef8-716">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="41ef8-717">有关详细信息，请参阅混合<a href="https://go.microsoft.com/fwlink/?linkid=853548">功能的最低公共SharePoint级别</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="41ef8-717">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="41ef8-718">
  <strong>注意：</strong>有关多地理位置功能的信息，请参阅 OneDrive 和 SharePoint Online 中的多<a href="https://go.microsoft.com/fwlink/?linkid=831056">地理位置Office 365。</a><em></em>  </span><span class="sxs-lookup"><span data-stu-id="41ef8-718">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="41ef8-719"><strong>Yammer 企业版</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-719"><strong>Yammer Enterprise</strong></span></span></td>
<td>
<span data-ttu-id="41ef8-720">我们提供启用 Yammer Enterprise 服务的远程指导。</span><span class="sxs-lookup"><span data-stu-id="41ef8-720">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</td>
<td><span data-ttu-id="41ef8-721">联机客户端软件必须处于最低级别，如 Microsoft 365 和 Office 的系统<a href="https://go.microsoft.com/fwlink/?LinkID=723597">要求中定义</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-721">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="41ef8-722">企业移动性 + 安全性</span><span class="sxs-lookup"><span data-stu-id="41ef8-722">Enterprise Mobility + Security</span></span> 

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="41ef8-723"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-723"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="41ef8-724"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-724"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="41ef8-725"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-725"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="41ef8-726"><strong>Azure Active Directory (Azure AD) 和 Azure AD 高级版</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-726"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-727">有关详细信息，请参阅安全与Azure Active Directory (中的 azure AD) 和<strong>Azure AD</strong> <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">高级版。</a></span><span class="sxs-lookup"><span data-stu-id="41ef8-727">For more information, see <strong> Azure Active Directory (Azure AD) and Azure AD Premium</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="41ef8-728"><strong>Azure 信息保护 </strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-728"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="41ef8-729">有关 Azure 信息保护详细信息，请参阅 <strong>安全</strong> 与合规中的 Microsoft <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> 信息保护。</span><span class="sxs-lookup"><span data-stu-id="41ef8-729">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="41ef8-730"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-730"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-731">有关详细信息，<strong>请参阅安全与</strong>Microsoft Intune<a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">中的"安全与合规"。</a></span><span class="sxs-lookup"><span data-stu-id="41ef8-731">For more information, see <strong> Microsoft Intune</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span>
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="41ef8-732">Windows 10</span><span class="sxs-lookup"><span data-stu-id="41ef8-732">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="41ef8-733"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-733"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="41ef8-734"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-734"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="41ef8-735"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-735"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="41ef8-736"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-736"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-737">我们提供有关从 Windows 7 专业版 Windows 8.1 Professional 升级到 Windows 10 企业版 的指南。</span><span class="sxs-lookup"><span data-stu-id="41ef8-737">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="41ef8-738">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-738">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-739">了解Windows 10意图。</span><span class="sxs-lookup"><span data-stu-id="41ef8-739">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-740">评估源环境和要求 (确保Microsoft Endpoint Configuration Manager升级到所需级别，以支持Windows 10部署) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-740">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-741">使用 Windows 10 企业版 或 Microsoft 365 应用版 部署Microsoft Endpoint Configuration Manager和Microsoft 365。</span><span class="sxs-lookup"><span data-stu-id="41ef8-741">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-742">推荐用于评估应用Windows 10选项。</span><span class="sxs-lookup"><span data-stu-id="41ef8-742">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-743">通过创建桌面分析部署计划，支持使用桌面分析和指导。</span><span class="sxs-lookup"><span data-stu-id="41ef8-743">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-744">Microsoft 365 应用版 Configuration Manager 中的 Office 365 准备情况仪表板或独立的准备情况仪表板进行兼容性评估Toolkit Office部署Microsoft 365 应用版。</span><span class="sxs-lookup"><span data-stu-id="41ef8-744">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-745">创建修正清单，检查需要执行哪些操作，使源环境达到成功部署的最低要求。</span><span class="sxs-lookup"><span data-stu-id="41ef8-745">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-746">为现有设备提供升级指南，Windows 10 企业版满足所需设备硬件要求时进行升级。</span><span class="sxs-lookup"><span data-stu-id="41ef8-746">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-747">提供升级指南以支持现有部署运动。</span><span class="sxs-lookup"><span data-stu-id="41ef8-747">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="41ef8-748">FastTrack 推荐并提供有关就地升级到 Windows 10 的指南。</span><span class="sxs-lookup"><span data-stu-id="41ef8-748">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="41ef8-749">指南还可用于 Windows 干净图片安装和 Windows Autopilot 部署方案。</span><span class="sxs-lookup"><span data-stu-id="41ef8-749">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-750">在Microsoft 365 应用版部署中，使用 Configuration Manager 部署Windows 10部署。</span><span class="sxs-lookup"><span data-stu-id="41ef8-750">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="41ef8-751">提供指导，帮助你的组织使用现有的 Configuration Manager Windows 10 企业版Microsoft 365 应用版保持最新状态Microsoft 365。</span><span class="sxs-lookup"><span data-stu-id="41ef8-751">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="41ef8-752">
  
<strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="41ef8-752">
  
<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="41ef8-753">将 Configuration Manager 升级到当前分支。</span><span class="sxs-lookup"><span data-stu-id="41ef8-753">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-754">创建适用于 Windows 10 部署的自定义映像。</span><span class="sxs-lookup"><span data-stu-id="41ef8-754">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-755">创建和支持 Windows 10 部署的部署脚本。</span><span class="sxs-lookup"><span data-stu-id="41ef8-755">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-756">将 Windows 10 系统从 BIOS 转换为统一可扩展固件接口 (UEFI)。</span><span class="sxs-lookup"><span data-stu-id="41ef8-756">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-757">启用 Windows 10 安全功能。</span><span class="sxs-lookup"><span data-stu-id="41ef8-757">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-758">配置用于启动前执行环境 (PXE) 启动的 Windows 部署服务 (WDS)。</span><span class="sxs-lookup"><span data-stu-id="41ef8-758">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-759">使用 Microsoft 部署工具包 (MDT) 捕获和部署 Windows 10 映像。</span><span class="sxs-lookup"><span data-stu-id="41ef8-759">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-760">使用用户状态迁移工具 (USMT)。</span><span class="sxs-lookup"><span data-stu-id="41ef8-760">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="41ef8-761">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="41ef8-761">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="41ef8-762">要升级电脑，必须满足以下要求：</span><span class="sxs-lookup"><span data-stu-id="41ef8-762">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-763">源操作系统：Windows 7 企业版、Professional、Windows 8.1 企业版或Professional。</span><span class="sxs-lookup"><span data-stu-id="41ef8-763">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-764">设备：台式机、笔记本或平板电脑设备。</span><span class="sxs-lookup"><span data-stu-id="41ef8-764">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-765">目标操作系统：窗口 10 Enterprise。</span><span class="sxs-lookup"><span data-stu-id="41ef8-765">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="41ef8-766">若要升级基础结构，必须满足以下要求：</span><span class="sxs-lookup"><span data-stu-id="41ef8-766">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-767">Microsoft Endpoint Configuration Manager。</span><span class="sxs-lookup"><span data-stu-id="41ef8-767">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-768">配置管理器版本必须受目标Windows 10支持。</span><span class="sxs-lookup"><span data-stu-id="41ef8-768">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="41ef8-769">有关详细信息，请参阅 <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager 中的 Windows 10 支持</a>中的 Configuration Manager 支持表格。</span><span class="sxs-lookup"><span data-stu-id="41ef8-769">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="41ef8-770"><strong>Microsoft Defender for Endpoint</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-770"><strong>Microsoft Defender for Endpoint</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-771">有关详细信息，请参阅安全与合规中的<strong>Microsoft Defender for Endpoint。</strong> <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"></a></span><span class="sxs-lookup"><span data-stu-id="41ef8-771">For more information, see <strong> Microsoft Defender for Endpoint</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance</a>.</span></span></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="41ef8-772">Windows 虚拟桌面</span><span class="sxs-lookup"><span data-stu-id="41ef8-772">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="41ef8-773"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-773"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="41ef8-774"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-774"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="41ef8-775"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-775"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="41ef8-776"><strong>Windows 虚拟桌面</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-776"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="41ef8-777">我们提供载入虚拟桌面的部署Windows桌面 (桌面应用虚拟化服务) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-777">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="41ef8-778">Windows虚拟桌面利用Windows 10会话体验，并针对 Microsoft 365 应用版 进行了优化Enterprise集成的安全性和管理，Microsoft 365。</span><span class="sxs-lookup"><span data-stu-id="41ef8-778">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="41ef8-779">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="41ef8-779">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="41ef8-780">通过Windows部署虚拟桌面Windows 10 企业版，Microsoft 365 应用版Enterprise部署虚拟桌面环境：</span><span class="sxs-lookup"><span data-stu-id="41ef8-780">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="41ef8-781">Azure Marketplace 映像。</span><span class="sxs-lookup"><span data-stu-id="41ef8-781">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="41ef8-782">共享图像。</span><span class="sxs-lookup"><span data-stu-id="41ef8-782">Shared image.</span></span></li>
<li><span data-ttu-id="41ef8-783">Office部署Toolkit (ODT) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-783">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="41ef8-784">配置 FSLogix：</span><span class="sxs-lookup"><span data-stu-id="41ef8-784">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="41ef8-785">使用配置文件容器部署 FSLogix 代理。</span><span class="sxs-lookup"><span data-stu-id="41ef8-785">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="41ef8-786">使用容器部署 FSLogix Office代理。</span><span class="sxs-lookup"><span data-stu-id="41ef8-786">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="41ef8-787">使用内容排除项配置 FSLogix 文件夹。</span><span class="sxs-lookup"><span data-stu-id="41ef8-787">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="41ef8-788">部署Microsoft Edge。</span><span class="sxs-lookup"><span data-stu-id="41ef8-788">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="41ef8-789">部署Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="41ef8-789">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="41ef8-790">使用虚拟Windows客户端进行连接。</span><span class="sxs-lookup"><span data-stu-id="41ef8-790">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="41ef8-791">

<strong>以下内容超出范围</strong>
</span><span class="sxs-lookup"><span data-stu-id="41ef8-791">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="41ef8-792">Project虚拟桌面部署Windows管理。</span><span class="sxs-lookup"><span data-stu-id="41ef8-792">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="41ef8-793">第三方应用虚拟化和部署。</span><span class="sxs-lookup"><span data-stu-id="41ef8-793">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="41ef8-794">自定义图像。</span><span class="sxs-lookup"><span data-stu-id="41ef8-794">Custom images.</span></span></li>
<li><span data-ttu-id="41ef8-795">涉及 VMware 和 Citrix 的迁移和方案。</span><span class="sxs-lookup"><span data-stu-id="41ef8-795">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="41ef8-796">Linux 方案。</span><span class="sxs-lookup"><span data-stu-id="41ef8-796">Linux scenarios.</span></span></li>
<li><span data-ttu-id="41ef8-797">用户配置文件的转换或迁移。</span><span class="sxs-lookup"><span data-stu-id="41ef8-797">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="41ef8-798">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="41ef8-798">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="41ef8-799">你应该已经拥有以下内容：</span><span class="sxs-lookup"><span data-stu-id="41ef8-799">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="41ef8-800"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows虚拟桌面许可要求</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-800"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="41ef8-801">Azure 网络：</span><span class="sxs-lookup"><span data-stu-id="41ef8-801">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="41ef8-802">使用 VNET (虚拟网络) 和子网。</span><span class="sxs-lookup"><span data-stu-id="41ef8-802">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="41ef8-803">防火墙和网络安全组。</span><span class="sxs-lookup"><span data-stu-id="41ef8-803">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="41ef8-804">VPN 和 ExpressRoute。</span><span class="sxs-lookup"><span data-stu-id="41ef8-804">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="41ef8-805">从本地路由到 Azure。</span><span class="sxs-lookup"><span data-stu-id="41ef8-805">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="41ef8-806">允许连接到虚拟桌面Windows防火墙规则。</span><span class="sxs-lookup"><span data-stu-id="41ef8-806">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="41ef8-807">有关详细信息，请参阅支持的 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> 远程桌面客户端</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-807">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="41ef8-808">Azure AD 常规设置：</span><span class="sxs-lookup"><span data-stu-id="41ef8-808">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="41ef8-809">标识 <i> 策略 (只能使用以下三个选项之一) ：</i>
</span><span class="sxs-lookup"><span data-stu-id="41ef8-809">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="41ef8-810">Azure 中具有 Azure AD 连接 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="41ef8-810">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="41ef8-811">通过 VPN 或 ExpressRoute 在本地连接 Azure AD 的 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="41ef8-811">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="41ef8-812">Active Directory 域服务 (AD DS) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-812">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="41ef8-813">应用保证</span><span class="sxs-lookup"><span data-stu-id="41ef8-813">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="41ef8-814"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-814"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="41ef8-815"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-815"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="41ef8-816"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-816"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="41ef8-817"><strong>应用保证</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-817"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="41ef8-818">应用保证是一项旨在解决与应用兼容性Windows 10 Microsoft 365 应用版的问题的服务。</span><span class="sxs-lookup"><span data-stu-id="41ef8-818">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="41ef8-819">当你请求应用保证服务时，我们会与你在符合条件的订阅中一起处理有效的应用问题，无需额外付费。</span><span class="sxs-lookup"><span data-stu-id="41ef8-819">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="41ef8-820">我们还为在部署虚拟桌面和 Windows时面临兼容性问题的客户提供指导Microsoft Edge并尽一切努力解决兼容性问题。</span><span class="sxs-lookup"><span data-stu-id="41ef8-820">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="41ef8-821">我们为以下 Microsoft 产品上部署的应用提供修正帮助：</span><span class="sxs-lookup"><span data-stu-id="41ef8-821">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="41ef8-822"><strong>Windows 10 (</strong>包括 ARM64 设备) </span><span class="sxs-lookup"><span data-stu-id="41ef8-822"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="41ef8-823"><strong>Microsoft 365 应用版</strong>  </span><span class="sxs-lookup"><span data-stu-id="41ef8-823"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="41ef8-824"><strong>Microsoft Edge -</strong>有关部署指南，请参阅<a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">部署Microsoft Edge概述</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-824"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-825"><strong>Windows虚拟桌面</strong> -有关详细信息，请参阅什么是虚拟<a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows？</a>和Windows 10 企业版<a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">会话常见问题解答</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-825"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="41ef8-826">

<strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="41ef8-826">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="41ef8-827">用于确定在 Windows 10 和 Microsoft 365 应用版上是否正常运作的应用清单和测试。</span><span class="sxs-lookup"><span data-stu-id="41ef8-827">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="41ef8-828">有关此过程的更多指导，请访问<a href="https://go.microsoft.com/fwlink/?linkid=2080140">桌面部署中心</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-828">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="41ef8-829">如果对深入升级就绪性评估感兴趣，请填写<a href="https://go.microsoft.com/fwlink/?linkid=2053818">新式桌面评估的客户请求</a>表单。</span><span class="sxs-lookup"><span data-stu-id="41ef8-829">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="41ef8-830">研究 Windows 10 兼容性和支持语句的第三方 ISV 应用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-830">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="41ef8-831">有关详细信息，请参阅<a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">桌面分析</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-831">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="41ef8-832">仅限应用打包的服务。</span><span class="sxs-lookup"><span data-stu-id="41ef8-832">App packaging-only services.</span></span> <span data-ttu-id="41ef8-833">但是，应用保证团队会打包我们已为 Windows 10 修正的应用，以确保可以在客户环境中部署。</span><span class="sxs-lookup"><span data-stu-id="41ef8-833">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="41ef8-834">

<strong>客户职责包括</strong>  
</span><span class="sxs-lookup"><span data-stu-id="41ef8-834">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="41ef8-835">创建应用清单。</span><span class="sxs-lookup"><span data-stu-id="41ef8-835">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="41ef8-836">验证 Windows 10 和 Microsoft 365 应用版上的应用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-836">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="41ef8-837">
<strong>注意：</strong>  Microsoft 无法对源代码进行更改。</span><span class="sxs-lookup"><span data-stu-id="41ef8-837">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="41ef8-838">但是，如果可提供应用的源代码，则应用保证团队可向应用开发人员提供指导。</span><span class="sxs-lookup"><span data-stu-id="41ef8-838">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="41ef8-839">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="41ef8-839">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="41ef8-840"><strong>Windows 10 和 Microsoft 365 应用版</strong>
</span><span class="sxs-lookup"><span data-stu-id="41ef8-840"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="41ef8-841">在 Windows 7、Windows 8.1、Office 2010 和 Office 2013 上运行的应用也可在 Windows 10 和 Microsoft 365 应用版上运行。</span><span class="sxs-lookup"><span data-stu-id="41ef8-841">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="41ef8-842">
<strong>Windows 10 ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="41ef8-842">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="41ef8-843">在 WINDOWS 7、Office 2010 或更高版本上运行的应用也可在 ARM64 Windows 10 Microsoft 365 应用版设备上运行。</span><span class="sxs-lookup"><span data-stu-id="41ef8-843">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="41ef8-844">
  <strong>注意：</strong> 
</span><span class="sxs-lookup"><span data-stu-id="41ef8-844">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="41ef8-845">x64 (预览版 64) 预览版，适用于参与预览体验计划Windows<a href="https://insider.windows.com/">客户</a>。</span><span class="sxs-lookup"><span data-stu-id="41ef8-845">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="41ef8-846">对于 Windows使用 Windows 10 2004 (或更高版本) 的非预览体验成员客户，ARM64 Photoshop 支持使用 OpenCL 和<a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL</a>兼容包。</span><span class="sxs-lookup"><span data-stu-id="41ef8-846">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="41ef8-847">预览体验Windows计划的客户可以下载预览体验成员版本的 OpenCL 和 OpenGL 兼容包，以与其他应用一同使用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-847">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="41ef8-848">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="41ef8-848">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="41ef8-849">如果你的 Web 应用或网站在 Internet Explorer 11、受支持的 Google Chrome 版本或任何 Microsoft Edge 版本上工作，它们也将与 Microsoft Edge 一Microsoft Edge。</span><span class="sxs-lookup"><span data-stu-id="41ef8-849">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-850">随着 Web 的不断发展，请务必查看此已发布的已知网站兼容性影响更改列表，以<a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">Microsoft Edge。</a></span><span class="sxs-lookup"><span data-stu-id="41ef8-850">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="41ef8-851">
  <strong>Windows虚拟桌面</strong>  
</span><span class="sxs-lookup"><span data-stu-id="41ef8-851">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="41ef8-852">在 Windows Server 远程桌面会话主机 (RDSH) 上运行的虚拟化应用也可作为 Windows 虚拟桌面的一部分在 Windows 10 企业版多会话中运行。</span><span class="sxs-lookup"><span data-stu-id="41ef8-852">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-853">在任何 Windows 7 或 Windows 10 虚拟桌面基础结构 (VDI) 环境中运行的应用也将在 Windows 7 企业版 上运行Windows 10 企业版虚拟桌面Windows一部分。</span><span class="sxs-lookup"><span data-stu-id="41ef8-853">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-854">在 Windows 7 或 Windows 10 客户端设备中运行的应用也可作为 Windows 虚拟桌面的一部分在 Windows 7 企业版和 Windows 10 企业版上运行。</span><span class="sxs-lookup"><span data-stu-id="41ef8-854">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="41ef8-855">
  <strong>注意：Windows 10 企业版</strong>会话兼容性排除和限制包括：</span><span class="sxs-lookup"><span data-stu-id="41ef8-855">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="41ef8-856">硬件重定向受到限制。</span><span class="sxs-lookup"><span data-stu-id="41ef8-856">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-857">A/V 密集型应用可能功能受限。</span><span class="sxs-lookup"><span data-stu-id="41ef8-857">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="41ef8-858">64 位 Windows 虚拟桌面不支持 16 位应用。</span><span class="sxs-lookup"><span data-stu-id="41ef8-858">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="41ef8-859">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="41ef8-859">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="41ef8-860"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-860"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="41ef8-861"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-861"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="41ef8-862"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="41ef8-862"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="41ef8-863"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="41ef8-863"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="41ef8-864">我们提供远程部署和采用指南以及兼容性协助，用于：</span><span class="sxs-lookup"><span data-stu-id="41ef8-864">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="41ef8-865">使用 Microsoft Edge 或 Intune Windows 10 Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager部署) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-865">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-866">使用Microsoft Edge (或 Intune 应用配置以及应用策略配置) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-866">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="41ef8-867">清点可能需要在活动模式中使用Internet Explorer列表。</span><span class="sxs-lookup"><span data-stu-id="41ef8-867">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="41ef8-868">使用Internet Explorer站点列表启用Enterprise模式。</span><span class="sxs-lookup"><span data-stu-id="41ef8-868">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="41ef8-869"> (有关详细信息，请参阅 <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">吸引 FastTrack</a>) 。</span><span class="sxs-lookup"><span data-stu-id="41ef8-869">(For more information, see <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span></span> <span data-ttu-id="41ef8-870">此外，如果你有一个与 Internet Explorer 或 Google Chrome 一起工作的 Web 应用或网站，并且你遇到兼容性问题，我们会提供指导，以便无需额外付费地解决该问题。</span><span class="sxs-lookup"><span data-stu-id="41ef8-870">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="41ef8-871">若要请求应用保证的兼容性支持，请登录到 <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack 门户</a> 以启动服务活动。</span><span class="sxs-lookup"><span data-stu-id="41ef8-871">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="41ef8-872">Microsoft 搜索书签的边缘采用和配置指南的规划指南。</span><span class="sxs-lookup"><span data-stu-id="41ef8-872">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="41ef8-873">

<strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="41ef8-873">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="41ef8-874">客户的 Microsoft Edge 部署的项目管理。</span><span class="sxs-lookup"><span data-stu-id="41ef8-874">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="41ef8-875">现场支持。</span><span class="sxs-lookup"><span data-stu-id="41ef8-875">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
