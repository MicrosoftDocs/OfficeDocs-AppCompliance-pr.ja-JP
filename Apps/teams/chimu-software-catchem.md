---
title: Chimuソフトウェアによるキャッチエムのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 03/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CatchEm、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STARレジストリ内のセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 55b248c8f99e18d08ddf60dec177ce92b543f008
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552318"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021年3月27日</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Chimuソフトウェアがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | CatchEm |
| ID | WA200002639 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Chimu Software |
| パートナーウェブサイトのURL | [https://www.chimusoftware.com](https://www.chimusoftware.com) |
| アプリケーション情報ページTeams URL | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| プライバシーポリシーの URL | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| 利用規約の URL | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法と、アプリが収集するデータに対する組織の制御についてChimu Softwareによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Chat.ReadBasic | 委任 | このアクセス許可は、アプリケーション ユーザーの連絡先を決定するために必要です。 AadObjectId: ユーザーを一意に識別します。 テナント ID: 連絡先が内部または外部のユーザーかどうかを判断します。 表示名、ギブン名、姓: アプリケーション ユーザーへの連絡先を識別します。 電子メール、ユーザー プリンシパル名: 同じ名前の連絡先を区別し、クリックして &quot; チャット機能を許可します &quot; 。 最新のチャット ID: &quot; クリックしてチャット機能を有効にするには &quot; | このアクセス許可は、アプリケーション ユーザーの連絡先を決定するために必要です。 AadObjectId: ユーザーを一意に識別します。 テナント ID: 連絡先が内部または外部のユーザーかどうかを判断します。 表示名、ギブン名、姓: アプリケーション ユーザーへの連絡先を識別します。 電子メール、ユーザー プリンシパル名: 同じ名前の連絡先を区別し、クリックして &quot; チャット機能を許可します &quot; 。 最新のチャット ID: &quot; クリックしてチャット機能を有効にするには &quot; | fc686a41-3bd0-45b3-a56d-f27888fd694 |
>| People.Read | 委任 | 外部連絡先のデータの精度を向上させるため。 表示名: アプリケーション ユーザーの連絡先を識別します。 | 外部連絡先のデータの精度を向上させるため。 表示名: アプリケーション ユーザーの連絡先を識別します。 | fc686a41-3bd0-45b3-a56d-f27888fd694 |
>| Presence.Read.All | 委任 | 連絡先現在のプレゼンス状態 | 該当なし | fc686a41-3bd0-45b3-a56d-f27888fd694 |
>| TeamsActivity.Send | 両方とも | 連絡先のプレゼンス状態が変化したときにユーザーに通知を送信するには | 該当なし | fc686a41-3bd0-45b3-a56d-f27888fd694 |
>| ユーザーのインストール | 委任 | アプリケーションの自動更新を有効にするには | 該当なし | fc686a41-3bd0-45b3-a56d-f27888fd694 |
>| User.Read | 委任 | AadObjectId: ユーザーを一意に識別します。 テナント ID: 連絡先が内部または外部のユーザーかどうかを判断します。 表示名、ギブン名、姓: アプリケーション ユーザーへの連絡先を識別します。 電子メール、IM アドレス、ユーザー プリンシパル名: 同じ名前の連絡先を区別し、 &quot; クリックしてチャット機能を許可します &quot; 。 会社名、国:分析。 アカウント有効、削除日時: 無効なユーザーのユーザー データの自動削除 | AadObjectId: ユーザーを一意に識別します。 テナント ID: 連絡先が内部または外部のユーザーかどうかを判断します。 表示名、ギブン名、姓: アプリケーション ユーザーへの連絡先を識別します。 電子メール、IM アドレス、ユーザー プリンシパル名: 同じ名前の連絡先を区別し、 &quot; クリックしてチャット機能を許可します &quot; 。 会社名、国:分析。 アカウント有効、削除日時: 無効なユーザーのユーザー データの自動削除 | fc686a41-3bd0-45b3-a56d-f27888fd694 |
>| User.ReadBasic.All | 委任 | 内部連絡先のデータの精度を向上させるため。 AadObjectId: ユーザーを一意に識別します。 テナント ID: 連絡先が内部または外部のユーザーかどうかを判断します。 表示名、ギブン名、姓: アプリケーション ユーザーへの連絡先を識別します。 電子メール、ユーザー プリンシパル名: 同じ名前の連絡先を区別し、クリックして &quot; チャット機能を許可します &quot; 。 | 内部連絡先のデータの精度を向上させるため。 AadObjectId: ユーザーを一意に識別します。 テナント ID: 連絡先が内部または外部のユーザーかどうかを判断します。 表示名、ギブン名、姓: アプリケーション ユーザーへの連絡先を識別します。 電子メール、ユーザー プリンシパル名: 同じ名前の連絡先を区別し、クリックして &quot; チャット機能を許可します &quot; 。 | fc686a41-3bd0-45b3-a56d-f27888fd694 |
>| offline_access | 委任 | セキュリティ トークンをGraph、ユーザーがアプリケーションをアクティブに使用していないときに、アプリケーションが連絡先のプレゼンスの変更を通知し、連絡先リストを更新できるようにします。 | セキュリティ トークンのGraph | fc686a41-3bd0-45b3-a56d-f27888fd694 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| &quot;メッセージ機能のタグは &quot; 、連絡先の表示名を使用してアプリケーション ユーザーに表示する必要があります | 連絡先の表示名 | 連絡先の名前をアプリケーション ユーザーに返せるようにするには |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>該当なし

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベストプラクティス、およびその他のID基準を処理する方法についてChimuソフトウェアによって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| マイクロソフト識別プラットフォーム (Azure AD) と統合しますか。  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか。  | はい |
| アプリは認証に MSAL (マイクロソフト認証ライブラリ) を使用していますか? | はい |
| アプリで条件付きアクセス ポリシーがサポートされていますか。 | いいえ |
| アプリがシナリオに対して最低限の権限を要求しているか。 | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的に、または増分的に要求するアクセス許可を正確に反映していますか。 | いいえ |
| アプリでマルチテナント機能がサポートされていますか。 | はい |
| アプリに機密クライアントが存在しますか? | はい |
| アプリに登録されているすべてのリダイレクト統一リソース識別子 (URI) を所有していますか。 | はい |
| アプリは Web API を公開していますか。 | はい |
| クライアント アプリが適切な同意を得た場合にのみ、アクセス許可モデルで呼び出しが成功することを許可しますか。 | はい |
| アプリでプレビュー API を使用していますか。 | はい |
| アプリで非推奨の API が使用されていますか。 | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
