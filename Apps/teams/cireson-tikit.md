---
title: Cireson による Tikit のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
description: Tikit で利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d053d3093bb27996a0e6ff726c2b6ed1be9812ac
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095408"
---
# <a name="tikit"></a>Tikit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 3 月 11 日</p>

* <a href="https://teams.microsoft.com/l/app/b13c40ee-e073-459e-96b5-3f3cca046a37" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002602" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Cireson から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Tikit |
| ID | WA200002602 |
| 機能 | ボット、メッセージングの拡張機能 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Cireson |
| パートナー Web サイトの URL | [https://tikit.ai](https://tikit.ai) |
| [アプリケーション情報Teamsページの URL | [https://tikit.ai](https://tikit.ai) |
| プライバシー ポリシーの URL | [https://tikit.ai/privacy-statement](https://tikit.ai/privacy-statement) |
| 利用規約の URL | [https://tikit.ai/terms-service](https://tikit.ai/terms-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて、Cireson によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Device.Read | アプリケーション | Teams ボット通信によるシングル サインオンに使用されるユーザー グラフ情報  | ユーザー の役割、ファミリ名、名前、電子メール、AAD ID、ユーザー ID Teams保存します。 この情報は、アプリケーション認証、セキュリティ、RBAC、チーム統合、チーム通知、およびユーザー関係マッピングに使用されます。   | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.AccessAsUser.All | 委任 | RBAC のグループ名と役割 | グループ名 &amp; 役割名、セキュリティで保護されたマップされたアクセス制御を提供する必要があります。 | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Directory.Read.All | 委任 | RBAC のグループ名と役割 | グループ名 &amp; 役割名、セキュリティで保護されたマップされたアクセス制御を提供する必要があります。 | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| Group.Read.All | 両方とも | RBAC のグループ名と役割 | RBAC のグループ名と役割 | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read | 委任 | ユーザー の役割、ファミリ名、指定された名前、電子メール、AAD ID、Teams ID、認証に使用されるユーザー ID  | ユーザー の役割、ファミリ名、指定された名前、電子メール、AAD ID、Teams ID、認証に使用されるユーザー ID  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.Read.All | アプリケーション | ユーザー の役割、ファミリ名、指定された名前、電子メール、AAD ID、Teams ID、認証に使用されるユーザー ID  | ユーザー の役割、ファミリ名、指定された名前、電子メール、AAD ID、Teams ID、認証に使用されるユーザー ID  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| User.ReadBasic.All | 委任 | ユーザー の役割、ファミリ名、指定された名前、電子メール、AAD ID、Teams ID、認証に使用されるユーザー ID  | ユーザー の役割、ファミリ名、指定された名前、電子メール、AAD ID、Teams ID、認証に使用されるユーザー ID  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| メール | 委任 | 関連するエンティティのログインと関連付けられた ID に使用されるユーザー 電子メール。 &quot;割り当てられたユーザー&quot; | 関連するエンティティのログインと関連付けられた ID に使用されるユーザー 電子メール。 &quot;割り当てられたユーザー&quot; | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| openid | 委任 | 要件ごとの MSAL による認証に使用される  | 要件ごとの MSAL による認証に使用される  | b13c40ee-e073-459e-96b5-3f3cca046a37 |
>| profile | 委任 | 要件ごとの MSAL による認証に使用される  | 要件ごとの MSAL による認証に使用される  | b13c40ee-e073-459e-96b5-3f3cca046a37 |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| QnA Maker | いいえ |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| ユーザー エンティティ関係の名前と電子メール &quot; チケット要求者&quot;  | 名前とメール  | ユーザー エンティティの関係の &quot; チケット要求者&quot;  |



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>会社名、テナント ID、メール、ボット クライアント ID をアプリの分析情報に保存し、30 dat 保持ポリシーを使用します。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>パートナー システムにはデータが含まれておりかねない。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36548" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity 条件を処理する方法について、Cireson によって提供されています。

| **Information** | **応答** |
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
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、
<br />
- OAuth2 暗黙的なFlow(SPA に必要な場合を含む)
<br />
- リソース所有者パスワード資格情報 (ROPC) フロー | |アプリは Web API を公開していますか? |はい | |アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? |はい | |アプリでプレビュー API を使用していますか? |はい | |アプリで非推奨の API を使用していますか? |いいえ|

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
