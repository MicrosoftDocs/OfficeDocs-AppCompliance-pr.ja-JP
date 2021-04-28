---
title: Publisher 構成証明とは
author: LGerrard
ms.author: legerrar
description: Publisher 構成証明プログラムの詳細
keywords: アプリ構成証明認定 365 アンケート appSource Publisher
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 44ccc49f229ac6881d6626b7e3b63f83100b8227
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/28/2021
ms.locfileid: "52071326"
---
# <a name="what-is-publisher-attestation"></a><span data-ttu-id="509fc-104">Publisher 構成証明とは</span><span class="sxs-lookup"><span data-stu-id="509fc-104">What is Publisher Attestation?</span></span>

<span data-ttu-id="509fc-105">Publisher 構成証明は、Microsoft 365 アプリ コンプライアンス プログラムの次の層です。</span><span class="sxs-lookup"><span data-stu-id="509fc-105">Publisher Attestation is the next tier in the Microsoft 365 App Compliance Program.</span></span> <span data-ttu-id="509fc-106">アプリ開発者は、ユーザーまたは IT 管理者がアプリのセキュリティとコンプライアンスを評価するときによく寄せられる質問を含む自己評価を完了する必要があります。</span><span class="sxs-lookup"><span data-stu-id="509fc-106">The app developer is asked to complete a self-assessment that includes questions frequently asked by customers or IT admins when they are evaluating the security and compliance of an app.</span></span> <span data-ttu-id="509fc-107">その後、Microsoft は、この情報を公開して、より簡単で、より時間の大きいな評価を行います。</span><span class="sxs-lookup"><span data-stu-id="509fc-107">Microsoft then publishes this information for easier and more timely evaluation.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="509fc-108">Microsoft は、提供された情報を検証しない。</span><span class="sxs-lookup"><span data-stu-id="509fc-108">Microsoft does not validate the information provided.</span></span> <span data-ttu-id="509fc-109">アプリ開発者は、公開構成証明で提供する情報に対して、一人で責任を負います。</span><span class="sxs-lookup"><span data-stu-id="509fc-109">The app developer is solely responsible for the information they provide in the publish attestation.</span></span> 

<span data-ttu-id="509fc-110">Publisher 構成証明は、次の Microsoft プラットフォームと統合するアプリに適用されます。</span><span class="sxs-lookup"><span data-stu-id="509fc-110">Publisher Attestation applies to apps that integrate with these Microsoft platforms:</span></span>
- <span data-ttu-id="509fc-111">Teams</span><span class="sxs-lookup"><span data-stu-id="509fc-111">Teams</span></span>
- <span data-ttu-id="509fc-112">Word</span><span class="sxs-lookup"><span data-stu-id="509fc-112">Word</span></span>
- <span data-ttu-id="509fc-113">Excel</span><span class="sxs-lookup"><span data-stu-id="509fc-113">Excel</span></span>
- <span data-ttu-id="509fc-114">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="509fc-114">PowerPoint</span></span> 
- <span data-ttu-id="509fc-115">Outlook</span><span class="sxs-lookup"><span data-stu-id="509fc-115">Outlook</span></span>
- <span data-ttu-id="509fc-116">SharePoint</span><span class="sxs-lookup"><span data-stu-id="509fc-116">SharePoint</span></span>
- <span data-ttu-id="509fc-117">Project</span><span class="sxs-lookup"><span data-stu-id="509fc-117">Project</span></span>
- <span data-ttu-id="509fc-118">OneNote</span><span class="sxs-lookup"><span data-stu-id="509fc-118">OneNote</span></span>

### <a name="benefits-for-it-admins"></a><span data-ttu-id="509fc-119">IT 管理者のメリット</span><span class="sxs-lookup"><span data-stu-id="509fc-119">Benefits for IT admins</span></span>
<span data-ttu-id="509fc-120">IT 管理者向け Publisher 構成証明を完了する利点は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="509fc-120">The benefits of completing the Publisher Attestation for IT admins includes:</span></span>
-   <span data-ttu-id="509fc-121">組織で有効になっているアプリケーションのセキュリティとコンプライアンス対策に対する信頼度を追加しました</span><span class="sxs-lookup"><span data-stu-id="509fc-121">Added confidence in the security and compliance measures of applications enabled in the organization</span></span>
-   <span data-ttu-id="509fc-122">アプリのセキュリティとコンプライアンスの姿勢を確認する時間の短縮</span><span class="sxs-lookup"><span data-stu-id="509fc-122">Reduced time to review an app's security and compliance posture</span></span>

### <a name="benefits-for-app-developers"></a><span data-ttu-id="509fc-123">アプリ開発者のメリット</span><span class="sxs-lookup"><span data-stu-id="509fc-123">Benefits for App Developers</span></span> 
<span data-ttu-id="509fc-124">開発者向けの Publisher 構成証明を完了する利点は次のとおりです。</span><span class="sxs-lookup"><span data-stu-id="509fc-124">The benefits of completing the Publisher Attestation for developers includes:</span></span> 
-   <span data-ttu-id="509fc-125">時間の節約。</span><span class="sxs-lookup"><span data-stu-id="509fc-125">Time savings.</span></span> <span data-ttu-id="509fc-126">よく聞く質問に関する情報については、アプリの Microsoft Docs ページを表示する</span><span class="sxs-lookup"><span data-stu-id="509fc-126">View the app's Microsoft Docs page for information to commonly asked questions</span></span>
-   <span data-ttu-id="509fc-127">企業組織のセキュリティとコンプライアンスの内部レビュータイムラインの高速化</span><span class="sxs-lookup"><span data-stu-id="509fc-127">Accelerating an enterprise organization's security and compliance internal review timeline</span></span>
-   <span data-ttu-id="509fc-128">透明度の向上</span><span class="sxs-lookup"><span data-stu-id="509fc-128">Increased transparency</span></span>
- <span data-ttu-id="509fc-129">Microsoft は追加コストでこのサービスを提供します</span><span class="sxs-lookup"><span data-stu-id="509fc-129">Microsoft provides this service at no additional cost</span></span>
-   <span data-ttu-id="509fc-130">ストア内の他のアプリとの差別化</span><span class="sxs-lookup"><span data-stu-id="509fc-130">Differentiation from other apps in the store</span></span>
-   <span data-ttu-id="509fc-131">AppSource のエントリからドキュメント ページへのリンク</span><span class="sxs-lookup"><span data-stu-id="509fc-131">Link to your docs page from your entry in AppSource</span></span>
-   <span data-ttu-id="509fc-132">Microsoft 365 認定を開始する資格</span><span class="sxs-lookup"><span data-stu-id="509fc-132">Qualification to start the Microsoft 365 Certification</span></span>


## <a name="publisher-attestation-scope"></a><span data-ttu-id="509fc-133">Publisher 構成証明スコープ</span><span class="sxs-lookup"><span data-stu-id="509fc-133">Publisher Attestation scope</span></span>

<span data-ttu-id="509fc-134">構成証明プロセスは、アプリのセキュリティ、データ処理、コンプライアンス属性を詳細に示す広範なアンケートを中心に行います。</span><span class="sxs-lookup"><span data-stu-id="509fc-134">The attestation process centers on an extensive questionnaire detailing an app's security, data handling, and compliance attributes.</span></span> <span data-ttu-id="509fc-135">提供される情報は、組織の Microsoft 365 プラットフォームでアプリがアクティブ化された場合に公開されるアプリの機能全体をカバーし、次の機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="509fc-135">The information provided covers the entire app functionality that is exposed when the app is activated in an organization's Microsoft 365 platform and includes the following:</span></span>

- <span data-ttu-id="509fc-136">データ処理: アプリが組織データを収集および保存する方法と、そのデータに対する組織の制御</span><span class="sxs-lookup"><span data-stu-id="509fc-136">Data Handling: How an app collects and stores organizational data, and what control an organization has over that data</span></span>
- <span data-ttu-id="509fc-137">セキュリティ: アプリがデータを保護し、サイバー攻撃を検出して撃退するために必要なプロトコル、プロセス、および手順</span><span class="sxs-lookup"><span data-stu-id="509fc-137">Security: The protocols, processes, and procedures that an app has to protect data and detect and repel cyber-attacks</span></span>
- <span data-ttu-id="509fc-138">コンプライアンス: 必要な業界標準と仕様へのアプリの準拠</span><span class="sxs-lookup"><span data-stu-id="509fc-138">Compliance: The app's adherence to required industry standards and specifications</span></span>
- <span data-ttu-id="509fc-139">法的: 適用される立法上の彫像と規制に対するアプリの遵守</span><span class="sxs-lookup"><span data-stu-id="509fc-139">Legal: The app's adherence to applicable legislative statues and regulations</span></span>

### <a name="confirmation-criteria"></a><span data-ttu-id="509fc-140">確認条件</span><span class="sxs-lookup"><span data-stu-id="509fc-140">Confirmation criteria</span></span>

<span data-ttu-id="509fc-141">構成証明は、Microsoft Cloud App Security によって識別される 80 を超えるリスク要因に対するアプリのセキュリティ、データ処理、コンプライアンスのプラクティス [を反映します](https://www.microsoft.com/microsoft-365/enterprise-mobility-security/cloud-app-security)。</span><span class="sxs-lookup"><span data-stu-id="509fc-141">The attestation will reflect an app's security, data handling, and compliance practices against more than 80 risk factors identified by [Microsoft Cloud App Security](https://www.microsoft.com/microsoft-365/enterprise-mobility-security/cloud-app-security).</span></span> <span data-ttu-id="509fc-142">最初の構成証明ドキュメントの提出に失敗した場合、基本的な一貫性テストの基準は、アプリケーションは承認されません。</span><span class="sxs-lookup"><span data-stu-id="509fc-142">If the initial attestation documentation submission fails basic consistency testing criteria the application will not be approved.</span></span> <span data-ttu-id="509fc-143">承認後、ドキュメント提出の誤った情報やアプリの失敗が報告または検出された場合、構成証明の確認状態は取り消されます。</span><span class="sxs-lookup"><span data-stu-id="509fc-143">Following approval, if misinformation in the documentation submission or an app failure is reported or discovered, the attestation confirmation status will be rescinded.</span></span> <span data-ttu-id="509fc-144">いずれの場合も、開発者は、修正プロセスを支援するために関連する詳細情報を受け取る。</span><span class="sxs-lookup"><span data-stu-id="509fc-144">In either instance, the developer will receive pertinent and detailed information to aid in the correction process.</span></span>

### <a name="confirmation-time-frame"></a><span data-ttu-id="509fc-145">確認の時間枠</span><span class="sxs-lookup"><span data-stu-id="509fc-145">Confirmation time frame</span></span>

<span data-ttu-id="509fc-146">構成証明は、申請時から 1 年間有効です。</span><span class="sxs-lookup"><span data-stu-id="509fc-146">The attestation is valid for one year from the time of submission.</span></span> <span data-ttu-id="509fc-147">ただし、アプリが暫定的な期間中に更新または変更された場合、開発者は構成証明を修正して再提出する必要があります。</span><span class="sxs-lookup"><span data-stu-id="509fc-147">However, if an app is updated or modified during the interim period, the developer is required to revise and resubmit the attestation</span></span>

## <a name="reviewing-an-apps-publisher-attestation"></a><span data-ttu-id="509fc-148">アプリの Publisher 構成証明の確認</span><span class="sxs-lookup"><span data-stu-id="509fc-148">Reviewing an app's Publisher Attestation</span></span>

<span data-ttu-id="509fc-149">開発者は、アプリ用に作成された Microsoft ドキュメント ページで、アプリの Publisher 構成証明の結果の詳細情報を確認できます。</span><span class="sxs-lookup"><span data-stu-id="509fc-149">The developer can review detailed information of the results of an app's Publisher Attestation on the Microsoft docs page created for their app.</span></span> <span data-ttu-id="509fc-150">Publisher の構成証明または Microsoft 365 認定を完了したアプリはすべて一覧表示され、各登録情報には、コンプライアンス プログラムで達成されたレベルが明確に示されます。</span><span class="sxs-lookup"><span data-stu-id="509fc-150">All apps that have completed either Publisher Attestation or Microsoft 365 Certification will be listed, and each listing will clearly show what level in the compliance program has been achieved.</span></span>

<span data-ttu-id="509fc-151">**Publisher 構成 [証明を](https://docs.microsoft.com/microsoft-365-app-certification/teams/iglobe-mipa-your-personal-assistant?pivots=mcas) 完了したアプリの例については、MIPA の一覧を参照してください。**</span><span class="sxs-lookup"><span data-stu-id="509fc-151">**See the [MIPA](https://docs.microsoft.com/microsoft-365-app-certification/teams/iglobe-mipa-your-personal-assistant?pivots=mcas) listing for an example of an app that has completed the Publisher Attestation.**</span></span> 

## <a name="learn-more"></a><span data-ttu-id="509fc-152">詳細情報</span><span class="sxs-lookup"><span data-stu-id="509fc-152">Learn more</span></span>

* [<span data-ttu-id="509fc-153">Microsoft 365 アプリ コンプライアンス プログラムの概要</span><span class="sxs-lookup"><span data-stu-id="509fc-153">Microsoft 365 App Compliance Program Overview</span></span>](~/overview.md)
* [<span data-ttu-id="509fc-154">Publisher Verification とは</span><span class="sxs-lookup"><span data-stu-id="509fc-154">What is Publisher Verification</span></span>](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)
* [<span data-ttu-id="509fc-155">完全な Publisher 構成証明</span><span class="sxs-lookup"><span data-stu-id="509fc-155">Complete Publisher Attestation</span></span>](~/docs/attestation.md)  
* [<span data-ttu-id="509fc-156">Microsoft 365 認定とは </span><span class="sxs-lookup"><span data-stu-id="509fc-156">What is Microsoft 365 Certification? </span></span>](~/docs/enterprise-app-certification-guide.md)
