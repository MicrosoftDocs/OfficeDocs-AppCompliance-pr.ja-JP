---
title: Chrono Innovation によるクロノスコープ時間追跡のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR レジストリの Chronoscope Time Tracking、データ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、およびセキュリティ/コンプライアンス情報に関する利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: e275e7a41794b06cb7afc65d60e99ef9037f50a5
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428834"
---
# <a name="chronoscope-time-tracking"></a>時系列の時間追跡

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 7 月 23 日</p>

* <a href="https://teams.microsoft.com/l/app/5b3ded07-fa1a-4fd8-a323-e5fe3f8cf740" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003095" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Chrono Innovation から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | 時系列の時間追跡 |
| ID | WA200003095 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Chrono Innovation |
| パートナー Web サイトの URL | [https://www.chronoinnovation.com](https://www.chronoinnovation.com) |
| [アプリケーション情報Teamsページの URL | [https://www.chronoscope.app](https://www.chronoscope.app) |
| プライバシー ポリシーの URL | [https://www.chronoscope.app/privacy-policy](https://www.chronoscope.app/privacy-policy) |
| 利用規約の URL | [https://www.chronoscope.app/terms-of-service](https://www.chronoscope.app/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Chrono Innovation によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AccessReview.Read.All | アプリケーション | teams tenantId、teams addObjectId、teams ユーザー アカウント情報。 Chronoscope ユーザーをリンクする場合、電子メールが Teams アカウントと一致することを検証し、ユーザーから手動で手順を実行せずにアカウントをリンクできます。 | teams tenantId 、teams addObjectId、teams ユーザー アカウント情報。 Chronoscope ユーザーをリンクする場合、電子メールが Teams アカウントと一致することを検証し、ユーザーから手動で手順を実行せずにアカウントをリンクできます。 | [9bc8244d-a186-4b12-809e-c47b3eee73c6](https://docs.microsoft.com/microsoft-365-app-certification/azure/9bc8244d-a186-4b12-809e-c47b3eee73c6) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| teams ユーザーワークスpaを見つけるために、Chronoscope ユーザーをリンクするときに、電子メールが Teams アカウントと一致することを検証しています。そのため、アプリケーションのデータベースの user.ce から手動でアカウントをリンクし、その teams ユーザーを認証できます。 | tenantId , userId , addObjectId , givenName ,email ,role,objectId などのユーザー アカウント情報 | Chronoscope ユーザーをリンクする場合、電子メールが Teams アカウントと一致することを検証しています。そのため、ユーザーから手動で手順を実行せずにアカウントをリンクできます。 また、事前に入力されたユーザーの時間エントリに関する通知をプッシュして、ユーザーが保存/編集/削除できる。 |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>時間エントリに関連する情報。 Chrono Innovation は、Chronoscope アカウントが削除された 90 日後に顧客データを削除します。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>管理者は、パートナーのシステムに存在する情報を完全に制御できます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 基準を処理する方法について Chrono Innovation によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/> |
| アプリは Web API を公開していますか? | 不要 |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
