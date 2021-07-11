---
title: Microsoft 365 アプリ コンプライアンス プログラム
author: LGerrard
ms.author: Legerrar
description: プログラムの紹介と概要
keywords: microsoft 365 m365 アプリ Publisher の構成証明書
ms.topic: overview
ms.service: attestation
localization_priority: Priority
ms.openlocfilehash: c644414281f46696ff49f3b9eb1341f02e96f0ba
ms.sourcegitcommit: 78dbace87a9b5027ea5aa23a6be9b8c613bd06ce
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/07/2021
ms.locfileid: "53315117"
---
# <a name="microsoft-365-app-compliance-program"></a><span data-ttu-id="7f922-104">Microsoft 365 アプリ コンプライアンス プログラム</span><span class="sxs-lookup"><span data-stu-id="7f922-104">Microsoft 365 App Compliance Program</span></span>

<span data-ttu-id="7f922-105">Microsoft 365 アプリ コンプライアンス プログラムは、アプリのセキュリティとコンプライアンスへの 3 層構成のアプローチです。</span><span class="sxs-lookup"><span data-stu-id="7f922-105">The Microsoft 365 App Compliance Program, is a three tier approach to app security and compliance.</span></span> <span data-ttu-id="7f922-106">各層は次の層に基づいて構築され、Microsoft 365 エコシステムでアプリを使用する際に、ユーザーに求められる信頼性を備えた階層化プログラムを提供します。 </span><span class="sxs-lookup"><span data-stu-id="7f922-106">Each tier builds upon the next – offering a layered program to give users the confidence they need while using apps in the Microsoft 365 ecosystem.</span></span> <span data-ttu-id="7f922-107">現在、プログラムのすべての層は任意であり、アプリ開発者の判断で完了しています。</span><span class="sxs-lookup"><span data-stu-id="7f922-107">Currently all tiers in the program are voluntary and are completed at the app developers discretion.</span></span> 

<span data-ttu-id="7f922-108">Microsoft のミッション ステートメント: Microsoft のお客様は、組織を動かしているアプリへの絶大な信頼感を抱いておられます。</span><span class="sxs-lookup"><span data-stu-id="7f922-108">Our mission statement: Microsoft customers have complete trust in the applications that run their organizations.</span></span>

  ![アプリのコンプライアンスに対する 3 層構成のアプローチ](media/Microsoft-App-Compliance-Overview.png) 

## <a name="publisher-verification"></a><span data-ttu-id="7f922-110">Publisher の検証</span><span class="sxs-lookup"><span data-stu-id="7f922-110">Publisher Verification</span></span>

<span data-ttu-id="7f922-111">[Publisher の検証](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)は、管理者とユーザーが、Microsoft ID プラットフォームと統合するアプリ開発者の信頼性について理解する上で役立ちます。</span><span class="sxs-lookup"><span data-stu-id="7f922-111">[Publisher Verification](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview) helps admins and users understand the authenticity of app developers integrating with the Microsoft identity platform.</span></span> <span data-ttu-id="7f922-112">アプリが Publisher の検証済みとしてマークされる場合、それは Publisher が、検証プロセスを完了して、この MPN アカウントをアプリケーション登録に関連付けた Microsoft Partner Network アカウントを使用し ID を検証したことを意味します。</span><span class="sxs-lookup"><span data-stu-id="7f922-112">When an app is marked as publisher verified, it means that the publisher has verified their identity using a Microsoft Partner Network account that has completed the verification process and has associated this MPN account with their application registration.</span></span>
<span data-ttu-id="7f922-113">Publisher の検証は、次の条件を満たすアプリに適用されます。</span><span class="sxs-lookup"><span data-stu-id="7f922-113">Publisher Verification applies to apps that meet the following conditions:</span></span>  
- <span data-ttu-id="7f922-114">OAuth 2.0 と OpenID Connect を使用してユーザーにサインインし、Microsoft Graph などのサービス側の API を使用して、データへのアクセスを要求します。</span><span class="sxs-lookup"><span data-stu-id="7f922-114">Using OAuth 2.0 and OpenID Connect to sign users in and request access to data using service-side APIs such as Microsoft Graph.</span></span> 
- <span data-ttu-id="7f922-115">Azure AD にマルチ テナントとして登録されます。</span><span class="sxs-lookup"><span data-stu-id="7f922-115">Registered in Azure AD as multi-tenant.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="7f922-116">Publisher の検証は、アプリ開発者が Publisher の構成証明または Microsoft 365 認証を開始または完了することを防止するものではありません。</span><span class="sxs-lookup"><span data-stu-id="7f922-116">Publisher Verification does not preclude an app developer from starting or completing Publisher Attestation or Microsoft 365 Certification.</span></span> <span data-ttu-id="7f922-117">アプリの検証に適用されない場合はスキップされ、構成証明を開始することができます。</span><span class="sxs-lookup"><span data-stu-id="7f922-117">If it does not apply to the app verification may be skipped and the attestation can be started.</span></span>

## <a name="publisher-attestation"></a><span data-ttu-id="7f922-118">Publisher の構成証明</span><span class="sxs-lookup"><span data-stu-id="7f922-118">Publisher Attestation</span></span>

<span data-ttu-id="7f922-119">[Publisher 構成証明](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide)は、開発者が、アプリ サービスに関する一般的なデータの取り扱い、セキュリティとコンプライアンスに関する情報を共有する場所です。</span><span class="sxs-lookup"><span data-stu-id="7f922-119">[Publisher Attestation](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide) is where developers share general, data handling, and security and compliance information about their app service.</span></span> <span data-ttu-id="7f922-120">これにより、IT 管理者がアプリの発行元と直接作業する必要が軽減されます。</span><span class="sxs-lookup"><span data-stu-id="7f922-120">This reduces the need for IT admins to work directly with app publishers.</span></span> <span data-ttu-id="7f922-121">十分な情報に基づいた意思決定に必要となるすべての情報は、発行元の構成証明が完了しているすべてのアプリに対して、 1 か所に一貫した形式でまとめられています。</span><span class="sxs-lookup"><span data-stu-id="7f922-121">All the information needed to make an informed decision can be found for all apps that have completed the publisher attestation in one place and in a consistent format.</span></span> <span data-ttu-id="7f922-122">目標は、アプリの導入プロセスを簡単かつ迅速に行いつつ、テナントで使用するアプリが組織の基準を満たしていることを顧客に保証することです。</span><span class="sxs-lookup"><span data-stu-id="7f922-122">The goal is to make it easier and speed up the process of app adoption while assuring customers that the apps they use in their tenants meets their organizational standards.</span></span>

<span data-ttu-id="7f922-123">Publisher 構成証明は、WebApp、および次の Microsoft 製品と統合されるすべてのアプリに適用されます。</span><span class="sxs-lookup"><span data-stu-id="7f922-123">Publisher Attestation applies to WebApps, and all apps that integrate with the following Microsoft products:</span></span>
-   <span data-ttu-id="7f922-124">Teams</span><span class="sxs-lookup"><span data-stu-id="7f922-124">Teams</span></span>
-   <span data-ttu-id="7f922-125">Word</span><span class="sxs-lookup"><span data-stu-id="7f922-125">Word</span></span>
-   <span data-ttu-id="7f922-126">Excel</span><span class="sxs-lookup"><span data-stu-id="7f922-126">Excel</span></span>
-   <span data-ttu-id="7f922-127">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7f922-127">PowerPoint</span></span> 
-   <span data-ttu-id="7f922-128">Outlook</span><span class="sxs-lookup"><span data-stu-id="7f922-128">Outlook</span></span>
- <span data-ttu-id="7f922-129">SharePoint</span><span class="sxs-lookup"><span data-stu-id="7f922-129">SharePoint</span></span>
- <span data-ttu-id="7f922-130">Project</span><span class="sxs-lookup"><span data-stu-id="7f922-130">Project</span></span>
- <span data-ttu-id="7f922-131">OneNote</span><span class="sxs-lookup"><span data-stu-id="7f922-131">OneNote</span></span>

> [!IMPORTANT]
> <span data-ttu-id="7f922-p105">Microsoft は、提供された情報を検証しません。開発者は、構成証明ドキュメントと対応するアプリのパフォーマンス データの信ぴょう性、正確さ、整合性のみを確認します。</span><span class="sxs-lookup"><span data-stu-id="7f922-p105">Microsoft does not validate the information provided. The developer, solely affirms the veracity, accuracy, and integrity of the attestation documentation and corresponding app performance data.</span></span> 

## <a name="microsoft-365-certification"></a><span data-ttu-id="7f922-134">Microsoft 365 認定</span><span class="sxs-lookup"><span data-stu-id="7f922-134">Microsoft 365 Certification</span></span>
<span data-ttu-id="7f922-135">[Microsoft 365 認定](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide)では、Microsoft Teams アプリを使用する際に、データとプライバシーが適切な方法で安全に保護されていることを組織に保証し、信頼を提供します。</span><span class="sxs-lookup"><span data-stu-id="7f922-135">The [Microsoft 365 Certification](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide) offers assurance and confidence to organizations that data and privacy are adequately secured and protected when using Microsoft Teams apps.</span></span> <span data-ttu-id="7f922-136">認証により、アプリ ソリューションが Microsoft のテクノロジと互換性があり、クラウド アプリのセキュリティのベスト プラクティスに準拠し、Microsoft によってサポートされていることが確認されます。</span><span class="sxs-lookup"><span data-stu-id="7f922-136">Certification confirms that an app solution is compatible with Microsoft technologies, compliant with cloud app security best practices, and supported by Microsoft.</span></span><span data-ttu-id="7f922-137"> このプロセスの間、アプリ開発者はサードパーティの評価者と協力して、組織のセキュリティとコンプライアンス標準を検証します。</span><span class="sxs-lookup"><span data-stu-id="7f922-137"> During this process, app developers work with a third-party assessor to validate organizational security and compliance standards.</span></span> <span data-ttu-id="7f922-138">Microsoft 365 認定では、発行元構成証明と同等のアプリに適用されます。</span><span class="sxs-lookup"><span data-stu-id="7f922-138">Microsoft 365 Certification applies to the same apps that qualify for the Publisher Attestation.</span></span> 


