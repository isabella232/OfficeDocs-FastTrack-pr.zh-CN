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
# <a name="windows-virtual-desktop"></a>Windows 虚拟桌面

<table>
<thead>
<tr class="header">
<th><strong>服务</strong></th>
<th><strong>FastTrack 指南详细信息</strong></th>
<th><strong>对源环境的预期</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Windows 虚拟桌面</td>
<td><p>FastTrack 提供了 Windows 虚拟桌面部署指南，可帮助你轻松载入此桌面和应用虚拟化服务，同时利用 Windows 10 多会话体验，该体验针对 Microsoft 365 企业应用版进行了优化，具有集成的 Microsoft 365 安全和管理。</p>
<p>你可与 FastTrack 专家协作：</p>
<ul>
<li><p>使用 Windows 10 企业版多会话 + Microsoft 365 企业应用版部署 WVD 环境，如下所示：</p>
<ul>
<li><p>Azure 市场映像</p></li>
<li><p>共享图像</p></li>
<li><p>Office 部署Toolkit (ODT) </p></li>
</ul></li>
<li><p>配置 FSLogix</p>
<ul>
<li><p>使用配置文件容器部署 FSLogix 代理</p></li>
<li><p>使用 Office 容器部署 FSLogix 代理</p></li>
<li><p>使用内容排除项配置 FSLogix 文件夹</p></li>
</ul></li>
<li><p>部署 Microsoft Edge</p></li>
<li><p>部署 Microsoft Teams</p></li>
<li><p>使用 Windows 虚拟桌面客户端进行连接</p></li>
</ul>
<p><strong>以下内容超出范围</strong></p>
<ul>
<li><p>客户的 Windows 虚拟桌面部署的项目管理。</p></li>
<li><p>现场支持。</p></li>
<li><p>第三方应用程序虚拟化/部署。</p></li>
<li><p>自定义图像。</p></li>
<li><p>涉及 VMware 和 Citrix 的迁移和方案。</p></li>
<li><p>Linux 方案。</p></li>
<li><p>用户配置文件的转换或迁移。</p></li>
</ul>
<p>请与 <a href="https://go.microsoft.com/fwlink/?linkid=2080150">Microsoft 合作伙伴联系</a> ，获得这些服务的帮助。</p></td>
<td><p>你应该已经拥有以下内容：</p>
<ul>
<li><p><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">WVD 许可要求</a></p></li>
<li><p>Azure 网络：</p>
<ul>
<li><p>VNET 创建 &amp; 子网</p></li>
<li><p>防火墙/网络安全组</p></li>
<li><p>VPN/ ExpressRoute</p></li>
<li><p>从本地路由到 Azure</p></li>
<li><p>允许连接到 WVD 的防火墙规则</p>
<ul>
<li><p><a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients">文档参考</a></p></li>
</ul></li>
</ul></li>
<li><p>Azure Active Directory 常规设置</p>
<ul>
<li><p>标识策略 <strong> (仅选择以下 3 个选项中的 1 个选项) </strong></p>
<ul>
<li><p>Azure 中具有 Azure AD Connect 的 Active Directory</p></li>
<li><p>通过 VPN/ER 在内部部署上使用 Azure AD Connect 的 Active Directory</p></li>
<li><p>Active Directory 域服务</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
