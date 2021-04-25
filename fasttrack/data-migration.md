---
title: 数据迁移
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 4/21/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack 可以帮助你将源环境中的邮件和文件数据迁移到 Office 365（Exchange Online、SharePoint Online 和 OneDrive for Business）。 我们提供的帮助类型取决于你的 Office 365 许可证数量。
ms.openlocfilehash: 8d74a288291907db22213f317ce8e89923590907
ms.sourcegitcommit: 5d40d060bbcf4b266a0d6f3e4bbc151f94288b00
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/25/2021
ms.locfileid: "51996251"
---
# <a name="data-migration"></a><span data-ttu-id="73f61-104">数据迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-104">Data Migration</span></span>

<span data-ttu-id="73f61-105">FastTrack 可以帮助你将源环境中的邮件和文件数据迁移到 Office 365（Exchange Online、SharePoint Online 和 OneDrive for Business）。</span><span class="sxs-lookup"><span data-stu-id="73f61-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="73f61-106">我们提供的帮助类型取决于你的 Office 365 许可证数量：</span><span class="sxs-lookup"><span data-stu-id="73f61-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="73f61-107">**对于具有 150-499 个许可证的 Office 365 租户**：FastTrack 仅提供迁移指南；你负责执行数据迁移。</span><span class="sxs-lookup"><span data-stu-id="73f61-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="73f61-108">我们将指导你阅读文档，以帮助你计划和使用免费工具来执行自助服务迁移。</span><span class="sxs-lookup"><span data-stu-id="73f61-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="73f61-109">**对于具有 500 个或更多许可证的 Office 365 租户**：FastTrack 提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="73f61-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="73f61-110">我们提供指导，以帮助你计划迁移、配置源环境和 Office 365 租户，并利用我们的数据迁移服务来迁移数据。</span><span class="sxs-lookup"><span data-stu-id="73f61-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="73f61-111">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="73f61-111">You create and schedule your migration events.</span></span> <span data-ttu-id="73f61-112">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="73f61-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="73f61-113">如果你在 2017 年 9 月 1 日之前购买或续订了商业计划，则只需 150 个许可证即可获得数据迁移服务的资格。</span><span class="sxs-lookup"><span data-stu-id="73f61-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="73f61-114">对于教育计划，只有付费教职员工许可证才有资格获得数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="73f61-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="73f61-115">注意事项</span><span class="sxs-lookup"><span data-stu-id="73f61-115">Considerations</span></span>

  - <span data-ttu-id="73f61-116">你的源环境必须满足特定的期望才能将数据迁移到 Office 365。</span><span class="sxs-lookup"><span data-stu-id="73f61-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="73f61-117">有关 Exchange、SharePoint 和 OneDrive for Business 的源环境期望的更多信息，请参阅[产品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="73f61-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="73f61-118">我们需要对你的源环境和 Office 365 租户具有适当的访问权限和权限才能提供数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="73f61-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="73f61-119">我们的数据迁移服务并非为满足特殊法律或法规要求的数据而设计或以此为目的。</span><span class="sxs-lookup"><span data-stu-id="73f61-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="73f61-120">我们迁移数据时，可将其传输到我们维护设施的任何位置、从中进行存储和处理（除非为你的 FastTrack 迁移项目提供了其他位置）。</span><span class="sxs-lookup"><span data-stu-id="73f61-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="73f61-121">我们无法保证邮件或文件的迁移速度。</span><span class="sxs-lookup"><span data-stu-id="73f61-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="73f61-122">不可预见的问题（例如源环境中不可读或损坏的项）可能会阻止我们迁移某些数据项。</span><span class="sxs-lookup"><span data-stu-id="73f61-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="73f61-123">我们无法控制的外部因素（例如对第三方应用程序编程接口 (API) 的更改）可能会导致我们的数据迁移服务发生更改、延迟或暂停。</span><span class="sxs-lookup"><span data-stu-id="73f61-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="73f61-124">迁移服务可用性</span><span class="sxs-lookup"><span data-stu-id="73f61-124">Migration service availability</span></span>

  - <span data-ttu-id="73f61-125">**对于商业和英国政府客户：** 我们每周七 (7) 天，每天 24 小时 (24x7) 提供数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="73f61-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="73f61-126">**对于美国政府/DOD 客户：** 我们每周五 (5) 天，每天 24 小时 (24x5) 提供数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="73f61-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="73f61-127">到 Exchange Online 的迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-127">Migration to Exchange Online</span></span>

<span data-ttu-id="73f61-128">当你选择使用 FastTrack 将电子邮件迁移到 Exchange Online 时，我们将提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="73f61-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="73f61-129">我们提供指导，以帮助你计划迁移、配置源环境和 Exchange Online，并利用我们的数据迁移服务来迁移邮箱。</span><span class="sxs-lookup"><span data-stu-id="73f61-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="73f61-130">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="73f61-130">You create and schedule your migration events.</span></span> <span data-ttu-id="73f61-131">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="73f61-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="73f61-132">迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源邮箱中的的邮件已迁移到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="73f61-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="73f61-133">注意事项</span><span class="sxs-lookup"><span data-stu-id="73f61-133">Considerations</span></span>

  - <span data-ttu-id="73f61-134">迁移前，必须完成 Exchange Online 的FastTrack 核心载入；</span><span class="sxs-lookup"><span data-stu-id="73f61-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="73f61-135">如果你自行执行载入，则必须通过必需的检查和先决条件。</span><span class="sxs-lookup"><span data-stu-id="73f61-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="73f61-136">有关详细信息，请参阅[产品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="73f61-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="73f61-137">FastTrack 仅迁移到活动的 Office 365 邮箱。</span><span class="sxs-lookup"><span data-stu-id="73f61-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="73f61-138">如果要从本地 Exchange 环境迁移，则必须满足特定要求。</span><span class="sxs-lookup"><span data-stu-id="73f61-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="73f61-139">有关详细信息，请参阅[配置混合部署先决条件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="73f61-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="73f61-140">每个源环境都必须处于源环境中相应产品的最新服务包 (SP) 和汇总更新 (RU)/累积更新 (CU) 级别。</span><span class="sxs-lookup"><span data-stu-id="73f61-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="73f61-141">位于本地 Active Directory 中的通讯组列表（*MailEnabledGroup* 对象）和外部联系人（*MailEnabledContact* 对象）不是邮箱数据迁移的一部分。</span><span class="sxs-lookup"><span data-stu-id="73f61-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="73f61-142">但是，你可以使用 Azure Active Directory (Azure AD) Connect 将它们同步。</span><span class="sxs-lookup"><span data-stu-id="73f61-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="73f61-143">源环境</span><span class="sxs-lookup"><span data-stu-id="73f61-143">Source environments</span></span>

<span data-ttu-id="73f61-144">我们的数据迁移服务从以下源环境迁移数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="73f61-145">具有单个或多个 Exchange 组织的单个或多个 Active Directory 林（每个 Exchange 邮件系统均须为 Exchange 2010 或更高版本）。</span><span class="sxs-lookup"><span data-stu-id="73f61-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="73f61-146">一个支持 IMAP 的电子邮件环境。</span><span class="sxs-lookup"><span data-stu-id="73f61-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="73f61-147">G 套件环境（仅限 Gmail、联系人和日历）</span><span class="sxs-lookup"><span data-stu-id="73f61-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="73f61-148">下表显示了特定于每个源环境的迁移详细信息：</span><span class="sxs-lookup"><span data-stu-id="73f61-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="73f61-149"><strong>源环境</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="73f61-150"><strong>迁移类型</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="73f61-151"><strong>迁移内容</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="73f61-152"><strong>不迁移的内容</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="73f61-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="73f61-154">
<strong>注意：</strong> 有关本地 Exchange 依赖项，请参阅混合 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">部署先决条件</span></a>。</span><span class="sxs-lookup"><span data-stu-id="73f61-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="73f61-155">使用混合部署进行的迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="73f61-156">电子邮件</span><span class="sxs-lookup"><span data-stu-id="73f61-156">Emails</span></span></li>
<li><span data-ttu-id="73f61-157">服务器端邮箱规则</span><span class="sxs-lookup"><span data-stu-id="73f61-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="73f61-158">代理</span><span class="sxs-lookup"><span data-stu-id="73f61-158">Delegates</span></span></li>
<li><span data-ttu-id="73f61-159">邮箱联系人</span><span class="sxs-lookup"><span data-stu-id="73f61-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="73f61-160">日历</span><span class="sxs-lookup"><span data-stu-id="73f61-160">Calendar</span></span> </li>
<li> <span data-ttu-id="73f61-161">任务</span><span class="sxs-lookup"><span data-stu-id="73f61-161">Tasks</span></span> </li>
<li> <span data-ttu-id="73f61-162">权限管理的电子邮件</span><span class="sxs-lookup"><span data-stu-id="73f61-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="73f61-163">加密电子邮件</span><span class="sxs-lookup"><span data-stu-id="73f61-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="73f61-164">签名</span><span class="sxs-lookup"><span data-stu-id="73f61-164">Signatures</span></span> </li>
<li> <span data-ttu-id="73f61-165">与用户的邮箱一起迁移的个人存档</span><span class="sxs-lookup"><span data-stu-id="73f61-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="73f61-166">可恢复的项目</span><span class="sxs-lookup"><span data-stu-id="73f61-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="73f61-167">公用文件夹</span><span class="sxs-lookup"><span data-stu-id="73f61-167">Public folders</span></span> </li>
<li> <span data-ttu-id="73f61-168">超出邮件大小限制的所有电子邮件</span><span class="sxs-lookup"><span data-stu-id="73f61-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="73f61-169">日记存档或任何第三方存档解决方案</span><span class="sxs-lookup"><span data-stu-id="73f61-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="73f61-170">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="73f61-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="73f61-171">来自个人存储表 (PST) 文件的存档数据</span><span class="sxs-lookup"><span data-stu-id="73f61-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="73f61-172">已损坏的项目</span><span class="sxs-lookup"><span data-stu-id="73f61-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="73f61-173">非活动邮箱</span><span class="sxs-lookup"><span data-stu-id="73f61-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="73f61-174">客户端邮箱规则</span><span class="sxs-lookup"><span data-stu-id="73f61-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="73f61-175"><strong>G 套件环境（仅限 Gmail、联系人和日历）</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="73f61-176">
<strong>注意：</strong> G 套件环境必须满足执行 G 套件迁移 <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">中所述的先决条件</a>。</span><span class="sxs-lookup"><span data-stu-id="73f61-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="73f61-177">直接转换或暂存</span><span class="sxs-lookup"><span data-stu-id="73f61-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-178">电子邮件</span><span class="sxs-lookup"><span data-stu-id="73f61-178">Emails</span></span> </li>
<li> <span data-ttu-id="73f61-179">邮箱联系人（每个联系人最多迁移 3 个电子邮件地址）</span><span class="sxs-lookup"><span data-stu-id="73f61-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="73f61-180">日历</span><span class="sxs-lookup"><span data-stu-id="73f61-180">Calendar</span></span> </li>
<li> <span data-ttu-id="73f61-181">标签</span><span class="sxs-lookup"><span data-stu-id="73f61-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="73f61-182">规则</span><span class="sxs-lookup"><span data-stu-id="73f61-182">Rules</span></span> </li>
<li> <span data-ttu-id="73f61-183">代理</span><span class="sxs-lookup"><span data-stu-id="73f61-183">Delegates</span></span> </li>
<li> <span data-ttu-id="73f61-184">签名</span><span class="sxs-lookup"><span data-stu-id="73f61-184">Signatures</span></span> </li>
<li> <span data-ttu-id="73f61-185">任务</span><span class="sxs-lookup"><span data-stu-id="73f61-185">Tasks</span></span> </li>
<li> <span data-ttu-id="73f61-186">超出邮件大小限制的所有电子邮件或附件</span><span class="sxs-lookup"><span data-stu-id="73f61-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="73f61-187">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="73f61-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="73f61-188">来自 PST 文件或任何第三方存档解决方案（例如 Google Vault）的存档数据</span><span class="sxs-lookup"><span data-stu-id="73f61-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="73f61-189">权限管理或加密电子邮件</span><span class="sxs-lookup"><span data-stu-id="73f61-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="73f61-190">已损坏的项目</span><span class="sxs-lookup"><span data-stu-id="73f61-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="73f61-191">Google Hangout\*\*</span><span class="sxs-lookup"><span data-stu-id="73f61-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="73f61-192">Google 组</span><span class="sxs-lookup"><span data-stu-id="73f61-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="73f61-193">资源邮箱</span><span class="sxs-lookup"><span data-stu-id="73f61-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="73f61-194">非活动邮箱</span><span class="sxs-lookup"><span data-stu-id="73f61-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="73f61-195">假期设置和自动答复设置</span><span class="sxs-lookup"><span data-stu-id="73f61-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="73f61-196">共享日历、云附件、Google Hangout 链接和事件颜色</span><span class="sxs-lookup"><span data-stu-id="73f61-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="73f61-197">\*\*迁移另存为标签的环聊对话。</span><span class="sxs-lookup"><span data-stu-id="73f61-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="73f61-198"><strong>IMAP4 源（如 Domino、GroupWise 或 Zimbra）</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="73f61-199">使用本机 IMAP4 工具进行迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="73f61-200">电子邮件</span><span class="sxs-lookup"><span data-stu-id="73f61-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="73f61-201">Rules</span><span class="sxs-lookup"><span data-stu-id="73f61-201">Rules</span></span> </li>
<li> <span data-ttu-id="73f61-202">代理</span><span class="sxs-lookup"><span data-stu-id="73f61-202">Delegates</span></span> </li>
<li> <span data-ttu-id="73f61-203">通讯组列表</span><span class="sxs-lookup"><span data-stu-id="73f61-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="73f61-204">外部联系人</span><span class="sxs-lookup"><span data-stu-id="73f61-204">External contacts</span></span> </li>
<li> <span data-ttu-id="73f61-205">启用邮件的用户</span><span class="sxs-lookup"><span data-stu-id="73f61-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="73f61-206">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="73f61-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="73f61-207">邮箱联系人</span><span class="sxs-lookup"><span data-stu-id="73f61-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="73f61-208">日历</span><span class="sxs-lookup"><span data-stu-id="73f61-208">Calendar</span></span> </li>
<li> <span data-ttu-id="73f61-209">签名</span><span class="sxs-lookup"><span data-stu-id="73f61-209">Signatures</span></span> </li>
<li> <span data-ttu-id="73f61-210">任务</span><span class="sxs-lookup"><span data-stu-id="73f61-210">Tasks</span></span> </li>
<li> <span data-ttu-id="73f61-211">超出邮件大小限制的所有电子邮件</span><span class="sxs-lookup"><span data-stu-id="73f61-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="73f61-212">存档数据</span><span class="sxs-lookup"><span data-stu-id="73f61-212">Archive data</span></span> </li>
<li> <span data-ttu-id="73f61-213">加密电子邮件</span><span class="sxs-lookup"><span data-stu-id="73f61-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="73f61-214">已损坏的项目</span><span class="sxs-lookup"><span data-stu-id="73f61-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="73f61-215">非活动邮箱</span><span class="sxs-lookup"><span data-stu-id="73f61-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-exchange-online-migrations"></a><span data-ttu-id="73f61-216">FastTrack 对 Exchange Online 迁移的责任</span><span class="sxs-lookup"><span data-stu-id="73f61-216">FastTrack responsibilities for Exchange Online migrations</span></span>

<span data-ttu-id="73f61-217">我们的 FastTrack 专家在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="73f61-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="73f61-218">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="73f61-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="73f61-219">我们的 FastTrack 专家还执行以下特定于 Exchange 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="73f61-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="73f61-220">提供指导以帮助你在源环境和 Exchange Online 之间启用 SMTP 邮件路由共存（如果适用）。</span><span class="sxs-lookup"><span data-stu-id="73f61-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="73f61-221">你的责任</span><span class="sxs-lookup"><span data-stu-id="73f61-221">Your responsibilities</span></span>

<span data-ttu-id="73f61-222">你在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="73f61-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="73f61-223">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="73f61-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="73f61-224">此外，你还将执行以下特定于 Exchange 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="73f61-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="73f61-225">完成 Exchange Online 的FastTrack 核心载入。</span><span class="sxs-lookup"><span data-stu-id="73f61-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="73f61-226">如果你自行执行载入，则必须通过必需的检查和先决条件。</span><span class="sxs-lookup"><span data-stu-id="73f61-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="73f61-227">有关详细信息，请参阅[产品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="73f61-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="73f61-228">根据 Office 365 准则安装客户端软件的相应级别。</span><span class="sxs-lookup"><span data-stu-id="73f61-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="73f61-229">有关详细信息，请参阅[新式工作区](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)。</span><span class="sxs-lookup"><span data-stu-id="73f61-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="73f61-230">如果要从本地 Exchange 环境迁移，需满足特定要求。</span><span class="sxs-lookup"><span data-stu-id="73f61-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="73f61-231">有关详细信息，请参阅[配置混合部署先决条件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="73f61-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="73f61-232">确保每个源环境都位于最新服务包 (SP) 和汇总 (RU)/累积更新 (CU) 级别（如果适用）。</span><span class="sxs-lookup"><span data-stu-id="73f61-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="73f61-233">配置和验证源环境和 Exchange Online 之间的 SMTP 邮件路由共存（如果适用）。</span><span class="sxs-lookup"><span data-stu-id="73f61-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="73f61-234">确保源邮箱大小不超过目标邮箱配额。</span><span class="sxs-lookup"><span data-stu-id="73f61-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="73f61-235">根据源平台的不同，可能需要将源数据限制为目标邮箱配额的 85%。</span><span class="sxs-lookup"><span data-stu-id="73f61-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="73f61-236">根据需要迁移客户端数据。</span><span class="sxs-lookup"><span data-stu-id="73f61-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="73f61-237">这包括但不限于本地通讯簿、本地 PST 文件中的数据、Outlook 规则和本地 Outlook 设置。</span><span class="sxs-lookup"><span data-stu-id="73f61-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="73f61-238">帮助最终用户修正客户端迁移问题。</span><span class="sxs-lookup"><span data-stu-id="73f61-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="73f61-239">到 SharePoint Online 的迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="73f61-240">当你选择使用 FastTrack 将文件迁移到 SharePoint Online 时，我们将提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="73f61-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="73f61-241">我们提供指导，以帮助你计划迁移、配置源环境和 SharePoint Online，并利用我们的数据迁移服务来迁移文件。</span><span class="sxs-lookup"><span data-stu-id="73f61-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="73f61-242">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="73f61-242">You create and schedule your migration events.</span></span> <span data-ttu-id="73f61-243">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="73f61-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="73f61-244">迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源中的的文件已迁移到 SharePoint Online。</span><span class="sxs-lookup"><span data-stu-id="73f61-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="73f61-245">注意事项</span><span class="sxs-lookup"><span data-stu-id="73f61-245">Considerations</span></span>

 - <span data-ttu-id="73f61-246">所有迁移均受 SharePoint Online 配额的限制。</span><span class="sxs-lookup"><span data-stu-id="73f61-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="73f61-247">有关详细信息， <a href="https://go.microsoft.com/fwlink/?LinkId=698855">请参阅 SharePoint</a> 限制。</span><span class="sxs-lookup"><span data-stu-id="73f61-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="73f61-248">建议将迁移总量限制在你享有的整体 SharePoint Online 存储配额（包括你可能单独购买的其他存储）的 75% 以内。</span><span class="sxs-lookup"><span data-stu-id="73f61-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="73f61-249">源环境详细信息</span><span class="sxs-lookup"><span data-stu-id="73f61-249">Source environment details</span></span>

<span data-ttu-id="73f61-250">我们的数据迁移服务从以下源环境迁移数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="73f61-251">文件共享（支持 SMB 2.0 前向的设备上的服务器消息块 (SMB) 文件共享）。</span><span class="sxs-lookup"><span data-stu-id="73f61-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="73f61-252">单个 G 套件环境（仅限 Google Drive）。</span><span class="sxs-lookup"><span data-stu-id="73f61-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="73f61-253">Box（Starter、Business、Enterprise）。</span><span class="sxs-lookup"><span data-stu-id="73f61-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="73f61-254">用于 Teams的 Dropbox（标准版和高级版）</span><span class="sxs-lookup"><span data-stu-id="73f61-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="73f61-255">下表显示了特定于每个源环境的迁移详细信息：</span><span class="sxs-lookup"><span data-stu-id="73f61-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="73f61-256"><strong>源环境</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="73f61-257"><strong>迁移类型</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="73f61-258"><strong>迁移内容</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="73f61-259"><strong>不迁移的内容</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="73f61-260"><strong>任何支持 SMB 2.0 及更高版本的文件共享设备</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="73f61-261">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="73f61-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-262">文档</span><span class="sxs-lookup"><span data-stu-id="73f61-262">Documents</span></span> </li>
<li> <span data-ttu-id="73f61-263">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="73f61-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="73f61-264">用户级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="73f61-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="73f61-265">组级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="73f61-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="73f61-266">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="73f61-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="73f61-267">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="73f61-268">创建日期</span><span class="sxs-lookup"><span data-stu-id="73f61-268">Created date</span></span> </li>
<li> <span data-ttu-id="73f61-269">修改日期</span><span class="sxs-lookup"><span data-stu-id="73f61-269">Modified date</span></span> </li>
<li> <span data-ttu-id="73f61-270">创建者</span><span class="sxs-lookup"><span data-stu-id="73f61-270">Created by</span></span> </li>
<li> <span data-ttu-id="73f61-271">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="73f61-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="73f61-272">\*必须配置目录同步。</span><span class="sxs-lookup"><span data-stu-id="73f61-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="73f61-273">只迁移对 Windows 文件资源管理器公开的 NTFS 权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="73f61-274">不会迁移文件共享设备上直接托管的权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="73f61-275">如果数据存储在 SMB 2.0 设备上，只会迁移 SMB 协议公开的与 NTFS 等同的权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-276">所有权历史记录和旧版本</span><span class="sxs-lookup"><span data-stu-id="73f61-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="73f61-277">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="73f61-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="73f61-278">旧版本</span><span class="sxs-lookup"><span data-stu-id="73f61-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="73f61-279">Windows 文件和文件夹属性（如只读和隐藏）</span><span class="sxs-lookup"><span data-stu-id="73f61-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="73f61-280">非 Windows 新技术文件系统 (NTFS) 和 NTFS 高级权限和特殊设置：</span><span class="sxs-lookup"><span data-stu-id="73f61-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="73f61-281">显式拒绝权限（在迁移后删除的权限、从属于并行权限的内容或父文件夹上的权限）</span><span class="sxs-lookup"><span data-stu-id="73f61-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="73f61-282">NTFS 审核配置</span><span class="sxs-lookup"><span data-stu-id="73f61-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="73f61-283">文件分类基础结构 (FCI) 提供的附加文件元数据</span><span class="sxs-lookup"><span data-stu-id="73f61-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="73f61-284">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="73f61-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="73f61-285">隐藏的共享</span><span class="sxs-lookup"><span data-stu-id="73f61-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="73f61-286">共享（如在共享级别授予的权限）</span><span class="sxs-lookup"><span data-stu-id="73f61-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="73f61-287">超出当前 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制的文件或文件夹</span></a> </span><span class="sxs-lookup"><span data-stu-id="73f61-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="73f61-288"><strong>单个 G 套件环境（仅限 Google 云端硬盘）</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="73f61-289">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="73f61-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-290">Google 文档、工作表和幻灯片（文件转换为等同的 Office 格式），包括超过10 MB的</span><span class="sxs-lookup"><span data-stu-id="73f61-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="73f61-291">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="73f61-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="73f61-292">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="73f61-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="73f61-293">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="73f61-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="73f61-294">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="73f61-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="73f61-295">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="73f61-296">创建日期</span><span class="sxs-lookup"><span data-stu-id="73f61-296">Created date</span></span> </li>
<li> <span data-ttu-id="73f61-297">修改日期</span><span class="sxs-lookup"><span data-stu-id="73f61-297">Modified date</span></span> </li>
<li> <span data-ttu-id="73f61-298">创建者</span><span class="sxs-lookup"><span data-stu-id="73f61-298">Created by</span></span> </li>
<li> <span data-ttu-id="73f61-299">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="73f61-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="73f61-300">共享驱动器 （文件夹和文件）</span><span class="sxs-lookup"><span data-stu-id="73f61-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="73f61-301">属于 Google 云端硬盘帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="73f61-302">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="73f61-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="73f61-303">文件和文件夹说明、文件夹颜色</span><span class="sxs-lookup"><span data-stu-id="73f61-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="73f61-304">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-305">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-306">高级元数据</span><span class="sxs-lookup"><span data-stu-id="73f61-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="73f61-307">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="73f61-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="73f61-308">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="73f61-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="73f61-309">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="73f61-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="73f61-310">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="73f61-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="73f61-311">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="73f61-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="73f61-312">Google 相册、Forms、地图和其他已连接应用</span><span class="sxs-lookup"><span data-stu-id="73f61-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="73f61-313">Google 绘图</span><span class="sxs-lookup"><span data-stu-id="73f61-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="73f61-314">组织外部的共享内容</span><span class="sxs-lookup"><span data-stu-id="73f61-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="73f61-315">不属于Google 云端硬盘帐户的内容被迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="73f61-316">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Google 云端硬盘管理报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="73f61-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="73f61-317">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="73f61-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="73f61-318">共享驱动器成员资格权限（<strong>注意</strong>：使用 Google 云端硬盘管理报告来标识共享驱动器成员资格。</span><span class="sxs-lookup"><span data-stu-id="73f61-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="73f61-319">指示最终用户迁移前在目标上配置这些成员资格设置。）</span><span class="sxs-lookup"><span data-stu-id="73f61-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="73f61-320">标记为受限或不可复制的文件</span><span class="sxs-lookup"><span data-stu-id="73f61-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="73f61-321">超出当前 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制的文件或文件夹</span></a> </span><span class="sxs-lookup"><span data-stu-id="73f61-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="73f61-322"><strong>Box（Starter、Business、Enterprise）</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="73f61-323">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="73f61-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-324">文档</span><span class="sxs-lookup"><span data-stu-id="73f61-324">Documents</span></span> </li>
<li> <span data-ttu-id="73f61-325">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="73f61-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="73f61-326">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="73f61-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="73f61-327">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="73f61-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="73f61-328">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="73f61-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="73f61-329">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="73f61-330">创建日期</span><span class="sxs-lookup"><span data-stu-id="73f61-330">Created date</span></span> </li>
<li> <span data-ttu-id="73f61-331">修改日期</span><span class="sxs-lookup"><span data-stu-id="73f61-331">Modified date</span></span> </li>
<li> <span data-ttu-id="73f61-332">创建者</span><span class="sxs-lookup"><span data-stu-id="73f61-332">Created by</span></span> </li>
<li> <span data-ttu-id="73f61-333">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="73f61-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="73f61-334">属于 Box 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="73f61-335">转换为 Word 文档 (格式的方框) </span><span class="sxs-lookup"><span data-stu-id="73f61-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="73f61-336">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="73f61-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="73f61-337">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="73f61-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="73f61-338">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-339">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-340">Box 标记和高级元数据</span><span class="sxs-lookup"><span data-stu-id="73f61-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="73f61-341">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="73f61-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="73f61-342">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="73f61-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="73f61-343">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="73f61-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="73f61-344">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="73f61-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="73f61-345">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="73f61-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="73f61-346">Box 应用、书签、收藏夹和工作流</span><span class="sxs-lookup"><span data-stu-id="73f61-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="73f61-347">不属于已迁移 Box 帐户的内容</span><span class="sxs-lookup"><span data-stu-id="73f61-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="73f61-348">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Box 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="73f61-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="73f61-349">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="73f61-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="73f61-350">超出当前 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制的文件或文件夹</span></a> </span><span class="sxs-lookup"><span data-stu-id="73f61-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="73f61-351"><strong>用于 Teams的 Dropbox（标准版和高级版）</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="73f61-352">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="73f61-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-353">文档</span><span class="sxs-lookup"><span data-stu-id="73f61-353">Documents</span></span> </li>
<li> <span data-ttu-id="73f61-354">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="73f61-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="73f61-355">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="73f61-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="73f61-356">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="73f61-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="73f61-357">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="73f61-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="73f61-358">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="73f61-359">创建日期</span><span class="sxs-lookup"><span data-stu-id="73f61-359">Created date</span></span> </li>
<li> <span data-ttu-id="73f61-360">修改日期</span><span class="sxs-lookup"><span data-stu-id="73f61-360">Modified date</span></span> </li>
<li> <span data-ttu-id="73f61-361">创建者</span><span class="sxs-lookup"><span data-stu-id="73f61-361">Created by</span></span> </li>
<li> <span data-ttu-id="73f61-362">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="73f61-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="73f61-363">共享团队文件夹和内容</span><span class="sxs-lookup"><span data-stu-id="73f61-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="73f61-364">属于 Dropbox 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="73f61-365">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="73f61-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="73f61-366">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="73f61-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="73f61-367">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-368">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-369">高级元数据</span><span class="sxs-lookup"><span data-stu-id="73f61-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="73f61-370">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="73f61-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="73f61-371">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="73f61-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="73f61-372">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="73f61-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="73f61-373">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="73f61-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="73f61-374">已卸载的 Dropbox 文件夹</span><span class="sxs-lookup"><span data-stu-id="73f61-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="73f61-375">已删除或已断开连接的用户</span><span class="sxs-lookup"><span data-stu-id="73f61-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="73f61-376">Dropbox Paper 文件、Dropbox Showcase 和 Dropbox Space</span><span class="sxs-lookup"><span data-stu-id="73f61-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="73f61-377">Dropbox 应用及收藏夹（已固定或加星标）</span><span class="sxs-lookup"><span data-stu-id="73f61-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="73f61-378">已迁移的 Dropbox 帐户不拥有的内容</span><span class="sxs-lookup"><span data-stu-id="73f61-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="73f61-379">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Dropbox 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="73f61-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="73f61-380">指示最终用户在迁移后与外部用户重新共享内容）</span><span class="sxs-lookup"><span data-stu-id="73f61-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="73f61-381">超出当前 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制的文件或文件夹</span></a> </span><span class="sxs-lookup"><span data-stu-id="73f61-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-sharepoint-online-migrations"></a><span data-ttu-id="73f61-382">SharePoint Online 迁移的 FastTrack 责任</span><span class="sxs-lookup"><span data-stu-id="73f61-382">FastTrack responsibilities for SharePoint Online migrations</span></span>

<span data-ttu-id="73f61-383">我们的 FastTrack 专家在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="73f61-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="73f61-384">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息</span><span class="sxs-lookup"><span data-stu-id="73f61-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="73f61-385">你的责任</span><span class="sxs-lookup"><span data-stu-id="73f61-385">Your responsibilities</span></span>

<span data-ttu-id="73f61-386">你在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="73f61-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="73f61-387">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息</span><span class="sxs-lookup"><span data-stu-id="73f61-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="73f61-388">此外，你还将执行以下特定于 SharePoint Online 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="73f61-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="73f61-389">预置将作为迁移事件目标的所有 SharePoint 团队网站。</span><span class="sxs-lookup"><span data-stu-id="73f61-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="73f61-390">到 OneDrive for Business 的迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="73f61-391">当你选择使用 FastTrack 将文件迁移到 OneDrive for Business 时，我们将提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="73f61-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="73f61-392">我们提供指导，以帮助你计划迁移、配置源环境和 OneDrive for Business，并利用我们的数据迁移服务来迁移文件。</span><span class="sxs-lookup"><span data-stu-id="73f61-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="73f61-393">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="73f61-393">You create and schedule your migration events.</span></span> <span data-ttu-id="73f61-394">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="73f61-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="73f61-395">迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源中的的文件已迁移到 OneDrive for Business。</span><span class="sxs-lookup"><span data-stu-id="73f61-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="73f61-396">注意事项</span><span class="sxs-lookup"><span data-stu-id="73f61-396">Considerations</span></span>

  - <span data-ttu-id="73f61-397">所有迁移均受 SharePoint Online 配额的限制。</span><span class="sxs-lookup"><span data-stu-id="73f61-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="73f61-398">有关详细信息， <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> 请参阅 SharePoint</a> 限制。</span><span class="sxs-lookup"><span data-stu-id="73f61-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="73f61-399">建议将迁移数据总量限制在你享有的整体 SharePoint Online 存储配额（包括你可能单独购买的其他存储）的 75% 以内。</span><span class="sxs-lookup"><span data-stu-id="73f61-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="73f61-400">FastTrack 仅迁移到活动的 OneDrive for Business 驱动器。</span><span class="sxs-lookup"><span data-stu-id="73f61-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="73f61-401">源环境详细信息</span><span class="sxs-lookup"><span data-stu-id="73f61-401">Source environment details</span></span>

<span data-ttu-id="73f61-402">我们的数据迁移服务从以下源环境迁移数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="73f61-403">文件共享（SMB 文件在支持 SMB 2.0 前向的设备上共享）。</span><span class="sxs-lookup"><span data-stu-id="73f61-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="73f61-404">单个 G 套件环境（仅限 Google 云端硬盘）。</span><span class="sxs-lookup"><span data-stu-id="73f61-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="73f61-405">Box（Starter、Business、Enterprise）。</span><span class="sxs-lookup"><span data-stu-id="73f61-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="73f61-406">用于 Teams的 Dropbox（标准版和高级版）</span><span class="sxs-lookup"><span data-stu-id="73f61-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="73f61-407">下表显示了特定于每个源环境的迁移详细信息：</span><span class="sxs-lookup"><span data-stu-id="73f61-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="73f61-408"><strong>源环境</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="73f61-409"><strong>迁移类型</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="73f61-410"><strong>迁移内容</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="73f61-411"><strong>不迁移的内容</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="73f61-412"><strong>任何支持 SMB 2.0 及更高版本的文件共享设备</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="73f61-413">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="73f61-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-414">文档</span><span class="sxs-lookup"><span data-stu-id="73f61-414">Documents</span></span> </li>
<li> <span data-ttu-id="73f61-415">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="73f61-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="73f61-416">用户级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="73f61-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="73f61-417">组级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="73f61-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="73f61-418">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="73f61-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="73f61-419">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="73f61-420">创建日期</span><span class="sxs-lookup"><span data-stu-id="73f61-420">Created date</span></span> </li>
<li> <span data-ttu-id="73f61-421">修改日期</span><span class="sxs-lookup"><span data-stu-id="73f61-421">Modified date</span></span> </li>
<li> <span data-ttu-id="73f61-422">创建者</span><span class="sxs-lookup"><span data-stu-id="73f61-422">Created by</span></span> </li>
<li> <span data-ttu-id="73f61-423">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="73f61-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="73f61-424">\*必须配置目录同步。</span><span class="sxs-lookup"><span data-stu-id="73f61-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="73f61-425">只迁移对 Windows 文件资源管理器公开的 NTFS 权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="73f61-426">不会迁移文件共享设备上直接托管的权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="73f61-427">如果数据存储在 SMB 2.0 设备上，只会迁移 SMB 协议公开的与 NTFS 等同的权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="73f61-428">所有权历史记录和旧版本</span><span class="sxs-lookup"><span data-stu-id="73f61-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="73f61-429">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="73f61-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="73f61-430">旧版本</span><span class="sxs-lookup"><span data-stu-id="73f61-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="73f61-431">Windows 文件和文件夹属性（如只读和隐藏）</span><span class="sxs-lookup"><span data-stu-id="73f61-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="73f61-432">非 Windows 新技术文件系统 (NTFS) 和 NTFS 高级权限和特殊设置：</span><span class="sxs-lookup"><span data-stu-id="73f61-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="73f61-433">显式拒绝权限（在迁移后删除的权限、从属于并行权限的内容或父文件夹上的权限）</span><span class="sxs-lookup"><span data-stu-id="73f61-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="73f61-434">NTFS 审核配置</span><span class="sxs-lookup"><span data-stu-id="73f61-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="73f61-435">文件分类基础结构 (FCI) 提供的附加文件元数据</span><span class="sxs-lookup"><span data-stu-id="73f61-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="73f61-436">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="73f61-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="73f61-437">隐藏的共享</span><span class="sxs-lookup"><span data-stu-id="73f61-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="73f61-438">共享（如在共享级别授予的权限）</span><span class="sxs-lookup"><span data-stu-id="73f61-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="73f61-439">超出当前 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制的文件或文件夹</span></a> </span><span class="sxs-lookup"><span data-stu-id="73f61-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="73f61-440"><strong>单个 G 套件环境（仅限 Google 云端硬盘）</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="73f61-441">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="73f61-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-442">Google 文档、工作表和幻灯片（文件包括超过10 MB的，转换为等同的 Office 格式）</span><span class="sxs-lookup"><span data-stu-id="73f61-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="73f61-443">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="73f61-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="73f61-444">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="73f61-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="73f61-445">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="73f61-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="73f61-446">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="73f61-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="73f61-447">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="73f61-448">创建日期</span><span class="sxs-lookup"><span data-stu-id="73f61-448">Created date</span></span> </li>
<li> <span data-ttu-id="73f61-449">修改日期</span><span class="sxs-lookup"><span data-stu-id="73f61-449">Modified date</span></span> </li>
<li> <span data-ttu-id="73f61-450">创建者</span><span class="sxs-lookup"><span data-stu-id="73f61-450">Created by</span></span> </li>
<li> <span data-ttu-id="73f61-451">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="73f61-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="73f61-452">共享驱动器 （文件夹和文件）</span><span class="sxs-lookup"><span data-stu-id="73f61-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="73f61-453">属于 Google 云端硬盘帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="73f61-454">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="73f61-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="73f61-455">文件和文件夹说明、文件夹颜色</span><span class="sxs-lookup"><span data-stu-id="73f61-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="73f61-456">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-457">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-458">高级元数据</span><span class="sxs-lookup"><span data-stu-id="73f61-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="73f61-459">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="73f61-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="73f61-460">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="73f61-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="73f61-461">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="73f61-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="73f61-462">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="73f61-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="73f61-463">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="73f61-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="73f61-464">Google 相册、Forms、地图和其他已连接应用</span><span class="sxs-lookup"><span data-stu-id="73f61-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="73f61-465">Google 绘图</span><span class="sxs-lookup"><span data-stu-id="73f61-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="73f61-466">组织外部的共享内容</span><span class="sxs-lookup"><span data-stu-id="73f61-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="73f61-467">不属于Google 云端硬盘帐户的内容被迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="73f61-468">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Google 云端硬盘管理报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="73f61-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="73f61-469">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="73f61-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="73f61-470">共享驱动器成员资格权限（<strong>注意</strong>：使用 Google 云端硬盘管理报告来标识共享驱动器成员资格。</span><span class="sxs-lookup"><span data-stu-id="73f61-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="73f61-471">指示最终用户迁移前在目标上配置这些成员资格设置。）</span><span class="sxs-lookup"><span data-stu-id="73f61-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="73f61-472">超出当前 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制的文件或文件夹</span></a> </span><span class="sxs-lookup"><span data-stu-id="73f61-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="73f61-473"><strong>Box（Starter、Business、Enterprise）</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="73f61-474">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="73f61-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-475">文档</span><span class="sxs-lookup"><span data-stu-id="73f61-475">Documents</span></span> </li>
<li> <span data-ttu-id="73f61-476">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="73f61-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="73f61-477">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="73f61-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="73f61-478">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="73f61-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="73f61-479">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="73f61-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="73f61-480">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="73f61-481">创建日期</span><span class="sxs-lookup"><span data-stu-id="73f61-481">Created date</span></span> </li>
<li> <span data-ttu-id="73f61-482">修改日期</span><span class="sxs-lookup"><span data-stu-id="73f61-482">Modified date</span></span> </li>
<li> <span data-ttu-id="73f61-483">创建者</span><span class="sxs-lookup"><span data-stu-id="73f61-483">Created by</span></span> </li>
<li> <span data-ttu-id="73f61-484">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="73f61-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="73f61-485">属于 Box 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="73f61-486">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="73f61-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="73f61-487">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="73f61-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="73f61-488">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-489">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-490">Box 标记和高级元数据</span><span class="sxs-lookup"><span data-stu-id="73f61-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="73f61-491">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="73f61-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="73f61-492">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="73f61-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="73f61-493">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="73f61-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="73f61-494">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="73f61-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="73f61-495">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="73f61-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="73f61-496">Box 应用、书签、收藏夹和工作流</span><span class="sxs-lookup"><span data-stu-id="73f61-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="73f61-497">不属于已迁移 Box 帐户的内容</span><span class="sxs-lookup"><span data-stu-id="73f61-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="73f61-498">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Box 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="73f61-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="73f61-499">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="73f61-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="73f61-500">超出当前 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制的文件或文件夹</span></a> </span><span class="sxs-lookup"><span data-stu-id="73f61-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="73f61-501"><strong>用于 Teams的 Dropbox（标准版和高级版）</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="73f61-502">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="73f61-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-503">文档</span><span class="sxs-lookup"><span data-stu-id="73f61-503">Documents</span></span> </li>
<li> <span data-ttu-id="73f61-504">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="73f61-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="73f61-505">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="73f61-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="73f61-506">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="73f61-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="73f61-507">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="73f61-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="73f61-508">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="73f61-509">创建日期</span><span class="sxs-lookup"><span data-stu-id="73f61-509">Created date</span></span> </li>
<li> <span data-ttu-id="73f61-510">修改日期</span><span class="sxs-lookup"><span data-stu-id="73f61-510">Modified date</span></span> </li>
<li> <span data-ttu-id="73f61-511">创建者</span><span class="sxs-lookup"><span data-stu-id="73f61-511">Created by</span></span> </li>
<li> <span data-ttu-id="73f61-512">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="73f61-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="73f61-513">共享团队文件夹和内容</span><span class="sxs-lookup"><span data-stu-id="73f61-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="73f61-514">属于 Dropbox 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="73f61-515">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="73f61-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="73f61-516">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="73f61-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="73f61-517">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-518">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-519">高级元数据</span><span class="sxs-lookup"><span data-stu-id="73f61-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="73f61-520">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="73f61-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="73f61-521">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="73f61-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="73f61-522">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="73f61-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="73f61-523">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="73f61-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="73f61-524">已卸载的 Dropbox 文件夹</span><span class="sxs-lookup"><span data-stu-id="73f61-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="73f61-525">已删除或已断开连接的用户</span><span class="sxs-lookup"><span data-stu-id="73f61-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="73f61-526">Dropbox Paper 文件、Dropbox Showcase 和 Dropbox Space</span><span class="sxs-lookup"><span data-stu-id="73f61-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="73f61-527">Dropbox 应用及收藏夹（已固定或加星标）</span><span class="sxs-lookup"><span data-stu-id="73f61-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="73f61-528">已迁移的 Dropbox 帐户不拥有的内容</span><span class="sxs-lookup"><span data-stu-id="73f61-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="73f61-529">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Dropbox 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="73f61-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="73f61-530">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="73f61-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="73f61-531">超出当前 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制的文件或文件夹</span></a> </span><span class="sxs-lookup"><span data-stu-id="73f61-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-onedrive-for-business-migrations"></a><span data-ttu-id="73f61-532">OneDrive for Business 迁移的 FastTrack 责任</span><span class="sxs-lookup"><span data-stu-id="73f61-532">FastTrack responsibilities for OneDrive for Business migrations</span></span>

<span data-ttu-id="73f61-533">我们的 FastTrack 专家在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="73f61-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="73f61-534">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="73f61-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="73f61-535">你的责任</span><span class="sxs-lookup"><span data-stu-id="73f61-535">Your responsibilities</span></span>

<span data-ttu-id="73f61-536">你在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="73f61-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="73f61-537">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="73f61-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="73f61-538">此外，你还将执行以下特定于 OneDrive for Business 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="73f61-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="73f61-539">预置将作为迁移事件目标的所有 OneDrive for Business 网站。</span><span class="sxs-lookup"><span data-stu-id="73f61-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="73f61-540">迁移到 Microsoft Teams 和 Microsoft 365 组</span><span class="sxs-lookup"><span data-stu-id="73f61-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="73f61-541">当你选择使用 FastTrack 将文件迁移到 Microsoft Teams 和 Microsoft 365 组时，我们提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="73f61-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="73f61-542">我们提供指导，帮助你规划迁移、配置源环境、Teams 和 Microsoft 365 组，以及利用我们的数据迁移服务迁移文件。</span><span class="sxs-lookup"><span data-stu-id="73f61-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="73f61-543">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="73f61-543">You create and schedule your migration events.</span></span> <span data-ttu-id="73f61-544">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="73f61-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="73f61-545">迁移事件完成后，你可以预期源环境的适当计划源和符合条件的源中的文件已迁移到 Teams 和 Microsoft 365 组。</span><span class="sxs-lookup"><span data-stu-id="73f61-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="73f61-546">客户必须先预配 Teams 频道和 Microsoft 365 组，然后才能将数据迁移到这些目标类型。</span><span class="sxs-lookup"><span data-stu-id="73f61-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="73f61-547">Teams 和 Microsoft 365 组会影响你对文件目标位置的权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="73f61-548">Teams 和 Microsoft 365 组是专为允许协作而构建的。</span><span class="sxs-lookup"><span data-stu-id="73f61-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="73f61-549">Teams 频道或 Microsoft 365 组确定迁移到这些目的地时谁有权访问这些文件。</span><span class="sxs-lookup"><span data-stu-id="73f61-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="73f61-550">在迁移期间，FastTrack 不会将最终用户或组添加到任何 Teams 频道或 Microsoft 365 组权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

## <a name="considerations"></a><span data-ttu-id="73f61-551">注意事项</span><span class="sxs-lookup"><span data-stu-id="73f61-551">Considerations</span></span>

- <span data-ttu-id="73f61-552">所有迁移均受 SharePoint Online 配额的限制。</span><span class="sxs-lookup"><span data-stu-id="73f61-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="73f61-553">有关详细信息， <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> 请参阅 SharePoint</a> 限制。</span><span class="sxs-lookup"><span data-stu-id="73f61-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="73f61-554">建议将迁移总量限制在你享有的整体 SharePoint Online 存储配额（包括你可能单独购买的其他存储）的 75% 以内。</span><span class="sxs-lookup"><span data-stu-id="73f61-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


## <a name="source-environment-details"></a><span data-ttu-id="73f61-555">源环境详细信息</span><span class="sxs-lookup"><span data-stu-id="73f61-555">Source environment details</span></span>

<span data-ttu-id="73f61-556">我们的数据迁移服务从以下源环境迁移数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="73f61-557">文件共享（支持 SMB 2.0 前向的设备上的服务器消息块 (SMB) 文件共享）。</span><span class="sxs-lookup"><span data-stu-id="73f61-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="73f61-558">单个 G 套件环境（仅限 Google Drive）。</span><span class="sxs-lookup"><span data-stu-id="73f61-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="73f61-559">Box（Starter、Business、Enterprise）。</span><span class="sxs-lookup"><span data-stu-id="73f61-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="73f61-560">用于 Teams的 Dropbox（标准版和高级版）</span><span class="sxs-lookup"><span data-stu-id="73f61-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="73f61-561">下表显示了特定于每个源环境的迁移详细信息：</span><span class="sxs-lookup"><span data-stu-id="73f61-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="73f61-562"><strong>源环境</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="73f61-563"><strong>迁移类型</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="73f61-564"><strong>迁移内容</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="73f61-565"><strong>不迁移的内容</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="73f61-566"><strong>任何支持 SMB 2.0 及更高版本的文件共享设备</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="73f61-567">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="73f61-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-568">文档</span><span class="sxs-lookup"><span data-stu-id="73f61-568">Documents</span></span> </li>
<li> <span data-ttu-id="73f61-569">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="73f61-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="73f61-570">用户级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="73f61-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="73f61-571">组级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="73f61-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="73f61-572">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="73f61-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="73f61-573">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="73f61-574">创建日期</span><span class="sxs-lookup"><span data-stu-id="73f61-574">Created date</span></span> </li>
<li> <span data-ttu-id="73f61-575">修改日期</span><span class="sxs-lookup"><span data-stu-id="73f61-575">Modified date</span></span> </li>
<li> <span data-ttu-id="73f61-576">创建者</span><span class="sxs-lookup"><span data-stu-id="73f61-576">Created by</span></span> </li>
<li> <span data-ttu-id="73f61-577">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="73f61-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="73f61-578">\*必须配置目录同步。</span><span class="sxs-lookup"><span data-stu-id="73f61-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="73f61-579">只迁移对 Windows 文件资源管理器公开的 NTFS 权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="73f61-580">不会迁移文件共享设备上直接托管的权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="73f61-581">如果数据存储在 SMB 2.0 设备上，只会迁移 SMB 协议公开的与 NTFS 等同的权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="73f61-582">权限受 Microsoft 365 组和/或 Microsoft Teams 频道的影响。</span><span class="sxs-lookup"><span data-stu-id="73f61-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="73f61-583">如果目标为 Microsoft 365 组或 Microsoft Teams 频道，则组或频道将确定迁移文件的最终权限配置文件。</span><span class="sxs-lookup"><span data-stu-id="73f61-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="73f61-584">建议不要迁移迁移到 Microsoft 365 组或 Microsoft Teams 频道的文件权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-585">所有权历史记录和旧版本</span><span class="sxs-lookup"><span data-stu-id="73f61-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="73f61-586">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="73f61-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="73f61-587">旧版本</span><span class="sxs-lookup"><span data-stu-id="73f61-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="73f61-588">Windows 文件和文件夹属性（如只读和隐藏）</span><span class="sxs-lookup"><span data-stu-id="73f61-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="73f61-589">非 Windows 新技术文件系统 (NTFS) 和 NTFS 高级权限和特殊设置：</span><span class="sxs-lookup"><span data-stu-id="73f61-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="73f61-590">显式拒绝权限（在迁移后删除的权限、从属于并行权限的内容或父文件夹上的权限）</span><span class="sxs-lookup"><span data-stu-id="73f61-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="73f61-591">NTFS 审核配置</span><span class="sxs-lookup"><span data-stu-id="73f61-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="73f61-592">文件分类基础结构 (FCI) 提供的附加文件元数据</span><span class="sxs-lookup"><span data-stu-id="73f61-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="73f61-593">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="73f61-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="73f61-594">隐藏的共享</span><span class="sxs-lookup"><span data-stu-id="73f61-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="73f61-595">共享（如在共享级别授予的权限）</span><span class="sxs-lookup"><span data-stu-id="73f61-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="73f61-596">超出当前 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制的文件或文件夹</span></a> </span><span class="sxs-lookup"><span data-stu-id="73f61-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="73f61-597"><strong>单个 G 套件环境（仅限 Google 云端硬盘）</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="73f61-598">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="73f61-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-599">Google 文档、工作表和幻灯片（文件包括超过10 MB的，转换为等同的 Office 格式）</span><span class="sxs-lookup"><span data-stu-id="73f61-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="73f61-600">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="73f61-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="73f61-601">用户级别文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="73f61-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="73f61-602">组级别文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="73f61-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="73f61-603">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="73f61-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="73f61-604">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="73f61-605">创建日期</span><span class="sxs-lookup"><span data-stu-id="73f61-605">Created date</span></span> </li>
<li> <span data-ttu-id="73f61-606">修改日期</span><span class="sxs-lookup"><span data-stu-id="73f61-606">Modified date</span></span> </li>
<li> <span data-ttu-id="73f61-607">创建者</span><span class="sxs-lookup"><span data-stu-id="73f61-607">Created by</span></span> </li>
<li> <span data-ttu-id="73f61-608">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="73f61-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="73f61-609">共享驱动器 （文件夹和文件）</span><span class="sxs-lookup"><span data-stu-id="73f61-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="73f61-610">属于 Google 云端硬盘帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="73f61-611">\*权限受 Microsoft 365 组和/或 Microsoft Teams 频道影响。</span><span class="sxs-lookup"><span data-stu-id="73f61-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="73f61-612">如果目标为 Microsoft 365 组或 Microsoft Teams 频道，则组或频道将确定迁移文件的最终权限配置文件。</span><span class="sxs-lookup"><span data-stu-id="73f61-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="73f61-613">建议不要迁移迁移到 Microsoft 365 组或 Microsoft Teams 频道的文件权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="73f61-614">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="73f61-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="73f61-615">文件和文件夹说明、文件夹颜色</span><span class="sxs-lookup"><span data-stu-id="73f61-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="73f61-616">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-617">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-618">高级元数据</span><span class="sxs-lookup"><span data-stu-id="73f61-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="73f61-619">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="73f61-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="73f61-620">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="73f61-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="73f61-621">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="73f61-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="73f61-622">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="73f61-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="73f61-623">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="73f61-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="73f61-624">Google 相册、Forms、地图和其他已连接应用</span><span class="sxs-lookup"><span data-stu-id="73f61-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="73f61-625">Google 绘图</span><span class="sxs-lookup"><span data-stu-id="73f61-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="73f61-626">组织外部的共享内容</span><span class="sxs-lookup"><span data-stu-id="73f61-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="73f61-627">不属于Google 云端硬盘帐户的内容被迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="73f61-628">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Google 云端硬盘管理报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="73f61-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="73f61-629">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="73f61-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="73f61-630">共享驱动器成员资格权限（<strong>注意</strong>：使用 Google 云端硬盘管理报告来标识共享驱动器成员资格。</span><span class="sxs-lookup"><span data-stu-id="73f61-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="73f61-631">指示最终用户迁移前在目标上配置这些成员资格设置。）</span><span class="sxs-lookup"><span data-stu-id="73f61-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="73f61-632">超出当前 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制的文件或文件夹</span></a> </span><span class="sxs-lookup"><span data-stu-id="73f61-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="73f61-633"><strong>Box（Starter、Business、Enterprise）</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="73f61-634">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="73f61-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-635">文档</span><span class="sxs-lookup"><span data-stu-id="73f61-635">Documents</span></span> </li>
<li> <span data-ttu-id="73f61-636">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="73f61-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="73f61-637">用户级别文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="73f61-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="73f61-638">组级别文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="73f61-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="73f61-639">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="73f61-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="73f61-640">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="73f61-641">创建日期</span><span class="sxs-lookup"><span data-stu-id="73f61-641">Created date</span></span> </li>
<li> <span data-ttu-id="73f61-642">修改日期</span><span class="sxs-lookup"><span data-stu-id="73f61-642">Modified date</span></span> </li>
<li> <span data-ttu-id="73f61-643">创建者</span><span class="sxs-lookup"><span data-stu-id="73f61-643">Created by</span></span> </li>
<li> <span data-ttu-id="73f61-644">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="73f61-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="73f61-645">属于 Box 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="73f61-646">转换为 Word 文档 (格式的方框) </span><span class="sxs-lookup"><span data-stu-id="73f61-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="73f61-647">\*权限受 Microsoft 365 组和/或 Microsoft Teams 频道影响。</span><span class="sxs-lookup"><span data-stu-id="73f61-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="73f61-648">如果目标为 Microsoft 365 组或 Microsoft Teams 频道，则组或频道将确定迁移文件的最终权限配置文件。</span><span class="sxs-lookup"><span data-stu-id="73f61-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="73f61-649">建议不要迁移迁移到 Microsoft 365 组或 Microsoft Teams 频道的文件权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="73f61-650">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="73f61-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="73f61-651">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="73f61-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="73f61-652">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-653">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-654">Box 标记和高级元数据</span><span class="sxs-lookup"><span data-stu-id="73f61-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="73f61-655">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="73f61-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="73f61-656">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="73f61-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="73f61-657">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="73f61-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="73f61-658">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="73f61-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="73f61-659">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="73f61-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="73f61-660">Box 应用、书签、收藏夹和工作流</span><span class="sxs-lookup"><span data-stu-id="73f61-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="73f61-661">不属于已迁移 Box 帐户的内容</span><span class="sxs-lookup"><span data-stu-id="73f61-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="73f61-662">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Box 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="73f61-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="73f61-663">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="73f61-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="73f61-664">超出当前 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制的文件或文件夹</span></a> </span><span class="sxs-lookup"><span data-stu-id="73f61-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="73f61-665"><strong>用于 Teams的 Dropbox（标准版和高级版）</strong></span><span class="sxs-lookup"><span data-stu-id="73f61-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="73f61-666">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="73f61-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="73f61-667">文档</span><span class="sxs-lookup"><span data-stu-id="73f61-667">Documents</span></span> </li>
<li> <span data-ttu-id="73f61-668">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="73f61-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="73f61-669">用户级别文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="73f61-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="73f61-670">组级别文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="73f61-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="73f61-671">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="73f61-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="73f61-672">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="73f61-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="73f61-673">创建日期</span><span class="sxs-lookup"><span data-stu-id="73f61-673">Created date</span></span> </li>
<li> <span data-ttu-id="73f61-674">修改日期</span><span class="sxs-lookup"><span data-stu-id="73f61-674">Modified date</span></span> </li>
<li> <span data-ttu-id="73f61-675">创建者</span><span class="sxs-lookup"><span data-stu-id="73f61-675">Created by</span></span> </li>
<li> <span data-ttu-id="73f61-676">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="73f61-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="73f61-677">共享团队文件夹和内容</span><span class="sxs-lookup"><span data-stu-id="73f61-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="73f61-678">属于 Dropbox 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="73f61-679">\*权限受 Microsoft 365 组和/或 Microsoft Teams 频道影响。</span><span class="sxs-lookup"><span data-stu-id="73f61-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="73f61-680">如果目标为 Microsoft 365 组或 Microsoft Teams 频道，则组或频道将确定迁移文件的最终权限配置文件。</span><span class="sxs-lookup"><span data-stu-id="73f61-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="73f61-681">建议不要迁移迁移到 Microsoft 365 组或 Microsoft Teams 频道的文件权限。</span><span class="sxs-lookup"><span data-stu-id="73f61-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="73f61-682">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="73f61-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="73f61-683">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="73f61-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="73f61-684">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-685">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="73f61-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="73f61-686">高级元数据</span><span class="sxs-lookup"><span data-stu-id="73f61-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="73f61-687">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="73f61-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="73f61-688">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="73f61-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="73f61-689">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="73f61-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="73f61-690">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="73f61-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="73f61-691">已卸载的 Dropbox 文件夹</span><span class="sxs-lookup"><span data-stu-id="73f61-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="73f61-692">已删除或已断开连接的用户</span><span class="sxs-lookup"><span data-stu-id="73f61-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="73f61-693">Dropbox Paper 文件、Dropbox Showcase 和 Dropbox Space</span><span class="sxs-lookup"><span data-stu-id="73f61-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="73f61-694">Dropbox 应用及收藏夹（已固定或加星标）</span><span class="sxs-lookup"><span data-stu-id="73f61-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="73f61-695">已迁移的 Dropbox 帐户不拥有的内容</span><span class="sxs-lookup"><span data-stu-id="73f61-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="73f61-696">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Dropbox 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="73f61-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="73f61-697">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="73f61-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="73f61-698">超出当前 <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制的文件或文件夹</span></a> </span><span class="sxs-lookup"><span data-stu-id="73f61-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities-for-microsoft-teams-and-microsoft-365-groups-migrations"></a><span data-ttu-id="73f61-699">FastTrack 负责 Microsoft Teams 和 Microsoft 365 组迁移</span><span class="sxs-lookup"><span data-stu-id="73f61-699">FastTrack responsibilities for Microsoft Teams and Microsoft 365 Groups migrations</span></span>

<span data-ttu-id="73f61-700">我们的 FastTrack 专家在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="73f61-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="73f61-701">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="73f61-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="73f61-702">你的责任</span><span class="sxs-lookup"><span data-stu-id="73f61-702">Your responsibilities</span></span> 

<span data-ttu-id="73f61-703">你在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="73f61-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="73f61-704">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="73f61-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="73f61-705">还可以执行以下特定于 Microsoft Teams 和 Microsoft 365 组迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="73f61-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="73f61-706">根据迁移事件设置所有 Microsoft Teams 频道和 Microsoft 365 组。</span><span class="sxs-lookup"><span data-stu-id="73f61-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="73f61-707">FastTrack 不会预配 Microsoft Teams 频道或 Microsoft 365 组。</span><span class="sxs-lookup"><span data-stu-id="73f61-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="73f61-708">FastTrack 不会将最终用户或组添加到 Microsoft Teams 频道或 Microsoft 365 组。</span><span class="sxs-lookup"><span data-stu-id="73f61-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="73f61-709">在将数据迁移到目标之前，必须将最终用户或组添加到所有 Microsoft Teams 频道和 Microsoft 365 组，以便这些最终用户能够访问新迁移的文档</span><span class="sxs-lookup"><span data-stu-id="73f61-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>