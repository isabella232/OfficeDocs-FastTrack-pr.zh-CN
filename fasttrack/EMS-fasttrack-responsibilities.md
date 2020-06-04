---
title: FastTrack 责任
description: 在客户使用适用于 EMS 的 FastTrack 中心权益时，FastTrack 的责任
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
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 62ed549ea78146541d0d4a2d860f02b15c02f44f
ms.sourcegitcommit: 826f140cc0ddee32005f74e5d995073af1dc3fa2
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 06/02/2020
ms.locfileid: "44471713"
---
# <a name="fasttrack-responsibilities"></a>FastTrack 责任

FastTrack 在载入过程中将承担以下责任。

## <a name="general"></a>概要

-   为你提供远程支持协助，帮助你完成详细阶段说明中所列出的相应配置活动。

-   提供可用的文档、软件工具和管理控制台，以帮助你减少或消除配置任务。

## <a name="initiate-phase"></a>启动阶段

-   与你共同启动载入。

-   定义您需要初始启用的符合条件的服务。

## <a name="assess-phase"></a>评估阶段

-   提供管理概述。

-   针对以下内容提供相关指导：

    -   DNS、网络和基础结构需求。

    -   客户端需求（Internet 浏览器、客户端操作系统和服务需求）。

    -   用户标识和设置。

    -   使已购买且定义的符合条件的服务纳入载入的范围。

-   制定修正活动的日程表。

-   提供 Intune 和 Azure AD Premium 的修正清单。

## <a name="remediate-phase"></a>修正阶段

-   根据商定的日程安排与你举行电话会议，以审查修正活动的进度，例如，指导你在载入 Microsoft 云服务之前完成安装先决条件。

## <a name="enable-phase"></a>启用阶段
针对以下内容提供相关指导：

-   激活 Microsoft 联机服务租户或订阅。

-   配置 TCP/IP 协议和防火墙端口。

-   为符合条件的服务配置 DNS。

-   验证与 Microsoft 联机服务的连接。

-   对于单个林环境：

    -   在 Active Directory 域服务 (AD DS) 和符合条件的 Microsoft 联机服务之间安装目录同步服务器（仅在需要时提供指导）。

    -   使用 Azure Active Directory Connect 工具配置托管身份验证（密码哈希同步或直通身份验证）。 （仅在需要时提供指导）。

        > [!NOTE]
        > 开发和实现自定义规则扩展超出范围。

-   对于单个林，当目标是联合标识时：必要时，安装和配置 Active Directory 联合身份验证服务 (AD FS)，以供在单个站点的容错配置中对 Intune 进行本地域身份验证。

    > [!NOTE]
    > 对于所有多个林配置，AD FS 部署不在此范围内。

-   测试单一登录 (SSO) 功能（如果已部署）。

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>启用阶段 - Microsoft Azure Active Directory Premium

针对以下内容提供相关指导：

- 激活 Azure AD Premium 租户。

- 配置防火墙端口。

- 为符合条件的服务配置 DNS。

- 验证 Azure AD Premium 服务的连接。

- 对于单个林环境：

  -   必要时，在 Active Directory 域服务 (AD DS) 和 Azure AD Connect 之间安装目录同步。

  -   使用 Azure AD Connect 工具配置身份验证方法（密码哈希同步或直通身份验证）。

- 对于多个林环境：

  -   安装 Azure AD Connect 同步，为多个林设置方案。
- 对于单林和多林环境：
  - 根据需要，配置 Azure Active Directory 直通身份验证。
  - 根据需要，配置 Azure Active Directory 无缝单一登录 (SSO)。
    > [!NOTE]
    > 如果 Active Directory 林之间存在林信任且名称后缀路由配置正确，则支持为多林环境配置 Azure Active Directory 直通身份验证。 可以在多个本地服务器上安装其他代理，提供登录请求所需的高可用性。

  - 有关详细信息，请参阅 [Azure Active Directory 直通身份验证：快速入门](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites)和 [Azure Active Directory 无缝单一登录：快速入门](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites)。
  - 若要详细了解直通身份验证限制，请参阅 [Azure Active Directory 直通身份验证：当前限制](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations)。
  - 若要详细了解无缝 SSO 问题，请参阅[排除 Azure Active Directory 无缝单一登录故障](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso)。

      > [!NOTE]
      > 密码哈希同步和密码回写支持多个林。 但是，不支持其他写回方案。

  - 配置本地 Active Directory 林和 Microsoft Azure Active Directory Premium 目录（Azure Active Directory）之间的同步。

    > [!NOTE]
    > 开发和实现自定义规则扩展超出范围。

- 对于单个林，当目标是联合标识时：

  -   安装和配置 AD FS，以供在单个站点的容错配置中对 Azure AD Premium 进行本地域身份验证（如果需要）。

  > [!NOTE]
  > 对于所有多个林配置，AD FS 部署不在此范围内。

- 测试 SSO 功能（如果已部署）。

### <a name="enable-phase---azure-ad-premium---with-azure-ad-connect-and-ad-fs"></a>启用阶段 - Azure AD Premium - 使用 Azure AD Connect 和 AD FS

提供有关设置的指导：

- 用户预配（包括许可）。

- Azure AD Connect 目录同步（使用密码写回和密码哈希同步）。

  - Azure Active Directory 自助密码重置 (SSPR)。

  - Azure 多重身份验证。

  - 在 [Azure Active Directory 应用商店](https://azure.microsoft.com/marketplace/active-directory/)中，通过单一登录 (SSO) 实现高达三 (3) 个或更多软件即服务 (SaaS) 应用程序集成。

  - 针对[应用集成教程列表](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list)中列出的预集成 SaaS 应用程序进行自动用户预配，仅限于出站配置。

  - 自定义登录屏幕，包括徽标、文本和图像。

  - 自助服务和动态组（组）。

  - Azure Active Directory 应用程序代理。

  - Azure Active Directory Connect Health。

  - Azure Active Directory 条件访问。

  - Azure Active Directory 使用条款。

  - Azure Active Directory Identity Protection。

  - Azure Active Directory Privileged Identity Management。

  - Azure Active Directory 访问审查。

  -   Azure Active Directory 密码保护。

  -   Azure Active Directory B2B。

### <a name="enable-phase---intune"></a>启用阶段 - Intune

> [!IMPORTANT]
> FastTrack 不支持通过 Intune 进行 Windows 10 经典电脑管理。 FastTrack 仅支持通过 Intune 移动设备管理 (MDM) 进行 Windows 10 管理。

针对以下内容提供相关指导：

-   通过利用本地 Active Directory 或云标识 (Azure Active Directory)，配置供 Intune 使用的标识。

-   许可最终用户。

-   将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。

-   根据管理需求配置移动设备管理 (MDM) 颁发机构，包括：

    -   将 Intune 设置为 MDM 颁发机构。

    -   配置用于验证 MDM 管理策略的测试组。

    -   浏览 Intune 管理门户以查找有关用户和设备的信息。

    -   设置 Intune 角色（帮助台操作员、管理员等）

    -   配置 MDM 管理策略和服务，如：

        -   通过 Web 链接、MSI 和/或深度链接为每个受支持的平台部署应用。

        -   将 Office 专业增强版部署到 Windows 10 设备。

        -   用于应用部署的批量购买程序，包括 Apple 的 VPP、适用于企业的 Windows 应用商店和 Google 的 Play for Work 应用商店。

        -   部署电子邮件、无线网络和 VPN 配置文件（如果你的组织中具有现有证书颁发机构、Wi-Fi 或 VPN 基础结构）。

        -   设置 Microsoft Intune Exchange 连接器（如果适用）。

        -   受支持的设备平台的设备配置文件。

    -   设置条件访问策略。

    -   为每个受支持的平台配置和部署 Intune 应用保护策略。

    -   为 Intune 应用保护策略准备业务线 (LOB) 应用，并提供可用选项的指导。

    -   使用 Microsoft Intune 服务将每个受支持平台的设备注册到 Intune 或配置管理器。

    -   连接到 Intune 数据仓库。

    -   将 Intune 与以下内容进行集成：
        -   用于远程协助的 Team Viewer（需要 Team Viewer 订阅）。

        -   移动威胁防护合作伙伴解决方案（需要移动威胁防护合作伙伴解决方案订阅）。

        -   电信费用管理解决方案（需要电信费用管理解决方案订阅）。

        -   Microsoft Defender 高级威胁防护（需要 Windows E5 或 Microsoft 365 E5 许可证）。

    -   为适用的受支持平台配置软件更新。

    -   用于用户采用计划的资源。

- 设置 Windows Autopilot：

    - 配置和设置用于 Windows Autopilot 的 Microsoft Intune。

    - 配置 Azure AD 动态组

    - 将公司品牌添加到 Azure AD。

    - 创建设备并将其分配给 Windows Autopilot 配置文件（例如限制本地管理员帐户创建的 Windows Autopilot 配置文件）。

    - 定制开箱即用体验 (OOBE) 以符合组织的要求。

    - 在 Azure AD 和 Intune 中配置 MDM 自动注册。

    > [!NOTE]
    > 设置 Windows Autopilot 外部 Intune 超出了 FastTrack 权益范围。

### <a name="enable-phase---cloud-attach"></a>启用阶段 - 云附加

针对以下内容提供相关指导：

-   许可最终用户。

-   在 Configuration Manager 中启用云附加。

-   将用户添加到 Intune 订阅，定义 IT 管理角色并创建用户和设备组（如果未安装Intune）。

-   设置混合的 Azure Active Directory 加入。

-   为 MDM 自动注册设置 Azure Active Directory。

-   设置云管理网关。

-   将 Intune 订阅添加到用户，定义 IT 管理角色并创建用户和设备组。

-   为设备管理准备 Intune 服务。

-   设置移动设备管理 (MDM)权限为 Intune。

-   配置用于验证 MDM 管理策略的测试组。

-   浏览 Intune 管理门户以查找有关用户和设备的信息。

-   设置 Intune 角色（帮助台操作员、管理员等）

-   将 Windows 10 设备注册到 Intune。

-   切换工作负载，以根据需要由 Intune 进行管理。

### <a name="enable-phase--azure-information-protection"></a>启用阶段 - Azure 信息保护

针对以下内容提供相关指导： 

- 激活和配置客户租户。

- 创建和设置标签和策略。

- 向文档应用信息保护。 

- 自动对在 Windows 上运行的 Office 应用（如Word、PowerPoint、Excel 和 Outlook）中的信息进行分类和标记，并使用 Azure 信息保护客户端。

- 使用带有 Azure 信息保护扫描程序的静态文件。

- 使用 Exchange Online 邮件流规则监视传输中的电子邮件。

向希望使用 Microsoft Azure 权限管理服务 (Azure RMS)、Office 365 邮件加密 (OME) 和数据丢失防护 (DLP) 应用保护的客户提供指导。

> [!NOTE]
> **想了解更多信息？** 请参阅[企业移动性 + 安全性](https://www.microsoft.com/cloud-platform/enterprise-mobility)。

## <a name="next-steps"></a>后续步骤

[适用于 EMS 的 FastTrack 权益 - 你的责任](EMS-your-responsibilities.md)

