---
title: セールスティム別アプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: SalesTim の利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c9094f50723c7094f895d21f8a9569dedbb5863b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553918"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者による最終更新日: 2020年10月27日</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

SalesTim がマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | SalesTim |
| ID | WA200001393 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | SalesTim |
| パートナーウェブサイトのURL | [https://www.salestim.com](https://www.salestim.com) |
| プライバシーポリシーの URL | [https://www.salestim.com/legal/privacy](https://www.salestim.com/legal/privacy) |
| 利用規約の URL | [https://www.salestim.com/legal/tos](https://www.salestim.com/legal/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法、およびアプリが収集するデータに対する組織のコントロールに関する SalesTim によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | 委任 | 動作しない | アプリが企業アプリ カタログに独自のパッケージをインストールして更新できるようにします。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | 委任 | 一部のユーザー ID のみを再保存&#8217;、プロファイル データは格納しません。 | ワークフロー内の承認者の選択など、アプリケーションのさまざまな場所で他のユーザーを選択できます。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | 委任 | グループ/チームの ID のみを再保存&#8217;、グループ/チームのコンテンツを格納&#8217;。 | アプリがグループを作成し、サインインしているユーザーに代わってすべてのグループ プロパティとメンバーシップを読み取ることができます。 さらに、グループの所有者が自身のグループを管理できるよう、またグループ メンバーがグループのコンテンツを更新できるようにします。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | 委任 | 通知日、受信者 (ID のみ)、要求 ID など、このアクションのメタデータを再び格納&#8217;。 | 承認ワークフロー中に通知メールを送信することをアプリに許可します。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | 委任 | データを格納するためにいくつかの Azure サービス Cosmosを使用しています。 | チームプロビジョニングプロセス中に、チームに関連付けられたドライブ (ファイルとフォルダー) をアプリが管理できるようにします。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | 委任 | 一部のユーザー ID のみを再保存&#8217;、プロファイル データは格納しません。 | アプリが、すべてのユーザーのプロファイル プロパティ、レポート、およびマネージャーの完全なセットを読み取ることができます。 特に、対象ユーザーのターゲット設定プロセスで、現在のユーザー プロファイルに基づいてコンテンツをフィルター処理するために使用されます。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| オフラインアクセス | 委任 | いいえ | アプリがユーザーとしていくつかのバックグラウンド操作とアクションを実行できるようにします。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>| **すべての非Microsoft サービス OII は、** |  **どのようなOIIが転送されますか?** | **OIIを転送するための正当性?** |
>|:-------------------|:--------------------------|:--------------------------|
>| 私たちは、私たちの主なサポートアプリケーションとしてインターコムを使用しています。 Intercom には、次の説明に従って、基本的なユーザー プロファイル情報が含まれている場合があります。 https://developers.salestim.com/platform/datamanagement.html#support-data |  | 運用環境から問題を自動的に生成するために、GitHub API を使用しています。 また、GitHubに技術的なログを保存しています(ここで説明するように https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) : . これらの問題とログには、基本的なユーザー プロファイル情報が含まれている場合があります。 これらの問題とログは、15 日ごとに自動的に削除されます。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>収集されたすべてのデータは次のとおりです: https://developers.salestim.com/platform/datamanagement.html#application-data 説明したように、ログは一時的に 15 日間保存され、自動的に削除されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>ほとんどのデータは、Azure Cosmos DB に格納されます。
運用環境へのアクセスは 2 人に制限され、これらの管理者アカウントは MFA が適用されます。
これらのアカウントは専用であり、当社の企業アカウントとは異なります。
データは、使用しているすべての Azure サービスで保存時に暗号化されます。
運用環境への展開は、GitHub環境の専用の保護されたブランチを通じて自動化され、変更を承認できるのは 2 人だけです。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

