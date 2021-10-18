---
title: Witivio による予定表Proアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 09/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: カレンダー Pro、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリのセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 262747068d05ac8aa5c0987c8f6838715eabdf0c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60444937"
---
# <a name="calendar-pro"></a>カレンダー Pro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 9 月 2 日</p>

* <a href="https://teams.microsoft.com/l/app/19a29a41-cbca-4152-a2af-dd9728ea35f1" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002152" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Witivio が Microsoft に提供する情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | カレンダー Pro |
| ID | WA200002152 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Witivio |
| パートナー Web サイトの URL | [https://www.witivio.com](https://www.witivio.com) |
| プライバシー ポリシーの URL | [https://www.teams-pro.com/en/privacy-policy/](https://www.teams-pro.com/en/privacy-policy/) |
| 利用規約の URL | [https://www.teams-pro.com/en/terms-of-use/](https://www.teams-pro.com/en/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Witivio によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 委任 | データが使用される | データは、UI に情報を表示するために使用されます。 | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| User.ReadBasic.All | 委任 | データが使用される | データは、ユーザー選択を有効にするためのユーザーを一覧表示するために使用されます。 | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| メール | 委任 | 電子メールが使用される | 電子メールは、UI 内のユーザーを識別するために使用されます。 | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| offline_access | 委任 | データが使用される | オフライン アクセスを使用して、SSO を有効Microsoft Teams | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| openid | 委任 | 認証 | OpenID は、ユーザーの認証に使用Microsoft Teams | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |
>| profile | 委任 | データが使用される | プロファイルは、ユーザーが SSO を有効にMicrosoft Teams | [fb507a6d-2eaa-4f1f-b43a-140f388c4445](https://docs.microsoft.com/microsoft-365-app-certification/azure/fb507a6d-2eaa-4f1f-b43a-140f388c4445) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>テレメトリには、診断用の UPN AAD ID が含まれる。 PROD/Run 管理者だけが、実稼働テレメトリにアクセスできます。 ログは 90 日間保存され、要求に応じて電子メールで削除 dpo@witivio.com

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>Witivio は、北Microsoft Azure展開されているコンポーネントのみを使用します。 アプリケーションインサイトとデータ分析とストレージCosmos DB を使用します。 Witivio は、管理者を含むすべてのユーザーに MFA を使用します。 管理者には、ユーザー アカウント (ワークステーション用) と、Azure ressources にアクセスする特権アカウントがあります。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Id 条件を処理する方法について Witivio によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | ,<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/> |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
