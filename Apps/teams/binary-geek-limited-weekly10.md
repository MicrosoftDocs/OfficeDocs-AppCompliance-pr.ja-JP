---
title: Binary Geek Limited による Weekly10 のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/26/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Weekly10 で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9bdd5e42398270719c9f0ecd9814155974dbee6f
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411131"
---
# <a name="weekly10"></a>Weekly10

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>最終更新日: 2021 年 8 月 19 日</p>

* <a href="https://teams.microsoft.com/l/app/c80cee99-d17f-4b2d-a2a4-57652ffd2a4b" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001441" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Binary Geek Limited to Microsoft が提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Weekly10 |
| ID | WA200001441 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Binary Geek Limited |
| パートナー Web サイトの URL | [https://www.weekly10.com](https://www.weekly10.com) |
| [アプリケーション情報Teamsページの URL | [https://www.weekly10.com/integrations/microsoft-teams/](https://www.weekly10.com/integrations/microsoft-teams/) |
| プライバシー ポリシーの URL | [https://www.weekly10.com/terms/privacy](https://www.weekly10.com/terms/privacy) |
| 利用規約の URL | [https://www.weekly10.com/terms/customer](https://www.weekly10.com/terms/customer) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関して、Binary Geek Limited によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | アプリケーション | ユーザーが Weekly10 にAzure AD同期する (オプション) | ユーザー ID データ: ユーザー プリンシパル名、メール、名、名、およびマネージャー。 | [2cc7f3cd-05e3-4ebb-b9f9-d92f1bcda7fb](https://docs.microsoft.com/microsoft-365-app-certification/azure/2cc7f3cd-05e3-4ebb-b9f9-d92f1bcda7fb) |
>| Calendars.ReadWrite | アプリケーション | 従業員の空き時間の確認と会議の自動予約 (オプション)。 | 従業員の空き時間 (詳細ではない) と、その会議への参照を会議が予約された場合。 このデータは、シームレスな従業員エクスペリエンスのために従業員がオフィスを外れた場合の把握や、1:1s または Performance Reviews の会議の予約に使用されます。 | [494610b2-b490-4f54-8384-312d6f9b4869](https://docs.microsoft.com/microsoft-365-app-certification/azure/494610b2-b490-4f54-8384-312d6f9b4869) |
>| User.Read | 委任 | SSO 目的のユーザーの検証を、Azure AD。 | トークン情報以外に追加のデータは保持されません。 | [6fd1421e-89e8-4a8b-bd01-9397656a50d5](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fd1421e-89e8-4a8b-bd01-9397656a50d5) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 個人のTeamsユーザー ID にのみアクセスします。 つまり、ボットは特定の方法でそのユーザーに応答できます。 | 不要 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>報告されたバグや問題が発生した場合の組織名とユーザー名。 ログは、この形式で最大 30 日間保存され、削除されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>Weekly10 に存在するデータはすべて、指定した管理者によって制御できます。 Weekly10 でポリシーを変更すると、クライアント データが存在する Microsoft Azureデータに直接影響します。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について、Binary Geek Limited によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | いいえ |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/><br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

