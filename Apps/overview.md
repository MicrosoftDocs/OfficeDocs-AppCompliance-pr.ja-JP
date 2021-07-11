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
# <a name="microsoft-365-app-compliance-program"></a>Microsoft 365 アプリ コンプライアンス プログラム

Microsoft 365 アプリ コンプライアンス プログラムは、アプリのセキュリティとコンプライアンスへの 3 層構成のアプローチです。 各層は次の層に基づいて構築され、Microsoft 365 エコシステムでアプリを使用する際に、ユーザーに求められる信頼性を備えた階層化プログラムを提供します。  現在、プログラムのすべての層は任意であり、アプリ開発者の判断で完了しています。 

Microsoft のミッション ステートメント: Microsoft のお客様は、組織を動かしているアプリへの絶大な信頼感を抱いておられます。

  ![アプリのコンプライアンスに対する 3 層構成のアプローチ](media/Microsoft-App-Compliance-Overview.png) 

## <a name="publisher-verification"></a>Publisher の検証

[Publisher の検証](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)は、管理者とユーザーが、Microsoft ID プラットフォームと統合するアプリ開発者の信頼性について理解する上で役立ちます。 アプリが Publisher の検証済みとしてマークされる場合、それは Publisher が、検証プロセスを完了して、この MPN アカウントをアプリケーション登録に関連付けた Microsoft Partner Network アカウントを使用し ID を検証したことを意味します。
Publisher の検証は、次の条件を満たすアプリに適用されます。  
- OAuth 2.0 と OpenID Connect を使用してユーザーにサインインし、Microsoft Graph などのサービス側の API を使用して、データへのアクセスを要求します。 
- Azure AD にマルチ テナントとして登録されます。  

> [!IMPORTANT]
> Publisher の検証は、アプリ開発者が Publisher の構成証明または Microsoft 365 認証を開始または完了することを防止するものではありません。 アプリの検証に適用されない場合はスキップされ、構成証明を開始することができます。

## <a name="publisher-attestation"></a>Publisher の構成証明

[Publisher 構成証明](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-attestation-guide)は、開発者が、アプリ サービスに関する一般的なデータの取り扱い、セキュリティとコンプライアンスに関する情報を共有する場所です。 これにより、IT 管理者がアプリの発行元と直接作業する必要が軽減されます。 十分な情報に基づいた意思決定に必要となるすべての情報は、発行元の構成証明が完了しているすべてのアプリに対して、 1 か所に一貫した形式でまとめられています。 目標は、アプリの導入プロセスを簡単かつ迅速に行いつつ、テナントで使用するアプリが組織の基準を満たしていることを顧客に保証することです。

Publisher 構成証明は、WebApp、および次の Microsoft 製品と統合されるすべてのアプリに適用されます。
-   Teams
-   Word
-   Excel
-   PowerPoint 
-   Outlook
- SharePoint
- Project
- OneNote

> [!IMPORTANT]
> Microsoft は、提供された情報を検証しません。開発者は、構成証明ドキュメントと対応するアプリのパフォーマンス データの信ぴょう性、正確さ、整合性のみを確認します。 

## <a name="microsoft-365-certification"></a>Microsoft 365 認定
[Microsoft 365 認定](https://docs.microsoft.com/microsoft-365-app-certification/docs/enterprise-app-certification-guide)では、Microsoft Teams アプリを使用する際に、データとプライバシーが適切な方法で安全に保護されていることを組織に保証し、信頼を提供します。 認証により、アプリ ソリューションが Microsoft のテクノロジと互換性があり、クラウド アプリのセキュリティのベスト プラクティスに準拠し、Microsoft によってサポートされていることが確認されます。 このプロセスの間、アプリ開発者はサードパーティの評価者と協力して、組織のセキュリティとコンプライアンス標準を検証します。 Microsoft 365 認定では、発行元構成証明と同等のアプリに適用されます。 


