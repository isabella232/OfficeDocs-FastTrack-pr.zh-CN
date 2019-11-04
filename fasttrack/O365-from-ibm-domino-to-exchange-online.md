---
title: 附录 A：从 IBM Domino 迁移到 Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 11/02/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: 从 IBM Domino 迁移到 Exchange Online 包括几个重要方面，其中包括在以下阶段中发生的情况：
ms.openlocfilehash: 6d45487b1a71cff4205be7e1650ca259d812d241
ms.sourcegitcommit: f8d7e570b60a55c244af0eceb6fbb0e591257f11
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/01/2019
ms.locfileid: "37921530"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a><span data-ttu-id="ee95d-103">附录 A - 从 IBM Domino 迁移到 Exchange Online</span><span class="sxs-lookup"><span data-stu-id="ee95d-103">Appendix A - Migration from IBM Domino to Exchange Online</span></span>

<span data-ttu-id="ee95d-104">从 IBM Domino 迁移到 Exchange Online 包括几个重要方面，其中包括在以下阶段中发生的情况：</span><span class="sxs-lookup"><span data-stu-id="ee95d-104">Migration from IBM Domino to Exchange Online includes several important aspects, including what happens during the following phases:</span></span> 
- [<span data-ttu-id="ee95d-105">启动阶段</span><span class="sxs-lookup"><span data-stu-id="ee95d-105">Initiate phase</span></span>](#initiate-phase)   
- [<span data-ttu-id="ee95d-106">评估阶段</span><span class="sxs-lookup"><span data-stu-id="ee95d-106">Assess phase</span></span>](#assess-phase)
- [<span data-ttu-id="ee95d-107">修正阶段</span><span class="sxs-lookup"><span data-stu-id="ee95d-107">Remediate phase</span></span>](#remediate-phase)  
- [<span data-ttu-id="ee95d-108">启用阶段</span><span class="sxs-lookup"><span data-stu-id="ee95d-108">Enable phase</span></span>](#enable-phase)  
- [<span data-ttu-id="ee95d-109">迁移阶段</span><span class="sxs-lookup"><span data-stu-id="ee95d-109">Migrate phase</span></span>](#migrate-phase)
    
## <a name="identities"></a><span data-ttu-id="ee95d-110">标识</span><span class="sxs-lookup"><span data-stu-id="ee95d-110">Identities</span></span>

<span data-ttu-id="ee95d-111">你负责创建和管理标识（仅限云，与其本地 Active Directory 同步或联合）。</span><span class="sxs-lookup"><span data-stu-id="ee95d-111">You are responsible for creating and managing the identities (cloud only, synchronized, or federated with their on-premises Active Directory).</span></span> <span data-ttu-id="ee95d-112">在载入的早期阶段，你必须在 Domino 和本地 Active Directory 或 Azure Active Directory 之间完成标识映射（如果不存在）。</span><span class="sxs-lookup"><span data-stu-id="ee95d-112">You must complete the mapping of identities (if not already present) between Domino and the on-premises Active Directory or Azure Active Directory during the early stages of onboarding.</span></span>
  
## <a name="coexistence"></a><span data-ttu-id="ee95d-113">共存</span><span class="sxs-lookup"><span data-stu-id="ee95d-113">Coexistence</span></span>

<span data-ttu-id="ee95d-114">适用于 Office 365 的 FastTrack 中心权益向所有客户提供本地 Domino 环境与 Exchange Online 之间的双向邮件流。</span><span class="sxs-lookup"><span data-stu-id="ee95d-114">The FastTrack Center Benefit for Office 365 provides bidirectional mail flow between the on-premises Domino environment and Exchange Online to all customers.</span></span>
  
## <a name="migration"></a><span data-ttu-id="ee95d-115">迁移</span><span class="sxs-lookup"><span data-stu-id="ee95d-115">Migration</span></span>

<span data-ttu-id="ee95d-p102">从 Domino 迁移到 Exchange Online 的标准 FastTrack 中心过程包括，在迁移到 Exchange Online 邮箱之前将 Domino 数据预暂存到 Azure。 FastTrack 迁移需要由 FastTrack 中心人员和客户在载入的不同阶段执行活动。以下各部分概述了这些活动。</span><span class="sxs-lookup"><span data-stu-id="ee95d-p102">The standard FastTrack Center process for migration from Domino to Exchange Online involves pre-staging Domino data to Azure before migration to Exchange Online mailboxes. FastTrack migrations require activities to be performed at different stages of onboarding by FastTrack Center personnel and you. We cover these activities in the following sections.</span></span>
  
> [!NOTE]
> <span data-ttu-id="ee95d-p103">可在美国或 Microsoft 维护其设备的任何地方转移、存储和处理通过 FastTrack 服务迁移的数据。FastTrack 服务并非为满足特殊法律或法规要求的数据而设计或以此为目的。</span><span class="sxs-lookup"><span data-stu-id="ee95d-p103">Data migrated through the FastTrack services may be transferred to, stored, and processed in the United States or anywhere that Microsoft maintains facilities. The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements.</span></span> 
  
## <a name="initiate-phase"></a><span data-ttu-id="ee95d-121">启动阶段</span><span class="sxs-lookup"><span data-stu-id="ee95d-121">Initiate phase</span></span>

 <span data-ttu-id="ee95d-122">**关键操作**</span><span class="sxs-lookup"><span data-stu-id="ee95d-122">**Key actions**</span></span>
  
- <span data-ttu-id="ee95d-123">将 Domino 标识为源邮件平台。</span><span class="sxs-lookup"><span data-stu-id="ee95d-123">Identify Domino as the source mail platform.</span></span>   
- <span data-ttu-id="ee95d-124">确定 FastTrack 中心是否执行迁移。</span><span class="sxs-lookup"><span data-stu-id="ee95d-124">Determine whether the FastTrack Center performs the migration.</span></span>
    
 <span data-ttu-id="ee95d-125">**客户责任**</span><span class="sxs-lookup"><span data-stu-id="ee95d-125">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="ee95d-126">提供有关源邮件平台的基本信息，并与 FastTrack 中心确认迁移意向。</span><span class="sxs-lookup"><span data-stu-id="ee95d-126">Provide basic information about the source messaging platform, and confirm the migration intent with the FastTrack Center.</span></span> 
- <span data-ttu-id="ee95d-127">参与 FastTrack 中心权益流程的演练。</span><span class="sxs-lookup"><span data-stu-id="ee95d-127">Participate in a walkthrough of the FastTrack Center Benefit processes.</span></span>  
- <span data-ttu-id="ee95d-128">签署 FastTrack 服务协议。</span><span class="sxs-lookup"><span data-stu-id="ee95d-128">Sign the FastTrack Services Agreement.</span></span>
    
## <a name="assess-phase"></a><span data-ttu-id="ee95d-129">评估阶段</span><span class="sxs-lookup"><span data-stu-id="ee95d-129">Assess phase</span></span>

 <span data-ttu-id="ee95d-130">**关键操作**</span><span class="sxs-lookup"><span data-stu-id="ee95d-130">**Key actions**</span></span>
  
- <span data-ttu-id="ee95d-131">FastTrack 中心 安排与客户之间的迁移研讨会。</span><span class="sxs-lookup"><span data-stu-id="ee95d-131">The FastTrack Center conducts a migration workshop with the customer.</span></span> 
- <span data-ttu-id="ee95d-132">您已完成迁移必备项，如迁移调查表和预配管理工作站。</span><span class="sxs-lookup"><span data-stu-id="ee95d-132">You complete the migration prerequisites, like the migration questionnaire and the provisioning of admin workstations.</span></span>    
- <span data-ttu-id="ee95d-133">在您的本地环境中执行 Domino 的迁移评估。</span><span class="sxs-lookup"><span data-stu-id="ee95d-133">Migration assessment for Domino is performed in your on-premises environment.</span></span>
    
 <span data-ttu-id="ee95d-134">**客户责任**</span><span class="sxs-lookup"><span data-stu-id="ee95d-134">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="ee95d-135">FastTrack 中心用于管理载入和迁移任务的预配管理工作站，如迁移过程中的评估、副本创建、审核、设置转发等。</span><span class="sxs-lookup"><span data-stu-id="ee95d-135">Provision admin workstations that the FastTrack Center uses to administer onboarding and migration tasks, like assessment, replica creation, auditing, setting forwarding during migration, and so on.</span></span>
    > [!NOTE]
    > <span data-ttu-id="ee95d-p104">评估是成功规划和执行快速迁移的关键。它由需要 Domino 环境的特定访问权限的迁移架构师执行。需要的管理员工作站组件包括已配置为可以访问所有源 Domino 邮件服务器和 Azure Domino 副本暂存服务器的 Notes 客户端。</span><span class="sxs-lookup"><span data-stu-id="ee95d-p104">Assessment is critical for successful planning and execution of velocity migrations. It's performed by a migration architect who needs specific access to the Domino environment. Required admin workstation components include a Notes client configured to access all source Domino mail servers and the Azure Domino replica staging server.</span></span> 
- <span data-ttu-id="ee95d-p105">提供迁移团队对管理工作站和帐户的远程访问权限以及执行评估和迁移活动的权限。这包括在本地和具有迁移所需的管理权限的 Exchange Online 中预配多个帐户。</span><span class="sxs-lookup"><span data-stu-id="ee95d-p105">Provide the migration team remote access to the admin workstations, accounts, and permissions for performing assessment and migration activities. This includes provisioning multiple accounts on-premises and in Exchange Online with administrative permissions needed for migration.</span></span>    
- <span data-ttu-id="ee95d-p106">打开防火墙端口。出站端口必须在源 Domino 邮件服务器和 Azure 暂存服务器之间打开。其他通信端口（如管理工作站、源 Domino 服务器和本地 Exchange 服务器（如果有））也必须打开。</span><span class="sxs-lookup"><span data-stu-id="ee95d-p106">Open firewall ports. Outbound ports must be opened between the source Domino mail servers and the Azure staging server. Other ports for communication (like admin workstations, source Domino servers, and Exchange servers on-premises (if present)) must also must be opened.</span></span> 
- <span data-ttu-id="ee95d-p107">启用源 Domino 环境和 Azure Domino 暂存服务器之间的交叉证书以进行复制。交叉认证任务在客户的 Domino 管理员和 FastTrack 中心之间协调。</span><span class="sxs-lookup"><span data-stu-id="ee95d-p107">Enable cross-certification between the source Domino environment and the Azure Domino staging server to facilitate replication. Cross-certification tasks are coordinated between the customer's Domino admin and the FastTrack Center.</span></span>  
- <span data-ttu-id="ee95d-146">完成迁移调查表，以便捕获在 Azure 中配置迁移环境所需的信息（如工具、脚本和迁移服务器）。</span><span class="sxs-lookup"><span data-stu-id="ee95d-146">Complete the migration questionnaire, which captures information required to configure the migration environment in Azure (like tools, scripts, and migration servers).</span></span>   
- <span data-ttu-id="ee95d-147">确保 Office 365 中的目标邮箱已启用消息应用程序接口 (MAPI) 协议。</span><span class="sxs-lookup"><span data-stu-id="ee95d-147">Ensure target mailboxes in Office 365 have Messaging Application Program Interface (MAPI) protocol enabled.</span></span>  
> [!NOTE]
> <span data-ttu-id="ee95d-p108">一些 Office 365 计划不支持 MAPI 协议。必须在迁移事件发生前将使用这些计划的邮箱转换为支持 MAPI 的计划，才能迁移数据。迁移后，可以恢复这些计划。</span><span class="sxs-lookup"><span data-stu-id="ee95d-p108">Some Office 365 plans don't support MAPI protocol. In order to migrate data, mailboxes from these plans need to be converted to a plan that supports MAPI ahead of the migration event. Following migration, these plans can be changed back.</span></span> 
  
## <a name="remediate-phase"></a><span data-ttu-id="ee95d-151">修正阶段</span><span class="sxs-lookup"><span data-stu-id="ee95d-151">Remediate phase</span></span>

 <span data-ttu-id="ee95d-152">**关键操作**</span><span class="sxs-lookup"><span data-stu-id="ee95d-152">**Key actions**</span></span>
  
- <span data-ttu-id="ee95d-153">FastTrack 中心审查迁移评估报告并测试你使用调查表提供的详细信息。</span><span class="sxs-lookup"><span data-stu-id="ee95d-153">The FastTrack Center reviews the migration assessment report and tests the details that you supply using the questionnaire.</span></span>   
- <span data-ttu-id="ee95d-154">FastTrack 中心建议的修正项必须由您亲自完成。</span><span class="sxs-lookup"><span data-stu-id="ee95d-154">Remediation items suggested by the FastTrack Center must be completed by you.</span></span>
    
 <span data-ttu-id="ee95d-155">**客户责任**</span><span class="sxs-lookup"><span data-stu-id="ee95d-155">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="ee95d-156">基于 FastTrack 中心提供的准则修正 Domino 环境（例如，设置邮件文件中标记为缺失的任何必需的权限）。</span><span class="sxs-lookup"><span data-stu-id="ee95d-156">Remediate the Domino environment based on guidelines that the FastTrack Center provides (for example, setting any required permissions that are identified as missing in the mail files).</span></span>  
- <span data-ttu-id="ee95d-157">确保 Domino 邮箱的大小低于通过迁移允许的最大大小。</span><span class="sxs-lookup"><span data-stu-id="ee95d-157">Ensure that Domino mailboxes are below the maximum size allowed through migration.</span></span>
    > [!NOTE]
    >  <span data-ttu-id="ee95d-158">虽然 FastTrack 会迁移达到允许总目标大小的 85% 的邮箱，但是尝试迁移大小超过 2GB 的邮箱会带来额外的风险，如：</span><span class="sxs-lookup"><span data-stu-id="ee95d-158">Although FastTrack migrates mailboxes up to 85% of the total allowable target size, attempting to migrate mailboxes larger than 2 GB carries additional risks like:</span></span>    <br/> <span data-ttu-id="ee95d-p109">迁移的持续时间延长。    </span><span class="sxs-lookup"><span data-stu-id="ee95d-p109">Lengthened duration of migrations.    </span></span><br/> <span data-ttu-id="ee95d-p110">转为使用用于迁移其他邮箱的资源。    </span><span class="sxs-lookup"><span data-stu-id="ee95d-p110">Using resources otherwise used for migrating other mailboxes.    </span></span><br/> <span data-ttu-id="ee95d-161">错误率大幅提升。</span><span class="sxs-lookup"><span data-stu-id="ee95d-161">A considerable increase in error rates.</span></span> 
- <span data-ttu-id="ee95d-p111">准备邮件内数据库及其访问控制列表 (ACL)，以便进行迁移。必须执行一些修正步骤，才能将邮件内数据库及其权限成功迁移到 Exchange Online 中的共享邮箱。其中一些步骤如下：</span><span class="sxs-lookup"><span data-stu-id="ee95d-p111">Prepare the mail-in databases and their access control lists (ACLs) for migration. You must perform some remediation steps to successfully migrate mail-in databases and their permissions to a shared mailbox in Exchange Online. A few of these steps are as follows:</span></span> 
  - <span data-ttu-id="ee95d-165">删除 Domino 目录中现有的邮件内数据库条目，并创建新的人员记录。</span><span class="sxs-lookup"><span data-stu-id="ee95d-165">Remove existing mail-in database entries in the Domino directory and create new Person records.</span></span>
  - <span data-ttu-id="ee95d-166">在同步到 Office 365 Azure Active Directory 且用于在 Exchange Online 中的共享邮箱上配置权限的本地 Active Directory 中创建已启用邮件的通用安全组。</span><span class="sxs-lookup"><span data-stu-id="ee95d-166">Create mail-enabled universal security groups in the on-premises Active Directory that are synchronized to Office 365 Azure Active Directory and used to configure permissions on the shared mailbox in Exchange Online.</span></span> <span data-ttu-id="ee95d-167">这将在邮件内数据库上设置的权限转移到 Exchange Online 中的共享邮箱。</span><span class="sxs-lookup"><span data-stu-id="ee95d-167">This transfers the permissions set on the mail-in database over to the shared mailbox in Exchange Online.</span></span>
    
> [!NOTE]
> <span data-ttu-id="ee95d-168">现在即可开始新邮件系统和客户端的最终用户准备工作和培训。</span><span class="sxs-lookup"><span data-stu-id="ee95d-168">End-user readiness and training for the new messaging system and client can be started now.</span></span> 
  
## <a name="enable-phase"></a><span data-ttu-id="ee95d-169">启用阶段</span><span class="sxs-lookup"><span data-stu-id="ee95d-169">Enable phase</span></span>

 <span data-ttu-id="ee95d-170">**关键操作**</span><span class="sxs-lookup"><span data-stu-id="ee95d-170">**Key actions**</span></span>
  
- <span data-ttu-id="ee95d-171">FastTrack 中心：</span><span class="sxs-lookup"><span data-stu-id="ee95d-171">The FastTrack Center:</span></span> 
    - <span data-ttu-id="ee95d-172">在 Azure 中设置迁移环境。</span><span class="sxs-lookup"><span data-stu-id="ee95d-172">Sets up the migration environment in Azure.</span></span>  
    - <span data-ttu-id="ee95d-173">在本地管理工作站中配置迁移工具。</span><span class="sxs-lookup"><span data-stu-id="ee95d-173">Configures the migration tools on the on-premises admin workstations.</span></span> 
    - <span data-ttu-id="ee95d-174">配置和演示如何使用自动导入工具。</span><span class="sxs-lookup"><span data-stu-id="ee95d-174">Configures and demonstrates how to use the Auto-Import tool.</span></span>  
    - <span data-ttu-id="ee95d-175">验证所有迁移组件，并执行测试迁移。</span><span class="sxs-lookup"><span data-stu-id="ee95d-175">Conducts validation of all migration components and performs test migrations.</span></span>
    
 <span data-ttu-id="ee95d-176">**客户责任**</span><span class="sxs-lookup"><span data-stu-id="ee95d-176">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="ee95d-p113">负责安排邮箱迁移的人员必须了解如何使用自动导入工具。可以使用此工具将迁移计划导入到调度数据库中，FastTrack 中心使用该数据库执行迁移前活动。</span><span class="sxs-lookup"><span data-stu-id="ee95d-p113">Your personnel in charge of scheduling mailbox migration must understand how to use the Auto-Import tool. You use this tool to import the migration schedule into the scheduling database which the FastTrack Center uses to perform pre-migration activities.</span></span> 
- <span data-ttu-id="ee95d-179">执行迁移前活动，如导入用户计划、分析审核报告、修正任何问题以及重新导入有问题的用户帐户。</span><span class="sxs-lookup"><span data-stu-id="ee95d-179">Perform pre-migration activities like importing user schedules, analyzing audit reports, remediating any issues, and reimporting user accounts with problems.</span></span>
    
<span data-ttu-id="ee95d-p114">迁移前活动在你与 FastTrack 中心之间协调。导入用户迁移计划后，开始复制到 Azure。</span><span class="sxs-lookup"><span data-stu-id="ee95d-p114">Pre-migration activities are coordinated between you and the FastTrack Center. Replication to Azure begins after the user migration schedule is imported.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="ee95d-p115">复制所需的时间取决于数据量。然后，FastTrack 中心执行审核以确定迁移准备情况。审核结果会提供给你，以便你了解正常所需的后续修正。所有这些步骤被称为"倒计时"活动，因为它们必须在用户的计划迁移之前开始。</span><span class="sxs-lookup"><span data-stu-id="ee95d-p115">The time required to replicate depends on the amount of data. The FastTrack Center then performs auditing to determine migration readiness. Audit results are provided to you with the understanding that subsequent remediation is normally required. All of these steps are called "T-minus" activities because they must begin in advance of the users' scheduled migration.</span></span> 
  
## <a name="migrate-phase"></a><span data-ttu-id="ee95d-186">迁移阶段</span><span class="sxs-lookup"><span data-stu-id="ee95d-186">Migrate phase</span></span>

 <span data-ttu-id="ee95d-187">**关键操作**</span><span class="sxs-lookup"><span data-stu-id="ee95d-187">**Key actions**</span></span>
  
- <span data-ttu-id="ee95d-188">FastTrack 中心：</span><span class="sxs-lookup"><span data-stu-id="ee95d-188">The FastTrack Center:</span></span>
    - <span data-ttu-id="ee95d-189">执行试点迁移和快速迁移。</span><span class="sxs-lookup"><span data-stu-id="ee95d-189">Performs pilot and velocity migrations.</span></span>  
    - <span data-ttu-id="ee95d-190">执行迁移事件和倒计时活动。</span><span class="sxs-lookup"><span data-stu-id="ee95d-190">Performs migration events and T-minus activities.</span></span>
    - <span data-ttu-id="ee95d-191">提供迁移后协助。</span><span class="sxs-lookup"><span data-stu-id="ee95d-191">Provides post-migration assistance.</span></span>
    
 <span data-ttu-id="ee95d-192">**客户责任**</span><span class="sxs-lookup"><span data-stu-id="ee95d-192">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="ee95d-193">迁移之前 21 天确定并导入迁移计划。</span><span class="sxs-lookup"><span data-stu-id="ee95d-193">Identify and import migration schedules 21 days prior to migration.</span></span>
    > [!NOTE]
    > <span data-ttu-id="ee95d-p116">此任务非常重要，因为迁移前活动涉及在实际迁移日 (T-0) 之前的不同阶段对副本创建进行的修正和可能的重试。一些邮箱正在迁移时，倒计时活动将在其他邮箱上执行。这使适当的规划和协调必不可少。</span><span class="sxs-lookup"><span data-stu-id="ee95d-p116">This task is critical because the pre-migration activities involve remediation and possible retries of replica creation at different stages before the actual migration day (T-0). While some mailboxes are migrating, T-minus activities are being performed on others. This makes proper planning and coordination a must.</span></span> 
- <span data-ttu-id="ee95d-197">修复在倒计时活动执行过程中发现的问题。</span><span class="sxs-lookup"><span data-stu-id="ee95d-197">Fix issues identified during T-minus activities.</span></span>
- <span data-ttu-id="ee95d-198">解决和修复影响迁移活动的所有 Domino 服务器问题。</span><span class="sxs-lookup"><span data-stu-id="ee95d-198">Address and fix any Domino server issues that impact migration activities.</span></span> 
- <span data-ttu-id="ee95d-199">与最终用户沟通即将到来的迁移日期的相关事宜。</span><span class="sxs-lookup"><span data-stu-id="ee95d-199">Conduct end-user communications about the upcoming migration date.</span></span>
- <span data-ttu-id="ee95d-200">开展新邮件系统和客户端的最终用户准备活动和培训。</span><span class="sxs-lookup"><span data-stu-id="ee95d-200">Conduct end-user readiness activities and training for the new messaging system and client.</span></span>   
- <span data-ttu-id="ee95d-p117">识别并报告迁移后问题。FastTrack 中心在迁移完成后的 T+5 天内提供迁移后支持，在这个时间之后将由你亲自负责。你可以记录迁移后票证来记录问题，如：缺少电子邮件、日历项目和联系人，或者记录邮箱中的重复项。</span><span class="sxs-lookup"><span data-stu-id="ee95d-p117">Identify and report post-migration issues. The FastTrack Center provides post-migration assistance until T+5 days after migration, after which it becomes your responsibility. You can log post-migration tickets for issues like missing emails, calendar items, and contacts, or for duplicates in the mailbox.</span></span>
    
<span data-ttu-id="ee95d-204">FastTrack 中心不涉及部署、许可费或与目录准备相关的协助（包括 Domino 到 Active Directory 的目录同步），适用于 Notes 应用程序互操作性的共存软件附加设备、自助服务迁移或存档迁移。</span><span class="sxs-lookup"><span data-stu-id="ee95d-204">The FastTrack Center doesn't cover deployment, license fees, or assistance related to directory preparation (including Domino-to-Active Directory directory synchronization), coexistence software add-ons for Notes application interoperability, self-service migration, or archive migration.</span></span>
  

  

