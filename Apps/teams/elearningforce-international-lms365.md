---
title: ELEARNINGFORCE International による LMS365 のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 02/25/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: LMS365 で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
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

* <a href="https://teams.microsoft.com/l/app/d136f17e-df84-47f2-97a4-13aa24c0c647" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381467" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

ELEARNINGFORCE International から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | LMS365 |
| ID | WA104381467 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | ELEARNINGFORCE International |
| パートナー Web サイトの URL | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| [アプリケーション情報Teamsページの URL | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| プライバシー ポリシーの URL | [https://www.elearningforce.com/privacy](https://www.elearningforce.com/privacy) |
| 利用規約の URL | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、ELEARNINGFORCE International から、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| GroupMember.Read.All | アプリケーション | なし | ユーザーのグループをコースAD登録するために必要なグループ メンバーをアプリで展開できます。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| Mail.Send | 委任 | なし | 通知用の電子メール アカウントの構成中に、アクセス許可が動的に要求されます。 アプリが通知メールを送信できます | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| RoleManagement.Read.Directory | アプリケーション | なし | テナントのプロビジョニング中にアプリSharePointドメインを取得できます。 ドメインは URL の構築に使用されます。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Invite.All | 委任 | なし | アプリが現在ログインしているユーザーに代わって外部ユーザーを招待できます | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read | 委任 | なし | サインインおよびユーザー プロファイルの読み取り。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | 委任 | なし | アプリが現在ログインしているユーザーの完全なプロファイルを読み取るを許可します。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| User.Read.All | アプリケーション | アプリが完全なユーザー プロファイルを読み取るを許可します。 階層&#8217;作成するには、管理者のユーザー&#8217;読み取る必要があります。 | 次の個人データは、アプリケーション内の Learner Management Manager ダッシュボード機能に使用される各顧客の専用データベース &amp; に格納されます。 アカウント名、ユーザー表示名、メール アドレス、部署、役職、Office、国、市、マネージャー ID/メール | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |
>| profile | 委任 | なし | ユーザーの基本的なプロファイルを表示します。 | a1a0b277-0efb-4f00-9661-6d1a3df3cddc |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | いいえ |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| ファースト ネームは、ボットがユーザーに挨拶するときに、カスタマイズされたメッセージを表示する場合にのみ使用します。 | 個人データは、LMS365 アプリケーション内の Learner Management Manager ダッシュボード機能に使用されるそれぞれの顧客用の専用 &amp; の Azure Database に格納されます。 | アカウント名、ユーザー表示名、メール アドレス、部署、役職、Office、国、市、マネージャー ID/メール |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>はい、トラブルシューティングにのみ使用される Insights Log Analytics テレメトリ/ログを使用し、90 日間の保持ポリシーを持ち、その後すべてのデータが削除されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>LMS365 には、クライアント LMS365 データベースから個人データを削除する Purge 関数が装備されています。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について ELEARNINGFORCE International から提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | デバイス プラットフォーム、デバイス状態、クライアント アプリ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | いいえ |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
