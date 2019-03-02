---
title: 对源环境的预期
description: 对 EMS 使用 FastTrack 中心权益的源环境要求
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 03/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 6b3a5ed24ac254c3a989a584df0cbd89533ff1af
ms.sourcegitcommit: 5abb49be2bfa99110f17245839c3468318b8a3db
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/01/2019
ms.locfileid: "30359980"
---
# <a name="source-environment-expectations"></a><span data-ttu-id="bf18c-103">对源环境的预期</span><span class="sxs-lookup"><span data-stu-id="bf18c-103">Source Environment Expectations</span></span>

<span data-ttu-id="bf18c-104">使用[适用于企业移动性 + 安全性 (EMS) 的 FastTrack 中心权益](EMS-fasttrack-benefit-for-EMS.md)获取 microsoft Azure Active Directory Premium 和 microsoft Intune 准备好使用时, 您的环境需要满足以下各节中所述的期望。</span><span class="sxs-lookup"><span data-stu-id="bf18c-104">When you use the [FastTrack Center Benefit for Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) to get Microsoft Azure Active Directory Premium and Microsoft Intune ready for use, your environment needs to meet the expectations described in the following sections.</span></span>

<span data-ttu-id="bf18c-p101">您可能已在组织中具有内部部署 Active Directory, 您希望将其与企业移动性 + 安全性 (EMS) 或从单个控制台使用丰富的身份管理的任何单个服务集成在一起。企业移动性 + 安全性 (EMS) 的 FastTrack 中心权益包括帮助您将 Azure Active directory 与您现有的本地 Active directory 环境集成。</span><span class="sxs-lookup"><span data-stu-id="bf18c-p101">You may already have on-premises Active Directory in your organization that you want to integrate with Enterprise Mobility + Security (EMS) or any of its individual services that uses rich identity management from a single console. The FastTrack Center Benefit for Enterprise Mobility + Security (EMS) includes helping you integrate Azure Active Directory with your existing on-premises Active Directory environment.</span></span>

<span data-ttu-id="bf18c-107">下表显示了对现有源环境的预期。</span><span class="sxs-lookup"><span data-stu-id="bf18c-107">The following table shows expectations for your existing source environment for on-boarding.</span></span>

|<span data-ttu-id="bf18c-108">活动</span><span class="sxs-lookup"><span data-stu-id="bf18c-108">Activity</span></span>|<span data-ttu-id="bf18c-109">对源环境的预期</span><span class="sxs-lookup"><span data-stu-id="bf18c-109">Source environment expectation</span></span>|
|------------|----------------------------------|
|<span data-ttu-id="bf18c-110">内核补</span><span class="sxs-lookup"><span data-stu-id="bf18c-110">Core on-boarding</span></span>|<span data-ttu-id="bf18c-111">将功能林级别设置为 Windows Server 2008 或更高版本的 Active Directory 林, 具有以下林配置:</span><span class="sxs-lookup"><span data-stu-id="bf18c-111">Active Directory forests with the functional forest level set to Windows Server 2008 or above, with the following forest configuration:</span></span><br /><br /><span data-ttu-id="bf18c-112">-单个 Active Directory 林</span><span class="sxs-lookup"><span data-stu-id="bf18c-112">-   Single Active Directory forest</span></span><br /><span data-ttu-id="bf18c-113">-多个 Active Directory 林</span><span class="sxs-lookup"><span data-stu-id="bf18c-113">-   Multiple Active Directory forests</span></span> </br></br><span data-ttu-id="bf18c-114">**注意**: 对于所有的多林配置, Active Directory 联合身份验证服务 (AD FS) 部署超出了 FastTrack 中心权益的范围。</span><span class="sxs-lookup"><span data-stu-id="bf18c-114">**Note**: For all multiple forests configurations, Active Directory Federation Services (AD FS) deployment is out of scope for the FastTrack Center Benefit.</span></span>|
|<span data-ttu-id="bf18c-115">Azure AD Premium 补接</span><span class="sxs-lookup"><span data-stu-id="bf18c-115">Azure AD Premium on-boarding</span></span>|<span data-ttu-id="bf18c-116">已为 Azure ad premium 准备内部部署 Active Directory 及其环境, 其中包括对阻止与 azure ad 和 azure ad 高级功能集成的已确定问题的补救措施。</span><span class="sxs-lookup"><span data-stu-id="bf18c-116">The on-premises Active Directory and its environment have been prepared for Azure AD Premium, which includes remediation of identified issues that prevent integration with Azure AD and Azure AD Premium features.</span></span>|
|<span data-ttu-id="bf18c-117">Intune 入职</span><span class="sxs-lookup"><span data-stu-id="bf18c-117">Intune on-boarding</span></span>| <span data-ttu-id="bf18c-118">在计划使用 Intune 部署 WiFi 和 vpn 配置文件时, IT 管理员需要具有已在其生产环境中工作的现有证书颁发机构、WiFi 和 vpn 基础结构。</span><span class="sxs-lookup"><span data-stu-id="bf18c-118">IT admins need to have existing Certificate Authority, WiFi, and VPN infrastructures already working in their production environments when planning on deploying WiFi and VPN profiles with Intune.</span></span><br /><br /> <span data-ttu-id="bf18c-119">**注意**: 服务权益不包括设置或配置证书颁发机构、WiFi、VPN 基础结构或 Apple MDM push 证书的帮助</span><span class="sxs-lookup"><span data-stu-id="bf18c-119">**Note**: The service benefit doesn’t include assistance for setting up or configuring Certificate Authorities, WiFi, VPN infrastructures, or Apple MDM push certificates for</span></span>  |
|<span data-ttu-id="bf18c-120">Comanagement</span><span class="sxs-lookup"><span data-stu-id="bf18c-120">Comanagement</span></span>|<span data-ttu-id="bf18c-121">使用 Comanagement IT 管理员负责准备本地环境, 其中可能包括一些问题的补救措施, 这些问题会妨碍您同时使用 Configuration Manager 和 Intune 管理 Windows 10 设备。</span><span class="sxs-lookup"><span data-stu-id="bf18c-121">With Comanagement IT admins are responsible for preparing the on-premises environment, which might include remediation of issues that prevent you from concurrently manage Windows 10 devices using both Configuration Manager and Intune.</span></span><br /><br /><span data-ttu-id="bf18c-122">**注意**: FastTrack 服务权益不包括将 configuration manager 站点服务器和/或 configuration manager 客户端设置或升级到支持 Windows 10 设备的 Comanagement 所需的最低要求的帮助。</span><span class="sxs-lookup"><span data-stu-id="bf18c-122">**Note**: The FastTrack service benefit doesn't include assistance for setting up or upgrading Configuration Manager site server and/or Configuration Manager client to the minimum requirements needed to support Comanagement with Windows 10 devices.</span></span> |
|<span data-ttu-id="bf18c-123">与 Windows defender 高级威胁防护集成的 Intune (windows defender ATP)</span><span class="sxs-lookup"><span data-stu-id="bf18c-123">Intune integrated with Windows Defender Advanced Threat Protection (Windows Defender ATP)</span></span>|<span data-ttu-id="bf18c-124">您的 Windows Defender ATP 订阅已根据贵公司的安全要求而激活和配置。</span><span class="sxs-lookup"><span data-stu-id="bf18c-124">Your Windows Defender ATP subscription has been activated and configured based on your company security requirements.</span></span><br /><br /><span data-ttu-id="bf18c-p102">**注意**: FastTrack 服务优势提供了有关将 Intune 与 windows Defender ATP 集成在一起的帮助, 以及如何基于其 Windows 10 风险级别评估创建设备合规性策略。FastTrack 服务优势不提供有关购买、许可、激活或使用 Windows Defender ATP 及其安全中心控制台的帮助。</span><span class="sxs-lookup"><span data-stu-id="bf18c-p102">**Note**: The FastTrack service benefit provides assistance on integrating Intune with Windows Defender ATP, and creating device compliance policies based on its Windows 10 risk level assessment. The FastTrack service benefit does not provide assistance on purchasing, licensing, activating, or using Windows Defender ATP and its Security Center console.</span></span> |
|<span data-ttu-id="bf18c-127">Windows Autopilot</span><span class="sxs-lookup"><span data-stu-id="bf18c-127">Windows Autopilot</span></span>|<span data-ttu-id="bf18c-128">IT 管理员负责将其设备注册到其组织, 方法是让硬件供应商代表自己上载其硬件 id, 或将自己上载到 Windows Autopilot 服务中。</span><span class="sxs-lookup"><span data-stu-id="bf18c-128">IT admins are responsible for registering their devices to their organization by either having the hardware vendor upload their hardware IDs on their behalf or by uploading it themselves into the Windows Autopilot service.</span></span> |
|<span data-ttu-id="bf18c-129">使用 Intune 安全地部署 Outlook for iOS 和 Android</span><span class="sxs-lookup"><span data-stu-id="bf18c-129">Deploy Outlook for iOS and Android securely with Intune</span></span>|<br /><br /><span data-ttu-id="bf18c-130">-在 Azure AD for Office 365 中启用的用户标识。</span><span class="sxs-lookup"><span data-stu-id="bf18c-130">-   User identities enabled in Azure AD for Office 365.</span></span><br /><span data-ttu-id="bf18c-131">-使用分配了用户许可证的 Exchange Online 或混合 Exchange 配置。</span><span class="sxs-lookup"><span data-stu-id="bf18c-131">-   Exchange Online or Hybrid Exchange configured with user licenses assigned.</span></span><br />|

> [!NOTE]
> <span data-ttu-id="bf18c-132">**想要了解更多信息？**
> [企业移动性 + 安全性](https://www.microsoft.com/cloud-platform/enterprise-mobility)</span><span class="sxs-lookup"><span data-stu-id="bf18c-132">**Want to learn more?**
[Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)</span></span>

## <a name="next-steps"></a><span data-ttu-id="bf18c-133">后续步骤</span><span class="sxs-lookup"><span data-stu-id="bf18c-133">Next steps</span></span>

[<span data-ttu-id="bf18c-134">EMS 载入阶段的 FastTrack 中心权益</span><span class="sxs-lookup"><span data-stu-id="bf18c-134">FastTrack Center Benefit for EMS onboarding phases</span></span>](EMS-onboarding-phases.md)
