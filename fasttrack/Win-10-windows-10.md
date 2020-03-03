---
title: Windows 10
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 3/03/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack 提供 Windows 10 部署指南，以帮助你从 Windows 7 专业版和 Windows 8.1 专业版升级到 Windows 10 企业版。
ms.openlocfilehash: 8d959c773009f144b258d18629c18a94d5c180fb
ms.sourcegitcommit: 79a5b31863be3d554223f75ca866dcf40dd2c2dd
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/02/2020
ms.locfileid: "42347512"
---
# <a name="windows-10"></a><span data-ttu-id="0739c-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="0739c-103">Windows 10</span></span>

<span data-ttu-id="0739c-104">FastTrack 提供 Windows 10 部署指南，以帮助你从 Windows 7 专业版和 Windows 8.1 专业版升级到 Windows 10 企业版。</span><span class="sxs-lookup"><span data-stu-id="0739c-104">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="0739c-105">你可与 FastTrack 专家协作：</span><span class="sxs-lookup"><span data-stu-id="0739c-105">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="0739c-106">使用 Microsoft Endpoint Configuration Manager 或 Microsoft 365 部署 Windows 10 企业版。</span><span class="sxs-lookup"><span data-stu-id="0739c-106">Deploy Windows 10 Enterprise using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="0739c-107">部署 Office 365 专业增强版。</span><span class="sxs-lookup"><span data-stu-id="0739c-107">Deploy Office 365 ProPlus.</span></span> 
- <span data-ttu-id="0739c-108">使用 Microsoft Endpoint Configuration Manager 或 Microsoft 365 更新 Windows 10 企业版和 Office 365 专业增强版。</span><span class="sxs-lookup"><span data-stu-id="0739c-108">Update Windows 10 Enterprise and Office 365 ProPlus using Microsoft Endpoint Configuration Manager or Microsoft 365.</span></span>
- <span data-ttu-id="0739c-109">将 Configuration Manager 云附加与 Microsoft Intune，或将 Intune 部署为唯一的云管理解决方案。</span><span class="sxs-lookup"><span data-stu-id="0739c-109">Cloud-attach Configuration Manager with Microsoft Intune or deploy Intune as the sole cloud management solution.</span></span>
  
> [!NOTE]
> <span data-ttu-id="0739c-110">FastTrack 为客户提供了建议的方法、指南以及经过工程设计旨在交付快速和可预测结果的最佳做法。</span><span class="sxs-lookup"><span data-stu-id="0739c-110">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="0739c-111">如果选择不依据本指南进行部署，那么你的体验可能会受到影响。</span><span class="sxs-lookup"><span data-stu-id="0739c-111">If you choose to deploy outside of this guidance, your experience may be impacted.</span></span> <span data-ttu-id="0739c-112">指导定义为口头和书面协助的组合。</span><span class="sxs-lookup"><span data-stu-id="0739c-112">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="0739c-113">在 FastTrack 专家提供指导时，FastTrack 人员不得以客户名义执行操作。</span><span class="sxs-lookup"><span data-stu-id="0739c-113">When FastTrack Specialists provide guidance, FastTrack personnel can’t act on your behalf.</span></span> <span data-ttu-id="0739c-114">只要您的订阅是最新的，就可以使用 FastTrack 服务来实施满足符合条件的计划。</span><span class="sxs-lookup"><span data-stu-id="0739c-114">You can use FastTrack services for qualifying plans as long as your subscription is current.</span></span>  
    
<span data-ttu-id="0739c-115">下表列出了流程中的角色和职责。</span><span class="sxs-lookup"><span data-stu-id="0739c-115">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="0739c-116">**角色**</span><span class="sxs-lookup"><span data-stu-id="0739c-116">**Role**</span></span> <br/> |<span data-ttu-id="0739c-117">**职责**</span><span class="sxs-lookup"><span data-stu-id="0739c-117">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="0739c-118">**FastTrack 专家**</span><span class="sxs-lookup"><span data-stu-id="0739c-118">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="0739c-119">远程提供所有部署和更新服务。</span><span class="sxs-lookup"><span data-stu-id="0739c-119">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="0739c-120">通过综合使用工具和发布的文档远程协助你。</span><span class="sxs-lookup"><span data-stu-id="0739c-120">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="0739c-121">直接协助你或你的代表。</span><span class="sxs-lookup"><span data-stu-id="0739c-121">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="0739c-122">**FastTrack 中心**</span><span class="sxs-lookup"><span data-stu-id="0739c-122">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="0739c-123">提供用于规划和部署 Windows 10 企业版的指南。</span><span class="sxs-lookup"><span data-stu-id="0739c-123">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="0739c-124">在正常工作时间对特定区域提供协助。</span><span class="sxs-lookup"><span data-stu-id="0739c-124">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="0739c-125">使用繁体中文、简体中文（仅限讲普通话的资源）、英语、法语、德语、意大利语、日语、韩语、葡萄牙语（巴西）、西班牙语、泰语和越南语提供协助。</span><span class="sxs-lookup"><span data-stu-id="0739c-125">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 
<span data-ttu-id="0739c-126">可以通过 [Microsoft 365 管理中心](https://go.microsoft.com/fwlink/?linkid=2032704)或 [FastTrack 站点](https://go.microsoft.com/fwlink/?linkid=780698)获得帮助。</span><span class="sxs-lookup"><span data-stu-id="0739c-126">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> <span data-ttu-id="0739c-127">要进行登录，必须在活动租户上具备有效的工作或学校帐户（组织 ID 或 Azure Active Directory ID）。</span><span class="sxs-lookup"><span data-stu-id="0739c-127">To sign in, you must have an active work or school account (organizational ID or Azure Active Directory ID) on an active tenant.</span></span> 

<span data-ttu-id="0739c-128">通过 [FastTrack 站点](https://go.microsoft.com/fwlink/?linkid=780698)获取帮助：</span><span class="sxs-lookup"><span data-stu-id="0739c-128">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.  <span data-ttu-id="0739c-129">登录到 [FastTrack 站点](https://go.microsoft.com/fwlink/?linkid=780698)。</span><span class="sxs-lookup"><span data-stu-id="0739c-129">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.  <span data-ttu-id="0739c-130">从登录页面顶部的“**快速操作**”中选择“**Microsoft 365 的请求帮助**”，或者在部署卡上选择“**Microsoft 365 的请求帮助**”。</span><span class="sxs-lookup"><span data-stu-id="0739c-130">Select **Request assistance for Microsoft 365** from the **quick actions** on the top of your landing page or by selecting **Request assistance for Microsoft 365** on the deploy card.</span></span>
3.  <span data-ttu-id="0739c-131">完成“**Microsoft 365 的请求帮助**”表单。</span><span class="sxs-lookup"><span data-stu-id="0739c-131">Complete the **Request Assistance for Microsoft 365** form.</span></span>
  
<span data-ttu-id="0739c-p104">合作伙伴也可以客户身份通过 [FastTrack 网站](https://go.microsoft.com/fwlink/?linkid=780698)获取帮助。若要执行此操作：</span><span class="sxs-lookup"><span data-stu-id="0739c-p104">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer. To do so:</span></span>
1.  <span data-ttu-id="0739c-134">登录到 [FastTrack 站点](https://go.microsoft.com/fwlink/?linkid=780698)。</span><span class="sxs-lookup"><span data-stu-id="0739c-134">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.  <span data-ttu-id="0739c-135">选择“我的客户”\*\*\*\*。</span><span class="sxs-lookup"><span data-stu-id="0739c-135">Select **My Customers**.</span></span>
3.  <span data-ttu-id="0739c-136">搜索你的客户或从你的客户列表中选择。</span><span class="sxs-lookup"><span data-stu-id="0739c-136">Search for your customer or select them from your customer list.</span></span>
4.  <span data-ttu-id="0739c-137">选择“服务”\*\*\*\*。</span><span class="sxs-lookup"><span data-stu-id="0739c-137">Select **Services**.</span></span>
5.  <span data-ttu-id="0739c-138">选择“**Microsoft 365 的请求帮助**”表单。</span><span class="sxs-lookup"><span data-stu-id="0739c-138">Select the **Request Assistance for Microsoft 365** form.</span></span>
6.  <span data-ttu-id="0739c-139">选择 Windows 10 产品选项并填写表单。</span><span class="sxs-lookup"><span data-stu-id="0739c-139">Select the Windows 10 product option and complete the form.</span></span>
 