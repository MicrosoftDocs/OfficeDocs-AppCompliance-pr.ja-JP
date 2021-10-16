---
title: 野心による野心のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 野望に関して利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 41a69c23e64a1059d99c18511837cb166bcf27a0
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410471"
---
# <a name="ambition"></a>Ambition

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 8 月 17 日</p>

* <a href="https://teams.microsoft.com/l/app/250ef61a-9fa3-434b-ae2a-0ecbe3f8116b" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003159" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

マイクロソフトに対する野心によって提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Ambition |
| ID | WA200003159 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Ambition |
| パートナー Web サイトの URL | [https://ambition.com](https://ambition.com) |
| [アプリケーション情報Teamsページの URL | [https://ambition.com](https://ambition.com) |
| プライバシー ポリシーの URL | [https://ambition.com/privacy/](https://ambition.com/privacy/) |
| 利用規約の URL | [https://ambition.com/pages/terms/](https://ambition.com/pages/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する、野心によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | 委任 | チャネルへの野心通知の送信 | チャネル ID &amp; 名。 | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| Group.Read.All | 委任 | チーム内の特定のチャネルに対する野心ワークフロー通知をセットアップします。 | チームの名前 &amp; ID。 | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| User.Read | 委任 | 野望アプリを承認した管理者を特定するには | ユーザー名 &amp; 電子メール、野望ユーザーと同期する | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| User.ReadBasic.All | 委任 | ユーザーの名前の &amp; 電子メールを使用して、ユーザーを野望アカウントと同期します。 | ユーザーの名前の &amp; 電子メールが格納されます。 | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| offline_access | 委任 | ユーザーがオフラインMicrosoft Teamsデータを同期するには。 | OAuth Access トークン更新 &amp; トークンが格納されます。 | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |
>| openid | 委任 | これは、Microsoft のサインイン機能を使用するために必要です。 | 該当なし | [24a9cf21-407c-41f9-8cc6-e7015f4e02af](https://docs.microsoft.com/microsoft-365-app-certification/azure/24a9cf21-407c-41f9-8cc6-e7015f4e02af) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| https://ambition.com/pages/subprocessors/ | 従業員名、名、電子メール アドレス | 表示/検索/フィルターの目的 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 表示の目的。  | メール &amp; の名前を指定します。 | Microsoft Users をその野望アカウントにリンクするには。 |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>https://ambition.com/privacy/

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>知る必要があるアクセス許可。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity 条件を処理する方法について、野望によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | 不要 |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

