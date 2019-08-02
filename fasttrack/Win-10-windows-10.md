---
title: Windows 10
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 08/02/2019
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack 提供 Windows 10 部署指南，以帮助你从 Windows 7 专业版和 Windows 8.1 专业版升级到 Windows 10 企业版。
ms.openlocfilehash: 50a33d07593eef18a4d0dff8efb6adef0ca10250
ms.sourcegitcommit: 911b0d32a26eb068a2a94ebc48d9f8f2fc70e5a9
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/01/2019
ms.locfileid: "36054071"
---
# <a name="windows-10"></a><span data-ttu-id="f00db-103">Windows 10</span><span class="sxs-lookup"><span data-stu-id="f00db-103">Windows 10</span></span>

<span data-ttu-id="f00db-104">FastTrack 提供 Windows 10 部署指南，以帮助你从 Windows 7 专业版和 Windows 8.1 专业版升级到 Windows 10 企业版。</span><span class="sxs-lookup"><span data-stu-id="f00db-104">FastTrack provides Windows 10 deployment guidance to help you for upgrade from Windows 7 Professional and Windows 8.1 Professional to Windows 10 Enterprise.</span></span> <span data-ttu-id="f00db-105">你可与 FastTrack 专家协作：</span><span class="sxs-lookup"><span data-stu-id="f00db-105">You work with FastTrack Specialists to:</span></span>

- <span data-ttu-id="f00db-106">部署 Windows 10 企业版。</span><span class="sxs-lookup"><span data-stu-id="f00db-106">Windows 10 Enterprise</span></span>
- <span data-ttu-id="f00db-107">部署 Office 365 专业增强版。</span><span class="sxs-lookup"><span data-stu-id="f00db-107">Deploy Office 365 ProPlus</span></span> 
- <span data-ttu-id="f00db-108">使用 Microsoft System Center Configuration Manager 或 Microsoft 365 更新 Windows 10 企业版和 Office 365 专业增强版。</span><span class="sxs-lookup"><span data-stu-id="f00db-108">Update Windows 10 Enterprise and Office 365 ProPlus using Microsoft System Center Configuration Manager or Microsoft 365.</span></span>
  
> [!NOTE]
> <span data-ttu-id="f00db-109">FastTrack 为客户提供了建议的方法、指南以及经过工程设计旨在交付快速和可预测结果的最佳做法。</span><span class="sxs-lookup"><span data-stu-id="f00db-109">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="f00db-110">如果选择不依据本指南进行部署，那么你的体验可能会受到影响。</span><span class="sxs-lookup"><span data-stu-id="f00db-110">If you choose to deploy outside of this guidance, your onboarding experience and usage of the service may be impacted.</span></span> <span data-ttu-id="f00db-111">指导定义为口头和书面协助的组合。</span><span class="sxs-lookup"><span data-stu-id="f00db-111">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="f00db-112">在 FastTrack 专家提供指导时，FastTrack 人员不得以客户名义执行操作。</span><span class="sxs-lookup"><span data-stu-id="f00db-112">When FastTrack Specialists provide guidance, FastTrack personnel cannot act on your behalf.</span></span> <span data-ttu-id="f00db-113">只要您的订阅是最新的，就可以使用 FastTrack 服务来实施满足符合条件的计划。</span><span class="sxs-lookup"><span data-stu-id="f00db-113">You can use FastTrack services to onboard and adopt any qualifying product workload as long as your subscription is current.</span></span>  
    
<span data-ttu-id="f00db-114">下表列出了流程中的角色和职责。</span><span class="sxs-lookup"><span data-stu-id="f00db-114">The following table lists roles and responsibilities for the process.</span></span>

|||
|:-----|:-----|
|<span data-ttu-id="f00db-115">**角色**</span><span class="sxs-lookup"><span data-stu-id="f00db-115">**Role**</span></span> <br/> |<span data-ttu-id="f00db-116">**职责**</span><span class="sxs-lookup"><span data-stu-id="f00db-116">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="f00db-117">**FastTrack 专家**</span><span class="sxs-lookup"><span data-stu-id="f00db-117">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="f00db-118">远程提供所有部署和更新服务。</span><span class="sxs-lookup"><span data-stu-id="f00db-118">Provides all deployment and update services remotely.</span></span>  <br/> <span data-ttu-id="f00db-119">通过综合使用工具和发布的文档远程协助你。</span><span class="sxs-lookup"><span data-stu-id="f00db-119">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="f00db-120">直接协助你或你的代表。</span><span class="sxs-lookup"><span data-stu-id="f00db-120">Works directly with you or your representative.</span></span>|
|<span data-ttu-id="f00db-121">**FastTrack 中心**</span><span class="sxs-lookup"><span data-stu-id="f00db-121">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="f00db-122">提供用于规划和部署 Windows 10 企业版的指南。</span><span class="sxs-lookup"><span data-stu-id="f00db-122">Provides guidance to plan and deploy Windows 10 Enterprise.</span></span>   <br/> <span data-ttu-id="f00db-123">在正常工作时间对特定区域提供协助。</span><span class="sxs-lookup"><span data-stu-id="f00db-123">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="f00db-124">使用繁体中文、简体中文（仅限讲普通话的资源）、英语、法语、德语、意大利语、日语、韩语、葡萄牙语（巴西）、西班牙语、泰语和越南语提供协助。</span><span class="sxs-lookup"><span data-stu-id="f00db-124">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
 

 