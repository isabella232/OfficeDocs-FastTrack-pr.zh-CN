---
title: FastTrack 过程
description: FastTrack 中心福利载入过程概述
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 04/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a2d3f601c1395b908d2ad8fd7a6a0dde38502784
ms.sourcegitcommit: 8d1fbbfc6b05522ea1259149349548f072fefcac
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/01/2019
ms.locfileid: "31016776"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a><span data-ttu-id="4e201-103">适用于企业移动性 + 安全性 (EMS) 的 FastTrack 中心权益流程</span><span class="sxs-lookup"><span data-stu-id="4e201-103">FastTrack Center Benefit Process for Enterprise Mobility + Security (EMS)</span></span>
<span data-ttu-id="4e201-104">如果您的组织有资格获得 EMS 的 FastTrack 中心权益, 您可以与 FastTrack 专家远程合作, 以获取 microsoft Azure Active Directory Premium 和 microsoft Intune 准备好使用。</span><span class="sxs-lookup"><span data-stu-id="4e201-104">If your organization is eligible for the FastTrack Center Benefit for EMS, you can work remotely with FastTrack Specialists to get Microsoft Azure Active Directory Premium and Microsoft Intune ready for use.</span></span> <span data-ttu-id="4e201-105">您还可以通过[FastTrack 网站](https://www.microsoft.com/fasttrack/microsoft-365/ems)请求获取 Azure 信息保护、microsoft 云应用安全和 microsoft 高级威胁分析的帮助。</span><span class="sxs-lookup"><span data-stu-id="4e201-105">You can also request help through the [FastTrack site](https://www.microsoft.com/fasttrack/microsoft-365/ems) for Azure Information Protection, Microsoft Cloud App Security and Microsoft Advanced Threat Analytics.</span></span> <span data-ttu-id="4e201-106">若要了解您的组织是否符合条件, 请参阅[符合条件的服务和计划](M365-eligible-services-and-plans.md)。</span><span class="sxs-lookup"><span data-stu-id="4e201-106">To learn whether your organization is eligible, see [Eligible Services and Plans](M365-eligible-services-and-plans.md).</span></span>


<span data-ttu-id="4e201-107">以下是关于载入过程的讨论:</span><span class="sxs-lookup"><span data-stu-id="4e201-107">Here's what we cover about the onboarding process:</span></span>

-   [<span data-ttu-id="4e201-108">加入过程概述</span><span class="sxs-lookup"><span data-stu-id="4e201-108">Overview of the onboarding process</span></span>](EMS-fasttrack-benefit-overview.md)

-   [<span data-ttu-id="4e201-109">对源环境的预期</span><span class="sxs-lookup"><span data-stu-id="4e201-109">Expectations for your source environment</span></span>](EMS-source-environment-expectations.md)

-   [<span data-ttu-id="4e201-110">载入过程的各个阶段</span><span class="sxs-lookup"><span data-stu-id="4e201-110">Phases of the onboarding process</span></span>](EMS-onboarding-phases.md)

-   <span data-ttu-id="4e201-111">每个阶段的[FastTrack 责任](EMS-fasttrack-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="4e201-111">[FastTrack responsibilities](EMS-fasttrack-responsibilities.md) for each phase</span></span>

-   <span data-ttu-id="4e201-112">每个阶段的[客户责任](EMS-your-responsibilities.md)</span><span class="sxs-lookup"><span data-stu-id="4e201-112">[Customer responsibilities](EMS-your-responsibilities.md) for each phase</span></span>

<span data-ttu-id="4e201-113">以下是完成载入时可以预料到的事项:</span><span class="sxs-lookup"><span data-stu-id="4e201-113">Here’s what you can expect when onboarding is complete:</span></span>

-   <span data-ttu-id="4e201-114">将创建所选服务的 EMS 租户。</span><span class="sxs-lookup"><span data-stu-id="4e201-114">Your EMS tenants for your selected services are created.</span></span>

-   <span data-ttu-id="4e201-115">许可用户可以使用以下标识选项之一访问 EMS 服务:</span><span class="sxs-lookup"><span data-stu-id="4e201-115">Licensed users can access EMS Services by using one of the following identity options:</span></span>

    -   <span data-ttu-id="4e201-116">云标识 (唯一 EMS 帐户)。</span><span class="sxs-lookup"><span data-stu-id="4e201-116">Cloud Identities (unique EMS accounts).</span></span>

    -   <span data-ttu-id="4e201-117">同步标识: 使用 Azure active directory Connect 工具 (密码哈希同步或传递身份验证) 从本地 Active directory 同步的 EMS 帐户。</span><span class="sxs-lookup"><span data-stu-id="4e201-117">Synchronized Identities: EMS accounts synchronized from your on-premises Active Directory by using the Azure Active Directory Connect tool (Password Hash Sync or Pass-through Authentication).</span></span> <span data-ttu-id="4e201-118">此选项适用于具有单个林或多个 Active Directory 林的客户。</span><span class="sxs-lookup"><span data-stu-id="4e201-118">This option is for customers with a single forest or multiple Active Directory forests.</span></span>

    -   <span data-ttu-id="4e201-119">联合身份--包含的 Microsoft EMS 帐户为:</span><span class="sxs-lookup"><span data-stu-id="4e201-119">Federated Identities--with Microsoft EMS accounts that are:</span></span>

        -   <span data-ttu-id="4e201-120">从 Active Directory 与 Azure AD Connect 工具同步。</span><span class="sxs-lookup"><span data-stu-id="4e201-120">Synchronized from Active Directory with the Azure AD Connect tool.</span></span> <span data-ttu-id="4e201-121">此选项适用于具有单个 Active Directory 林配置的客户。</span><span class="sxs-lookup"><span data-stu-id="4e201-121">This option is for customers with a single Active Directory forest configuration.</span></span>

        -   <span data-ttu-id="4e201-122">从本地 Active directory 与 Windows Server 2012 R2 active directory 联合身份验证服务 (AD FS) 2.0 或更高版本联合。</span><span class="sxs-lookup"><span data-stu-id="4e201-122">Federated with Windows Server 2012 R2 Active Directory Federation Services (AD FS) 2.0 or later from your on-premises Active Directory.</span></span>
