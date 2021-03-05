---
title: 产品和功能
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 2/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: 本主题包含有关 FastTrack 支持的工作负荷方案的详细信息，以及开始之前所需的源环境预期。 根据您的当前设置，我们一起制定修正计划，使源环境达到成功载入的最低要求。
ms.openlocfilehash: e49ada61aee869785f061bbebbee4ae14aaee045
ms.sourcegitcommit: 895a8b9df9a7cd26e27e95e5fd3145e7306c78e8
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/05/2021
ms.locfileid: "50464204"
---
# <a name="products-and-capabilities"></a><span data-ttu-id="9e50a-104">产品和功能</span><span class="sxs-lookup"><span data-stu-id="9e50a-104">Products and Capabilities</span></span>

## <a name="services-and-scenarios-supported-by-fasttrack"></a><span data-ttu-id="9e50a-105">FastTrack 支持的服务和方案</span><span class="sxs-lookup"><span data-stu-id="9e50a-105">Services and scenarios supported by FastTrack</span></span> 

<span data-ttu-id="9e50a-106">本主题包含有关 FastTrack 支持的工作负荷方案的详细信息，以及开始之前所需的源环境预期。</span><span class="sxs-lookup"><span data-stu-id="9e50a-106">This topic includes details on the workload scenarios supported by FastTrack and the source environment expectations necessary before we can begin.</span></span> <span data-ttu-id="9e50a-107">根据您的当前设置，我们一起制定修正计划，使源环境达到成功载入的最低要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-107">Based on your current setup, we work with you to create a remediation plan that brings your source environment up to the minimum requirements for successful onboarding.</span></span>

<span data-ttu-id="9e50a-108">FastTrack 提供指导，帮助你首先获得所有 (通用的核心Microsoft Online Services) ，然后载入每个符合条件的服务：</span><span class="sxs-lookup"><span data-stu-id="9e50a-108">FastTrack provides guidance to help you first with core capabilities (common for all Microsoft Online Services) and then with onboarding each eligible service:</span></span>

  - [<span data-ttu-id="9e50a-109">常规</span><span class="sxs-lookup"><span data-stu-id="9e50a-109">General</span></span>](#general)
  - [<span data-ttu-id="9e50a-110">安全性和符合性</span><span class="sxs-lookup"><span data-stu-id="9e50a-110">Security and Compliance</span></span>](#security-and-compliance)
  - [<span data-ttu-id="9e50a-111">Office 365</span><span class="sxs-lookup"><span data-stu-id="9e50a-111">Office 365</span></span>](#office-365)
  - [<span data-ttu-id="9e50a-112">企业移动性 + 安全性</span><span class="sxs-lookup"><span data-stu-id="9e50a-112">Enterprise Mobility + Security</span></span>](#enterprise-mobility--security)
  - [<span data-ttu-id="9e50a-113">Windows 10</span><span class="sxs-lookup"><span data-stu-id="9e50a-113">Windows 10</span></span>](#windows-10)
  - [<span data-ttu-id="9e50a-114">Windows 虚拟桌面</span><span class="sxs-lookup"><span data-stu-id="9e50a-114">Windows Virtual Desktop</span></span>](#windows-virtual-desktop)
  - [<span data-ttu-id="9e50a-115">应用保证</span><span class="sxs-lookup"><span data-stu-id="9e50a-115">App Assure</span></span>](#app-assure)
  - [<span data-ttu-id="9e50a-116">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="9e50a-116">Microsoft Edge</span></span>](#microsoft-edge)

> [!NOTE]
> <span data-ttu-id="9e50a-117">若要了解 Office 365 US Government 的源环境预期，请参阅 [Office 365 US Government 的源环境预期](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations)。</span><span class="sxs-lookup"><span data-stu-id="9e50a-117">For information on source environment expectations for Office 365 US Government, see [Source Environment Expectations for Office 365 US Government](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).</span></span> 
 
## <a name="general"></a><span data-ttu-id="9e50a-118">常规</span><span class="sxs-lookup"><span data-stu-id="9e50a-118">General</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9e50a-119"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-119"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="9e50a-120"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-120"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="9e50a-121"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-121"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9e50a-122"><strong>核心入门</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-122"><strong>Core onboarding</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-123">我们提供有关核心载入的远程指导，其中涉及服务预配、租户和标识集成。</span><span class="sxs-lookup"><span data-stu-id="9e50a-123">We provide remote guidance on core onboarding, which involves service provisioning, tenant, and identity integration.</span></span> <span data-ttu-id="9e50a-124">它还包括为载入服务（如 Exchange Online、SharePoint Online 和 Microsoft Teams）提供基础的步骤，包括有关安全性、网络连接性和合规性 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">的讨论</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-124">It also includes steps for providing a foundation for onboarding services like Exchange Online, SharePoint Online, and Microsoft Teams, including a <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">discussion on security, network connectivity, and compliance</a>.</span></span>  
  <span data-ttu-id="9e50a-125">在核心载入完成后，便可以开始载入一个或多个符合条件的服务。</span><span class="sxs-lookup"><span data-stu-id="9e50a-125">Onboarding for one or more eligible services can begin once core onboarding is finished.</span></span>
<span data-ttu-id="9e50a-126"></li>
</ul>  

<strong> 标识集成 </strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-126"></li>
</ul>  

<strong> Identity Integration </strong></span></span>

<span data-ttu-id="9e50a-127">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-127">We provide remote guidance for:</span></span>
<ul>
<li><span data-ttu-id="9e50a-128">准备本地 Active Directory 标识以同步到 Azure Active Directory (Azure AD) 包括安装和配置 Azure AD Connect (单林或多林) 以及许可 (包括基于组的许可) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-128">Preparing on-premises Active Directory Identities for synchronization to Azure Active Directory (Azure AD) including installing and configuring Azure AD Connect (single- or multi-forest) and licensing (including group-based licensing).</span></span></li>
<li><span data-ttu-id="9e50a-129">创建云标识，包括批量导入和许可，包括使用基于组的许可。</span><span class="sxs-lookup"><span data-stu-id="9e50a-129">Creating cloud identities including bulk import and licensing including using group-based licensing.</span></span></li>
<li><span data-ttu-id="9e50a-130">为云旅程、密码哈希同步、传递身份验证或 Active Directory 联合身份验证服务 (AD FS) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-130">Choosing and enabling the correct authentication method for your cloud journey, Password Hash Sync, Pass-through Authentication, or Active Directory Federation Services (AD FS).</span></span></li>
<li><span data-ttu-id="9e50a-131">为具有单个 Active Directory 林且标识与 Azure AD Connect 工具同步的客户启用 AD FS。</span><span class="sxs-lookup"><span data-stu-id="9e50a-131">Enabling AD FS for customers with a single Active Directory forest and identities synchronized with the Azure AD Connect tool.</span></span> <span data-ttu-id="9e50a-132">这需要Windows Server 2012 R2 Active Directory 联合身份验证服务 2.0 或更大。</span><span class="sxs-lookup"><span data-stu-id="9e50a-132">This requires Windows Server 2012 R2 Active Directory Federation Services 2.0 or greater.</span></span></li>
<li><span data-ttu-id="9e50a-133">使用密码哈希同步或传递身份验证将身份验证从 AD FS 迁移到 Azure AD。</span><span class="sxs-lookup"><span data-stu-id="9e50a-133">Migrating authentication from AD FS to Azure AD using Password Hash Sync or Pass-through Authentication.</span></span></li>
<li><span data-ttu-id="9e50a-134">将预集成应用 (如 Azure AD 库软件即服务 (SaaS) 应用) 从 AD FS 迁移到 Azure AD，实现单一登录 (SSO) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-134">Migrating pre-integrated apps (like Azure AD gallery software-as-a-service (SaaS) apps) from AD FS to Azure AD for single sign-on (SSO).</span></span></li>
<li><span data-ttu-id="9e50a-135">从 Azure AD 库启用 SaaS 应用与 SSO 的集成。</span><span class="sxs-lookup"><span data-stu-id="9e50a-135">Enabling SaaS app integrations with SSO from the Azure AD gallery.</span></span></li>
<li><span data-ttu-id="9e50a-136">为预集成 SaaS 应用启用自动用户预配，如应用集成教程列表 <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list"> (仅限于</a> Azure AD 库 SaaS 应用，而出站预配仅) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-136">Enabling automatic user provisioning for pre-integrated SaaS apps as listed in the <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">App integration tutorial list</a> (limited to Azure AD gallery SaaS apps and outbound provisioning only).</span></span>  </li>
</td>

<td>  <span data-ttu-id="9e50a-137"><strong>网络启用 </strong>  
  </span><span class="sxs-lookup"><span data-stu-id="9e50a-137"><strong>Network enablement </strong>  
  </span></span><br><span data-ttu-id="9e50a-138">作为 FastTrack 权益的一部分，我们建议你采用连接到云服务的最佳实践，以确保 Microsoft 365 的最高级别的性能。</span><span class="sxs-lookup"><span data-stu-id="9e50a-138">As part of the FastTrack benefit, we advise you as to best practices for connecting to cloud services to ensure the highest levels of performance of Microsoft 365.</span></span>  
  
<span data-ttu-id="9e50a-139"><strong>Active Directory 林</strong> 它们的功能林级别设置为 Windows Server 2003 前向，具有以下林配置：</span><span class="sxs-lookup"><span data-stu-id="9e50a-139"><strong>Active Directory forests</strong> These have the functional forest level set to Windows Server 2003 onward, with the following forest configuration:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-140">单个 Active Directory 林。</span><span class="sxs-lookup"><span data-stu-id="9e50a-140">A single Active Directory forest.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-141">单一 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。</span><span class="sxs-lookup"><span data-stu-id="9e50a-141">A single Active Directory account forest and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-142">多个 Active Directory 帐户林和资源林（Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business）拓扑。</span><span class="sxs-lookup"><span data-stu-id="9e50a-142">Multiple Active Directory account forests and resource forest (Exchange and/or Lync 2010, Lync 2013, or Skype for Business) topologies.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-143">多个 Active Directory 帐户林，其中的一个林是一个含有 Exchange 和/或 Lync 2010、Lync 2013 或 Skype for Business 的集中式 Active Directory 帐户林。</span><span class="sxs-lookup"><span data-stu-id="9e50a-143">Multiple Active Directory account forests with one of the forests being a centralized Active Directory account forest that includes Exchange and/or Lync 2010, Lync 2013, or Skype for Business.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-144">多个 Active Directory 帐户林，每一个都有自己的 Exchange 组织。</span><span class="sxs-lookup"><span data-stu-id="9e50a-144">Multiple Active Directory account forests, each with its own Exchange organization.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-145">租户配置和与 Azure Active Directory 集成所需的任务（如果需要）。</span><span class="sxs-lookup"><span data-stu-id="9e50a-145">Tasks required for tenant configuration and integration with Azure Active Directory, if needed.</span></span>   </li>
</ul><span data-ttu-id="9e50a-146">
  <strong>重要</strong>  </span><span class="sxs-lookup"><span data-stu-id="9e50a-146">
  <strong>Important</strong>  </span></span><ul>
<li>  <span data-ttu-id="9e50a-147">对于多林 Active Directory 方案，如果部署了 Lync 2010、Lync 2013 或 Skype for Business，则必须将其部署在 Exchange 相同的 Active Directory 林中。</span><span class="sxs-lookup"><span data-stu-id="9e50a-147">For multi-forest Active Directory scenarios, if Lync 2010, Lync 2013, or Skype for Business is deployed, it must be deployed in the same Active Directory forest as Exchange.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-148">在 Exchange 多混合配置中使用多个 Exchange 组织实现多个 Active Directory 林时，不支持在源林之间 (UPN) 命名空间的共享用户主体名称。</span><span class="sxs-lookup"><span data-stu-id="9e50a-148">When implementing multiple Active Directory forests with multiple Exchange organizations in an Exchange multi-hybrid configuration, shared user principal name (UPN) namespaces between source forests aren't supported.</span></span> <span data-ttu-id="9e50a-149">Exchange 组织之间的主要 SMTP 命名空间也应该进行分隔。</span><span class="sxs-lookup"><span data-stu-id="9e50a-149">Primary SMTP namespaces between Exchange organizations should also be separated.</span></span> <span data-ttu-id="9e50a-150">有关详细信息，请参阅 <a href="https://go.microsoft.com/fwlink/?linkid=845444">具有多个 Active Directory 林的混合部署</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-150">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=845444">Hybrid deployments with multiple Active Directory forests</a>.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-151">对于所有多林配置，Active Directory 联合身份验证服务 (AD FS) 部署超出范围。</span><span class="sxs-lookup"><span data-stu-id="9e50a-151">For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope.</span></span> <span data-ttu-id="9e50a-152">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-152">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9e50a-153"><strong>Microsoft 365 应用版</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-153"><strong>Microsoft 365 Apps</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-154">我们提供远程部署指南，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-154">We provide remote deployment guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-155">解决部署问题。</span><span class="sxs-lookup"><span data-stu-id="9e50a-155">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-156">使用 Microsoft 365 管理中心和 Windows PowerShell 分配基于最终用户和设备的许可证。</span><span class="sxs-lookup"><span data-stu-id="9e50a-156">Assigning end-user and device-based licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-157">使用即点即用从 Office 365 门户安装 Microsoft 365 应用版。</span><span class="sxs-lookup"><span data-stu-id="9e50a-157">Installing Microsoft 365 Apps from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-158">在 iOS 或 Android 设备上安装 Office Mobile 应用（如 Outlook Mobile、Word Mobile、Excel Mobile 和 PowerPoint Mobile）。</span><span class="sxs-lookup"><span data-stu-id="9e50a-158">Installing Office Mobile apps (like Outlook Mobile, Word Mobile, Excel Mobile, and PowerPoint Mobile) on your iOS or Android devices.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-159">使用 Office 365 部署工具配置更新设置。</span><span class="sxs-lookup"><span data-stu-id="9e50a-159">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-160">本地或云安装的选择和设置。</span><span class="sxs-lookup"><span data-stu-id="9e50a-160">Selection and setup of a local or cloud installation.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-161">使用 Office 自定义工具或用于配置部署包的本地 XML 创建 Office 部署工具配置 XML。</span><span class="sxs-lookup"><span data-stu-id="9e50a-161">Creation of the Office Deployment Tool configuration XML with the Office Customization Tool or native XML to configure the deployment package.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-162">使用 Microsoft Endpoint Configuration Manager 的部署，包括帮助创建 Microsoft Endpoint Configuration Manager 打包。</span><span class="sxs-lookup"><span data-stu-id="9e50a-162">Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.</span></span>  
  <span data-ttu-id="9e50a-163">此外，如果你有一个使用 Office 早期版本的宏或外接程序，并且你遇到兼容性问题，我们会指导你通过应用保证计划免费修复兼容性问题。</span><span class="sxs-lookup"><span data-stu-id="9e50a-163">Additionally, if you have a macro or add-in that worked with prior versions of Office and you experience compatibility issues, we provide guidance to remediate the compatibility issue at no additional cost through the App Assure program.</span></span> <span data-ttu-id="9e50a-164">有关详细信息， <strong>请参阅</strong> Windows <a href="#windows-10">10</a> 的应用保证部分。</span><span class="sxs-lookup"><span data-stu-id="9e50a-164">See the <strong>App Assure</strong> portion of <a href="#windows-10">Windows 10</a> for more details.</span></span> </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="9e50a-165">联机客户端软件必须达到 Microsoft <a href="https://go.microsoft.com/fwlink/?LinkID=723597">365</a>和 Office 的系统要求中定义的最低级别。</span><span class="sxs-lookup"><span data-stu-id="9e50a-165">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9e50a-166"><strong>网络运行状况</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-166"><strong>Network health</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-167">我们提供远程指导，以便从你的环境中获取和解释关键网络连接数据，显示组织网站如何与 Microsoft 的网络连接 <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">原则保持一致</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-167">We provide remote guidance with obtaining and interpreting key network connectivity data from your environment showing how aligned your organization’s sites are to Microsoft’s <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">principles of network connectivity</a>.</span></span> <span data-ttu-id="9e50a-168">这突出显示了直接影响迁移速度、用户体验、服务性能和可靠性的网络分数。</span><span class="sxs-lookup"><span data-stu-id="9e50a-168">This highlights your network score which directly impacts migration velocity, user experience, service performance, and reliability.</span></span>  
  <span data-ttu-id="9e50a-169">我们还指导你完成此数据突出显示的任何修正步骤，以帮助你提高网络分数。</span><span class="sxs-lookup"><span data-stu-id="9e50a-169">We also guide you through any remediation steps highlighted by this data to help you improve your network score.</span></span>  </td>
<td><ul>
<li>  <span data-ttu-id="9e50a-170">Microsoft 365 管理中心访问权限。</span><span class="sxs-lookup"><span data-stu-id="9e50a-170">Microsoft 365 Admin Center access.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-171">需要最新版本的 Microsoft 365 应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-171">Up-to-date versions of Microsoft 365 apps are required.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-172">根据 Microsoft 365 管理中心预览版中的网络性能建议<a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview"> (定位) 。 </a></span><span class="sxs-lookup"><span data-stu-id="9e50a-172">Location services enabled as per <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">Network performance recommendations in the Microsoft 365 Admin Center (preview)</a>.</span></span>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a><span data-ttu-id="9e50a-173">安全性和合规性</span><span class="sxs-lookup"><span data-stu-id="9e50a-173">Security and Compliance</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9e50a-174"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-174"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="9e50a-175"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-175"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="9e50a-176"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-176"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><span data-ttu-id="9e50a-177"><strong>Azure Active Directory (Azure AD) 和 Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-177"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-178">我们针对以下方案提供用于保护云标识的远程指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-178">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="9e50a-179">

<strong>安全的基础基础结构</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="9e50a-179">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="9e50a-180">为标识配置和启用强身份验证，包括使用 Azure 多重身份验证 (MFA)  (云仅) 、Microsoft Authenticator 应用以及 Azure MFA 和自助服务密码重置 (SSPR) 的组合注册进行保护。</span><span class="sxs-lookup"><span data-stu-id="9e50a-180">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-181">对于非 Azure AD Premium 客户，提供了使用安全默认值保护标识的指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-181">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-182">对于 Azure AD 高级客户，提供了使用条件访问保护标识的指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-182">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-183">通过 Azure AD 密码保护检测和阻止使用弱密码。</span><span class="sxs-lookup"><span data-stu-id="9e50a-183">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-184">使用 Azure AD 应用程序代理保护对本地 Web 应用的远程访问。</span><span class="sxs-lookup"><span data-stu-id="9e50a-184">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-185">使用 Azure Identity Protection 启用基于风险的检测和修正。</span><span class="sxs-lookup"><span data-stu-id="9e50a-185">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-186">启用自定义登录屏幕，包括徽标、文本和具有自定义品牌的图像。</span><span class="sxs-lookup"><span data-stu-id="9e50a-186">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-187">使用 Azure AD B2B 安全地与来宾用户共享应用和服务。</span><span class="sxs-lookup"><span data-stu-id="9e50a-187">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-188">使用基于角色的访问控制 (RBAC) 内置管理角色管理 Office 365 管理员的访问权限，并减少特权管理员帐户的数量。</span><span class="sxs-lookup"><span data-stu-id="9e50a-188">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-189">配置混合 Azure AD 加入。</span><span class="sxs-lookup"><span data-stu-id="9e50a-189">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-190">配置 Azure AD 加入。</span><span class="sxs-lookup"><span data-stu-id="9e50a-190">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="9e50a-191">
  
<strong>监视和报告</strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-191">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="9e50a-192">使用 Azure AD Connect Health 为 AD FS、Azure AD Connect 和域控制器启用远程监视。</span><span class="sxs-lookup"><span data-stu-id="9e50a-192">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="9e50a-193">
  
<strong>治理</strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-193">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="9e50a-194">通过 Azure AD 权利管理大规模管理 Azure AD 标识和访问生命周期。</span><span class="sxs-lookup"><span data-stu-id="9e50a-194">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="9e50a-195">使用 Azure AD 访问评审管理 Azure AD 组成员身份、企业应用访问权限和角色分配。</span><span class="sxs-lookup"><span data-stu-id="9e50a-195">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-196">查看 Azure AD 使用条款。</span><span class="sxs-lookup"><span data-stu-id="9e50a-196">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-197">使用 Azure AD Privileged Identity Management 管理和控制对特权管理员帐户的访问。</span><span class="sxs-lookup"><span data-stu-id="9e50a-197">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="9e50a-198">
  
<strong>自动化和效率 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-198">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="9e50a-199">启用 Azure AD SSPR。</span><span class="sxs-lookup"><span data-stu-id="9e50a-199">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="9e50a-200">允许用户使用 Azure AD 自助服务组管理创建和管理自己的云安全或 Office 365 组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-200">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-201">使用 Azure AD 委派组管理管理企业应用的委派访问权限。</span><span class="sxs-lookup"><span data-stu-id="9e50a-201">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-202">启用 Azure AD 动态组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-202">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-203">使用集合在"我的应用"门户中组织应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-203">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="9e50a-204">本地 Active Directory 及其环境已针对 Azure AD Premium 做好准备，包括修复阻止与 Azure AD 和 Azure AD Premium 功能集成的已识别问题。</span><span class="sxs-lookup"><span data-stu-id="9e50a-204">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9e50a-205"><strong>Azure 信息保护 </strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-205"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="9e50a-206">有关 Azure 信息保护详细信息，请参阅 <strong>此表中的 Microsoft 信息</strong> 保护。</span><span class="sxs-lookup"><span data-stu-id="9e50a-206">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> further in this table.</span></span>

  </td>
<td>  
  <tr class="odd">
<td><span data-ttu-id="9e50a-207"><strong>发现&响应</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-207"><strong>Discovery & Response</strong></span></span></td>
<td>  

<span data-ttu-id="9e50a-208"><strong>高级电子数据展示</strong>
  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-208"><strong>Advanced eDiscovery</strong>
  
</span></span><ul>
<li>  <span data-ttu-id="9e50a-209">启用安全链接、安全附件和防钓鱼。</span><span class="sxs-lookup"><span data-stu-id="9e50a-209">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-210">配置自动化、调查和响应。</span><span class="sxs-lookup"><span data-stu-id="9e50a-210">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-211">使用攻击模拟器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-211">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-212">报告和威胁分析。</span><span class="sxs-lookup"><span data-stu-id="9e50a-212">Reporting and threat analytics.</span></span>  </li>
</ul>

<span data-ttu-id="9e50a-213"><strong>仅 (</strong> E5 版本支持高级审核) </span><span class="sxs-lookup"><span data-stu-id="9e50a-213"><strong>Advanced Audit</strong> (only supported in E5)</span></span>

<span data-ttu-id="9e50a-214">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-214">We provide remote guidance for:</span></span>  
<ul>
<li> <span data-ttu-id="9e50a-215">启用高级审核。</span><span class="sxs-lookup"><span data-stu-id="9e50a-215">Enabling advanced auditing.</span></span></li>
<li> <span data-ttu-id="9e50a-216">使用 UI 和审核日志审核 PowerShell 命令执行搜索。</span><span class="sxs-lookup"><span data-stu-id="9e50a-216">Performing a search audit log UI and basic audit PowerShell commands.</span></span></li>
</ul><span data-ttu-id="9e50a-217">

<strong> 合规性管理器</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-217">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="9e50a-218">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-218">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="9e50a-219">查看角色类型。</span><span class="sxs-lookup"><span data-stu-id="9e50a-219">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="9e50a-220">添加和配置评估。</span><span class="sxs-lookup"><span data-stu-id="9e50a-220">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="9e50a-221">通过实施改进操作和确定这如何影响合规性分数来评估合规性。</span><span class="sxs-lookup"><span data-stu-id="9e50a-221">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="9e50a-222">查看内置控件映射和评估控件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-222">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="9e50a-223">在评估内生成报告。</span><span class="sxs-lookup"><span data-stu-id="9e50a-223">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="9e50a-224">

<strong>以下内容超出范围 </strong> 
</span><span class="sxs-lookup"><span data-stu-id="9e50a-224">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="9e50a-225">自定义脚本或编码。</span><span class="sxs-lookup"><span data-stu-id="9e50a-225">Custom scripting or coding.</span></span></li>
<li> <span data-ttu-id="9e50a-226">电子数据展示 API。</span><span class="sxs-lookup"><span data-stu-id="9e50a-226">eDiscovery API.</span></span> </li>
<li> <span data-ttu-id="9e50a-227">数据连接器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-227">Data connectors.</span></span> </li>
<li> <span data-ttu-id="9e50a-228">合规性边界和安全筛选器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-228">Compliance boundaries and security filters.</span></span></li>
<li> <span data-ttu-id="9e50a-229">数据调查。</span><span class="sxs-lookup"><span data-stu-id="9e50a-229">Data investigations.</span></span></li>
<li> <span data-ttu-id="9e50a-230">数据主体请求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-230">Data subject requests.</span></span></li>
<li> <span data-ttu-id="9e50a-231">设计、架构师和第三方文档审阅。</span><span class="sxs-lookup"><span data-stu-id="9e50a-231">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="9e50a-232">遵守行业和区域法规和要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-232">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="9e50a-233">合规性管理器中评估的建议改进措施的动手实施。</span><span class="sxs-lookup"><span data-stu-id="9e50a-233">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>
</td>
<td><span data-ttu-id="9e50a-234">除了"<strong>常规"中的核心</strong>载入部分<a href="#general"></a>外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-234">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>

<tr class="odd">
<td><span data-ttu-id="9e50a-235"><strong>预览体验成员威胁管理</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-235"><strong>Insider Threat Management</strong></span></span></td>

<td>  <span data-ttu-id="9e50a-236">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-236">We provide remote guidance for:</span></span>
<ul>
<li> <span data-ttu-id="9e50a-237">创建策略并查看设置。</span><span class="sxs-lookup"><span data-stu-id="9e50a-237">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="9e50a-238">访问报告和警报。</span><span class="sxs-lookup"><span data-stu-id="9e50a-238">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="9e50a-239">创建案例。</span><span class="sxs-lookup"><span data-stu-id="9e50a-239">Creating cases.</span></span></li>
<li> <span data-ttu-id="9e50a-240">创建通知模板。</span><span class="sxs-lookup"><span data-stu-id="9e50a-240">Creating notice templates.</span></span></li>
<li> <span data-ttu-id="9e50a-241">有关通过 HR 连接器 (人力资源) 指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-241">Guidance on creating the human resources (HR) connector.</span></span></li>
</ul><span data-ttu-id="9e50a-242">

<strong> 通信合规性 </strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-242">

<strong> Communication Compliance </strong></span></span> 

<span data-ttu-id="9e50a-243">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-243">We provide remote guidance for:</span></span> 
<ul>
<li> <span data-ttu-id="9e50a-244">创建策略并查看设置。</span><span class="sxs-lookup"><span data-stu-id="9e50a-244">Creating policies and reviewing settings.</span></span></li>
<li> <span data-ttu-id="9e50a-245">访问报告和警报。</span><span class="sxs-lookup"><span data-stu-id="9e50a-245">Accessing reports and alerts.</span></span></li>
<li> <span data-ttu-id="9e50a-246">创建通知模板。</span><span class="sxs-lookup"><span data-stu-id="9e50a-246">Creating notice templates.</span></span></li>
</ul><span data-ttu-id="9e50a-247">

<strong> 合规性管理器</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-247">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="9e50a-248">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-248">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="9e50a-249">查看角色类型。</span><span class="sxs-lookup"><span data-stu-id="9e50a-249">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="9e50a-250">添加和配置评估。</span><span class="sxs-lookup"><span data-stu-id="9e50a-250">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="9e50a-251">通过实施改进操作和确定这如何影响合规性分数来评估合规性。</span><span class="sxs-lookup"><span data-stu-id="9e50a-251">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="9e50a-252">查看内置控件映射和评估控件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-252">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="9e50a-253">在评估内生成报告。</span><span class="sxs-lookup"><span data-stu-id="9e50a-253">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="9e50a-254">

<strong>以下内容超出范围 </strong> 
</span><span class="sxs-lookup"><span data-stu-id="9e50a-254">

<strong>The following is out of scope </strong> 
</span></span><ul>
<li> <span data-ttu-id="9e50a-255">创建和管理 Power Automate 流。</span><span class="sxs-lookup"><span data-stu-id="9e50a-255">Creating and managing Power Automate flows.</span></span></li>
<li> <span data-ttu-id="9e50a-256">数据连接器 (HR 连接器之外) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-256">Data connectors (beyond the HR connector).</span></span> </li>
<li> <span data-ttu-id="9e50a-257">RegEx (配置) 正则表达式。</span><span class="sxs-lookup"><span data-stu-id="9e50a-257">Custom regular expression (RegEx) configurations.</span></span></li>
<li> <span data-ttu-id="9e50a-258">设计、架构师和第三方文档审阅。</span><span class="sxs-lookup"><span data-stu-id="9e50a-258">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="9e50a-259">信息障碍。</span><span class="sxs-lookup"><span data-stu-id="9e50a-259">Information barriers.</span></span></li>
<li> <span data-ttu-id="9e50a-260">特权访问管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-260">Privileged access management.</span></span></li>
<li> <span data-ttu-id="9e50a-261">遵守行业和区域法规和要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-261">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="9e50a-262">合规性管理器中评估的建议改进措施的动手实施。</span><span class="sxs-lookup"><span data-stu-id="9e50a-262">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul></td>
<td><span data-ttu-id="9e50a-263">除了"<strong>常规"中的核心</strong>载入部分<a href="#general"></a>外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-263">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</td>
</tr>

<tr class="even">
<td><span data-ttu-id="9e50a-264"><strong>Microsoft 365 Defender</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-264"><strong>Microsoft 365 Defender</strong></span></span></td>

<td> <p> <span data-ttu-id="9e50a-265">Microsoft 365 Defender 是一个统一的攻破前和攻破后企业防御套件，在本机协调跨终结点、标识、电子邮件和应用进行检测、预防、调查和响应，以提供针对复杂攻击的集成保护。</span><span class="sxs-lookup"><span data-stu-id="9e50a-265">Microsoft 365 Defender is a unified pre- and post-breach enterprise defense suite that natively coordinates detection, prevention, investigation, and response across endpoints, identities, email, and apps to provide integrated protection against sophisticated attacks.</span></span> <span data-ttu-id="9e50a-266">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-266">We provide remote guidance for:</span></span> </p> 
<ul>
<li>  <span data-ttu-id="9e50a-267">提供 Microsoft 365 安全中心概述。</span><span class="sxs-lookup"><span data-stu-id="9e50a-267">Providing an overview of the Microsoft 365 security center.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-268">查看跨产品事件，包括通过确保完整的攻击范围、受影响的资产和组合在一起的自动修正操作来重点关注关键事件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-268">Reviewing cross-product incidents, including focusing on what's critical by ensuring the full attack scope, impacted assets, and automated remediation actions that are grouped together.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-269">演示 Microsoft 365 Defender 如何协调对资产、用户、设备和邮箱的调查，这些资产、用户、设备和邮箱可能由于自动自我修复而受到威胁。</span><span class="sxs-lookup"><span data-stu-id="9e50a-269">Demonstrating how Microsoft 365 Defender can orchestrate the investigation of assets, users, devices, and mailboxes that might have been compromised through automated self-healing.</span></span> </li>
<li>  <span data-ttu-id="9e50a-270">解释并提供客户如何跨多个数据集主动搜寻影响电子邮件、数据、设备和帐户的入侵尝试和泄露活动的示例。</span><span class="sxs-lookup"><span data-stu-id="9e50a-270">Explaining and providing examples of how customers can proactively hunt for intrusion attempts and breach activity affecting your email, data, devices, and accounts across multiple data sets.</span></span>   </li>
<li> <span data-ttu-id="9e50a-271">显示客户如何使用 Microsoft 安全分数全面查看和改进其安全状况。</span><span class="sxs-lookup"><span data-stu-id="9e50a-271">Showing customers how they can review and improve their security posture holistically using Microsoft Secure Score.</span></span></li>
</ul>
<p><span data-ttu-id="9e50a-272"><strong>以下内容超出范围</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-272"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="9e50a-273">客户补救活动的项目管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-273">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="9e50a-274">持续管理、威胁响应和修正。</span><span class="sxs-lookup"><span data-stu-id="9e50a-274">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="9e50a-275">部署指南或教育：：</span><span class="sxs-lookup"><span data-stu-id="9e50a-275">Deployment guidance or education on:</span></span>
<ul>
<li> <span data-ttu-id="9e50a-276">如何修正或解释各种警报类型和受监视的活动。</span><span class="sxs-lookup"><span data-stu-id="9e50a-276">How to remediate or interpret the various alert types and monitored activities.</span></span> </li>
<li> <span data-ttu-id="9e50a-277">如何调查用户、计算机、横向移动路径或实体。</span><span class="sxs-lookup"><span data-stu-id="9e50a-277">How to investigate a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="9e50a-278">自定义威胁搜寻。</span><span class="sxs-lookup"><span data-stu-id="9e50a-278">Custom threat hunting.</span></span>  </li>
</ul>
</li>
<li> <span data-ttu-id="9e50a-279">SIEM 或 API 集成 (安全) 事件管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-279">Security information and event management (SIEM) or API integration.</span></span></li>
</td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9e50a-280"><strong>Microsoft Cloud App Security</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-280"><strong>Microsoft Cloud App Security</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-281">Microsoft Cloud App Security 是云访问安全代理 (CASB) ，可提供丰富的可见性、控制数据旅行以及复杂的分析，以识别和防御所有 Microsoft 和第三方云服务中的网络威胁。</span><span class="sxs-lookup"><span data-stu-id="9e50a-281">Microsoft Cloud App Security is a Cloud Access Security Broker (CASB) that provides rich visibility, control over data travel, and sophisticated analytics to identify and combat cyber threats across all your Microsoft and third-party cloud services.</span></span> <span data-ttu-id="9e50a-282">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-282">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-283">配置门户，包括：</span><span class="sxs-lookup"><span data-stu-id="9e50a-283">Configuring the portal, including:</span></span>  </li>
<ul>
<li> <span data-ttu-id="9e50a-284">导入用户组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-284">Importing user groups.</span></span></li>
<li> <span data-ttu-id="9e50a-285">管理管理员访问权限和设置。</span><span class="sxs-lookup"><span data-stu-id="9e50a-285">Managing admin access and settings.</span></span>  </li>
<li> <span data-ttu-id="9e50a-286">界定部署范围以选择要监视或排除监视的某些用户组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-286">Scoping your deployment to select certain user groups to monitor or exclude from monitoring.</span></span></li>
<li> <span data-ttu-id="9e50a-287">设置 IP 范围和标记。</span><span class="sxs-lookup"><span data-stu-id="9e50a-287">Setting IP ranges and tags.</span></span></li>
<li> <span data-ttu-id="9e50a-288">使用徽标和自定义消息对最终用户体验进行个性化设置。</span><span class="sxs-lookup"><span data-stu-id="9e50a-288">Personalizing the end-user experience with your logo and custom messaging.</span></span></li>
</ul>
<li> <span data-ttu-id="9e50a-289">设置云发现以使用：</span><span class="sxs-lookup"><span data-stu-id="9e50a-289">Setting up cloud discovery to provide shadow IT using:</span></span></li>
<ul>
<li> <span data-ttu-id="9e50a-290">适用于终结点的 Microsoft Defender。</span><span class="sxs-lookup"><span data-stu-id="9e50a-290">Microsoft Defender for Endpoints.</span></span></li>
<li> <span data-ttu-id="9e50a-291">Zscaler。</span><span class="sxs-lookup"><span data-stu-id="9e50a-291">Zscaler.</span></span></li>
<li> <span data-ttu-id="9e50a-292">iboss。</span><span class="sxs-lookup"><span data-stu-id="9e50a-292">iboss.</span></span></li>
</ul>
<li> <span data-ttu-id="9e50a-293">使用 <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">应用连接器</a> 连接特色应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-293">Connecting <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">featured apps</a> using app connectors.</span></span></li>
<li> <span data-ttu-id="9e50a-294">在条件访问和云应用安全门户中设置条件访问应用控件以应用实时会话控件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-294">Setting up Conditional Access App Control in the Conditional Access and Cloud App Security portals to apply real time session controls.</span></span></li>
<li> <span data-ttu-id="9e50a-295">部署 Cloud App Security 和 Cloud Discovery 仪表板。</span><span class="sxs-lookup"><span data-stu-id="9e50a-295">Deploying the Cloud App Security and Cloud Discovery dashboards.</span></span></li>
<li> <span data-ttu-id="9e50a-296">根据组织优先级自定义应用风险评分。</span><span class="sxs-lookup"><span data-stu-id="9e50a-296">Customizing app risk scores based on your organization’s priorities.</span></span></li>
<li> <span data-ttu-id="9e50a-297">创建应用标记和类别。</span><span class="sxs-lookup"><span data-stu-id="9e50a-297">Creating app tags and categories.</span></span></li>
<li> <span data-ttu-id="9e50a-298">批准和取消批准应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-298">Sanctioning and unsanctioning apps.</span></span></li>
<li> <span data-ttu-id="9e50a-299">使用活动和文件日志。</span><span class="sxs-lookup"><span data-stu-id="9e50a-299">Using the activity and file logs.</span></span></li>
<li> <span data-ttu-id="9e50a-300">管理 OAuth 应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-300">Managing OAuth apps.</span></span></li>
<li> <span data-ttu-id="9e50a-301">了解 Microsoft 365 Defender 门户中的事件关联。</span><span class="sxs-lookup"><span data-stu-id="9e50a-301">Understanding incident correlation in the Microsoft 365 Defender portal.</span></span></li>
<li> <span data-ttu-id="9e50a-302">为 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">CASB 的前 20</a> 个用例提供配置帮助 (包括创建或更新最多六个 6 (6) 策略，) 除外：</span><span class="sxs-lookup"><span data-stu-id="9e50a-302">Providing configuration assistance with the <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">top 20 use cases for CASBs</a> (including the creation or updating of up to six (6) policies) except:</span></span> </li>
<ul>
<li> <span data-ttu-id="9e50a-303">审核作为服务服务的 Internet 配置， (IaaS) 环境 (#18) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-303">Auditing the configuration of your internet as a service (IaaS) environments (#18).</span></span></li>
<li> <span data-ttu-id="9e50a-304">监视用户活动，防止 IaaS 环境中 (#19) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-304">Monitoring user activities to protect against threats in your IaaS environments (#19).</span></span></li>
</ul>
</ul>
<p><span data-ttu-id="9e50a-305"><strong>以下内容超出范围</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-305"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li> <span data-ttu-id="9e50a-306">客户补救活动的项目管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-306">Project management of the customer's remediation activities.</span></span></li>
<li> <span data-ttu-id="9e50a-307">持续管理、威胁响应和修正。</span><span class="sxs-lookup"><span data-stu-id="9e50a-307">Ongoing management, threat response, and remediation.</span></span> </li>
<li> <span data-ttu-id="9e50a-308">使用 Docker 或日志收集器为连续报告设置自动日志上载的基础结构、安装或部署。</span><span class="sxs-lookup"><span data-stu-id="9e50a-308">Setting up the infrastructure, installation, or deployment of automatic log uploads for continuous reports using Docker or a log collector.</span></span> <span data-ttu-id="9e50a-309">有关详细信息 <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">，请参阅 CASB 的前 20</a> 个用例。</span><span class="sxs-lookup"><span data-stu-id="9e50a-309">See <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">Top 20 use cases for CASBs</a> for more details.</span></span></li>
<li> <span data-ttu-id="9e50a-310">创建云发现快照报告。</span><span class="sxs-lookup"><span data-stu-id="9e50a-310">Creating a Cloud Discovery snapshot report.</span></span></li>
<li> <span data-ttu-id="9e50a-311">使用块脚本阻止应用使用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-311">Blocking app usage using block scripts.</span></span></li>
<li> <span data-ttu-id="9e50a-312">连接自定义应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-312">Connecting custom apps.</span></span></li>
<li> <span data-ttu-id="9e50a-313">与第三方标识提供程序 (ISP) DLP (数据丢失防护) 集成。</span><span class="sxs-lookup"><span data-stu-id="9e50a-313">Integrating with third-party identity providers (IsPs) and data loss prevention (DLP) providers.</span></span></li>
<li> <span data-ttu-id="9e50a-314">有关高级搜寻的培训或指导。</span><span class="sxs-lookup"><span data-stu-id="9e50a-314">Training or guidance covering advanced hunting.</span></span></li>
<li> <span data-ttu-id="9e50a-315">自动调查和修正，包括 Microsoft Power Automate 操作手册。</span><span class="sxs-lookup"><span data-stu-id="9e50a-315">Automated investigation and remediation including Microsoft Power Automate playbooks.</span></span></li>
<li> <span data-ttu-id="9e50a-316">SIEM 安全信息和事件 (SIEM) API 集成 (包括 Azure Sentinel) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-316">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span></li>
<li> <span data-ttu-id="9e50a-317">部署云应用发现作为概念证明。</span><span class="sxs-lookup"><span data-stu-id="9e50a-317">Deploying Cloud App Discovery as a proof of concept.</span></span></li>
</ul></td>
</tr>



<tr class="even">
<td><span data-ttu-id="9e50a-318"><strong>Microsoft Defender 高级威胁防护 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-318"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-319">Microsoft Defender 高级威胁防护 (ATP) 是旨在帮助企业网络预防、检测、调查和响应高级威胁的平台。</span><span class="sxs-lookup"><span data-stu-id="9e50a-319">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="9e50a-320">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-320">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-321">部署用于保护终结点的技术。</span><span class="sxs-lookup"><span data-stu-id="9e50a-321">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-322">配置终结点保护和设备限制配置文件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-322">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-323">评估操作系统版本和设备管理 (包括 Intune、Microsoft Endpoint Configuration Manager、组策略对象 (GPO) 和第三方配置) 以及 Windows Defender AV 服务或其他终结点安全软件的状态。</span><span class="sxs-lookup"><span data-stu-id="9e50a-323">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-324">评估 Windows AV 服务或其他终结点安全软件的状态。</span><span class="sxs-lookup"><span data-stu-id="9e50a-324">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-325">评估限制网络流量的代理和防火墙。</span><span class="sxs-lookup"><span data-stu-id="9e50a-325">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-326">通过说明如何使用载入终结点部署 ATP 代理配置文件来启用 Microsoft Defender ATP 服务。</span><span class="sxs-lookup"><span data-stu-id="9e50a-326">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-327">部署指南、配置协助和教育：</span><span class="sxs-lookup"><span data-stu-id="9e50a-327">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="9e50a-328">威胁和漏洞管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-328">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-329">攻击面减少。</span><span class="sxs-lookup"><span data-stu-id="9e50a-329">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-330">新一代保护。</span><span class="sxs-lookup"><span data-stu-id="9e50a-330">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-331">终结点检测和响应。</span><span class="sxs-lookup"><span data-stu-id="9e50a-331">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-332">自动调查和修复。</span><span class="sxs-lookup"><span data-stu-id="9e50a-332">Automated investigation and remediation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-333">安全功能分数。</span><span class="sxs-lookup"><span data-stu-id="9e50a-333">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="9e50a-334">查看模拟和教程 (方案、虚假恶意软件和自动调查等) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-334">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-335">报告和威胁分析功能概述。</span><span class="sxs-lookup"><span data-stu-id="9e50a-335">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-336">将 Office 365 ATP 与 Microsoft Defender ATP 集成。</span><span class="sxs-lookup"><span data-stu-id="9e50a-336">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-337">在 Microsoft Defender 安全中心门户中执行演练。</span><span class="sxs-lookup"><span data-stu-id="9e50a-337">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-338">以下操作系统：</span><span class="sxs-lookup"><span data-stu-id="9e50a-338">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="9e50a-339">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="9e50a-339">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-340">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="9e50a-340">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-341">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="9e50a-341">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-342">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="9e50a-342">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-343">Windows Server Semi-Annual Channel (SAC) 版本 1803。</span><span class="sxs-lookup"><span data-stu-id="9e50a-343">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-344">macOS 版本 10.13、10.14 和 10.15。</span><span class="sxs-lookup"><span data-stu-id="9e50a-344">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="9e50a-345">
<strong>注意：</strong> 所有 Windows Server 版本都必须由最新版本的 System Center Configuration Manager 2012 (版本 1012 R2、1511 或 1602) 或 Microsoft Endpoint Configuration Manager (版本 2002 或) 管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-345">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="9e50a-346"></li>
</ul>

<strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-346"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="9e50a-347">客户补救活动的项目管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-347">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-348">现场支持。</span><span class="sxs-lookup"><span data-stu-id="9e50a-348">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-349">持续管理和威胁响应。</span><span class="sxs-lookup"><span data-stu-id="9e50a-349">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-350">以下 Microsoft Defender ATP 代理的加入或配置：</span><span class="sxs-lookup"><span data-stu-id="9e50a-350">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="9e50a-351">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="9e50a-351">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-352">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="9e50a-352">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-353">Linux。</span><span class="sxs-lookup"><span data-stu-id="9e50a-353">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-354">Android 和 iOS (移动设备) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-354">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="9e50a-355">虚拟桌面基础结构 (VDI)  (持久或非永久性) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-355">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9e50a-356">服务器载入和配置：</span><span class="sxs-lookup"><span data-stu-id="9e50a-356">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="9e50a-357">为脱机通信配置代理服务器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-357">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-358">在下层 Configuration Manager 实例和版本上配置 Configuration Manager 部署包。</span><span class="sxs-lookup"><span data-stu-id="9e50a-358">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-359">将服务器载入 Azure 安全中心。</span><span class="sxs-lookup"><span data-stu-id="9e50a-359">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-360">未由 Configuration Manager 管理的服务器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-360">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="9e50a-361">macOS 载入和配置：</span><span class="sxs-lookup"><span data-stu-id="9e50a-361">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="9e50a-362">基于 Intune 的手动部署。</span><span class="sxs-lookup"><span data-stu-id="9e50a-362">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-363">基于 JAMF 的部署。</span><span class="sxs-lookup"><span data-stu-id="9e50a-363">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="9e50a-364">MDM 的其他移动设备管理 () 基于产品的部署。</span><span class="sxs-lookup"><span data-stu-id="9e50a-364">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-365">手动部署。</span><span class="sxs-lookup"><span data-stu-id="9e50a-365">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="9e50a-366">配置以下攻击面减少功能：</span><span class="sxs-lookup"><span data-stu-id="9e50a-366">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="9e50a-367">基于硬件的隔离。</span><span class="sxs-lookup"><span data-stu-id="9e50a-367">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-368">应用控件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-368">App control.</span></span>  
  </li>
<li> <span data-ttu-id="9e50a-369">设备控件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-369">Device control.</span></span></li>
<li>  
  <span data-ttu-id="9e50a-370">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="9e50a-370">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-371">网络防火墙。</span><span class="sxs-lookup"><span data-stu-id="9e50a-371">Network firewall.</span></span>  
  </li>



</ul></li>
<li> <span data-ttu-id="9e50a-372">配置或管理帐户保护功能，例如：</span><span class="sxs-lookup"><span data-stu-id="9e50a-372">Configuration or management of account protection features like:</span></span> </li>
<ul>

<li> <span data-ttu-id="9e50a-373">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="9e50a-373">Windows Hello</span></span></li>
<li> <span data-ttu-id="9e50a-374">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="9e50a-374">Credential Guard</span></span></li>
</ul>
<li> <span data-ttu-id="9e50a-375">BitLocker 的配置或管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-375">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="9e50a-376">注册或配置 Microsoft 威胁专家。</span><span class="sxs-lookup"><span data-stu-id="9e50a-376">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-377">在 SIEM 连接中查看 API 或安全信息 (或) 培训。</span><span class="sxs-lookup"><span data-stu-id="9e50a-377">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-378">注册或配置 Microsoft 威胁防护 (MTP)。</span><span class="sxs-lookup"><span data-stu-id="9e50a-378">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-379">有关高级搜寻的培训或指导。</span><span class="sxs-lookup"><span data-stu-id="9e50a-379">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-380">有关使用或创建 Kusto 查询的培训或指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-380">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="9e50a-381">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-381">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

<tr class="odd">
<td><span data-ttu-id="9e50a-382"><strong>Microsoft Defender for Identity </strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-382"><strong>Microsoft Defender for Identity </strong></span></span></td>
<td>  <span data-ttu-id="9e50a-383">Microsoft Defender for Identity 是一种基于云的安全解决方案，可利用本地 Active Directory 信号来识别、检测和调查针对组织的高级威胁、已遭入侵标识和恶意内部行为。</span><span class="sxs-lookup"><span data-stu-id="9e50a-383">Microsoft Defender for Identity is a cloud-based security solution that leverages your on-premises Active Directory signals to identify, detect, and investigate advanced threats, compromised identities, and malicious insider actions directed at your organization.</span></span> <span data-ttu-id="9e50a-384">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-384">We provide remote guidance for:</span></span>
<ul>
<li>   <span data-ttu-id="9e50a-385">创建 Defender for Identity 的实例。</span><span class="sxs-lookup"><span data-stu-id="9e50a-385">Creating your instance of Defender for Identity.</span></span> </li>
<li>   <span data-ttu-id="9e50a-386">将 Defender for Identity 连接到 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="9e50a-386">Connecting Defender for Identity to Active Directory.</span></span> </li>
<li>   <span data-ttu-id="9e50a-387">评估环境在域控制器上部署 Defender for Identity 传感器的准备情况，包括：</span><span class="sxs-lookup"><span data-stu-id="9e50a-387">Assessing the readiness of your environment to deploy the Defender for Identity sensor on your domain controllers, including:</span></span></li>   
<ul> 
<li>  <span data-ttu-id="9e50a-388">运行资源容量规划大小工具。</span><span class="sxs-lookup"><span data-stu-id="9e50a-388">Running the sizing tool for resource capacity planning.</span></span> </li>
<li>  <span data-ttu-id="9e50a-389">运行审核工具来评估域控制器与传感器的兼容性。</span><span class="sxs-lookup"><span data-stu-id="9e50a-389">Running the auditing tool to assess the compatibility of your domain controllers with the sensor.</span></span> </li>
</ul>
<li>  <span data-ttu-id="9e50a-390">部署传感器以直接从域控制器捕获和分析网络流量和 Windows 事件，包括：</span><span class="sxs-lookup"><span data-stu-id="9e50a-390">Deploying the sensor to capture and parse network traffic and Windows events directly from your domain controllers, including:</span></span> </li>
<ul> 
<li>  <span data-ttu-id="9e50a-391">下载传感器包。</span><span class="sxs-lookup"><span data-stu-id="9e50a-391">Downloading the sensor package.</span></span> </li>
<li>  <span data-ttu-id="9e50a-392">配置传感器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-392">Configuring the sensor.</span></span> </li>
<li>  <span data-ttu-id="9e50a-393">以静默方式在域控制器上安装传感器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-393">Installing the sensor on your domain controller silently.</span></span> </li>
<li>  <span data-ttu-id="9e50a-394">将传感器部署到多林环境。</span><span class="sxs-lookup"><span data-stu-id="9e50a-394">Deploying the sensor to your multi-forest environment.</span></span> </li>
</ul>
<li>  <span data-ttu-id="9e50a-395">不需要将 Defender for Identity 与 Microsoft Cloud App Security (云应用安全许可集成) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-395">Integrating  Defender for Identity with Microsoft Cloud App Security (Cloud App Security licensing isn't required).</span></span> </li>
<li>  <span data-ttu-id="9e50a-396">提供有关：</span><span class="sxs-lookup"><span data-stu-id="9e50a-396">Providing deployment guidance, configuration assistance, and education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="9e50a-397">调整环境以减少"噪音"。</span><span class="sxs-lookup"><span data-stu-id="9e50a-397">Tuning the environment to reduce  “noise.”</span></span>  </li>
<li>  <span data-ttu-id="9e50a-398">了解标识安全状态评估报告。</span><span class="sxs-lookup"><span data-stu-id="9e50a-398">Understanding the identity security posture assessment report.</span></span> </li>
<li>  <span data-ttu-id="9e50a-399">了解用户调查优先级分数和用户调查排名报告。</span><span class="sxs-lookup"><span data-stu-id="9e50a-399">Understanding the user Investigation priority score and user Investigation ranking report.</span></span> </li>
<li> <span data-ttu-id="9e50a-400">了解非活动用户报告。</span><span class="sxs-lookup"><span data-stu-id="9e50a-400">Understanding the inactive user report.</span></span>  </li>
<li> <span data-ttu-id="9e50a-401">在遭到入侵的帐户上提供修正选项。</span><span class="sxs-lookup"><span data-stu-id="9e50a-401">Providing remediation options on a compromised account.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="9e50a-402">促进从高级威胁分析 (ATA) Defender for Identity。</span><span class="sxs-lookup"><span data-stu-id="9e50a-402">Facilitating the migration from Advanced Threat Analytics (ATA) to Defender for Identity.</span></span> </li>
</ul>
<p><span data-ttu-id="9e50a-403"><strong>以下内容超出范围</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-403"><strong>The following is out of scope</strong></span></span></p>
<ul>

<li> <span data-ttu-id="9e50a-404">客户补救活动的项目管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-404">Project management of the customer's remediation activities.</span></span> </li>
<li> <span data-ttu-id="9e50a-405">持续管理、威胁响应和修正。</span><span class="sxs-lookup"><span data-stu-id="9e50a-405">Ongoing management, threat response, and remediation.</span></span>  </li>
<li> <span data-ttu-id="9e50a-406">部署 Defender for Identity 传感器，包括：</span><span class="sxs-lookup"><span data-stu-id="9e50a-406">Deploying the Defender for Identity sensor, including:</span></span> </li>
<ul>
<li> <span data-ttu-id="9e50a-407">手动容量规划。</span><span class="sxs-lookup"><span data-stu-id="9e50a-407">Manual capacity planning.</span></span> </li>
<li> <span data-ttu-id="9e50a-408">以独立容量部署传感器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-408">Deploying the sensor in a standalone capacity.</span></span> </li>
<li> <span data-ttu-id="9e50a-409">使用网络接口卡 (NIC) 适配器部署传感器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-409">Deploying the sensor using a Network Interface Card (NIC) Teaming adaptor.</span></span> </li>
<li> <span data-ttu-id="9e50a-410">通过第三方工具部署传感器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-410">Deploying the sensor through a third-party tool.</span></span> </li>
<li> <span data-ttu-id="9e50a-411">通过 Web 代理连接连接到 Defender for Identity 云服务。</span><span class="sxs-lookup"><span data-stu-id="9e50a-411">Connecting to the Defender for Identity cloud service through a web proxy connection.</span></span> </li>
</ul>
<li> <span data-ttu-id="9e50a-412">创建和管理 honeytokens。</span><span class="sxs-lookup"><span data-stu-id="9e50a-412">Creation and management of honeytokens.</span></span> </li>
<li> <span data-ttu-id="9e50a-413">部署指南或教育：：</span><span class="sxs-lookup"><span data-stu-id="9e50a-413">Deployment guidance or education on:</span></span> </li>
<ul>
<li> <span data-ttu-id="9e50a-414">修正或解释各种警报类型和受监视的活动。</span><span class="sxs-lookup"><span data-stu-id="9e50a-414">Remediating or interpreting various alert types and monitored activities.</span></span>  </li>
<li> <span data-ttu-id="9e50a-415">调查用户、计算机、横向移动路径或实体。</span><span class="sxs-lookup"><span data-stu-id="9e50a-415">Investigating a user, computer, lateral movement path, or entity.</span></span> </li>
<li> <span data-ttu-id="9e50a-416">威胁或高级搜寻。</span><span class="sxs-lookup"><span data-stu-id="9e50a-416">Threat or advanced hunting.</span></span> </li>
<li> <span data-ttu-id="9e50a-417">事件响应。</span><span class="sxs-lookup"><span data-stu-id="9e50a-417">Incident response.</span></span> </li>
</ul>
<li> <span data-ttu-id="9e50a-418">为 Defender for Identity 提供安全警报实验室教程。</span><span class="sxs-lookup"><span data-stu-id="9e50a-418">Providing a security alert lab tutorial for Defender for Identity.</span></span> </li>
<li> <span data-ttu-id="9e50a-419">当 Defender for Identity 检测到可疑活动时，通过指定的传感器向 syslog 服务器发送安全警报，从而提供通知。</span><span class="sxs-lookup"><span data-stu-id="9e50a-419">Providing notification when Defender for Identity detects suspicious activities by sending security alerts to your syslog server through a nominated sensor.</span></span>  </li>
<li> <span data-ttu-id="9e50a-420">配置 Defender for Identity 以使用安全帐户管理器远程 (SAMR) 协议执行查询，以标识特定计算机上的本地管理员。</span><span class="sxs-lookup"><span data-stu-id="9e50a-420">Configuring Defender for Identity to perform queries using security account manager remote (SAMR) protocol to identify local admins on specific machines.</span></span> </li>
<li> <span data-ttu-id="9e50a-421">配置 VPN 解决方案以将信息从 VPN 连接添加到用户配置文件页。</span><span class="sxs-lookup"><span data-stu-id="9e50a-421">Configuring VPN solutions to add information from the VPN connection to a user’s profile page.</span></span>  </li>
<li> <span data-ttu-id="9e50a-422">SIEM 安全信息和事件 (SIEM) API 集成 (包括 Azure Sentinel) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-422">Security information and event management (SIEM) or API integration (including Azure Sentinel).</span></span> </li>
<li> <span data-ttu-id="9e50a-423">部署 Defender for Identity 传感器作为概念证明。</span><span class="sxs-lookup"><span data-stu-id="9e50a-423">Deploying Defender for Identity sensors as a proof of concept.</span></span></li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="9e50a-424">已部署 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="9e50a-424">Active Directory deployed.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-425">打算安装 Defender for Identity 传感器的域控制器具有与 Defender for Identity 云服务的 Internet 连接。</span><span class="sxs-lookup"><span data-stu-id="9e50a-425">The domain controllers you intend to install Defender for Identity sensors on have internet connectivity to the Defender for Identity cloud service.</span></span>  </li>
<ul>
<li> <span data-ttu-id="9e50a-426">防火墙和代理必须处于打开状态，以与 Defender for Identity 云服务进行通信 (\*.atp.azure.com 端口 443 必须) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-426">Your firewall and proxy must be open to communicate with the Defender for Identity cloud service (\*.atp.azure.com port 443 must be open).</span></span></li>
</ul>
<li> <span data-ttu-id="9e50a-427">在下列其中一个上运行的域控制器：</span><span class="sxs-lookup"><span data-stu-id="9e50a-427">Domain controllers running on one of the following:</span></span></li>
<ul>
<li> <span data-ttu-id="9e50a-428">Windows Server 2008 R2 SP1。</span><span class="sxs-lookup"><span data-stu-id="9e50a-428">Windows Server 2008 R2 SP1.</span></span></li>
<li> <span data-ttu-id="9e50a-429">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="9e50a-429">Windows Server 2012.</span></span></li>
<li> <span data-ttu-id="9e50a-430">Windows Server 2012 R2。</span><span class="sxs-lookup"><span data-stu-id="9e50a-430">Windows Server 2012 R2.</span></span></li>
<li> <span data-ttu-id="9e50a-431">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="9e50a-431">Windows Server 2016.</span></span></li>
<li> <span data-ttu-id="9e50a-432">Windows Server 2019 KB4487044 (操作系统版本 17763.316) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-432">Windows Server 2019 with KB4487044 (OS Build 17763.316).</span></span></li>
</ul>
</ul></td>
</tr>

<tr class="even">
<td><span data-ttu-id="9e50a-433"><strong>Microsoft 信息管控</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-433"><strong>Microsoft Information Governance</strong></span></span></td>

<td>  <span data-ttu-id="9e50a-434">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-434">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-435">创建和发布保留标签和策略 (仅在 E5) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-435">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="9e50a-436">记录管理 (仅在 E5) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-436">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="9e50a-437">查看文件计划创建。</span><span class="sxs-lookup"><span data-stu-id="9e50a-437">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="9e50a-438">创建和管理记录 (包括基于事件的记录) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-438">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-439">正在审阅处置。</span><span class="sxs-lookup"><span data-stu-id="9e50a-439">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="9e50a-440">

<strong> 合规性管理器</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-440">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="9e50a-441">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-441">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="9e50a-442">查看角色类型。</span><span class="sxs-lookup"><span data-stu-id="9e50a-442">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="9e50a-443">添加和配置评估。</span><span class="sxs-lookup"><span data-stu-id="9e50a-443">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="9e50a-444">通过实施改进操作和确定这如何影响合规性分数来评估合规性。</span><span class="sxs-lookup"><span data-stu-id="9e50a-444">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="9e50a-445">查看内置控件映射和评估控件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-445">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="9e50a-446">在评估内生成报告。</span><span class="sxs-lookup"><span data-stu-id="9e50a-446">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="9e50a-447">

  <strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-447">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="9e50a-448">开发记录管理文件计划。</span><span class="sxs-lookup"><span data-stu-id="9e50a-448">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="9e50a-449">数据连接器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-449">Data connectors.</span></span></li>
<li> <span data-ttu-id="9e50a-450">在 SharePoint 中开发信息体系结构。</span><span class="sxs-lookup"><span data-stu-id="9e50a-450">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="9e50a-451">自定义脚本和编码。</span><span class="sxs-lookup"><span data-stu-id="9e50a-451">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="9e50a-452">设计、架构师和第三方文档审阅。</span><span class="sxs-lookup"><span data-stu-id="9e50a-452">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="9e50a-453">支持 E3。</span><span class="sxs-lookup"><span data-stu-id="9e50a-453">Support for E3.</span></span></li>
<li> <span data-ttu-id="9e50a-454">遵守行业和区域法规和要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-454">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="9e50a-455">合规性管理器中评估的建议改进措施的动手实施。</span><span class="sxs-lookup"><span data-stu-id="9e50a-455">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="9e50a-456">除了"<strong>常规"中的核心</strong>载入部分<a href="#general"></a>外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-456">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9e50a-457"><strong>Microsoft 信息保护</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-457"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-458">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-458">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-459">E3 和 E5 (支持的数据) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-459">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-460">E3 和 E5 (支持敏感信息) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-460">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-461">创建敏感度标签 (E3 和 E5 支持) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-461">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-462">在 E3 和 E5 (中支持应用敏感度) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-462">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-463">E5 (支持可训练分类器) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-463">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-464">使用内容资源管理器和活动资源管理器了解数据 (E5) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-464">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-465">使用策略发布标签 (E5)  (支持手动和自动) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-465">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-466">为 Windows 10 (DLP) 策略创建终结点数据丢失防护 (E5) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-466">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-467">为 Microsoft Teams 聊天和频道创建 DLP 策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-467">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="9e50a-468">

<strong> 合规性管理器</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-468">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="9e50a-469">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-469">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="9e50a-470">查看角色类型。</span><span class="sxs-lookup"><span data-stu-id="9e50a-470">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="9e50a-471">添加和配置评估。</span><span class="sxs-lookup"><span data-stu-id="9e50a-471">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="9e50a-472">通过实施改进操作和确定这如何影响合规性分数来评估合规性。</span><span class="sxs-lookup"><span data-stu-id="9e50a-472">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="9e50a-473">查看内置控件映射和评估控件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-473">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="9e50a-474">在评估内生成报告。</span><span class="sxs-lookup"><span data-stu-id="9e50a-474">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="9e50a-475">

<strong> Azure 信息保护</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-475">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="9e50a-476">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-476">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="9e50a-477">激活和配置租户。</span><span class="sxs-lookup"><span data-stu-id="9e50a-477">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-478">创建和设置 P1 和 P2 (支持的标签和) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-478">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-479">对 P1 和 P2 (支持的文档应用信息保护) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-479">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-480">自动对 Office 应用中的信息进行分类和标记 (如在 Windows 上运行的 Word、PowerPoint、Excel 和 Outlook) 以及使用 P2 (支持的 Azure 信息保护客户端) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-480">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-481">使用 Azure 信息保护扫描程序发现和标记 (P1 和 P2) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-481">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-482">使用 Exchange Online 邮件流规则监视传输中的电子邮件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-482">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>

  <span data-ttu-id="9e50a-483">如果你希望使用 Microsoft Azure Rights Management Services (Azure RMS) 、Office 365 邮件加密 (OME) 和数据丢失防护 (DLP) ，我们还会提供指导。</span><span class="sxs-lookup"><span data-stu-id="9e50a-483">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="9e50a-484"><strong>以下内容超出范围 </strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-484"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="9e50a-485">客户密钥。</span><span class="sxs-lookup"><span data-stu-id="9e50a-485">Customer key.</span></span></li>
<li><span data-ttu-id="9e50a-486">RegEx (正则表达式) 敏感信息类型的开发。</span><span class="sxs-lookup"><span data-stu-id="9e50a-486">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="9e50a-487">创建或修改关键字词典。</span><span class="sxs-lookup"><span data-stu-id="9e50a-487">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="9e50a-488">自定义脚本和编码。</span><span class="sxs-lookup"><span data-stu-id="9e50a-488">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="9e50a-489">Azure Azure。</span><span class="sxs-lookup"><span data-stu-id="9e50a-489">Azure Purview.</span></span></li>
<li> <span data-ttu-id="9e50a-490">设计、架构师和第三方文档审阅。</span><span class="sxs-lookup"><span data-stu-id="9e50a-490">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="9e50a-491">遵守行业和区域法规和要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-491">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="9e50a-492">合规性管理器中评估的建议改进措施的动手实施。</span><span class="sxs-lookup"><span data-stu-id="9e50a-492">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

<ul>

</td>
<td><span data-ttu-id="9e50a-493">除了常规<strong>的核心</strong>载入部分外，除<a href="#general"></a>Azure 信息保护外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-493">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="9e50a-494"><strong>Azure 信息保护</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-494"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="9e50a-495">客户先决条件职责包括：</span><span class="sxs-lookup"><span data-stu-id="9e50a-495">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="9e50a-496">要扫描的文件共享位置的列表。</span><span class="sxs-lookup"><span data-stu-id="9e50a-496">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-497">批准的分类分类。</span><span class="sxs-lookup"><span data-stu-id="9e50a-497">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="9e50a-498">了解有关密钥管理的任何法规限制或要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-498">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-499">为本地 Active Directory 创建的已与 Azure AD 同步的服务帐户。</span><span class="sxs-lookup"><span data-stu-id="9e50a-499">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="9e50a-500">为分类和保护配置的标签。</span><span class="sxs-lookup"><span data-stu-id="9e50a-500">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="9e50a-501">Azure 信息保护扫描程序的所有先决条件已就位。</span><span class="sxs-lookup"><span data-stu-id="9e50a-501">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="9e50a-502">有关详细信息，请参阅安装和部署 Azure 信息保护统一标签扫描程序 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">的先决条件</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-502">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="9e50a-503">确保用户设备正在运行受支持的操作系统，并且已安装必要的必备组件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-503">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="9e50a-504">有关详细信息，请参阅以下内容。</span><span class="sxs-lookup"><span data-stu-id="9e50a-504">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="9e50a-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理指南：为用户安装 Azure 信息保护统一标签客户端</a>   </span><span class="sxs-lookup"><span data-stu-id="9e50a-505"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="9e50a-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">什么是适用于 iOS 或 Android 的 Azure 信息保护应用？</a>  </span><span class="sxs-lookup"><span data-stu-id="9e50a-506"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="9e50a-507">安装和配置 Azure RMS 连接器和服务器，包括 Active Directory RMS (AD RMS) 连接器，实现混合支持。</span><span class="sxs-lookup"><span data-stu-id="9e50a-507">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="9e50a-508">设置和配置自带密钥 (BYOK) 、双密钥加密 (DKE)  (统一标记客户端仅) 或仅保留您自己的密钥 (HYOK)  (经典客户端) （如果部署需要这些选项之一）。</span><span class="sxs-lookup"><span data-stu-id="9e50a-508">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="9e50a-509"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-509"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-510">我们提供有关准备好使用 Intune 作为应用和设备的基于云的移动设备管理 (MDM) 和移动应用管理 (MAM) 提供程序的远程指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-510">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="9e50a-511">具体步骤取决于你的源环境，并且基于你的移动设备和移动应用管理需求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-511">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="9e50a-512">所包含的具体步骤如下：</span><span class="sxs-lookup"><span data-stu-id="9e50a-512">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-513">许可最终用户。</span><span class="sxs-lookup"><span data-stu-id="9e50a-513">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-514">通过利用本地 Active Directory 或 Azure AD (云标识配置由 Intune 使用的) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-514">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-515">将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-515">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-516">根据管理需求配置 MDM 颁发机构，包括：</span><span class="sxs-lookup"><span data-stu-id="9e50a-516">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-517">如果 Intune 是唯一的 MDM 解决方案，将 Intune 设置为 MDM 颁发机构。</span><span class="sxs-lookup"><span data-stu-id="9e50a-517">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9e50a-518">为以下操作提供 MDM 指南:</span><span class="sxs-lookup"><span data-stu-id="9e50a-518">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-519">配置用于验证 MDM 管理策略的测试组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-519">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-520">配置 MDM 管理策略和服务，如：</span><span class="sxs-lookup"><span data-stu-id="9e50a-520">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-521">通过 Web 链接或深层链接针对每个受支持的平台的应用部署。</span><span class="sxs-lookup"><span data-stu-id="9e50a-521">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-522">条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-522">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-523">如果组织中已有证书颁发机构、无线网络或 VPN 基础结构，则部署电子邮件、无线网络和 VPN 配置文件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-523">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-524">连接到 Intune 数据仓库。</span><span class="sxs-lookup"><span data-stu-id="9e50a-524">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-525">将 Intune 与以下内容进行集成：</span><span class="sxs-lookup"><span data-stu-id="9e50a-525">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-526">需要团队查看器 (团队查看器订阅的远程) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-526">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-527">移动威胁防护 (MTD) MTD (需要 MTD 订阅) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-527">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-528">需要电信费用管理解决方案 (需要电信费用管理解决方案订阅) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-528">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>

</ul></li>
<li>  <span data-ttu-id="9e50a-529">将每个受支持平台的设备注册到 Intune。</span><span class="sxs-lookup"><span data-stu-id="9e50a-529">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="9e50a-530">提供应用保护指南，</span><span class="sxs-lookup"><span data-stu-id="9e50a-530">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-531">为每个受支持的平台配置应用保护策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-531">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-532">为托管应用配置条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-532">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-533">使用前面提到的 MAM 策略面向相应的用户组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-533">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-534">使用托管应用使用情况报告。</span><span class="sxs-lookup"><span data-stu-id="9e50a-534">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9e50a-535">提供从旧版电脑管理到 Intune MDM 的迁移指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-535">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="9e50a-536">
 
</li>
</ul>
  
<strong>云附加</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-536">
 
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="9e50a-537">我们将指导你准备好使用 Intune 云附加现有 Configuration Manager 环境。</span><span class="sxs-lookup"><span data-stu-id="9e50a-537">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="9e50a-538">具体步骤取决于源环境。</span><span class="sxs-lookup"><span data-stu-id="9e50a-538">The exact steps depend on your source environment.</span></span> <span data-ttu-id="9e50a-539">这些步骤包括：</span><span class="sxs-lookup"><span data-stu-id="9e50a-539">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="9e50a-540">许可最终用户。</span><span class="sxs-lookup"><span data-stu-id="9e50a-540">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-541">通过利用本地 Active Directory 和云标识，配置供 Intune 使用的标识。</span><span class="sxs-lookup"><span data-stu-id="9e50a-541">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-542">将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-542">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-543">提供设置混合 Azure AD 加入的指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-543">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-544">提供有关为 MDM 自动注册设置 Azure AD 的指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-544">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-545">提供有关在将云管理网关用作远程基于 Internet 的设备管理共同管理的解决方案时如何设置云管理网关的指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-545">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-546">配置要切换到 Intune 的受支持工作负载。</span><span class="sxs-lookup"><span data-stu-id="9e50a-546">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-547">在 Intune 注册的设备中安装 Configuration Manager 客户端。</span><span class="sxs-lookup"><span data-stu-id="9e50a-547">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="9e50a-548"><strong>安全地部署适用于 iOS 和 Android 的 Outlook 移动版</strong> 我们可以提供指导，帮助你在组织中安全地部署适用于 iOS 和 Android 的 Outlook 移动版，以确保用户已安装所有必需的应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-548"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="9e50a-549">使用 Intune 安全地部署适用于 iOS 和 Android 的 Outlook 移动版的步骤取决于您的源环境。</span><span class="sxs-lookup"><span data-stu-id="9e50a-549">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="9e50a-550">它可以包括：</span><span class="sxs-lookup"><span data-stu-id="9e50a-550">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-551">通过 Apple App Store 或 Google Play 商店下载 Outlook for iOS 和 Android、Microsoft Authenticator 和 Intune 公司门户应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-551">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-552">提供有关设置的指导：</span><span class="sxs-lookup"><span data-stu-id="9e50a-552">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-553">使用 Intune 部署 Outlook for iOS 和 Android、Microsoft Authenticator 和 Intune 公司门户应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-553">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-554">应用保护策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-554">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-555">条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-555">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-556">应用配置策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-556">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="9e50a-557">当规划使用 Intune 部署无线网络和 VPN 配置文件时，IT 管理员需要具有已在其生产环境中工作的现有证书颁发机构、无线网络和 VPN 基础结构。</span><span class="sxs-lookup"><span data-stu-id="9e50a-557">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="9e50a-558"><strong>注意</strong>：FastTrack 服务权益不包括帮助为 Intune 设置或配置证书颁发机构、无线网络、VPN 基础结构或 Apple MDM 推送证书。</span><span class="sxs-lookup"><span data-stu-id="9e50a-558"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="9e50a-559"><strong>注意</strong>：FastTrack 服务权益不包括有关将配置管理器站点服务器或配置管理器客户端设置或升级到支持云附加所需的最低要求的帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-559"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="9e50a-560">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-560">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="9e50a-561"><strong>Intune 与 Microsoft Defender 高级威胁防护 (ATP) 集成</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-561"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="9e50a-562"><strong>注意</strong>：我们协助将 Intune 与 Microsoft Defender ATP 集成，并基于 Windows 10 风险级别评估创建设备合规性策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-562"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="9e50a-563">我们不提供有关购买、许可或激活的帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-563">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="9e50a-564">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-564">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="9e50a-565"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-565"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="9e50a-566">IT 管理员负责通过让硬件供应商代表他们上载其硬件 ID 或自己将其上载到 Windows Autopilot 服务中来向其组织注册设备。</span><span class="sxs-lookup"><span data-stu-id="9e50a-566">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>

<tr class="odd">
<td><span data-ttu-id="9e50a-567"><strong>Office 365 高级威胁防护 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-567"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-568">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-568">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-569">启用安全链接、安全附件和防钓鱼。</span><span class="sxs-lookup"><span data-stu-id="9e50a-569">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-570">配置自动化、调查和响应。</span><span class="sxs-lookup"><span data-stu-id="9e50a-570">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-571">使用攻击模拟器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-571">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-572">报告和威胁分析。</span><span class="sxs-lookup"><span data-stu-id="9e50a-572">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="9e50a-573">除了"<strong>常规"中的核心</strong>载入部分<a href="#general"></a>外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-573">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a><span data-ttu-id="9e50a-574">Office 365</span><span class="sxs-lookup"><span data-stu-id="9e50a-574">Office 365</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9e50a-575"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-575"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="9e50a-576"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-576"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="9e50a-577"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-577"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9e50a-578"><strong>Exchange Online</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-578"><strong>Exchange Online</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-579">对于 Exchange Online，我们会全程指导你，直到你的组织可以使用电子邮件为止。</span><span class="sxs-lookup"><span data-stu-id="9e50a-579">For Exchange Online, we guide you through the process to get your organization ready to use email.</span></span> <span data-ttu-id="9e50a-580">具体步骤取决于您的源环境和电子邮件迁移计划。</span><span class="sxs-lookup"><span data-stu-id="9e50a-580">The exact steps depend on your source environment and your email migration plans.</span></span>  
  <span data-ttu-id="9e50a-581">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-581">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-582">为 Office 365 中验证的所有启用邮件的域设置 Exchange Online Protection (EOP) 功能。</span><span class="sxs-lookup"><span data-stu-id="9e50a-582">Setting up Exchange Online Protection (EOP) features for all mail-enabled domains validated in Office 365.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-583">将邮件交换 (MX) 指向 Office 365。</span><span class="sxs-lookup"><span data-stu-id="9e50a-583">Pointing your mail exchange (MX) records to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-584">如果 Office 365 ATP 功能是订阅服务的一部分，则设置该功能。</span><span class="sxs-lookup"><span data-stu-id="9e50a-584">Setting up the Office 365 ATP feature if it’s a part of your subscription service.</span></span> <span data-ttu-id="9e50a-585">有关详细信息，请参阅此表的 <strong>Office 365 高级威胁</strong> 防护部分。</span><span class="sxs-lookup"><span data-stu-id="9e50a-585">For more information, see the <strong>Office 365 Advanced Threat Protection</strong> portion of this table.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-p127">为在 Office 365 中验证的所有已启用邮件的域设置数据丢失防护 (DLP) 功能，将其作为订阅服务的一部分。这可在 MX 记录指向 Office 365 后完成。</span><span class="sxs-lookup"><span data-stu-id="9e50a-p127">Setting up the data loss prevention (DLP) feature for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
<li>  <span data-ttu-id="9e50a-p128">为在 Office 365 中验证的所有已启用邮件的域设置 Office 365 邮件加密 (OME) ，将其作为订阅服务的一部分。这可在 MX 记录指向 Office 365 后完成。</span><span class="sxs-lookup"><span data-stu-id="9e50a-p128">Setting up Office 365 Message Encryption (OME) for all mail-enabled domains validated in Office 365 as part of your subscription service. This is done once your MX records point to Office 365.  </span></span></li>
</ul><span data-ttu-id="9e50a-590">
  <strong>注意：</strong> 邮箱复制服务 (MRS) 尝试将信息权限托管 (IRM) 电子邮件从本地邮箱迁移到相应的 Exchange Online 邮箱。</span><span class="sxs-lookup"><span data-stu-id="9e50a-590">
  <strong>Note:</strong> The Mailbox Replication service (MRS) attempts to migrate Information Rights Managed (IRM) emails from your on-premises mailbox to the corresponding Exchange Online mailbox.</span></span> <span data-ttu-id="9e50a-591">可读取受保护内容迁移后的能力取决于客户映射和将 Active Directory Rights Managed Services (AD RMS) 模板复制到 Azure Rights Management Service (Azure RMS)。</span><span class="sxs-lookup"><span data-stu-id="9e50a-591">Ability to read the protected content post-migration depends on the customer mapping and copying Active Directory Rights Managed Services (AD RMS) templates to the Azure Rights Management Service (Azure RMS).</span></span>  
<ul>
<li>  <span data-ttu-id="9e50a-592">配置防火墙端口。</span><span class="sxs-lookup"><span data-stu-id="9e50a-592">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-593">根据需要设置 DNS，包括所需的自动发现、发件人策略框架 (SPF) 、DomainKeys 标识的邮件 (DKIM) 、基于域的邮件身份验证、报告和一致性 (DMARC) 和 MX 记录 () 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-593">Setting up DNS, including the required Autodiscover, sender policy framework (SPF), DomainKeys Identified Mail (DKIM), Domain-based Message Authentication, Reporting and Conformance (DMARC) and MX records (as needed).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-594">设置源邮件环境和 Exchange Online 之间的电子邮件流（根据需要）。</span><span class="sxs-lookup"><span data-stu-id="9e50a-594">Setting up email flow between your source messaging environment and Exchange Online (as needed).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-595">执行从源邮件环境到 Office 365 的邮件迁移。</span><span class="sxs-lookup"><span data-stu-id="9e50a-595">Undertaking mail migration from your source messaging environment to Office 365.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-596">配置邮箱客户端（Outlook for Windows、Outlook 网页版以及 Outlook for iOS 和 Outlook for Android）。</span><span class="sxs-lookup"><span data-stu-id="9e50a-596">Configuring mailbox clients (Outlook for Windows, Outlook on the web, and Outlook for iOS and Android).</span></span>  </li>
</ul><span data-ttu-id="9e50a-597">
  <strong>数据迁移</strong>  </span><span class="sxs-lookup"><span data-stu-id="9e50a-597">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="9e50a-598">有关将数据迁移到 Office 365 的 FastTrack 权益的信息，请参阅<a href="https://docs.microsoft.com/fasttrack/data-migration">"数据迁移"。</a></span><span class="sxs-lookup"><span data-stu-id="9e50a-598">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>   
<td>  <span data-ttu-id="9e50a-599">源环境必须具有以下最低级别之一：</span><span class="sxs-lookup"><span data-stu-id="9e50a-599">Your source environment must have one of the following minimum levels:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-600">具有 Exchange Server 2003 前向的单个或多个 Exchange 组织。</span><span class="sxs-lookup"><span data-stu-id="9e50a-600">Single or multiple Exchange organizations with Exchange Server 2003 onward.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-601">一个支持 Internet 邮件访问协议 (IMAP) 的电子邮件环境。</span><span class="sxs-lookup"><span data-stu-id="9e50a-601">A single Internet Message Access Protocol (IMAP)-capable email environment.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-602">单个 G 套件环境（仅限 Gmail、联系人和日历）。</span><span class="sxs-lookup"><span data-stu-id="9e50a-602">A single G Suite environment (Gmail, Contacts, and Calendar only).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-603">有关多地理位置功能的信息，请参阅 Exchange Online 中的多 <a href="https://go.microsoft.com/fwlink/?linkid=872776">地理位置功能</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-603">For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=872776">Multi-Geo Capabilities in Exchange Online</a>.</span></span>  </li>
</ul>
<span data-ttu-id="9e50a-604">Project for Office 365、Outlook for Windows、Outlook for iOS 和 Outlook for Android、OneDrive for Business 同步客户端、Power BI Desktop 和 Skype for Business 等联机客户端软件必须处于最低级别，如 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 Office</a>的系统要求所定义。</span><span class="sxs-lookup"><span data-stu-id="9e50a-604">Online client software like Project for Office 365, Outlook for Windows, Outlook for iOS and Android, OneDrive for Business sync client, Power BI Desktop, and Skype for Business must be at a minimum level as defined in <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 Office</a>.</span></span>  </td>
</tr>
<tr class="even">
<td><span data-ttu-id="9e50a-605"><strong>Microsoft 信息管控</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-605"><strong>Microsoft Information Governance</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-606">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-606">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-607">创建和发布保留标签和策略 (仅在 E5) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-607">Creating and publishing retention labels and policies (only supported in E5).</span></span>  
</li>
<li>  <span data-ttu-id="9e50a-608">记录管理 (仅在 E5) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-608">Records management (only supported in E5).</span></span>  </li>
<ul><li>  <span data-ttu-id="9e50a-609">查看文件计划创建。</span><span class="sxs-lookup"><span data-stu-id="9e50a-609">Reviewing file plan creation.</span></span> </li>
<li>  <span data-ttu-id="9e50a-610">创建和管理记录 (包括基于事件的记录) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-610">Creating and managing records (including event-based records).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-611">正在审阅处置。</span><span class="sxs-lookup"><span data-stu-id="9e50a-611">Reviewing disposition.</span></span> </ul> </li>
</ul><span data-ttu-id="9e50a-612">

<strong> 合规性管理器</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-612">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="9e50a-613">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-613">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="9e50a-614">查看角色类型。</span><span class="sxs-lookup"><span data-stu-id="9e50a-614">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="9e50a-615">添加和配置评估。</span><span class="sxs-lookup"><span data-stu-id="9e50a-615">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="9e50a-616">通过实施改进操作和确定这如何影响合规性分数来评估合规性。</span><span class="sxs-lookup"><span data-stu-id="9e50a-616">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="9e50a-617">查看内置控件映射和评估控件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-617">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="9e50a-618">在评估内生成报告。</span><span class="sxs-lookup"><span data-stu-id="9e50a-618">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="9e50a-619">

  <strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-619">

  <strong>The following is out of scope </strong>  
</span></span><ul>
<li> <span data-ttu-id="9e50a-620">开发记录管理文件计划。</span><span class="sxs-lookup"><span data-stu-id="9e50a-620">Development of a records management file plan.</span></span></li>
<li> <span data-ttu-id="9e50a-621">数据连接器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-621">Data connectors.</span></span></li>
<li> <span data-ttu-id="9e50a-622">在 SharePoint 中开发信息体系结构。</span><span class="sxs-lookup"><span data-stu-id="9e50a-622">Development of information architecture in SharePoint.</span></span></li>
<li> <span data-ttu-id="9e50a-623">自定义脚本和编码。</span><span class="sxs-lookup"><span data-stu-id="9e50a-623">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="9e50a-624">设计、架构师和第三方文档审阅。</span><span class="sxs-lookup"><span data-stu-id="9e50a-624">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="9e50a-625">支持 E3。</span><span class="sxs-lookup"><span data-stu-id="9e50a-625">Support for E3.</span></span></li>
<li> <span data-ttu-id="9e50a-626">遵守行业和区域法规和要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-626">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="9e50a-627">合规性管理器中评估的建议改进措施的动手实施。</span><span class="sxs-lookup"><span data-stu-id="9e50a-627">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>


</td>
<td><span data-ttu-id="9e50a-628">除了"<strong>常规"中的核心</strong>载入部分<a href="#general"></a>外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-628">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9e50a-629"><strong>Microsoft 信息保护</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-629"><strong>Microsoft Information Protection</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-630">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-630">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-631">E3 和 E5 (支持的数据) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-631">Data classification (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-632">E3 和 E5 (支持敏感信息) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-632">Sensitive information types (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-633">创建敏感度标签 (E3 和 E5 支持) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-633">Creating sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-634">在 E3 和 E5 (中支持应用敏感度) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-634">Applying sensitivity labels (supported in E3 and E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-635">E5 (支持可训练分类器) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-635">Trainable classifiers (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-636">使用内容资源管理器和活动资源管理器了解数据 (E5) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-636">Knowing your data with content explorer and activity explorer (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-637">使用策略发布标签 (E5)  (支持手动和自动) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-637">Publishing labels using policies (manual and automatic) (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-638">为 Windows 10 (DLP) 策略创建终结点数据丢失防护 (E5) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-638">Creating Endpoint data loss prevention (DLP) policies for Windows 10 devices (supported in E5).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-639">为 Microsoft Teams 聊天和频道创建 DLP 策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-639">Creating DLP policies for Microsoft Teams chats and channels.</span></span>  </li>
</ul><span data-ttu-id="9e50a-640">

<strong> 合规性管理器</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-640">

<strong> Compliance Manager</strong></span></span>

<span data-ttu-id="9e50a-641">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-641">We provide remote guidance for:</span></span>  

<ul> <li><span data-ttu-id="9e50a-642">查看角色类型。</span><span class="sxs-lookup"><span data-stu-id="9e50a-642">Reviewing role types.</span></span>  </li>
<li> <span data-ttu-id="9e50a-643">添加和配置评估。</span><span class="sxs-lookup"><span data-stu-id="9e50a-643">Adding and configuring assessments.</span></span></li>
<li> <span data-ttu-id="9e50a-644">通过实施改进操作和确定这如何影响合规性分数来评估合规性。</span><span class="sxs-lookup"><span data-stu-id="9e50a-644">Assessing compliance by implementing improvement actions and determining how this impacts your compliance score.</span></span></li>
<li> <span data-ttu-id="9e50a-645">查看内置控件映射和评估控件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-645">Reviewing built-in control mapping and assessing controls.</span></span></li>
<li> <span data-ttu-id="9e50a-646">在评估内生成报告。</span><span class="sxs-lookup"><span data-stu-id="9e50a-646">Generating a report within an assessment.</span></span></li>
</ul><span data-ttu-id="9e50a-647">

<strong> Azure 信息保护</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-647">

<strong> Azure Information Protection</strong></span></span>

<span data-ttu-id="9e50a-648">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-648">We provide remote guidance for:</span></span>  
<ul>
<li>  <span data-ttu-id="9e50a-649">激活和配置租户。</span><span class="sxs-lookup"><span data-stu-id="9e50a-649">Activating and configuring your tenant.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-650">创建和设置 P1 和 P2 (支持的标签和) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-650">Creating and setting up labels and policies (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-651">对 P1 和 P2 (支持的文档应用信息保护) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-651">Applying information protection to documents (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-652">自动对 Office 应用中的信息进行分类和标记 (如在 Windows 上运行的 Word、PowerPoint、Excel 和 Outlook) 以及使用 P2 (支持的 Azure 信息保护客户端) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-652">Automatically classifying and labeling information in Office apps (like Word, PowerPoint, Excel, and Outlook) running on Windows and using the Azure Information Protection client (supported in P2).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-653">使用 Azure 信息保护扫描程序发现和标记 (P1 和 P2) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-653">Discovering and labeling files at rest using the Azure Information Protection scanner (supported in P1 and P2).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-654">使用 Exchange Online 邮件流规则监视传输中的电子邮件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-654">Monitoring emails in transit using Exchange Online mail flow rules.</span></span>  </li>
</ul>
  
<span data-ttu-id="9e50a-655">如果你希望使用 Microsoft Azure Rights Management Services (Azure RMS) 、Office 365 邮件加密 (OME) 和数据丢失防护 (DLP) ，我们还会提供指导。</span><span class="sxs-lookup"><span data-stu-id="9e50a-655">We also provide guidance if you want to apply protection using Microsoft Azure Rights Management Services (Azure RMS), Office 365 Message Encryption (OME), and data loss prevention (DLP).</span></span>

<span data-ttu-id="9e50a-656"><strong>以下内容超出范围 </strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-656"><strong>The following is out of scope </strong></span></span>  
<ul>
<li><span data-ttu-id="9e50a-657">客户密钥。</span><span class="sxs-lookup"><span data-stu-id="9e50a-657">Customer key.</span></span></li>
<li><span data-ttu-id="9e50a-658">RegEx (正则表达式) 敏感信息类型的开发。</span><span class="sxs-lookup"><span data-stu-id="9e50a-658">Custom regular expressions (RegEx) development for sensitive information types.</span></span></li>
<li><span data-ttu-id="9e50a-659">创建或修改关键字词典。</span><span class="sxs-lookup"><span data-stu-id="9e50a-659">Creation or modification of keyword dictionaries.</span></span></li>
<li><span data-ttu-id="9e50a-660">自定义脚本和编码。</span><span class="sxs-lookup"><span data-stu-id="9e50a-660">Custom scripting and coding.</span></span></li>
<li> <span data-ttu-id="9e50a-661">Azure Azure。</span><span class="sxs-lookup"><span data-stu-id="9e50a-661">Azure Purview.</span></span></li>
<li> <span data-ttu-id="9e50a-662">设计、架构师和第三方文档审阅。</span><span class="sxs-lookup"><span data-stu-id="9e50a-662">Design, architect, and third-party document review.</span></span></li>
<li> <span data-ttu-id="9e50a-663">遵守行业和区域法规和要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-663">Compliance with industry and regional regulations and requirements.</span></span></li>
<li> <span data-ttu-id="9e50a-664">合规性管理器中评估的建议改进措施的动手实施。</span><span class="sxs-lookup"><span data-stu-id="9e50a-664">Hands-on implementation of recommended improvement actions for assessments in Compliance Manager.</span></span></li>
</ul>

</td>
<td><span data-ttu-id="9e50a-665">除了常规<strong>的核心</strong>载入部分外，除<a href="#general"></a>Azure 信息保护外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-665">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements with the exception of Azure Information Protection.</span></span>

<span data-ttu-id="9e50a-666"><strong>Azure 信息保护</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-666"><strong>Azure Information Protection</strong></span></span>

<span data-ttu-id="9e50a-667">客户先决条件职责包括：</span><span class="sxs-lookup"><span data-stu-id="9e50a-667">Customer prerequisite responsibilities include:</span></span>  
<ul>
<li>  <span data-ttu-id="9e50a-668">要扫描的文件共享位置的列表。</span><span class="sxs-lookup"><span data-stu-id="9e50a-668">A list of file share locations to be scanned.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-669">批准的分类分类。</span><span class="sxs-lookup"><span data-stu-id="9e50a-669">An approved classification taxonomy.</span></span> </li>
<li> <span data-ttu-id="9e50a-670">了解有关密钥管理的任何法规限制或要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-670">Understanding of any regulatory restriction or requirements regarding key management.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-671">为本地 Active Directory 创建的已与 Azure AD 同步的服务帐户。</span><span class="sxs-lookup"><span data-stu-id="9e50a-671">A service account created for your on-premises Active Directory that has been synchronized with Azure AD.</span></span> </li>
<li>  <span data-ttu-id="9e50a-672">为分类和保护配置的标签。</span><span class="sxs-lookup"><span data-stu-id="9e50a-672">Labels configured for classification and protection.</span></span> </li>
<li> <span data-ttu-id="9e50a-673">Azure 信息保护扫描程序的所有先决条件已就位。</span><span class="sxs-lookup"><span data-stu-id="9e50a-673">All prerequisites for the Azure Information Protection scanner are in place.</span></span> <span data-ttu-id="9e50a-674">有关详细信息，请参阅安装和部署 Azure 信息保护统一标签扫描程序 <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">的先决条件</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-674">For more information, see <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">Prerequisites for installing and deploying the Azure Information Protection unified labeling scanner</a>.</span></span> </li>
<li>  <span data-ttu-id="9e50a-675">确保用户设备正在运行受支持的操作系统，并且已安装必要的必备组件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-675">Ensure user devices are running a supported operating system and have the necessary prerequisites installed.</span></span> <span data-ttu-id="9e50a-676">有关详细信息，请参阅以下内容。</span><span class="sxs-lookup"><span data-stu-id="9e50a-676">See the following for more details.</span></span></li>
<ul>
<li> <span data-ttu-id="9e50a-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">管理指南：为用户安装 Azure 信息保护统一标签客户端</a>   </span><span class="sxs-lookup"><span data-stu-id="9e50a-677"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Admin Guide: Install the Azure Information Protection unified labeling client for users</a>   </span></span></li>
<li>  <span data-ttu-id="9e50a-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">什么是适用于 iOS 或 Android 的 Azure 信息保护应用？</a>  </span><span class="sxs-lookup"><span data-stu-id="9e50a-678"><a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">What is the Azure Information Protection app for iOS or Android?</a>  </span></span></li>
</ul>
<li> <span data-ttu-id="9e50a-679">安装和配置 Azure RMS 连接器和服务器，包括 Active Directory RMS (AD RMS) 连接器，实现混合支持。</span><span class="sxs-lookup"><span data-stu-id="9e50a-679">Installation and configuration of the Azure RMS connector and servers including the Active Directory RMS (AD RMS) connector for hybrid support.</span></span>  </li>
<li> <span data-ttu-id="9e50a-680">设置和配置自带密钥 (BYOK) 、双密钥加密 (DKE)  (统一标记客户端仅) 或仅保留您自己的密钥 (HYOK)  (经典客户端) （如果部署需要这些选项之一）。</span><span class="sxs-lookup"><span data-stu-id="9e50a-680">Setup and configuration of Bring Your Own Key (BYOK), Double Key Encryption (DKE) (unified labeling client only), or Hold Your Own Key (HYOK) (classic client only) should you require one of these options for your deployment.</span></span>  </li>
  </ul>
</ul>.

</td>
</tr>
<tr class="even">
<td><span data-ttu-id="9e50a-681"><strong>Microsoft Teams</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-681"><strong>Microsoft Teams</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-682">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-682">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-683">确认 Exchange Online、SharePoint Online、Office 365 组和 Azure AD 中支持 Teams 的最低要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-683">Confirming minimum requirements in Exchange Online, SharePoint Online, Office 365 Groups, and Azure AD to support Teams.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-684">配置防火墙端口。</span><span class="sxs-lookup"><span data-stu-id="9e50a-684">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-685">设置 DNS。</span><span class="sxs-lookup"><span data-stu-id="9e50a-685">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-686">确认是否已在 Office 365 租户上启用 Teams。</span><span class="sxs-lookup"><span data-stu-id="9e50a-686">Confirming Teams is enabled on your Office 365 tenant.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-687">启用或禁用用户许可证。</span><span class="sxs-lookup"><span data-stu-id="9e50a-687">Enabling or disabling user licenses.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-688">Teams 的网络评估：</span><span class="sxs-lookup"><span data-stu-id="9e50a-688">Network assessment for Teams:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-689">端口和终结点检查。</span><span class="sxs-lookup"><span data-stu-id="9e50a-689">Port and endpoint checks.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-690">连接质量检查。</span><span class="sxs-lookup"><span data-stu-id="9e50a-690">Connection quality checks.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-691">带宽预估。</span><span class="sxs-lookup"><span data-stu-id="9e50a-691">Bandwidth estimates.</span></span>  </li>
</ul>
<ul>
<li>  <span data-ttu-id="9e50a-692">配置 Teams 应用策略 (Teams Web 应用、Teams 桌面应用和适用于 iOS 和 Android 应用的 Teams 应用) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-692">Configuring Teams app policy (Teams web app, Teams Desktop app, and Teams for iOS and Android app).</span></span>  </li>
</ul>
<span data-ttu-id="9e50a-693">如果适用，我们还提供有关：</span><span class="sxs-lookup"><span data-stu-id="9e50a-693">If applicable, we also provide guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-694">Microsoft Teams 会议室设备：</span><span class="sxs-lookup"><span data-stu-id="9e50a-694">Microsoft Teams Room Devices:</span></span>  </li>
<ul>
<li>  <span data-ttu-id="9e50a-695">创建 <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams 设备目录</a>中所列支持的电话和会议室设备所需的在线帐户。</span><span class="sxs-lookup"><span data-stu-id="9e50a-695">Creation of online accounts needed for supported telephony and conference room devices listed in the <a href="https://go.microsoft.com/fwlink/?linkid=2066478">Teams devices catalog</a>.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-696">远程协助认证的 Microsoft Teams 会议室设备的服务器端配置。</span><span class="sxs-lookup"><span data-stu-id="9e50a-696">Remote assistance with service-side configuration of certified Microsoft Teams Rooms devices.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-697">启用音频会议：</span><span class="sxs-lookup"><span data-stu-id="9e50a-697">Enabling Audio Conferencing:</span></span>  </li>
<li>  <span data-ttu-id="9e50a-698">会议桥默认设置的组织设置。</span><span class="sxs-lookup"><span data-stu-id="9e50a-698">Organization setup for conference bridge default settings.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-699">向许可用户分配会议桥。</span><span class="sxs-lookup"><span data-stu-id="9e50a-699">Assignment of conference bridge to licensed users.</span></span>  </li>
</ul>
<li>  <span data-ttu-id="9e50a-700">电话系统：</span><span class="sxs-lookup"><span data-stu-id="9e50a-700">Phone System:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-701">组织设置云语音默认设置。</span><span class="sxs-lookup"><span data-stu-id="9e50a-701">Organization setup for Cloud Voice default settings.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-702">通话套餐指南 (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">可用市场) ：</a></span><span class="sxs-lookup"><span data-stu-id="9e50a-702">Calling Plans guidance (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">available markets</a>):</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-703">向许可用户分配号码。</span><span class="sxs-lookup"><span data-stu-id="9e50a-703">Assignment of numbers to licensed users.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-704">通过用户界面 (UI) 进行本地号码端口定位的指南（最多到 999）。</span><span class="sxs-lookup"><span data-stu-id="9e50a-704">Local number porting guidance through user interface (UI) up to 999.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-705">超过 999 的本地号码端口定位服务请求 (SR) 支持。</span><span class="sxs-lookup"><span data-stu-id="9e50a-705">Local number porting service request (SR) support over 999.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9e50a-706">直接路由指南：</span><span class="sxs-lookup"><span data-stu-id="9e50a-706">Direct Routing guidance:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-707">针对合作伙伴托管的方案或客户部署的最多 10 个站点的直接路由设计的组织设置指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-707">Organization setup guidance for Direct Routing design of partner-hosted scenarios, or customer-deployed scenarios for up to 10 sites.</span></span>  </li>
<li> <span data-ttu-id="9e50a-708">会话边界控制器 (SBC) 配置评审。</span><span class="sxs-lookup"><span data-stu-id="9e50a-708">Session Border Controller (SBC) configuration review.</span></span> </li>

<li> <span data-ttu-id="9e50a-709">拨号计划配置的远程协助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-709">Remote assistance with dial plan configuration.</span></span> </li>

<li> <span data-ttu-id="9e50a-710">语音路由配置。</span><span class="sxs-lookup"><span data-stu-id="9e50a-710">Voice route configuration.</span></span></li>

<li> <span data-ttu-id="9e50a-711">媒体旁路和本地媒体优化。</span><span class="sxs-lookup"><span data-stu-id="9e50a-711">Media bypass and local media optimization.</span></span> </li>

</ul></li>
</ul></li>
<li>  <span data-ttu-id="9e50a-712">启用 Teams 实时事件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-712">Enabling Teams live events.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-713">组织设置和集成到 Microsoft Stream。</span><span class="sxs-lookup"><span data-stu-id="9e50a-713">Organization setup and integration into Microsoft Stream.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-714">Skype for Business 到 Teams 转换的指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-714">Guidance for Skype for Business to Teams transition.</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="9e50a-715">在适用于 Office 365 的 Azure AD 中启用的标识。</span><span class="sxs-lookup"><span data-stu-id="9e50a-715">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-716">对 SharePoint Online 启用的用户。</span><span class="sxs-lookup"><span data-stu-id="9e50a-716">Users enabled for SharePoint Online.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-717">Exchange 邮箱 (Exchange 混合配置中的联机和本地) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-717">Exchange mailboxes are present (online and on-premises in an Exchange hybrid configuration).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-718">针对 Office 365 组启用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-718">Enabled for Office 365 Groups.</span></span>  </li>
</ul><span data-ttu-id="9e50a-719">
  <strong>注意：</strong> 如果未为用户分配和启用 SharePoint Online 许可证，则他们在 Office 365 中将没有 OneDrive for Business 存储。</span><span class="sxs-lookup"><span data-stu-id="9e50a-719">
  <strong>Note:</strong> If users aren't assigned and enabled with SharePoint Online licenses, they won't have OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="9e50a-720">文件共享继续在频道中工作，但用户在没有 Office 365 中的 OneDrive for Business 存储的情况下无法共享聊天中的文件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-720">File sharing continues to work in Channels, but users can't share files in Chats without OneDrive for Business storage in Office 365.</span></span> <span data-ttu-id="9e50a-721">Teams 不支持本地 SharePoint。</span><span class="sxs-lookup"><span data-stu-id="9e50a-721">Teams doesn't support SharePoint on-premises.</span></span>  <br><span data-ttu-id="9e50a-722">
  <strong>注意：</strong> 理想的状态是所有用户的邮箱都位于 Exchange Online 上。</span><span class="sxs-lookup"><span data-stu-id="9e50a-722">
  <strong>Note:</strong> The ideal state is for all users to have their mailboxes homed on Exchange Online.</span></span> <span data-ttu-id="9e50a-723">拥有本地托管邮箱的用户必须通过 Azure AD Connect 将其标识同步到 Office 365 目录。</span><span class="sxs-lookup"><span data-stu-id="9e50a-723">Users with mailboxes homed on-premises must have their identities synchronized to the Office 365 directory through Azure AD Connect.</span></span> <span data-ttu-id="9e50a-724">对于这些 Exchange 混合客户，如果用户的邮箱在本地，则用户无法添加或配置连接器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-724">For these Exchange hybrid customers, if the user's mailbox is on-premises, the user cannot add or configure Connectors.</span></span>  
  <span data-ttu-id="9e50a-725">可以从 <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> 下载 Microsoft Teams Windows 和 Mac 桌面客户端的安装程序。</span><span class="sxs-lookup"><span data-stu-id="9e50a-725">The installers for the Microsoft Teams Windows and Mac desktop clients can be downloaded from <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a>.</span></span>  </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9e50a-726"><strong>Office 365 高级威胁防护 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-726"><strong>Office 365 Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-727">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-727">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-728">启用安全链接、安全附件和防钓鱼。</span><span class="sxs-lookup"><span data-stu-id="9e50a-728">Enabling Safe Links, Safe Attachments, and anti-phishing.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-729">配置自动化、调查和响应。</span><span class="sxs-lookup"><span data-stu-id="9e50a-729">Configuring automation, investigation, and response.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-730">使用攻击模拟器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-730">Using Attack Simulator.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-731">报告和威胁分析。</span><span class="sxs-lookup"><span data-stu-id="9e50a-731">Reporting and threat analytics.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="9e50a-732">除了"<strong>常规"中的核心</strong>载入部分<a href="#general"></a>外，没有最低系统要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-732">Aside from the <strong>Core onboarding</strong> portion in <a href="#general">General</a>, there are no minimum system requirements.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9e50a-733"><strong>iOS 和 Android 版 Outlook</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-733"><strong>Outlook for iOS and Android</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-734">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-734">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-735">从 Apple App Store 和 Google Play 下载 Outlook for iOS 和 Outlook for Android。</span><span class="sxs-lookup"><span data-stu-id="9e50a-735">Downloading Outlook for iOS and Android from the Apple App Store and Google Play.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-736">配置帐户和访问 Exchange Online 邮箱。</span><span class="sxs-lookup"><span data-stu-id="9e50a-736">Configuring accounts and accessing the Exchange Online mailbox.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-737">保护 Outlook 移动 (请参阅在 Exchange Online 中保护 Outlook for iOS 和 <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Outlook for Android，</a> 了解) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-737">Securing Outlook mobile (see <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">Securing Outlook for iOS and Android in Exchange Online</a> for more information).</span></span>  </li>
</ul></td>
<td><ul>
<li>  <span data-ttu-id="9e50a-738">在适用于 Office 365 的 Azure AD 中启用的标识。</span><span class="sxs-lookup"><span data-stu-id="9e50a-738">Identities enabled in Azure AD for Office 365.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-739">配置了 Exchange Online 并分配了许可证。</span><span class="sxs-lookup"><span data-stu-id="9e50a-739">Exchange Online configured and licenses assigned.</span></span>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9e50a-740"><strong>Power BI</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-740"><strong>Power BI</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-741">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-741">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-742">分配 Power BI 许可证。</span><span class="sxs-lookup"><span data-stu-id="9e50a-742">Assigning Power BI licenses.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-743">部署 Power BI Desktop 应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-743">Deploying the Power BI Desktop app.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="9e50a-744">Power BI Desktop 等联机客户端软件必须处于最低级别，如 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>和 Office 的系统要求所定义。</span><span class="sxs-lookup"><span data-stu-id="9e50a-744">Online client software like Power BI Desktop must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9e50a-745"><strong>Project Online</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-745"><strong>Project Online</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-746">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-746">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-747">验证 Project Online 依赖的基本 SharePoint 功能。</span><span class="sxs-lookup"><span data-stu-id="9e50a-747">Verifying basic SharePoint functionality that Project Online relies on.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-748">向你的租户添加 Project Online 服务（包括向用户添加订阅）。</span><span class="sxs-lookup"><span data-stu-id="9e50a-748">Adding the Project Online service to your tenant (including adding subscriptions to users).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-749">设置企业资源池 (ERP)。</span><span class="sxs-lookup"><span data-stu-id="9e50a-749">Setting up the Enterprise Resource Pool (ERP).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-750">创建你的首个项目。</span><span class="sxs-lookup"><span data-stu-id="9e50a-750">Creating your first project.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="9e50a-751">Project for Office 365 等联机客户端软件必须处于最低级别，如 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>和 Office 的系统要求所定义。</span><span class="sxs-lookup"><span data-stu-id="9e50a-751">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9e50a-752"><strong>Project Online Professional 和 Premium</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-752"><strong>Project Online Professional and Premium</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-753">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-753">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-754">解决部署问题。</span><span class="sxs-lookup"><span data-stu-id="9e50a-754">Addressing deployment issues.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-755">使用 Microsoft 365 管理中心和 Windows PowerShell 分配最终用户许可证。</span><span class="sxs-lookup"><span data-stu-id="9e50a-755">Assigning end-user licenses using the Microsoft 365 admin center and Windows PowerShell.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-756">使用即点即用从 Office 365 门户安装 Project Online 桌面客户端。</span><span class="sxs-lookup"><span data-stu-id="9e50a-756">Installing Project Online Desktop Client from the Office 365 portal using Click-to-Run.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-757">使用 Office 365 部署工具配置更新设置。</span><span class="sxs-lookup"><span data-stu-id="9e50a-757">Configuring update settings using the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-758">为 Project Online 桌面客户端 设置一个现场分发服务器，包括帮助创建 configuration.xml 文件以与 Office 365 部署工具一起使用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-758">Setting up a single on-site distribution server for Project Online Desktop Client, including assistance with the creation of a configuration.xml file for use with the Office 365 Deployment Tool.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-759">将 Project Online 桌面客户端 连接到 Project Online Professional 或 Project Online 高级版。</span><span class="sxs-lookup"><span data-stu-id="9e50a-759">Connecting Project Online Desktop Client to Project Online Professional or Project Online Premium.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="9e50a-760">Project for Office 365 等联机客户端软件必须处于最低级别，如 <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365</a>和 Office 的系统要求所定义。</span><span class="sxs-lookup"><span data-stu-id="9e50a-760">Online client software like Project for Office 365 must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9e50a-761"><strong>SharePoint Online 和 OneDrive for Business</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-761"><strong>SharePoint Online and OneDrive for Business</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-762">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-762">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-763">设置 DNS。</span><span class="sxs-lookup"><span data-stu-id="9e50a-763">Setting up DNS.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-764">配置防火墙端口。</span><span class="sxs-lookup"><span data-stu-id="9e50a-764">Configuring firewall ports.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-765">设置用户和许可证。</span><span class="sxs-lookup"><span data-stu-id="9e50a-765">Provisioning users and licenses.</span></span>  </li>
<li><span data-ttu-id="9e50a-766">为你的 SharePoint Online 管理员启用站点创建。</span><span class="sxs-lookup"><span data-stu-id="9e50a-766">Enabling site creation for your SharePoint Online admin.</span></span></li>
<li><span data-ttu-id="9e50a-767">规划网站集。</span><span class="sxs-lookup"><span data-stu-id="9e50a-767">Planning site collections.</span></span></li>
<li><span data-ttu-id="9e50a-768">保护内容安全和管理权限。</span><span class="sxs-lookup"><span data-stu-id="9e50a-768">Securing content and managing permissions.</span></span></li>
<li><span data-ttu-id="9e50a-769">配置 SharePoint Online 功能。</span><span class="sxs-lookup"><span data-stu-id="9e50a-769">Configuring SharePoint Online features.</span></span></li>
<li>  <span data-ttu-id="9e50a-770">配置 SharePoint 混合功能，如混合搜索、混合网站、混合分类、内容类型、混合自助式网站创建（仅适用于 SharePoint Server 2013）、扩展的应用启动器、混合 OneDrive for Business 和 Extranet 网站。</span><span class="sxs-lookup"><span data-stu-id="9e50a-770">Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-771">迁移方法。</span><span class="sxs-lookup"><span data-stu-id="9e50a-771">Your migration approach.</span></span>  </li>
</ul>
<span data-ttu-id="9e50a-772">根据 SharePoint 版本，为 OneDrive for Business 提供了其他指南，例如：</span><span class="sxs-lookup"><span data-stu-id="9e50a-772">Additional guidance is provided for OneDrive for Business depending on your SharePoint version, like:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-773">确定集成选项并查看本地和联机网络基础结构和带宽。</span><span class="sxs-lookup"><span data-stu-id="9e50a-773">Identifying integration options and reviewing on-premises and online network infrastructure and bandwidth.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-774">安装 SharePoint Online 2013 SP1 (（如果适用) ，规划和实现同步和标识要求，以及标识 OneDrive for Business 同步客户端。</span><span class="sxs-lookup"><span data-stu-id="9e50a-774">Installing SharePoint Online 2013 SP1 (if applicable), planning and implementing sync and identity requirements, and identifying your OneDrive for Business sync client.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-775">为所有用户规划和实施单个推出 (或分阶段推出) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-775">Planning and implementing a single rollout for all users (or a phased rollout).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-776">分配许可证、将"我的网站"和个人文档库重定向到适用于 SharePoint Online 2013 (的 Office 365) ，设置访问群体以控制对适用于 SharePoint Online 2013 (的 OneDrive) 的访问。</span><span class="sxs-lookup"><span data-stu-id="9e50a-776">Assigning licenses, redirecting My Sites and personal document libraries to Office 365 (applicable to SharePoint Online 2013), setting up audiences to control access to OneDrive (applicable to SharePoint Online 2013).</span></span>  </li>
<li><span data-ttu-id="9e50a-777">将已知文件夹重定向或移动到 OneDrive。</span><span class="sxs-lookup"><span data-stu-id="9e50a-777">Redirecting or moving known folders to OneDrive.</span></span></li>
<li>  <span data-ttu-id="9e50a-778">部署 OneDrive for Business 客户端同步。</span><span class="sxs-lookup"><span data-stu-id="9e50a-778">Deploying the OneDrive for Business client sync.</span></span>  </li>
</ul><span data-ttu-id="9e50a-779">
  <strong>数据迁移</strong>  </span><span class="sxs-lookup"><span data-stu-id="9e50a-779">
  <strong>Data migration</strong>  </span></span><br>
<span data-ttu-id="9e50a-780">有关将数据迁移到 Office 365 的 FastTrack 权益的信息，请参阅<a href="https://docs.microsoft.com/fasttrack/data-migration">"数据迁移"。</a></span><span class="sxs-lookup"><span data-stu-id="9e50a-780">For information on using the FastTrack benefit for data migration to Office 365, see <a href="https://docs.microsoft.com/fasttrack/data-migration">Data Migration</a>.</span></span>
</ul></td>
<td><br><span data-ttu-id="9e50a-781"><strong>对于 SharePoint 混合：</strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-781"><strong>For SharePoint hybrid:</strong>  
</span></span><ul>
<li>  <span data-ttu-id="9e50a-782">SharePoint 混合配置包括配置混合搜索、网站、分类、内容类型、OneDrive for Business、扩展的应用程序启动器、Extranet 网站以及从本地连接到单个目标 SharePoint Online 环境的自助式网站创建。</span><span class="sxs-lookup"><span data-stu-id="9e50a-782">SharePoint hybrid configuration includes configuring hybrid search, sites, taxonomy, content types, OneDrive for Business, an extended app launcher, extranet sites, and self-service site creation connected from on-premises to a single target SharePoint Online environment.</span></span>  </li>
</ul><span data-ttu-id="9e50a-783">
  <strong>注意：</strong> 自助式网站创建不在运行 SharePoint 2013 的本地服务器范围内。</span><span class="sxs-lookup"><span data-stu-id="9e50a-783">
  <strong>Note:</strong> Self-service site creation is not in scope with on-premises servers running SharePoint 2013.</span></span>  
<ul>
<li>  <span data-ttu-id="9e50a-784">若要启用 SharePoint 混合，您必须具有以下本地 SharePoint Server 环境之一：2013、2016 或 2019。</span><span class="sxs-lookup"><span data-stu-id="9e50a-784">To enable SharePoint hybrid, you must have one of the following on-premises SharePoint Server environments: 2013, 2016, or 2019.</span></span>  </li>
</ul><span data-ttu-id="9e50a-785">
  <strong>注意：</strong> 将本地 SharePoint 环境升级到 SharePoint Server 不在范围内。</span><span class="sxs-lookup"><span data-stu-id="9e50a-785">
  <strong>Note:</strong> Upgrade of on-premises SharePoint environments to SharePoint Server is not in scope.</span></span> <span data-ttu-id="9e50a-786">请联系 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴寻求帮助</a> 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-786">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance.</span></span> <span data-ttu-id="9e50a-787">有关详细信息，请参阅 <a href="https://go.microsoft.com/fwlink/?linkid=853548">SharePoint 混合功能的最低公共更新级别</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="9e50a-787">For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=853548">Minimum public update levels for SharePoint hybrid features</a><em>.</em>  </span></span><br><span data-ttu-id="9e50a-788">
  <strong>注意：</strong> 有关多地理位置功能的信息，请参阅 Office <a href="https://go.microsoft.com/fwlink/?linkid=831056">365 中的 OneDrive 和 SharePoint Online 中的多地理位置功能</a><em>。</em>  </span><span class="sxs-lookup"><span data-stu-id="9e50a-788">
  <strong>Note:</strong> For information on Multi-Geo Capabilities, see <a href="https://go.microsoft.com/fwlink/?linkid=831056">Multi-Geo Capabilities in OneDrive and SharePoint Online in Office 365</a><em>.</em>  </span></span></td>
</tr>
<tr class="even">
<td><span data-ttu-id="9e50a-789"><strong>Yammer 企业版</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-789"><strong>Yammer Enterprise</strong></span></span></td>
<td><ul>
<span data-ttu-id="9e50a-790">我们提供启用 Yammer Enterprise 服务的远程指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-790">We provide remote guidance for enabling the Yammer Enterprise service.</span></span>  
</ul></td>
<td><span data-ttu-id="9e50a-791">联机客户端软件必须达到 Microsoft <a href="https://go.microsoft.com/fwlink/?LinkID=723597">365</a>和 Office 的系统要求中定义的最低级别。</span><span class="sxs-lookup"><span data-stu-id="9e50a-791">Online client software must be at a minimum level as defined in the <a href="https://go.microsoft.com/fwlink/?LinkID=723597">System requirements for Microsoft 365 and Office</a>.</span></span></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a><span data-ttu-id="9e50a-792">企业移动性 + 安全性</span><span class="sxs-lookup"><span data-stu-id="9e50a-792">Enterprise Mobility + Security</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9e50a-793"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-793"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="9e50a-794"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-794"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="9e50a-795"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-795"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="9e50a-796"><strong>Azure Active Directory (Azure AD) 和 Azure AD Premium</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-796"><strong>Azure Active Directory (Azure AD) and Azure AD Premium</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-797">我们针对以下方案提供用于保护云标识的远程指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-797">We provide remote guidance for securing your cloud identities for the following scenarios.</span></span>  

 <br/><span data-ttu-id="9e50a-798">

<strong>安全的基础基础结构</strong>  </ul>
</span><span class="sxs-lookup"><span data-stu-id="9e50a-798">

<strong>Secure foundation infrastructure</strong>  </ul>
</span></span><ul>
<li>  <span data-ttu-id="9e50a-799">为标识配置和启用强身份验证，包括使用 Azure 多重身份验证 (MFA)  (云仅) 、Microsoft Authenticator 应用以及 Azure MFA 和自助服务密码重置 (SSPR) 的组合注册进行保护。</span><span class="sxs-lookup"><span data-stu-id="9e50a-799">Configuring and enabling strong authentication for your identities, including protecting with Azure Multi-Factor Authentication (MFA) (cloud only), the Microsoft Authenticator app, and combined registration for Azure MFA and self-service password reset (SSPR).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-800">对于非 Azure AD Premium 客户，提供了使用安全默认值保护标识的指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-800">For non-Azure AD Premium customers, guidance is provided to secure your identities using security defaults.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-801">对于 Azure AD 高级客户，提供了使用条件访问保护标识的指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-801">For Azure AD premium customers, guidance is provided to secure your identities with Conditional Access.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-802">通过 Azure AD 密码保护检测和阻止使用弱密码。</span><span class="sxs-lookup"><span data-stu-id="9e50a-802">Detecting and blocking the use of weak passwords with Azure AD Password Protection.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-803">使用 Azure AD 应用程序代理保护对本地 Web 应用的远程访问。</span><span class="sxs-lookup"><span data-stu-id="9e50a-803">Securing remote access to on-premises web apps with Azure AD Application Proxy.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-804">使用 Azure Identity Protection 启用基于风险的检测和修正。</span><span class="sxs-lookup"><span data-stu-id="9e50a-804">Enabling risk-based detection and remediation with Azure Identity Protection.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-805">启用自定义登录屏幕，包括徽标、文本和具有自定义品牌的图像。</span><span class="sxs-lookup"><span data-stu-id="9e50a-805">Enabling a customized sign-in screen, including logo, text, and images with custom branding.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-806">使用 Azure AD B2B 安全地与来宾用户共享应用和服务。</span><span class="sxs-lookup"><span data-stu-id="9e50a-806">Securely sharing apps and services with guest users using Azure AD B2B.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-807">使用基于角色的访问控制 (RBAC) 内置管理角色管理 Office 365 管理员的访问权限，并减少特权管理员帐户的数量。</span><span class="sxs-lookup"><span data-stu-id="9e50a-807">Managing access for your Office 365 admins using role-based access control (RBAC) built-in administrative roles and to reduce the number of privileged admin accounts.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-808">配置混合 Azure AD 加入。</span><span class="sxs-lookup"><span data-stu-id="9e50a-808">Configuring hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-809">配置 Azure AD 加入。</span><span class="sxs-lookup"><span data-stu-id="9e50a-809">Configuring Azure AD join.</span></span>  </li>
</ul><span data-ttu-id="9e50a-810">
  
<strong>监视和报告</strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-810">
  
<strong>Monitor and reporting</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="9e50a-811">使用 Azure AD Connect Health 为 AD FS、Azure AD Connect 和域控制器启用远程监视。</span><span class="sxs-lookup"><span data-stu-id="9e50a-811">Enabling remote monitoring for AD FS, Azure AD Connect, and domain controllers with Azure AD Connect Health.</span></span>  
  </li>
</ul><span data-ttu-id="9e50a-812">
  
<strong>治理</strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-812">
  
<strong>Governance</strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="9e50a-813">通过 Azure AD 权利管理大规模管理 Azure AD 标识和访问生命周期。</span><span class="sxs-lookup"><span data-stu-id="9e50a-813">Managing your Azure AD identity and access lifecycle at scale with Azure AD entitlement management.</span></span>
  </li>
<li>  
  <span data-ttu-id="9e50a-814">使用 Azure AD 访问评审管理 Azure AD 组成员身份、企业应用访问权限和角色分配。</span><span class="sxs-lookup"><span data-stu-id="9e50a-814">Managing Azure AD group memberships, enterprise app access, and role assignments with Azure AD access reviews.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-815">查看 Azure AD 使用条款。</span><span class="sxs-lookup"><span data-stu-id="9e50a-815">Reviewing Azure AD Terms of Use.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-816">使用 Azure AD Privileged Identity Management 管理和控制对特权管理员帐户的访问。</span><span class="sxs-lookup"><span data-stu-id="9e50a-816">Managing and controlling access to privileged admin accounts with Azure AD Privileged Identity Management.</span></span>  
  </li>
</ul><span data-ttu-id="9e50a-817">
  
<strong>自动化和效率 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-817">
  
<strong>Automation and efficiencies </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="9e50a-818">启用 Azure AD SSPR。</span><span class="sxs-lookup"><span data-stu-id="9e50a-818">Enabling Azure AD SSPR.</span></span>  
  </li>
<li>  <span data-ttu-id="9e50a-819">允许用户使用 Azure AD 自助服务组管理创建和管理自己的云安全或 Office 365 组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-819">Allowing users to create and manage their own cloud security or Office 365 groups with Azure AD self-service group management.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-820">使用 Azure AD 委派组管理管理企业应用的委派访问权限。</span><span class="sxs-lookup"><span data-stu-id="9e50a-820">Managing delegated access to enterprise apps with Azure AD delegated group management.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-821">启用 Azure AD 动态组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-821">Enabling Azure AD dynamic groups.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-822">使用集合在"我的应用"门户中组织应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-822">Organizing apps in the My Apps portal using collections.</span></span>  </li>
</ul></td>
<td><span data-ttu-id="9e50a-823">本地 Active Directory 及其环境已针对 Azure AD Premium 做好准备，包括修复阻止与 Azure AD 和 Azure AD Premium 功能集成的已识别问题。</span><span class="sxs-lookup"><span data-stu-id="9e50a-823">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, including remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="9e50a-824"><strong>Azure 信息保护 </strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-824"><strong>Azure Information Protection </strong></span></span></td>
<td>  <span data-ttu-id="9e50a-825">有关 Azure 信息保护详细信息，请参阅 <strong>"安全性和合规性中的 Microsoft 信息</strong> <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> 保护"。</span><span class="sxs-lookup"><span data-stu-id="9e50a-825">For more information on Azure Information Protection, see <strong>Microsoft Information Protection</strong> in <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">Security and Compliance.</span></span>  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><span data-ttu-id="9e50a-826"><strong>Microsoft Intune</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-826"><strong>Microsoft Intune</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-827">我们提供有关准备好使用 Intune 作为应用和设备的基于云的移动设备管理 (MDM) 和移动应用管理 (MAM) 提供程序的远程指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-827">We provide remote guidance on getting ready to use Intune as the cloud-based mobile device management (MDM) and mobile app management (MAM) provider for your apps and devices.</span></span> <span data-ttu-id="9e50a-828">具体步骤取决于你的源环境，并且基于你的移动设备和移动应用管理需求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-828">The exact steps depend on your source environment and are based on your mobile device and mobile app management needs.</span></span> <span data-ttu-id="9e50a-829">所包含的具体步骤如下：</span><span class="sxs-lookup"><span data-stu-id="9e50a-829">The steps can include:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-830">许可最终用户。</span><span class="sxs-lookup"><span data-stu-id="9e50a-830">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-831">通过利用本地 Active Directory 或 Azure AD (云标识配置由 Intune 使用的) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-831">Configuring identities to be used by Intune by leveraging either your on-premises Active Directory or cloud identities (Azure AD).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-832">将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-832">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-833">根据管理需求配置 MDM 颁发机构，包括：</span><span class="sxs-lookup"><span data-stu-id="9e50a-833">Configuring your MDM authority, based on your management needs, including:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-834">如果 Intune 是唯一的 MDM 解决方案，将 Intune 设置为 MDM 颁发机构。</span><span class="sxs-lookup"><span data-stu-id="9e50a-834">Setting Intune as your MDM authority when Intune is your only MDM solution.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9e50a-835">为以下操作提供 MDM 指南:</span><span class="sxs-lookup"><span data-stu-id="9e50a-835">Providing MDM guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-836">配置用于验证 MDM 管理策略的测试组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-836">Configuring tests groups to be used to validate MDM management policies.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-837">配置 MDM 管理策略和服务，如：</span><span class="sxs-lookup"><span data-stu-id="9e50a-837">Configuring MDM management policies and services like:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-838">通过 Web 链接或深层链接针对每个受支持的平台的应用部署。</span><span class="sxs-lookup"><span data-stu-id="9e50a-838">App deployment for each supported platform through web links or deep links.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-839">条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-839">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-840">如果组织中已有证书颁发机构、无线网络或 VPN 基础结构，则部署电子邮件、无线网络和 VPN 配置文件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-840">Deployment of email, wireless networks, and VPN profiles if you have an existing certificate authority, wireless network, or VPN infrastructure in your organization.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-841">连接到 Intune 数据仓库。</span><span class="sxs-lookup"><span data-stu-id="9e50a-841">Connecting to the Intune Data Warehouse.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-842">将 Intune 与以下内容进行集成：</span><span class="sxs-lookup"><span data-stu-id="9e50a-842">Integrating Intune with:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-843">需要团队查看器 (团队查看器订阅的远程) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-843">Team Viewer for remote assistance (a Team Viewer subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-844">移动威胁防护 (MTD) MTD (需要 MTD 订阅) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-844">Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-845">需要电信费用管理解决方案 (需要电信费用管理解决方案订阅) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-845">A telecom expense management solution (a telecom expense management solution subscription is required).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9e50a-846">将每个受支持平台的设备注册到 Intune。</span><span class="sxs-lookup"><span data-stu-id="9e50a-846">Enrolling devices of each supported platform to Intune.</span></span>  </li>
</ul></li>
</ul></li>
<li>  <span data-ttu-id="9e50a-847">提供应用保护指南，</span><span class="sxs-lookup"><span data-stu-id="9e50a-847">Providing app protection guidance on:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-848">为每个受支持的平台配置应用保护策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-848">Configuring app protection policies for each supported platform.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-849">为托管应用配置条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-849">Configuring Conditional Access policies for managed apps.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-850">使用前面提到的 MAM 策略面向相应的用户组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-850">Targeting the appropriate user groups with the previously mentioned MAM policies.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-851">使用托管应用使用情况报告。</span><span class="sxs-lookup"><span data-stu-id="9e50a-851">Using managed-apps usage reports.</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9e50a-852">提供从旧版电脑管理到 Intune MDM 的迁移指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-852">Providing migration guidance from legacy PC management to Intune MDM.</span></span>  </li>
</ul><span data-ttu-id="9e50a-853">
  
</li>
</ul>
  
<strong>云附加</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-853">
  
</li>
</ul>
  
<strong>Cloud-attach</strong></span></span>  

  <span data-ttu-id="9e50a-854">我们将指导你准备好使用 Intune 云附加现有 Configuration Manager 环境。</span><span class="sxs-lookup"><span data-stu-id="9e50a-854">We guide you through getting ready to cloud-attach existing Configuration Manager environments with Intune.</span></span> <span data-ttu-id="9e50a-855">具体步骤取决于源环境。</span><span class="sxs-lookup"><span data-stu-id="9e50a-855">The exact steps depend on your source environment.</span></span> <span data-ttu-id="9e50a-856">这些步骤包括：</span><span class="sxs-lookup"><span data-stu-id="9e50a-856">These steps can include:</span></span>  
<ul>
<li>  <span data-ttu-id="9e50a-857">许可最终用户。</span><span class="sxs-lookup"><span data-stu-id="9e50a-857">Licensing your end users.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-858">通过利用本地 Active Directory 和云标识，配置供 Intune 使用的标识。</span><span class="sxs-lookup"><span data-stu-id="9e50a-858">Configuring identities to be used by Intune by leveraging your on-premises Active Directory and cloud identities.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-859">将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-859">Adding users to your Intune subscription, defining IT admin roles, and creating user and device groups.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-860">提供设置混合 Azure AD 加入的指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-860">Providing guidance setting up hybrid Azure AD join.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-861">提供有关为 MDM 自动注册设置 Azure AD 的指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-861">Providing guidance on setting up Azure AD for MDM auto-enrollment.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-862">提供有关在将云管理网关用作远程基于 Internet 的设备管理共同管理的解决方案时如何设置云管理网关的指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-862">Providing guidance on how to set up cloud management gateway when used as a solution for co-management of remote internet-based device management.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-863">配置要切换到 Intune 的受支持工作负载。</span><span class="sxs-lookup"><span data-stu-id="9e50a-863">Configuring supported workloads that you want to switch to Intune.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-864">在 Intune 注册的设备中安装 Configuration Manager 客户端。</span><span class="sxs-lookup"><span data-stu-id="9e50a-864">Installing the Configuration Manager client on Intune-enrolled devices.</span></span>  </li>
</ul> 

<span data-ttu-id="9e50a-865"><strong>安全地部署适用于 iOS 和 Android 的 Outlook 移动版</strong> 我们可以提供指导，帮助你在组织中安全地部署适用于 iOS 和 Android 的 Outlook 移动版，以确保用户已安装所有必需的应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-865"><strong>Deploy Outlook mobile for iOS and Android securely</strong> We can provide guidance to help you deploy Outlook mobile for iOS and Android securely in your organization to ensure your users have all the required apps installed.</span></span>  
  <span data-ttu-id="9e50a-866">使用 Intune 安全地部署适用于 iOS 和 Android 的 Outlook 移动版的步骤取决于您的源环境。</span><span class="sxs-lookup"><span data-stu-id="9e50a-866">The steps to securely deploy Outlook mobile for iOS and Android with Intune depends on your source environment.</span></span> <span data-ttu-id="9e50a-867">它可以包括：</span><span class="sxs-lookup"><span data-stu-id="9e50a-867">It can include:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-868">通过 Apple App Store 或 Google Play 商店下载 Outlook for iOS 和 Android、Microsoft Authenticator 和 Intune 公司门户应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-868">Downloading the Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps through the Apple App Store or Google Play Store.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-869">提供有关设置的指导：</span><span class="sxs-lookup"><span data-stu-id="9e50a-869">Providing guidance on setting up:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-870">使用 Intune 部署 Outlook for iOS 和 Android、Microsoft Authenticator 和 Intune 公司门户应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-870">The Outlook for iOS and Android, Microsoft Authenticator, and Intune Company Portal apps deployment with Intune.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-871">应用保护策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-871">App protection policies.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-872">条件访问策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-872">Conditional Access policies.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-873">应用配置策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-873">App configuration policies.</span></span>  </li>
</ul></li>
</ul>  
  </td>
<td>  <span data-ttu-id="9e50a-874">当规划使用 Intune 部署无线网络和 VPN 配置文件时，IT 管理员需要具有已在其生产环境中工作的现有证书颁发机构、无线网络和 VPN 基础结构。</span><span class="sxs-lookup"><span data-stu-id="9e50a-874">IT admins need to have existing Certificate Authority, wireless network, and VPN infrastructures already working in their production environments when planning on deploying wireless network and VPN profiles with Intune.</span></span>  
  <span data-ttu-id="9e50a-875"><strong>注意</strong>：FastTrack 服务权益不包括帮助为 Intune 设置或配置证书颁发机构、无线网络、VPN 基础结构或 Apple MDM 推送证书。</span><span class="sxs-lookup"><span data-stu-id="9e50a-875"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or configuring Certificate Authorities, wireless networks, VPN infrastructures, or Apple MDM push certificates for Intune.</span></span>  
 
  <span data-ttu-id="9e50a-876"><strong>注意</strong>：FastTrack 服务权益不包括有关将配置管理器站点服务器或配置管理器客户端设置或升级到支持云附加所需的最低要求的帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-876"><strong>Note</strong>: The FastTrack service benefit doesn't include assistance for setting up or upgrading either the Configuration Manager site server or Configuration Manager client to the minimum requirements needed to support cloud-attach.</span></span> <span data-ttu-id="9e50a-877">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-877">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>

  <span data-ttu-id="9e50a-878"><strong>Intune 与 Microsoft Defender 高级威胁防护 (ATP) 集成</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-878"><strong>Intune integrated with Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span> 
 
  <span data-ttu-id="9e50a-879"><strong>注意</strong>：我们协助将 Intune 与 Microsoft Defender ATP 集成，并基于 Windows 10 风险级别评估创建设备合规性策略。</span><span class="sxs-lookup"><span data-stu-id="9e50a-879"><strong>Note</strong>: We provide assistance on integrating Intune with Microsoft Defender ATP and creating device compliance policies based on its Windows 10 risk level assessment.</span></span> <span data-ttu-id="9e50a-880">我们不提供有关购买、许可或激活的帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-880">We don't provide assistance on purchasing, licensing, or activation.</span></span> <span data-ttu-id="9e50a-881">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-881">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with this.</span></span>  
  
<span data-ttu-id="9e50a-882"><strong>Windows Autopilot</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-882"><strong>Windows Autopilot</strong></span></span> 
 
  <span data-ttu-id="9e50a-883">IT 管理员负责通过让硬件供应商代表他们上载其硬件 ID 或自己将其上载到 Windows Autopilot 服务中来向其组织注册设备。</span><span class="sxs-lookup"><span data-stu-id="9e50a-883">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a><span data-ttu-id="9e50a-884">Windows 10</span><span class="sxs-lookup"><span data-stu-id="9e50a-884">Windows 10</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9e50a-885"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-885"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="9e50a-886"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-886"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="9e50a-887"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-887"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9e50a-888"><strong>Windows 10</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-888"><strong>Windows 10</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-889">我们提供从 Windows 7 专业版 和 Windows 8.1 专业版升级到 Windows 10 企业版的指导。</span><span class="sxs-lookup"><span data-stu-id="9e50a-889">We provide guidance for upgrading from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span>  
  <span data-ttu-id="9e50a-890">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-890">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-891">了解你的 Windows 10 意图。</span><span class="sxs-lookup"><span data-stu-id="9e50a-891">Understanding your Windows 10 intention.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-892">评估源环境和要求 (确保 Microsoft Endpoint Configuration Manager 升级到所需级别以支持 Windows 10 部署) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-892">Assessing your source environment and the requirements (ensure that Microsoft Endpoint Configuration Manager is upgraded to the required level to support the Windows 10 deployment).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-893">使用 Microsoft Endpoint Configuration Manager 或 Microsoft 365 部署 Windows 10 企业版和 Microsoft 365 应用版。</span><span class="sxs-lookup"><span data-stu-id="9e50a-893">Deploying Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-894">推荐用于评估 Windows 10 应用的选项。</span><span class="sxs-lookup"><span data-stu-id="9e50a-894">Recommending options for you to assess your Windows 10 apps.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-895">通过创建桌面分析部署计划，支持使用桌面分析和指导。</span><span class="sxs-lookup"><span data-stu-id="9e50a-895">Enabling use of Desktop Analytics and guidance through creation of a Desktop Analytics deployment plan.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-896">Microsoft 365 应用版兼容性评估，利用 Configuration Manager 中的 Office 365 准备情况仪表板或独立的 Office 就绪情况 Toolkit 以及 Microsoft 365 应用版部署帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-896">Microsoft 365 Apps compatibility assessment by leveraging the Office 365 readiness dashboard in Configuration Manager or with the stand-alone Readiness Toolkit for Office plus assistance deploying Microsoft 365 Apps.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-897">针对所需操作创建修正清单，使源环境达到成功部署的最低要求。</span><span class="sxs-lookup"><span data-stu-id="9e50a-897">Creating a remediation checklist on what you need to do to bring your source environment up to the minimum requirements for a successful deployment.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-898">如果你的现有设备满足所需的设备硬件要求，请为它们提供升级到 Windows 10 企业版的指导。</span><span class="sxs-lookup"><span data-stu-id="9e50a-898">Providing upgrade guidance for your existing devices to Windows 10 Enterprise if they meet the needed device hardware requirements.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-899">提供升级指南以支持现有部署运动。</span><span class="sxs-lookup"><span data-stu-id="9e50a-899">Providing upgrade guidance to support your existing deployment motion.</span></span> <span data-ttu-id="9e50a-900">FastTrack 推荐并提供有关就地升级到 Windows 10 的指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-900">FastTrack recommends and provides guidance for an in-place upgrade to Windows 10.</span></span> <span data-ttu-id="9e50a-901">指南还可用于 Windows 干净图片安装和 Windows Autopilot 部署方案。</span><span class="sxs-lookup"><span data-stu-id="9e50a-901">Guidance is also available for Windows clean image installation and Windows Autopilot deployment scenarios.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-902">使用 Configuration Manager 部署 Microsoft 365 应用作为 Windows 10 部署的一部分。</span><span class="sxs-lookup"><span data-stu-id="9e50a-902">Deploying Microsoft 365 Apps using Configuration Manager as part of the Windows 10 deployment.</span></span>   </li>
<li>  <span data-ttu-id="9e50a-903">提供指南，帮助你的组织使用现有的 Configuration Manager 环境或 Microsoft 365 使用 Windows 10 企业版和 Microsoft 365 应用版保持最新。</span><span class="sxs-lookup"><span data-stu-id="9e50a-903">Providing guidance to help your organization stay up to date with Windows 10 Enterprise and Microsoft 365 Apps using your existing Configuration Manager environment or Microsoft 365.</span></span>  </li>
</ul><span data-ttu-id="9e50a-904">
  <strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-904">
  <strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="9e50a-905">将 Configuration Manager 升级到当前分支。</span><span class="sxs-lookup"><span data-stu-id="9e50a-905">Upgrading Configuration Manager to Current Branch.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-906">创建适用于 Windows 10 部署的自定义映像。</span><span class="sxs-lookup"><span data-stu-id="9e50a-906">Creating custom images for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-907">创建和支持 Windows 10 部署的部署脚本。</span><span class="sxs-lookup"><span data-stu-id="9e50a-907">Creating and supporting deployment scripts for Windows 10 deployment.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-908">将 Windows 10 系统从 BIOS 转换为统一可扩展固件接口 (UEFI)。</span><span class="sxs-lookup"><span data-stu-id="9e50a-908">Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-909">启用 Windows 10 安全功能。</span><span class="sxs-lookup"><span data-stu-id="9e50a-909">Enabling Windows 10 security features.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-910">配置用于启动前执行环境 (PXE) 启动的 Windows 部署服务 (WDS)。</span><span class="sxs-lookup"><span data-stu-id="9e50a-910">Configuring Windows Deployment Services (WDS) for Preboot Execution Environment (PXE) booting.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-911">使用 Microsoft 部署工具包 (MDT) 捕获和部署 Windows 10 映像。</span><span class="sxs-lookup"><span data-stu-id="9e50a-911">Using the Microsoft Deployment Toolkit (MDT) to capture and deploy Windows 10 images.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-912">使用用户状态迁移工具 (USMT)。</span><span class="sxs-lookup"><span data-stu-id="9e50a-912">Using the User State Migration Tool (USMT).</span></span>  </li>
</ul>
<span data-ttu-id="9e50a-913">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-913">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>
<td>  <span data-ttu-id="9e50a-914">要升级电脑，必须满足以下要求：</span><span class="sxs-lookup"><span data-stu-id="9e50a-914">For PC upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-915">源操作系统：Windows 7 企业版专业版、Windows 8.1 企业版或专业版。</span><span class="sxs-lookup"><span data-stu-id="9e50a-915">Source OS: Windows 7 Enterprise or Professional, Windows 8.1 Enterprise or Professional.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-916">设备：台式机、笔记本或平板电脑外形型号。</span><span class="sxs-lookup"><span data-stu-id="9e50a-916">Devices: Desktop, notebook, or tablet form factor.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-917">目标操作系统：窗口 10 企业版。</span><span class="sxs-lookup"><span data-stu-id="9e50a-917">Target OS: Window 10 Enterprise.</span></span>  </li>
</ul>
<span data-ttu-id="9e50a-918">若要升级基础结构，必须满足以下要求：</span><span class="sxs-lookup"><span data-stu-id="9e50a-918">For infrastructure upgrade, you must meet these requirements:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-919">Microsoft Endpoint Configuration Manager。</span><span class="sxs-lookup"><span data-stu-id="9e50a-919">Microsoft Endpoint Configuration Manager.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-920">Configuration Manager 版本必须受 Windows 10 目标版本支持。</span><span class="sxs-lookup"><span data-stu-id="9e50a-920">The Configuration Manager version must be supported by the Windows 10 target version.</span></span> <span data-ttu-id="9e50a-921">有关详细信息，请参阅 <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Configuration Manager 中的 Windows 10 支持</a>中的 Configuration Manager 支持表格。</span><span class="sxs-lookup"><span data-stu-id="9e50a-921">For more information, see the Configuration Manager support table at <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">Support for Windows 10 in Configuration Manager</a>.</span></span>  </li>
</ul>

<tr class="odd">
<td><span data-ttu-id="9e50a-922"><strong>Microsoft Defender 高级威胁防护 (ATP)</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-922"><strong>Microsoft Defender Advanced Threat Protection (ATP)</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-923">Microsoft Defender 高级威胁防护 (ATP) 是旨在帮助企业网络预防、检测、调查和响应高级威胁的平台。</span><span class="sxs-lookup"><span data-stu-id="9e50a-923">Microsoft Defender Advanced Threat Protection (ATP) is a platform designed to help enterprise networks prevent, detect, investigate, and respond to advanced threats.</span></span>  
  <span data-ttu-id="9e50a-924">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-924">We provide remote guidance for:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-925">部署用于保护终结点的技术。</span><span class="sxs-lookup"><span data-stu-id="9e50a-925">Deploying the technologies to secure your endpoints.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-926">配置终结点保护和设备限制配置文件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-926">Configuring endpoint protection and device restriction profiles.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-927">评估操作系统版本和设备管理 (包括 Intune、Microsoft Endpoint Configuration Manager、组策略对象 (GPO) 和第三方配置) 以及 Windows Defender AV 服务或其他终结点安全软件的状态。</span><span class="sxs-lookup"><span data-stu-id="9e50a-927">Assessing the OS version and device management (including Intune, Microsoft Endpoint Configuration Manager, Group Policy Objects (GPOs), and third-party configurations) as well as the status of your Windows Defender AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-928">评估 Windows AV 服务或其他终结点安全软件的状态。</span><span class="sxs-lookup"><span data-stu-id="9e50a-928">Assessing the status of your Windows AV services or other endpoint security software.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-929">评估限制网络流量的代理和防火墙。</span><span class="sxs-lookup"><span data-stu-id="9e50a-929">Assessing proxies and firewalls restricting network traffic.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-930">通过说明如何使用载入终结点部署 ATP 代理配置文件来启用 Microsoft Defender ATP 服务。</span><span class="sxs-lookup"><span data-stu-id="9e50a-930">Enabling the Microsoft Defender ATP service by explaining how to deploy an ATP agent profile using an onboard endpoint.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-931">部署指南、配置协助和教育：</span><span class="sxs-lookup"><span data-stu-id="9e50a-931">Deployment guidance, configuration assistance, and education on:</span></span>
<ul>
<li>  
  <span data-ttu-id="9e50a-932">威胁和漏洞管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-932">Threat and vulnerability management.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-933">攻击面减少。</span><span class="sxs-lookup"><span data-stu-id="9e50a-933">Attack surface reduction.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-934">新一代保护。</span><span class="sxs-lookup"><span data-stu-id="9e50a-934">Next-generation protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-935">终结点检测和响应。</span><span class="sxs-lookup"><span data-stu-id="9e50a-935">Endpoint detection and response.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-936">自动调查和修复。</span><span class="sxs-lookup"><span data-stu-id="9e50a-936">Automated investigation and remediation.</span></span>  
  </li>
<li> <span data-ttu-id="9e50a-937">需要 Microsoft Defender ATP (Windows E5 或 Microsoft 365 E5 许可证) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-937">Microsoft Defender ATP (Windows E5 or Microsoft 365 E5 licenses are required).</span></span>  </li>
<li>  
  <span data-ttu-id="9e50a-938">安全功能分数。</span><span class="sxs-lookup"><span data-stu-id="9e50a-938">Secure score.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="9e50a-939">查看模拟和教程 (方案、虚假恶意软件和自动调查等) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-939">Reviewing simulations and tutorials (like practice scenarios, fake malware, and automated investigations).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-940">报告和威胁分析功能概述。</span><span class="sxs-lookup"><span data-stu-id="9e50a-940">Overview of reporting and threat analytics features.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-941">将 Office 365 ATP 与 Microsoft Defender ATP 集成。</span><span class="sxs-lookup"><span data-stu-id="9e50a-941">Integrating Office 365 ATP with Microsoft Defender ATP.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-942">在 Microsoft Defender 安全中心门户中执行演练。</span><span class="sxs-lookup"><span data-stu-id="9e50a-942">Conduct walkthroughs of the Microsoft Defender Security Center portal.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-943">以下操作系统：</span><span class="sxs-lookup"><span data-stu-id="9e50a-943">The following operating systems:</span></span>
<ul>
<li>  
  <span data-ttu-id="9e50a-944">Windows 10。</span><span class="sxs-lookup"><span data-stu-id="9e50a-944">Windows 10.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-945">Windows Server 2016。</span><span class="sxs-lookup"><span data-stu-id="9e50a-945">Windows Server 2016.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-946">Windows Server 2019。</span><span class="sxs-lookup"><span data-stu-id="9e50a-946">Windows Server 2019.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-947">Windows Server 2019 Core Edition。</span><span class="sxs-lookup"><span data-stu-id="9e50a-947">Windows Server 2019 Core Edition.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-948">Windows Server Semi-Annual Channel (SAC) 版本 1803。</span><span class="sxs-lookup"><span data-stu-id="9e50a-948">Windows Server Semi-Annual Channel (SAC) version 1803.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-949">macOS 版本 10.13、10.14 和 10.15。</span><span class="sxs-lookup"><span data-stu-id="9e50a-949">macOS versions 10.13, 10.14, and 10.15.</span></span>  
  </li>
</ul>
</li>
</ul><span data-ttu-id="9e50a-950">
<strong>注意：</strong> 所有 Windows Server 版本都必须由最新版本的 System Center Configuration Manager 2012 (版本 1012 R2、1511 或 1602) 或 Microsoft Endpoint Configuration Manager (版本 2002 或) 管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-950">
<strong>Note:</strong> All Windows Server versions must be managed by the latest version of System Center Configuration Manager 2012 (versions 1012 R2, 1511, or 1602) or Microsoft Endpoint Configuration Manager (version 2002 or greater).</span></span> 

<span data-ttu-id="9e50a-951"></li>
</ul>

<strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-951"></li>
</ul>

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="9e50a-952">客户补救活动的项目管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-952">Project management of the customer's remediation activities.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-953">现场支持。</span><span class="sxs-lookup"><span data-stu-id="9e50a-953">On-site support.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-954">持续管理和威胁响应。</span><span class="sxs-lookup"><span data-stu-id="9e50a-954">Ongoing management and threat response.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-955">以下 Microsoft Defender ATP 代理的加入或配置：</span><span class="sxs-lookup"><span data-stu-id="9e50a-955">Onboarding or configuration for the following Microsoft Defender ATP agents:</span></span>
<ul>
<li>  
  <span data-ttu-id="9e50a-956">Windows Server 2008。</span><span class="sxs-lookup"><span data-stu-id="9e50a-956">Windows Server 2008.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-957">Windows Server 2012。</span><span class="sxs-lookup"><span data-stu-id="9e50a-957">Windows Server 2012.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-958">Linux。</span><span class="sxs-lookup"><span data-stu-id="9e50a-958">Linux.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-959">Android 和 iOS (移动设备) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-959">Mobile devices (Android and iOS).</span></span>  
  </li>
<li> <span data-ttu-id="9e50a-960">虚拟桌面基础结构 (VDI)  (持久或非永久性) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-960">Virtual Desktop Infrastructure (VDI) (persistent or non-persistent).</span></span>  </li>
</ul></li>
<li>  <span data-ttu-id="9e50a-961">服务器载入和配置：</span><span class="sxs-lookup"><span data-stu-id="9e50a-961">Server onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="9e50a-962">为脱机通信配置代理服务器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-962">Configuring a proxy server for offline communications.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-963">在下层 Configuration Manager 实例和版本上配置 Configuration Manager 部署包。</span><span class="sxs-lookup"><span data-stu-id="9e50a-963">Configuring Configuration Manager deployment packages on down-level Configuration Manager instances and versions.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-964">将服务器载入 Azure 安全中心。</span><span class="sxs-lookup"><span data-stu-id="9e50a-964">Onboarding servers to Azure Security Center.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-965">未由 Configuration Manager 管理的服务器。</span><span class="sxs-lookup"><span data-stu-id="9e50a-965">Servers not managed by Configuration Manager.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="9e50a-966">macOS 载入和配置：</span><span class="sxs-lookup"><span data-stu-id="9e50a-966">macOS onboarding and configuration:</span></span>
<ul>
<li>  
  <span data-ttu-id="9e50a-967">基于 Intune 的手动部署。</span><span class="sxs-lookup"><span data-stu-id="9e50a-967">Manual Intune-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-968">基于 JAMF 的部署。</span><span class="sxs-lookup"><span data-stu-id="9e50a-968">JAMF-based deployment.</span></span>
  </li>
<li>  
  <span data-ttu-id="9e50a-969">MDM 的其他移动设备管理 () 基于产品的部署。</span><span class="sxs-lookup"><span data-stu-id="9e50a-969">Other mobile device management (MDM) product-based deployment.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-970">手动部署。</span><span class="sxs-lookup"><span data-stu-id="9e50a-970">Manual deployment.</span></span>  
  </li>
</ul></li>
<li>  <span data-ttu-id="9e50a-971">配置以下攻击面减少功能：</span><span class="sxs-lookup"><span data-stu-id="9e50a-971">Configuration of the following attack surface reduction capabilities:</span></span>
<ul>
<li>  
  <span data-ttu-id="9e50a-972">基于硬件的隔离。</span><span class="sxs-lookup"><span data-stu-id="9e50a-972">Hardware-based isolation.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-973">应用控件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-973">App control.</span></span>  
  </li>
<li> <span data-ttu-id="9e50a-974">设备控件。</span><span class="sxs-lookup"><span data-stu-id="9e50a-974">Device control.</span></span></li>
<li>  
  <span data-ttu-id="9e50a-975">Exploit Protection。</span><span class="sxs-lookup"><span data-stu-id="9e50a-975">Exploit protection.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-976">网络防火墙。</span><span class="sxs-lookup"><span data-stu-id="9e50a-976">Network firewall.</span></span>  
  </li>

<ul>
<li> <span data-ttu-id="9e50a-977">Windows Hello</span><span class="sxs-lookup"><span data-stu-id="9e50a-977">Windows Hello</span></span></li>
<li> <span data-ttu-id="9e50a-978">Credential Guard</span><span class="sxs-lookup"><span data-stu-id="9e50a-978">Credential Guard</span></span></li>
</ul>

</ul></li>
<li> <span data-ttu-id="9e50a-979">BitLocker 的配置或管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-979">Configuration or management of BitLocker.</span></span></li>
<li>  <span data-ttu-id="9e50a-980">注册或配置 Microsoft 威胁专家。</span><span class="sxs-lookup"><span data-stu-id="9e50a-980">Enrollment or configuration of Microsoft Threat Experts.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-981">在 SIEM 连接中查看 API 或安全信息 (或) 培训。</span><span class="sxs-lookup"><span data-stu-id="9e50a-981">Configuration or training reviewing API or security information and event management (SIEM) connections.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-982">注册或配置 Microsoft 威胁防护 (MTP)。</span><span class="sxs-lookup"><span data-stu-id="9e50a-982">Enrollment or configuration of Microsoft Threat Protection (MTP).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-983">有关高级搜寻的培训或指导。</span><span class="sxs-lookup"><span data-stu-id="9e50a-983">Training or guidance covering advanced hunting.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-984">有关使用或创建 Kusto 查询的培训或指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-984">Training or guidance covering the use of or creation of Kusto queries.</span></span></li>
</li>
</ul>
<span data-ttu-id="9e50a-985">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-985">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  
</ul></td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a><span data-ttu-id="9e50a-986">Windows 虚拟桌面</span><span class="sxs-lookup"><span data-stu-id="9e50a-986">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9e50a-987"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-987"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="9e50a-988"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-988"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="9e50a-989"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-989"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="9e50a-990"><strong>Windows 虚拟桌面</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-990"><strong>Windows Virtual Desktop</strong></span></span></td>
<td><p><span data-ttu-id="9e50a-991">我们提供载入 Windows 虚拟桌面的部署指南 (桌面应用虚拟化服务) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-991">We provide deployment guidance for onboarding to Windows Virtual Desktop (a desktop and app virtualization service).</span></span> <span data-ttu-id="9e50a-992">Windows 虚拟桌面利用 Windows 10 多会话体验，并针对 Microsoft 365 企业应用版进行了优化，集成了 Microsoft 365 的安全性和管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-992">Windows Virtual Desktop takes advantage of Windows 10 multi-session experience and is optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="9e50a-993">我们提供远程指导，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-993">We provide remote guidance for:</span></span></p>
<ul>
<li><span data-ttu-id="9e50a-994">使用 Windows 10 企业版多会话和 Microsoft 365 企业应用版部署 Windows 虚拟桌面环境，方法如下：</span><span class="sxs-lookup"><span data-stu-id="9e50a-994">Deploying your Windows Virtual Desktop environment with Windows 10 Enterprise multi-session and Microsoft 365 Apps for Enterprise using the following:</span></span>
<ul>
<li><span data-ttu-id="9e50a-995">Azure Marketplace 映像。</span><span class="sxs-lookup"><span data-stu-id="9e50a-995">Azure Marketplace Image.</span></span></li>
<li><span data-ttu-id="9e50a-996">共享图像。</span><span class="sxs-lookup"><span data-stu-id="9e50a-996">Shared image.</span></span></li>
<li><span data-ttu-id="9e50a-997">Office 部署Toolkit (ODT) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-997">Office Deployment Toolkit (ODT).</span></span></li>
</ul></li>
<li><span data-ttu-id="9e50a-998">配置 FSLogix：</span><span class="sxs-lookup"><span data-stu-id="9e50a-998">Configuring FSLogix:</span></span>
<ul>
<li><span data-ttu-id="9e50a-999">使用配置文件容器部署 FSLogix 代理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-999">Deploying FSLogix Agent with Profile Container.</span></span></li>
<li><span data-ttu-id="9e50a-1000">使用 Office 容器部署 FSLogix 代理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1000">Deploying FSLogix Agent with Office Container.</span></span></li>
<li><span data-ttu-id="9e50a-1001">配置包含内容排除项的 FSLogix 文件夹。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1001">Configuring FSLogix folder with content exclusions.</span></span></li>
</ul></li>
<li><span data-ttu-id="9e50a-1002">部署 Microsoft Edge。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1002">Deploying Microsoft Edge.</span></span></li>
<li><span data-ttu-id="9e50a-1003">部署 Microsoft Teams。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1003">Deploying Microsoft Teams.</span></span></li>
<li><span data-ttu-id="9e50a-1004">使用 Windows 虚拟桌面客户端进行连接。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1004">Connecting using Windows Virtual Desktop clients.</span></span></li>
</ul><span data-ttu-id="9e50a-1005">

<strong>以下内容超出范围</strong>
</span><span class="sxs-lookup"><span data-stu-id="9e50a-1005">

<strong>The following is out of scope</strong>
</span></span><ul>
<li><span data-ttu-id="9e50a-1006">客户的 Windows 虚拟桌面部署的项目管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1006">Project management of the customer's Windows Virtual Desktop deployment.</span></span></li>
<li><span data-ttu-id="9e50a-1007">第三方应用虚拟化和部署。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1007">Third-party app virtualization and deployment.</span></span></li>
<li><span data-ttu-id="9e50a-1008">自定义图像。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1008">Custom images.</span></span></li>
<li><span data-ttu-id="9e50a-1009">涉及 VMware 和 Citrix 的迁移和方案。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1009">Migrations and scenarios involving VMware and Citrix.</span></span></li>
<li><span data-ttu-id="9e50a-1010">Linux 方案。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1010">Linux scenarios.</span></span></li>
<li><span data-ttu-id="9e50a-1011">用户配置文件的转换或迁移。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1011">Conversion or migrations of user profiles.</span></span></li>
</ul>
<span data-ttu-id="9e50a-1012">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1012">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></td>
<td><span data-ttu-id="9e50a-1013">你应该已经拥有以下内容：</span><span class="sxs-lookup"><span data-stu-id="9e50a-1013">You should already have the following:</span></span>
<ul>
<li><span data-ttu-id="9e50a-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows 虚拟桌面许可要求</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1014"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">Windows Virtual Desktop licensing requirements</a>.</span></span></li>
<li><span data-ttu-id="9e50a-1015">Azure 网络：</span><span class="sxs-lookup"><span data-stu-id="9e50a-1015">Azure networking:</span></span>
<ul>
<li><span data-ttu-id="9e50a-1016">创建和 (VNET) 虚拟网络。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1016">Virtual network (VNET) creation and subnetting.</span></span></li>
<li><span data-ttu-id="9e50a-1017">防火墙和网络安全组。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1017">Firewall and network security groups.</span></span></li>
<li><span data-ttu-id="9e50a-1018">VPN 和 ExpressRoute。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1018">VPN and ExpressRoute.</span></span></li>
<li><span data-ttu-id="9e50a-1019">从本地路由到 Azure。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1019">Routing to Azure from on-premises.</span></span></li>
<li><span data-ttu-id="9e50a-1020">允许连接到 Windows 虚拟桌面的防火墙规则。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1020">Firewall rules to allow connectivity to Windows Virtual Desktop.</span></span>
</ul>
<span data-ttu-id="9e50a-1021">有关详细信息，请参阅支持的 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> 远程桌面客户端</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1021">For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> Supported Remote Desktop clients</a>.</span></span>
</ul>
<ul><li><span data-ttu-id="9e50a-1022">Azure AD 常规设置：</span><span class="sxs-lookup"><span data-stu-id="9e50a-1022">Azure AD general setup:</span></span>
<ul>
<li><span data-ttu-id="9e50a-1023">标识 <i> 策略 (只能使用以下三个选项之一) ：</i>
</span><span class="sxs-lookup"><span data-stu-id="9e50a-1023">Identity strategy <i>(you can use only one of the following three options):</i>
</span></span><ul>
<li><span data-ttu-id="9e50a-1024">Azure 中的 Active Directory 和 Azure AD Connect。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1024">Active Directory with Azure AD Connect in Azure.</span></span></li>
<li><span data-ttu-id="9e50a-1025">通过 VPN 或 ExpressRoute 在本地使用 Azure AD Connect 的 Active Directory。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1025">Active Directory with Azure AD Connect on-premises over VPN or ExpressRoute.</span></span></li>
<li><span data-ttu-id="9e50a-1026">Active Directory 域服务 (AD DS) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1026">Active Directory Domain Services (AD DS).</span></span></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a><span data-ttu-id="9e50a-1027">应用保证</span><span class="sxs-lookup"><span data-stu-id="9e50a-1027">App Assure</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9e50a-1028"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-1028"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="9e50a-1029"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-1029"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="9e50a-1030"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-1030"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="9e50a-1031"><strong>应用保证</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-1031"><strong>App Assure</strong></span></span></td>
<td>  <span data-ttu-id="9e50a-1032">应用保证是一项旨在解决 Windows 10 和 Microsoft 365 应用应用兼容性问题的服务。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1032">App Assure is a service designed to address issues with Windows 10 and Microsoft 365 Apps app compatibility.</span></span> <span data-ttu-id="9e50a-1033">当你请求应用保证服务时，我们会与你在符合条件的订阅中一起处理有效的应用问题，无需额外付费。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1033">When you request the App Assure service, we work with you to address valid app issues at no additional cost to you with an eligible subscription.</span></span> <span data-ttu-id="9e50a-1034">我们还为在部署 Windows 虚拟桌面和 Microsoft Edge 时面临兼容性问题的客户提供指导，并尽一切合理努力来解决兼容性问题。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1034">We also provide guidance to customers who face compatibility issues when deploying Windows Virtual Desktop and Microsoft Edge and make every reasonable effort to resolve compatibility issues.</span></span> <span data-ttu-id="9e50a-1035">我们为以下 Microsoft 产品上部署的应用提供修正帮助：</span><span class="sxs-lookup"><span data-stu-id="9e50a-1035">We provide remediation assistance for apps deployed on the following Microsoft products:</span></span>
<ul>
<li>  <span data-ttu-id="9e50a-1036"><strong>Windows 10 </strong> (包括 ARM64) </span><span class="sxs-lookup"><span data-stu-id="9e50a-1036"><strong>Windows 10 </strong> (including ARM64 devices)</span></span></li>
<li> <span data-ttu-id="9e50a-1037"><strong>Microsoft 365 应用版</strong>  </span><span class="sxs-lookup"><span data-stu-id="9e50a-1037"><strong>Microsoft 365 Apps</strong>  </span></span></li>
<li>  <span data-ttu-id="9e50a-1038"><strong>Microsoft Edge -</strong> 有关部署指南，请参阅 <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Microsoft Edge 频道概述</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1038"><strong>Microsoft Edge -</strong> For deployment guidance, see <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">Overview of the Microsoft Edge channels</a>.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-1039"><strong>Windows 虚拟桌面</strong> - 有关详细信息，请参阅什么是 <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows 虚拟桌面？</a> 以及 <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 企业版多会话常见问题解答</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1039"><strong>Windows Virtual Desktop</strong> - For more information, see <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">What is Windows Virtual Desktop?</a> and <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">Windows 10 Enterprise multi-session FAQ</a>.</span></span>  </li>
</ul><span data-ttu-id="9e50a-1040">

<strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-1040">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li>  <span data-ttu-id="9e50a-1041">用于确定在 Windows 10 和 Microsoft 365 应用版上是否正常运作的应用清单和测试。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1041">App inventory and testing to determine what does and doesn't work on Windows 10 and Microsoft 365 Apps.</span></span> <span data-ttu-id="9e50a-1042">有关此过程的更多指导，请访问<a href="https://go.microsoft.com/fwlink/?linkid=2080140">桌面部署中心</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1042">For more guidance on this process, visit the <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Desktop Deployment Center</a>.</span></span> <span data-ttu-id="9e50a-1043">如果对深入升级就绪性评估感兴趣，请填写<a href="https://go.microsoft.com/fwlink/?linkid=2053818">新式桌面评估的客户请求</a>表单。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1043">If you're interested in an in-depth upgrade readiness assessment, complete the <a href="https://go.microsoft.com/fwlink/?linkid=2053818">Customer Request for Modern Desktop Assessment</a> form.</span></span></li>
<li>  <span data-ttu-id="9e50a-1044">研究 Windows 10 兼容性和支持语句的第三方 ISV 应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1044">Researching third-party ISV apps for Windows 10 compatibility and support statements.</span></span> <span data-ttu-id="9e50a-1045">有关详细信息，请参阅<a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">桌面分析</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1045">For more information, see <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">Desktop Analytics</a>.</span></span></li>
<li><span data-ttu-id="9e50a-1046">仅限应用打包的服务。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1046">App packaging-only services.</span></span> <span data-ttu-id="9e50a-1047">但是，应用保证团队会打包我们已为 Windows 10 修正的应用，以确保可以在客户环境中部署。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1047">However, the App Assure team packages apps that we have remediated for Windows 10 to ensure they can be deployed in the customer's environment.</span></span></li>
</ul><span data-ttu-id="9e50a-1048">

<strong>客户责任包括</strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-1048">

<strong>Customer responsibilities include</strong>  
</span></span><ul>
<li>  <span data-ttu-id="9e50a-1049">创建应用清单。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1049">Creating an app inventory.</span></span></li>
<li>  <span data-ttu-id="9e50a-1050">验证 Windows 10 和 Microsoft 365 应用版上的应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1050">Validating those apps on Windows 10 and Microsoft 365 Apps.</span></span></li>
</ul><span data-ttu-id="9e50a-1051">
<strong>注意：</strong>  Microsoft 无法更改源代码。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1051">
<strong>Note:</strong>  Microsoft can't make changes to your source code.</span></span> <span data-ttu-id="9e50a-1052">但是，如果可提供应用的源代码，则应用保证团队可向应用开发人员提供指导。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1052">However, the App Assure team can provide guidance to app developers if the source code is available for your apps.</span></span> 


  <span data-ttu-id="9e50a-1053">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，以寻求这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1053">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span>  </td>

</td>
<td><span data-ttu-id="9e50a-1054"><strong>Windows 10 和 Microsoft 365 应用版</strong>
</span><span class="sxs-lookup"><span data-stu-id="9e50a-1054"><strong>Windows 10 and Microsoft 365 Apps</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="9e50a-1055">在 Windows 7、Windows 8.1、Office 2010 和 Office 2013 上运行的应用也可在 Windows 10 和 Microsoft 365 应用版上运行。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1055">Apps that worked on Windows 7, Windows 8.1, Office 2010, and Office 2013 also work on Windows 10 and Microsoft 365 Apps.</span></span>  
  </li>
</ul><span data-ttu-id="9e50a-1056">
<strong>Windows 10 on ARM</strong>
</span><span class="sxs-lookup"><span data-stu-id="9e50a-1056">
<strong>Windows 10 on ARM</strong>
</span></span><ul>
<li>  
<span data-ttu-id="9e50a-1057">使用 Windows 7、Office 2010 或更高版本的应用也可在 ARM64 设备上在 Windows 10 和 Microsoft 365 应用版上运行。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1057">Apps that worked on Windows 7, Office 2010, or later versions also work on Windows 10 and Microsoft 365 Apps on ARM64 devices.</span></span> 
  </li>
</ul><span data-ttu-id="9e50a-1058">
  <strong>注意：</strong> 
</span><span class="sxs-lookup"><span data-stu-id="9e50a-1058">
  <strong>Note:</strong> 
</span></span><ul>
<li> <span data-ttu-id="9e50a-1059">x64 (64 位) 预览版，可供参与 Windows 预览体验计划 <a href="https://insider.windows.com/">的客户使用</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1059">x64 (64-bit) emulation is available in preview for customers participating in the <a href="https://insider.windows.com/">Windows Insider Program</a>.</span></span>  </li>
<li>  
 <span data-ttu-id="9e50a-1060">对于使用 Windows 10 版本 2004 (或更高版本) 的非 Windows 预览体验成员客户，ARM64 Photoshop 支持使用 OpenCL 和 <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL 兼容包</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1060">For non-Windows Insider customers on Windows 10 version 2004 (or later), ARM64 Photoshop is supported using the <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenCL and OpenGL Compatibility Pack</a>.</span></span> 
  </li>
<li>  
  <span data-ttu-id="9e50a-1061">Windows 预览体验计划的客户可以下载预览体验成员版本的 OpenCL 和 OpenGL 兼容性包，以与其他应用一同使用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1061">Customers in the Windows Insider Program can download an Insider version of the OpenCL and OpenGL Compatibility Pack for use with additional apps.</span></span>    
  </li>
</ul><span data-ttu-id="9e50a-1062">
<strong>Microsoft Edge</strong>
</span><span class="sxs-lookup"><span data-stu-id="9e50a-1062">
<strong>Microsoft Edge</strong>
</span></span><ul>
<li>  
  <span data-ttu-id="9e50a-1063">如果你的 Web 应用或网站在 Internet Explorer 11、受支持的 Google Chrome 版本或任何版本的 Microsoft Edge 上工作，它们也将与 Microsoft Edge 一起运行。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1063">If your web apps or sites work on Internet Explorer 11, supported versions of Google Chrome, or any version of Microsoft Edge, they'll also work with Microsoft Edge.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-1064">随着 Web 的不断发展，请务必查看 Microsoft Edge 的已知站点兼容性影响更改的 <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">已发布列表</a>。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1064">As the web is constantly evolving, be sure to review this published list of known <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">site compatibility-impacting changes for Microsoft Edge</a>.</span></span>  
  </li>
</ul><span data-ttu-id="9e50a-1065">
  <strong>Windows 虚拟桌面 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-1065">
  <strong>Windows Virtual Desktop </strong>  
</span></span><ul>
<li>  
  <span data-ttu-id="9e50a-1066">在 Windows Server 远程桌面会话主机 (RDSH) 上运行的虚拟化应用也可作为 Windows 虚拟桌面的一部分在 Windows 10 企业版多会话中运行。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1066">Virtualized apps that run on Windows Server Remote Desktop Session Host (RDSH) also run on Windows 10 Enterprise multi-session as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-1067">在任何 Windows 7 或 Windows 10 虚拟桌面基础结构 (VDI) 环境中运行的应用也作为 Windows 虚拟桌面的一部分在 Windows 7 企业版 和 Windows 10 企业版上运行。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1067">Apps running on any Windows 7 or Windows 10 virtual desktop infrastructure (VDI) environment also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-1068">在 Windows 7 或 Windows 10 客户端设备中运行的应用也可作为 Windows 虚拟桌面的一部分在 Windows 7 企业版和 Windows 10 企业版上运行。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1068">Apps running on Windows 7 or Windows 10 client devices also run on Windows 7 Enterprise and Windows 10 Enterprise as part of Windows Virtual Desktop.</span></span>  
  </li>
</ul><span data-ttu-id="9e50a-1069">
  <strong>注意：</strong> Windows 10 企业版多会话兼容性排除和限制包括：</span><span class="sxs-lookup"><span data-stu-id="9e50a-1069">
  <strong>Note:</strong> Windows 10 Enterprise multi-session compatibility exclusions and limitations include:</span></span>
<ul>
<li>  
  <span data-ttu-id="9e50a-1070">硬件重定向受到限制。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1070">Limited redirection of hardware.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-1071">A/V 密集型应用可能功能受限。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1071">A/V-intensive apps may perform in a diminished capacity.</span></span>  
  </li>
<li>  
  <span data-ttu-id="9e50a-1072">64 位 Windows 虚拟桌面不支持 16 位应用。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1072">16-bit apps aren't supported for 64-bit Windows Virtual Desktop.</span></span>  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a><span data-ttu-id="9e50a-1073">Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="9e50a-1073">Microsoft Edge</span></span>


<table>
<thead>
<tr class="header">
<th><span data-ttu-id="9e50a-1074"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-1074"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="9e50a-1075"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-1075"><strong>FastTrack guidance details</strong></span></span></th>
<th><span data-ttu-id="9e50a-1076"><strong>源环境预期</strong></span><span class="sxs-lookup"><span data-stu-id="9e50a-1076"><strong>Source environment expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><span data-ttu-id="9e50a-1077"><strong>Microsoft Edge</strong> </span><span class="sxs-lookup"><span data-stu-id="9e50a-1077"><strong>Microsoft Edge</strong> </span></span></td>
<td>
<span data-ttu-id="9e50a-1078">我们提供远程部署和采用指南以及兼容性帮助，用于：</span><span class="sxs-lookup"><span data-stu-id="9e50a-1078">We provide remote deployment and adoption guidance and compatibility assistance for:</span></span> <ul> <li><span data-ttu-id="9e50a-1079">使用 Microsoft Endpoint Manager 在 Windows 10 上部署 Microsoft Edge (Microsoft Endpoint Configuration Manager 或 Intune) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1079">Deploying Microsoft Edge on Windows 10 with Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager or Intune).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-1080">使用组 (或 Intune 应用配置以及应用策略配置 Microsoft Edge) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1080">Configuring Microsoft Edge (using group policies or Intune app configuration and app policies).</span></span>  </li>
<li>  <span data-ttu-id="9e50a-1081">清点可能需要在安全模式下Internet Explorer列表。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1081">Inventorying the list of sites that may require use in Internet Explorer mode.</span></span>  </li>
<li>  <span data-ttu-id="9e50a-1082">使用Internet Explorer站点列表启用模式。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1082">Enabling Internet Explorer mode with the existing Enterprise Site List.</span></span> <span data-ttu-id="9e50a-1083"> (有关详细信息，请参阅 <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">"吸引 FastTrack</a>) 。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1083">(For more information, see <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">Engaging FastTrack</a>).</span></span> <span data-ttu-id="9e50a-1084">此外，如果你有一个与 Internet Explorer 或 Google Chrome 一起工作的 Web 应用或网站，并且你遇到兼容性问题，我们会指导你解决问题，无需额外付费。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1084">Additionally, if you have a web app or site that works with Internet Explorer or Google Chrome and you experience compatibility issues, we provide guidance to resolve the issue at no additional cost.</span></span> <span data-ttu-id="9e50a-1085">若要请求应用保证的兼容性支持，请登录到 <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack 门户</a> 以启动服务活动。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1085">To request compatibility support for App Assure, sign in to the <a href="https://fasttrack.microsoft.com/portal#/signin">FastTrack portal</a> to start an engagement.</span></span>  </li>
<li> <span data-ttu-id="9e50a-1086">Microsoft 搜索书签的边缘采用和配置指南规划指南。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1086">Planning guidance for Edge adoption and configuration guidance for Microsoft Search bookmarks.</span></span></li>
</ul><span data-ttu-id="9e50a-1087">

<strong>以下内容超出范围 </strong>  
</span><span class="sxs-lookup"><span data-stu-id="9e50a-1087">

<strong>The following is out of scope </strong>  
</span></span><ul>
<li><span data-ttu-id="9e50a-1088">客户的 Microsoft Edge 部署的项目管理。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1088">Project management of the customer's Microsoft Edge deployment.</span></span></li>
<li>  <span data-ttu-id="9e50a-1089">现场支持。</span><span class="sxs-lookup"><span data-stu-id="9e50a-1089">On-site support.</span></span></li>

</td>
<td></td>
</tr>
</tbody>
</table>
