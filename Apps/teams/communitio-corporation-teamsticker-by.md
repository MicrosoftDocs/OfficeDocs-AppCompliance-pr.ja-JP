---
title: Communitio Corporation による Communitio による TeamSticker のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 01/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Communitio による TeamSticker で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 75509ae7266f44470530418c955ba70713126783
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552258"
---
# <a name="teamsticker-by-communitio"></a>TeamSticker by Communitio

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 1 月 5 日</p>

* <a href="https://teams.microsoft.com/l/app/bceca1f0-723f-44d0-b732-b3506c0a641d" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000894" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Communitio Corporation から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | TeamSticker by Communitio |
| ID | WA200000894 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Communitio Corporation |
| パートナー Web サイトの URL | [https://www.teamsuite.biz/](https://www.teamsuite.biz/) |
| [アプリケーション情報Teamsページの URL | [https://www.teamsuite.biz/feature/](https://www.teamsuite.biz/feature/) |
| プライバシー ポリシーの URL | [https://www.teamsuite.biz/privacy/](https://www.teamsuite.biz/privacy/) |
| 利用規約の URL | [https://www.teamsuite.biz/terms/](https://www.teamsuite.biz/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、Communitio Corporation から、このアプリが組織データを収集および保存する方法、およびアプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Chat.ReadWrite | アプリケーション |  なぜなら、アプリケーションはチャットに投稿します。 | アプリケーションはデータを保存しない。 | bceca1f0-723f-44d0-b732-b3506c0a641d |
>| Group.ReadWrite.All | 両方とも | アプリケーションは、グループ ID とグループ名を収集します。 | アプリケーションは、グループ ID と名前のペアを格納します。 | bceca1f0-723f-44d0-b732-b3506c0a641d |
>| User.Read | 委任 | アプリケーションは、ユーザーのプロファイル イメージを収集します。 | アプリケーションは、ユーザーのプロファイル イメージを保存して、ユーザー アイコンを表示します。 | bceca1f0-723f-44d0-b732-b3506c0a641d |
>| User.Read.All | 両方とも | アプリケーションは、ユーザーの objectId/email/name を収集して、カードを送信するユーザーを検索します。 | この場合、アプリケーションはデータを格納しない。 | bceca1f0-723f-44d0-b732-b3506c0a641d |
>| offline_access | 委任 | アプリケーションは、バックグラウンドで User.Read/ User.Read.All を使用するためにユーザーの API トークンを収集します。 | アプリケーションは、User.Read / User.Read.All をバックグラウンドで使用するためにユーザーの API トークンを格納します。 | bceca1f0-723f-44d0-b732-b3506c0a641d |
>| openid | 委任 | 収集されたデータはありません。 | アプリケーションでは、このアクセス許可を使用して openid でログインします。 | bceca1f0-723f-44d0-b732-b3506c0a641d |
>| profile | 委任 | アプリケーションは、ユーザーの objectId/email/name を収集します。 | アプリケーションには、ユーザーの objectId/email/name が格納されます。 | bceca1f0-723f-44d0-b732-b3506c0a641d |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>|  Bot Framework REST API | いいえ |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| User.Read.All のアクセス許可を持つためです。 | いいえ |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>該当なし

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36366' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36366" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、Communitio Corporation から、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | いいえ |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | いいえ |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
