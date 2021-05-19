---
title: スプリングワークス HR テックによるトリビア向けアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 01/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: トリビアの利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、およびCSA STARレジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: fbd1b9f5f308f3690a9d55a40993ba6122e8f81b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553848"
---
# <a name="trivia"></a>Trivia

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 1 月 13 日</p>

* <a href="https://teams.microsoft.com/l/app/391082c3-968b-47b1-9c92-b5daf008000b" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001956" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

スプリングワークス HR テックがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Trivia |
| ID | WA200001956 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Springworks HR Tech |
| パートナーウェブサイトのURL | [https://springworks.in/](https://springworks.in/) |
| アプリケーション情報ページTeams URL | [https://www.springworks.in/trivia](https://www.springworks.in/trivia) |
| プライバシーポリシーの URL | [https://trivia.springworks.in/policy](https://trivia.springworks.in/policy) |
| 利用規約の URL | [https://trivia.springworks.in/tnc](https://trivia.springworks.in/tnc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して保存する方法と、アプリが収集するデータに対する組織のコントロールについてSpringworks HR Techによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | 委任 | いいえ | ユーザーが属しているTeamsの一覧を取得するには | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| Team.ReadBasic.All | 委任 | はい、ボットが追加されたチームのリストを格納します | ワークスペースに存在するすべてのチームに関する基本情報を収集するには | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| User.Read.All | 委任 | はい、ユーザーの一意な aadObjectId を格納します。 また、ユーザー名、電子メールなど、ユーザーのさまざまな詳細を、トリビアのダッシュボードに表示 | ワークスペースに存在するすべてのユーザーの詳細を取得するには | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| openid | 委任 | はい、アプリにサインインするユーザーを格納します。 |  ユーザーが自分のアカウントでアプリを使用できるようにし、アプリがユーザーのデータを使用できるようにする | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| profile | 委任 | はい、クイズやその他の機能のホストのユーザーIDと名前を保存し、それらを一意に識別します | ユーザー名などのユーザーの基本的なプロフィール情報を読むには、電子メール | 43bc466a-7678-476f-b904-2d933c5bbfc3 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>| **すべての非Microsoft サービス OII は、** |  **どのようなOIIが転送されますか?** | **OIIを転送するための正当性?** |
>|:-------------------|:--------------------------|:--------------------------|
>| AWS, メールチンパンジー, ストライプ.  | 顧客名、電子メール、IP、支払情報 | 当社は、これらの第三者を使用して、お客様に最高のカスタマーエクスペリエンスを提供します |

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| このデータは、クイズやその他の機能に参加者のリストを表示し、保存するために使用されます | 名前、電子メール | はい、クイズの主催者や参加者のデータを保存して、エラーが発生した場合のホストとの分析やコミュニケーションのために |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>OII: 組織名、テナント ID がログに表示されます。EUII: aad オブジェクト ID、フル ネーム、電子メールがログに表示されます。 ログが自動的に削除される 30 日間の保持期間の投稿があります。 


#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>RDS、AWS に保存されたデータ。 暗号化されます。 エンジニア、エンジニアリングリード、創業者のDevOpsにのみアクセスできます

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベストプラクティス、およびその他のID基準を処理する方法についてSpringworks HR Techによって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| マイクロソフト識別プラットフォーム (Azure AD) と統合しますか。  | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
