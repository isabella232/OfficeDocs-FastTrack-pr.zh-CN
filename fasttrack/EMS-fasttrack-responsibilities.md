---
title: FastTrack 责任
description: 当客户对 EMS 使用 FastTrack 中心权益时的 FastTrack 责任
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 05/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 9b766eea35cb1c22906bf68733c1b19471858fb9
ms.sourcegitcommit: ccdd833af651980ea6ac655bf32b4262474b35d4
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/01/2019
ms.locfileid: "33513831"
---
# <a name="fasttrack-responsibilities"></a>FastTrack 责任

在载入过程中, FastTrack 具有以下职责。

## <a name="general"></a>概要

-   向您提供远程支持协助, 以获取详细阶段说明中列出的必需配置活动。

-   提供可用的文档、软件工具和管理控制台, 以帮助您减少或消除配置任务。

## <a name="initiate-phase"></a>启动阶段

-   与您合作以开始加入。

-   定义您需要初始启用的符合条件的服务。

## <a name="assess-phase"></a>评估阶段

-   提供管理概述。

-   针对以下内容提供相关指导：

    -   DNS、网络和基础结构需求。

    -   客户端需求 (Internet 浏览器、客户端操作系统和服务需求)。

    -   用户标识和设置。

    -   启用已购买并定义为加入的符合条件的服务。

-   制定修正活动的日程表。

-   为 Intune 和 Azure AD Premium 提供修补程序清单。

## <a name="remediate-phase"></a>修正阶段

-   根据已商定的计划来召开会议呼叫, 以查看补救活动的进度, 例如, 引导您在预安装 Microsoft 云服务之前安装必备组件。

## <a name="enable-phase"></a>启用阶段
针对以下内容提供相关指导：

-   激活你的 Microsoft online 服务租户或订阅。

-   配置 TCP/IP 协议和防火墙端口。

-   为符合条件的服务配置 DNS。

-   验证与 Microsoft online services 的连接。

-   对于单林环境:

    -   在 Active Directory 域服务 (AD DS) 和符合条件的 Microsoft online services 之间安装目录同步服务器 (仅在需要时提供指导)。

    -   使用 Azure Active Directory Connect 工具配置托管身份验证 (密码哈希同步或传递身份验证)。 (仅在需要时提供指导)。

        > [!NOTE]
        > 自定义规则扩展的开发和实现不在范围内。

-   在目标为联合身份的情况下, 对于单个林: 如果需要, 在单站点的容错配置中安装和配置 Active Directory 联合身份验证服务 (AD FS) 以使用 Intune 进行本地域身份验证。

    > [!NOTE]
    > 对于所有的多林配置, AD FS 部署不在作用域内。

-   测试单一登录 (SSO) 功能 (如果已部署)。

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>启用阶段-Microsoft Azure Active Directory Premium

针对以下内容提供相关指导：

- 激活你的 Azure AD Premium 租户。

- 配置防火墙端口。

- 为符合条件的服务配置 DNS。

- 验证与 Azure AD Premium 服务的连接。

- 对于单林环境:

  -   如果需要, 在 Active Directory 域服务 (AD DS) 和 Azure AD Connect 之间安装目录同步。

  -   使用 Azure AD Connect 工具配置身份验证方法 (密码哈希同步或传递身份验证)。

- 对于多林环境:

  -   安装 Azure AD Connect 同步, 为多林方案设置。
- 对于单林和多林环境：
  - 根据需要，配置 Azure Active Directory 直通身份验证。
  - 根据需要，配置 Azure Active Directory 无缝单一登录 (SSO)。
    > [!NOTE]
    > 如果 Active Directory 林之间存在林信任且名称后缀路由配置正确，则支持为多林环境配置 Azure Active Directory 直通身份验证。 可以在多个本地服务器上安装其他代理，提供登录请求所需的高可用性。

  - 有关详细信息，请参阅 [Azure Active Directory 直通身份验证：快速入门](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites)和 [Azure Active Directory 无缝单一登录：快速入门](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites)。
  - 若要详细了解直通身份验证限制，请参阅 [Azure Active Directory 直通身份验证：当前限制](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations)。
  - 若要详细了解无缝 SSO 问题，请参阅[排除 Azure Active Directory 无缝单一登录故障](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso)。

      > [!NOTE]
      > 密码哈希同步和密码写回支持多个林。 但是, 不支持其他写回方案。

  - 配置本地 Active Directory 林与 Microsoft Azure Active directory 高级目录之间的同步 (Azure Active Directory)。

    > [!NOTE]
    > 自定义规则扩展的开发和实现不在范围内。

- 对于单个林, 当目标为联合身份时:

  -   在单一站点、容错配置 (如果需要) 中为使用 Azure AD Premium 的本地域身份验证安装和配置 AD FS。

  > [!NOTE]
  > 对于所有的多林配置, AD FS 部署不在作用域内。

- 测试 SSO 功能 (如果已部署)。

### <a name="enable-phase---azure-ad-premium--with-azure-ad-connect-and-ad-fs"></a>启用阶段-Azure AD Premium--Azure AD Connect 和 AD FS

提供有关设置的指导:

- 用户预配, 包括许可。

- Azure AD Connect directory 同步 (使用密码写回和密码哈希同步)。

  - Azure Active Directory 自助服务密码重置 (SSPR)。

  - Azure 多因素身份验证。

  - 最多三台 (3) 或更多软件即服务 (SaaS) 应用程序集成, 使用来自[Azure Active Directory 市场](https://azure.microsoft.com/marketplace/active-directory/)的单一登录 (SSO)。

  - 在[应用集成教程列表](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/tutorial-list)中列出的预集成 SaaS 应用程序的自动用户预配, 仅限于出站预配。

  - 自定义登录屏幕, 包括徽标、文本和图像。

  - 自助服务和动态组 (组)。

  - Azure Active Directory 应用程序代理。

  - Azure Active Directory Connect Health。

  - Azure Active Directory 条件访问。

  - Azure Active Directory 使用条款。

  - Azure Active Directory 标识保护。

  - Azure Active Directory 的特权标识管理。

  - Azure Active Directory 访问检查。

### <a name="enable-phase---intune"></a>启用阶段-Intune

> [!IMPORTANT]
> FastTrack 不支持使用 Intune 的 Windows 10 经典电脑管理。 FastTrack 仅支持通过 Intune 移动设备管理 (MDM) 进行 Windows 10 管理。

提供有关以下内容的**指导**:

-   通过利用本地 Active Directory 或云标识 (Azure Active Directory) 配置由 Intune 使用的标识。

-   许可最终用户。

-   将用户添加到 Intune 订阅、定义 IT 管理员角色以及创建用户和设备组。

-   根据您的管理需求配置移动设备管理 MDM) 证书颁发机构, 其中包括:

    -   将 Intune 设置为你的 MDM 颁发机构。

    -   配置用于验证 MDM 管理策略的测试组。

    -   导航 Intune 管理门户以查找有关用户和设备的信息。

    -   设置 Intune 角色 (技术支持运营商、管理员等)

    -   配置 MDM 管理策略和服务, 如:

        -   通过 web 链接、MSI 和/或深层链接针对每个受支持的平台的应用程序部署。

        -   将 Office 专业增强版部署到 Windows 10 设备上。

        -   适用于应用程序部署的批量购买计划, 包括 Apple 的 VPP、适用于企业的 Windows 应用商店和 Google 的工作商店重头戏。

        -   如果您的组织中有现有的证书颁发机构、Wlan 或 VPN 基础结构, 则部署电子邮件、无线网络和 VPN 配置文件。

        -   设置 Microsoft Intune Exchange Connector (如果适用)。

        -   受支持的设备平台的设备配置文件。

    -   设置条件访问策略。

    -   为每个受支持的平台配置和部署 Intune 应用保护策略。

    -   为 Intune 应用保护策略准备业务线 (LOB) 应用程序, 并提供可用选项的指导。

    -   使用 Microsoft Intune 服务将每个受支持平台的设备注册到 Intune 或配置管理器。

    -   连接到 Intune 数据仓库。

    -   将 Intune 与以下项集成:
        -   用于远程协助的团队查看器 (需要团队查看器订阅)。

        -   移动威胁防护合作伙伴解决方案 (需要移动威胁防护合作伙伴解决方案订阅)。

        -   电信费用管理解决方案 (需要电信费用管理解决方案订阅)。

        -   Windows Defender 高级威胁防护 (Windows E5 或 Microsoft 365 E5 许可证是必需的)。

    -   为适用的受支持平台配置软件更新。

    -   用于用户采用规划的资源。

- 设置 Windows Autopilot:

    - 为 Windows Autopilot 配置和设置 Microsoft Intune。

    - 配置 Azure AD 动态组

    - 将公司品牌添加到 Azure AD 中。

    - 创建设备并将其分配给 Windows Autopilot 配置文件 (例如, 限制本地管理员帐户创建的 Windows Autopilot 配置文件)。

    - 自定义现成体验 (OOBE) 以符合组织的要求。

    - 在 Azure AD 和 Intune 中配置 MDM 自动注册。

    > [!NOTE]
    > 设置 Windows Autopilot 外部 Intune 不在 FastTrack 权益范围之外。

### <a name="enable-phase---co-management"></a>启用阶段-共同管理

针对以下内容提供相关指导：

-   许可最终用户。

-   将用户添加到 Intune 订阅、定义 IT 管理员角色以及创建用户和设备组 (如果未安装 Intune)。

-   为 MDM 自动注册设置 Azure Active Directory。

-   设置混合 Azure Active Directory 加入。

-   设置云管理网关。

-   将用户添加到 Intune 订阅、定义 IT 管理员角色以及创建用户和设备组。

-   准备 Intune (如果未安装 Intune):

    -   根据您的管理需求配置移动设备管理 MDM) 证书颁发机构, 其中包括:

    -   将 Intune 设置为你的 MDM 颁发机构。

    -   配置用于验证 MDM 管理策略的测试组。

    -   导航 Intune 管理门户以查找有关用户和设备的信息。

    -   设置 Intune 角色 (技术支持运营商、管理员等)

    -   为每个受支持的平台配置和部署 Intune 应用保护策略。

    -   将 Windows 10 设备注册到 Intune。

- 在 Configuration Manager 控制台中启用联合管理。

- 将工作负荷切换到 Intune。

- 监视环境中的联合管理活动。

### <a name="enable-phase--azure-information-protection"></a>启用阶段– Azure 信息保护

提供以下支持: 

- 客户能够在 Windows 上运行的 Office 应用程序 (如 Word、PowerPoint、Excel 和 Outlook) 中自动分类和标记信息, 并使用 Azure 信息保护客户端。 
- 使用 Azure 信息保护扫描程序的 rest 文件。
- 使用 Exchange Online 邮件流规则的传输中的电子邮件。 

此外, 还向希望使用 Microsoft Azure 权限管理服务 (Azure RMS)、Office 365 邮件加密 (OME) 和数据丢失防护 (DLP) 应用保护的客户提供支持。 

向客户提供有关如何执行以下操作的指南: 

- 激活并配置其租户。
- 创建和设置标签和策略。
- 对文档应用信息保护。 

> [!NOTE]
> **想要了解更多信息？** 请参阅[企业移动性 + 安全性](https://www.microsoft.com/cloud-platform/enterprise-mobility)。

## <a name="next-steps"></a>后续步骤

[FastTrack 为 EMS 带来的好处-你的责任](EMS-your-responsibilities.md)
