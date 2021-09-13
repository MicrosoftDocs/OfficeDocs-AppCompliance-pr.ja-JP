---
title: OOO RD17 による RD17 による完全な Wiki のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: RD17 による Perfect Wiki で利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: deacceb8c77fd935e6ff7dd03fe8195042b8e259
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287803"
---
# <a name="perfect-wiki-by-rd17"></a>Perfect Wiki by RD17

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 8 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/40906836-4323-4bbe-875e-3cbb134c40a2" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001679" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

OOO RD17 から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Perfect Wiki by RD17 |
| ID | WA200001679 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | OOO RD17 |
| パートナー Web サイトの URL | [https://perfectwikiforteams.com](https://perfectwikiforteams.com) |
| [アプリケーション情報Teamsページの URL | [https://perfectwikiforteams.com](https://perfectwikiforteams.com) |
| プライバシー ポリシーの URL | [https://docs.google.com/document/d/e/2PACX-1vQHouhjK2Qof_NK...](https://docs.google.com/document/d/e/2PACX-1vQHouhjK2Qof_NKFVucpN44PO30SFZHDfxWhu-u5wlZI56UW7v3bT-WCM4zH4ZaWGzQR7lnoUpVyU1S/pub) |
| 利用規約の URL | [https://docs.google.com/document/d/e/2PACX-1vTMQNAdgN7xy6n9...](https://docs.google.com/document/d/e/2PACX-1vTMQNAdgN7xy6n9tNvhDe8Sb2AF8A9v8jfG3gJ503cXzIq1nr_Zbq5aShN0mU49fvADgKZ8a58Oha-C/pub) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する OOO RD17 によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | 委任 | ChannelId と channelName、アプリでユーザーを表示する情報を取得します | channelId と channelName を保存して、後でユーザーに表示します | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |
>| Team.ReadBasic.All | 委任 | ユーザーの teamId を取得し、チーム名を取得する | teamId と teamName を使用して、どのチーム ユーザーが属しているのか理解します。 | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |
>| User.Read | 委任 | ユーザーがログインしているユーザーを理解するために使用される userId | ハッシュされた userId、 を使用してユーザーにログインし、DB から関連データを取得する | [b9604964-9c3a-483e-abf2-1b5cba495081](https://docs.microsoft.com/microsoft-365-app-certification/azure/b9604964-9c3a-483e-abf2-1b5cba495081) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>パートナーのシステムで操作を行う場合は、役割ベースのアクセス制御を使用します。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について OOO RD17 によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
