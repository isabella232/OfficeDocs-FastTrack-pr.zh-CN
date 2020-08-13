---
title: Windows 10
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack 提供 Windows 10 部署指南，以帮助你从 Windows 7 专业版和 Windows 8.1 专业版升级到 Windows 10 企业版。
ms.openlocfilehash: da069420434a8087c661f77400edd9239f56c366
ms.sourcegitcommit: 7da7b0966b08486a0ede148240af958408a271f7
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/11/2020
ms.locfileid: "46634166"
---
# <a name="windows-10"></a><span data-ttu-id="8b4a2-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="8b4a2-103">Windows 10</span></span>

<span data-ttu-id="8b4a2-104">FastTrack 提供 Windows 10 部署指南，以帮助你从 Windows 7 专业版和 Windows 8.1 专业版升级到 Windows 10 企业版。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-104">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="8b4a2-105">你可与 FastTrack 专家协作：</span><span class="sxs-lookup"><span data-stu-id="8b4a2-105">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="8b4a2-106">使用 Microsoft Endpoint Configuration Manager 或 Microsoft 365 部署 Windows 10 企业版。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-106">Deploy Windows 10 Enterprise using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="8b4a2-107">部署 Microsoft 365 应用版。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-107">Deploy Microsoft 365 Apps.</span></span> 
- <span data-ttu-id="8b4a2-108">使用 Microsoft Endpoint Configuration Manager 或 Microsoft 365 更新 Windows 10 企业版和 Microsoft 365 应用版。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-108">Update Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="8b4a2-109">将 Configuration Manager 云附加与 Microsoft Intune，或将 Intune 部署为唯一的云管理解决方案。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-109">Cloud-attach Configuration Manager with Microsoft Intune or deploy Intune as the sole cloud management solution.</span></span>
  
> [!NOTE]
> <span data-ttu-id="8b4a2-110">FastTrack 为客户提供了建议的方法、指南以及经过工程设计旨在交付快速和可预测结果的最佳做法。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-110">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="8b4a2-111">如果选择不依据本指南进行部署，那么你的体验可能会受到影响。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-111">If you choose to deploy outside of this guidance, your experience may be impacted.</span></span> <span data-ttu-id="8b4a2-112">指导定义为口头和书面协助的组合。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-112">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="8b4a2-113">在 FastTrack 专家提供指导时，FastTrack 人员不得以客户名义执行操作。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-113">When FastTrack Specialists provide guidance, FastTrack personnel can't act on your behalf.</span></span> <span data-ttu-id="8b4a2-114">只要您的订阅是最新的，就可以使用 FastTrack 服务来实施满足符合条件的计划。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-114">You can use FastTrack services for qualifying plans as long as your subscription is current.</span></span>  
    
<span data-ttu-id="8b4a2-115">下表列出了流程中的角色和职责。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-115">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="8b4a2-116">**角色**</span><span class="sxs-lookup"><span data-stu-id="8b4a2-116">**Role**</span></span> <br/> |<span data-ttu-id="8b4a2-117">**职责**</span><span class="sxs-lookup"><span data-stu-id="8b4a2-117">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="8b4a2-118">**FastTrack 专家**</span><span class="sxs-lookup"><span data-stu-id="8b4a2-118">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="8b4a2-119">远程提供所有部署和更新服务。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-119">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="8b4a2-120">通过综合使用工具和发布的文档远程协助你。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-120">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="8b4a2-121">直接协助你或你的代表。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-121">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="8b4a2-122">**FastTrack 中心**</span><span class="sxs-lookup"><span data-stu-id="8b4a2-122">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="8b4a2-123">提供用于规划和部署 Windows 10 企业版的指南。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-123">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="8b4a2-124">在正常工作时间对特定区域提供协助。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-124">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="8b4a2-125">使用繁体中文、简体中文（仅限讲普通话的资源）、英语、法语、德语、意大利语、日语、韩语、葡萄牙语（巴西）、西班牙语、泰语和越南语提供协助。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-125">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 
<span data-ttu-id="8b4a2-126">可以通过 [Microsoft 365 管理中心](https://go.microsoft.com/fwlink/?linkid=2032704)或 [FastTrack 站点](https://go.microsoft.com/fwlink/?linkid=780698)获得帮助。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-126">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> <span data-ttu-id="8b4a2-127">要进行登录，必须在活动租户上具备有效的工作或学校帐户（组织 ID 或 Azure Active Directory ID）。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-127">To sign in, you must have an active work or school account (organizational ID or Azure Active Directory ID) on an active tenant.</span></span> 

<span data-ttu-id="8b4a2-128">通过 [FastTrack 站点](https://go.microsoft.com/fwlink/?linkid=780698)获取帮助：</span><span class="sxs-lookup"><span data-stu-id="8b4a2-128">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.    <span data-ttu-id="8b4a2-129">登录到 [FastTrack 站点](https://go.microsoft.com/fwlink/?linkid=780698)。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-129">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="8b4a2-130">在登录页面顶部的**快速操作**中选择**请求Microsoft 365 的协助**。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-130">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="8b4a2-131">完成**请求Microsoft 365 的协助** 表单。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-131">Complete the **Request Assistance with Microsoft 365** form.</span></span>
  
<span data-ttu-id="8b4a2-p104">合作伙伴也可以客户身份通过 [FastTrack 网站](https://go.microsoft.com/fwlink/?linkid=780698)获取帮助。若要执行此操作：</span><span class="sxs-lookup"><span data-stu-id="8b4a2-p104">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer. To do so:</span></span>
1.    <span data-ttu-id="8b4a2-134">登录到 [FastTrack 站点](https://go.microsoft.com/fwlink/?linkid=780698)。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-134">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="8b4a2-135">在登录页面顶部的**快速操作**中选择**请求Microsoft 365 的协助**。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-135">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="8b4a2-136">通过输入客户名称、域名或TPID搜索客户。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-136">Search for your customer by entering the customer name, domain, or TPID.</span></span>
4.    <span data-ttu-id="8b4a2-137">在搜索结果中选择客户。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-137">Select customer from the search results.</span></span>
5.    <span data-ttu-id="8b4a2-138">完成**请求Microsoft 365 的协助** 表单。</span><span class="sxs-lookup"><span data-stu-id="8b4a2-138">Complete the **Request Assistance with Microsoft 365** form.</span></span>
 
