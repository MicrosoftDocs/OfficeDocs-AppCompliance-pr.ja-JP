---
title: Engage Squared によるボード Connectアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 02/16/2021
ms.topic: article
ms.service: attestation
description: ボード Connect、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリのセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 51c344c6810287c155dffbac170fea0c1ab16259
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095248"
---
# <a name="board-connect"></a>Board Connect

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 2 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/e8f06a4e-cefe-4b1e-a24b-c97bea471130" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001955" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Engage Squared から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Board Connect |
| ID | WA200001955 |
| 機能 | Tab |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Engage Squared |
| パートナー Web サイトの URL | [https://boardconnect.app](https://boardconnect.app) |
| [アプリケーション情報Teamsページの URL | [https://boardconnect.app](https://boardconnect.app) |
| プライバシー ポリシーの URL | [https://boardconnect.app/privacy](https://boardconnect.app/privacy) |
| 利用規約の URL | [https://boardconnect.app/terms](https://boardconnect.app/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Engage Squared によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 委任 | アプリがユーザーカレンダーを更新して、アプリを介して提出された会議出席応答を反映するように許可する。 | Azure テーブル ストレージ内にデータが格納されません | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| Group.ReadWrite.All | 委任 | アプリがグループ予定表イベントを作成、更新、削除を許可する。 | グループの ID をテナント ID と共に格納します。これは、組織が Board Connect のライセンスを受け取っているのを検証するために、ライセンスの観点から保存および使用されます。 また、これを使用して、テナント内のアプリケーションのインストール数を追跡します。これはライセンス モデルとインラインです。 | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| Sites.Manage.All | 委任 | アプリがリストとライブラリを作成するには、リスト アイテムを管理し、チーム サイト コレクションでドキュメントを管理します。 | なし | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| User.Read | 委任 | ユーザーがアプリにサインインし、アプリが現在サインインしているユーザーのプロファイルを読み取るのを許可する。 | このエンドポイントからのデータは Azure テーブル ストレージに格納されません | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| User.ReadBasic.All | 委任 | サインインしているユーザーの代わりに他のユーザーのプロファイル プロパティの基本的なセットをアプリで読み取り、これをアプリに表示できます。 これには、表示名、名と名、電子メール アドレス、写真が含まれます。 | なし、データは Azure テーブル ストレージに格納されません | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |
>| offline_access | 委任 | アプリが更新トークンを取得するには、現在のトークンが期限切れになったときに新しいアクセス トークンを取得するために使用できます。 | なし、データは Azure テーブル ストレージ内に格納されません | 4a6873f6-8360-4023-bd6f-2923d1eb2e94 |


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

>すべての管理者に 2FA を割り当て、2 人の二乗ユーザーだけがアクセスできます

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36435" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 基準を処理する方法について Engage Squared によって提供されています。

| **Information** | **応答** |
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
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、
<br />
- OAuth2 暗黙的なFlow(SPA に必要な場合を含む)
<br />
 | |アプリは Web API を公開していますか? |はい | |アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? |はい | |アプリでプレビュー API を使用していますか? |いいえ| |アプリで非推奨の API を使用していますか? |いいえ|

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
