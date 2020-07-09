---
title: FastTrack 中心权益概述
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see FastTrack Center Benefit for Office 365.
ms.openlocfilehash: 3537f6effa5bd2c65f542496ea42ab70075621ce
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011330"
---
# <a name="fasttrack-center-benefit-overview"></a>FastTrack 中心权益概述

With FastTrack Center Benefit for Office 365, you work remotely with FastTrack Specialists to get your Office 365 environment ready for use and plan rollout and usage within your organization. To learn more about eligibility, see [FastTrack Center Benefit for Office 365](O365-fasttrack-benefit-for-office-365.md).
  
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
    
Your Office 365 tenant is created at the completion of onboarding. Licensed users can access Office 365 by using one of the following identity options:
- 具有唯一 Office 365 帐户的云标识。
- Synchronized Identities with Office 365 accounts synchronized from your on-premises Active Directory with Azure Active Directory Connect (Password Hash Sync or Pass-through Authentication). These are for customers with:
  - 单一 Active Directory 林环境。
  - Supported multi-forests Active Directory topology. For supported topologies, see [Source Environment Expectations](O365-source-environment-expectations.md).
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

