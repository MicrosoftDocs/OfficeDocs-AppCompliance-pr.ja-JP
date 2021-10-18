---
title: yasoon GmbH による Jira Connectスマート デバイスのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 07/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Smart Connect for Jira で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3c5dbcb87b2d99c727b01ff903ec9daf83935978
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430285"
---
# <a name="smart-connect-for-jira"></a>Smart Connect for Jira

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 7 月 21 日</p>

* <a href="https://teams.microsoft.com/l/app/6402de97-ce33-4386-bf28-b37e9e139c09" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002055" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

yasoon GmbH から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Smart Connect for Jira |
| ID | WA200002055 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | yasoon GmbH |
| パートナー Web サイトの URL | [https://www.yasoon.com](https://www.yasoon.com) |
| [アプリケーション情報Teamsページの URL | [https://yasoon.com/microsoft-teams-for-jira/](https://yasoon.com/microsoft-teams-for-jira/) |
| プライバシー ポリシーの URL | [https://yasoon.com/privacy-policy-services/](https://yasoon.com/privacy-policy-services/) |
| 利用規約の URL | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474846970/Product_42949680957/Asset_3f25ec80-eacb-454f-8cc2-eeee583b65c6/170825EULAOfficeaddinEN.doc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する yasoon GmbH によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | 委任 | このアクセス許可は、ユーザーが Jira でこの参加チャネルの 1 つを選択するために使用されます。 | キャッシュの目的でチャネル ID | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelMessage.Read.Group | アプリケーション | アプリが Jira でリンクされたチャネル メッセージを表示できます。 | Jira の問題にメッセージをリンクするメッセージの ID | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelMessage.Send | 委任 | データは使用されません。この API は、ユーザーが Jira からのチャネル メッセージに返信するために使用されます。 | なし | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| ChannelSettings.Read.Group | アプリケーション | チャネルに関する詳細情報を参照するために使用します。 | なし | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Chat.ReadWrite | 委任 | ユーザーがチャットに新しい返信を追加し、Jira からのチャット メッセージを表示するために使用します。 | なし | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Member.Read.Group | アプリケーション | アクセス許可のチェックに使用され、アプリはユーザーのチーム メンバーシップを検証できます。 | なし | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| Team.ReadBasic.All | 委任 | このアクセス許可は、ユーザーが Jira でこの参加チームの 1 つを選択するために使用されます。 | キャッシュ用のチームの ID | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| TeamSettings.Read.Group | アプリケーション | アプリでチーム設定を読み取り、特定の既定値を尊重できます。 | なし | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |
>| User.ReadBasic.All | 委任 | ユーザーがチャネル メッセージで @-mention する同僚を選択できます | なし | [89d5ca9f-d63b-4885-bd30-6e7433c1540c](https://docs.microsoft.com/microsoft-365-app-certification/azure/89d5ca9f-d63b-4885-bd30-6e7433c1540c) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Atlassian Jira と、おそらく弊社の請負業者の 1 つは、次の場所で見ることができます。 https://go.yasoon.com/contractors | メッセージ メタデータ (ids、タイムスタンプ)、ユーザーおよび組織のメタデータ (ユーザー ID、組織 ID)、およびユーザーの電子メール アドレス | アプリ機能のサポート (Atlassian アカウントと Office アカウントの照合など) をサポートし、問題のトラブルシューティングを迅速に行うことができます。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| ユーザーとユーザー Teams Atlassian Jira アカウントを照合する | 不要 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>ユーザー メタデータ (ID)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>厳密なデータプライバシー保証を提供するサービスのみを扱います。 

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>不要

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36422" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、yasoon GmbH によって、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | 不要 |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | 不要 |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
