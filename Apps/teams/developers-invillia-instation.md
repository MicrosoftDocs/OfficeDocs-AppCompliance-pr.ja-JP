---
title: インビリア開発者によるインステーション向けアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: InStation で利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、およびCSA STARレジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 40c86e4284ed201fedf63bfe3bbd7570b61049b7
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552248"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年8月6日</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

開発者インビリアがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | InStation |
| ID | WA200001701 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Developers Invillia |
| パートナーウェブサイトのURL | [https://instation.invillia.com/](https://instation.invillia.com/) |
| プライバシーポリシーの URL | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| 利用規約の URL | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法と、アプリが収集するデータに対する組織のコントロールについて開発者 Invillia によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| OnlineMeetings.Read.All | 委任 | 店舗: id、join_url、join_web_url、およびchat_id。 アプリで会議を作成できます。 | 店舗: id、join_url、join_web_url、およびchat_id。 アプリで会議を作成できます。 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OnlineMeetings.ReadWrite.All | 委任 | 店舗: id、join_url、join_web_url、およびchat_id。 アプリで会議を作成できます。 | 店舗: id、join_url、join_web_url、およびchat_id。 アプリで会議を作成できます。 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read | 委任 | アプリが最初のステップで組織にログインすることを許可します。 | 活動と有数。 アプリがユーザーの状態をキャプチャできるようにします。 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read.All | 委任 | アプリが最初のステップで組織にログインすることを許可します。 | 活動と有数。 アプリがユーザーの状態をキャプチャできるようにします。 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read | 委任 | ストア: ID、メール、表示名、姓と画像。 アプリがユーザー データを検索できるようにします。 | ストア: ID、メール、表示名、姓と画像。 アプリがユーザー データを検索できるようにします。 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read.All | 委任 | ストア: ID、メール、表示名、姓と画像。 アプリがユーザー データを検索できるようにします。 | ストア: ID、メール、表示名、姓と画像。 アプリがユーザー データを検索できるようにします。 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| メール | 委任 | アプリは、最初のログインで管理者&#180;の基本情報をキャプチャすることができます | アプリは、最初のログインで管理者&#180;の基本情報をキャプチャすることができます | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| offline_access | 委任 | ストア: トークンと更新トークン。 アプリが MS トークンに対して更新を実行できるようにします。 | ストア: トークンと更新トークン。 アプリが MS トークンに対して更新を実行できるようにします。 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| openid | 委任 | アプリが最初のステップで組織にログインすることを許可します。 | アプリが最初のステップで組織にログインすることを許可します。 | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| profile | 委任 | アプリは、最初のログイン時に管理者&#180;の基本情報をキャプチャできます。 | アプリは、最初のログイン時に管理者&#180;の基本情報をキャプチャできます。 | 0c841985-9919-4c0a-b87d-b06b301148b3 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>アプリケーション内では、ユーザー使用状況ログのみを保存します。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>アプリケーション内では、ユーザー使用状況ログのみを保存します。 何も機密、暗号化を必要とせず、唯一の特定の管理者は、このデータへのアクセスを持っています。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

