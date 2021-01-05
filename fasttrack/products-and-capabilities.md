---
title: 产品和功能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/4/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: 本主题包含有关 FastTrack 支持的工作负荷方案的详细信息，以及开始之前所需的源环境预期。 根据您的当前设置，我们一起制定修正计划，使源环境达到成功载入的最低要求。
ms.openlocfilehash: 5e65d160822ed50840ecc65f484433bf0d485913
ms.sourcegitcommit: cf07b074931fd6877ba7e8938440dc7ebaf4ac69
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/04/2021
ms.locfileid: "49750097"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="2fa0d-104">产品和功能</span><span class="sxs-lookup"><span data-stu-id="2fa0d-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="2fa0d-105">FastTrack 支持的服务和方案</span><span class="sxs-lookup"><span data-stu-id="2fa0d-105">Services and scenarios supported by FastTrack</span></span>

<span data-ttu-id="2fa0d-106">本主题包含有关 FastTrack 支持的工作负荷方案的详细信息，以及开始之前所需的源环境预期。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="2fa0d-107">根据您的当前设置，我们一起制定修正计划，使源环境达到成功载入的最低要求。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="2fa0d-108">FastTrack 提供指导，帮助你首先获得所有 (通用的核心Microsoft Online Services) ，然后载入每个符合条件的服务：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="2fa0d-109">常规</span><span class="sxs-lookup"><span data-stu-id="2fa0d-109">General</span></span>](#general)
  - [<span data-ttu-id="2fa0d-110">安全性和符合性</span><span class="sxs-lookup"><span data-stu-id="2fa0d-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="2fa0d-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="2fa0d-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="2fa0d-112">企业移动性 + 安全性</span><span class="sxs-lookup"><span data-stu-id="2fa0d-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="2fa0d-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="2fa0d-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="2fa0d-114">Windows 虚拟桌面</span><span class="sxs-lookup"><span data-stu-id="2fa0d-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="2fa0d-115">应用保证</span><span class="sxs-lookup"><span data-stu-id="2fa0d-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="2fa0d-116">新版 Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="2fa0d-116">The new Microsoft Edge</span></span>](#the-new-microsoft-edge)

> [!NOTE]
> <span data-ttu-id="2fa0d-117">若要了解 Office 365 US Government 的源环境预期，请参阅 [Office 365 US Government 的源环境预期](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="2fa0d-118">常规</span><span class="sxs-lookup"><span data-stu-id="2fa0d-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2fa0d-119"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2fa0d-120"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2fa0d-121"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2fa0d-122"><strong>核心入门</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-123">我们提供有关核心载入的远程指导，其中包括服务预配、租户和标识集成。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="2fa0d-124">它还包括为载入服务（如 Exchange Online、SharePoint Online 和 Microsoft Teams）提供基础的步骤，包括有关安全性、网络连接性和合规性 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">的讨论</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="2fa0d-125">在核心载入完成后，便可以开始载入一个或多个符合条件的服务。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="2fa0d-126"></li>
</ul>  

<strong> 标识集成 </strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="2fa0d-127">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="2fa0d-128">准备本地 Active Directory 标识以同步到 Azure Active Directory (Azure AD) 包括安装和配置 Azure AD Connect (单林或多林) 以及许可 (包括基于组的许可) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="2fa0d-129">创建云标识，包括批量导入和许可，包括使用基于组的许可。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="2fa0d-130">为云旅程、密码哈希同步、传递身份验证或 Active Directory 联合身份验证服务选择和启用正确的身份验证方法 (AD FS) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="2fa0d-131">为具有单个 Active Directory 林且标识与 Azure AD Connect 工具同步的客户启用 AD FS。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="2fa0d-132">这要求Windows Server 2012 R2 Active Directory 联合身份验证服务 2.0 或更大。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="2fa0d-133">使用密码哈希同步或传递身份验证将身份验证从 AD FS 迁移到 Azure AD。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="2fa0d-134">将预集成应用 (如 Azure AD 库软件即服务 (SaaS) 应用) 从 AD FS 迁移到 Azure AD，实现单一登录 (SSO) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="2fa0d-135">从 Azure AD 库启用 SaaS 应用与 SSO 的集成。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="2fa0d-136">为预集成 SaaS 应用启用自动用户预配，如应用集成教程列表 <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list"> (仅限</a> Azure AD 库 SaaS 应用和仅) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="2fa0d-137"><strong>网络启用 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="2fa0d-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="2fa0d-138">作为 FastTrack 权益的一部分，我们建议你采用连接到云服务的最佳实践，以确保 Microsoft 365 的最高性能级别。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="2fa0d-139"><strong>Active Directory 林</strong> 这些功能林级别已设置为 Windows Server 2003 前向，具有以下林配置：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-140">单个 Active Directory 林。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-141">单一 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-142">多个 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-143">多个 Active Directory 帐户林，其中的一个林是一个含有 Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business 的集中式 Active Directory 帐户林。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-144">多个 Active Directory 帐户林，每一个都有自己的 Exchange 组织。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-145">租户配置和与 Azure Active Directory 集成所需的任务（如果需要）。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="2fa0d-146">
  <strong>重要</strong>  </span><span class="sxs-lookup"><span data-stu-id="2fa0d-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="2fa0d-147">对于多林 Active Directory 方案，如果部署了 Lync 2010、Lync 2013 或 Skype for Business，则必须将其部署在与 Exchange 相同的 Active Directory 林中。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-148">在 Exchange 多混合配置中使用多个 Exchange 组织实现多个 Active Directory 林时，不支持在源林之间 (UPN) 命名空间的共享用户主体名称。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="2fa0d-149">Exchange 组织之间的主要 SMTP 命名空间也应该进行分隔。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="2fa0d-150">有关详细信息，请参阅 <a href="https://go.microsoft.com/fwlink/?linkid=845444">具有多个 Active Directory 林的混合部署</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-151">对于所有多林配置，Active Directory 联合身份验证服务 (AD FS) 超出了范围。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="2fa0d-152">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2fa0d-153"><strong>Microsoft 365 应用版</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-154">我们提供远程部署指南，用于：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-155">解决部署问题。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-156">使用 Microsoft 365 管理中心和 Windows PowerShell 分配基于最终用户和设备的许可证。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-157">使用即点即用从 Office 365 门户安装 Microsoft 365 应用版。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-158">在 iOS 或 Android 设备上安装 Office Mobile 应用（如 Outlook Mobile、Word Mobile、Excel Mobile 和 PowerPoint Mobile）。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-159">使用 Office 365 部署工具配置更新设置。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-160">本地或云安装的选择和设置。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-161">使用 Office 自定义工具或用于配置部署包的本地 XML 创建 Office 部署工具配置 XML。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-162">使用 Microsoft Endpoint Configuration Manager 的部署，包括帮助创建 Microsoft Endpoint Configuration Manager 打包。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="2fa0d-163">此外，如果你有使用 Office 早期版本的宏或外接程序，并且你遇到兼容性问题，我们会指导你通过应用保证计划免费修复兼容性问题。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="2fa0d-164">有关详细信息， <strong>请参阅</strong> Windows <a href="#windows-10">10</a> 的应用保证部分。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="2fa0d-165">联机客户端软件必须处于 Microsoft <a href="https://go.microsoft.com/fwlink/?LinkID=723597">365</a>和 Office 的系统要求中定义的最低级别。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2fa0d-166"><strong>网络运行状况</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-167">我们提供远程指导，以便从你的环境中获取和解释关键网络连接数据，表明组织的网站如何与 Microsoft 的网络连接 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">原则保持一致</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="2fa0d-168">这突出显示了直接影响迁移速度、用户体验、服务性能和可靠性的网络分数。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="2fa0d-169">我们还指导你完成此数据突出显示的任何修正步骤，以帮助你提高网络分数。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="2fa0d-170">Microsoft 365 管理中心访问权限。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-171">需要最新版本的 Microsoft 365 应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-172">根据 Microsoft 365 管理中心预览版中的网络性能建议<a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">启用 (定位) 。 </a></span><span class="sxs-lookup"><span data-stu-id="2fa0d-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="2fa0d-173">安全性和合规性</span><span class="sxs-lookup"><span data-stu-id="2fa0d-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2fa0d-174"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2fa0d-175"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2fa0d-176"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="2fa0d-177"><strong>Azure Active Directory (Azure AD) 和 Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-178">我们针对以下方案提供用于保护云标识的远程指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="2fa0d-179">

<strong>安全的基础基础结构</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="2fa0d-180">为标识配置和启用强身份验证，包括使用 Azure 多重身份验证 (MFA)  (云仅) 、Microsoft Authenticator 应用以及 Azure MFA 和自助服务密码重置联合注册 (SSPR) 进行保护。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-181">对于非 Azure AD Premium 客户，提供了使用安全默认值保护标识的指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-182">对于 Azure AD 高级客户，提供了使用条件访问保护标识的指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-183">通过 Azure AD 密码保护检测和阻止使用弱密码。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-184">使用 Azure AD 应用程序代理保护对本地 Web 应用的远程访问。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-185">使用 Azure Identity Protection 启用基于风险的检测和修正。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-186">启用自定义登录屏幕，包括徽标、文本和具有自定义品牌的图像。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-187">使用 Azure AD B2B 安全地与来宾用户共享应用和服务。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-188">使用基于角色的访问控制 (RBAC) 内置管理角色管理 Office 365 管理员的访问权限，并减少特权管理员帐户的数量。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-189">配置混合 Azure AD 加入。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-190">配置 Azure AD 加入。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-191">
  
<strong>监视和报告</strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="2fa0d-192">使用 Azure AD Connect Health 为 AD FS、Azure AD Connect 和域控制器启用远程监视。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="2fa0d-193">
  
<strong>治理</strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="2fa0d-194">使用 Azure AD 权利管理大规模管理 Azure AD 标识和访问生命周期。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="2fa0d-195">通过 Azure AD 访问评审管理 Azure AD 组成员身份、企业应用访问权限和角色分配。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-196">查看 Azure AD 使用条款。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-197">使用 Azure AD Privileged Identity Management 管理和控制对特权管理员帐户的访问。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="2fa0d-198">
  
<strong>自动化和效率 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="2fa0d-199">启用 Azure AD SSPR。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="2fa0d-200">允许用户使用 Azure AD 自助服务组管理创建和管理自己的云安全或 Office 365 组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-201">使用 Azure AD 委派组管理管理企业应用的委派访问权限。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-202">启用 Azure AD 动态组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-203">使用集合在"我的应用程序"门户中组织应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="2fa0d-204">本地 Active Directory 及其环境已针对 Azure AD Premium 做好准备，包括修复阻止与 Azure AD 和 Azure AD Premium 功能集成的已识别问题。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2fa0d-205"><strong>Azure 信息保护 </strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-206">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-206">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-207">激活和配置租户。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-207">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-208">创建和设置标签和策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-208">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-209">向文档应用信息保护。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-209">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-210">自动对在 Windows 上运行的 Office 应用（如Word、PowerPoint、Excel 和 Outlook）中的信息进行分类和标记，并使用 Azure 信息保护客户端。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-210">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-211">使用 Azure 信息保护扫描程序发现并标记其余文件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-211">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-212">使用 Exchange Online 邮件流规则监视传输中的电子邮件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-212">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="2fa0d-213">如果你希望使用 Microsoft Azure 权限管理服务 (Azure RMS) 、Office 365 邮件加密 (OME) 和数据丢失防护 (DLP) ，我们还会提供指导。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-213">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="2fa0d-214">客户先决条件职责包括：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-214">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-215">要扫描的文件共享位置的列表。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-215">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-216">批准的分类分类。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-216">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="2fa0d-217">了解有关密钥管理的任何监管限制或要求。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-217">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-218">为本地 Active Directory 创建的已与 Azure AD 同步的服务帐户。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-218">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="2fa0d-219">为分类和保护配置的标签。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-219">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="2fa0d-220">Azure 信息保护扫描程序的所有先决条件都已到位。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-220">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="2fa0d-221">有关详细信息，请参阅安装和部署 Azure 信息保护 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">统一</a>标签扫描程序的先决条件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-221">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="2fa0d-222">确保用户设备正在运行受支持的操作系统，并且已安装必要的必备组件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-222">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="2fa0d-223">有关详细信息，请参阅以下内容。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-223">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="2fa0d-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理员指南：为用户安装 Azure 信息保护统一标签客户端</a>   </span><span class="sxs-lookup"><span data-stu-id="2fa0d-224"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="2fa0d-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">什么是适用于 iOS 或 Android 的 Azure 信息保护应用？</a>  </span><span class="sxs-lookup"><span data-stu-id="2fa0d-225"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="2fa0d-226">安装和配置 Azure RMS 连接器和服务器（包括 Active Directory RMS (AD RMS) 连接器，实现混合支持。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-226">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="2fa0d-227">设置和配置仅自带密钥 (BYOK) 、双密钥加密 (DKE)  (统一标记客户端) 或仅保留您自己的密钥 (HYOK)  (经典客户端) （如果部署需要这些选项之一）。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-227">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="2fa0d-228"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-228"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="2fa0d-229">Microsoft 365 Defender 是一个统一的入侵前和入侵后企业防御套件，可本机协调跨终结点、标识、电子邮件和应用进行检测、预防、调查和响应，以提供针对复杂攻击的集成保护。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-229">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="2fa0d-230">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-230">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="2fa0d-231">提供 Microsoft 365 安全中心概述。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-231">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-232">查看跨产品事件，包括通过确保完全攻击范围、受影响的资产和分组在一起的自动修正操作来重点关注关键事件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-232">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-233">演示 Microsoft 365 Defender 如何协调对资产、用户、设备和邮箱的调查，这些资产、用户、设备和邮箱可能通过自动自我修复而遭到入侵。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-233">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="2fa0d-234">解释并提供客户如何主动搜寻跨多个数据集影响电子邮件、数据、设备和帐户的入侵尝试和入侵活动的示例。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-234">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="2fa0d-235">显示客户如何使用 Microsoft 安全分数全面查看和改进其安全状况。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-235">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="2fa0d-236"><strong>以下内容超出范围</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-236"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="2fa0d-237">客户补救活动的项目管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-237">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="2fa0d-238">持续管理、威胁响应和修正。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-238">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="2fa0d-239">部署指南或教育：：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-239">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="2fa0d-240">如何修正或解释各种警报类型和受监视的活动。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-240">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="2fa0d-241">如何调查用户、计算机、横向移动路径或实体。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-241">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="2fa0d-242">自定义威胁搜寻。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-242">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="2fa0d-243">SIEM 或 API 集成 (安全) 事件管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-243">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2fa0d-244"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-244"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-245">Microsoft Cloud App Security 是云访问安全代理 (CASB) ，可提供丰富的可见性、控制数据旅行和复杂的分析，以识别和防御所有 Microsoft 和第三方云服务中的网络威胁。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-245">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="2fa0d-246">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-246">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-247">配置门户，包括：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-247">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="2fa0d-248">导入用户组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-248">Importing user groups.</span></span></li>
<li> <span data-ttu-id="2fa0d-249">管理管理员访问权限和设置。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-249">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="2fa0d-250">将部署范围确定为选择要监视或排除在监控范围中的特定用户组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-250">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="2fa0d-251">设置 IP 范围和标记。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-251">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="2fa0d-252">使用徽标和自定义消息个性化最终用户体验。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-252">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="2fa0d-253">设置云发现以使用：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-253">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="2fa0d-254">适用于终结点的 Microsoft Defender。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-254">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="2fa0d-255">Zscaler。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-255">Zscaler.</span></span></li>
<li> <span data-ttu-id="2fa0d-256">iboss。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-256">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="2fa0d-257">使用 <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">应用连接器</a> 连接特色应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-257">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="2fa0d-258">在条件访问和云应用安全门户中设置条件访问应用控件，以应用实时会话控件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-258">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="2fa0d-259">部署 Cloud App Security 和 Cloud Discovery 仪表板。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-259">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="2fa0d-260">根据组织优先级自定义应用风险评分。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-260">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="2fa0d-261">创建应用标记和类别。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-261">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="2fa0d-262">批准和取消批准应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-262">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="2fa0d-263">使用活动和文件日志。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-263">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="2fa0d-264">管理 OAuth 应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-264">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="2fa0d-265">了解 Microsoft 365 Defender 门户中的事件相关性。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-265">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="2fa0d-266">为 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">CASB 的前 20</a> 个用例提供配置帮助 (包括创建或更新多达 6 (6) 策略，) 除外：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-266">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="2fa0d-267">审核 IaaS (18) 环境 (#18) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-267">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="2fa0d-268">监视用户活动，防止 IaaS 环境中的威胁 (#19) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-268">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="2fa0d-269"><strong>以下内容超出范围</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-269"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="2fa0d-270">客户补救活动的项目管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-270">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="2fa0d-271">持续管理、威胁响应和修正。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-271">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="2fa0d-272">使用 Docker 或日志收集器为连续报告设置自动日志上载的基础结构、安装或部署。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-272">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="2fa0d-273">有关详细信息 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">，请参阅 CASB 的前 20</a> 个用例。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-273">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="2fa0d-274">创建云发现快照报告。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-274">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="2fa0d-275">使用阻止脚本阻止应用使用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-275">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="2fa0d-276">连接自定义应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-276">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="2fa0d-277">与第三方标识提供程序 (DLP) 提供程序 (数据丢失防护) ISP。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-277">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="2fa0d-278">有关高级搜寻的培训或指导。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-278">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="2fa0d-279">自动调查和修正，包括 Microsoft Power Automate 手册。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-279">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="2fa0d-280">SIEM (或 API 集成) 安全信息和事件 (包括 Azure Sentinel) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-280">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="2fa0d-281">部署云应用发现作为概念证明。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-281">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="2fa0d-282"><strong>Microsoft Defender 高级威胁防护 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-282"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-283">Microsoft Defender 高级威胁防护 (ATP) 是旨在帮助企业网络预防、检测、调查和响应高级威胁的平台。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-283">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="2fa0d-284">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-284">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-285">部署技术以确保终结点安全。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-285">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-286">配置终结点保护和设备限制配置文件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-286">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-287">评估操作系统版本和设备管理 (包括 Intune、Microsoft Endpoint Configuration Manager、组策略对象 (GPO) 和第三方配置) 以及 Windows Defender AV 服务或其他终结点安全软件的状态。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-287">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-288">评估 Windows AV 服务或其他终结点安全软件的状态。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-288">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-289">评估限制网络流量的代理和防火墙。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-289">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-290">通过说明如何使用载入终结点部署 ATP 代理配置文件来启用 Microsoft Defender ATP 服务。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-290">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-291">部署指南、配置帮助和教育：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-291">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="2fa0d-292">威胁和漏洞管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-292">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-293">攻击面减少。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-293">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-294">新一代保护。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-294">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-295">终结点检测和响应。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-295">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-296">自动调查和修复。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-296">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-297">安全功能分数。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-297">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-298">查看模拟和教程 (方案、假恶意软件和自动调查等) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-298">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-299">报告和威胁分析功能概述。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-299">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-300">将 Office 365 ATP 与 Microsoft Defender ATP 集成。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-300">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-301">在 Microsoft Defender 安全中心门户中执行演练。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-301">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-302">以下操作系统：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-302">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="2fa0d-303">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-303">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-304">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-304">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-305">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-305">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-306">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-306">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-307">Windows Server Semi-Annual Channel (SAC) 版本 1803。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-307">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-308">macOS 版本 10.13、10.14 和 10.15。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-308">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="2fa0d-309">
<strong>注意：</strong> 所有 Windows Server 版本都必须由最新版本的 System Center Configuration Manager 2012 (版本 1012 R2、1511 或 1602) 或 Microsoft Endpoint Configuration Manager (版本 2002 或) 管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-309">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="2fa0d-310"></li>
</ul>

<strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-310"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="2fa0d-311">客户补救活动的项目管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-311">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-312">现场支持。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-312">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-313">持续管理和威胁响应。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-313">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-314">以下 Microsoft Defender ATP 代理的加入或配置：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-314">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="2fa0d-315">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-315">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-316">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-316">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-317">Linux。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-317">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-318">Android 和 iOS (移动设备) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-318">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-319">服务器载入和配置：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-319">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="2fa0d-320">为脱机通信配置代理服务器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-320">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-321">在下层 Configuration Manager 实例和版本上配置 Configuration Manager 部署包。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-321">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-322">将服务器载入 Azure 安全中心。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-322">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-323">不由 Configuration Manager 管理的服务器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-323">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-324">macOS 载入和配置：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-324">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="2fa0d-325">基于 Intune 的手动部署。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-325">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-326">基于 JAMF 的部署。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-326">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="2fa0d-327">MDM 的其他移动设备管理 () 基于产品的部署。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-327">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-328">手动部署。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-328">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-329">配置以下攻击面减少功能：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-329">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="2fa0d-330">基于硬件的隔离。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-330">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-331">应用控件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-331">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-332">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-332">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-333">网络防火墙。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-333">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-334">注册或配置 Microsoft 威胁专家。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-334">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-335">在 SIEM 连接中查看 API 或安全信息 (或) 培训。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-335">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-336">注册或配置 Microsoft 威胁防护 (MTP)。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-336">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-337">有关高级搜寻的培训或指导。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-337">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-338">有关使用或创建 Kusto 查询的培训或指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-338">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="2fa0d-339">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-339">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="2fa0d-340"><strong>Microsoft Defender for Identity </strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-340"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-341">Microsoft Defender for Identity 是一种基于云的安全解决方案，可利用本地 Active Directory 信号来识别、检测和调查针对组织的高级威胁、已遭入侵标识和恶意内部行为。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-341">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="2fa0d-342">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-342">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="2fa0d-343">创建 Defender for Identity 实例。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-343">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="2fa0d-344">将 Defender for Identity 连接到 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-344">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="2fa0d-345">评估环境在域控制器上部署 Defender for Identity 传感器的准备情况，包括：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-345">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="2fa0d-346">运行资源容量规划大小工具。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-346">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="2fa0d-347">运行审核工具来评估域控制器与传感器的兼容性。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-347">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="2fa0d-348">部署传感器以直接从域控制器捕获和分析网络流量和 Windows 事件，包括：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-348">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="2fa0d-349">下载传感器包。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-349">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="2fa0d-350">配置传感器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-350">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="2fa0d-351">以静默方式在域控制器上安装传感器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-351">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="2fa0d-352">将传感器部署到多林环境。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-352">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="2fa0d-353">无需将 Defender for Identity 与 Microsoft Cloud App Security (云应用安全许可) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-353">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="2fa0d-354">提供部署指南、配置帮助和教育：：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-354">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="2fa0d-355">调整环境以减少"噪音"。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-355">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-356">了解标识安全状态评估报告。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-356">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="2fa0d-357">了解用户调查优先级分数和用户调查排名报告。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-357">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="2fa0d-358">了解非活动用户报告。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-358">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="2fa0d-359">在遭到入侵的帐户上提供修正选项。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-359">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="2fa0d-360">推动从高级威胁分析 (ATA) Defender for Identity。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-360">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="2fa0d-361"><strong>以下内容超出范围</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-361"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="2fa0d-362">客户补救活动的项目管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-362">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="2fa0d-363">持续管理、威胁响应和修正。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-363">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="2fa0d-364">部署 Defender for Identity 传感器，包括：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-364">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="2fa0d-365">手动容量规划。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-365">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="2fa0d-366">以独立容量部署传感器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-366">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="2fa0d-367">使用网络接口卡和 NIC (适配器) 传感器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-367">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="2fa0d-368">通过第三方工具部署传感器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-368">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="2fa0d-369">通过 Web 代理连接连接到 Defender for Identity 云服务。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-369">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="2fa0d-370">创建和管理 honeytokens。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-370">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="2fa0d-371">部署指南或教育：：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-371">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="2fa0d-372">修正或解释各种警报类型和监视的活动。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-372">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="2fa0d-373">调查用户、计算机、横向移动路径或实体。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-373">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="2fa0d-374">威胁或高级搜寻。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-374">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="2fa0d-375">事件响应。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-375">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="2fa0d-376">为 Defender for Identity 提供安全警报实验室教程。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-376">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="2fa0d-377">当 Defender for Identity 检测到可疑活动时，通过指定的传感器向 syslog 服务器发送安全警报，从而提供通知。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-377">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="2fa0d-378">将 Defender for Identity 配置为使用安全帐户管理器远程 (SAMR) 协议执行查询，以标识特定计算机上的本地管理员。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-378">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="2fa0d-379">配置 VPN 解决方案以将信息从 VPN 连接添加到用户配置文件页面。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-379">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="2fa0d-380">SIEM (或 API 集成) 安全信息和事件 (包括 Azure Sentinel) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-380">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="2fa0d-381">部署 Defender for Identity 传感器作为概念证明。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-381">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="2fa0d-382">已部署 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-382">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-383">打算安装 Defender for Identity 传感器的域控制器具有与 Defender for Identity 云服务的 Internet 连接。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-383">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="2fa0d-384">防火墙和代理必须处于打开状态，以与 Defender for Identity 云服务通信 (\*.atp.azure.com 端口 443 必须) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-384">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="2fa0d-385">在下列其中一个上运行的域控制器：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-385">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="2fa0d-386">Windows Server 2008 R2 SP1。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-386">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="2fa0d-387">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-387">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="2fa0d-388">Windows Server 2012 R2。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-388">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="2fa0d-389">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-389">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="2fa0d-390">Windows Server 2019 KB4487044 (操作系统版本 17763.316) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-390">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="2fa0d-391"><strong>Microsoft 信息管控</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-391"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-392">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-392">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-393">保留标签和策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-393">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-394">记录管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-394">Records management.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-395">删除策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-395">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-396">通信合规性。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-396">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-397">内部风险管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-397">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-398">高级电子数据展示。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-398">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-399">

  <strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-399">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="2fa0d-400">开发记录管理文件计划。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-400">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="2fa0d-401">数据连接器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-401">Data connectors.</span></span></li>
<li> <span data-ttu-id="2fa0d-402">信息屏障。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-402">Information barriers.</span></span></li>
<li> <span data-ttu-id="2fa0d-403">特权访问管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-403">Privileged access management.</span></span></li>
<li> <span data-ttu-id="2fa0d-404">在 SharePoint 中开发信息体系结构。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-404">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="2fa0d-405">自定义脚本和编码。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-405">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="2fa0d-406">除" <strong>常规"中的核心</strong> 载入 <a href="#general">部分</a>外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-406">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2fa0d-407"><strong>Microsoft 信息保护</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-407"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-408">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-408">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-409">数据分类。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-409">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-410">敏感信息类型。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-410">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-411">创建敏感度标签。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-411">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-412">应用敏感度标签。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-412">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-413">统一标记。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-413">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-414">可训练的分类器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-414">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-415">通过内容浏览器和活动浏览器了解你的数据。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-415">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-416">使用策略来发布标签（手动和自动）。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-416">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-417">创建针对 Microsoft Teams 聊天和频道的数据丢失防护 (DLP) 策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-417">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-418">为 Windows 10 设备创建终结点 DLP 策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-418">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-419">

<strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-419">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="2fa0d-420">客户密钥。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-420">Customer key.</span></span></li>
<li><span data-ttu-id="2fa0d-421">RegEx (正则表达式) 敏感信息类型的开发。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-421">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="2fa0d-422">创建或修改关键字词典。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-422">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="2fa0d-423">自定义脚本和编码。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-423">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="2fa0d-424">
<strong>注意：</strong> 有关详细信息，请参阅企业移动性 + 安全性中的 <strong> Azure </strong> <a href="#enterprise-mobility--security">信息保护</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-424">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="2fa0d-425">除" <strong>常规"中的核心</strong> 载入 <a href="#general">部分</a>外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-425">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="2fa0d-426"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-426"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-427">我们提供有关准备好使用 Intune 作为基于云的移动设备管理 (MDM) 和移动应用管理 (MAM) 提供程序的远程指导。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-427">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="2fa0d-428">具体步骤取决于你的源环境，并且基于你的移动设备和移动应用管理需求。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-428">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="2fa0d-429">所包含的具体步骤如下：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-429">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-430">许可最终用户。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-430">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-431">通过利用本地 Active Directory 或 Azure AD (云标识配置由 Intune 使用的) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-431">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-432">将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-432">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-433">根据管理需求配置 MDM 颁发机构，包括：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-433">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-434">如果 Intune 是唯一的 MDM 解决方案，将 Intune 设置为 MDM 颁发机构。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-434">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-435">为以下操作提供 MDM 指南:</span><span class="sxs-lookup"><span data-stu-id="2fa0d-435">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-436">配置用于验证 MDM 管理策略的测试组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-436">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-437">配置 MDM 管理策略和服务，如：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-437">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-438">通过 Web 链接或深层链接针对每个受支持的平台进行应用部署。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-438">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-439">条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-439">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-440">如果组织中已有证书颁发机构、无线网络或 VPN 基础结构，则部署电子邮件、无线网络和 VPN 配置文件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-440">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-441">连接到 Intune 数据仓库。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-441">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-442">将 Intune 与以下内容进行集成：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-442">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-443">使用团队查看器订阅 (远程协助的团队查看器) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-443">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-444">移动威胁防护 (MTD) 需要 (MTD 订阅的合作伙伴解决方案) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-444">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-445">需要电信费用管理解决方案 (电信费用管理解决方案订阅) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-445">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-446">需要 Microsoft Defender ATP (Windows E5 或 Microsoft 365 E5 许可证才能) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-446">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-447">将每个受支持平台的设备注册到 Intune。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-447">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-448">提供应用保护指南，</span><span class="sxs-lookup"><span data-stu-id="2fa0d-448">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-449">为每个受支持的平台配置应用保护策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-449">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-450">为托管应用配置条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-450">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-451">使用前面提到的 MAM 策略面向相应的用户组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-451">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-452">使用托管应用使用情况报告。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-452">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-453">提供从旧版电脑管理到 Intune MDM 的迁移指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-453">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-454">
  <strong>注意</strong>：自 2020 年 10 月 15 日起，不再支持旧版电脑管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-454">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="2fa0d-455"></li>
</ul>
  
<strong>云附加</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-455"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="2fa0d-456">我们指导你准备好使用 Intune 云附加现有 Configuration Manager 环境。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-456">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="2fa0d-457">具体步骤取决于源环境。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-457">The exact steps depend on your source environment.</span></span> <span data-ttu-id="2fa0d-458">这些步骤包括：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-458">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="2fa0d-459">许可最终用户。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-459">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-460">通过利用本地 Active Directory 和云标识，配置供 Intune 使用的标识。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-460">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-461">将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-461">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-462">提供设置混合 Azure AD 加入的指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-462">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-463">提供有关为 MDM 自动注册设置 Azure AD 的指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-463">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-464">提供有关如何设置云管理网关的指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-464">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-465">配置要切换到 Intune 的受支持工作负载。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-465">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-466">在 Intune 注册的设备中安装 Configuration Manager 客户端。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-466">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="2fa0d-467"><strong>安全地部署适用于 iOS 和 Android 的 Outlook 移动版</strong> 我们可以提供指导，帮助你在组织中安全地部署适用于 iOS 和 Android 的 Outlook 移动版，以确保用户已安装所有必需的应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-467"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="2fa0d-468">使用 Intune 安全部署适用于 iOS 和 Android 的 Outlook 移动版的步骤取决于源环境。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-468">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="2fa0d-469">它可以包括：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-469">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-470">通过 Apple App Store 或 Google Play 商店下载 Outlook for iOS 和 Outlook for Android、Microsoft Authenticator 和 Intune 公司门户应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-470">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-471">提供有关设置的指导：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-471">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-472">使用 Intune 部署 Outlook for iOS 和 Outlook for Android、Microsoft Authenticator 和 Intune 公司门户应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-472">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-473">应用保护策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-473">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-474">条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-474">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-475">应用配置策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-475">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="2fa0d-476"><strong>注意</strong>：FastTrack 不支持使用 Exchange 移动设备邮箱策略保护 Outlook for iOS 和 Outlook for Android。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-476"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="2fa0d-477">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-477">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="2fa0d-478">在规划使用 Intune 部署无线网络和 VPN 配置文件时，IT 管理员需要具有已在生产环境中工作的现有证书颁发机构、无线网络和 VPN 基础结构。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-478">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="2fa0d-479"><strong>注意</strong>：FastTrack 服务权益不包括有关为 Intune 设置或配置证书颁发机构、无线网络、VPN 基础结构或 Apple MDM 推送证书的帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-479"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="2fa0d-480"><strong>注意</strong>：FastTrack 服务权益不包括有关将配置管理器站点服务器或配置管理器客户端设置或升级到支持云附加所需的最低要求的帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-480"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="2fa0d-481">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-481">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="2fa0d-482"><strong>Intune 与 Microsoft Defender 高级威胁防护 (ATP) 集成</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-482"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="2fa0d-483"><strong>注意</strong>：我们提供有关将 Intune 与 Microsoft Defender ATP 集成以及基于其 Windows 10 风险级别评估创建设备合规性策略的帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-483"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="2fa0d-484">我们不提供有关购买、许可或激活的帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-484">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="2fa0d-485">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-485">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="2fa0d-486"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-486"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="2fa0d-487">IT 管理员负责通过让硬件供应商代表他们上载其硬件 ID 或自己将其上载到 Windows Autopilot 服务中来向其组织注册设备。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-487">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="2fa0d-488"><strong>Office 365 高级威胁防护 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-488"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-489">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-489">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-490">启用安全链接、安全附件和防钓鱼。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-490">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-491">配置自动化、调查和响应。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-491">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-492">使用攻击模拟器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-492">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-493">报告和威胁分析。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-493">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="2fa0d-494">除" <strong>常规"中的核心</strong> 载入 <a href="#general">部分</a>外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-494">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="2fa0d-495">Office 365</span><span class="sxs-lookup"><span data-stu-id="2fa0d-495">Office 365</span></span>

<<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2fa0d-496"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-496"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2fa0d-497"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-497"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2fa0d-498"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-498"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2fa0d-499"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-499"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-500">对于 Exchange Online，我们会全程指导你，直到你的组织可以使用电子邮件为止。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-500">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="2fa0d-501">具体步骤取决于源环境和电子邮件迁移计划。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-501">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="2fa0d-502">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-502">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-503">为 Office 365 中验证的所有启用邮件的域设置 Exchange Online Protection (EOP) 功能。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-503">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-504">将邮件交换 (MX) 指向 Office 365。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-504">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-505">如果 Office 365 ATP 功能是订阅服务的一部分，则设置该功能。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-505">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="2fa0d-506">有关详细信息，请参阅此表的 <strong>Office 365 高级威胁</strong> 防护部分。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-506">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-p128">为在 Office 365 中验证的所有已启用邮件的域设置数据丢失防护 (DLP) 功能，将其作为订阅服务的一部分。这可在 MX 记录指向 Office 365 后完成。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-p128">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="2fa0d-p129">为在 Office 365 中验证的所有已启用邮件的域设置 Office 365 邮件加密 (OME) ，将其作为订阅服务的一部分。这可在 MX 记录指向 Office 365 后完成。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-p129">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="2fa0d-511">
  <strong>注意：</strong> MRS 邮箱复制服务 (MRS) 尝试将信息权限托管 (IRM) 电子邮件从本地邮箱迁移到相应的 Exchange Online 邮箱。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-511">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="2fa0d-512">可读取受保护内容迁移后的能力取决于客户映射和将 Active Directory Rights Managed Services (AD RMS) 模板复制到 Azure Rights Management Service (Azure RMS)。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-512">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="2fa0d-513">配置防火墙端口。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-513">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-514">根据需要设置 DNS，包括所需的自动发现、发件人策略框架 (SPF) 、域密钥识别邮件 (DKIM) 、基于域的邮件身份验证、报告和一致性 (DMARC) 和 MX 记录 () 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-514">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-515">设置源邮件环境和 Exchange Online 之间的电子邮件流（根据需要）。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-515">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-516">执行从源邮件环境到 Office 365 的邮件迁移。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-516">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-517">配置邮箱客户端（Outlook for Windows、Outlook 网页版以及 Outlook for iOS 和 Outlook for Android）。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-517">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="2fa0d-518">
  <strong>数据迁移</strong>  </span><span class="sxs-lookup"><span data-stu-id="2fa0d-518">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="2fa0d-519">有关使用 FastTrack 权益将数据迁移到 Office 365 的信息，请参阅<a href="https://docs.microsoft.com/fasttrack/data-migration">"数据迁移"。</a></span><span class="sxs-lookup"><span data-stu-id="2fa0d-519">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="2fa0d-520">源环境必须具有以下最低级别之一：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-520">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-521">具有 Exchange Server 2003 前向的单个或多个 Exchange 组织。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-521">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-522">一个支持 Internet 邮件访问协议 (IMAP) 的电子邮件环境。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-522">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-523">单个 G 套件环境（仅限 Gmail、联系人和日历）。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-523">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-524">有关多地理位置功能的信息，请参阅 Exchange Online 中的多 <a href="https://go.microsoft.com/fwlink/?linkid=872776">地理位置功能</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-524">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="2fa0d-525">联机客户端软件（如 Project for Office 365、Outlook for Windows、Outlook for iOS 和 Outlook for Android、OneDrive for Business 同步客户端、Power BI Desktop 和 Skype for Business）必须处于最低级别，如 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office</a>的系统要求所定义。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-525">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="2fa0d-526"><strong>Microsoft 信息管控</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-526"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-527">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-527">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-528">保留标签和策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-528">Retention labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-529">记录管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-529">Records management.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-530">删除策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-530">Deletion policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-531">通信合规性。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-531">Communication compliance.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-532">内部风险管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-532">Insider risk management.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-533">高级电子数据展示。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-533">Advanced eDiscovery.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-534">

  <strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-534">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="2fa0d-535">开发记录管理文件计划。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-535">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="2fa0d-536">数据连接器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-536">Data connectors.</span></span></li>
<li> <span data-ttu-id="2fa0d-537">信息屏障。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-537">Information barriers.</span></span></li>
<li> <span data-ttu-id="2fa0d-538">特权访问管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-538">Privileged access management.</span></span></li>
<li> <span data-ttu-id="2fa0d-539">在 SharePoint 中开发信息体系结构。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-539">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="2fa0d-540">自定义脚本和编码。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-540">Custom scripting and coding.</span></span></li>
</td>
<td><span data-ttu-id="2fa0d-541">除" <strong>常规"中的核心</strong> 载入 <a href="#general">部分</a>外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-541">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2fa0d-542"><strong>Microsoft 信息保护</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-542"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-543">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-543">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-544">数据分类。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-544">Data classification.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-545">敏感信息类型。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-545">Sensitive information types.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-546">创建敏感度标签。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-546">Creating sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-547">应用敏感度标签。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-547">Applying sensitivity labels.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-548">统一标记。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-548">Unified labeling.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-549">可训练的分类器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-549">Trainable classifiers.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-550">通过内容浏览器和活动浏览器了解你的数据。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-550">Knowing your data with content explorer and activity explorer.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-551">使用策略来发布标签（手动和自动）。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-551">Publishing labels using policies (manual and automatic).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-552">创建针对 Microsoft Teams 聊天和频道的数据丢失防护 (DLP) 策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-552">Creating data loss prevention (DLP) policies for Microsoft Teams chats and channels.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-553">为 Windows 10 设备创建终结点 DLP 策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-553">Creating Endpoint DLP policies for Windows 10 devices.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-554">

<strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-554">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="2fa0d-555">客户密钥。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-555">Customer key.</span></span></li>
<li><span data-ttu-id="2fa0d-556">RegEx (正则表达式) 敏感信息类型的开发。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-556">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="2fa0d-557">创建或修改关键字词典。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-557">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="2fa0d-558">自定义脚本和编码。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-558">Custom scripting and coding.</span></span></li>
</ul><span data-ttu-id="2fa0d-559">
<strong>注意：</strong> 有关详细信息，请参阅企业移动性 + 安全性中的 <strong> Azure </strong> <a href="#enterprise-mobility--security">信息保护</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-559">
<strong>Note:</strong> For more information, see <strong> Azure Information Protection </strong> in <a href="#enterprise-mobility--security">Enterprise Mobility + Security</a>.</span></span>
<ul>

</td>
<td><span data-ttu-id="2fa0d-560">除" <strong>常规"中的核心</strong> 载入 <a href="#general">部分</a>外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-560">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2fa0d-561"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-561"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-562">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-562">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-563">确认 Exchange Online、SharePoint Online、Office 365 组和 Azure AD 中支持 Teams 的最低要求。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-563">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-564">配置防火墙端口。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-564">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-565">设置 DNS。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-565">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-566">确认是否已在 Office 365 租户上启用 Teams。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-566">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-567">启用或禁用用户许可证。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-567">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-568">Teams 的网络评估：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-568">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-569">端口和终结点检查。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-569">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-570">连接质量检查。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-570">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-571">带宽预估。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-571">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="2fa0d-572">配置 Teams 应用策略 (Teams Web 应用、Teams 桌面应用和适用于 iOS 和 Android 应用的 Teams) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-572">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="2fa0d-573">如果适用，我们还提供有关：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-573">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-574">Microsoft Teams 会议室设备：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-574">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="2fa0d-575">创建 <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams 设备目录</a>中所列支持的电话和会议室设备所需的在线帐户。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-575">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-576">远程协助认证的 Microsoft Teams 会议室设备的服务器端配置。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-576">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-577">启用音频会议：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-577">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-578">会议桥默认设置的组织设置。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-578">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-579">向许可用户分配会议桥。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-579">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="2fa0d-580">电话系统：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-580">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-581">组织设置云语音默认设置。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-581">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-582">通话套餐指南 (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">市场) ：</a></span><span class="sxs-lookup"><span data-stu-id="2fa0d-582">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-583">向许可用户分配号码。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-583">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-584">通过用户界面 (UI) 进行本地号码端口定位的指南（最多到 999）。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-584">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-585">超过 999 的本地号码端口定位服务请求 (SR) 支持。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-585">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-586">直接路由指南：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-586">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-587">针对合作伙伴托管方案的直接路由设计或客户部署方案（最多 10 个站点）的组织设置指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-587">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="2fa0d-588">会话边界控制器 (SBC) 配置评审。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-588">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="2fa0d-589">拨号计划配置的远程协助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-589">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="2fa0d-590">语音路由配置。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-590">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="2fa0d-591">媒体旁路和本地媒体优化。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-591">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-592">启用 Teams 实时事件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-592">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-593">组织设置和集成到 Microsoft Stream。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-593">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-594">Skype for Business 到 Teams 转换的指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-594">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="2fa0d-595">在适用于 Office 365 的 Azure AD 中启用的标识。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-595">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-596">对 SharePoint Online 启用的用户。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-596">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-597">Exchange 邮箱 (Exchange 混合配置策略中的联机和本地) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-597">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-598">针对 Office 365 组启用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-598">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-599">
  <strong>注意：</strong> 如果未为用户分配和启用 SharePoint Online 许可证，他们将不会在 Office 365 中拥有 OneDrive for Business 存储。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-599">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="2fa0d-600">文件共享继续在频道中工作，但用户在没有 Office 365 中的 OneDrive for Business 存储的情况下无法共享聊天中的文件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-600">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="2fa0d-601">Teams 不支持本地 SharePoint。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-601">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="2fa0d-602">
  <strong>注意：</strong> 理想的状态是所有用户的邮箱都位于 Exchange Online 上。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-602">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="2fa0d-603">具有本地托管邮箱的用户必须通过 Azure AD Connect 将其标识同步到 Office 365 目录。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-603">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="2fa0d-604">对于这些 Exchange 混合客户，如果用户的邮箱在本地，则用户无法添加或配置连接器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-604">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="2fa0d-605">可以从 <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> 下载 Microsoft Teams Windows 和 Mac 桌面客户端的安装程序。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-605">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2fa0d-606"><strong>Office 365 高级威胁防护 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-606"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-607">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-607">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-608">启用安全链接、安全附件和防钓鱼。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-608">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-609">配置自动化、调查和响应。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-609">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-610">使用攻击模拟器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-610">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-611">报告和威胁分析。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-611">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="2fa0d-612">除" <strong>常规"中的核心</strong> 载入 <a href="#general">部分</a>外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-612">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2fa0d-613"><strong>iOS 和 Android 版 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-613"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-614">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-614">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-615">从 Apple App Store 和 Google Play 下载 Outlook for iOS 和 Outlook for Android。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-615">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-616">配置帐户和访问 Exchange Online 邮箱。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-616">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-617">保护 Outlook 移动 (请参阅保护 Exchange Online 中的 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Outlook for iOS</a> 和 Outlook for Android，) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-617">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="2fa0d-618">在适用于 Office 365 的 Azure AD 中启用的标识。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-618">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-619">配置了 Exchange Online 并分配了许可证。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-619">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2fa0d-620"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-620"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-621">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-621">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-622">分配 Power BI 许可证。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-622">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-623">部署 Power BI Desktop 应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-623">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="2fa0d-624">Power BI Desktop 等联机客户端软件必须处于最低级别，如 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>和 Office 的系统要求所定义。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-624">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2fa0d-625"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-625"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-626">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-626">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-627">验证 Project Online 依赖的基本 SharePoint 功能。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-627">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-628">向你的租户添加 Project Online 服务（包括向用户添加订阅）。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-628">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-629">设置企业资源池 (ERP)。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-629">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-630">创建你的首个项目。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-630">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="2fa0d-631">Project for Office 365 等联机客户端软件必须处于最低级别，如 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>和 Office 的系统要求所定义。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-631">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2fa0d-632"><strong>Project Online Professional 和 Premium</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-632"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-633">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-633">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-634">解决部署问题。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-634">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-635">使用 Microsoft 365 管理中心和 Windows PowerShell 分配最终用户许可证。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-635">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-636">使用即点即用从 Office 365 门户安装 Project Online 桌面客户端。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-636">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-637">使用 Office 365 部署工具配置更新设置。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-637">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-638">为 Project Online 桌面客户端 设置一个现场分发服务器，包括帮助创建 configuration.xml 文件以与 Office 365 部署工具一起使用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-638">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-639">将 Project Online 桌面客户端 连接到 Project Online Professional 或 Project Online 高级版。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-639">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="2fa0d-640">Project for Office 365 等联机客户端软件必须处于最低级别，如 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>和 Office 的系统要求所定义。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-640">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2fa0d-641"><strong>SharePoint Online 和 OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-641"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-642">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-642">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-643">设置 DNS。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-643">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-644">配置防火墙端口。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-644">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-645">设置用户和许可证。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-645">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="2fa0d-646">为你的 SharePoint Online 管理员启用站点创建。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-646">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="2fa0d-647">规划网站集。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-647">Planning site collections.</span></span></li>
<li><span data-ttu-id="2fa0d-648">保护内容安全和管理权限。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-648">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="2fa0d-649">配置 SharePoint Online 功能。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-649">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="2fa0d-650">配置 SharePoint 混合功能，如混合搜索、混合网站、混合分类、内容类型、混合自助式网站创建（仅适用于 SharePoint Server 2013）、扩展的应用启动器、混合 OneDrive for Business 和 Extranet 网站。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-650">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-651">迁移方法。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-651">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="2fa0d-652">根据 SharePoint 版本，为 OneDrive for Business 提供了其他指南，例如：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-652">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-653">确定集成选项并查看本地和联机网络基础结构和带宽。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-653">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-654">安装 SharePoint Online 2013 SP1 (（如果适用) 、规划和实现同步和标识要求，以及确定 OneDrive for Business 同步客户端）。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-654">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-655">规划和实现针对所有用户的单个推出 (分阶段推出) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-655">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-656">分配许可证、将"我的网站"和个人文档库重定向到适用于 SharePoint Online 2013) 的 Office 365 (，设置访问群体以控制对适用于 SharePoint Online 2013 (的 OneDrive) 的访问。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-656">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="2fa0d-657">将已知文件夹重定向或移动到 OneDrive。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-657">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="2fa0d-658">部署 OneDrive for Business 客户端同步。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-658">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-659">
  <strong>数据迁移</strong>  </span><span class="sxs-lookup"><span data-stu-id="2fa0d-659">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="2fa0d-660">有关使用 FastTrack 权益将数据迁移到 Office 365 的信息，请参阅<a href="https://docs.microsoft.com/fasttrack/data-migration">"数据迁移"。</a></span><span class="sxs-lookup"><span data-stu-id="2fa0d-660">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="2fa0d-661"><strong>对于 SharePoint 混合：</strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-661"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="2fa0d-662">SharePoint 混合配置包括配置混合搜索、网站、分类、内容类型、OneDrive for Business、扩展的应用启动器、Extranet 网站以及从本地连接到单个目标 SharePoint Online 环境的自助式网站创建。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-662">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-663">
  <strong>注意：</strong> 自助式网站创建不在运行 SharePoint 2013 的本地服务器范围内。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-663">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="2fa0d-664">若要启用 SharePoint 混合，您必须具有以下本地 SharePoint Server 环境之一：2013、2016 或 2019。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-664">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-665">
  <strong>注意：</strong> 未将本地 SharePoint 环境升级到 SharePoint Server。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-665">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="2fa0d-666">请联系 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴寻求帮助</a> 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-666">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="2fa0d-667">有关详细信息，请参阅 <a href="https://go.microsoft.com/fwlink/?linkid=853548">SharePoint 混合功能的最低公共更新级别</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="2fa0d-667">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="2fa0d-668">
  <strong>注意：</strong> 有关多地理位置功能的信息，请参阅 Office <a href="https://go.microsoft.com/fwlink/?linkid=831056">365 中的 OneDrive 和 SharePoint Online 中的多地理位置功能</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="2fa0d-668">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2fa0d-669"><strong>Yammer 企业版</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-669"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="2fa0d-670">我们提供启用 Yammer Enterprise 服务的远程指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-670">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="2fa0d-671">联机客户端软件必须处于 Microsoft <a href="https://go.microsoft.com/fwlink/?LinkID=723597">365</a>和 Office 的系统要求中定义的最低级别。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-671">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="2fa0d-672">企业移动性 + 安全性</span><span class="sxs-lookup"><span data-stu-id="2fa0d-672">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2fa0d-673"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-673"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2fa0d-674"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-674"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2fa0d-675"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-675"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="2fa0d-676"><strong>Azure Active Directory (Azure AD) 和 Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-676"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-677">我们针对以下方案提供用于保护云标识的远程指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-677">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="2fa0d-678">

<strong>安全的基础基础结构</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-678">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="2fa0d-679">为标识配置和启用强身份验证，包括使用 Azure 多重身份验证 (MFA)  (云仅) 、Microsoft Authenticator 应用以及 Azure MFA 和自助服务密码重置联合注册 (SSPR) 进行保护。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-679">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-680">对于非 Azure AD Premium 客户，提供了使用安全默认值保护标识的指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-680">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-681">对于 Azure AD 高级客户，提供了使用条件访问保护标识的指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-681">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-682">通过 Azure AD 密码保护检测和阻止使用弱密码。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-682">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-683">使用 Azure AD 应用程序代理保护对本地 Web 应用的远程访问。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-683">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-684">使用 Azure Identity Protection 启用基于风险的检测和修正。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-684">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-685">启用自定义登录屏幕，包括徽标、文本和具有自定义品牌的图像。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-685">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-686">使用 Azure AD B2B 安全地与来宾用户共享应用和服务。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-686">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-687">使用基于角色的访问控制 (RBAC) 内置管理角色管理 Office 365 管理员的访问权限，并减少特权管理员帐户的数量。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-687">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-688">配置混合 Azure AD 加入。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-688">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-689">配置 Azure AD 加入。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-689">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-690">
  
<strong>监视和报告</strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-690">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="2fa0d-691">使用 Azure AD Connect Health 为 AD FS、Azure AD Connect 和域控制器启用远程监视。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-691">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="2fa0d-692">
  
<strong>治理</strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-692">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="2fa0d-693">使用 Azure AD 权利管理大规模管理 Azure AD 标识和访问生命周期。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-693">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="2fa0d-694">通过 Azure AD 访问评审管理 Azure AD 组成员身份、企业应用访问权限和角色分配。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-694">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-695">查看 Azure AD 使用条款。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-695">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-696">使用 Azure AD Privileged Identity Management 管理和控制对特权管理员帐户的访问。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-696">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="2fa0d-697">
  
<strong>自动化和效率 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-697">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="2fa0d-698">启用 Azure AD SSPR。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-698">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="2fa0d-699">允许用户使用 Azure AD 自助服务组管理创建和管理自己的云安全或 Office 365 组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-699">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-700">使用 Azure AD 委派组管理管理企业应用的委派访问权限。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-700">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-701">启用 Azure AD 动态组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-701">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-702">使用集合在"我的应用程序"门户中组织应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-702">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="2fa0d-703">本地 Active Directory 及其环境已针对 Azure AD Premium 做好准备，包括修复阻止与 Azure AD 和 Azure AD Premium 功能集成的已识别问题。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-703">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2fa0d-704"><strong>Azure 信息保护 </strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-704"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-705">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-705">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-706">激活和配置租户。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-706">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-707">创建和设置标签和策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-707">Creating and setting up labels and policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-708">向文档应用信息保护。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-708">Applying information protection to documents.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-709">自动对在 Windows 上运行的 Office 应用（如Word、PowerPoint、Excel 和 Outlook）中的信息进行分类和标记，并使用 Azure 信息保护客户端。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-709">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-710">使用 Azure 信息保护扫描程序发现并标记其余文件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-710">Discovering and labeling files at rest using the Azure Information Protection scanner.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-711">使用 Exchange Online 邮件流规则监视传输中的电子邮件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-711">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
<span data-ttu-id="2fa0d-712">如果你希望使用 Microsoft Azure 权限管理服务 (Azure RMS) 、Office 365 邮件加密 (OME) 和数据丢失防护 (DLP) ，我们还会提供指导。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-712">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>  </td>
<td>  <span data-ttu-id="2fa0d-713">客户先决条件职责包括：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-713">Customer prerequisite responsibilities include:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-714">要扫描的文件共享位置的列表。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-714">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-715">批准的分类分类。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-715">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="2fa0d-716">了解有关密钥管理的任何监管限制或要求。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-716">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-717">为本地 Active Directory 创建的已与 Azure AD 同步的服务帐户。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-717">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="2fa0d-718">为分类和保护配置的标签。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-718">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="2fa0d-719">Azure 信息保护扫描程序的所有先决条件都已到位。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-719">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="2fa0d-720">有关详细信息，请参阅安装和部署 Azure 信息保护 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">统一</a>标签扫描程序的先决条件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-720">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="2fa0d-721">确保用户设备正在运行受支持的操作系统，并且已安装必要的必备组件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-721">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="2fa0d-722">有关详细信息，请参阅以下内容。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-722">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="2fa0d-723"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理员指南：为用户安装 Azure 信息保护统一标签客户端</a>   </span><span class="sxs-lookup"><span data-stu-id="2fa0d-723"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="2fa0d-724"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">什么是适用于 iOS 或 Android 的 Azure 信息保护应用？</a>  </span><span class="sxs-lookup"><span data-stu-id="2fa0d-724"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="2fa0d-725">安装和配置 Azure RMS 连接器和服务器（包括 Active Directory RMS (AD RMS) 连接器，实现混合支持。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-725">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="2fa0d-726">设置和配置仅自带密钥 (BYOK) 、双密钥加密 (DKE)  (统一标记客户端) 或仅保留您自己的密钥 (HYOK)  (经典客户端) （如果部署需要这些选项之一）。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-726">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="2fa0d-727"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-727"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-728">我们提供有关准备好使用 Intune 作为基于云的移动设备管理 (MDM) 和移动应用管理 (MAM) 提供程序的远程指导。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-728">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="2fa0d-729">具体步骤取决于你的源环境，并且基于你的移动设备和移动应用管理需求。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-729">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="2fa0d-730">所包含的具体步骤如下：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-730">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-731">许可最终用户。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-731">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-732">通过利用本地 Active Directory 或 Azure AD (云标识配置由 Intune 使用的) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-732">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-733">将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-733">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-734">根据管理需求配置 MDM 颁发机构，包括：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-734">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-735">如果 Intune 是唯一的 MDM 解决方案，将 Intune 设置为 MDM 颁发机构。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-735">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-736">为以下操作提供 MDM 指南:</span><span class="sxs-lookup"><span data-stu-id="2fa0d-736">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-737">配置用于验证 MDM 管理策略的测试组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-737">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-738">配置 MDM 管理策略和服务，如：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-738">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-739">通过 Web 链接或深层链接针对每个受支持的平台进行应用部署。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-739">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-740">条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-740">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-741">如果组织中已有证书颁发机构、无线网络或 VPN 基础结构，则部署电子邮件、无线网络和 VPN 配置文件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-741">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-742">连接到 Intune 数据仓库。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-742">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-743">将 Intune 与以下内容进行集成：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-743">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-744">使用团队查看器订阅 (远程协助的团队查看器) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-744">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-745">移动威胁防护 (MTD) 需要 (MTD 订阅的合作伙伴解决方案) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-745">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-746">需要电信费用管理解决方案 (电信费用管理解决方案订阅) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-746">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-747">需要 Microsoft Defender ATP (Windows E5 或 Microsoft 365 E5 许可证才能) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-747">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-748">将每个受支持平台的设备注册到 Intune。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-748">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-749">提供应用保护指南，</span><span class="sxs-lookup"><span data-stu-id="2fa0d-749">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-750">为每个受支持的平台配置应用保护策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-750">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-751">为托管应用配置条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-751">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-752">使用前面提到的 MAM 策略面向相应的用户组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-752">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-753">使用托管应用使用情况报告。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-753">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-754">提供从旧版电脑管理到 Intune MDM 的迁移指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-754">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-755">
  <strong>注意</strong>：自 2020 年 10 月 15 日起，不再支持旧版电脑管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-755">
  <strong>Note</strong>: Legacy PC management is no longer supported from October 15, 2020 onward.</span></span>  
<span data-ttu-id="2fa0d-756"></li>
</ul>
  
<strong>云附加</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-756"></li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="2fa0d-757">我们指导你准备好使用 Intune 云附加现有 Configuration Manager 环境。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-757">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="2fa0d-758">具体步骤取决于源环境。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-758">The exact steps depend on your source environment.</span></span> <span data-ttu-id="2fa0d-759">这些步骤包括：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-759">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="2fa0d-760">许可最终用户。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-760">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-761">通过利用本地 Active Directory 和云标识，配置供 Intune 使用的标识。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-761">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-762">将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-762">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-763">提供设置混合 Azure AD 加入的指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-763">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-764">提供有关为 MDM 自动注册设置 Azure AD 的指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-764">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-765">提供有关如何设置云管理网关的指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-765">Providing guidance on how to set up cloud management gateway.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-766">配置要切换到 Intune 的受支持工作负载。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-766">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-767">在 Intune 注册的设备中安装 Configuration Manager 客户端。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-767">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="2fa0d-768"><strong>安全地部署适用于 iOS 和 Android 的 Outlook 移动版</strong> 我们可以提供指导，帮助你在组织中安全地部署适用于 iOS 和 Android 的 Outlook 移动版，以确保用户已安装所有必需的应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-768"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="2fa0d-769">使用 Intune 安全部署适用于 iOS 和 Android 的 Outlook 移动版的步骤取决于源环境。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-769">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="2fa0d-770">它可以包括：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-770">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-771">通过 Apple App Store 或 Google Play 商店下载 Outlook for iOS 和 Outlook for Android、Microsoft Authenticator 和 Intune 公司门户应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-771">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-772">提供有关设置的指导：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-772">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-773">使用 Intune 部署 Outlook for iOS 和 Outlook for Android、Microsoft Authenticator 和 Intune 公司门户应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-773">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-774">应用保护策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-774">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-775">条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-775">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-776">应用配置策略。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-776">App configuration policies.</span></span>  </li>
</ul></li>
</ul>
  
  <span data-ttu-id="2fa0d-777"><strong>注意</strong>：FastTrack 不支持使用 Exchange 移动设备邮箱策略保护 Outlook for iOS 和 Outlook for Android。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-777"><strong>Note</strong>: FastTrack doesn’t support securing Outlook for iOS and Android with Exchange mobile device mailbox policies.</span></span> <span data-ttu-id="2fa0d-778">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-778">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  </td>
<td>  <span data-ttu-id="2fa0d-779">在规划使用 Intune 部署无线网络和 VPN 配置文件时，IT 管理员需要具有已在生产环境中工作的现有证书颁发机构、无线网络和 VPN 基础结构。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-779">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="2fa0d-780"><strong>注意</strong>：FastTrack 服务权益不包括有关为 Intune 设置或配置证书颁发机构、无线网络、VPN 基础结构或 Apple MDM 推送证书的帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-780"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="2fa0d-781"><strong>注意</strong>：FastTrack 服务权益不包括有关将配置管理器站点服务器或配置管理器客户端设置或升级到支持云附加所需的最低要求的帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-781"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="2fa0d-782">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-782">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="2fa0d-783"><strong>Intune 与 Microsoft Defender 高级威胁防护 (ATP) 集成</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-783"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="2fa0d-784"><strong>注意</strong>：我们提供有关将 Intune 与 Microsoft Defender ATP 集成以及基于其 Windows 10 风险级别评估创建设备合规性策略的帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-784"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="2fa0d-785">我们不提供有关购买、许可或激活的帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-785">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="2fa0d-786">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-786">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="2fa0d-787"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-787"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="2fa0d-788">IT 管理员负责通过让硬件供应商代表他们上载其硬件 ID 或自己将其上载到 Windows Autopilot 服务中来向其组织注册设备。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-788">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="2fa0d-789">Windows 10</span><span class="sxs-lookup"><span data-stu-id="2fa0d-789">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2fa0d-790"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-790"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2fa0d-791"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-791"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2fa0d-792"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-792"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2fa0d-793"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-793"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-794">我们提供从 Windows 7 专业版 和 Windows 8.1 专业版升级到 Windows 10 企业版的指导。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-794">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="2fa0d-795">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-795">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-796">了解你的 Windows 10 意图。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-796">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-797">评估源环境和要求 (确保 Microsoft Endpoint Configuration Manager 已升级到所需级别，以支持 Windows 10 部署) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-797">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-798">使用 Microsoft Endpoint Configuration Manager 或 Microsoft 365 部署 Windows 10 企业版和 Microsoft 365 应用版。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-798">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-799">推荐用于评估 Windows 10 应用的选项。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-799">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-800">通过创建桌面分析部署计划，支持使用桌面分析和指导。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-800">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-801">Microsoft 365 应用版兼容性评估，通过利用 Configuration Manager 中的 Office 365 准备情况仪表板或独立就绪情况 Toolkit for Office，以及 Microsoft 365 应用版部署帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-801">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-802">创建一个修正清单，以规定需要执行哪些操作，使源环境达到成功部署的最低要求。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-802">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-803">为 Windows 10 企业版的现有设备提供升级指南（如果它们满足所需的设备硬件要求）。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-803">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-804">提供升级指南以支持现有部署运动。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-804">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="2fa0d-805">FastTrack 推荐并提供有关就地升级到 Windows 10 的指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-805">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="2fa0d-806">指南还可用于 Windows 干净图片安装和 Windows Autopilot 部署方案。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-806">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-807">使用 Configuration Manager 部署 Microsoft 365 应用作为 Windows 10 部署的一部分。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-807">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="2fa0d-808">提供指南，帮助你的组织使用现有的 Configuration Manager 环境或 Microsoft 365 使用 Windows 10 企业版和 Microsoft 365 应用版保持最新状态。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-808">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-809">
  <strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-809">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="2fa0d-810">将 Configuration Manager 升级到当前分支。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-810">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-811">创建适用于 Windows 10 部署的自定义映像。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-811">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-812">创建和支持 Windows 10 部署的部署脚本。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-812">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-813">将 Windows 10 系统从 BIOS 转换为统一可扩展固件接口 (UEFI)。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-813">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-814">启用 Windows 10 安全功能。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-814">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-815">配置用于启动前执行环境 (PXE) 启动的 Windows 部署服务 (WDS)。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-815">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-816">使用 Microsoft 部署工具包 (MDT) 捕获和部署 Windows 10 映像。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-816">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-817">使用用户状态迁移工具 (USMT)。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-817">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="2fa0d-818">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-818">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="2fa0d-819">要升级电脑，必须满足以下要求：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-819">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-820">源操作系统：Windows 7 企业版专业版、Windows 8.1 企业版或专业版。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-820">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-821">设备：台式机、笔记本或平板电脑外形型号。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-821">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-822">目标操作系统：窗口 10 企业版。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-822">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="2fa0d-823">若要升级基础结构，必须满足以下要求：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-823">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-824">Microsoft Endpoint Configuration Manager。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-824">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-825">Configuration Manager 版本必须受 Windows 10 目标版本支持。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-825">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="2fa0d-826">有关详细信息，请参阅 <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager 中的 Windows 10 支持</a>中的 Configuration Manager 支持表格。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-826">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="2fa0d-827"><strong>Microsoft Defender 高级威胁防护 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-827"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-828">Microsoft Defender 高级威胁防护 (ATP) 是旨在帮助企业网络预防、检测、调查和响应高级威胁的平台。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-828">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="2fa0d-829">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-829">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-830">部署技术以确保终结点安全。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-830">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-831">配置终结点保护和设备限制配置文件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-831">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-832">评估操作系统版本和设备管理 (包括 Intune、Microsoft Endpoint Configuration Manager、组策略对象 (GPO) 和第三方配置) 以及 Windows Defender AV 服务或其他终结点安全软件的状态。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-832">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-833">评估 Windows AV 服务或其他终结点安全软件的状态。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-833">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-834">评估限制网络流量的代理和防火墙。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-834">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-835">通过说明如何使用载入终结点部署 ATP 代理配置文件来启用 Microsoft Defender ATP 服务。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-835">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-836">部署指南、配置帮助和教育：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-836">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="2fa0d-837">威胁和漏洞管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-837">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-838">攻击面减少。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-838">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-839">新一代保护。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-839">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-840">终结点检测和响应。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-840">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-841">自动调查和修复。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-841">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-842">安全功能分数。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-842">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-843">查看模拟和教程 (方案、假恶意软件和自动调查等) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-843">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-844">报告和威胁分析功能概述。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-844">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-845">将 Office 365 ATP 与 Microsoft Defender ATP 集成。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-845">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-846">在 Microsoft Defender 安全中心门户中执行演练。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-846">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-847">以下操作系统：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-847">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="2fa0d-848">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-848">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-849">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-849">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-850">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-850">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-851">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-851">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-852">Windows Server Semi-Annual Channel (SAC) 版本 1803。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-852">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-853">macOS 版本 10.13、10.14 和 10.15。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-853">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="2fa0d-854">
<strong>注意：</strong> 所有 Windows Server 版本都必须由最新版本的 System Center Configuration Manager 2012 (版本 1012 R2、1511 或 1602) 或 Microsoft Endpoint Configuration Manager (版本 2002 或) 管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-854">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="2fa0d-855"></li>
</ul>

<strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-855"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="2fa0d-856">客户补救活动的项目管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-856">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-857">现场支持。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-857">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-858">持续管理和威胁响应。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-858">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-859">以下 Microsoft Defender ATP 代理的加入或配置：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-859">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="2fa0d-860">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-860">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-861">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-861">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-862">Linux。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-862">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-863">Android 和 iOS (移动设备) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-863">Mobile devices (Android and iOS).</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-864">服务器载入和配置：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-864">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="2fa0d-865">为脱机通信配置代理服务器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-865">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-866">在下层 Configuration Manager 实例和版本上配置 Configuration Manager 部署包。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-866">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-867">将服务器载入 Azure 安全中心。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-867">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-868">不由 Configuration Manager 管理的服务器。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-868">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-869">macOS 载入和配置：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-869">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="2fa0d-870">基于 Intune 的手动部署。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-870">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-871">基于 JAMF 的部署。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-871">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="2fa0d-872">MDM 的其他移动设备管理 () 基于产品的部署。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-872">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-873">手动部署。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-873">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-874">配置以下攻击面减少功能：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-874">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="2fa0d-875">基于硬件的隔离。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-875">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-876">应用控件。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-876">App control.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-877">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-877">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-878">网络防火墙。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-878">Network firewall.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="2fa0d-879">注册或配置 Microsoft 威胁专家。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-879">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-880">在 SIEM 连接中查看 API 或安全信息 (或) 培训。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-880">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-881">注册或配置 Microsoft 威胁防护 (MTP)。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-881">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-882">有关高级搜寻的培训或指导。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-882">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-883">有关使用或创建 Kusto 查询的培训或指南。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-883">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="2fa0d-884">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-884">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="2fa0d-885">Windows 虚拟桌面</span><span class="sxs-lookup"><span data-stu-id="2fa0d-885">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2fa0d-886"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-886"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2fa0d-887"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-887"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2fa0d-888"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-888"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2fa0d-889"><strong>Windows 虚拟桌面</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-889"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="2fa0d-890">我们提供载入 Windows 虚拟桌面的部署指南 (桌面应用虚拟化服务) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-890">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="2fa0d-891">Windows 虚拟桌面利用 Windows 10 多会话体验，并针对 Microsoft 365 企业应用版进行了优化，并集成了 Microsoft 365 的安全性和管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-891">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="2fa0d-892">我们提供针对：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-892">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="2fa0d-893">使用 Windows 10 企业版多会话和 Microsoft 365 企业应用版部署 Windows 虚拟桌面环境，方法如下：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-893">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="2fa0d-894">Azure Marketplace 映像。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-894">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="2fa0d-895">共享图像。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-895">Shared image.</span></span></li>
<li><span data-ttu-id="2fa0d-896">Office 部署Toolkit (ODT) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-896">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="2fa0d-897">配置 FSLogix：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-897">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="2fa0d-898">使用配置文件容器部署 FSLogix 代理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-898">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="2fa0d-899">使用 Office 容器部署 FSLogix 代理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-899">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="2fa0d-900">使用内容排除项配置 FSLogix 文件夹。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-900">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="2fa0d-901">部署 Microsoft Edge。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-901">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="2fa0d-902">部署 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-902">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="2fa0d-903">使用 Windows 虚拟桌面客户端进行连接。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-903">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="2fa0d-904">

<strong>以下内容超出范围</strong>
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-904">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="2fa0d-905">客户的 Windows 虚拟桌面部署的项目管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-905">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="2fa0d-906">第三方应用虚拟化和部署。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-906">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="2fa0d-907">自定义图像。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-907">Custom images.</span></span></li>
<li><span data-ttu-id="2fa0d-908">涉及 VMware 和 Citrix 的迁移和方案。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-908">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="2fa0d-909">Linux 方案。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-909">Linux scenarios.</span></span></li>
<li><span data-ttu-id="2fa0d-910">用户配置文件的转换或迁移。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-910">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="2fa0d-911">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-911">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="2fa0d-912">你应该已经拥有以下内容：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-912">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="2fa0d-913"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows 虚拟桌面许可要求</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-913"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="2fa0d-914">Azure 网络：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-914">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="2fa0d-915">创建和 (VNET) 虚拟网络。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-915">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="2fa0d-916">防火墙和网络安全组。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-916">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="2fa0d-917">VPN 和 ExpressRoute。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-917">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="2fa0d-918">从本地路由到 Azure。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-918">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="2fa0d-919">允许连接到 Windows 虚拟桌面的防火墙规则。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-919">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="2fa0d-920">有关详细信息，请参阅支持的 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> 远程桌面客户端</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-920">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="2fa0d-921">Azure AD 常规设置：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-921">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="2fa0d-922">标识 <i> 策略 (只能使用以下三个选项之一) ：</i>
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-922">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="2fa0d-923">Azure 中具有 Azure AD Connect 的 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-923">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="2fa0d-924">通过 VPN 或 ExpressRoute 在本地使用 Azure AD Connect 的 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-924">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="2fa0d-925">Active Directory 域服务 (AD DS) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-925">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="2fa0d-926">应用保证</span><span class="sxs-lookup"><span data-stu-id="2fa0d-926">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2fa0d-927"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-927"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2fa0d-928"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-928"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2fa0d-929"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-929"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="2fa0d-930"><strong>应用保证</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-930"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="2fa0d-931">应用保证是一项旨在解决 Windows 10 和 Microsoft 365 应用应用兼容性问题的服务。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-931">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="2fa0d-932">当你请求应用保证服务时，我们将与你在一起，通过符合条件的订阅免费解决有效的应用问题。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-932">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="2fa0d-933">我们还为在部署 Windows 虚拟桌面和新 Microsoft Edge 时面临兼容性问题的客户提供指导，并尽一切努力解决兼容性问题。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-933">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and the new Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="2fa0d-934">我们为以下 Microsoft 产品上部署的应用提供修正帮助：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-934">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="2fa0d-935"><strong>Windows 10 </strong> (包括 ARM64) </span><span class="sxs-lookup"><span data-stu-id="2fa0d-935"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="2fa0d-936"><strong>Microsoft 365 应用版</strong>  </span><span class="sxs-lookup"><span data-stu-id="2fa0d-936"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="2fa0d-937"><strong>新的 Microsoft Edge -</strong> 有关部署指南，请参阅 <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Microsoft Edge 频道概述</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-937"><strong>The new Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-938"><strong>Windows 虚拟桌面</strong> - 有关详细信息，请参阅什么是 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows 虚拟桌面？</a> 以及 <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 企业版多会话常见问题解答</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-938"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-939">

<strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-939">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="2fa0d-940">用于确定在 Windows 10 和 Microsoft 365 应用版上是否正常运作的应用清单和测试。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-940">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="2fa0d-941">有关此过程的更多指导，请访问<a href="https://go.microsoft.com/fwlink/?linkid=2080140">桌面部署中心</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-941">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="2fa0d-942">如果对深入升级就绪性评估感兴趣，请填写<a href="https://go.microsoft.com/fwlink/?linkid=2053818">新式桌面评估的客户请求</a>表单。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-942">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="2fa0d-943">研究 Windows 10 兼容性和支持语句的第三方 ISV 应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-943">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="2fa0d-944">有关详细信息，请参阅<a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">桌面分析</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-944">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="2fa0d-945">仅限应用打包的服务。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-945">App packaging-only services.</span></span> <span data-ttu-id="2fa0d-946">但是，应用保证团队会打包我们已为 Windows 10 修正的应用，以确保可以在客户环境中部署。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-946">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="2fa0d-947">

<strong>客户责任包括</strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-947">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="2fa0d-948">创建应用清单。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-948">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="2fa0d-949">验证 Windows 10 和 Microsoft 365 应用版上的应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-949">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="2fa0d-950">
<strong>注意：</strong>  Microsoft 无法更改源代码。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-950">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="2fa0d-951">但是，如果可提供应用的源代码，则应用保证团队可向应用开发人员提供指导。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-951">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="2fa0d-952">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-952">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="2fa0d-953"><strong>Windows 10 和 Microsoft 365 应用版</strong>
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-953"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="2fa0d-954">在 Windows 7、Windows 8.1、Office 2010 和 Office 2013 上运行的应用也可在 Windows 10 和 Microsoft 365 应用版上运行。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-954">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="2fa0d-955">
<strong>Windows 10 on ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-955">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="2fa0d-956">在 Windows 7、Office 2010 或更高版本上运行的应用也可在 ARM64 设备上在 Windows 10 和 Microsoft 365 应用版上运行。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-956">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="2fa0d-957">
  <strong>注意：</strong> 
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-957">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="2fa0d-958">x64 (64 位) 模拟适用于参与 Windows 预览体验 <a href="https://insider.windows.com/">计划的客户预览版</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-958">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="2fa0d-959">对于使用 Windows 10 版本 2004 (或更高版本) 的非 Windows 预览体验成员客户，ARM64 Photoshop 支持使用 OpenCL 和 <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL 兼容包</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-959">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="2fa0d-960">Windows 预览体验计划的客户可以下载预览体验成员版本的 OpenCL 和 OpenGL 兼容性包，以与其他应用一同使用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-960">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="2fa0d-961">
<strong>新的 Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-961">
<strong>The new Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="2fa0d-962">如果你的 Web 应用或网站适用于 Internet Explorer 11、受支持的 Google Chrome 版本或任何 Microsoft Edge 版本，则它们也将适用于新版 Microsoft Edge。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-962">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with the new Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-963">随着 Web 的不断发展，请务必查看 Microsoft Edge 的已知站点兼容性影响更改的 <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">已发布列表</a>。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-963">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="2fa0d-964">
  <strong>Windows 虚拟桌面 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-964">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="2fa0d-965">在 Windows Server 远程桌面会话主机 (RDSH) 上运行的虚拟化应用也可作为 Windows 虚拟桌面的一部分在 Windows 10 企业版多会话中运行。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-965">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-966">在任何 Windows 7 或 Windows 10 虚拟桌面基础结构 (VDI) 环境中运行的应用也会作为 Windows 虚拟桌面的一部分在 Windows 7 企业版 和 Windows 10 企业版上运行。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-966">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-967">在 Windows 7 或 Windows 10 客户端设备中运行的应用也可作为 Windows 虚拟桌面的一部分在 Windows 7 企业版和 Windows 10 企业版上运行。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-967">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="2fa0d-968">
  <strong>注意：</strong> Windows 10 企业版多会话兼容性排除和限制包括：</span><span class="sxs-lookup"><span data-stu-id="2fa0d-968">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="2fa0d-969">硬件重定向受到限制。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-969">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-970">A/V 密集型应用可能功能受限。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-970">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="2fa0d-971">64 位 Windows 虚拟桌面不支持 16 位应用。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-971">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="the-new-microsoft-edge"></a><span data-ttu-id="2fa0d-972">新版 Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="2fa0d-972">The new Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2fa0d-973"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-973"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="2fa0d-974"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-974"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="2fa0d-975"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="2fa0d-975"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="2fa0d-976"><strong>适用于 Windows</strong> 10 企业 (的 Microsoft Edge) </span><span class="sxs-lookup"><span data-stu-id="2fa0d-976"><strong>Microsoft Edge</strong> (for Windows 10 Enterprise customers)</span></span></td>
<td><ul>
<li>  <span data-ttu-id="2fa0d-977">我们提供远程部署指南和兼容性帮助：使用 Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager 或 Intune) 在 Windows 10 企业版上部署新的 Microsoft Edge。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-977">We provide remote deployment guidance and compatibility assistance for: Deploying the new Microsoft Edge on Windows 10 Enterprise with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-978">Microsoft Edge 配置 (组策略或 Intune 应用配置以及应用策略) 。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-978">Microsoft Edge configuration (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-979">清点可能需要在活动模式下使用Internet Explorer列表。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-979">Inventory the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="2fa0d-980">使用Internet Explorer站点列表启用启用模式。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-980">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span>  
  <span data-ttu-id="2fa0d-981">此外，如果你有一个使用 Internet Explorer Google Chrome 的 Web 应用或网站，并且你遇到兼容性问题，我们将指导你无需额外付费地解决问题。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-981">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="2fa0d-982">有关 <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">更多详细信息，</a> 请参阅应用保证。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-982">See <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#app-assure">App Assure</a> for more details.</span></span>  </li>
</ul><span data-ttu-id="2fa0d-983">

<strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="2fa0d-983">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="2fa0d-984">客户的 Microsoft Edge 部署的项目管理。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-984">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="2fa0d-985">现场支持。</span><span class="sxs-lookup"><span data-stu-id="2fa0d-985">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
