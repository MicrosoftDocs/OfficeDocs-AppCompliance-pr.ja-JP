---
title: エキスパートシステムIVR(アジア)Co.Ltd によるecBookingの申込情報
ms.author: elmalova
author: elenamalova
ms.date: 12/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: ECBooking、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STARレジストリ内のセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1cdd05e4acfb1c7720af1a2e22b2c6d29425ca60
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552178"
---
# <a name="ecbooking"></a>ecBooking

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年12月28日</p>

* <a href="https://teams.microsoft.com/l/app/fe9627db-f23e-42b1-b454-d4d1ca5af33e" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002096" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

エキスパートシステムズIVR(アジア)Co.Ltd 提供の情報マイクロソフトに:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | ecBooking |
| ID | WA200002096 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Expert Systems IVR(Asia) Co.Ltd. |
| パートナーウェブサイトのURL | [https://www.esi-asia.com/](https://www.esi-asia.com/) |
| アプリケーション情報ページTeams URL | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/) |
| プライバシーポリシーの URL | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1510822239639-efecac03-d43200b0-aa88) |
| 利用規約の URL | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1598241760681-29d114e0-5c2b) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報はエキスパートシステムIVR(アジア)Co.Ltd から提供されています。このアプリが組織データをどのように収集して保存するかについて、およびアプリが収集するデータに対して組織が持つ制御について説明します。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | アプリケーション | ユーザーメール、ユーザーイベントなどのデータが保存されます。 ルームの可用性を確認し、イベントを作成するために、ユーザイベントが収集されます。 | ユーザーイベントのID、ロケーション名、その他のイベントの詳細が保存されます。 ルームの可用性を確認し、イベントを作成するためのデータが収集されます。 | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| Mail.Send | アプリケーション | ユーザーの電子メールなどのデータ。 ユーザーの電子メールは、部屋の予約リマインダー電子メールを送信するために収集されます。 | ユーザーの電子メールなどのデータ。 ユーザーの電子メールは、部屋の予約リマインダー電子メールを送信するために収集されます。 | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| User.Read | 委任 | ユーザー ID 、名前、電子メールなどのデータ。 アプリケーションでサインイン ユーザーのユーザー データが収集されます。 | ユーザー ID 、名前、電子メールなどのデータ。 アプリケーションでサインイン ユーザーのユーザー データが収集されます。 | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| User.Read.All | アプリケーション | ユーザー ID 、名前、電子メールなどのデータ。 アプリケーションでサインイン ユーザーのユーザー データが収集されます。 | ユーザー ID 、名前、電子メールなどのデータ。 アプリケーションでサインイン ユーザーのユーザー データが収集されます。 | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| メール | 委任 | ユーザーの電子メールなどのデータ。 ユーザーの電子メールは、ユーザーの可用性を確認し、イベントを作成するために収集されます。 | ユーザーの電子メールなどのデータ。 ユーザーの電子メールは、ユーザーの可用性を確認し、イベントを作成するために収集されます。 | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |
>| openid | 委任 | ユーザーがアプリケーションにログインできるように、ユーザーの openid を指定します。 | ユーザーがアプリケーションにログインできるように、ユーザーの openid を指定します。 | a85d5d70-9b9c-46e4-bdd6-d139f1648dea |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>ユーザーメール、ユーザーイベントなどのデータが保存されます。 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>データベースに格納されているデータ。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報はエキスパートシステムIVR(アジア)Co.Ltd から提供されています。このアプリが認証、承認、アプリケーション登録のベスト プラクティス、およびその他の ID 条件を処理する方法について説明します。

| **Information** | **応答** |
|:----------------|:-------------|
| マイクロソフト識別プラットフォーム (Azure AD) と統合しますか。  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか。  | はい |
| アプリは認証に MSAL (マイクロソフト認証ライブラリ) を使用していますか? | いいえ |
| アプリで条件付きアクセス ポリシーがサポートされていますか。 | いいえ |
| アプリがシナリオに対して最低限の権限を要求しているか。 | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的に、または増分的に要求するアクセス許可を正確に反映していますか。 | はい |
| アプリでマルチテナント機能がサポートされていますか。 | はい |
| アプリに機密クライアントが存在しますか? | いいえ |
| アプリに登録されているすべてのリダイレクト統一リソース識別子 (URI) を所有していますか。 | はい |
| アプリの場合、何を使用しないようにしますか。 | - ワイルドカードリダイレクト URI<br/><br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか。 | はい |
| クライアント アプリが適切な同意を得た場合にのみ、アクセス許可モデルで呼び出しが成功することを許可しますか。 | はい |
| アプリでプレビュー API を使用していますか。 | いいえ |
| アプリで非推奨の API が使用されていますか。 | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
