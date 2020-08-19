---
title: 载入阶段
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: Windows 10 载入分为四个主要阶段：启动、评估、修正和启用。
ms.openlocfilehash: 5781c71ee9748579097adc1a0ea103e7dc64945d
ms.sourcegitcommit: 1b2242be54dd0d000c6384f45f18e1951c31998b
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/18/2020
ms.locfileid: "46800676"
---
# <a name="onboarding-phases"></a>载入阶段

> [!CAUTION]
> 此内容已不再是最新的，并计划删除。 对当前内容使用左侧导航栏中的目录。

Windows 10 载入分为四个主要阶段：启动、评估、修正和启用。

## <a name="initiate"></a>启动

在此阶段，我们会讨论载入过程、验证您的数据并安排启动会议。 这包括与你一起了解 Windows 10 目标。

## <a name="assess"></a>评估

FastTrack 专家与你一起评估你的源环境和需求。 确保 Microsoft Endpoint Configuration Manager 升级到所需级别，以便支持 Windows 10 部署。 

我们为你提供用于评估 Windows 10 应用的推荐选项。 FastTrack 提供桌面分析使用指南，还引导你创建桌面分析部署计划。

FastTrack 还可指导你利用 Configuration Manager 中的 Office 365 准备仪表板或使用 Office 的独立准备情况工具包进行 Microsoft 365 应用版兼容性评估。 有关可用服务的详细信息，请参阅[适用于 Office 365 的 FastTrack 中心权益](O365-fasttrack-benefit-for-office-365.md)。 

FastTrack 还会为你评估新式管理策略，包括将 Configuration Manager 云附加到 Microsoft Intune，或者将 Intune 部署为唯一的云管理解决方案。

## <a name="remediate"></a>修正

您基于您的源环境执行修正任务，以便您满足载入的要求。 我们提供了准备环境和验证这些元素是否就绪的修正计划，使你的源环境达到成功部署的最低要求。 

## <a name="enable"></a>启用

FastTrack 提供将现有设备升级到 Windows 10 企业版的指导，只要它们满足所需的设备硬件要求。 提供升级指南以支持现有部署运动。 FastTrack 推荐并提供有关就地升级到 Windows 10 的指南。 指南还可用于 Windows 干净图片安装和 [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot) 部署方案。 

我们提供了在 Windows 10 部署过程中使用 Configuration Manager 部署 Microsoft 365 应用版的指导。 请参阅 [Microsoft 365 应用版](O365-onboarding-and-migration.md#microsoft-365-apps)了解相关服务的更多详情。

我们提供指导，帮助你的组织使用现有 Configuration Manager 环境或 Microsoft 365 保持最新的 Windows 10 企业版和 Microsoft 365 应用版。

如果需要，FastTrack 可指导客户通过将 Configuration Manager 云附加到 Intune 或单独部署 Intune 来启用新式管理。 有关相关服务的详细信息，请参阅[适用于企业移动性 + 安全性 (EMS) 的 FastTrack 中心权益流程](EMS-fasttrack-process.md)。

> [!NOTE]
> 如果没有现有的部署和维护计划或流程，我们可以根据就地升级方案（推荐）或 [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot) 提供最佳做法指南。

## <a name="out-of-scope"></a>超出范围

FastTrack 不会提供以下指南：

- 将 Configuration Manager 升级到当前分支。
- 创建适用于 Windows 10 部署的自定义映像。
- 创建和支持 Windows 10 部署的部署脚本。
- 将 Windows 10 系统从 BIOS 转换为统一可扩展固件接口 (UEFI)。
- 启用 Windows 10 安全功能。 
- 配置用于启动前执行环境 (PXE) 启动的 Windows 部署服务 (WDS)。
- 使用 Microsoft 部署工具包 (MDT) 捕获和部署 Windows 10 映像。
- 使用用户状态迁移工具 (USMT)。

  > [!NOTE]
  > 请联系 [Microsoft 合作伙伴](https://go.microsoft.com/fwlink/?linkid=2080150)，以提供超出范围服务方面的帮助。

 