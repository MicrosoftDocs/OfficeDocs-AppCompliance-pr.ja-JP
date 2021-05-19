---
title: ViimaソリューションズオイによるViimaのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: VIIMaの利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STARレジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 703c1bf3b2980fae538af764bfa1d2024a86a366
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553978"
---
# <a name="viima"></a>Viima

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年11月17日</p>

* <a href="https://teams.microsoft.com/l/app/2bffa4e8-aac7-4d2e-976d-5a7db5c4b768" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001589" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

ViimaソリューションズOyがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Viima |
| ID | WA200001589 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Viima Solutions Oy |
| パートナーウェブサイトのURL | [https://www.viima.com/](https://www.viima.com/) |
| アプリケーション情報ページTeams URL | [https://www.viima.com/product](https://www.viima.com/product) |
| プライバシーポリシーの URL | [https://www.viima.com/privacy-policy](https://www.viima.com/privacy-policy) |
| 利用規約の URL | [https://www.viima.com/terms](https://www.viima.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対する組織のコントロールについてViima Solutions Oyによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 委任 |  姓名、UPN/電子メールアドレス、場所、ロケール、部門、オフィスの場所。 これらは、ユーザーをログインし、アプリ内でユーザーの基本的なプロファイル情報を提供するために使用されます。 | ユーザーがログインできるようにし、アプリにUPNと基本的なプロファイル情報へのアクセスを提供して、サイレントログインを有効にする | b8ea7030-ce4d-4ecd-98d7-dc16d8298d1b |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>組織名、Viima 組織 ID、エンドユーザーのメール、ID がログに表示されます。 ISO27001 互換の第三者監査管理は、アクセスを制限し、そのデータのアーカイブ/削除を行いました。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>データは AWS (アイルランド) に保存されます。 データへのアクセスは、適切なトレーニングを受け、2FA、保護されたIP範囲(企業ネットワークからのアクセスのみ)などの多くのセキュリティ対策で保護されている、認定されたメンテナンスおよび技術サポートスタッフのみに限定されます。対策はISO27001に対応し、第三者によって監査されています。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/33480' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/33480" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベストプラクティス、およびその他のID基準を処理する方法についてViimaソリューションOyによって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| マイクロソフト識別プラットフォーム (Azure AD) と統合しますか。  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか。  | はい |
| アプリは認証に MSAL (マイクロソフト認証ライブラリ) を使用していますか? | いいえ |
| アプリで条件付きアクセス ポリシーがサポートされていますか。 | いいえ |
| アプリがシナリオに対して最低限の権限を要求しているか。 | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的に、または増分的に要求するアクセス許可を正確に反映していますか。 | はい |
| アプリでマルチテナント機能がサポートされていますか。 | はい |
| アプリに機密クライアントが存在しますか? | はい |
| アプリに登録されているすべてのリダイレクト統一リソース識別子 (URI) を所有していますか。 | はい |
| アプリの場合、何を使用しないようにしますか。 | - ワイルドカードリダイレクト URI<br/>- Spa に必要な場合を除き、OAuth2 暗黙的なFlow<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか。 | はい |
| クライアント アプリが適切な同意を得た場合にのみ、アクセス許可モデルで呼び出しが成功することを許可しますか。 | はい |
| アプリでプレビュー API を使用していますか。 | いいえ |
| アプリで非推奨の API が使用されていますか。 | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
