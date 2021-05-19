---
title: チキットのアプリケーション情報(シレソン)
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tikit の利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: de10b787d3e4100972e46efe76050ed0c7df31fd
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553248"
---
# <a name="tikit"></a>Tikit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021年3月11日</p>

* <a href="https://teams.microsoft.com/l/app/b13c40ee-e073-459e-96b5-3f3cca046a37" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002602" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

サーソンがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Tikit |
| ID | WA200002602 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Cireson |
| パートナーウェブサイトのURL | [https://tikit.ai](https://tikit.ai) |
| アプリケーション情報ページTeams URL | [https://tikit.ai](https://tikit.ai) |
| プライバシーポリシーの URL | [https://tikit.ai/privacy-statement](https://tikit.ai/privacy-statement) |
| 利用規約の URL | [https://tikit.ai/terms-service](https://tikit.ai/terms-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法と、アプリが収集するデータに対する組織のコントロールに関する Cireson によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Device.Read | アプリケーション | シングル サインオンに使用されるユーザー グラフ情報 (チーム ボット通信経由)  | ユーザーロール、家族名、名前、電子メール、AAD ID、TeamsユーザーIDを保存します。 この情報は、アプリケーション認証、セキュリティ、RBAC、チーム統合、チーム通知、およびユーザー関係マッピングに使用されます。   | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.AccessAsUser.All | 委任 | RBAC のグループ名とロール | グループ名 &amp; の役割名、セキュアなマップされたアクセス制御を提供する必要があります。 | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.Read.All | 委任 | RBAC のグループ名とロール | グループ名 &amp; の役割名、セキュアなマップされたアクセス制御を提供する必要があります。 | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Group.Read.All | 両方とも | RBAC のグループ名とロール | RBAC のグループ名とロール | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read | 委任 | ユーザー ロール、ファミリ名、名前、電子メール、AAD ID、Teamsユーザー ID、認証に使用  | ユーザー ロール、ファミリ名、名前、電子メール、AAD ID、Teamsユーザー ID、認証に使用  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read.All | アプリケーション | ユーザー ロール、ファミリ名、名前、電子メール、AAD ID、Teamsユーザー ID、認証に使用  | ユーザー ロール、ファミリ名、名前、電子メール、AAD ID、Teamsユーザー ID、認証に使用  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.ReadBasic.All | 委任 | ユーザー ロール、ファミリ名、名前、電子メール、AAD ID、Teamsユーザー ID、認証に使用  | ユーザー ロール、ファミリ名、名前、電子メール、AAD ID、Teamsユーザー ID、認証に使用  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| メール | 委任 | ログインに使用されるユーザー電子メールと関連するエンティティの識別。 &quot;割り当てられたユーザー&quot; | ログインに使用されるユーザー電子メールと関連するエンティティの識別。 &quot;割り当てられたユーザー&quot; | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| openid | 委任 | 要件ごとに MSAL による認証に使用される  | 要件ごとに MSAL による認証に使用される  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| profile | 委任 | 要件ごとに MSAL による認証に使用される  | 要件ごとに MSAL による認証に使用される  | b13c40ee-e073-459e-96b5-3f3cca046a37 |

#### <a name="data-access-using-other-microsoft-apis"></a>他のマイクロソフト API を使用したデータ アクセス

Microsoft 365上に構築されたアプリやアドインでは、Microsoft Graph 以外の Microsoft API を使用して、組織を識別できる情報 (OII) を収集または処理できます。 このアプリが使用するマイクロソフトGraph以外のマイクロソフト API を一覧表示します。

>| **API** |  **OIIは収集されますか?** |  **OIIは何を収集されますか?** | **OIIを収集するための正当性?** | **OII は保存されていますか?** | **OIIを格納するための正当性?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| QnAメーカー | いいえ |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| ユーザー エンティティの関連付け &quot; チケット要求者の名前と電子メール&quot;  | 名前と電子メール  | ユーザー エンティティの関連付け &quot; チケット要求者&quot;  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>会社名、テナント ID、電子メール、ボット クライアント ID はアプリインサイトに保存し、30 dat 保持ポリシーを使用します。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>パートナーシステムにはデータがありません。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベストプラクティス、およびその他のID基準を処理する方法についてCiresonによって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| マイクロソフト識別プラットフォーム (Azure AD) と統合しますか。  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか。  | はい |
| アプリは認証に MSAL (マイクロソフト認証ライブラリ) を使用していますか? | はい |
| アプリで条件付きアクセス ポリシーがサポートされていますか。 | いいえ |
| アプリがシナリオに対して最低限の権限を要求しているか。 | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的に、または増分的に要求するアクセス許可を正確に反映していますか。 | はい |
| アプリでマルチテナント機能がサポートされていますか。 | はい |
| アプリに機密クライアントが存在しますか? | はい |
| アプリに登録されているすべてのリダイレクト統一リソース識別子 (URI) を所有していますか。 | はい |
| アプリの場合、何を使用しないようにしますか。 | - ワイルドカードリダイレクト URI<br/>- Spa に必要な場合を除き、OAuth2 暗黙的なFlow<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか。 | はい |
| クライアント アプリが適切な同意を得た場合にのみ、アクセス許可モデルで呼び出しが成功することを許可しますか。 | はい |
| アプリでプレビュー API を使用していますか。 | はい |
| アプリで非推奨の API が使用されていますか。 | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
