---
title: FastTrack 过程
description: FastTrack 中心福利载入过程概述
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 1e3f34284cb4b6300a50116ad2bb1df3cb6ab0fe
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513771"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>适用于企业移动性 + 安全性 (EMS) 的 FastTrack 中心权益流程
如果你的组织符合 EMS 的 FastTrack 中心权益, 你可以与 FastTrack 专家远程合作, 以获取 Microsoft Azure Active Directory Premium、Microsoft Intune 和 Azure 信息保护 (可供使用)。 您还可以通过[FastTrack 网站](https://www.microsoft.com/fasttrack/microsoft-365/ems)请求获取 Azure 信息保护、Microsoft 云应用安全和 Microsoft 高级威胁分析的帮助。 若要了解您的组织是否符合条件, 请参阅[符合条件的服务和计划](M365-eligible-services-and-plans.md)。


以下是关于载入过程的讨论:

-   [加入过程概述](EMS-fasttrack-benefit-overview.md)

-   [对源环境的预期](EMS-source-environment-expectations.md)

-   [载入过程的各个阶段](EMS-onboarding-phases.md)

-   每个阶段的[FastTrack 责任](EMS-fasttrack-responsibilities.md)

-   每个阶段的[客户责任](EMS-your-responsibilities.md)

以下是完成载入时可以预料到的事项:

-   将创建所选服务的 EMS 租户。

-   许可用户可以使用以下标识选项之一访问 EMS 服务:

    -   云标识 (唯一 EMS 帐户)。

    -   同步标识: 使用 Azure Active Directory Connect 工具 (密码哈希同步或传递身份验证) 从本地 Active Directory 同步的 EMS 帐户。 此选项适用于具有单个林或多个 Active Directory 林的客户。

    -   联合身份--包含的 Microsoft EMS 帐户为:

        -   从 Active Directory 与 Azure AD Connect 工具同步。 此选项适用于具有单个 Active Directory 林配置的客户。

        -   从本地 Active Directory 与 Windows Server 2012 R2 Active Directory 联合身份验证服务 (AD FS) 2.0 或更高版本联合。

        -   能够在 rest 和通过 Azure 信息保护的传输过程中自动分类和保护信息。 

        -   能够使用 Azure 信息保护扫描程序发现内部部署文件共享和 SharePoint 服务器中的信息。 

        -   在 Azure Key Vault 中管理 Azure 信息保护租户密钥的功能。 
