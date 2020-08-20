---
title: 数据迁移
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack 可以帮助你将源环境中的邮件和文件数据迁移到 Office 365（Exchange Online、SharePoint Online 和 OneDrive for Business）。 我们提供的帮助类型取决于你的 Office 365 许可证数量。
ms.openlocfilehash: 6b2c9cc3afba415c200b14fe34e65f1c3286e450
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817709"
---
# <a name="data-migration"></a><span data-ttu-id="07af8-104">数据迁移</span><span class="sxs-lookup"><span data-stu-id="07af8-104">Data Migration</span></span>

<span data-ttu-id="07af8-105">FastTrack 可以帮助你将源环境中的邮件和文件数据迁移到 Office 365（Exchange Online、SharePoint Online 和 OneDrive for Business）。</span><span class="sxs-lookup"><span data-stu-id="07af8-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="07af8-106">我们提供的帮助类型取决于你的 Office 365 许可证数量：</span><span class="sxs-lookup"><span data-stu-id="07af8-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="07af8-107">**对于具有 150-499 个许可证的 Office 365 租户**：FastTrack 仅提供迁移指南；你负责执行数据迁移。</span><span class="sxs-lookup"><span data-stu-id="07af8-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="07af8-108">我们将指导你阅读文档，以帮助你计划和使用免费工具来执行自助服务迁移。</span><span class="sxs-lookup"><span data-stu-id="07af8-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="07af8-109">**对于具有 500 个或更多许可证的 Office 365 租户**：FastTrack 提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="07af8-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="07af8-110">我们提供指导，以帮助你计划迁移、配置源环境和 Office 365 租户，并利用我们的数据迁移服务来迁移数据。</span><span class="sxs-lookup"><span data-stu-id="07af8-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="07af8-111">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="07af8-111">You create and schedule your migration events.</span></span> <span data-ttu-id="07af8-112">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="07af8-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="07af8-113">如果你在 2017 年 9 月 1 日之前购买或续订了商业计划，则只需 150 个许可证即可获得数据迁移服务的资格。</span><span class="sxs-lookup"><span data-stu-id="07af8-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="07af8-114">对于教育计划，只有付费教职员工许可证才有资格获得数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="07af8-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="07af8-115">注意事项</span><span class="sxs-lookup"><span data-stu-id="07af8-115">Considerations</span></span>

  - <span data-ttu-id="07af8-116">你的源环境必须满足特定的期望才能将数据迁移到 Office 365。</span><span class="sxs-lookup"><span data-stu-id="07af8-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="07af8-117">有关 Exchange、SharePoint 和 OneDrive for Business 的源环境期望的更多信息，请参阅[产品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="07af8-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="07af8-118">我们需要对你的源环境和 Office 365 租户具有适当的访问权限和权限才能提供数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="07af8-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="07af8-119">我们的数据迁移服务并非为满足特殊法律或法规要求的数据而设计或以此为目的。</span><span class="sxs-lookup"><span data-stu-id="07af8-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="07af8-120">我们迁移数据时，可将其传输到我们维护设施的任何位置、从中进行存储和处理（除非为你的 FastTrack 迁移项目提供了其他位置）。</span><span class="sxs-lookup"><span data-stu-id="07af8-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="07af8-121">我们无法保证邮件或文件的迁移速度。</span><span class="sxs-lookup"><span data-stu-id="07af8-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="07af8-122">不可预见的问题（例如源环境中不可读或损坏的项）可能会阻止我们迁移某些数据项。</span><span class="sxs-lookup"><span data-stu-id="07af8-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="07af8-123">我们无法控制的外部因素（例如对第三方应用程序编程接口 (API) 的更改）可能会导致我们的数据迁移服务发生更改、延迟或暂停。</span><span class="sxs-lookup"><span data-stu-id="07af8-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="07af8-124">迁移服务可用性</span><span class="sxs-lookup"><span data-stu-id="07af8-124">Migration service availability</span></span>

  - <span data-ttu-id="07af8-125">**对于商业和英国政府客户：** 我们每周七 (7) 天，每天 24 小时 (24x7) 提供数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="07af8-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="07af8-126">**对于美国政府/DOD 客户：** 我们每周五 (5) 天，每天 24 小时 (24x5) 提供数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="07af8-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="07af8-127">到 Exchange Online 的迁移</span><span class="sxs-lookup"><span data-stu-id="07af8-127">Migration to Exchange Online</span></span>

<span data-ttu-id="07af8-128">当你选择使用 FastTrack 将电子邮件迁移到 Exchange Online 时，我们将提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="07af8-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="07af8-129">我们提供指导，以帮助你计划迁移、配置源环境和 Exchange Online，并利用我们的数据迁移服务来迁移邮箱。</span><span class="sxs-lookup"><span data-stu-id="07af8-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="07af8-130">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="07af8-130">You create and schedule your migration events.</span></span> <span data-ttu-id="07af8-131">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="07af8-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="07af8-132">迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源邮箱中的的邮件已迁移到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="07af8-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="07af8-133">注意事项</span><span class="sxs-lookup"><span data-stu-id="07af8-133">Considerations</span></span>

  - <span data-ttu-id="07af8-134">迁移前，必须完成 Exchange Online 的FastTrack 核心载入；</span><span class="sxs-lookup"><span data-stu-id="07af8-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="07af8-135">如果你自行执行载入，则必须通过必需的检查和先决条件。</span><span class="sxs-lookup"><span data-stu-id="07af8-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="07af8-136">有关详细信息，请参阅[产品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="07af8-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="07af8-137">FastTrack 仅迁移到活动的 Office 365 邮箱。</span><span class="sxs-lookup"><span data-stu-id="07af8-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="07af8-138">如果要从本地 Exchange 环境迁移，则必须满足特定要求。</span><span class="sxs-lookup"><span data-stu-id="07af8-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="07af8-139">有关详细信息，请参阅[配置混合部署先决条件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="07af8-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="07af8-140">每个源环境都必须处于源环境中相应产品的最新服务包 (SP) 和汇总更新 (RU)/累积更新 (CU) 级别。</span><span class="sxs-lookup"><span data-stu-id="07af8-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="07af8-141">位于本地 Active Directory 中的通讯组列表（*MailEnabledGroup* 对象）和外部联系人（*MailEnabledContact* 对象）不是邮箱数据迁移的一部分。</span><span class="sxs-lookup"><span data-stu-id="07af8-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="07af8-142">但是，你可以使用 Azure Active Directory (Azure AD) Connect 将它们同步。</span><span class="sxs-lookup"><span data-stu-id="07af8-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="07af8-143">源环境</span><span class="sxs-lookup"><span data-stu-id="07af8-143">Source environments</span></span>

<span data-ttu-id="07af8-144">我们的数据迁移服务从以下源环境迁移数据：</span><span class="sxs-lookup"><span data-stu-id="07af8-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="07af8-145">具有单个或多个 Exchange 组织的单个或多个 Active Directory 林（每个 Exchange 邮件系统均须为 Exchange 2010 或更高版本）。</span><span class="sxs-lookup"><span data-stu-id="07af8-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="07af8-146">一个支持 IMAP 的电子邮件环境。</span><span class="sxs-lookup"><span data-stu-id="07af8-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="07af8-147">G 套件环境（仅限 Gmail、联系人和日历）</span><span class="sxs-lookup"><span data-stu-id="07af8-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="07af8-148">下表显示了特定于每个源环境的迁移详细信息：</span><span class="sxs-lookup"><span data-stu-id="07af8-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="07af8-149"><strong>源环境</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="07af8-150"><strong>迁移类型</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="07af8-151"><strong>迁移内容</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="07af8-152"><strong>不迁移的内容</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="07af8-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="07af8-154">
<strong>注意：</strong> 有关本地 Exchange 依赖项的信息，请参阅 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">混合部署先决条件</span></a>。</span><span class="sxs-lookup"><span data-stu-id="07af8-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="07af8-155">使用混合部署进行的迁移</span><span class="sxs-lookup"><span data-stu-id="07af8-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="07af8-156">电子邮件</span><span class="sxs-lookup"><span data-stu-id="07af8-156">Emails</span></span></li>
<li><span data-ttu-id="07af8-157">邮箱规则</span><span class="sxs-lookup"><span data-stu-id="07af8-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="07af8-158">代理</span><span class="sxs-lookup"><span data-stu-id="07af8-158">Delegates</span></span></li>
<li><span data-ttu-id="07af8-159">邮箱联系人</span><span class="sxs-lookup"><span data-stu-id="07af8-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="07af8-160">日历</span><span class="sxs-lookup"><span data-stu-id="07af8-160">Calendar</span></span> </li>
<li> <span data-ttu-id="07af8-161">任务</span><span class="sxs-lookup"><span data-stu-id="07af8-161">Tasks</span></span> </li>
<li> <span data-ttu-id="07af8-162">权限管理的电子邮件</span><span class="sxs-lookup"><span data-stu-id="07af8-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="07af8-163">加密电子邮件</span><span class="sxs-lookup"><span data-stu-id="07af8-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="07af8-164">签名</span><span class="sxs-lookup"><span data-stu-id="07af8-164">Signatures</span></span> </li>
<li> <span data-ttu-id="07af8-165">与用户的邮箱一起迁移的个人存档</span><span class="sxs-lookup"><span data-stu-id="07af8-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="07af8-166">可恢复的项目</span><span class="sxs-lookup"><span data-stu-id="07af8-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="07af8-167">公用文件夹</span><span class="sxs-lookup"><span data-stu-id="07af8-167">Public folders</span></span> </li>
<li> <span data-ttu-id="07af8-168">超出邮件大小限制的所有电子邮件</span><span class="sxs-lookup"><span data-stu-id="07af8-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="07af8-169">日记存档或任何第三方存档解决方案</span><span class="sxs-lookup"><span data-stu-id="07af8-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="07af8-170">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="07af8-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="07af8-171">来自个人存储表 (PST) 文件的存档数据</span><span class="sxs-lookup"><span data-stu-id="07af8-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="07af8-172">已损坏的项目</span><span class="sxs-lookup"><span data-stu-id="07af8-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="07af8-173">非活动邮箱</span><span class="sxs-lookup"><span data-stu-id="07af8-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="07af8-174"><strong>G 套件环境（仅限 Gmail、联系人和日历）</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="07af8-175">
<strong>注意：</strong> 你的 G 套件环境必须满足<a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">执行 G 套件迁移</a>中所述的先决条件。</span><span class="sxs-lookup"><span data-stu-id="07af8-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="07af8-176">直接转换或暂存</span><span class="sxs-lookup"><span data-stu-id="07af8-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="07af8-177">电子邮件</span><span class="sxs-lookup"><span data-stu-id="07af8-177">Emails</span></span> </li>
<li> <span data-ttu-id="07af8-178">邮箱联系人（每个联系人最多迁移 3 个电子邮件地址）</span><span class="sxs-lookup"><span data-stu-id="07af8-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="07af8-179">日历</span><span class="sxs-lookup"><span data-stu-id="07af8-179">Calendar</span></span> </li>
<li> <span data-ttu-id="07af8-180">标签</span><span class="sxs-lookup"><span data-stu-id="07af8-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="07af8-181">规则</span><span class="sxs-lookup"><span data-stu-id="07af8-181">Rules</span></span> </li>
<li> <span data-ttu-id="07af8-182">代理</span><span class="sxs-lookup"><span data-stu-id="07af8-182">Delegates</span></span> </li>
<li> <span data-ttu-id="07af8-183">签名</span><span class="sxs-lookup"><span data-stu-id="07af8-183">Signatures</span></span> </li>
<li> <span data-ttu-id="07af8-184">任务</span><span class="sxs-lookup"><span data-stu-id="07af8-184">Tasks</span></span> </li>
<li> <span data-ttu-id="07af8-185">超出邮件大小限制的所有电子邮件或附件</span><span class="sxs-lookup"><span data-stu-id="07af8-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="07af8-186">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="07af8-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="07af8-187">来自 PST 文件或任何第三方存档解决方案（例如 Google Vault）的存档数据</span><span class="sxs-lookup"><span data-stu-id="07af8-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="07af8-188">权限管理或加密电子邮件</span><span class="sxs-lookup"><span data-stu-id="07af8-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="07af8-189">已损坏的项目</span><span class="sxs-lookup"><span data-stu-id="07af8-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="07af8-190">Google Hangout\*\*</span><span class="sxs-lookup"><span data-stu-id="07af8-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="07af8-191">Google 组</span><span class="sxs-lookup"><span data-stu-id="07af8-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="07af8-192">资源邮箱</span><span class="sxs-lookup"><span data-stu-id="07af8-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="07af8-193">非活动邮箱</span><span class="sxs-lookup"><span data-stu-id="07af8-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="07af8-194">假期设置和自动答复设置</span><span class="sxs-lookup"><span data-stu-id="07af8-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="07af8-195">共享日历、云附件、Google Hangout 链接和事件颜色</span><span class="sxs-lookup"><span data-stu-id="07af8-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="07af8-196">\*\*迁移另存为标签的环聊对话。</span><span class="sxs-lookup"><span data-stu-id="07af8-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="07af8-197"><strong>IMAP4 源（如 Domino、GroupWise 或 Zimbra）</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="07af8-198">使用本机 IMAP4 工具进行迁移</span><span class="sxs-lookup"><span data-stu-id="07af8-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="07af8-199">电子邮件</span><span class="sxs-lookup"><span data-stu-id="07af8-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="07af8-200">规则</span><span class="sxs-lookup"><span data-stu-id="07af8-200">Rules</span></span> </li>
<li> <span data-ttu-id="07af8-201">代理</span><span class="sxs-lookup"><span data-stu-id="07af8-201">Delegates</span></span> </li>
<li> <span data-ttu-id="07af8-202">通讯组列表</span><span class="sxs-lookup"><span data-stu-id="07af8-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="07af8-203">外部联系人</span><span class="sxs-lookup"><span data-stu-id="07af8-203">External contacts</span></span> </li>
<li> <span data-ttu-id="07af8-204">启用邮件的用户</span><span class="sxs-lookup"><span data-stu-id="07af8-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="07af8-205">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="07af8-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="07af8-206">邮箱联系人</span><span class="sxs-lookup"><span data-stu-id="07af8-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="07af8-207">日历</span><span class="sxs-lookup"><span data-stu-id="07af8-207">Calendar</span></span> </li>
<li> <span data-ttu-id="07af8-208">签名</span><span class="sxs-lookup"><span data-stu-id="07af8-208">Signatures</span></span> </li>
<li> <span data-ttu-id="07af8-209">任务</span><span class="sxs-lookup"><span data-stu-id="07af8-209">Tasks</span></span> </li>
<li> <span data-ttu-id="07af8-210">超出邮件大小限制的所有电子邮件</span><span class="sxs-lookup"><span data-stu-id="07af8-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="07af8-211">存档数据</span><span class="sxs-lookup"><span data-stu-id="07af8-211">Archive data</span></span> </li>
<li> <span data-ttu-id="07af8-212">加密电子邮件</span><span class="sxs-lookup"><span data-stu-id="07af8-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="07af8-213">已损坏的项目</span><span class="sxs-lookup"><span data-stu-id="07af8-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="07af8-214">非活动邮箱</span><span class="sxs-lookup"><span data-stu-id="07af8-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="07af8-215">FastTrack 责任</span><span class="sxs-lookup"><span data-stu-id="07af8-215">FastTrack responsibilities</span></span>

<span data-ttu-id="07af8-216">我们的 FastTrack 专家在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="07af8-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="07af8-217">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="07af8-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="07af8-218">我们的 FastTrack 专家还执行以下特定于 Exchange 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="07af8-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="07af8-219">提供指导以帮助你在源环境和 Exchange Online 之间启用 SMTP 邮件路由共存（如果适用）。</span><span class="sxs-lookup"><span data-stu-id="07af8-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="07af8-220">你的责任</span><span class="sxs-lookup"><span data-stu-id="07af8-220">Your responsibilities</span></span>

<span data-ttu-id="07af8-221">你在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="07af8-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="07af8-222">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="07af8-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="07af8-223">此外，你还将执行以下特定于 Exchange 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="07af8-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="07af8-224">完成 Exchange Online 的FastTrack 核心载入。</span><span class="sxs-lookup"><span data-stu-id="07af8-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="07af8-225">如果你自行执行载入，则必须通过必需的检查和先决条件。</span><span class="sxs-lookup"><span data-stu-id="07af8-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="07af8-226">有关详细信息，请参阅[产品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="07af8-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="07af8-227">根据 Office 365 准则安装客户端软件的相应级别。</span><span class="sxs-lookup"><span data-stu-id="07af8-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="07af8-228">有关详细信息，请参阅[新式工作区](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)。</span><span class="sxs-lookup"><span data-stu-id="07af8-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="07af8-229">如果要从本地 Exchange 环境迁移，需满足特定要求。</span><span class="sxs-lookup"><span data-stu-id="07af8-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="07af8-230">有关详细信息，请参阅[配置混合部署先决条件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="07af8-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="07af8-231">确保每个源环境都位于最新服务包 (SP) 和汇总 (RU)/累积更新 (CU) 级别（如果适用）。</span><span class="sxs-lookup"><span data-stu-id="07af8-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="07af8-232">配置和验证源环境和 Exchange Online 之间的 SMTP 邮件路由共存（如果适用）。</span><span class="sxs-lookup"><span data-stu-id="07af8-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="07af8-233">确保源邮箱大小不超过目标邮箱配额。</span><span class="sxs-lookup"><span data-stu-id="07af8-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="07af8-234">根据源平台的不同，可能需要将源数据限制为目标邮箱配额的 85%。</span><span class="sxs-lookup"><span data-stu-id="07af8-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="07af8-235">根据需要迁移客户端数据。</span><span class="sxs-lookup"><span data-stu-id="07af8-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="07af8-236">这包括但不限于本地通讯簿、本地 PST 文件中的数据、Outlook 规则和本地 Outlook 设置。</span><span class="sxs-lookup"><span data-stu-id="07af8-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="07af8-237">帮助最终用户修正客户端迁移问题。</span><span class="sxs-lookup"><span data-stu-id="07af8-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="07af8-238">到 SharePoint Online 的迁移</span><span class="sxs-lookup"><span data-stu-id="07af8-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="07af8-239">当你选择使用 FastTrack 将文件迁移到 SharePoint Online 时，我们将提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="07af8-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="07af8-240">我们提供指导，以帮助你计划迁移、配置源环境和 SharePoint Online，并利用我们的数据迁移服务来迁移文件。</span><span class="sxs-lookup"><span data-stu-id="07af8-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="07af8-241">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="07af8-241">You create and schedule your migration events.</span></span> <span data-ttu-id="07af8-242">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="07af8-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="07af8-243">迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源中的的文件已迁移到 SharePoint Online。</span><span class="sxs-lookup"><span data-stu-id="07af8-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="07af8-244">注意事项</span><span class="sxs-lookup"><span data-stu-id="07af8-244">Considerations</span></span>

  - <span data-ttu-id="07af8-245">所有迁移均受 SharePoint Online 配额的限制。</span><span class="sxs-lookup"><span data-stu-id="07af8-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="07af8-246">有关详细信息，请参阅 [<span class="underline">SharePoint Online 和 OneDrive for Business 的软件边界与限制</span>](https://go.microsoft.com/fwlink/?LinkId=698855)。</span><span class="sxs-lookup"><span data-stu-id="07af8-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="07af8-247">建议将迁移总量限制在你享有的整体 SharePoint Online 存储配额（包括你可能单独购买的其他存储）的 75% 以内。</span><span class="sxs-lookup"><span data-stu-id="07af8-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="07af8-248">源环境详细信息</span><span class="sxs-lookup"><span data-stu-id="07af8-248">Source environment details</span></span>

<span data-ttu-id="07af8-249">我们的数据迁移服务从以下源环境迁移数据：</span><span class="sxs-lookup"><span data-stu-id="07af8-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="07af8-250">文件共享（支持 SMB 2.0 前向的设备上的服务器消息块 (SMB) 文件共享）。</span><span class="sxs-lookup"><span data-stu-id="07af8-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="07af8-251">单个 G 套件环境（仅限 Google Drive）。</span><span class="sxs-lookup"><span data-stu-id="07af8-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="07af8-252">Box（Starter、Business、Enterprise）。</span><span class="sxs-lookup"><span data-stu-id="07af8-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="07af8-253">用于 Teams的 Dropbox（标准版和高级版）</span><span class="sxs-lookup"><span data-stu-id="07af8-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="07af8-254">下表显示了特定于每个源环境的迁移详细信息：</span><span class="sxs-lookup"><span data-stu-id="07af8-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="07af8-255"><strong>源环境</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="07af8-256"><strong>迁移类型</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="07af8-257"><strong>迁移内容</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="07af8-258"><strong>不迁移的内容</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="07af8-259"><strong>任何支持 SMB 2.0 及更高版本的文件共享设备</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="07af8-260">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="07af8-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="07af8-261">文档</span><span class="sxs-lookup"><span data-stu-id="07af8-261">Documents</span></span> </li>
<li> <span data-ttu-id="07af8-262">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="07af8-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="07af8-263">用户级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="07af8-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="07af8-264">组级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="07af8-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="07af8-265">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="07af8-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="07af8-266">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="07af8-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="07af8-267">创建日期</span><span class="sxs-lookup"><span data-stu-id="07af8-267">Created date</span></span> </li>
<li> <span data-ttu-id="07af8-268">修改日期</span><span class="sxs-lookup"><span data-stu-id="07af8-268">Modified date</span></span> </li>
<li> <span data-ttu-id="07af8-269">创建者</span><span class="sxs-lookup"><span data-stu-id="07af8-269">Created by</span></span> </li>
<li> <span data-ttu-id="07af8-270">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="07af8-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="07af8-271">\*必须配置目录同步。</span><span class="sxs-lookup"><span data-stu-id="07af8-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="07af8-272">只迁移对 Windows 文件资源管理器公开的 NTFS 权限。</span><span class="sxs-lookup"><span data-stu-id="07af8-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="07af8-273">不会迁移文件共享设备上直接托管的权限。</span><span class="sxs-lookup"><span data-stu-id="07af8-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="07af8-274">如果数据存储在 SMB 2.0 设备上，只会迁移 SMB 协议公开的与 NTFS 等同的权限。</span><span class="sxs-lookup"><span data-stu-id="07af8-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="07af8-275">所有权历史记录和旧版本</span><span class="sxs-lookup"><span data-stu-id="07af8-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="07af8-276">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="07af8-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="07af8-277">旧版本</span><span class="sxs-lookup"><span data-stu-id="07af8-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="07af8-278">Windows 文件和文件夹属性（如只读和隐藏）</span><span class="sxs-lookup"><span data-stu-id="07af8-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="07af8-279">非 Windows 新技术文件系统 (NTFS) 和 NTFS 高级权限和特殊设置：</span><span class="sxs-lookup"><span data-stu-id="07af8-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="07af8-280">显式拒绝权限（在迁移后删除的权限、从属于并行权限的内容或父文件夹上的权限）</span><span class="sxs-lookup"><span data-stu-id="07af8-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="07af8-281">NTFS 审核配置</span><span class="sxs-lookup"><span data-stu-id="07af8-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="07af8-282">文件分类基础结构 (FCI) 提供的附加文件元数据</span><span class="sxs-lookup"><span data-stu-id="07af8-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="07af8-283">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="07af8-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="07af8-284">隐藏的共享</span><span class="sxs-lookup"><span data-stu-id="07af8-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="07af8-285">共享（如在共享级别授予的权限）</span><span class="sxs-lookup"><span data-stu-id="07af8-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="07af8-286">超出当前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制和局限</span></a> 的文件或文件夹</span><span class="sxs-lookup"><span data-stu-id="07af8-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="07af8-287"><strong>单个 G 套件环境（仅限 Google 云端硬盘）</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="07af8-288">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="07af8-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="07af8-289">Google 文档、工作表和幻灯片（文件转换为等同的 Office 格式），包括超过10 MB的</span><span class="sxs-lookup"><span data-stu-id="07af8-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="07af8-290">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="07af8-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="07af8-291">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="07af8-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="07af8-292">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="07af8-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="07af8-293">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="07af8-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="07af8-294">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="07af8-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="07af8-295">创建日期</span><span class="sxs-lookup"><span data-stu-id="07af8-295">Created date</span></span> </li>
<li> <span data-ttu-id="07af8-296">修改日期</span><span class="sxs-lookup"><span data-stu-id="07af8-296">Modified date</span></span> </li>
<li> <span data-ttu-id="07af8-297">创建者</span><span class="sxs-lookup"><span data-stu-id="07af8-297">Created by</span></span> </li>
<li> <span data-ttu-id="07af8-298">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="07af8-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="07af8-299">共享驱动器 （文件夹和文件）</span><span class="sxs-lookup"><span data-stu-id="07af8-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="07af8-300">属于 Google 云端硬盘帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="07af8-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="07af8-301">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="07af8-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="07af8-302">文件和文件夹说明、文件夹颜色</span><span class="sxs-lookup"><span data-stu-id="07af8-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="07af8-303">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="07af8-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="07af8-304">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="07af8-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="07af8-305">高级元数据</span><span class="sxs-lookup"><span data-stu-id="07af8-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="07af8-306">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="07af8-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="07af8-307">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="07af8-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="07af8-308">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="07af8-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="07af8-309">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="07af8-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="07af8-310">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="07af8-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="07af8-311">Google 相册、Forms、地图和其他已连接应用</span><span class="sxs-lookup"><span data-stu-id="07af8-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="07af8-312">Google 绘图</span><span class="sxs-lookup"><span data-stu-id="07af8-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="07af8-313">组织外部的共享内容</span><span class="sxs-lookup"><span data-stu-id="07af8-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="07af8-314">不属于Google 云端硬盘帐户的内容被迁移</span><span class="sxs-lookup"><span data-stu-id="07af8-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="07af8-315">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Google 云端硬盘管理报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="07af8-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="07af8-316">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="07af8-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="07af8-317">共享驱动器成员资格权限（<strong>注意</strong>：使用 Google 云端硬盘管理报告来标识共享驱动器成员资格。</span><span class="sxs-lookup"><span data-stu-id="07af8-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="07af8-318">指示最终用户迁移前在目标上配置这些成员资格设置。）</span><span class="sxs-lookup"><span data-stu-id="07af8-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="07af8-319">超出当前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制和局限</span></a> 的文件或文件夹</span><span class="sxs-lookup"><span data-stu-id="07af8-319">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="07af8-320"><strong>Box（Starter、Business、Enterprise）</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-320"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="07af8-321">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="07af8-321">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="07af8-322">文档</span><span class="sxs-lookup"><span data-stu-id="07af8-322">Documents</span></span> </li>
<li> <span data-ttu-id="07af8-323">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="07af8-323">File and folder structure</span></span> </li>
<li> <span data-ttu-id="07af8-324">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="07af8-324">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="07af8-325">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="07af8-325">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="07af8-326">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="07af8-326">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="07af8-327">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="07af8-327">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="07af8-328">创建日期</span><span class="sxs-lookup"><span data-stu-id="07af8-328">Created date</span></span> </li>
<li> <span data-ttu-id="07af8-329">修改日期</span><span class="sxs-lookup"><span data-stu-id="07af8-329">Modified date</span></span> </li>
<li> <span data-ttu-id="07af8-330">创建者</span><span class="sxs-lookup"><span data-stu-id="07af8-330">Created by</span></span> </li>
<li> <span data-ttu-id="07af8-331">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="07af8-331">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="07af8-332">属于 Box 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="07af8-332">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="07af8-333">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="07af8-333">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="07af8-334">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="07af8-334">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="07af8-335">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="07af8-335">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="07af8-336">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="07af8-336">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="07af8-337">Box 标记和高级元数据</span><span class="sxs-lookup"><span data-stu-id="07af8-337">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="07af8-338">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="07af8-338">File lock attributes</span></span> </li>
<li> <span data-ttu-id="07af8-339">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="07af8-339">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="07af8-340">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="07af8-340">Trashed items</span></span> </li>
<li> <span data-ttu-id="07af8-341">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="07af8-341">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="07af8-342">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="07af8-342">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="07af8-343">Box 应用、书签、收藏夹和工作流</span><span class="sxs-lookup"><span data-stu-id="07af8-343">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="07af8-344">不属于已迁移 Box 帐户的内容</span><span class="sxs-lookup"><span data-stu-id="07af8-344">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="07af8-345">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Box 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="07af8-345">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="07af8-346">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="07af8-346">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="07af8-347">超出当前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制和局限</span></a> 的文件或文件夹</span><span class="sxs-lookup"><span data-stu-id="07af8-347">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="07af8-348"><strong>用于 Teams的 Dropbox（标准版和高级版）</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-348"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="07af8-349">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="07af8-349">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="07af8-350">文档</span><span class="sxs-lookup"><span data-stu-id="07af8-350">Documents</span></span> </li>
<li> <span data-ttu-id="07af8-351">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="07af8-351">File and folder structure</span></span> </li>
<li> <span data-ttu-id="07af8-352">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="07af8-352">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="07af8-353">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="07af8-353">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="07af8-354">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="07af8-354">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="07af8-355">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="07af8-355">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="07af8-356">创建日期</span><span class="sxs-lookup"><span data-stu-id="07af8-356">Created date</span></span> </li>
<li> <span data-ttu-id="07af8-357">修改日期</span><span class="sxs-lookup"><span data-stu-id="07af8-357">Modified date</span></span> </li>
<li> <span data-ttu-id="07af8-358">创建者</span><span class="sxs-lookup"><span data-stu-id="07af8-358">Created by</span></span> </li>
<li> <span data-ttu-id="07af8-359">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="07af8-359">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="07af8-360">共享团队文件夹和内容</span><span class="sxs-lookup"><span data-stu-id="07af8-360">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="07af8-361">属于 Dropbox 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="07af8-361">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="07af8-362">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="07af8-362">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="07af8-363">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="07af8-363">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="07af8-364">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="07af8-364">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="07af8-365">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="07af8-365">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="07af8-366">高级元数据</span><span class="sxs-lookup"><span data-stu-id="07af8-366">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="07af8-367">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="07af8-367">File lock attributes</span></span> </li>
<li> <span data-ttu-id="07af8-368">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="07af8-368">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="07af8-369">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="07af8-369">Trashed items</span></span> </li>
<li> <span data-ttu-id="07af8-370">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="07af8-370">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="07af8-371">已卸载的 Dropbox 文件夹</span><span class="sxs-lookup"><span data-stu-id="07af8-371">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="07af8-372">已删除或已断开连接的用户</span><span class="sxs-lookup"><span data-stu-id="07af8-372">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="07af8-373">Dropbox Paper 文件、Dropbox Showcase 和 Dropbox Space</span><span class="sxs-lookup"><span data-stu-id="07af8-373">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="07af8-374">Dropbox 应用及收藏夹（已固定或加星标）</span><span class="sxs-lookup"><span data-stu-id="07af8-374">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="07af8-375">已迁移的 Dropbox 帐户不拥有的内容</span><span class="sxs-lookup"><span data-stu-id="07af8-375">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="07af8-376">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Dropbox 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="07af8-376">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="07af8-377">指示最终用户在迁移后与外部用户重新共享内容）</span><span class="sxs-lookup"><span data-stu-id="07af8-377">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="07af8-378">超出当前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制和局限</span></a> 的文件或文件夹</span><span class="sxs-lookup"><span data-stu-id="07af8-378">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="07af8-379">FastTrack 责任</span><span class="sxs-lookup"><span data-stu-id="07af8-379">FastTrack responsibilities</span></span>

<span data-ttu-id="07af8-380">我们的 FastTrack 专家在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="07af8-380">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="07af8-381">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息</span><span class="sxs-lookup"><span data-stu-id="07af8-381">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="07af8-382">你的责任</span><span class="sxs-lookup"><span data-stu-id="07af8-382">Your responsibilities</span></span>

<span data-ttu-id="07af8-383">你在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="07af8-383">You perform standard activities during the migration project.</span></span> <span data-ttu-id="07af8-384">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息</span><span class="sxs-lookup"><span data-stu-id="07af8-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="07af8-385">此外，你还将执行以下特定于 SharePoint Online 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="07af8-385">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="07af8-386">预置将作为迁移事件目标的所有 SharePoint 团队网站。</span><span class="sxs-lookup"><span data-stu-id="07af8-386">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="07af8-387">到 OneDrive for Business 的迁移</span><span class="sxs-lookup"><span data-stu-id="07af8-387">Migration to OneDrive for Business</span></span>

<span data-ttu-id="07af8-388">当你选择使用 FastTrack 将文件迁移到 OneDrive for Business 时，我们将提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="07af8-388">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="07af8-389">我们提供指导，以帮助你计划迁移、配置源环境和 OneDrive for Business，并利用我们的数据迁移服务来迁移文件。</span><span class="sxs-lookup"><span data-stu-id="07af8-389">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="07af8-390">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="07af8-390">You create and schedule your migration events.</span></span> <span data-ttu-id="07af8-391">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="07af8-391">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="07af8-392">迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源中的的文件已迁移到 OneDrive for Business。</span><span class="sxs-lookup"><span data-stu-id="07af8-392">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="07af8-393">注意事项</span><span class="sxs-lookup"><span data-stu-id="07af8-393">Considerations</span></span>

  - <span data-ttu-id="07af8-394">所有迁移均受 OneDrive for business 配额限制。</span><span class="sxs-lookup"><span data-stu-id="07af8-394">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="07af8-395">有关详细信息，请参阅 [<span class="underline">SharePoint Online 和 OneDrive for Business 的软件边界与限制</span>](https://go.microsoft.com/fwlink/?LinkId=698855)。</span><span class="sxs-lookup"><span data-stu-id="07af8-395">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="07af8-396">建议将迁移数据总量限制在你享有的整体 SharePoint Online 存储配额（包括你可能单独购买的其他存储）的 75% 以内。</span><span class="sxs-lookup"><span data-stu-id="07af8-396">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="07af8-397">FastTrack 仅迁移到活动的 OneDrive for Business 驱动器。</span><span class="sxs-lookup"><span data-stu-id="07af8-397">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="07af8-398">源环境详细信息</span><span class="sxs-lookup"><span data-stu-id="07af8-398">Source environment details</span></span>

<span data-ttu-id="07af8-399">我们的数据迁移服务从以下源环境迁移数据：</span><span class="sxs-lookup"><span data-stu-id="07af8-399">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="07af8-400">文件共享（SMB 文件在支持 SMB 2.0 前向的设备上共享）。</span><span class="sxs-lookup"><span data-stu-id="07af8-400">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="07af8-401">单个 G 套件环境（仅限 Google 云端硬盘）。</span><span class="sxs-lookup"><span data-stu-id="07af8-401">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="07af8-402">Box（Starter、Business、Enterprise）。</span><span class="sxs-lookup"><span data-stu-id="07af8-402">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="07af8-403">用于 Teams的 Dropbox（标准版和高级版）</span><span class="sxs-lookup"><span data-stu-id="07af8-403">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="07af8-404">下表显示了特定于每个源环境的迁移详细信息：</span><span class="sxs-lookup"><span data-stu-id="07af8-404">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="07af8-405"><strong>源环境</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-405"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="07af8-406"><strong>迁移类型</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-406"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="07af8-407"><strong>迁移内容</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-407"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="07af8-408"><strong>不迁移的内容</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-408"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="07af8-409"><strong>任何支持 SMB 2.0 及更高版本的文件共享设备</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-409"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="07af8-410">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="07af8-410">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="07af8-411">文档</span><span class="sxs-lookup"><span data-stu-id="07af8-411">Documents</span></span> </li>
<li> <span data-ttu-id="07af8-412">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="07af8-412">File and folder structure</span></span> </li>
<li> <span data-ttu-id="07af8-413">用户级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="07af8-413">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="07af8-414">组级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="07af8-414">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="07af8-415">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="07af8-415">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="07af8-416">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="07af8-416">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="07af8-417">创建日期</span><span class="sxs-lookup"><span data-stu-id="07af8-417">Created date</span></span> </li>
<li> <span data-ttu-id="07af8-418">修改日期</span><span class="sxs-lookup"><span data-stu-id="07af8-418">Modified date</span></span> </li>
<li> <span data-ttu-id="07af8-419">创建者</span><span class="sxs-lookup"><span data-stu-id="07af8-419">Created by</span></span> </li>
<li> <span data-ttu-id="07af8-420">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="07af8-420">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="07af8-421">\*必须配置目录同步。</span><span class="sxs-lookup"><span data-stu-id="07af8-421">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="07af8-422">只迁移对 Windows 文件资源管理器公开的 NTFS 权限。</span><span class="sxs-lookup"><span data-stu-id="07af8-422">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="07af8-423">不会迁移文件共享设备上直接托管的权限。</span><span class="sxs-lookup"><span data-stu-id="07af8-423">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="07af8-424">如果数据存储在 SMB 2.0 设备上，只会迁移 SMB 协议公开的与 NTFS 等同的权限。</span><span class="sxs-lookup"><span data-stu-id="07af8-424">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="07af8-425">所有权历史记录和旧版本</span><span class="sxs-lookup"><span data-stu-id="07af8-425">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="07af8-426">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="07af8-426">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="07af8-427">旧版本</span><span class="sxs-lookup"><span data-stu-id="07af8-427">Previous versions</span></span> </li>
<li> <span data-ttu-id="07af8-428">Windows 文件和文件夹属性（如只读和隐藏）</span><span class="sxs-lookup"><span data-stu-id="07af8-428">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="07af8-429">非 Windows 新技术文件系统 (NTFS) 和 NTFS 高级权限和特殊设置：</span><span class="sxs-lookup"><span data-stu-id="07af8-429">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="07af8-430">显式拒绝权限（在迁移后删除的权限、从属于并行权限的内容或父文件夹上的权限）</span><span class="sxs-lookup"><span data-stu-id="07af8-430">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="07af8-431">NTFS 审核配置</span><span class="sxs-lookup"><span data-stu-id="07af8-431">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="07af8-432">文件分类基础结构 (FCI) 提供的附加文件元数据</span><span class="sxs-lookup"><span data-stu-id="07af8-432">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="07af8-433">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="07af8-433">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="07af8-434">隐藏的共享</span><span class="sxs-lookup"><span data-stu-id="07af8-434">Hidden shares</span></span> </li>
<li> <span data-ttu-id="07af8-435">共享（如在共享级别授予的权限）</span><span class="sxs-lookup"><span data-stu-id="07af8-435">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="07af8-436">超出当前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制和局限</span></a> 的文件或文件夹</span><span class="sxs-lookup"><span data-stu-id="07af8-436">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="07af8-437"><strong>单个 G 套件环境（仅限 Google 云端硬盘）</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-437"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="07af8-438">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="07af8-438">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="07af8-439">Google 文档、工作表和幻灯片（文件包括超过10 MB的，转换为等同的 Office 格式）</span><span class="sxs-lookup"><span data-stu-id="07af8-439">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="07af8-440">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="07af8-440">File and folder structure</span></span> </li>
<li> <span data-ttu-id="07af8-441">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="07af8-441">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="07af8-442">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="07af8-442">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="07af8-443">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="07af8-443">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="07af8-444">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="07af8-444">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="07af8-445">创建日期</span><span class="sxs-lookup"><span data-stu-id="07af8-445">Created date</span></span> </li>
<li> <span data-ttu-id="07af8-446">修改日期</span><span class="sxs-lookup"><span data-stu-id="07af8-446">Modified date</span></span> </li>
<li> <span data-ttu-id="07af8-447">创建者</span><span class="sxs-lookup"><span data-stu-id="07af8-447">Created by</span></span> </li>
<li> <span data-ttu-id="07af8-448">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="07af8-448">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="07af8-449">共享驱动器 （文件夹和文件）</span><span class="sxs-lookup"><span data-stu-id="07af8-449">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="07af8-450">属于 Google 云端硬盘帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="07af8-450">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="07af8-451">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="07af8-451">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="07af8-452">文件和文件夹说明、文件夹颜色</span><span class="sxs-lookup"><span data-stu-id="07af8-452">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="07af8-453">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="07af8-453">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="07af8-454">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="07af8-454">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="07af8-455">高级元数据</span><span class="sxs-lookup"><span data-stu-id="07af8-455">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="07af8-456">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="07af8-456">File lock attributes</span></span> </li>
<li> <span data-ttu-id="07af8-457">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="07af8-457">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="07af8-458">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="07af8-458">Trashed items</span></span> </li>
<li> <span data-ttu-id="07af8-459">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="07af8-459">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="07af8-460">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="07af8-460">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="07af8-461">Google 相册、Forms、地图和其他已连接应用</span><span class="sxs-lookup"><span data-stu-id="07af8-461">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="07af8-462">Google 绘图</span><span class="sxs-lookup"><span data-stu-id="07af8-462">Google Drawings</span></span> </li>
<li> <span data-ttu-id="07af8-463">组织外部的共享内容</span><span class="sxs-lookup"><span data-stu-id="07af8-463">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="07af8-464">不属于Google 云端硬盘帐户的内容被迁移</span><span class="sxs-lookup"><span data-stu-id="07af8-464">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="07af8-465">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Google 云端硬盘管理报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="07af8-465">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="07af8-466">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="07af8-466">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="07af8-467">共享驱动器成员资格权限（<strong>注意</strong>：使用 Google 云端硬盘管理报告来标识共享驱动器成员资格。</span><span class="sxs-lookup"><span data-stu-id="07af8-467">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="07af8-468">指示最终用户迁移前在目标上配置这些成员资格设置。）</span><span class="sxs-lookup"><span data-stu-id="07af8-468">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="07af8-469">超出当前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制和局限</span></a> 的文件或文件夹</span><span class="sxs-lookup"><span data-stu-id="07af8-469">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="07af8-470"><strong>Box（Starter、Business、Enterprise）</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-470"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="07af8-471">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="07af8-471">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="07af8-472">文档</span><span class="sxs-lookup"><span data-stu-id="07af8-472">Documents</span></span> </li>
<li> <span data-ttu-id="07af8-473">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="07af8-473">File and folder structure</span></span> </li>
<li> <span data-ttu-id="07af8-474">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="07af8-474">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="07af8-475">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="07af8-475">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="07af8-476">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="07af8-476">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="07af8-477">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="07af8-477">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="07af8-478">创建日期</span><span class="sxs-lookup"><span data-stu-id="07af8-478">Created date</span></span> </li>
<li> <span data-ttu-id="07af8-479">修改日期</span><span class="sxs-lookup"><span data-stu-id="07af8-479">Modified date</span></span> </li>
<li> <span data-ttu-id="07af8-480">创建者</span><span class="sxs-lookup"><span data-stu-id="07af8-480">Created by</span></span> </li>
<li> <span data-ttu-id="07af8-481">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="07af8-481">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="07af8-482">属于 Box 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="07af8-482">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="07af8-483">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="07af8-483">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="07af8-484">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="07af8-484">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="07af8-485">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="07af8-485">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="07af8-486">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="07af8-486">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="07af8-487">Box 标记和高级元数据</span><span class="sxs-lookup"><span data-stu-id="07af8-487">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="07af8-488">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="07af8-488">File lock attributes</span></span> </li>
<li> <span data-ttu-id="07af8-489">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="07af8-489">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="07af8-490">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="07af8-490">Trashed items</span></span> </li>
<li> <span data-ttu-id="07af8-491">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="07af8-491">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="07af8-492">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="07af8-492">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="07af8-493">Box 应用、书签、收藏夹和工作流</span><span class="sxs-lookup"><span data-stu-id="07af8-493">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="07af8-494">不属于已迁移 Box 帐户的内容</span><span class="sxs-lookup"><span data-stu-id="07af8-494">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="07af8-495">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Box 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="07af8-495">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="07af8-496">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="07af8-496">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="07af8-497">超出当前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制和局限</span></a> 的文件或文件夹</span><span class="sxs-lookup"><span data-stu-id="07af8-497">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="07af8-498"><strong>用于 Teams的 Dropbox（标准版和高级版）</strong></span><span class="sxs-lookup"><span data-stu-id="07af8-498"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="07af8-499">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="07af8-499">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="07af8-500">文档</span><span class="sxs-lookup"><span data-stu-id="07af8-500">Documents</span></span> </li>
<li> <span data-ttu-id="07af8-501">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="07af8-501">File and folder structure</span></span> </li>
<li> <span data-ttu-id="07af8-502">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="07af8-502">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="07af8-503">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="07af8-503">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="07af8-504">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="07af8-504">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="07af8-505">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="07af8-505">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="07af8-506">创建日期</span><span class="sxs-lookup"><span data-stu-id="07af8-506">Created date</span></span> </li>
<li> <span data-ttu-id="07af8-507">修改日期</span><span class="sxs-lookup"><span data-stu-id="07af8-507">Modified date</span></span> </li>
<li> <span data-ttu-id="07af8-508">创建者</span><span class="sxs-lookup"><span data-stu-id="07af8-508">Created by</span></span> </li>
<li> <span data-ttu-id="07af8-509">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="07af8-509">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="07af8-510">共享团队文件夹和内容</span><span class="sxs-lookup"><span data-stu-id="07af8-510">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="07af8-511">属于 Dropbox 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="07af8-511">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="07af8-512">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="07af8-512">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="07af8-513">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="07af8-513">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="07af8-514">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="07af8-514">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="07af8-515">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="07af8-515">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="07af8-516">高级元数据</span><span class="sxs-lookup"><span data-stu-id="07af8-516">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="07af8-517">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="07af8-517">File lock attributes</span></span> </li>
<li> <span data-ttu-id="07af8-518">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="07af8-518">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="07af8-519">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="07af8-519">Trashed items</span></span> </li>
<li> <span data-ttu-id="07af8-520">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="07af8-520">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="07af8-521">已卸载的 Dropbox 文件夹</span><span class="sxs-lookup"><span data-stu-id="07af8-521">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="07af8-522">已删除或已断开连接的用户</span><span class="sxs-lookup"><span data-stu-id="07af8-522">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="07af8-523">Dropbox Paper 文件、Dropbox Showcase 和 Dropbox Space</span><span class="sxs-lookup"><span data-stu-id="07af8-523">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="07af8-524">Dropbox 应用及收藏夹（已固定或加星标）</span><span class="sxs-lookup"><span data-stu-id="07af8-524">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="07af8-525">已迁移的 Dropbox 帐户不拥有的内容</span><span class="sxs-lookup"><span data-stu-id="07af8-525">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="07af8-526">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Dropbox 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="07af8-526">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="07af8-527">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="07af8-527">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="07af8-528">超出当前  <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online 限制和局限</span></a> 的文件或文件夹</span><span class="sxs-lookup"><span data-stu-id="07af8-528">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="07af8-529">FastTrack 责任</span><span class="sxs-lookup"><span data-stu-id="07af8-529">FastTrack responsibilities</span></span>

<span data-ttu-id="07af8-530">我们的 FastTrack 专家在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="07af8-530">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="07af8-531">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="07af8-531">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="07af8-532">你的责任</span><span class="sxs-lookup"><span data-stu-id="07af8-532">Your responsibilities</span></span>

<span data-ttu-id="07af8-533">你在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="07af8-533">You perform standard activities during the migration project.</span></span> <span data-ttu-id="07af8-534">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="07af8-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="07af8-535">此外，你还将执行以下特定于 OneDrive for Business 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="07af8-535">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="07af8-536">预置将作为迁移事件目标的所有 OneDrive for Business 网站。</span><span class="sxs-lookup"><span data-stu-id="07af8-536">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
