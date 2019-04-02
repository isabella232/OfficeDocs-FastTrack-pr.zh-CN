---
title: FastTrack 过程
description: FastTrack 中心福利载入过程概述
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 04/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a2d3f601c1395b908d2ad8fd7a6a0dde38502784
ms.sourcegitcommit: 8d1fbbfc6b05522ea1259149349548f072fefcac
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/01/2019
ms.locfileid: "31016776"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>适用于企业移动性 + 安全性 (EMS) 的 FastTrack 中心权益流程
如果您的组织有资格获得 EMS 的 FastTrack 中心权益, 您可以与 FastTrack 专家远程合作, 以获取 microsoft Azure Active Directory Premium 和 microsoft Intune 准备好使用。 您还可以通过[FastTrack 网站](https://www.microsoft.com/fasttrack/microsoft-365/ems)请求获取 Azure 信息保护、microsoft 云应用安全和 microsoft 高级威胁分析的帮助。 若要了解您的组织是否符合条件, 请参阅[符合条件的服务和计划](M365-eligible-services-and-plans.md)。


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

    -   同步标识: 使用 Azure active directory Connect 工具 (密码哈希同步或传递身份验证) 从本地 Active directory 同步的 EMS 帐户。 此选项适用于具有单个林或多个 Active Directory 林的客户。

    -   联合身份--包含的 Microsoft EMS 帐户为:

        -   从 Active Directory 与 Azure AD Connect 工具同步。 此选项适用于具有单个 Active Directory 林配置的客户。

        -   从本地 Active directory 与 Windows Server 2012 R2 active directory 联合身份验证服务 (AD FS) 2.0 或更高版本联合。
