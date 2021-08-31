---
title: Windows 虚拟桌面
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 7/01/2020
audience: ITPro
ms.topic: overview
ms.service: virtual-desktop
ms.localizationpriority: ''
ms.collection: FastTrack
description: FastTrack提供Windows虚拟桌面部署指南，以帮助你载入此桌面。
ms.openlocfilehash: f6925cbbb9e18921139d370ef32bb64f4658069e
ms.sourcegitcommit: 3d086ab6c4743afbedebed55a3ddb65f05422a1b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/30/2021
ms.locfileid: "58710514"
---
# <a name="windows-virtual-desktop"></a>Windows 虚拟桌面

<table>
<thead>
<tr class="header">
<th><strong>服务</strong></th>
<th><strong>FastTrack指南详细信息</strong></th>
<th><strong>对源环境的预期</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Windows 虚拟桌面</td>
<td><p>FastTrack 提供了 Windows 虚拟桌面部署指南，可帮助你轻松载入此桌面应用虚拟化服务，同时利用 Windows 10 多会话体验，该体验针对 Microsoft 365 应用版 for Enterprise 进行了优化，具有针对 Microsoft 365 的集成安全和管理。</p>
<p>你可与 FastTrack 专家协作：</p>
<ul>
<li><p>使用以下Windows 10 企业版部署具有Microsoft 365 应用版 +Enterprise的 WVD 环境：</p>
<ul>
<li><p>Azure 市场映像</p></li>
<li><p>共享图像</p></li>
<li><p>Office部署Toolkit (ODT) </p></li>
</ul></li>
<li><p>配置 FSLogix</p>
<ul>
<li><p>使用配置文件容器部署 FSLogix 代理</p></li>
<li><p>使用容器部署 FSLogix Office代理</p></li>
<li><p>使用内容排除项配置 FSLogix 文件夹</p></li>
</ul></li>
<li><p>部署 Microsoft Edge</p></li>
<li><p>部署Microsoft Teams</p></li>
<li><p>连接虚拟Windows客户端进行部署</p></li>
</ul>
<p><strong>以下内容超出范围</strong></p>
<ul>
<li><p>Project虚拟桌面部署Windows管理。</p></li>
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
<li><p>[WVD 许可要求](/azure/virtual-desktop/overview#requirements)</p></li>
<li><p>Azure 网络：</p>
<ul>
<li><p>VNET 创建 &amp; 子网</p></li>
<li><p>防火墙/网络安全组</p></li>
<li><p>VPN/ ExpressRoute</p></li>
<li><p>从本地路由到 Azure</p></li>
<li><p>允许连接到 WVD 的防火墙规则</p>
<ul>
<li><p>[文档参考](/azure/virtual-desktop/overview#supported-remote-desktop-clients)</p></li>
</ul></li>
</ul></li>
<li><p>Azure Active Directory常规设置</p>
<ul>
<li><p>标识策略 <strong> (仅选择以下 3 个选项中的 1 个选项) </strong></p>
<ul>
<li><p>Azure 中具有 Azure AD 连接 Active Directory</p></li>
<li><p>通过 VPN/ER 连接本地部署 Azure AD 的 Active Directory</p></li>
<li><p>Active Directory 域服务</p></li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>
