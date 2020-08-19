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
ms.openlocfilehash: e91c5a1c52125387a0d341a01e74be0a14738d29
ms.sourcegitcommit: 1b2242be54dd0d000c6384f45f18e1951c31998b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/18/2020
ms.locfileid: "46800604"
---
# <a name="windows-10"></a><span data-ttu-id="3226c-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="3226c-103">Windows 10</span></span>

> [!CAUTION]
> <span data-ttu-id="3226c-104">此内容已不再是最新的，并计划删除。</span><span class="sxs-lookup"><span data-stu-id="3226c-104">This content is no longer current and is scheduled for removal.</span></span> <span data-ttu-id="3226c-105">对当前内容使用左侧导航栏中的目录。</span><span class="sxs-lookup"><span data-stu-id="3226c-105">Use the table of contents in the left-hand navigation for current content.</span></span>

<span data-ttu-id="3226c-106">FastTrack 提供 Windows 10 部署指南，以帮助你从 Windows 7 专业版和 Windows 8.1 专业版升级到 Windows 10 企业版。</span><span class="sxs-lookup"><span data-stu-id="3226c-106">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="3226c-107">你可与 FastTrack 专家协作：</span><span class="sxs-lookup"><span data-stu-id="3226c-107">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="3226c-108">使用 Microsoft Endpoint Configuration Manager 或 Microsoft 365 部署 Windows 10 企业版。</span><span class="sxs-lookup"><span data-stu-id="3226c-108">Deploy Windows 10 Enterprise using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="3226c-109">部署 Microsoft 365 应用版。</span><span class="sxs-lookup"><span data-stu-id="3226c-109">Deploy Microsoft 365 Apps.</span></span> 
- <span data-ttu-id="3226c-110">使用 Microsoft Endpoint Configuration Manager 或 Microsoft 365 更新 Windows 10 企业版和 Microsoft 365 应用版。</span><span class="sxs-lookup"><span data-stu-id="3226c-110">Update Windows 10 Enterprise and Microsoft 365 Apps using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="3226c-111">将 Configuration Manager 云附加与 Microsoft Intune，或将 Intune 部署为唯一的云管理解决方案。</span><span class="sxs-lookup"><span data-stu-id="3226c-111">Cloud-attach Configuration Manager with Microsoft Intune or deploy Intune as the sole cloud management solution.</span></span>
  
> [!NOTE]
> <span data-ttu-id="3226c-112">FastTrack 为客户提供了建议的方法、指南以及经过工程设计旨在交付快速和可预测结果的最佳做法。</span><span class="sxs-lookup"><span data-stu-id="3226c-112">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="3226c-113">如果选择不依据本指南进行部署，那么你的体验可能会受到影响。</span><span class="sxs-lookup"><span data-stu-id="3226c-113">If you choose to deploy outside of this guidance, your experience may be impacted.</span></span> <span data-ttu-id="3226c-114">指导定义为口头和书面协助的组合。</span><span class="sxs-lookup"><span data-stu-id="3226c-114">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="3226c-115">在 FastTrack 专家提供指导时，FastTrack 人员不得以客户名义执行操作。</span><span class="sxs-lookup"><span data-stu-id="3226c-115">When FastTrack Specialists provide guidance, FastTrack personnel can't act on your behalf.</span></span> <span data-ttu-id="3226c-116">只要您的订阅是最新的，就可以使用 FastTrack 服务来实施满足符合条件的计划。</span><span class="sxs-lookup"><span data-stu-id="3226c-116">You can use FastTrack services for qualifying plans as long as your subscription is current.</span></span>  
    
<span data-ttu-id="3226c-117">下表列出了流程中的角色和职责。</span><span class="sxs-lookup"><span data-stu-id="3226c-117">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="3226c-118">**角色**</span><span class="sxs-lookup"><span data-stu-id="3226c-118">**Role**</span></span> <br/> |<span data-ttu-id="3226c-119">**职责**</span><span class="sxs-lookup"><span data-stu-id="3226c-119">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="3226c-120">**FastTrack 专家**</span><span class="sxs-lookup"><span data-stu-id="3226c-120">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="3226c-121">远程提供所有部署和更新服务。</span><span class="sxs-lookup"><span data-stu-id="3226c-121">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="3226c-122">通过综合使用工具和发布的文档远程协助你。</span><span class="sxs-lookup"><span data-stu-id="3226c-122">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="3226c-123">直接协助你或你的代表。</span><span class="sxs-lookup"><span data-stu-id="3226c-123">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="3226c-124">**FastTrack 中心**</span><span class="sxs-lookup"><span data-stu-id="3226c-124">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="3226c-125">提供用于规划和部署 Windows 10 企业版的指南。</span><span class="sxs-lookup"><span data-stu-id="3226c-125">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="3226c-126">在正常工作时间对特定区域提供协助。</span><span class="sxs-lookup"><span data-stu-id="3226c-126">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="3226c-127">使用繁体中文、简体中文（仅限讲普通话的资源）、英语、法语、德语、意大利语、日语、韩语、葡萄牙语（巴西）、西班牙语、泰语和越南语提供协助。</span><span class="sxs-lookup"><span data-stu-id="3226c-127">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 
<span data-ttu-id="3226c-128">可以通过 [Microsoft 365 管理中心](https://go.microsoft.com/fwlink/?linkid=2032704)或 [FastTrack 站点](https://go.microsoft.com/fwlink/?linkid=780698)获得帮助。</span><span class="sxs-lookup"><span data-stu-id="3226c-128">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> <span data-ttu-id="3226c-129">要进行登录，必须在活动租户上具备有效的工作或学校帐户（组织 ID 或 Azure Active Directory ID）。</span><span class="sxs-lookup"><span data-stu-id="3226c-129">To sign in, you must have an active work or school account (organizational ID or Azure Active Directory ID) on an active tenant.</span></span> 

<span data-ttu-id="3226c-130">通过 [FastTrack 站点](https://go.microsoft.com/fwlink/?linkid=780698)获取帮助：</span><span class="sxs-lookup"><span data-stu-id="3226c-130">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.    <span data-ttu-id="3226c-131">登录到 [FastTrack 站点](https://go.microsoft.com/fwlink/?linkid=780698)。</span><span class="sxs-lookup"><span data-stu-id="3226c-131">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="3226c-132">在登录页面顶部的**快速操作**中选择**请求Microsoft 365 的协助**。</span><span class="sxs-lookup"><span data-stu-id="3226c-132">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="3226c-133">完成**请求Microsoft 365 的协助** 表单。</span><span class="sxs-lookup"><span data-stu-id="3226c-133">Complete the **Request Assistance with Microsoft 365** form.</span></span>
  
<span data-ttu-id="3226c-p105">合作伙伴也可以客户身份通过 [FastTrack 网站](https://go.microsoft.com/fwlink/?linkid=780698)获取帮助。若要执行此操作：</span><span class="sxs-lookup"><span data-stu-id="3226c-p105">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer. To do so:</span></span>
1.    <span data-ttu-id="3226c-136">登录到 [FastTrack 站点](https://go.microsoft.com/fwlink/?linkid=780698)。</span><span class="sxs-lookup"><span data-stu-id="3226c-136">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="3226c-137">在登录页面顶部的**快速操作**中选择**请求Microsoft 365 的协助**。</span><span class="sxs-lookup"><span data-stu-id="3226c-137">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="3226c-138">通过输入客户名称、域名或TPID搜索客户。</span><span class="sxs-lookup"><span data-stu-id="3226c-138">Search for your customer by entering the customer name, domain, or TPID.</span></span>
4.    <span data-ttu-id="3226c-139">在搜索结果中选择客户。</span><span class="sxs-lookup"><span data-stu-id="3226c-139">Select customer from the search results.</span></span>
5.    <span data-ttu-id="3226c-140">完成**请求Microsoft 365 的协助** 表单。</span><span class="sxs-lookup"><span data-stu-id="3226c-140">Complete the **Request Assistance with Microsoft 365** form.</span></span>
 
