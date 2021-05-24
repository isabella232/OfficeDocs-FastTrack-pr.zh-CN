---
title: Windows 虚拟桌面
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: virtual-desktop
localization_priority: None
ms.collection: FastTrack
description: FastTrack Windows虚拟桌面部署指南，可帮助你载入此桌面。
ms.openlocfilehash: bdec1f6438a34b5ec023be5159329617bc5a78f9
ms.sourcegitcommit: e03f300ee223d72bc5af84d8d94e580dc649442c
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/21/2021
ms.locfileid: "52592435"
---
# <a name="windows-virtual-desktop"></a><span data-ttu-id="fea66-103">Windows 虚拟桌面</span><span class="sxs-lookup"><span data-stu-id="fea66-103">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="fea66-104"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="fea66-104"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="fea66-105"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="fea66-105"><strong>FastTrack Guidance Details</strong></span></span></th>
<th><span data-ttu-id="fea66-106"><strong>对源环境的预期</strong></span><span class="sxs-lookup"><span data-stu-id="fea66-106"><strong>Source Environment Expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="fea66-107">Windows 虚拟桌面</span><span class="sxs-lookup"><span data-stu-id="fea66-107">Windows Virtual Desktop</span></span></td>
<td><p><span data-ttu-id="fea66-108">FastTrack 提供了 Windows 虚拟桌面部署指南，可帮助你轻松载入此桌面应用虚拟化服务，同时利用 Windows 10 多会话体验，针对 Microsoft 365 应用版 for Enterprise 进行了优化，具有针对 Microsoft 365 的集成安全和管理。</span><span class="sxs-lookup"><span data-stu-id="fea66-108">FastTrack provides Windows Virtual Desktop deployment guidance to help you onboard to this desktop and app virtualization service with ease while taking advantage of Windows 10 multi-session experience, optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="fea66-109">你可与 FastTrack 专家协作：</span><span class="sxs-lookup"><span data-stu-id="fea66-109">You work with FastTrack Specialists to:</span></span></p>
<ul>
<li><p><span data-ttu-id="fea66-110">使用以下Windows 10 企业版部署具有Microsoft 365 应用版 +Enterprise的 WVD 环境：</span><span class="sxs-lookup"><span data-stu-id="fea66-110">Deploy WVD environment with Windows 10 Enterprise multi-session + Microsoft 365 Apps for Enterprise using the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="fea66-111">Azure 市场映像</span><span class="sxs-lookup"><span data-stu-id="fea66-111">Azure Marketplace Image</span></span></p></li>
<li><p><span data-ttu-id="fea66-112">共享图像</span><span class="sxs-lookup"><span data-stu-id="fea66-112">Shared Image</span></span></p></li>
<li><p><span data-ttu-id="fea66-113">Office部署Toolkit (ODT) </span><span class="sxs-lookup"><span data-stu-id="fea66-113">Office Deployment Toolkit (ODT)</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="fea66-114">配置 FSLogix</span><span class="sxs-lookup"><span data-stu-id="fea66-114">Configure FSLogix</span></span></p>
<ul>
<li><p><span data-ttu-id="fea66-115">使用配置文件容器部署 FSLogix 代理</span><span class="sxs-lookup"><span data-stu-id="fea66-115">Deploy FSLogix Agent with Profile Container</span></span></p></li>
<li><p><span data-ttu-id="fea66-116">使用容器部署 FSLogix Office代理</span><span class="sxs-lookup"><span data-stu-id="fea66-116">Deploy FSLogix Agent with Office Container</span></span></p></li>
<li><p><span data-ttu-id="fea66-117">使用内容排除项配置 FSLogix 文件夹</span><span class="sxs-lookup"><span data-stu-id="fea66-117">Configure FSLogix folder with content exclusions</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="fea66-118">部署 Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="fea66-118">Deploy Microsoft Edge</span></span></p></li>
<li><p><span data-ttu-id="fea66-119">部署Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="fea66-119">Deploy Microsoft Teams</span></span></p></li>
<li><p><span data-ttu-id="fea66-120">连接虚拟Windows客户端进行部署</span><span class="sxs-lookup"><span data-stu-id="fea66-120">Connect using Windows Virtual Desktop Clients</span></span></p></li>
</ul>
<p><span data-ttu-id="fea66-121"><strong>以下内容超出范围</strong></span><span class="sxs-lookup"><span data-stu-id="fea66-121"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="fea66-122">Project虚拟桌面部署Windows管理。</span><span class="sxs-lookup"><span data-stu-id="fea66-122">Project management of the customer's Windows Virtual Desktop deployment.</span></span></p></li>
<li><p><span data-ttu-id="fea66-123">现场支持。</span><span class="sxs-lookup"><span data-stu-id="fea66-123">On-site support.</span></span></p></li>
<li><p><span data-ttu-id="fea66-124">第三方应用程序虚拟化/部署。</span><span class="sxs-lookup"><span data-stu-id="fea66-124">Third-party application virtualization/deployment.</span></span></p></li>
<li><p><span data-ttu-id="fea66-125">自定义图像。</span><span class="sxs-lookup"><span data-stu-id="fea66-125">Custom images.</span></span></p></li>
<li><p><span data-ttu-id="fea66-126">涉及 VMware 和 Citrix 的迁移和方案。</span><span class="sxs-lookup"><span data-stu-id="fea66-126">Migrations and scenarios involving VMware and Citrix.</span></span></p></li>
<li><p><span data-ttu-id="fea66-127">Linux 方案。</span><span class="sxs-lookup"><span data-stu-id="fea66-127">Linux scenarios.</span></span></p></li>
<li><p><span data-ttu-id="fea66-128">用户配置文件的转换或迁移。</span><span class="sxs-lookup"><span data-stu-id="fea66-128">Conversion or migrations of user profiles.</span></span></p></li>
</ul>
<p><span data-ttu-id="fea66-129">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="fea66-129">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></p></td>
<td><p><span data-ttu-id="fea66-130">你应该已经拥有以下内容：</span><span class="sxs-lookup"><span data-stu-id="fea66-130">You should already have the following:</span></span></p>
<ul>
<li><p>[<span data-ttu-id="fea66-131">WVD 许可要求</span><span class="sxs-lookup"><span data-stu-id="fea66-131">WVD Licensing Requirements</span></span>](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p><span data-ttu-id="fea66-132">Azure 网络：</span><span class="sxs-lookup"><span data-stu-id="fea66-132">Azure Networking:</span></span></p>
<ul>
<li><p><span data-ttu-id="fea66-133">VNET 创建 &amp; 子网</span><span class="sxs-lookup"><span data-stu-id="fea66-133">VNET creation &amp; Subnetting</span></span></p></li>
<li><p><span data-ttu-id="fea66-134">防火墙/网络安全组</span><span class="sxs-lookup"><span data-stu-id="fea66-134">Firewall / Network Security Groups</span></span></p></li>
<li><p><span data-ttu-id="fea66-135">VPN/ ExpressRoute</span><span class="sxs-lookup"><span data-stu-id="fea66-135">VPN / ExpressRoute</span></span></p></li>
<li><p><span data-ttu-id="fea66-136">从本地路由到 Azure</span><span class="sxs-lookup"><span data-stu-id="fea66-136">Routing to Azure from on-premises</span></span></p></li>
<li><p><span data-ttu-id="fea66-137">允许连接到 WVD 的防火墙规则</span><span class="sxs-lookup"><span data-stu-id="fea66-137">Firewall rules to allow connectivity to WVD</span></span></p>
<ul>
<li><p>[<span data-ttu-id="fea66-138">文档参考</span><span class="sxs-lookup"><span data-stu-id="fea66-138">Docs Reference</span></span>](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p><span data-ttu-id="fea66-139">Azure Active Directory常规设置</span><span class="sxs-lookup"><span data-stu-id="fea66-139">Azure Active Directory General Setup</span></span></p>
<ul>
<li><p><span data-ttu-id="fea66-140">标识策略 <strong> (仅选择以下 3 个选项中的 1 个选项) </strong></span><span class="sxs-lookup"><span data-stu-id="fea66-140">Identity Strategy <strong>(Select ONLY 1 of the following 3 options)</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="fea66-141">Azure 中具有 Azure AD 连接 Active Directory</span><span class="sxs-lookup"><span data-stu-id="fea66-141">Active Directory with Azure AD Connect in Azure</span></span></p></li>
<li><p><span data-ttu-id="fea66-142">通过 VPN/ER 连接本地部署 Azure AD 的 Active Directory</span><span class="sxs-lookup"><span data-stu-id="fea66-142">Active Directory with Azure AD Connect On Premise over VPN / ER</span></span></p></li>
<li><p><span data-ttu-id="fea66-143">Active Directory 域服务</span><span class="sxs-lookup"><span data-stu-id="fea66-143">Active Directory Domain Services</span></span></p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
