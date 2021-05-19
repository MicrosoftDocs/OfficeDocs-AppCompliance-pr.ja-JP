---
title: Eラーニングフォース・インターナショナルによるLMS365のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 02/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: LMS365 の利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 44ed1631c7d0221b463f518f2494b7a8744eef30
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552218"
---
# <a name="lms365"></a>LMS365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 2 月 25 日</p>

* <a href="https://teams.microsoft.com/l/app/d136f17e-df84-47f2-97a4-13aa24c0c647" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381467" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Eラーニングフォースインターナショナルがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | LMS365 |
| ID | WA104381467 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | ELEARNINGFORCE International |
| パートナーウェブサイトのURL | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| アプリケーション情報ページTeams URL | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| プライバシーポリシーの URL | [https://www.elearningforce.com/privacy](https://www.elearningforce.com/privacy) |
| 利用規約の URL | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法、およびアプリケーションが収集するデータに対する組織のコントロールに関するELEARNINGFORCEインターナショナルによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | アプリケーション | なし | アプリが、ユーザーのグループをコースに登録するために必要な AD グループ メンバーを展開できるようにします。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | 委任 | なし | 通知用の電子メール アカウントの構成中に、アクセス許可が動的に要求されます。 アプリが通知メールを送信できるようにします | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | アプリケーション | なし | テナントのプロビジョニング中に、アプリSharePointドメインを取得できます。 ドメインは URL の構築に使用されます。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | 委任 | なし | アプリは、現在ログインしているユーザーに対して外部ユーザーを招待することを許可します。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | 委任 | なし | サインインおよびユーザー プロファイルの読み取り。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | 委任 | なし | アプリが現在ログインしているユーザーの完全なプロファイルを読み取ることができます。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | アプリケーション | アプリが完全なユーザー プロファイルを読み取ることを許可します。 階層レポートを作成するために、ユーザー&#8217;マネージャを読み取る必要&#8217;。 | 次の個人データは、アプリケーション内の学習者管理マネージャーダッシュボード機能に使用されるそれぞれの顧客の専用データベースに保存されます &amp; 。 アカウント名、ユーザー表示名、電子メールアドレス、部門、役職、Office、国、市区町村、管理者 ID/電子メール | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| profile | 委任 | なし | ユーザーの基本プロファイルを表示します。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>他のマイクロソフト API を使用したデータ アクセス

Microsoft 365上に構築されたアプリやアドインでは、Microsoft Graph 以外の Microsoft API を使用して、組織を識別できる情報 (OII) を収集または処理できます。 このアプリが使用するマイクロソフトGraph以外のマイクロソフト API を一覧表示します。

>| **API** |  **OIIは収集されますか?** |  **OIIは何を収集されますか?** | **OIIを収集するための正当性?** | **OII は保存されていますか?** | **OIIを格納するための正当性?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | いいえ |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| ボットがユーザーに挨拶する際に、個人向けメッセージを表示する場合にのみ、名を使用します。 | 個人データは &amp; 、LMS365 アプリケーション内の学習者管理マネージャー ダッシュボード機能に使用されるそれぞれの顧客に対応する専用の Azure データベースに格納されます。 | アカウント名、ユーザー表示名、電子メールアドレス、部門、役職、Office、国、市区町村、管理者 ID/電子メール |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>はい、私たちは、トラブルシューティングのみに使用され、すべてのデータが削除された後、90日間の保持ポリシーを持っているInsights Log Analyticsテレメトリ/ログを使用します。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>LMS365 は、クライアント LMS365 データベースから個人データを削除するパージ機能を備えています。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリケーションが認証、許可、アプリケーション登録のベストプラクティス、およびその他のID基準をどのように処理するかについて、ELEARNINGFORCEインターナショナルによって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| マイクロソフト識別プラットフォーム (Azure AD) と統合しますか。  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか。  | はい |
| アプリは認証に MSAL (マイクロソフト認証ライブラリ) を使用していますか? | はい |
| アプリで条件付きアクセス ポリシーがサポートされていますか。 | はい |
| サポートされているポリシーの種類を一覧表示する | デバイス プラットフォーム、デバイスの状態、クライアント アプリ |
| アプリがシナリオに対して最低限の権限を要求しているか。 | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的に、または増分的に要求するアクセス許可を正確に反映していますか。 | はい |
| アプリでマルチテナント機能がサポートされていますか。 | はい |
| アプリに機密クライアントが存在しますか? | いいえ |
| アプリに登録されているすべてのリダイレクト統一リソース識別子 (URI) を所有していますか。 | はい |
| アプリは Web API を公開していますか。 | はい |
| クライアント アプリが適切な同意を得た場合にのみ、アクセス許可モデルで呼び出しが成功することを許可しますか。 | はい |
| アプリでプレビュー API を使用していますか。 | いいえ |
| アプリで非推奨の API が使用されていますか。 | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
