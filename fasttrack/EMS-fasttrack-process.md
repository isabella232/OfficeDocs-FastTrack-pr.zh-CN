---
title: FastTrack 流程
description: FastTrack 中心权益载入流程概述
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 7/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: None
ms.collection: FastTrack
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: b0ed1d991eef76713924cc668adc47cfaf9da593
ms.sourcegitcommit: de2cc20b4ab297633cb254d42532719022bb8d99
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/02/2020
ms.locfileid: "47338374"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>适用于企业移动性 + 安全性 (EMS) 的 FastTrack 中心权益流程

> [!CAUTION]
> 此内容已不再是最新的，且已计划删除。 使用左侧导航栏中的目录可查看最新内容。

如果你的组织有资格享受适用于 EMS 的 FastTrack 中心权益，则你可以与 FastTrack 专家远程合作，以使 Microsoft Azure Active Directory Premium、Microsoft Intune 和 Azure 信息保护随时可用。 你还可以通过 [FastTrack 网站](https://www.microsoft.com/fasttrack/microsoft-365/ems)请求帮助，以实现 Azure 信息保护 和 Microsoft 云应用安全。 若要了解你的组织是否符合条件，请参阅[符合条件的服务和计划](M365-eligible-services-and-plans.md)。


下面是有关载入流程的介绍：

-   [载入流程概述](EMS-fasttrack-benefit-overview.md)

-   [对源环境的预期](EMS-source-environment-expectations.md)

-   [载入流程的各个阶段](EMS-onboarding-phases.md)

-   每个阶段的 [FastTrack 责任](EMS-fasttrack-responsibilities.md)

-   每个阶段的[客户责任](EMS-your-responsibilities.md)

载入完成后，你将看到的内容：

-   你的所选服务的 EMS 租户已创建。

-   许可用户可以使用以下任何一个标识选项访问 EMS 服务：

    -   云标识（唯一的 EMS 帐户）。

    -   同步标识：使用 Azure Active Directory Connect 工具（密码哈希同步或直通身份验证）从本地 Active Directory 同步的 EMS 帐户。 此选项适用于拥有单个林或多个 Active Directory 林的客户。

    -   具有满足以下条件的 Microsoft EMS 帐户的联合标识：

        -   已从 Active Directory 与 Azure AD Connect 工具同步。 此选项适用于具有单个 Active Directory 林配置的客户。

        -   与本地 Active Directory 中的 Windows Server 2012 R2 Active Directory 联合身份验证服务 (AD FS) 2.0 或更高版本联合。

        -   通过 Azure 信息保护自动分类和保护静止和传输中的信息的能力。 

        -   使用 Azure 信息保护扫描程序在本地文件共享和 SharePoint 服务器中发现信息的能力。 

        -   在 Azure 密钥存储库中管理 Azure 信息保护租户密钥的能力。 

