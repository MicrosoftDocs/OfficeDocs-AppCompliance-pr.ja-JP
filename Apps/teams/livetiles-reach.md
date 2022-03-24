---
title: LiveTiles によるリーチのアプリケーション情報
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Reach で利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: c58462500079df7f7b8b2736eec9289443df4a4c
ms.sourcegitcommit: 9199fd569c5e7c5dd338abd87428c94798a22352
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/23/2022
ms.locfileid: "63753743"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 3 月 22 日</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

LiveTiles から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Reach |
| ID | WA200002045 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | LiveTiles |
| パートナー Web サイトの URL | [https://livetilesglobal.com](https://livetilesglobal.com) |
| アプリケーション情報Teamsページの URL | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| プライバシー ポリシーの URL | [https://livetilesglobal.com/privacy-policy/](https://livetilesglobal.com/privacy-policy/) |
| 利用規約の URL | [https://livetilesglobal.com/eula/](https://livetilesglobal.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する LiveTiles によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph を使用したデータ アクセス

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | アプリケーション | none | none | [a7c1920d-3ac0-42db-9757-078a2b321fd8 ](../azure/a7c1920d-3ac0-42db-9757-078a2b321fd8.md ) |
>| User.Read | 委任 | ユーザーの DisplayName、ユーザーの電子メール アドレス、UPN。 ユーザーがアプリにサインインし、サインインしているユーザーの基本情報 (表示名など) を取得するために必要です。 電子メール アドレスは、電子メール通知の送信に使用されます。  | ユーザーの DisplayName、ユーザーの電子メール アドレス、UPN。 ユーザーがアプリにサインインし、サインインしているユーザーの基本情報 (表示名など) を取得するために必要です。 電子メール アドレスは、電子メール通知の送信に使用されます。  | [d492530a-8cff-481c-90da-9c3c3f1be7da](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md) |
>| User.ReadBasic.All | 委任 | User DisplayName, User Email Address, UPN, User Department, User Job Title, User Mobile 電話 Number, User Business 電話 Number, User Office Location. ユーザーがアプリ (Phonebook) 内で他のユーザーを検索し、他のユーザーの基本的なプロファイルと連絡先情報を表示するために必要です。  | none | [d492530a-8cff-481c-90da-9c3c3f1be7da](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md) |
>| Directory.Read.All | アプリケーション | グループ メンバーシップ、ディレクトリADグループ。 ユーザーのグループ メンバーシップは、キャッシュに格納され、Microsoft の api への呼び出しGraphされます。 ユーザーが Active Directory グループを検索するには必須です。 さらに、このアクセス許可は、アプリケーションがバックエンドの web ジョブADのグループ メンバーシップを解決するために必要です。 | ユーザーのグループ メンバーシップ。 ユーザーのグループ メンバーシップは、キャッシュに格納され、Microsoft の api への呼び出しGraphされます。 ユーザーが Active Directory グループを検索するには必須です。 さらに、このアクセス許可は、アプリケーションがバックエンドの web ジョブADのグループ メンバーシップを解決するために必要です。  | [d492530a-8cff-481c-90da-9c3c3f1be7da ](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md ) |
>| User.Read.All | アプリケーション | ユーザー プロファイルから取得されるデータは、アプリ内で指定された対象ユーザーターゲット機能の構成によって異なります。 サインインしているユーザーなしでユーザー プロファイルを読み取るアプリを許可するために必要です。 プロファイル データの読み取りは、特定のプロファイル プロパティ値に基づいて特定のユーザーに情報を表示するために、アプリケーション内の情報ターゲット機能に必要です。  | none | [d492530a-8cff-481c-90da-9c3c3f1be7da ](../azure/d492530a-8cff-481c-90da-9c3c3f1be7da.md ) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **すべての非Microsoft サービス OII がに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| SendGrid, OneSignal | 電子メール アドレス、表示名 | 電子メールとモバイル プッシュ通知を介してユーザーに通知を送信する |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>電子メール アドレス、UPN。 max. 60 日の保持期間(削除後)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>管理者は問い合わせのサポートに問い合わせできます

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>不要

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

次[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報を示します。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity 条件を処理する方法について LiveTiles によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | 不要 |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | 多要素認証、ユーザーの場所と IP 範囲の制限 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | 不要 |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow、SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | はい |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
