---
title: 附录 A：从 IBM Domino 迁移到 Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 10/02/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: 从 IBM Domino 迁移到 Exchange Online 包括几个重要方面，其中包括在以下阶段中发生的情况：
ms.openlocfilehash: 84e861794f540689c948762aedc2dee4fa54021b
ms.sourcegitcommit: 06eb1378c0f3601ca6909765ecacbff23db7e71f
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/01/2019
ms.locfileid: "37342207"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a>附录 A - 从 IBM Domino 迁移到 Exchange Online

从 IBM Domino 迁移到 Exchange Online 包括几个重要方面，其中包括在以下阶段中发生的情况： 
- [启动阶段](#initiate-phase)   
- [评估阶段](#assess-phase)
- [修正阶段](#remediate-phase)  
- [启用阶段](#enable-phase)  
- [迁移阶段](#migrate-phase)
    
## <a name="identities"></a>标识

你负责创建和管理标识（仅限云，与其本地 Active Directory 同步或联合）。 在载入的早期阶段，你必须在 Domino 和本地 Active Directory 或 Azure Active Directory 之间完成标识映射（如果不存在）。
  
## <a name="coexistence"></a>共存

适用于 Office 365 的 FastTrack 中心权益向所有客户提供本地 Domino 环境与 Exchange Online 之间的双向邮件流。
  
## <a name="migration"></a>迁移

从 Domino 迁移到 Exchange Online 的标准 FastTrack 中心过程包括，在迁移到 Exchange Online 邮箱之前将 Domino 数据预暂存到 Azure。 FastTrack 迁移需要由 FastTrack 中心人员和客户在载入的不同阶段执行活动。以下各部分概述了这些活动。
  
> [!NOTE]
> 可在美国或 Microsoft 维护其设备的任何地方转移、存储和处理通过 FastTrack 服务迁移的数据。FastTrack 服务并非为满足特殊法律或法规要求的数据而设计或以此为目的。 
  
## <a name="initiate-phase"></a>启动阶段

 **关键操作**
  
- 将 Domino 标识为源邮件平台。   
- 确定 FastTrack 中心是否执行迁移。
    
 **客户责任**
  
- 提供有关源邮件平台的基本信息，并与 FastTrack 中心确认迁移意向。 
- 参与 FastTrack 中心权益流程的演练。  
- 签署 FastTrack 服务协议。
    
## <a name="assess-phase"></a>评估阶段

 **关键操作**
  
- FastTrack 中心 安排与客户之间的迁移研讨会。 
- 您已完成迁移必备项，如迁移调查表和预配管理工作站。    
- 在您的本地环境中执行 Domino 的迁移评估。
    
 **客户责任**
  
- FastTrack 中心用于管理载入和迁移任务的预配管理工作站，如迁移过程中的评估、副本创建、审核、设置转发等。
    > [!NOTE]
    > 评估是成功规划和执行快速迁移的关键。它由需要 Domino 环境的特定访问权限的迁移架构师执行。需要的管理员工作站组件包括已配置为可以访问所有源 Domino 邮件服务器和 Azure Domino 副本暂存服务器的 Notes 客户端。 
- 提供迁移团队对管理工作站和帐户的远程访问权限以及执行评估和迁移活动的权限。这包括在本地和具有迁移所需的管理权限的 Exchange Online 中预配多个帐户。    
- 打开防火墙端口。出站端口必须在源 Domino 邮件服务器和 Azure 暂存服务器之间打开。其他通信端口（如管理工作站、源 Domino 服务器和本地 Exchange 服务器（如果有））也必须打开。 
- 启用源 Domino 环境和 Azure Domino 暂存服务器之间的交叉证书以进行复制。交叉认证任务在客户的 Domino 管理员和 FastTrack 中心之间协调。  
- 完成迁移调查表，以便捕获在 Azure 中配置迁移环境所需的信息（如工具、脚本和迁移服务器）。   
- 确保 Office 365 中的目标邮箱已启用消息应用程序接口 (MAPI) 协议。  
> [!NOTE]
> 一些 Office 365 计划不支持 MAPI 协议。必须在迁移事件发生前将使用这些计划的邮箱转换为支持 MAPI 的计划，才能迁移数据。迁移后，可以恢复这些计划。 
  
## <a name="remediate-phase"></a>修正阶段

 **关键操作**
  
- FastTrack 中心审查迁移评估报告并测试你使用调查表提供的详细信息。   
- FastTrack 中心建议的修正项必须由您亲自完成。
    
 **客户责任**
  
- 基于 FastTrack 中心提供的准则修正 Domino 环境（例如，设置邮件文件中标记为缺失的任何必需的权限）。  
- 确保 Domino 邮箱的大小低于通过迁移允许的最大大小。
    > [!NOTE]
    >  虽然 FastTrack 会迁移达到允许总目标大小的 85% 的邮箱，但是尝试迁移大小超过 2GB 的邮箱会带来额外的风险，如：    <br/> 迁移的持续时间延长。    <br/> 转为使用用于迁移其他邮箱的资源。    <br/> 错误率大幅提升。 
- 准备邮件内数据库及其访问控制列表 (ACL)，以便进行迁移。必须执行一些修正步骤，才能将邮件内数据库及其权限成功迁移到 Exchange Online 中的共享邮箱。其中一些步骤如下： 
  - 删除 Domino 目录中现有的邮件内数据库条目，并创建新的人员记录。
  - 在同步到 Office 365 Azure Active Directory 且用于在 Exchange Online 中的共享邮箱上配置权限的本地 Active Directory 中创建已启用邮件的通用安全组。 这将在邮件内数据库上设置的权限转移到 Exchange Online 中的共享邮箱。
    
> [!NOTE]
> 现在即可开始新邮件系统和客户端的最终用户准备工作和培训。 
  
## <a name="enable-phase"></a>启用阶段

 **关键操作**
  
- FastTrack 中心： 
    - 在 Azure 中设置迁移环境。  
    - 在本地管理工作站中配置迁移工具。 
    - 配置和演示如何使用自动导入工具。  
    - 验证所有迁移组件，并执行测试迁移。
    
 **客户责任**
  
- 负责安排邮箱迁移的人员必须了解如何使用自动导入工具。可以使用此工具将迁移计划导入到调度数据库中，FastTrack 中心使用该数据库执行迁移前活动。 
- 执行迁移前活动，如导入用户计划、分析审核报告、修正任何问题以及重新导入有问题的用户帐户。
    
迁移前活动在你与 FastTrack 中心之间协调。导入用户迁移计划后，开始复制到 Azure。 
    
> [!NOTE]
> 复制所需的时间取决于数据量。然后，FastTrack 中心执行审核以确定迁移准备情况。审核结果会提供给你，以便你了解正常所需的后续修正。所有这些步骤被称为"倒计时"活动，因为它们必须在用户的计划迁移之前开始。 
  
## <a name="migrate-phase"></a>迁移阶段

 **关键操作**
  
- FastTrack 中心：
    - 执行试点迁移和快速迁移。  
    - 执行迁移事件和倒计时活动。
    - 提供迁移后协助。
    
 **客户责任**
  
- 迁移之前 21 天确定并导入迁移计划。
    > [!NOTE]
    > 此任务非常重要，因为迁移前活动涉及在实际迁移日 (T-0) 之前的不同阶段对副本创建进行的修正和可能的重试。一些邮箱正在迁移时，倒计时活动将在其他邮箱上执行。这使适当的规划和协调必不可少。 
- 修复在倒计时活动执行过程中发现的问题。
- 解决和修复影响迁移活动的所有 Domino 服务器问题。 
- 与最终用户沟通即将到来的迁移日期的相关事宜。
- 开展新邮件系统和客户端的最终用户准备活动和培训。   
- 识别并报告迁移后问题。FastTrack 中心在迁移完成后的 T+5 天内提供迁移后支持，在这个时间之后将由你亲自负责。你可以记录迁移后票证来记录问题，如：缺少电子邮件、日历项目和联系人，或者记录邮箱中的重复项。
    
FastTrack 中心不涉及部署、许可费或与目录准备相关的协助（包括 Domino 到 Active Directory 的目录同步），适用于 Notes 应用程序互操作性的共存软件附加设备、自助服务迁移或存档迁移。
  

  

