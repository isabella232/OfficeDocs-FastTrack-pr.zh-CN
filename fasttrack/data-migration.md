---
title: 数据迁移
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 11/2/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack 可以帮助你将源环境中的邮件和文件数据迁移到 Office 365（Exchange Online、SharePoint Online 和 OneDrive for Business）。 我们提供的帮助类型取决于你的 Office 365 许可证数量。
ms.openlocfilehash: 7b796ea88c884445bd7069c6c7768c8fc3e3d170
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827644"
---
# <a name="data-migration"></a><span data-ttu-id="8506f-104">数据迁移</span><span class="sxs-lookup"><span data-stu-id="8506f-104">Data Migration</span></span>

<span data-ttu-id="8506f-105">FastTrack 可以帮助你将源环境中的邮件和文件数据迁移到 Office 365（Exchange Online、SharePoint Online 和 OneDrive for Business）。</span><span class="sxs-lookup"><span data-stu-id="8506f-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="8506f-106">我们提供的帮助类型取决于你的 Office 365 许可证数量：</span><span class="sxs-lookup"><span data-stu-id="8506f-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="8506f-107">**对于具有 150-499 个许可证的 Office 365 租户** ：FastTrack 仅提供迁移指南；你负责执行数据迁移。</span><span class="sxs-lookup"><span data-stu-id="8506f-107">**For Office 365 tenants with 150-499 licenses** : FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="8506f-108">我们将指导你阅读文档，以帮助你计划和使用免费工具来执行自助服务迁移。</span><span class="sxs-lookup"><span data-stu-id="8506f-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="8506f-109">**对于具有 500 个或更多许可证的 Office 365 租户** ：FastTrack 提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="8506f-109">**For Office 365 tenants with 500 or more licenses** : FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="8506f-110">我们提供指导，以帮助你计划迁移、配置源环境和 Office 365 租户，并利用我们的数据迁移服务来迁移数据。</span><span class="sxs-lookup"><span data-stu-id="8506f-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="8506f-111">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="8506f-111">You create and schedule your migration events.</span></span> <span data-ttu-id="8506f-112">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="8506f-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="8506f-113">如果你在 2017 年 9 月 1 日之前购买或续订了商业计划，则只需 150 个许可证即可获得数据迁移服务的资格。</span><span class="sxs-lookup"><span data-stu-id="8506f-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="8506f-114">对于教育计划，只有付费教职员工许可证才有资格获得数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="8506f-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="8506f-115">注意事项</span><span class="sxs-lookup"><span data-stu-id="8506f-115">Considerations</span></span>

  - <span data-ttu-id="8506f-116">你的源环境必须满足特定的期望才能将数据迁移到 Office 365。</span><span class="sxs-lookup"><span data-stu-id="8506f-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="8506f-117">有关 Exchange、SharePoint 和 OneDrive for Business 的源环境期望的更多信息，请参阅[产品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="8506f-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="8506f-118">我们需要对你的源环境和 Office 365 租户具有适当的访问权限和权限才能提供数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="8506f-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="8506f-119">我们的数据迁移服务并非为满足特殊法律或法规要求的数据而设计或以此为目的。</span><span class="sxs-lookup"><span data-stu-id="8506f-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="8506f-120">我们迁移数据时，可将其传输到我们维护设施的任何位置、从中进行存储和处理（除非为你的 FastTrack 迁移项目提供了其他位置）。</span><span class="sxs-lookup"><span data-stu-id="8506f-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="8506f-121">我们无法保证邮件或文件的迁移速度。</span><span class="sxs-lookup"><span data-stu-id="8506f-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="8506f-122">不可预见的问题（例如源环境中不可读或损坏的项）可能会阻止我们迁移某些数据项。</span><span class="sxs-lookup"><span data-stu-id="8506f-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="8506f-123">我们无法控制的外部因素（例如对第三方应用程序编程接口 (API) 的更改）可能会导致我们的数据迁移服务发生更改、延迟或暂停。</span><span class="sxs-lookup"><span data-stu-id="8506f-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="8506f-124">迁移服务可用性</span><span class="sxs-lookup"><span data-stu-id="8506f-124">Migration service availability</span></span>

  - <span data-ttu-id="8506f-125">**对于商业和英国政府客户：** 我们每周七 (7) 天，每天 24 小时 (24x7) 提供数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="8506f-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="8506f-126">**对于美国政府/DOD 客户：** 我们每周五 (5) 天，每天 24 小时 (24x5) 提供数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="8506f-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="8506f-127">到 Exchange Online 的迁移</span><span class="sxs-lookup"><span data-stu-id="8506f-127">Migration to Exchange Online</span></span>

<span data-ttu-id="8506f-128">当你选择使用 FastTrack 将电子邮件迁移到 Exchange Online 时，我们将提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="8506f-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8506f-129">我们提供指导，以帮助你计划迁移、配置源环境和 Exchange Online，并利用我们的数据迁移服务来迁移邮箱。</span><span class="sxs-lookup"><span data-stu-id="8506f-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="8506f-130">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="8506f-130">You create and schedule your migration events.</span></span> <span data-ttu-id="8506f-131">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="8506f-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8506f-132">迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源邮箱中的的邮件已迁移到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="8506f-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="8506f-133">注意事项</span><span class="sxs-lookup"><span data-stu-id="8506f-133">Considerations</span></span>

  - <span data-ttu-id="8506f-134">迁移前，必须完成 Exchange Online 的FastTrack 核心载入；</span><span class="sxs-lookup"><span data-stu-id="8506f-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="8506f-135">如果你自行执行载入，则必须通过必需的检查和先决条件。</span><span class="sxs-lookup"><span data-stu-id="8506f-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="8506f-136">有关详细信息，请参阅[产品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="8506f-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="8506f-137">FastTrack 仅迁移到活动的 Office 365 邮箱。</span><span class="sxs-lookup"><span data-stu-id="8506f-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="8506f-138">如果要从本地 Exchange 环境迁移，则必须满足特定要求。</span><span class="sxs-lookup"><span data-stu-id="8506f-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="8506f-139">有关详细信息，请参阅[配置混合部署先决条件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="8506f-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="8506f-140">每个源环境都必须处于源环境中相应产品的最新服务包 (SP) 和汇总更新 (RU)/累积更新 (CU) 级别。</span><span class="sxs-lookup"><span data-stu-id="8506f-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="8506f-141">位于本地 Active Directory 中的通讯组列表（ *MailEnabledGroup* 对象）和外部联系人（ *MailEnabledContact* 对象）不是邮箱数据迁移的一部分。</span><span class="sxs-lookup"><span data-stu-id="8506f-141">Distribution lists ( *MailEnabledGroup* objects) and external contacts ( *MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="8506f-142">但是，你可以使用 Azure Active Directory (Azure AD) Connect 将它们同步。</span><span class="sxs-lookup"><span data-stu-id="8506f-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="8506f-143">源环境</span><span class="sxs-lookup"><span data-stu-id="8506f-143">Source environments</span></span>

<span data-ttu-id="8506f-144">我们的数据迁移服务从以下源环境迁移数据：</span><span class="sxs-lookup"><span data-stu-id="8506f-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="8506f-145">具有单个或多个 Exchange 组织的单个或多个 Active Directory 林（每个 Exchange 邮件系统均须为 Exchange 2010 或更高版本）。</span><span class="sxs-lookup"><span data-stu-id="8506f-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="8506f-146">一个支持 IMAP 的电子邮件环境。</span><span class="sxs-lookup"><span data-stu-id="8506f-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="8506f-147">G 套件环境（仅限 Gmail、联系人和日历）</span><span class="sxs-lookup"><span data-stu-id="8506f-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="8506f-148">下表显示了特定于每个源环境的迁移详细信息：</span><span class="sxs-lookup"><span data-stu-id="8506f-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8506f-149"><strong>源环境</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="8506f-150"><strong>迁移类型</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="8506f-151"><strong>迁移内容</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="8506f-152"><strong>不迁移的内容</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8506f-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="8506f-154">
<strong>注意：</strong> 有关本地 Exchange 依存关系，请参阅 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">混合部署先决条件</span></a>。</span><span class="sxs-lookup"><span data-stu-id="8506f-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="8506f-155">使用混合部署进行的迁移</span><span class="sxs-lookup"><span data-stu-id="8506f-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="8506f-156">电子邮件</span><span class="sxs-lookup"><span data-stu-id="8506f-156">Emails</span></span></li>
<li><span data-ttu-id="8506f-157">邮箱规则</span><span class="sxs-lookup"><span data-stu-id="8506f-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="8506f-158">代理</span><span class="sxs-lookup"><span data-stu-id="8506f-158">Delegates</span></span></li>
<li><span data-ttu-id="8506f-159">邮箱联系人</span><span class="sxs-lookup"><span data-stu-id="8506f-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="8506f-160">日历</span><span class="sxs-lookup"><span data-stu-id="8506f-160">Calendar</span></span> </li>
<li> <span data-ttu-id="8506f-161">任务</span><span class="sxs-lookup"><span data-stu-id="8506f-161">Tasks</span></span> </li>
<li> <span data-ttu-id="8506f-162">权限管理的电子邮件</span><span class="sxs-lookup"><span data-stu-id="8506f-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="8506f-163">加密电子邮件</span><span class="sxs-lookup"><span data-stu-id="8506f-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="8506f-164">签名</span><span class="sxs-lookup"><span data-stu-id="8506f-164">Signatures</span></span> </li>
<li> <span data-ttu-id="8506f-165">与用户的邮箱一起迁移的个人存档</span><span class="sxs-lookup"><span data-stu-id="8506f-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="8506f-166">可恢复的项目</span><span class="sxs-lookup"><span data-stu-id="8506f-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8506f-167">公用文件夹</span><span class="sxs-lookup"><span data-stu-id="8506f-167">Public folders</span></span> </li>
<li> <span data-ttu-id="8506f-168">超出邮件大小限制的所有电子邮件</span><span class="sxs-lookup"><span data-stu-id="8506f-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8506f-169">日记存档或任何第三方存档解决方案</span><span class="sxs-lookup"><span data-stu-id="8506f-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="8506f-170">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="8506f-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8506f-171">来自个人存储表 (PST) 文件的存档数据</span><span class="sxs-lookup"><span data-stu-id="8506f-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="8506f-172">已损坏的项目</span><span class="sxs-lookup"><span data-stu-id="8506f-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8506f-173">非活动邮箱</span><span class="sxs-lookup"><span data-stu-id="8506f-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8506f-174"><strong>G 套件环境（仅限 Gmail、联系人和日历）</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="8506f-175">
<strong>注意：</strong> 您的 G 套件环境必须满足 <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">执行 G 套件迁移</a>中所述的先决条件。</span><span class="sxs-lookup"><span data-stu-id="8506f-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="8506f-176">直接转换或暂存</span><span class="sxs-lookup"><span data-stu-id="8506f-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="8506f-177">电子邮件</span><span class="sxs-lookup"><span data-stu-id="8506f-177">Emails</span></span> </li>
<li> <span data-ttu-id="8506f-178">邮箱联系人（每个联系人最多迁移 3 个电子邮件地址）</span><span class="sxs-lookup"><span data-stu-id="8506f-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="8506f-179">日历</span><span class="sxs-lookup"><span data-stu-id="8506f-179">Calendar</span></span> </li>
<li> <span data-ttu-id="8506f-180">标签</span><span class="sxs-lookup"><span data-stu-id="8506f-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8506f-181">规则</span><span class="sxs-lookup"><span data-stu-id="8506f-181">Rules</span></span> </li>
<li> <span data-ttu-id="8506f-182">代理</span><span class="sxs-lookup"><span data-stu-id="8506f-182">Delegates</span></span> </li>
<li> <span data-ttu-id="8506f-183">签名</span><span class="sxs-lookup"><span data-stu-id="8506f-183">Signatures</span></span> </li>
<li> <span data-ttu-id="8506f-184">任务</span><span class="sxs-lookup"><span data-stu-id="8506f-184">Tasks</span></span> </li>
<li> <span data-ttu-id="8506f-185">超出邮件大小限制的所有电子邮件或附件</span><span class="sxs-lookup"><span data-stu-id="8506f-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8506f-186">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="8506f-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8506f-187">来自 PST 文件或任何第三方存档解决方案（例如 Google Vault）的存档数据</span><span class="sxs-lookup"><span data-stu-id="8506f-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="8506f-188">权限管理或加密电子邮件</span><span class="sxs-lookup"><span data-stu-id="8506f-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="8506f-189">已损坏的项目</span><span class="sxs-lookup"><span data-stu-id="8506f-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8506f-190">Google Hangout\*\*</span><span class="sxs-lookup"><span data-stu-id="8506f-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="8506f-191">Google 组</span><span class="sxs-lookup"><span data-stu-id="8506f-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="8506f-192">资源邮箱</span><span class="sxs-lookup"><span data-stu-id="8506f-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="8506f-193">非活动邮箱</span><span class="sxs-lookup"><span data-stu-id="8506f-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="8506f-194">假期设置和自动答复设置</span><span class="sxs-lookup"><span data-stu-id="8506f-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="8506f-195">共享日历、云附件、Google Hangout 链接和事件颜色</span><span class="sxs-lookup"><span data-stu-id="8506f-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="8506f-196">\*\*迁移另存为标签的环聊对话。</span><span class="sxs-lookup"><span data-stu-id="8506f-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8506f-197"><strong>IMAP4 源（如 Domino、GroupWise 或 Zimbra）</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="8506f-198">使用本机 IMAP4 工具进行迁移</span><span class="sxs-lookup"><span data-stu-id="8506f-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="8506f-199">电子邮件</span><span class="sxs-lookup"><span data-stu-id="8506f-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="8506f-200">规则</span><span class="sxs-lookup"><span data-stu-id="8506f-200">Rules</span></span> </li>
<li> <span data-ttu-id="8506f-201">代理</span><span class="sxs-lookup"><span data-stu-id="8506f-201">Delegates</span></span> </li>
<li> <span data-ttu-id="8506f-202">通讯组列表</span><span class="sxs-lookup"><span data-stu-id="8506f-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="8506f-203">外部联系人</span><span class="sxs-lookup"><span data-stu-id="8506f-203">External contacts</span></span> </li>
<li> <span data-ttu-id="8506f-204">启用邮件的用户</span><span class="sxs-lookup"><span data-stu-id="8506f-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="8506f-205">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="8506f-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8506f-206">邮箱联系人</span><span class="sxs-lookup"><span data-stu-id="8506f-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="8506f-207">日历</span><span class="sxs-lookup"><span data-stu-id="8506f-207">Calendar</span></span> </li>
<li> <span data-ttu-id="8506f-208">签名</span><span class="sxs-lookup"><span data-stu-id="8506f-208">Signatures</span></span> </li>
<li> <span data-ttu-id="8506f-209">任务</span><span class="sxs-lookup"><span data-stu-id="8506f-209">Tasks</span></span> </li>
<li> <span data-ttu-id="8506f-210">超出邮件大小限制的所有电子邮件</span><span class="sxs-lookup"><span data-stu-id="8506f-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="8506f-211">存档数据</span><span class="sxs-lookup"><span data-stu-id="8506f-211">Archive data</span></span> </li>
<li> <span data-ttu-id="8506f-212">加密电子邮件</span><span class="sxs-lookup"><span data-stu-id="8506f-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="8506f-213">已损坏的项目</span><span class="sxs-lookup"><span data-stu-id="8506f-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="8506f-214">非活动邮箱</span><span class="sxs-lookup"><span data-stu-id="8506f-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8506f-215">FastTrack 责任</span><span class="sxs-lookup"><span data-stu-id="8506f-215">FastTrack responsibilities</span></span>

<span data-ttu-id="8506f-216">我们的 FastTrack 专家在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="8506f-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8506f-217">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="8506f-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8506f-218">我们的 FastTrack 专家还执行以下特定于 Exchange 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="8506f-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="8506f-219">提供指导以帮助你在源环境和 Exchange Online 之间启用 SMTP 邮件路由共存（如果适用）。</span><span class="sxs-lookup"><span data-stu-id="8506f-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8506f-220">你的责任</span><span class="sxs-lookup"><span data-stu-id="8506f-220">Your responsibilities</span></span>

<span data-ttu-id="8506f-221">你在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="8506f-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8506f-222">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="8506f-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8506f-223">此外，你还将执行以下特定于 Exchange 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="8506f-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="8506f-224">完成 Exchange Online 的FastTrack 核心载入。</span><span class="sxs-lookup"><span data-stu-id="8506f-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="8506f-225">如果你自行执行载入，则必须通过必需的检查和先决条件。</span><span class="sxs-lookup"><span data-stu-id="8506f-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="8506f-226">有关详细信息，请参阅[产品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="8506f-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="8506f-227">根据 Office 365 准则安装客户端软件的相应级别。</span><span class="sxs-lookup"><span data-stu-id="8506f-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="8506f-228">有关详细信息，请参阅[新式工作区](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)。</span><span class="sxs-lookup"><span data-stu-id="8506f-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="8506f-229">如果要从本地 Exchange 环境迁移，需满足特定要求。</span><span class="sxs-lookup"><span data-stu-id="8506f-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="8506f-230">有关详细信息，请参阅[配置混合部署先决条件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="8506f-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="8506f-231">确保每个源环境都位于最新服务包 (SP) 和汇总 (RU)/累积更新 (CU) 级别（如果适用）。</span><span class="sxs-lookup"><span data-stu-id="8506f-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="8506f-232">配置和验证源环境和 Exchange Online 之间的 SMTP 邮件路由共存（如果适用）。</span><span class="sxs-lookup"><span data-stu-id="8506f-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="8506f-233">确保源邮箱大小不超过目标邮箱配额。</span><span class="sxs-lookup"><span data-stu-id="8506f-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="8506f-234">根据源平台的不同，可能需要将源数据限制为目标邮箱配额的 85%。</span><span class="sxs-lookup"><span data-stu-id="8506f-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="8506f-235">根据需要迁移客户端数据。</span><span class="sxs-lookup"><span data-stu-id="8506f-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="8506f-236">这包括但不限于本地通讯簿、本地 PST 文件中的数据、Outlook 规则和本地 Outlook 设置。</span><span class="sxs-lookup"><span data-stu-id="8506f-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="8506f-237">帮助最终用户修正客户端迁移问题。</span><span class="sxs-lookup"><span data-stu-id="8506f-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="8506f-238">到 SharePoint Online 的迁移</span><span class="sxs-lookup"><span data-stu-id="8506f-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="8506f-239">当你选择使用 FastTrack 将文件迁移到 SharePoint Online 时，我们将提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="8506f-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8506f-240">我们提供指导，以帮助你计划迁移、配置源环境和 SharePoint Online，并利用我们的数据迁移服务来迁移文件。</span><span class="sxs-lookup"><span data-stu-id="8506f-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="8506f-241">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="8506f-241">You create and schedule your migration events.</span></span> <span data-ttu-id="8506f-242">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="8506f-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8506f-243">迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源中的的文件已迁移到 SharePoint Online。</span><span class="sxs-lookup"><span data-stu-id="8506f-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="8506f-244">注意事项</span><span class="sxs-lookup"><span data-stu-id="8506f-244">Considerations</span></span>

  - <span data-ttu-id="8506f-245">所有迁移均受 SharePoint Online 配额的限制。</span><span class="sxs-lookup"><span data-stu-id="8506f-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="8506f-246">有关详细信息，请参阅 [<span class="underline">SharePoint Online 和 OneDrive for Business 的软件边界与限制</span>](https://go.microsoft.com/fwlink/?LinkId=698855)。</span><span class="sxs-lookup"><span data-stu-id="8506f-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="8506f-247">建议将迁移总量限制在你享有的整体 SharePoint Online 存储配额（包括你可能单独购买的其他存储）的 75% 以内。</span><span class="sxs-lookup"><span data-stu-id="8506f-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="8506f-248">源环境详细信息</span><span class="sxs-lookup"><span data-stu-id="8506f-248">Source environment details</span></span>

<span data-ttu-id="8506f-249">我们的数据迁移服务从以下源环境迁移数据：</span><span class="sxs-lookup"><span data-stu-id="8506f-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="8506f-250">文件共享（支持 SMB 2.0 前向的设备上的服务器消息块 (SMB) 文件共享）。</span><span class="sxs-lookup"><span data-stu-id="8506f-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="8506f-251">单个 G 套件环境（仅限 Google Drive）。</span><span class="sxs-lookup"><span data-stu-id="8506f-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="8506f-252">Box（Starter、Business、Enterprise）。</span><span class="sxs-lookup"><span data-stu-id="8506f-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="8506f-253">用于 Teams的 Dropbox（标准版和高级版）</span><span class="sxs-lookup"><span data-stu-id="8506f-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="8506f-254">下表显示了特定于每个源环境的迁移详细信息：</span><span class="sxs-lookup"><span data-stu-id="8506f-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="8506f-255"><strong>源环境</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="8506f-256"><strong>迁移类型</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="8506f-257"><strong>迁移内容</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="8506f-258"><strong>不迁移的内容</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8506f-259"><strong>任何支持 SMB 2.0 及更高版本的文件共享设备</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="8506f-260">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="8506f-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8506f-261">文档</span><span class="sxs-lookup"><span data-stu-id="8506f-261">Documents</span></span> </li>
<li> <span data-ttu-id="8506f-262">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="8506f-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8506f-263">用户级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="8506f-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8506f-264">组级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="8506f-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8506f-265">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="8506f-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8506f-266">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="8506f-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8506f-267">创建日期</span><span class="sxs-lookup"><span data-stu-id="8506f-267">Created date</span></span> </li>
<li> <span data-ttu-id="8506f-268">修改日期</span><span class="sxs-lookup"><span data-stu-id="8506f-268">Modified date</span></span> </li>
<li> <span data-ttu-id="8506f-269">创建者</span><span class="sxs-lookup"><span data-stu-id="8506f-269">Created by</span></span> </li>
<li> <span data-ttu-id="8506f-270">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="8506f-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="8506f-271">\*必须配置目录同步。</span><span class="sxs-lookup"><span data-stu-id="8506f-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="8506f-272">只迁移对 Windows 文件资源管理器公开的 NTFS 权限。</span><span class="sxs-lookup"><span data-stu-id="8506f-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="8506f-273">不会迁移文件共享设备上直接托管的权限。</span><span class="sxs-lookup"><span data-stu-id="8506f-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="8506f-274">如果数据存储在 SMB 2.0 设备上，只会迁移 SMB 协议公开的与 NTFS 等同的权限。</span><span class="sxs-lookup"><span data-stu-id="8506f-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="8506f-275">所有权历史记录和旧版本</span><span class="sxs-lookup"><span data-stu-id="8506f-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="8506f-276">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="8506f-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8506f-277">旧版本</span><span class="sxs-lookup"><span data-stu-id="8506f-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="8506f-278">Windows 文件和文件夹属性（如只读和隐藏）</span><span class="sxs-lookup"><span data-stu-id="8506f-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="8506f-279">非 Windows 新技术文件系统 (NTFS) 和 NTFS 高级权限和特殊设置：</span><span class="sxs-lookup"><span data-stu-id="8506f-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="8506f-280">显式拒绝权限（在迁移后删除的权限、从属于并行权限的内容或父文件夹上的权限）</span><span class="sxs-lookup"><span data-stu-id="8506f-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="8506f-281">NTFS 审核配置</span><span class="sxs-lookup"><span data-stu-id="8506f-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="8506f-282">文件分类基础结构 (FCI) 提供的附加文件元数据</span><span class="sxs-lookup"><span data-stu-id="8506f-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="8506f-283">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="8506f-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8506f-284">隐藏的共享</span><span class="sxs-lookup"><span data-stu-id="8506f-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="8506f-285">共享（如在共享级别授予的权限）</span><span class="sxs-lookup"><span data-stu-id="8506f-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="8506f-286">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="8506f-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8506f-287"><strong>单个 G 套件环境（仅限 Google 云端硬盘）</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="8506f-288">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="8506f-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8506f-289">Google 文档、工作表和幻灯片（文件转换为等同的 Office 格式），包括超过10 MB的</span><span class="sxs-lookup"><span data-stu-id="8506f-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="8506f-290">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="8506f-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8506f-291">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="8506f-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8506f-292">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="8506f-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8506f-293">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="8506f-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8506f-294">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="8506f-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8506f-295">创建日期</span><span class="sxs-lookup"><span data-stu-id="8506f-295">Created date</span></span> </li>
<li> <span data-ttu-id="8506f-296">修改日期</span><span class="sxs-lookup"><span data-stu-id="8506f-296">Modified date</span></span> </li>
<li> <span data-ttu-id="8506f-297">创建者</span><span class="sxs-lookup"><span data-stu-id="8506f-297">Created by</span></span> </li>
<li> <span data-ttu-id="8506f-298">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="8506f-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8506f-299">共享驱动器 （文件夹和文件）</span><span class="sxs-lookup"><span data-stu-id="8506f-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="8506f-300">属于 Google 云端硬盘帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="8506f-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8506f-301">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="8506f-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8506f-302">文件和文件夹说明、文件夹颜色</span><span class="sxs-lookup"><span data-stu-id="8506f-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="8506f-303">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="8506f-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8506f-304">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="8506f-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8506f-305">高级元数据</span><span class="sxs-lookup"><span data-stu-id="8506f-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8506f-306">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="8506f-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8506f-307">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="8506f-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8506f-308">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="8506f-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="8506f-309">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="8506f-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8506f-310">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="8506f-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8506f-311">Google 相册、Forms、地图和其他已连接应用</span><span class="sxs-lookup"><span data-stu-id="8506f-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="8506f-312">Google 绘图</span><span class="sxs-lookup"><span data-stu-id="8506f-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="8506f-313">组织外部的共享内容</span><span class="sxs-lookup"><span data-stu-id="8506f-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="8506f-314">不属于Google 云端硬盘帐户的内容被迁移</span><span class="sxs-lookup"><span data-stu-id="8506f-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="8506f-315">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Google 云端硬盘管理报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="8506f-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="8506f-316">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="8506f-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8506f-317">共享驱动器成员资格权限（<strong>注意</strong>：使用 Google 云端硬盘管理报告来标识共享驱动器成员资格。</span><span class="sxs-lookup"><span data-stu-id="8506f-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="8506f-318">指示最终用户迁移前在目标上配置这些成员资格设置。）</span><span class="sxs-lookup"><span data-stu-id="8506f-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="8506f-319">标记为 "受限" 或 "未 copyable" 的文件</span><span class="sxs-lookup"><span data-stu-id="8506f-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="8506f-320">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="8506f-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8506f-321"><strong>Box（Starter、Business、Enterprise）</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="8506f-322">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="8506f-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8506f-323">文档</span><span class="sxs-lookup"><span data-stu-id="8506f-323">Documents</span></span> </li>
<li> <span data-ttu-id="8506f-324">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="8506f-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8506f-325">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="8506f-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8506f-326">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="8506f-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8506f-327">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="8506f-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8506f-328">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="8506f-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8506f-329">创建日期</span><span class="sxs-lookup"><span data-stu-id="8506f-329">Created date</span></span> </li>
<li> <span data-ttu-id="8506f-330">修改日期</span><span class="sxs-lookup"><span data-stu-id="8506f-330">Modified date</span></span> </li>
<li> <span data-ttu-id="8506f-331">创建者</span><span class="sxs-lookup"><span data-stu-id="8506f-331">Created by</span></span> </li>
<li> <span data-ttu-id="8506f-332">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="8506f-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8506f-333">属于 Box 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="8506f-333">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8506f-334">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="8506f-334">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8506f-335">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="8506f-335">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8506f-336">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="8506f-336">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8506f-337">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="8506f-337">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8506f-338">Box 标记和高级元数据</span><span class="sxs-lookup"><span data-stu-id="8506f-338">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="8506f-339">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="8506f-339">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8506f-340">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="8506f-340">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8506f-341">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="8506f-341">Trashed items</span></span> </li>
<li> <span data-ttu-id="8506f-342">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="8506f-342">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8506f-343">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="8506f-343">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8506f-344">Box 应用、书签、收藏夹和工作流</span><span class="sxs-lookup"><span data-stu-id="8506f-344">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="8506f-345">不属于已迁移 Box 帐户的内容</span><span class="sxs-lookup"><span data-stu-id="8506f-345">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="8506f-346">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Box 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="8506f-346">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="8506f-347">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="8506f-347">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8506f-348">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="8506f-348">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8506f-349"><strong>用于 Teams的 Dropbox（标准版和高级版）</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-349"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="8506f-350">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="8506f-350">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8506f-351">文档</span><span class="sxs-lookup"><span data-stu-id="8506f-351">Documents</span></span> </li>
<li> <span data-ttu-id="8506f-352">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="8506f-352">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8506f-353">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="8506f-353">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8506f-354">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="8506f-354">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8506f-355">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="8506f-355">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8506f-356">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="8506f-356">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8506f-357">创建日期</span><span class="sxs-lookup"><span data-stu-id="8506f-357">Created date</span></span> </li>
<li> <span data-ttu-id="8506f-358">修改日期</span><span class="sxs-lookup"><span data-stu-id="8506f-358">Modified date</span></span> </li>
<li> <span data-ttu-id="8506f-359">创建者</span><span class="sxs-lookup"><span data-stu-id="8506f-359">Created by</span></span> </li>
<li> <span data-ttu-id="8506f-360">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="8506f-360">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8506f-361">共享团队文件夹和内容</span><span class="sxs-lookup"><span data-stu-id="8506f-361">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="8506f-362">属于 Dropbox 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="8506f-362">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8506f-363">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="8506f-363">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8506f-364">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="8506f-364">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8506f-365">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="8506f-365">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8506f-366">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="8506f-366">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8506f-367">高级元数据</span><span class="sxs-lookup"><span data-stu-id="8506f-367">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8506f-368">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="8506f-368">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8506f-369">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="8506f-369">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8506f-370">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="8506f-370">Trashed items</span></span> </li>
<li> <span data-ttu-id="8506f-371">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="8506f-371">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8506f-372">已卸载的 Dropbox 文件夹</span><span class="sxs-lookup"><span data-stu-id="8506f-372">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="8506f-373">已删除或已断开连接的用户</span><span class="sxs-lookup"><span data-stu-id="8506f-373">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="8506f-374">Dropbox Paper 文件、Dropbox Showcase 和 Dropbox Space</span><span class="sxs-lookup"><span data-stu-id="8506f-374">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="8506f-375">Dropbox 应用及收藏夹（已固定或加星标）</span><span class="sxs-lookup"><span data-stu-id="8506f-375">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="8506f-376">已迁移的 Dropbox 帐户不拥有的内容</span><span class="sxs-lookup"><span data-stu-id="8506f-376">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="8506f-377">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Dropbox 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="8506f-377">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="8506f-378">指示最终用户在迁移后与外部用户重新共享内容）</span><span class="sxs-lookup"><span data-stu-id="8506f-378">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="8506f-379">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="8506f-379">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8506f-380">FastTrack 责任</span><span class="sxs-lookup"><span data-stu-id="8506f-380">FastTrack responsibilities</span></span>

<span data-ttu-id="8506f-381">我们的 FastTrack 专家在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="8506f-381">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8506f-382">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息</span><span class="sxs-lookup"><span data-stu-id="8506f-382">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8506f-383">你的责任</span><span class="sxs-lookup"><span data-stu-id="8506f-383">Your responsibilities</span></span>

<span data-ttu-id="8506f-384">你在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="8506f-384">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8506f-385">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息</span><span class="sxs-lookup"><span data-stu-id="8506f-385">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="8506f-386">此外，你还将执行以下特定于 SharePoint Online 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="8506f-386">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="8506f-387">预置将作为迁移事件目标的所有 SharePoint 团队网站。</span><span class="sxs-lookup"><span data-stu-id="8506f-387">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="8506f-388">到 OneDrive for Business 的迁移</span><span class="sxs-lookup"><span data-stu-id="8506f-388">Migration to OneDrive for Business</span></span>

<span data-ttu-id="8506f-389">当你选择使用 FastTrack 将文件迁移到 OneDrive for Business 时，我们将提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="8506f-389">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="8506f-390">我们提供指导，以帮助你计划迁移、配置源环境和 OneDrive for Business，并利用我们的数据迁移服务来迁移文件。</span><span class="sxs-lookup"><span data-stu-id="8506f-390">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="8506f-391">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="8506f-391">You create and schedule your migration events.</span></span> <span data-ttu-id="8506f-392">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="8506f-392">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="8506f-393">迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源中的的文件已迁移到 OneDrive for Business。</span><span class="sxs-lookup"><span data-stu-id="8506f-393">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="8506f-394">注意事项</span><span class="sxs-lookup"><span data-stu-id="8506f-394">Considerations</span></span>

  - <span data-ttu-id="8506f-395">所有迁移均受 OneDrive for business 配额限制。</span><span class="sxs-lookup"><span data-stu-id="8506f-395">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="8506f-396">有关详细信息，请参阅 [<span class="underline">SharePoint Online 和 OneDrive for Business 的软件边界与限制</span>](https://go.microsoft.com/fwlink/?LinkId=698855)。</span><span class="sxs-lookup"><span data-stu-id="8506f-396">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="8506f-397">建议将迁移数据总量限制在你享有的整体 SharePoint Online 存储配额（包括你可能单独购买的其他存储）的 75% 以内。</span><span class="sxs-lookup"><span data-stu-id="8506f-397">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="8506f-398">FastTrack 仅迁移到活动的 OneDrive for Business 驱动器。</span><span class="sxs-lookup"><span data-stu-id="8506f-398">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="8506f-399">源环境详细信息</span><span class="sxs-lookup"><span data-stu-id="8506f-399">Source environment details</span></span>

<span data-ttu-id="8506f-400">我们的数据迁移服务从以下源环境迁移数据：</span><span class="sxs-lookup"><span data-stu-id="8506f-400">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="8506f-401">文件共享（SMB 文件在支持 SMB 2.0 前向的设备上共享）。</span><span class="sxs-lookup"><span data-stu-id="8506f-401">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="8506f-402">单个 G 套件环境（仅限 Google 云端硬盘）。</span><span class="sxs-lookup"><span data-stu-id="8506f-402">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="8506f-403">Box（Starter、Business、Enterprise）。</span><span class="sxs-lookup"><span data-stu-id="8506f-403">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="8506f-404">用于 Teams的 Dropbox（标准版和高级版）</span><span class="sxs-lookup"><span data-stu-id="8506f-404">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="8506f-405">下表显示了特定于每个源环境的迁移详细信息：</span><span class="sxs-lookup"><span data-stu-id="8506f-405">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="8506f-406"><strong>源环境</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-406"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="8506f-407"><strong>迁移类型</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-407"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="8506f-408"><strong>迁移内容</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-408"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="8506f-409"><strong>不迁移的内容</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-409"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="8506f-410"><strong>任何支持 SMB 2.0 及更高版本的文件共享设备</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-410"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="8506f-411">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="8506f-411">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8506f-412">文档</span><span class="sxs-lookup"><span data-stu-id="8506f-412">Documents</span></span> </li>
<li> <span data-ttu-id="8506f-413">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="8506f-413">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8506f-414">用户级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="8506f-414">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8506f-415">组级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="8506f-415">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="8506f-416">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="8506f-416">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8506f-417">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="8506f-417">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8506f-418">创建日期</span><span class="sxs-lookup"><span data-stu-id="8506f-418">Created date</span></span> </li>
<li> <span data-ttu-id="8506f-419">修改日期</span><span class="sxs-lookup"><span data-stu-id="8506f-419">Modified date</span></span> </li>
<li> <span data-ttu-id="8506f-420">创建者</span><span class="sxs-lookup"><span data-stu-id="8506f-420">Created by</span></span> </li>
<li> <span data-ttu-id="8506f-421">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="8506f-421">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="8506f-422">\*必须配置目录同步。</span><span class="sxs-lookup"><span data-stu-id="8506f-422">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="8506f-423">只迁移对 Windows 文件资源管理器公开的 NTFS 权限。</span><span class="sxs-lookup"><span data-stu-id="8506f-423">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="8506f-424">不会迁移文件共享设备上直接托管的权限。</span><span class="sxs-lookup"><span data-stu-id="8506f-424">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="8506f-425">如果数据存储在 SMB 2.0 设备上，只会迁移 SMB 协议公开的与 NTFS 等同的权限。</span><span class="sxs-lookup"><span data-stu-id="8506f-425">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="8506f-426">所有权历史记录和旧版本</span><span class="sxs-lookup"><span data-stu-id="8506f-426">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="8506f-427">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="8506f-427">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8506f-428">旧版本</span><span class="sxs-lookup"><span data-stu-id="8506f-428">Previous versions</span></span> </li>
<li> <span data-ttu-id="8506f-429">Windows 文件和文件夹属性（如只读和隐藏）</span><span class="sxs-lookup"><span data-stu-id="8506f-429">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="8506f-430">非 Windows 新技术文件系统 (NTFS) 和 NTFS 高级权限和特殊设置：</span><span class="sxs-lookup"><span data-stu-id="8506f-430">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="8506f-431">显式拒绝权限（在迁移后删除的权限、从属于并行权限的内容或父文件夹上的权限）</span><span class="sxs-lookup"><span data-stu-id="8506f-431">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="8506f-432">NTFS 审核配置</span><span class="sxs-lookup"><span data-stu-id="8506f-432">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="8506f-433">文件分类基础结构 (FCI) 提供的附加文件元数据</span><span class="sxs-lookup"><span data-stu-id="8506f-433">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="8506f-434">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="8506f-434">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8506f-435">隐藏的共享</span><span class="sxs-lookup"><span data-stu-id="8506f-435">Hidden shares</span></span> </li>
<li> <span data-ttu-id="8506f-436">共享（如在共享级别授予的权限）</span><span class="sxs-lookup"><span data-stu-id="8506f-436">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="8506f-437">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="8506f-437">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8506f-438"><strong>单个 G 套件环境（仅限 Google 云端硬盘）</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-438"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="8506f-439">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="8506f-439">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8506f-440">Google 文档、工作表和幻灯片（文件包括超过10 MB的，转换为等同的 Office 格式）</span><span class="sxs-lookup"><span data-stu-id="8506f-440">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="8506f-441">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="8506f-441">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8506f-442">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="8506f-442">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8506f-443">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="8506f-443">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8506f-444">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="8506f-444">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8506f-445">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="8506f-445">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8506f-446">创建日期</span><span class="sxs-lookup"><span data-stu-id="8506f-446">Created date</span></span> </li>
<li> <span data-ttu-id="8506f-447">修改日期</span><span class="sxs-lookup"><span data-stu-id="8506f-447">Modified date</span></span> </li>
<li> <span data-ttu-id="8506f-448">创建者</span><span class="sxs-lookup"><span data-stu-id="8506f-448">Created by</span></span> </li>
<li> <span data-ttu-id="8506f-449">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="8506f-449">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8506f-450">共享驱动器 （文件夹和文件）</span><span class="sxs-lookup"><span data-stu-id="8506f-450">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="8506f-451">属于 Google 云端硬盘帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="8506f-451">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8506f-452">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="8506f-452">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8506f-453">文件和文件夹说明、文件夹颜色</span><span class="sxs-lookup"><span data-stu-id="8506f-453">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="8506f-454">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="8506f-454">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8506f-455">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="8506f-455">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8506f-456">高级元数据</span><span class="sxs-lookup"><span data-stu-id="8506f-456">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8506f-457">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="8506f-457">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8506f-458">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="8506f-458">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8506f-459">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="8506f-459">Trashed items</span></span> </li>
<li> <span data-ttu-id="8506f-460">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="8506f-460">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8506f-461">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="8506f-461">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8506f-462">Google 相册、Forms、地图和其他已连接应用</span><span class="sxs-lookup"><span data-stu-id="8506f-462">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="8506f-463">Google 绘图</span><span class="sxs-lookup"><span data-stu-id="8506f-463">Google Drawings</span></span> </li>
<li> <span data-ttu-id="8506f-464">组织外部的共享内容</span><span class="sxs-lookup"><span data-stu-id="8506f-464">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="8506f-465">不属于Google 云端硬盘帐户的内容被迁移</span><span class="sxs-lookup"><span data-stu-id="8506f-465">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="8506f-466">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Google 云端硬盘管理报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="8506f-466">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="8506f-467">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="8506f-467">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8506f-468">共享驱动器成员资格权限（<strong>注意</strong>：使用 Google 云端硬盘管理报告来标识共享驱动器成员资格。</span><span class="sxs-lookup"><span data-stu-id="8506f-468">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="8506f-469">指示最终用户迁移前在目标上配置这些成员资格设置。）</span><span class="sxs-lookup"><span data-stu-id="8506f-469">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="8506f-470">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="8506f-470">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="8506f-471"><strong>Box（Starter、Business、Enterprise）</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-471"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="8506f-472">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="8506f-472">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8506f-473">文档</span><span class="sxs-lookup"><span data-stu-id="8506f-473">Documents</span></span> </li>
<li> <span data-ttu-id="8506f-474">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="8506f-474">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8506f-475">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="8506f-475">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8506f-476">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="8506f-476">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8506f-477">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="8506f-477">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8506f-478">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="8506f-478">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8506f-479">创建日期</span><span class="sxs-lookup"><span data-stu-id="8506f-479">Created date</span></span> </li>
<li> <span data-ttu-id="8506f-480">修改日期</span><span class="sxs-lookup"><span data-stu-id="8506f-480">Modified date</span></span> </li>
<li> <span data-ttu-id="8506f-481">创建者</span><span class="sxs-lookup"><span data-stu-id="8506f-481">Created by</span></span> </li>
<li> <span data-ttu-id="8506f-482">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="8506f-482">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8506f-483">属于 Box 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="8506f-483">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8506f-484">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="8506f-484">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8506f-485">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="8506f-485">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8506f-486">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="8506f-486">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8506f-487">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="8506f-487">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8506f-488">Box 标记和高级元数据</span><span class="sxs-lookup"><span data-stu-id="8506f-488">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="8506f-489">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="8506f-489">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8506f-490">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="8506f-490">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8506f-491">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="8506f-491">Trashed items</span></span> </li>
<li> <span data-ttu-id="8506f-492">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="8506f-492">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8506f-493">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="8506f-493">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="8506f-494">Box 应用、书签、收藏夹和工作流</span><span class="sxs-lookup"><span data-stu-id="8506f-494">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="8506f-495">不属于已迁移 Box 帐户的内容</span><span class="sxs-lookup"><span data-stu-id="8506f-495">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="8506f-496">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Box 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="8506f-496">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="8506f-497">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="8506f-497">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8506f-498">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="8506f-498">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="8506f-499"><strong>用于 Teams的 Dropbox（标准版和高级版）</strong></span><span class="sxs-lookup"><span data-stu-id="8506f-499"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="8506f-500">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="8506f-500">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="8506f-501">文档</span><span class="sxs-lookup"><span data-stu-id="8506f-501">Documents</span></span> </li>
<li> <span data-ttu-id="8506f-502">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="8506f-502">File and folder structure</span></span> </li>
<li> <span data-ttu-id="8506f-503">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="8506f-503">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8506f-504">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="8506f-504">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="8506f-505">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="8506f-505">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="8506f-506">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="8506f-506">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="8506f-507">创建日期</span><span class="sxs-lookup"><span data-stu-id="8506f-507">Created date</span></span> </li>
<li> <span data-ttu-id="8506f-508">修改日期</span><span class="sxs-lookup"><span data-stu-id="8506f-508">Modified date</span></span> </li>
<li> <span data-ttu-id="8506f-509">创建者</span><span class="sxs-lookup"><span data-stu-id="8506f-509">Created by</span></span> </li>
<li> <span data-ttu-id="8506f-510">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="8506f-510">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="8506f-511">共享团队文件夹和内容</span><span class="sxs-lookup"><span data-stu-id="8506f-511">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="8506f-512">属于 Dropbox 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="8506f-512">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="8506f-513">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="8506f-513">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="8506f-514">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="8506f-514">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="8506f-515">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="8506f-515">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="8506f-516">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="8506f-516">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="8506f-517">高级元数据</span><span class="sxs-lookup"><span data-stu-id="8506f-517">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="8506f-518">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="8506f-518">File lock attributes</span></span> </li>
<li> <span data-ttu-id="8506f-519">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="8506f-519">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="8506f-520">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="8506f-520">Trashed items</span></span> </li>
<li> <span data-ttu-id="8506f-521">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="8506f-521">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="8506f-522">已卸载的 Dropbox 文件夹</span><span class="sxs-lookup"><span data-stu-id="8506f-522">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="8506f-523">已删除或已断开连接的用户</span><span class="sxs-lookup"><span data-stu-id="8506f-523">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="8506f-524">Dropbox Paper 文件、Dropbox Showcase 和 Dropbox Space</span><span class="sxs-lookup"><span data-stu-id="8506f-524">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="8506f-525">Dropbox 应用及收藏夹（已固定或加星标）</span><span class="sxs-lookup"><span data-stu-id="8506f-525">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="8506f-526">已迁移的 Dropbox 帐户不拥有的内容</span><span class="sxs-lookup"><span data-stu-id="8506f-526">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="8506f-527">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Dropbox 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="8506f-527">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="8506f-528">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="8506f-528">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="8506f-529">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="8506f-529">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="8506f-530">FastTrack 责任</span><span class="sxs-lookup"><span data-stu-id="8506f-530">FastTrack responsibilities</span></span>

<span data-ttu-id="8506f-531">我们的 FastTrack 专家在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="8506f-531">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="8506f-532">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="8506f-532">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="8506f-533">你的责任</span><span class="sxs-lookup"><span data-stu-id="8506f-533">Your responsibilities</span></span>

<span data-ttu-id="8506f-534">你在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="8506f-534">You perform standard activities during the migration project.</span></span> <span data-ttu-id="8506f-535">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="8506f-535">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="8506f-536">此外，你还将执行以下特定于 OneDrive for Business 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="8506f-536">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="8506f-537">预置将作为迁移事件目标的所有 OneDrive for Business 网站。</span><span class="sxs-lookup"><span data-stu-id="8506f-537">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
