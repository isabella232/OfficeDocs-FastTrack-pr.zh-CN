---
title: FastTrack 中心权益概述
ms.author: v-bermic@microsoft.com
author: rberg-steyer@microsoft.com
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: 使用适于 Office 365 的 FastTrack 中心权益，可以与 FastTrack 专家远程合作，共同让 Office 365 环境可供使用，并计划在组织内推动服务的使用。有关资格的详细信息，请参阅适用于 Office 365 的 FastTrack 中心权益。
ms.openlocfilehash: 039a1a409f35d12e61e25757e18f481c2b754571
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827078"
---
# <a name="fasttrack-center-benefit-overview"></a>FastTrack 中心权益概述

> [!CAUTION]
> 此内容已不再是最新的，且已计划删除。 使用左侧导航栏中的目录可查看最新内容。

使用适于 Office 365 的 FastTrack 中心权益，可以与 FastTrack 专家远程合作，共同让 Office 365 环境可供使用，并计划在组织内推动服务的使用。有关资格的详细信息，请参阅[适用于 Office 365 的 FastTrack 中心权益](O365-fasttrack-benefit-for-office-365.md)。
  
我们将介绍以下主题：
- [FastTrack 流程](O365-fasttrack-process.md) 
- [对源环境的预期](O365-source-environment-expectations.md)
- [载入和迁移阶段](O365-onboarding-and-migration.md)
- [数据迁移](O365-data-migration.md)
- [FastTrack 责任](O365-fasttrack-responsibilities.md)
- [你的责任](O365-your-responsibilities.md) 
- [附录 A - FastTrack 中心附加权益](O365-fasttrack-additional-benefits.md)
- [附录 B - FastTrack 中心 HIPAA 业务关联协议](O365-hipaa-business-associate-agreement.md)
- [附录 C - 适用于 Office 365 美国政府版的 FastTrack 中心权益概述](US-Gov-appendix-overview.md)
    
载入完成后，即会创建 Office 365 租户。许可用户可以使用以下任何一个标识选项访问 Office 365：
- 具有唯一 Office 365 帐户的云标识。
- 具有 Office 365 帐户的同步标识，从本地 Active Directory 与 Azure Active Directory Connect 同步（密码哈希同步或直通身份验证）。这些适合符合以下条件的客户：
  - 单一 Active Directory 林环境。
  - 受支持的多林 Active Directory 拓扑。有关受支持的拓扑，请参阅[对源环境的预期](O365-source-environment-expectations.md)。
- 具有满足以下条件的 Office 365 帐户的联合标识：
  - 为具有以下条件的客户从 Active Directory 与 Azure Active Directory Connect 工具进行同步：
      - 单一 Active Directory 林配置。
      - 单一 Active Directory 帐户林（也称为“登录林”）和单一 Active Directory 资源林配置。
  - 使用满足以下条件的本地 Active Directory 联合身份验证服务 (AD FS) 基础结构配置：
      - 从本地 Active Directory 与 Windows Server 2012 R2 前向 AD FS 角色联合。
      - 在需要时，使用 Windows Server 2012 R2 前向 Windows 应用程序代理 (WAP) 角色将本地 AD FS 基础结构发布到 internet。
    > [!NOTE]
    > AD FS 和 WAP 部署和配置可以通过使用本地环境中的 [ 配置向导 ](https://go.microsoft.com/fwlink/?linkid=844794)来完成。 
  
- 许可用户现在可以访问[符合条件的服务和计划](M365-eligible-services-and-plans.md)。

