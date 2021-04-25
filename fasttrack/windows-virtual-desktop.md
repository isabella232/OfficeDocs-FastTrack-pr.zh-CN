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
description: FastTrack 提供了 Windows 虚拟桌面部署指南，可帮助你载入此桌面。
ms.openlocfilehash: 9e8712b7a1f324d02715527b22eca3f7e4db4656
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996231"
---
# <a name="windows-virtual-desktop"></a><span data-ttu-id="7717c-103">Windows 虚拟桌面</span><span class="sxs-lookup"><span data-stu-id="7717c-103">Windows Virtual Desktop</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="7717c-104"><strong>服务</strong></span><span class="sxs-lookup"><span data-stu-id="7717c-104"><strong>Service</strong></span></span></th>
<th><span data-ttu-id="7717c-105"><strong>FastTrack 指南详细信息</strong></span><span class="sxs-lookup"><span data-stu-id="7717c-105"><strong>FastTrack Guidance Details</strong></span></span></th>
<th><span data-ttu-id="7717c-106"><strong>对源环境的预期</strong></span><span class="sxs-lookup"><span data-stu-id="7717c-106"><strong>Source Environment Expectations</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="7717c-107">Windows 虚拟桌面</span><span class="sxs-lookup"><span data-stu-id="7717c-107">Windows Virtual Desktop</span></span></td>
<td><p><span data-ttu-id="7717c-108">FastTrack 提供了 Windows 虚拟桌面部署指南，可帮助你轻松载入此桌面和应用虚拟化服务，同时利用 Windows 10 多会话体验，该体验针对 Microsoft 365 企业应用版进行了优化，具有集成的 Microsoft 365 安全和管理。</span><span class="sxs-lookup"><span data-stu-id="7717c-108">FastTrack provides Windows Virtual Desktop deployment guidance to help you onboard to this desktop and app virtualization service with ease while taking advantage of Windows 10 multi-session experience, optimized for Microsoft 365 Apps for Enterprise with integrated security and management for Microsoft 365.</span></span></p>
<p><span data-ttu-id="7717c-109">你可与 FastTrack 专家协作：</span><span class="sxs-lookup"><span data-stu-id="7717c-109">You work with FastTrack Specialists to:</span></span></p>
<ul>
<li><p><span data-ttu-id="7717c-110">使用 Windows 10 企业版多会话 + Microsoft 365 企业应用版部署 WVD 环境，如下所示：</span><span class="sxs-lookup"><span data-stu-id="7717c-110">Deploy WVD environment with Windows 10 Enterprise multi-session + Microsoft 365 Apps for Enterprise using the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="7717c-111">Azure 市场映像</span><span class="sxs-lookup"><span data-stu-id="7717c-111">Azure Marketplace Image</span></span></p></li>
<li><p><span data-ttu-id="7717c-112">共享图像</span><span class="sxs-lookup"><span data-stu-id="7717c-112">Shared Image</span></span></p></li>
<li><p><span data-ttu-id="7717c-113">Office 部署Toolkit (ODT) </span><span class="sxs-lookup"><span data-stu-id="7717c-113">Office Deployment Toolkit (ODT)</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="7717c-114">配置 FSLogix</span><span class="sxs-lookup"><span data-stu-id="7717c-114">Configure FSLogix</span></span></p>
<ul>
<li><p><span data-ttu-id="7717c-115">使用配置文件容器部署 FSLogix 代理</span><span class="sxs-lookup"><span data-stu-id="7717c-115">Deploy FSLogix Agent with Profile Container</span></span></p></li>
<li><p><span data-ttu-id="7717c-116">使用 Office 容器部署 FSLogix 代理</span><span class="sxs-lookup"><span data-stu-id="7717c-116">Deploy FSLogix Agent with Office Container</span></span></p></li>
<li><p><span data-ttu-id="7717c-117">使用内容排除项配置 FSLogix 文件夹</span><span class="sxs-lookup"><span data-stu-id="7717c-117">Configure FSLogix folder with content exclusions</span></span></p></li>
</ul></li>
<li><p><span data-ttu-id="7717c-118">部署 Microsoft Edge</span><span class="sxs-lookup"><span data-stu-id="7717c-118">Deploy Microsoft Edge</span></span></p></li>
<li><p><span data-ttu-id="7717c-119">部署 Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="7717c-119">Deploy Microsoft Teams</span></span></p></li>
<li><p><span data-ttu-id="7717c-120">使用 Windows 虚拟桌面客户端进行连接</span><span class="sxs-lookup"><span data-stu-id="7717c-120">Connect using Windows Virtual Desktop Clients</span></span></p></li>
</ul>
<p><span data-ttu-id="7717c-121"><strong>以下内容超出范围</strong></span><span class="sxs-lookup"><span data-stu-id="7717c-121"><strong>The following is out of scope</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="7717c-122">客户的 Windows 虚拟桌面部署的项目管理。</span><span class="sxs-lookup"><span data-stu-id="7717c-122">Project management of the customer's Windows Virtual Desktop deployment.</span></span></p></li>
<li><p><span data-ttu-id="7717c-123">现场支持。</span><span class="sxs-lookup"><span data-stu-id="7717c-123">On-site support.</span></span></p></li>
<li><p><span data-ttu-id="7717c-124">第三方应用程序虚拟化/部署。</span><span class="sxs-lookup"><span data-stu-id="7717c-124">Third-party application virtualization/deployment.</span></span></p></li>
<li><p><span data-ttu-id="7717c-125">自定义图像。</span><span class="sxs-lookup"><span data-stu-id="7717c-125">Custom images.</span></span></p></li>
<li><p><span data-ttu-id="7717c-126">涉及 VMware 和 Citrix 的迁移和方案。</span><span class="sxs-lookup"><span data-stu-id="7717c-126">Migrations and scenarios involving VMware and Citrix.</span></span></p></li>
<li><p><span data-ttu-id="7717c-127">Linux 方案。</span><span class="sxs-lookup"><span data-stu-id="7717c-127">Linux scenarios.</span></span></p></li>
<li><p><span data-ttu-id="7717c-128">用户配置文件的转换或迁移。</span><span class="sxs-lookup"><span data-stu-id="7717c-128">Conversion or migrations of user profiles.</span></span></p></li>
</ul>
<p><span data-ttu-id="7717c-129">请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。</span><span class="sxs-lookup"><span data-stu-id="7717c-129">Contact a <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft Partner</a> for assistance with these services.</span></span></p></td>
<td><p><span data-ttu-id="7717c-130">你应该已经拥有以下内容：</span><span class="sxs-lookup"><span data-stu-id="7717c-130">You should already have the following:</span></span></p>
<ul>
<li><p><span data-ttu-id="7717c-131"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">WVD 许可要求</a></span><span class="sxs-lookup"><span data-stu-id="7717c-131"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">WVD Licensing Requirements</a></span></span></p></li>
<li><p><span data-ttu-id="7717c-132">Azure 网络：</span><span class="sxs-lookup"><span data-stu-id="7717c-132">Azure Networking:</span></span></p>
<ul>
<li><p><span data-ttu-id="7717c-133">VNET 创建 &amp; 子网</span><span class="sxs-lookup"><span data-stu-id="7717c-133">VNET creation &amp; Subnetting</span></span></p></li>
<li><p><span data-ttu-id="7717c-134">防火墙/网络安全组</span><span class="sxs-lookup"><span data-stu-id="7717c-134">Firewall / Network Security Groups</span></span></p></li>
<li><p><span data-ttu-id="7717c-135">VPN/ ExpressRoute</span><span class="sxs-lookup"><span data-stu-id="7717c-135">VPN / ExpressRoute</span></span></p></li>
<li><p><span data-ttu-id="7717c-136">从本地路由到 Azure</span><span class="sxs-lookup"><span data-stu-id="7717c-136">Routing to Azure from on-premises</span></span></p></li>
<li><p><span data-ttu-id="7717c-137">允许连接到 WVD 的防火墙规则</span><span class="sxs-lookup"><span data-stu-id="7717c-137">Firewall rules to allow connectivity to WVD</span></span></p>
<ul>
<li><p><span data-ttu-id="7717c-138"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">文档参考</a></span><span class="sxs-lookup"><span data-stu-id="7717c-138"><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">Docs Reference</a></span></span></p></li>
</ul></li>
</ul></li>
<li><p><span data-ttu-id="7717c-139">Azure Active Directory 常规设置</span><span class="sxs-lookup"><span data-stu-id="7717c-139">Azure Active Directory General Setup</span></span></p>
<ul>
<li><p><span data-ttu-id="7717c-140">标识策略 <strong> (仅选择以下 3 个选项中的 1 个选项) </strong></span><span class="sxs-lookup"><span data-stu-id="7717c-140">Identity Strategy <strong>(Select ONLY 1 of the following 3 options)</strong></span></span></p>
<ul>
<li><p><span data-ttu-id="7717c-141">Azure 中具有 Azure AD Connect 的 Active Directory</span><span class="sxs-lookup"><span data-stu-id="7717c-141">Active Directory with Azure AD Connect in Azure</span></span></p></li>
<li><p><span data-ttu-id="7717c-142">通过 VPN/ER 在内部部署上使用 Azure AD Connect 的 Active Directory</span><span class="sxs-lookup"><span data-stu-id="7717c-142">Active Directory with Azure AD Connect On Premise over VPN / ER</span></span></p></li>
<li><p><span data-ttu-id="7717c-143">Active Directory 域服务</span><span class="sxs-lookup"><span data-stu-id="7717c-143">Active Directory Domain Services</span></span></p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
