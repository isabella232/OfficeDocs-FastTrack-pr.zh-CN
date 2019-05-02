---
title: 源环境预期
description: 对 EMS 使用 FastTrack 中心权益的源环境要求
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: a512e97f48df7fc3040478f4e35fe0c357ef7ce3
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513147"
---
# <a name="source-environment-expectations"></a>对源环境的预期

使用[适用于企业移动性 + 安全性 (EMS) 的 FastTrack 中心权益](EMS-fasttrack-benefit-for-EMS.md)获取 Microsoft Azure Active Directory Premium、Microsoft Intune 和 Azure 信息保护时, 您的环境需要满足预期以下各节中所述。

您可能已在组织中具有内部部署 Active Directory, 您希望将其与企业移动性 + 安全性 (EMS) 或从单个控制台使用丰富的身份管理的任何单个服务集成在一起。 企业移动性 + 安全性 (EMS) 的 FastTrack 中心权益包括帮助您将 Azure Active Directory 与您现有的本地 Active Directory 环境集成。

下表显示了对现有源环境的预期。

|活动|对源环境的预期|
|------------|----------------------------------|
|内核补|将功能林级别设置为 Windows Server 2008 或更高版本的 Active Directory 林, 具有以下林配置:<br /><br />-单个 Active Directory 林<br />-多个 Active Directory 林 </br></br>**注意**: 对于所有的多林配置, Active Directory 联合身份验证服务 (AD FS) 部署超出了 FastTrack 中心权益的范围。|
|Azure AD Premium 补接|已为 Azure AD Premium 准备内部部署 Active Directory 及其环境, 其中包括对阻止与 Azure AD 和 Azure AD 高级功能集成的已确定问题的补救措施。|
|Intune 入职| 在计划使用 Intune 部署 WiFi 和 VPN 配置文件时, IT 管理员需要具有已在其生产环境中工作的现有证书颁发机构、WiFi 和 VPN 基础结构。<br /><br /> **注意**: 服务权益不包括设置或配置证书颁发机构、WIFI、VPN 基础结构或 Apple MDM push 证书的帮助  |
|Comanagement|使用 Comanagement IT 管理员负责准备本地环境, 其中可能包括一些问题的补救措施, 这些问题会妨碍您同时使用 Configuration Manager 和 Intune 管理 Windows 10 设备。<br /><br />**注意**: FastTrack 服务权益不包括将 configuration manager 站点服务器和/或 configuration manager 客户端设置或升级到支持 Windows 10 设备的 Comanagement 所需的最低要求的帮助。 |
|与 Windows Defender 高级威胁防护集成的 Intune (Windows Defender ATP)|您的 Windows Defender ATP 订阅已根据贵公司的安全要求而激活和配置。<br /><br />**注意**: FastTrack 服务优势提供了有关将 Intune 与 WINDOWS Defender ATP 集成在一起的帮助, 以及如何基于其 Windows 10 风险级别评估创建设备合规性策略。 FastTrack 服务优势不提供有关购买、许可、激活或使用 Windows Defender ATP 及其安全中心控制台的帮助。 |
|Windows Autopilot|IT 管理员负责将其设备注册到其组织, 方法是让硬件供应商代表自己上载其硬件 Id, 或将自己上载到 Windows Autopilot 服务中。 |
|使用 Intune 安全地部署 Outlook for iOS 和 Android|<br /><br />-在 Azure AD for Office 365 中启用的用户标识。<br />-使用分配了用户许可证的 Exchange Online 或混合 Exchange 配置。<br />|
|Azure 信息保护 (P2 或 EMS E5)|<br /><br />客户应已执行以下操作: <br /> -使用 Azure AD。<br />-使用 Windows 或 iOS (其他 OSs 不在范围内)。<br /> -使用比不依赖 Office Online 作为主客户端的 Office 2010 SP2 新的 Office 客户端。 <br /> -具有其主文件共享位置。  <br /> -已从 Active Directory 权限管理服务 (AD RMS) 升级。 <br /> -具有已批准的分类分类。 <br /> -了解针对其受保护密钥管理的任何法规限制。 <br />|
|Azure 信息保护扫描程序|<br /><br /> 客户应已执行以下操作: <br /> -使用 Windows Server 2012 R2 或 Windows Server 2016。<br /> -具有 internet 连接。 <br /> -在本地或远程实例中安装 Microsoft SQL Server 2012。  <br /> -为其本地 Active Directory 创建了一个服务帐户, 并将其与 Azure AD 同步。  <br /> -已下载 Azinfoprotection.exe。 <br /> -为自动分类/保护配置标签。<br />|

> [!NOTE]
> **想要了解更多信息？**
> [企业移动性 + 安全性](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>后续步骤

[EMS 载入阶段的 FastTrack 中心权益](EMS-onboarding-phases.md)
