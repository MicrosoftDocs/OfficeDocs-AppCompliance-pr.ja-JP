---
title: H3ソリューションズ社によるAtBotのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: AtBot の利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3f56d0b3eb19f5bed8f7092507c8605af936b911
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552138"
---
# <a name="atbot"></a>AtBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

H3ソリューションズ社がマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | AtBot |
| ID | WA104381219 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | H3 Solutions, Inc. |
| パートナーウェブサイトのURL | [https://atbot.io](https://atbot.io) |
| アプリケーション情報ページTeams URL | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| プライバシーポリシーの URL | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| 利用規約の URL | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法、およびアプリが収集するデータに対する組織のコントロールについて、H3 Solutions, Inc. によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | アプリケーション | AAD グループ名、AAD グループ GUID、UPN | AAD グループを列挙して、ボットのスキルをセキュリティでトリミングできるようにします。 ライセンスを適用できるようにユーザーを列挙します。 管理者/共同作成者として追加するユーザーを列挙する | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| Directory.Read.All | 委任 | AAD グループ名、AAD グループ GUID、UPN | AAD グループを列挙して、ボットのスキルをセキュリティでトリミングできるようにします。 ライセンスを適用できるようにユーザーを列挙します。 管理者/共同作成者として追加するユーザーを列挙する | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| People.Read | 委任 | いいえ | [ユーザーの取得] アクションのユーザーをFlowから列挙します。  ボットが Microsoft Graphの /People エンドポイントからユーザーを取得できるようにします。 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| User.Read | 委任 | テナント ID、UPN | ユーザー&#8217;テナント ID と UPN にアクセスして、作成されたフロー/ロジック アプリを作成したユーザーに結び付けられるようにします。 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| メール | 委任 | いいえ | ユーザーの電子メール アドレスにアクセスできます。 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| offline_access | 委任 | アクセス/更新トークン。 | ユーザーのログインを維持するために更新トークンを使用できます。 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| openid | 委任 | いいえ | ユーザーがログインできるようにします。 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| profile | 委任 | UPN | ユーザーの UPN へのアクセス。 | 066a6b3a-f7a0-450a-98c7-34db1da31594 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| ボット生成のチャット メッセージでのメンションの作成 | いいえ |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>テナント ID、UPN アプリケーションインサイトを使用し、ログは 90 日間続き、自動的にアーカイブされます。 (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>管理者は、AAD グループ名/GUID を含む可能性のあるボットの構成を削除できます。
サービスのキャンセル時に、すべての UPN がライセンス データベースから削除されます。
Data Residencyの下にある「Azure サービス」を参照してください。  AtBot を使用して作成された顧客固有のデータの多くは顧客のテナントに格納されるため、そのテナントの管理者は、そこでデータを完全に制御できます。


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

