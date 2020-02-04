---
title: FastTrack 流程
description: FastTrack 中心权益载入流程概述
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 2/04/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 0d75ffe7aadf5d6b3e773846f33645214c300b26
ms.sourcegitcommit: 7365d80b2e4291e547c2d84b94da02697221abc9
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 02/03/2020
ms.locfileid: "41676572"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a><span data-ttu-id="94ba9-103">适用于企业移动性 + 安全性 (EMS) 的 FastTrack 中心权益流程</span><span class="sxs-lookup"><span data-stu-id="94ba9-103">FastTrack Center Benefit Process for Enterprise Mobility + Security (EMS)</span></span>
<span data-ttu-id="94ba9-104">如果你的组织有资格享受适用于 EMS 的 FastTrack 中心权益，则你可以与 FastTrack 专家远程合作，以使 Microsoft Azure Active Directory Premium、Microsoft Intune 和 Azure 信息保护随时可用。</span><span class="sxs-lookup"><span data-stu-id="94ba9-104">If your organization is eligible for the FastTrack Center Benefit for EMS, you can work remotely with FastTrack Specialists to get Microsoft Azure Active Directory Premium, Microsoft Intune, and Azure Information Protection ready for use.</span></span> <span data-ttu-id="94ba9-105">你还可以通过 [FastTrack 网站](https://www.microsoft.com/fasttrack/microsoft-365/ems)请求帮助，以实现 Azure 信息保护 和 Microsoft 云应用安全。</span><span class="sxs-lookup"><span data-stu-id="94ba9-105">You can also request help through the [FastTrack site](https://www.microsoft.com/fasttrack/microsoft-365/ems) for Azure Information Protection and Microsoft Cloud App Security.</span></span> <span data-ttu-id="94ba9-106">若要了解你的组织是否符合条件，请参阅[符合条件的服务和计划](M365-eligible-services-and-plans.md)。</span><span class="sxs-lookup"><span data-stu-id="94ba9-106">To learn whether your organization is eligible, see [Eligible Services and Plans](M365-eligible-services-and-plans.md).</span></span>


<span data-ttu-id="94ba9-107">下面是有关载入流程的介绍：</span><span class="sxs-lookup"><span data-stu-id="94ba9-107">Here's what we cover about the onboarding process:</span></span>

-   [<span data-ttu-id="94ba9-108">载入流程概述</span><span class="sxs-lookup"><span data-stu-id="94ba9-108">Overview of the onboarding process</span></span>](EMS-fasttrack-benefit-overview.md)

-   [<span data-ttu-id="94ba9-109">对源环境的预期</span><span class="sxs-lookup"><span data-stu-id="94ba9-109">Expectations for your source environment</span></span>](EMS-source-environment-expectations.md)

-   [<span data-ttu-id="94ba9-110">载入流程的各个阶段</span><span class="sxs-lookup"><span data-stu-id="94ba9-110">Phases of the onboarding process</span></span>](EMS-onboarding-phases.md)

-   <span data-ttu-id="94ba9-111">每个阶段的 [FastTrack 责任](EMS-fasttrack-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="94ba9-111">[FastTrack responsibilities](EMS-fasttrack-responsibilities.md) for each phase</span></span>

-   <span data-ttu-id="94ba9-112">每个阶段的[客户责任](EMS-your-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="94ba9-112">[Customer responsibilities](EMS-your-responsibilities.md) for each phase</span></span>

<span data-ttu-id="94ba9-113">载入完成后，你将看到的内容：</span><span class="sxs-lookup"><span data-stu-id="94ba9-113">Here’s what you can expect when onboarding is complete:</span></span>

-   <span data-ttu-id="94ba9-114">你的所选服务的 EMS 租户已创建。</span><span class="sxs-lookup"><span data-stu-id="94ba9-114">Your EMS tenants for your selected services are created.</span></span>

-   <span data-ttu-id="94ba9-115">许可用户可以使用以下任何一个标识选项访问 EMS 服务：</span><span class="sxs-lookup"><span data-stu-id="94ba9-115">Licensed users can access EMS Services by using one of the following identity options:</span></span>

    -   <span data-ttu-id="94ba9-116">云标识（唯一的 EMS 帐户）。</span><span class="sxs-lookup"><span data-stu-id="94ba9-116">Cloud Identities (unique EMS accounts).</span></span>

    -   <span data-ttu-id="94ba9-117">同步标识：使用 Azure Active Directory Connect 工具（密码哈希同步或直通身份验证）从本地 Active Directory 同步的 EMS 帐户。</span><span class="sxs-lookup"><span data-stu-id="94ba9-117">Synchronized Identities: EMS accounts synchronized from your on-premises Active Directory by using the Azure Active Directory Connect tool (Password Hash Sync or Pass-through Authentication).</span></span> <span data-ttu-id="94ba9-118">此选项适用于拥有单个林或多个 Active Directory 林的客户。</span><span class="sxs-lookup"><span data-stu-id="94ba9-118">This option is for customers with a single forest or multiple Active Directory forests.</span></span>

    -   <span data-ttu-id="94ba9-119">具有满足以下条件的 Microsoft EMS 帐户的联合标识：</span><span class="sxs-lookup"><span data-stu-id="94ba9-119">Federated Identities--with Microsoft EMS accounts that are:</span></span>

        -   <span data-ttu-id="94ba9-120">已从 Active Directory 与 Azure AD Connect 工具同步。</span><span class="sxs-lookup"><span data-stu-id="94ba9-120">Synchronized from Active Directory with the Azure AD Connect tool.</span></span> <span data-ttu-id="94ba9-121">此选项适用于具有单个 Active Directory 林配置的客户。</span><span class="sxs-lookup"><span data-stu-id="94ba9-121">This option is for customers with a single Active Directory forest configuration.</span></span>

        -   <span data-ttu-id="94ba9-122">与本地 Active Directory 中的 Windows Server 2012 R2 Active Directory 联合身份验证服务 (AD FS) 2.0 或更高版本联合。</span><span class="sxs-lookup"><span data-stu-id="94ba9-122">Federated with Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 or later from your on-premises Active Directory.</span></span>

        -   <span data-ttu-id="94ba9-123">通过 Azure 信息保护自动分类和保护静止和传输中的信息的能力。</span><span class="sxs-lookup"><span data-stu-id="94ba9-123">The ability to auto-classify and protect information both at rest and in transit with Azure Information Protection.</span></span> 

        -   <span data-ttu-id="94ba9-124">使用 Azure 信息保护扫描程序在本地文件共享和 SharePoint 服务器中发现信息的能力。</span><span class="sxs-lookup"><span data-stu-id="94ba9-124">The ability to discover information within on-premises file shares and SharePoint servers with the Azure Information Protection scanner.</span></span> 

        -   <span data-ttu-id="94ba9-125">在 Azure 密钥存储库中管理 Azure 信息保护租户密钥的能力。</span><span class="sxs-lookup"><span data-stu-id="94ba9-125">The ability to manage your Azure Information Protection tenant keys within the Azure Key Vault.</span></span> 
