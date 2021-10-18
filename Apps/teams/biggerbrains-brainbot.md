---
title: Biggerbrains による BrainBot のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 04/29/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: BrainBot、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 568e5b5ad334c5b93049c7bba878b39b73050050
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60445445"
---
# <a name="brainbot"></a>BrainBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 4 月 28 日</p>

* <a href="https://teams.microsoft.com/l/app/3c95872f-ca12-456e-84b9-c717fe93330c" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381981" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Biggerbrains から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | BrainBot |
| ID | WA104381981 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Biggerbrains |
| パートナー Web サイトの URL | [https://getbiggerbrains.com](https://getbiggerbrains.com) |
| [アプリケーション情報Teamsページの URL | [https://brainbot.ai](https://brainbot.ai) |
| プライバシー ポリシーの URL | [https://www.brainbot.ai/privacypolicy/](https://www.brainbot.ai/privacypolicy/) |
| 利用規約の URL | [https://brainbot.ai/terms/](https://brainbot.ai/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関して、Biggerbrains によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | アプリケーション | 認証プロセスの一環 &amp; として、電子メール アドレスのフルネームを使用します。 また、電子メール アドレスは、ユーザーが 1 つを購読するときに、ユーザーに学習シーケンスを送信するために使用されます。 | 認証プロセスの一環 &amp; として、電子メール アドレスのフルネームを使用します。 また、電子メール アドレスは、ユーザーが 1 つを購読するときに、ユーザーに学習シーケンスを送信するために使用されます。 | [b256b34a-b377-4fc2-b25a-a8f5f0594e86](https://docs.microsoft.com/microsoft-365-app-certification/azure/b256b34a-b377-4fc2-b25a-a8f5f0594e86) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 認証プロセスの一環 &amp; として、電子メール アドレスのフルネームを使用します。 また、電子メール アドレスは、ユーザーが 1 つを購読するときに、ユーザーに学習シーケンスを送信するために使用されます。 | 電子メール アドレス &amp; の完全な名前 | これらは、ログインの目的で使用され、アプリの機能の一部として使用され、ユーザーが学習シーケンスを購読するときにユーザーに送信します。 |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>トレーニング評価に対するユーザーの応答は、個人または組織から削除が要求されるまで保存されます。  非アクティブなアカウントは、12 か月後に削除されます。 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>n/a の場合、データはパートナー システムに保存されません

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37584' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37584" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 条件を処理する方法について、Biggerbrains によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | 不要 |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | 不要 |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | 不要 |
| アプリに機密クライアントがありますか? | 不要 |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | 不要 |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
