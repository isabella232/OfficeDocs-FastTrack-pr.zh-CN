---
title: 源环境预期
description: 使用适用于 EMS 的 FastTrack 中心权益的源环境要求
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 6/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 382d132cfe3c7dfa948568188f9050b389dec15f
ms.sourcegitcommit: 826f140cc0ddee32005f74e5d995073af1dc3fa2
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/02/2020
ms.locfileid: "44471693"
---
# <a name="source-environment-expectations"></a>源环境预期

当使用[适用于企业移动性 + 安全性 (EMS) 的 FastTrack 中心权益](EMS-fasttrack-benefit-for-EMS.md)以使 Microsoft Azure Active Directory Premium、Microsoft Intune 和 Azure 信息保护随时可用时，你的环境需要满足以下部分中描述的预期。

你的组织中可能已经具有要与企业移动性 + 安全性 (EMS) 集成的本地 Active Directory，或从单一控制台使用富标识管理的其任何单个服务。 适用于企业移动性 + 安全性 (EMS) 的 FastTrack 中心权益包括帮助你将 Azure Active Directory 与现有的本地 Active Directory 环境集成。

下表列出了对现有源环境的载入预期。

|活动|对源环境的预期|
|------------|----------------------------------|
|核心载入|将功能林级别设置为 Windows Server 2008 或更高版本的 Active Directory 林，具有以下林配置：<br /><br />-   单个 Active Directory 林<br />-   多个 Active Directory 林 </br></br>**注意**：对于所有的多林配置，Active Directory 联合身份验证服务 (AD FS) 部署超出了 FastTrack 中心权益的范围。|
|Azure AD Premium 载入|已为 Azure AD Premium 准备了本地 Active Directory 及其环境，其中包括对妨碍与 Azure AD 和 Azure AD Premium 功能集成的已确定问题的修正。|
|Intune 载入| 在计划使用 Intune 部署 WiFi 和 VPN 配置文件时，IT 管理员需要确保现有的证书颁发机构、WiFi 和 VPN 基础结构已经在其生产环境中正常使用。<br /><br /> **注意**：服务权益不包括有关设置或配置证书颁发机构、WiFi、VPN 基础结构或 Apple MDM 推送证书的帮助  |
|使用 Intune 云附加 Configuration Manager |通过云附加 ，IT 管理员负责准备本地环境，其中可能包括修复妨碍你使用 Intune 云附加 Configuration Manager 环境。<br /><br />**注意**：FastTrack 服务权益不包括有关将配置管理器站点服务器或配置管理器客户端设置或升级到支持云附加所需的最低要求的帮助。 |
|Intune 与 Microsoft Defender 高级威胁防护 (ATP) 集成|**注意**：FastTrack 服务权益可帮助你将 Intune 与 Microsoft Defender ATP 集成，并根据其 Windows 10 风险级别评估创建设备合规性策略。 服务权益不提供购买、许可或激活方面的协助。 |
|Windows Autopilot|IT 管理员负责通过让硬件供应商代表他们上载其硬件 ID 或自己将其上载到 Windows Autopilot 服务中来向其组织注册设备。 |
|使用 Intune 安全地部署 Outlook for iOS 和 Outlook for Android|<br /><br />-   在 Azure AD for Office 365 中启用的用户标识。<br />-   配置有已分配的用户许可证的 Exchange Online 或混合 Exchange。<br />|
|Azure 信息保护（P2 或 EMS E5）|<br /><br />客户应该已经： <br /> - 使用 Azure AD。<br />- 使用 Windows 或 iOS（其他操作系统超出范围）。<br /> - 使用不依赖 Office 作为主客户端的比 Office 2010 SP2 更高版本的 Office 客户端。 <br /> - 具有他们的主文件共享位置。  <br /> - 已从 Active Directory 权限管理服务 (AD RMS) 升级。 <br /> - 具有已批准的分类的分类法。 <br /> - 了解针对其受保护密钥管理的任何监管限制。 <br />|
|Azure 信息保护扫描程序|<br /><br /> 客户应该已经： <br /> - 使用 Windows Server 2012 R2 或 Windows Server 2016。<br /> - 具有 Internet 连接。 <br /> - 在本地或远程实例中安装了 Microsoft SQL Server 2012 或更高版本。  <br /> - 为其本地 Active Directory 创建了服务帐户，并已与 Azure AD 同步。  <br /> - 已下载 AzInfoProtection.exe。 <br /> - 已为自动分类/保护配置了标签。<br />|

> [!NOTE]
> **想了解更多信息？**
> [企业移动性 + 安全性](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>后续步骤

[适用于 EMS 的 FastTrack 中心权益的载入阶段](EMS-onboarding-phases.md)

