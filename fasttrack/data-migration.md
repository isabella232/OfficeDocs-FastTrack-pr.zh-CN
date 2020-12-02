---
title: 数据迁移
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 12/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack 可以帮助你将源环境中的邮件和文件数据迁移到 Office 365（Exchange Online、SharePoint Online 和 OneDrive for Business）。 我们提供的帮助类型取决于你的 Office 365 许可证数量。
ms.openlocfilehash: 5a64bcbecffa3fd78f54b9a5e0f3f07e76d0b316
ms.sourcegitcommit: d69d3e1e478a817f8279e9da98880499e9302665
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 12/01/2020
ms.locfileid: "49525328"
---
# <a name="data-migration"></a><span data-ttu-id="1d86c-104">数据迁移</span><span class="sxs-lookup"><span data-stu-id="1d86c-104">Data Migration</span></span>

<span data-ttu-id="1d86c-105">FastTrack 可以帮助你将源环境中的邮件和文件数据迁移到 Office 365（Exchange Online、SharePoint Online 和 OneDrive for Business）。</span><span class="sxs-lookup"><span data-stu-id="1d86c-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="1d86c-106">我们提供的帮助类型取决于你的 Office 365 许可证数量：</span><span class="sxs-lookup"><span data-stu-id="1d86c-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="1d86c-107">**对于具有 150-499 个许可证的 Office 365 租户**：FastTrack 仅提供迁移指南；你负责执行数据迁移。</span><span class="sxs-lookup"><span data-stu-id="1d86c-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="1d86c-108">我们将指导你阅读文档，以帮助你计划和使用免费工具来执行自助服务迁移。</span><span class="sxs-lookup"><span data-stu-id="1d86c-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="1d86c-109">**对于具有 500 个或更多许可证的 Office 365 租户**：FastTrack 提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="1d86c-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="1d86c-110">我们提供指导，以帮助你计划迁移、配置源环境和 Office 365 租户，并利用我们的数据迁移服务来迁移数据。</span><span class="sxs-lookup"><span data-stu-id="1d86c-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="1d86c-111">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="1d86c-111">You create and schedule your migration events.</span></span> <span data-ttu-id="1d86c-112">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="1d86c-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="1d86c-113">如果你在 2017 年 9 月 1 日之前购买或续订了商业计划，则只需 150 个许可证即可获得数据迁移服务的资格。</span><span class="sxs-lookup"><span data-stu-id="1d86c-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="1d86c-114">对于教育计划，只有付费教职员工许可证才有资格获得数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="1d86c-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="1d86c-115">注意事项</span><span class="sxs-lookup"><span data-stu-id="1d86c-115">Considerations</span></span>

  - <span data-ttu-id="1d86c-116">你的源环境必须满足特定的期望才能将数据迁移到 Office 365。</span><span class="sxs-lookup"><span data-stu-id="1d86c-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="1d86c-117">有关 Exchange、SharePoint 和 OneDrive for Business 的源环境期望的更多信息，请参阅[产品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="1d86c-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="1d86c-118">我们需要对你的源环境和 Office 365 租户具有适当的访问权限和权限才能提供数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="1d86c-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="1d86c-119">我们的数据迁移服务并非为满足特殊法律或法规要求的数据而设计或以此为目的。</span><span class="sxs-lookup"><span data-stu-id="1d86c-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="1d86c-120">我们迁移数据时，可将其传输到我们维护设施的任何位置、从中进行存储和处理（除非为你的 FastTrack 迁移项目提供了其他位置）。</span><span class="sxs-lookup"><span data-stu-id="1d86c-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="1d86c-121">我们无法保证邮件或文件的迁移速度。</span><span class="sxs-lookup"><span data-stu-id="1d86c-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="1d86c-122">不可预见的问题（例如源环境中不可读或损坏的项）可能会阻止我们迁移某些数据项。</span><span class="sxs-lookup"><span data-stu-id="1d86c-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="1d86c-123">我们无法控制的外部因素（例如对第三方应用程序编程接口 (API) 的更改）可能会导致我们的数据迁移服务发生更改、延迟或暂停。</span><span class="sxs-lookup"><span data-stu-id="1d86c-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="1d86c-124">迁移服务可用性</span><span class="sxs-lookup"><span data-stu-id="1d86c-124">Migration service availability</span></span>

  - <span data-ttu-id="1d86c-125">**对于商业和英国政府客户：** 我们每周七 (7) 天，每天 24 小时 (24x7) 提供数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="1d86c-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="1d86c-126">**对于美国政府/DOD 客户：** 我们每周五 (5) 天，每天 24 小时 (24x5) 提供数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="1d86c-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="1d86c-127">到 Exchange Online 的迁移</span><span class="sxs-lookup"><span data-stu-id="1d86c-127">Migration to Exchange Online</span></span>

<span data-ttu-id="1d86c-128">当你选择使用 FastTrack 将电子邮件迁移到 Exchange Online 时，我们将提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="1d86c-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="1d86c-129">我们提供指导，以帮助你计划迁移、配置源环境和 Exchange Online，并利用我们的数据迁移服务来迁移邮箱。</span><span class="sxs-lookup"><span data-stu-id="1d86c-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="1d86c-130">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="1d86c-130">You create and schedule your migration events.</span></span> <span data-ttu-id="1d86c-131">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="1d86c-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="1d86c-132">迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源邮箱中的的邮件已迁移到 Exchange Online。</span><span class="sxs-lookup"><span data-stu-id="1d86c-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="1d86c-133">注意事项</span><span class="sxs-lookup"><span data-stu-id="1d86c-133">Considerations</span></span>

  - <span data-ttu-id="1d86c-134">迁移前，必须完成 Exchange Online 的FastTrack 核心载入；</span><span class="sxs-lookup"><span data-stu-id="1d86c-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="1d86c-135">如果你自行执行载入，则必须通过必需的检查和先决条件。</span><span class="sxs-lookup"><span data-stu-id="1d86c-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="1d86c-136">有关详细信息，请参阅[产品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="1d86c-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="1d86c-137">FastTrack 仅迁移到活动的 Office 365 邮箱。</span><span class="sxs-lookup"><span data-stu-id="1d86c-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="1d86c-138">如果要从本地 Exchange 环境迁移，则必须满足特定要求。</span><span class="sxs-lookup"><span data-stu-id="1d86c-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="1d86c-139">有关详细信息，请参阅[配置混合部署先决条件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="1d86c-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="1d86c-140">每个源环境都必须处于源环境中相应产品的最新服务包 (SP) 和汇总更新 (RU)/累积更新 (CU) 级别。</span><span class="sxs-lookup"><span data-stu-id="1d86c-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="1d86c-141">位于本地 Active Directory 中的通讯组列表（*MailEnabledGroup* 对象）和外部联系人（*MailEnabledContact* 对象）不是邮箱数据迁移的一部分。</span><span class="sxs-lookup"><span data-stu-id="1d86c-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="1d86c-142">但是，你可以使用 Azure Active Directory (Azure AD) Connect 将它们同步。</span><span class="sxs-lookup"><span data-stu-id="1d86c-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="1d86c-143">源环境</span><span class="sxs-lookup"><span data-stu-id="1d86c-143">Source environments</span></span>

<span data-ttu-id="1d86c-144">我们的数据迁移服务从以下源环境迁移数据：</span><span class="sxs-lookup"><span data-stu-id="1d86c-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="1d86c-145">具有单个或多个 Exchange 组织的单个或多个 Active Directory 林（每个 Exchange 邮件系统均须为 Exchange 2010 或更高版本）。</span><span class="sxs-lookup"><span data-stu-id="1d86c-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="1d86c-146">一个支持 IMAP 的电子邮件环境。</span><span class="sxs-lookup"><span data-stu-id="1d86c-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="1d86c-147">G 套件环境（仅限 Gmail、联系人和日历）</span><span class="sxs-lookup"><span data-stu-id="1d86c-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="1d86c-148">下表显示了特定于每个源环境的迁移详细信息：</span><span class="sxs-lookup"><span data-stu-id="1d86c-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="1d86c-149"><strong>源环境</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="1d86c-150"><strong>迁移类型</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="1d86c-151"><strong>迁移内容</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="1d86c-152"><strong>不迁移的内容</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="1d86c-153"><strong>Exchange 2010、Exchange 2013、Exchange 2016、Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="1d86c-154">
<strong>注意：</strong> 有关本地 Exchange 依存关系，请参阅 <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">混合部署先决条件</span></a>。</span><span class="sxs-lookup"><span data-stu-id="1d86c-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="1d86c-155">使用混合部署进行的迁移</span><span class="sxs-lookup"><span data-stu-id="1d86c-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="1d86c-156">电子邮件</span><span class="sxs-lookup"><span data-stu-id="1d86c-156">Emails</span></span></li>
<li><span data-ttu-id="1d86c-157">邮箱规则</span><span class="sxs-lookup"><span data-stu-id="1d86c-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="1d86c-158">代理</span><span class="sxs-lookup"><span data-stu-id="1d86c-158">Delegates</span></span></li>
<li><span data-ttu-id="1d86c-159">邮箱联系人</span><span class="sxs-lookup"><span data-stu-id="1d86c-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="1d86c-160">日历</span><span class="sxs-lookup"><span data-stu-id="1d86c-160">Calendar</span></span> </li>
<li> <span data-ttu-id="1d86c-161">任务</span><span class="sxs-lookup"><span data-stu-id="1d86c-161">Tasks</span></span> </li>
<li> <span data-ttu-id="1d86c-162">权限管理的电子邮件</span><span class="sxs-lookup"><span data-stu-id="1d86c-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="1d86c-163">加密电子邮件</span><span class="sxs-lookup"><span data-stu-id="1d86c-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="1d86c-164">签名</span><span class="sxs-lookup"><span data-stu-id="1d86c-164">Signatures</span></span> </li>
<li> <span data-ttu-id="1d86c-165">与用户的邮箱一起迁移的个人存档</span><span class="sxs-lookup"><span data-stu-id="1d86c-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="1d86c-166">可恢复的项目</span><span class="sxs-lookup"><span data-stu-id="1d86c-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="1d86c-167">公用文件夹</span><span class="sxs-lookup"><span data-stu-id="1d86c-167">Public folders</span></span> </li>
<li> <span data-ttu-id="1d86c-168">超出邮件大小限制的所有电子邮件</span><span class="sxs-lookup"><span data-stu-id="1d86c-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="1d86c-169">日记存档或任何第三方存档解决方案</span><span class="sxs-lookup"><span data-stu-id="1d86c-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="1d86c-170">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="1d86c-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="1d86c-171">来自个人存储表 (PST) 文件的存档数据</span><span class="sxs-lookup"><span data-stu-id="1d86c-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="1d86c-172">已损坏的项目</span><span class="sxs-lookup"><span data-stu-id="1d86c-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="1d86c-173">非活动邮箱</span><span class="sxs-lookup"><span data-stu-id="1d86c-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="1d86c-174"><strong>G 套件环境（仅限 Gmail、联系人和日历）</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="1d86c-175">
<strong>注意：</strong> 您的 G 套件环境必须满足 <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">执行 G 套件迁移</a>中所述的先决条件。</span><span class="sxs-lookup"><span data-stu-id="1d86c-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="1d86c-176">直接转换或暂存</span><span class="sxs-lookup"><span data-stu-id="1d86c-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="1d86c-177">电子邮件</span><span class="sxs-lookup"><span data-stu-id="1d86c-177">Emails</span></span> </li>
<li> <span data-ttu-id="1d86c-178">邮箱联系人（每个联系人最多迁移 3 个电子邮件地址）</span><span class="sxs-lookup"><span data-stu-id="1d86c-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="1d86c-179">日历</span><span class="sxs-lookup"><span data-stu-id="1d86c-179">Calendar</span></span> </li>
<li> <span data-ttu-id="1d86c-180">标签</span><span class="sxs-lookup"><span data-stu-id="1d86c-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="1d86c-181">规则</span><span class="sxs-lookup"><span data-stu-id="1d86c-181">Rules</span></span> </li>
<li> <span data-ttu-id="1d86c-182">代理</span><span class="sxs-lookup"><span data-stu-id="1d86c-182">Delegates</span></span> </li>
<li> <span data-ttu-id="1d86c-183">签名</span><span class="sxs-lookup"><span data-stu-id="1d86c-183">Signatures</span></span> </li>
<li> <span data-ttu-id="1d86c-184">任务</span><span class="sxs-lookup"><span data-stu-id="1d86c-184">Tasks</span></span> </li>
<li> <span data-ttu-id="1d86c-185">超出邮件大小限制的所有电子邮件或附件</span><span class="sxs-lookup"><span data-stu-id="1d86c-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="1d86c-186">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="1d86c-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="1d86c-187">来自 PST 文件或任何第三方存档解决方案（例如 Google Vault）的存档数据</span><span class="sxs-lookup"><span data-stu-id="1d86c-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="1d86c-188">权限管理或加密电子邮件</span><span class="sxs-lookup"><span data-stu-id="1d86c-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="1d86c-189">已损坏的项目</span><span class="sxs-lookup"><span data-stu-id="1d86c-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="1d86c-190">Google Hangout\*\*</span><span class="sxs-lookup"><span data-stu-id="1d86c-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="1d86c-191">Google 组</span><span class="sxs-lookup"><span data-stu-id="1d86c-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="1d86c-192">资源邮箱</span><span class="sxs-lookup"><span data-stu-id="1d86c-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="1d86c-193">非活动邮箱</span><span class="sxs-lookup"><span data-stu-id="1d86c-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="1d86c-194">假期设置和自动答复设置</span><span class="sxs-lookup"><span data-stu-id="1d86c-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="1d86c-195">共享日历、云附件、Google Hangout 链接和事件颜色</span><span class="sxs-lookup"><span data-stu-id="1d86c-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="1d86c-196">\*\*迁移另存为标签的环聊对话。</span><span class="sxs-lookup"><span data-stu-id="1d86c-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="1d86c-197"><strong>IMAP4 源（如 Domino、GroupWise 或 Zimbra）</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="1d86c-198">使用本机 IMAP4 工具进行迁移</span><span class="sxs-lookup"><span data-stu-id="1d86c-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="1d86c-199">电子邮件</span><span class="sxs-lookup"><span data-stu-id="1d86c-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="1d86c-200">规则</span><span class="sxs-lookup"><span data-stu-id="1d86c-200">Rules</span></span> </li>
<li> <span data-ttu-id="1d86c-201">代理</span><span class="sxs-lookup"><span data-stu-id="1d86c-201">Delegates</span></span> </li>
<li> <span data-ttu-id="1d86c-202">通讯组列表</span><span class="sxs-lookup"><span data-stu-id="1d86c-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="1d86c-203">外部联系人</span><span class="sxs-lookup"><span data-stu-id="1d86c-203">External contacts</span></span> </li>
<li> <span data-ttu-id="1d86c-204">启用邮件的用户</span><span class="sxs-lookup"><span data-stu-id="1d86c-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="1d86c-205">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="1d86c-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="1d86c-206">邮箱联系人</span><span class="sxs-lookup"><span data-stu-id="1d86c-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="1d86c-207">日历</span><span class="sxs-lookup"><span data-stu-id="1d86c-207">Calendar</span></span> </li>
<li> <span data-ttu-id="1d86c-208">签名</span><span class="sxs-lookup"><span data-stu-id="1d86c-208">Signatures</span></span> </li>
<li> <span data-ttu-id="1d86c-209">任务</span><span class="sxs-lookup"><span data-stu-id="1d86c-209">Tasks</span></span> </li>
<li> <span data-ttu-id="1d86c-210">超出邮件大小限制的所有电子邮件</span><span class="sxs-lookup"><span data-stu-id="1d86c-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="1d86c-211">存档数据</span><span class="sxs-lookup"><span data-stu-id="1d86c-211">Archive data</span></span> </li>
<li> <span data-ttu-id="1d86c-212">加密电子邮件</span><span class="sxs-lookup"><span data-stu-id="1d86c-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="1d86c-213">已损坏的项目</span><span class="sxs-lookup"><span data-stu-id="1d86c-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="1d86c-214">非活动邮箱</span><span class="sxs-lookup"><span data-stu-id="1d86c-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="1d86c-215">FastTrack 责任</span><span class="sxs-lookup"><span data-stu-id="1d86c-215">FastTrack responsibilities</span></span>

<span data-ttu-id="1d86c-216">我们的 FastTrack 专家在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="1d86c-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="1d86c-217">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="1d86c-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="1d86c-218">我们的 FastTrack 专家还执行以下特定于 Exchange 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="1d86c-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="1d86c-219">提供指导以帮助你在源环境和 Exchange Online 之间启用 SMTP 邮件路由共存（如果适用）。</span><span class="sxs-lookup"><span data-stu-id="1d86c-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="1d86c-220">你的责任</span><span class="sxs-lookup"><span data-stu-id="1d86c-220">Your responsibilities</span></span>

<span data-ttu-id="1d86c-221">你在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="1d86c-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="1d86c-222">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="1d86c-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="1d86c-223">此外，你还将执行以下特定于 Exchange 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="1d86c-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="1d86c-224">完成 Exchange Online 的FastTrack 核心载入。</span><span class="sxs-lookup"><span data-stu-id="1d86c-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="1d86c-225">如果你自行执行载入，则必须通过必需的检查和先决条件。</span><span class="sxs-lookup"><span data-stu-id="1d86c-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="1d86c-226">有关详细信息，请参阅[产品和功能](products-and-capabilities.md)。</span><span class="sxs-lookup"><span data-stu-id="1d86c-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="1d86c-227">根据 Office 365 准则安装客户端软件的相应级别。</span><span class="sxs-lookup"><span data-stu-id="1d86c-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="1d86c-228">有关详细信息，请参阅[新式工作区](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg)。</span><span class="sxs-lookup"><span data-stu-id="1d86c-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="1d86c-229">如果要从本地 Exchange 环境迁移，需满足特定要求。</span><span class="sxs-lookup"><span data-stu-id="1d86c-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="1d86c-230">有关详细信息，请参阅[配置混合部署先决条件](https://go.microsoft.com/fwlink/?LinkId=787528)。</span><span class="sxs-lookup"><span data-stu-id="1d86c-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="1d86c-231">确保每个源环境都位于最新服务包 (SP) 和汇总 (RU)/累积更新 (CU) 级别（如果适用）。</span><span class="sxs-lookup"><span data-stu-id="1d86c-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="1d86c-232">配置和验证源环境和 Exchange Online 之间的 SMTP 邮件路由共存（如果适用）。</span><span class="sxs-lookup"><span data-stu-id="1d86c-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="1d86c-233">确保源邮箱大小不超过目标邮箱配额。</span><span class="sxs-lookup"><span data-stu-id="1d86c-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="1d86c-234">根据源平台的不同，可能需要将源数据限制为目标邮箱配额的 85%。</span><span class="sxs-lookup"><span data-stu-id="1d86c-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="1d86c-235">根据需要迁移客户端数据。</span><span class="sxs-lookup"><span data-stu-id="1d86c-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="1d86c-236">这包括但不限于本地通讯簿、本地 PST 文件中的数据、Outlook 规则和本地 Outlook 设置。</span><span class="sxs-lookup"><span data-stu-id="1d86c-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="1d86c-237">帮助最终用户修正客户端迁移问题。</span><span class="sxs-lookup"><span data-stu-id="1d86c-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="1d86c-238">到 SharePoint Online 的迁移</span><span class="sxs-lookup"><span data-stu-id="1d86c-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="1d86c-239">当你选择使用 FastTrack 将文件迁移到 SharePoint Online 时，我们将提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="1d86c-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="1d86c-240">我们提供指导，以帮助你计划迁移、配置源环境和 SharePoint Online，并利用我们的数据迁移服务来迁移文件。</span><span class="sxs-lookup"><span data-stu-id="1d86c-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="1d86c-241">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="1d86c-241">You create and schedule your migration events.</span></span> <span data-ttu-id="1d86c-242">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="1d86c-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="1d86c-243">迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源中的的文件已迁移到 SharePoint Online。</span><span class="sxs-lookup"><span data-stu-id="1d86c-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="1d86c-244">注意事项</span><span class="sxs-lookup"><span data-stu-id="1d86c-244">Considerations</span></span>

  - <span data-ttu-id="1d86c-245">所有迁移均受 SharePoint Online 配额的限制。</span><span class="sxs-lookup"><span data-stu-id="1d86c-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="1d86c-246">有关详细信息，请参阅 [<span class="underline">SharePoint Online 和 OneDrive for Business 的软件边界与限制</span>](https://go.microsoft.com/fwlink/?LinkId=698855)。</span><span class="sxs-lookup"><span data-stu-id="1d86c-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="1d86c-247">建议将迁移总量限制在你享有的整体 SharePoint Online 存储配额（包括你可能单独购买的其他存储）的 75% 以内。</span><span class="sxs-lookup"><span data-stu-id="1d86c-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="1d86c-248">源环境详细信息</span><span class="sxs-lookup"><span data-stu-id="1d86c-248">Source environment details</span></span>

<span data-ttu-id="1d86c-249">我们的数据迁移服务从以下源环境迁移数据：</span><span class="sxs-lookup"><span data-stu-id="1d86c-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="1d86c-250">文件共享（支持 SMB 2.0 前向的设备上的服务器消息块 (SMB) 文件共享）。</span><span class="sxs-lookup"><span data-stu-id="1d86c-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="1d86c-251">单个 G 套件环境（仅限 Google Drive）。</span><span class="sxs-lookup"><span data-stu-id="1d86c-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="1d86c-252">Box（Starter、Business、Enterprise）。</span><span class="sxs-lookup"><span data-stu-id="1d86c-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="1d86c-253">用于 Teams的 Dropbox（标准版和高级版）</span><span class="sxs-lookup"><span data-stu-id="1d86c-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="1d86c-254">下表显示了特定于每个源环境的迁移详细信息：</span><span class="sxs-lookup"><span data-stu-id="1d86c-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="1d86c-255"><strong>源环境</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="1d86c-256"><strong>迁移类型</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="1d86c-257"><strong>迁移内容</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="1d86c-258"><strong>不迁移的内容</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="1d86c-259"><strong>任何支持 SMB 2.0 及更高版本的文件共享设备</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="1d86c-260">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="1d86c-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="1d86c-261">文档</span><span class="sxs-lookup"><span data-stu-id="1d86c-261">Documents</span></span> </li>
<li> <span data-ttu-id="1d86c-262">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="1d86c-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="1d86c-263">用户级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="1d86c-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="1d86c-264">组级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="1d86c-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="1d86c-265">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="1d86c-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="1d86c-266">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="1d86c-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="1d86c-267">创建日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-267">Created date</span></span> </li>
<li> <span data-ttu-id="1d86c-268">修改日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-268">Modified date</span></span> </li>
<li> <span data-ttu-id="1d86c-269">创建者</span><span class="sxs-lookup"><span data-stu-id="1d86c-269">Created by</span></span> </li>
<li> <span data-ttu-id="1d86c-270">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="1d86c-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="1d86c-271">\*必须配置目录同步。</span><span class="sxs-lookup"><span data-stu-id="1d86c-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="1d86c-272">只迁移对 Windows 文件资源管理器公开的 NTFS 权限。</span><span class="sxs-lookup"><span data-stu-id="1d86c-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="1d86c-273">不会迁移文件共享设备上直接托管的权限。</span><span class="sxs-lookup"><span data-stu-id="1d86c-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="1d86c-274">如果数据存储在 SMB 2.0 设备上，只会迁移 SMB 协议公开的与 NTFS 等同的权限。</span><span class="sxs-lookup"><span data-stu-id="1d86c-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="1d86c-275">所有权历史记录和旧版本</span><span class="sxs-lookup"><span data-stu-id="1d86c-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="1d86c-276">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="1d86c-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="1d86c-277">旧版本</span><span class="sxs-lookup"><span data-stu-id="1d86c-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="1d86c-278">Windows 文件和文件夹属性（如只读和隐藏）</span><span class="sxs-lookup"><span data-stu-id="1d86c-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="1d86c-279">非 Windows 新技术文件系统 (NTFS) 和 NTFS 高级权限和特殊设置：</span><span class="sxs-lookup"><span data-stu-id="1d86c-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="1d86c-280">显式拒绝权限（在迁移后删除的权限、从属于并行权限的内容或父文件夹上的权限）</span><span class="sxs-lookup"><span data-stu-id="1d86c-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="1d86c-281">NTFS 审核配置</span><span class="sxs-lookup"><span data-stu-id="1d86c-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="1d86c-282">文件分类基础结构 (FCI) 提供的附加文件元数据</span><span class="sxs-lookup"><span data-stu-id="1d86c-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="1d86c-283">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="1d86c-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="1d86c-284">隐藏的共享</span><span class="sxs-lookup"><span data-stu-id="1d86c-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="1d86c-285">共享（如在共享级别授予的权限）</span><span class="sxs-lookup"><span data-stu-id="1d86c-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="1d86c-286">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="1d86c-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="1d86c-287"><strong>单个 G 套件环境（仅限 Google 云端硬盘）</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="1d86c-288">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="1d86c-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="1d86c-289">Google 文档、工作表和幻灯片（文件转换为等同的 Office 格式），包括超过10 MB的</span><span class="sxs-lookup"><span data-stu-id="1d86c-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="1d86c-290">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="1d86c-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="1d86c-291">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-292">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-293">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="1d86c-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="1d86c-294">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="1d86c-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="1d86c-295">创建日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-295">Created date</span></span> </li>
<li> <span data-ttu-id="1d86c-296">修改日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-296">Modified date</span></span> </li>
<li> <span data-ttu-id="1d86c-297">创建者</span><span class="sxs-lookup"><span data-stu-id="1d86c-297">Created by</span></span> </li>
<li> <span data-ttu-id="1d86c-298">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="1d86c-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="1d86c-299">共享驱动器 （文件夹和文件）</span><span class="sxs-lookup"><span data-stu-id="1d86c-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="1d86c-300">属于 Google 云端硬盘帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="1d86c-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="1d86c-301">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="1d86c-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="1d86c-302">文件和文件夹说明、文件夹颜色</span><span class="sxs-lookup"><span data-stu-id="1d86c-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="1d86c-303">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-304">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-305">高级元数据</span><span class="sxs-lookup"><span data-stu-id="1d86c-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="1d86c-306">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="1d86c-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="1d86c-307">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="1d86c-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="1d86c-308">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="1d86c-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="1d86c-309">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="1d86c-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="1d86c-310">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="1d86c-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="1d86c-311">Google 相册、Forms、地图和其他已连接应用</span><span class="sxs-lookup"><span data-stu-id="1d86c-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="1d86c-312">Google 绘图</span><span class="sxs-lookup"><span data-stu-id="1d86c-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="1d86c-313">组织外部的共享内容</span><span class="sxs-lookup"><span data-stu-id="1d86c-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="1d86c-314">不属于Google 云端硬盘帐户的内容被迁移</span><span class="sxs-lookup"><span data-stu-id="1d86c-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="1d86c-315">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Google 云端硬盘管理报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="1d86c-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="1d86c-316">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="1d86c-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="1d86c-317">共享驱动器成员资格权限（<strong>注意</strong>：使用 Google 云端硬盘管理报告来标识共享驱动器成员资格。</span><span class="sxs-lookup"><span data-stu-id="1d86c-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="1d86c-318">指示最终用户迁移前在目标上配置这些成员资格设置。）</span><span class="sxs-lookup"><span data-stu-id="1d86c-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="1d86c-319">标记为 "受限" 或 "未 copyable" 的文件</span><span class="sxs-lookup"><span data-stu-id="1d86c-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="1d86c-320">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="1d86c-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="1d86c-321"><strong>Box（Starter、Business、Enterprise）</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="1d86c-322">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="1d86c-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="1d86c-323">文档</span><span class="sxs-lookup"><span data-stu-id="1d86c-323">Documents</span></span> </li>
<li> <span data-ttu-id="1d86c-324">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="1d86c-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="1d86c-325">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-326">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-327">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="1d86c-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="1d86c-328">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="1d86c-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="1d86c-329">创建日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-329">Created date</span></span> </li>
<li> <span data-ttu-id="1d86c-330">修改日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-330">Modified date</span></span> </li>
<li> <span data-ttu-id="1d86c-331">创建者</span><span class="sxs-lookup"><span data-stu-id="1d86c-331">Created by</span></span> </li>
<li> <span data-ttu-id="1d86c-332">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="1d86c-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="1d86c-333">属于 Box 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="1d86c-333">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="1d86c-334">方框备注 (转换为 Word 文档格式) </span><span class="sxs-lookup"><span data-stu-id="1d86c-334">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="1d86c-335">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="1d86c-335">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="1d86c-336">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="1d86c-336">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="1d86c-337">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-337">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-338">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-338">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-339">Box 标记和高级元数据</span><span class="sxs-lookup"><span data-stu-id="1d86c-339">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="1d86c-340">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="1d86c-340">File lock attributes</span></span> </li>
<li> <span data-ttu-id="1d86c-341">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="1d86c-341">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="1d86c-342">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="1d86c-342">Trashed items</span></span> </li>
<li> <span data-ttu-id="1d86c-343">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="1d86c-343">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="1d86c-344">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="1d86c-344">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="1d86c-345">Box 应用、书签、收藏夹和工作流</span><span class="sxs-lookup"><span data-stu-id="1d86c-345">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="1d86c-346">不属于已迁移 Box 帐户的内容</span><span class="sxs-lookup"><span data-stu-id="1d86c-346">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="1d86c-347">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Box 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="1d86c-347">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="1d86c-348">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="1d86c-348">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="1d86c-349">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="1d86c-349">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="1d86c-350"><strong>用于 Teams的 Dropbox（标准版和高级版）</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-350"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="1d86c-351">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="1d86c-351">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="1d86c-352">文档</span><span class="sxs-lookup"><span data-stu-id="1d86c-352">Documents</span></span> </li>
<li> <span data-ttu-id="1d86c-353">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="1d86c-353">File and folder structure</span></span> </li>
<li> <span data-ttu-id="1d86c-354">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-354">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-355">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-355">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-356">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="1d86c-356">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="1d86c-357">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="1d86c-357">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="1d86c-358">创建日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-358">Created date</span></span> </li>
<li> <span data-ttu-id="1d86c-359">修改日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-359">Modified date</span></span> </li>
<li> <span data-ttu-id="1d86c-360">创建者</span><span class="sxs-lookup"><span data-stu-id="1d86c-360">Created by</span></span> </li>
<li> <span data-ttu-id="1d86c-361">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="1d86c-361">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="1d86c-362">共享团队文件夹和内容</span><span class="sxs-lookup"><span data-stu-id="1d86c-362">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="1d86c-363">属于 Dropbox 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="1d86c-363">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="1d86c-364">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="1d86c-364">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="1d86c-365">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="1d86c-365">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="1d86c-366">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-366">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-367">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-367">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-368">高级元数据</span><span class="sxs-lookup"><span data-stu-id="1d86c-368">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="1d86c-369">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="1d86c-369">File lock attributes</span></span> </li>
<li> <span data-ttu-id="1d86c-370">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="1d86c-370">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="1d86c-371">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="1d86c-371">Trashed items</span></span> </li>
<li> <span data-ttu-id="1d86c-372">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="1d86c-372">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="1d86c-373">已卸载的 Dropbox 文件夹</span><span class="sxs-lookup"><span data-stu-id="1d86c-373">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="1d86c-374">已删除或已断开连接的用户</span><span class="sxs-lookup"><span data-stu-id="1d86c-374">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="1d86c-375">Dropbox Paper 文件、Dropbox Showcase 和 Dropbox Space</span><span class="sxs-lookup"><span data-stu-id="1d86c-375">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="1d86c-376">Dropbox 应用及收藏夹（已固定或加星标）</span><span class="sxs-lookup"><span data-stu-id="1d86c-376">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="1d86c-377">已迁移的 Dropbox 帐户不拥有的内容</span><span class="sxs-lookup"><span data-stu-id="1d86c-377">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="1d86c-378">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Dropbox 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="1d86c-378">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="1d86c-379">指示最终用户在迁移后与外部用户重新共享内容）</span><span class="sxs-lookup"><span data-stu-id="1d86c-379">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="1d86c-380">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="1d86c-380">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="1d86c-381">FastTrack 责任</span><span class="sxs-lookup"><span data-stu-id="1d86c-381">FastTrack responsibilities</span></span>

<span data-ttu-id="1d86c-382">我们的 FastTrack 专家在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="1d86c-382">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="1d86c-383">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息</span><span class="sxs-lookup"><span data-stu-id="1d86c-383">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="1d86c-384">你的责任</span><span class="sxs-lookup"><span data-stu-id="1d86c-384">Your responsibilities</span></span>

<span data-ttu-id="1d86c-385">你在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="1d86c-385">You perform standard activities during the migration project.</span></span> <span data-ttu-id="1d86c-386">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息</span><span class="sxs-lookup"><span data-stu-id="1d86c-386">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="1d86c-387">此外，你还将执行以下特定于 SharePoint Online 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="1d86c-387">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="1d86c-388">预置将作为迁移事件目标的所有 SharePoint 团队网站。</span><span class="sxs-lookup"><span data-stu-id="1d86c-388">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="1d86c-389">到 OneDrive for Business 的迁移</span><span class="sxs-lookup"><span data-stu-id="1d86c-389">Migration to OneDrive for Business</span></span>

<span data-ttu-id="1d86c-390">当你选择使用 FastTrack 将文件迁移到 OneDrive for Business 时，我们将提供迁移指南和数据迁移服务。</span><span class="sxs-lookup"><span data-stu-id="1d86c-390">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="1d86c-391">我们提供指导，以帮助你计划迁移、配置源环境和 OneDrive for Business，并利用我们的数据迁移服务来迁移文件。</span><span class="sxs-lookup"><span data-stu-id="1d86c-391">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="1d86c-392">你可以创建和安排迁移事件。</span><span class="sxs-lookup"><span data-stu-id="1d86c-392">You create and schedule your migration events.</span></span> <span data-ttu-id="1d86c-393">我们将根据你的日程安排启动迁移事件、监视其进度并提供状态报告。</span><span class="sxs-lookup"><span data-stu-id="1d86c-393">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="1d86c-394">迁移事件完成后，可以预期源环境中经过适当计划且符合资格的源中的的文件已迁移到 OneDrive for Business。</span><span class="sxs-lookup"><span data-stu-id="1d86c-394">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="1d86c-395">注意事项</span><span class="sxs-lookup"><span data-stu-id="1d86c-395">Considerations</span></span>

  - <span data-ttu-id="1d86c-396">所有迁移均受 OneDrive for business 配额限制。</span><span class="sxs-lookup"><span data-stu-id="1d86c-396">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="1d86c-397">有关详细信息，请参阅 [<span class="underline">SharePoint Online 和 OneDrive for Business 的软件边界与限制</span>](https://go.microsoft.com/fwlink/?LinkId=698855)。</span><span class="sxs-lookup"><span data-stu-id="1d86c-397">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="1d86c-398">建议将迁移数据总量限制在你享有的整体 SharePoint Online 存储配额（包括你可能单独购买的其他存储）的 75% 以内。</span><span class="sxs-lookup"><span data-stu-id="1d86c-398">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="1d86c-399">FastTrack 仅迁移到活动的 OneDrive for Business 驱动器。</span><span class="sxs-lookup"><span data-stu-id="1d86c-399">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="1d86c-400">源环境详细信息</span><span class="sxs-lookup"><span data-stu-id="1d86c-400">Source environment details</span></span>

<span data-ttu-id="1d86c-401">我们的数据迁移服务从以下源环境迁移数据：</span><span class="sxs-lookup"><span data-stu-id="1d86c-401">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="1d86c-402">文件共享（SMB 文件在支持 SMB 2.0 前向的设备上共享）。</span><span class="sxs-lookup"><span data-stu-id="1d86c-402">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="1d86c-403">单个 G 套件环境（仅限 Google 云端硬盘）。</span><span class="sxs-lookup"><span data-stu-id="1d86c-403">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="1d86c-404">Box（Starter、Business、Enterprise）。</span><span class="sxs-lookup"><span data-stu-id="1d86c-404">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="1d86c-405">用于 Teams的 Dropbox（标准版和高级版）</span><span class="sxs-lookup"><span data-stu-id="1d86c-405">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="1d86c-406">下表显示了特定于每个源环境的迁移详细信息：</span><span class="sxs-lookup"><span data-stu-id="1d86c-406">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="1d86c-407"><strong>源环境</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-407"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="1d86c-408"><strong>迁移类型</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-408"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="1d86c-409"><strong>迁移内容</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-409"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="1d86c-410"><strong>不迁移的内容</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-410"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="1d86c-411"><strong>任何支持 SMB 2.0 及更高版本的文件共享设备</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-411"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="1d86c-412">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="1d86c-412">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="1d86c-413">文档</span><span class="sxs-lookup"><span data-stu-id="1d86c-413">Documents</span></span> </li>
<li> <span data-ttu-id="1d86c-414">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="1d86c-414">File and folder structure</span></span> </li>
<li> <span data-ttu-id="1d86c-415">用户级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="1d86c-415">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="1d86c-416">组级别的文件和文件夹权限\*</span><span class="sxs-lookup"><span data-stu-id="1d86c-416">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="1d86c-417">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="1d86c-417">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="1d86c-418">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="1d86c-418">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="1d86c-419">创建日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-419">Created date</span></span> </li>
<li> <span data-ttu-id="1d86c-420">修改日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-420">Modified date</span></span> </li>
<li> <span data-ttu-id="1d86c-421">创建者</span><span class="sxs-lookup"><span data-stu-id="1d86c-421">Created by</span></span> </li>
<li> <span data-ttu-id="1d86c-422">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="1d86c-422">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="1d86c-423">\*必须配置目录同步。</span><span class="sxs-lookup"><span data-stu-id="1d86c-423">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="1d86c-424">只迁移对 Windows 文件资源管理器公开的 NTFS 权限。</span><span class="sxs-lookup"><span data-stu-id="1d86c-424">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="1d86c-425">不会迁移文件共享设备上直接托管的权限。</span><span class="sxs-lookup"><span data-stu-id="1d86c-425">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="1d86c-426">如果数据存储在 SMB 2.0 设备上，只会迁移 SMB 协议公开的与 NTFS 等同的权限。</span><span class="sxs-lookup"><span data-stu-id="1d86c-426">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="1d86c-427">所有权历史记录和旧版本</span><span class="sxs-lookup"><span data-stu-id="1d86c-427">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="1d86c-428">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="1d86c-428">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="1d86c-429">旧版本</span><span class="sxs-lookup"><span data-stu-id="1d86c-429">Previous versions</span></span> </li>
<li> <span data-ttu-id="1d86c-430">Windows 文件和文件夹属性（如只读和隐藏）</span><span class="sxs-lookup"><span data-stu-id="1d86c-430">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="1d86c-431">非 Windows 新技术文件系统 (NTFS) 和 NTFS 高级权限和特殊设置：</span><span class="sxs-lookup"><span data-stu-id="1d86c-431">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="1d86c-432">显式拒绝权限（在迁移后删除的权限、从属于并行权限的内容或父文件夹上的权限）</span><span class="sxs-lookup"><span data-stu-id="1d86c-432">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="1d86c-433">NTFS 审核配置</span><span class="sxs-lookup"><span data-stu-id="1d86c-433">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="1d86c-434">文件分类基础结构 (FCI) 提供的附加文件元数据</span><span class="sxs-lookup"><span data-stu-id="1d86c-434">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="1d86c-435">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="1d86c-435">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="1d86c-436">隐藏的共享</span><span class="sxs-lookup"><span data-stu-id="1d86c-436">Hidden shares</span></span> </li>
<li> <span data-ttu-id="1d86c-437">共享（如在共享级别授予的权限）</span><span class="sxs-lookup"><span data-stu-id="1d86c-437">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="1d86c-438">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="1d86c-438">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="1d86c-439"><strong>单个 G 套件环境（仅限 Google 云端硬盘）</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-439"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="1d86c-440">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="1d86c-440">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="1d86c-441">Google 文档、工作表和幻灯片（文件包括超过10 MB的，转换为等同的 Office 格式）</span><span class="sxs-lookup"><span data-stu-id="1d86c-441">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="1d86c-442">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="1d86c-442">File and folder structure</span></span> </li>
<li> <span data-ttu-id="1d86c-443">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-443">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-444">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-444">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-445">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="1d86c-445">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="1d86c-446">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="1d86c-446">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="1d86c-447">创建日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-447">Created date</span></span> </li>
<li> <span data-ttu-id="1d86c-448">修改日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-448">Modified date</span></span> </li>
<li> <span data-ttu-id="1d86c-449">创建者</span><span class="sxs-lookup"><span data-stu-id="1d86c-449">Created by</span></span> </li>
<li> <span data-ttu-id="1d86c-450">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="1d86c-450">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="1d86c-451">共享驱动器 （文件夹和文件）</span><span class="sxs-lookup"><span data-stu-id="1d86c-451">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="1d86c-452">属于 Google 云端硬盘帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="1d86c-452">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="1d86c-453">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="1d86c-453">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="1d86c-454">文件和文件夹说明、文件夹颜色</span><span class="sxs-lookup"><span data-stu-id="1d86c-454">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="1d86c-455">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-455">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-456">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-456">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-457">高级元数据</span><span class="sxs-lookup"><span data-stu-id="1d86c-457">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="1d86c-458">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="1d86c-458">File lock attributes</span></span> </li>
<li> <span data-ttu-id="1d86c-459">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="1d86c-459">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="1d86c-460">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="1d86c-460">Trashed items</span></span> </li>
<li> <span data-ttu-id="1d86c-461">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="1d86c-461">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="1d86c-462">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="1d86c-462">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="1d86c-463">Google 相册、Forms、地图和其他已连接应用</span><span class="sxs-lookup"><span data-stu-id="1d86c-463">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="1d86c-464">Google 绘图</span><span class="sxs-lookup"><span data-stu-id="1d86c-464">Google Drawings</span></span> </li>
<li> <span data-ttu-id="1d86c-465">组织外部的共享内容</span><span class="sxs-lookup"><span data-stu-id="1d86c-465">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="1d86c-466">不属于Google 云端硬盘帐户的内容被迁移</span><span class="sxs-lookup"><span data-stu-id="1d86c-466">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="1d86c-467">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Google 云端硬盘管理报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="1d86c-467">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="1d86c-468">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="1d86c-468">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="1d86c-469">共享驱动器成员资格权限（<strong>注意</strong>：使用 Google 云端硬盘管理报告来标识共享驱动器成员资格。</span><span class="sxs-lookup"><span data-stu-id="1d86c-469">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="1d86c-470">指示最终用户迁移前在目标上配置这些成员资格设置。）</span><span class="sxs-lookup"><span data-stu-id="1d86c-470">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="1d86c-471">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="1d86c-471">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="1d86c-472"><strong>Box（Starter、Business、Enterprise）</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-472"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="1d86c-473">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="1d86c-473">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="1d86c-474">文档</span><span class="sxs-lookup"><span data-stu-id="1d86c-474">Documents</span></span> </li>
<li> <span data-ttu-id="1d86c-475">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="1d86c-475">File and folder structure</span></span> </li>
<li> <span data-ttu-id="1d86c-476">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-476">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-477">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-477">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-478">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="1d86c-478">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="1d86c-479">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="1d86c-479">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="1d86c-480">创建日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-480">Created date</span></span> </li>
<li> <span data-ttu-id="1d86c-481">修改日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-481">Modified date</span></span> </li>
<li> <span data-ttu-id="1d86c-482">创建者</span><span class="sxs-lookup"><span data-stu-id="1d86c-482">Created by</span></span> </li>
<li> <span data-ttu-id="1d86c-483">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="1d86c-483">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="1d86c-484">属于 Box 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="1d86c-484">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="1d86c-485">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="1d86c-485">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="1d86c-486">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="1d86c-486">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="1d86c-487">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-487">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-488">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-488">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-489">Box 标记和高级元数据</span><span class="sxs-lookup"><span data-stu-id="1d86c-489">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="1d86c-490">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="1d86c-490">File lock attributes</span></span> </li>
<li> <span data-ttu-id="1d86c-491">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="1d86c-491">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="1d86c-492">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="1d86c-492">Trashed items</span></span> </li>
<li> <span data-ttu-id="1d86c-493">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="1d86c-493">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="1d86c-494">被阻止的用户或非活动用户</span><span class="sxs-lookup"><span data-stu-id="1d86c-494">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="1d86c-495">Box 应用、书签、收藏夹和工作流</span><span class="sxs-lookup"><span data-stu-id="1d86c-495">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="1d86c-496">不属于已迁移 Box 帐户的内容</span><span class="sxs-lookup"><span data-stu-id="1d86c-496">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="1d86c-497">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Box 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="1d86c-497">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="1d86c-498">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="1d86c-498">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="1d86c-499">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="1d86c-499">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="1d86c-500"><strong>用于 Teams的 Dropbox（标准版和高级版）</strong></span><span class="sxs-lookup"><span data-stu-id="1d86c-500"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="1d86c-501">单通道或多通道</span><span class="sxs-lookup"><span data-stu-id="1d86c-501">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="1d86c-502">文档</span><span class="sxs-lookup"><span data-stu-id="1d86c-502">Documents</span></span> </li>
<li> <span data-ttu-id="1d86c-503">文件和文件夹结构</span><span class="sxs-lookup"><span data-stu-id="1d86c-503">File and folder structure</span></span> </li>
<li> <span data-ttu-id="1d86c-504">用户级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-504">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-505">组级别文件夹权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-505">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-506">小于 15GB 的文件</span><span class="sxs-lookup"><span data-stu-id="1d86c-506">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="1d86c-507">基本文档和文件夹元数据：</span><span class="sxs-lookup"><span data-stu-id="1d86c-507">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="1d86c-508">创建日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-508">Created date</span></span> </li>
<li> <span data-ttu-id="1d86c-509">修改日期</span><span class="sxs-lookup"><span data-stu-id="1d86c-509">Modified date</span></span> </li>
<li> <span data-ttu-id="1d86c-510">创建者</span><span class="sxs-lookup"><span data-stu-id="1d86c-510">Created by</span></span> </li>
<li> <span data-ttu-id="1d86c-511">最后一次修改者</span><span class="sxs-lookup"><span data-stu-id="1d86c-511">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="1d86c-512">共享团队文件夹和内容</span><span class="sxs-lookup"><span data-stu-id="1d86c-512">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="1d86c-513">属于 Dropbox 帐户的共享内容会被迁移</span><span class="sxs-lookup"><span data-stu-id="1d86c-513">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="1d86c-514">所有权历史记录、旧版本和注释</span><span class="sxs-lookup"><span data-stu-id="1d86c-514">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="1d86c-515">文件和文件夹说明</span><span class="sxs-lookup"><span data-stu-id="1d86c-515">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="1d86c-516">用户级别文件权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-516">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-517">组级别文件权限</span><span class="sxs-lookup"><span data-stu-id="1d86c-517">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="1d86c-518">高级元数据</span><span class="sxs-lookup"><span data-stu-id="1d86c-518">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="1d86c-519">文件锁定属性</span><span class="sxs-lookup"><span data-stu-id="1d86c-519">File lock attributes</span></span> </li>
<li> <span data-ttu-id="1d86c-520">内容中嵌入的 URL 的转换后对象</span><span class="sxs-lookup"><span data-stu-id="1d86c-520">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="1d86c-521">放入回收站的项</span><span class="sxs-lookup"><span data-stu-id="1d86c-521">Trashed items</span></span> </li>
<li> <span data-ttu-id="1d86c-522">无法访问或已损坏的文档</span><span class="sxs-lookup"><span data-stu-id="1d86c-522">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="1d86c-523">已卸载的 Dropbox 文件夹</span><span class="sxs-lookup"><span data-stu-id="1d86c-523">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="1d86c-524">已删除或已断开连接的用户</span><span class="sxs-lookup"><span data-stu-id="1d86c-524">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="1d86c-525">Dropbox Paper 文件、Dropbox Showcase 和 Dropbox Space</span><span class="sxs-lookup"><span data-stu-id="1d86c-525">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="1d86c-526">Dropbox 应用及收藏夹（已固定或加星标）</span><span class="sxs-lookup"><span data-stu-id="1d86c-526">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="1d86c-527">已迁移的 Dropbox 帐户不拥有的内容</span><span class="sxs-lookup"><span data-stu-id="1d86c-527">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="1d86c-528">外部用户的权限和基本元数据（<strong>注意</strong>：使用 Dropbox 报告确定与外部用户共享的内容。</span><span class="sxs-lookup"><span data-stu-id="1d86c-528">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="1d86c-529">指示最终用户在迁移后与外部用户重新共享内容。）</span><span class="sxs-lookup"><span data-stu-id="1d86c-529">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="1d86c-530">超出当前<a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online 限制和限制的</span>文件或文件夹</a> </span><span class="sxs-lookup"><span data-stu-id="1d86c-530">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="1d86c-531">FastTrack 责任</span><span class="sxs-lookup"><span data-stu-id="1d86c-531">FastTrack responsibilities</span></span>

<span data-ttu-id="1d86c-532">我们的 FastTrack 专家在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="1d86c-532">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="1d86c-533">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="1d86c-533">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="1d86c-534">你的责任</span><span class="sxs-lookup"><span data-stu-id="1d86c-534">Your responsibilities</span></span>

<span data-ttu-id="1d86c-535">你在迁移项目期间执行标准活动。</span><span class="sxs-lookup"><span data-stu-id="1d86c-535">You perform standard activities during the migration project.</span></span> <span data-ttu-id="1d86c-536">有关详细信息，请参阅[流程和期望](process-and-expectations.md)中的数据迁移职责信息。</span><span class="sxs-lookup"><span data-stu-id="1d86c-536">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="1d86c-537">此外，你还将执行以下特定于 OneDrive for Business 迁移的活动：</span><span class="sxs-lookup"><span data-stu-id="1d86c-537">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="1d86c-538">预置将作为迁移事件目标的所有 OneDrive for Business 网站。</span><span class="sxs-lookup"><span data-stu-id="1d86c-538">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
