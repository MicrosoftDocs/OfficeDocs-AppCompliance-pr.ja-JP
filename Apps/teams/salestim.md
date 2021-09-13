---
title: SalesTim による SalesTim のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: SalesTim のすべての利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b15cf2f87b6707b6fa82dfc3968444d7cad85e8a
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/12/2021
ms.locfileid: "59286924"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者が最終更新日: 2020 年 10 月 27 日</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

SalesTim から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | SalesTim |
| ID | WA200001393 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | SalesTim |
| パートナー Web サイトの URL | [https://www.salestim.com/](https://www.salestim.com/) |
| プライバシー ポリシーの URL | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| 利用規約の URL | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する SalesTim によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.ReadWrite.All | 委任 | 動作しない | アプリが企業アプリ カタログに独自のパッケージをインストールして更新できます。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Directory.AccessAsUser.All | 委任 | プロファイル データ&#8217;、一部のユーザーの ID のみを保存する必要があります。 | ユーザーは、ワークフロー内の承認者の選択など、アプリケーションのさまざまな場所で他のユーザーを選択できます。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Group.ReadWrite.All | 委任 | グループ&#8217;チームの ID のみを保存する必要があります。&#8217;/チームのコンテンツは保存されません。 | サインインしているユーザーに代わって、アプリがグループを作成し、すべてのグループ プロパティとメンバーシップを読み取ることができます。 さらに、グループの所有者が自身のグループを管理できるよう、またグループ メンバーがグループのコンテンツを更新できるようにします。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Mail.Send | 委任 | 通知&#8217;、受信者 (ID のみ)、要求 ID など、このアクションのメタデータを再格納する必要があります。 | アプリが承認ワークフロー中に、たとえば通知メールを送信できます。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Sites.ReadWrite.All | 委任 | Azure サービスの一部を使用してデータを格納しています。特に Azure および DB 上の Redis Cosmosしています | チームのプロビジョニング プロセス中に、チームに関連付けられたドライブ (ファイルとフォルダー) を管理できます。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| User.Read.All | 委任 | プロファイル データ&#8217;、一部のユーザーの ID のみを保存する必要があります。 | アプリが、すべてのユーザーのプロファイル プロパティ、レポート、および管理者の完全なセットを読み取ることができます。 これは、現在のユーザー プロファイルに基づいてコンテンツをフィルター処理するために、特に対象ユーザーのターゲット設定プロセス中に使用されます。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| offlineaccess | 委任 | いいえ | アプリがユーザーとしていくつかのバックグラウンド操作とアクションを実行できます。 | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| メイン サポート アプリケーションとして Intercom を使用しています。 Intercom には、次の説明に従って、いくつかの基本的なユーザー プロファイル情報が含まれている場合があります。 https://developers.salestim.com/platform/datamanagement.html#support-data |  | この API を使用GitHub、実稼働環境から自動的に問題を生成します。 また、いくつかの技術的なログを GitHubに格納します (以下で説明します https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) )。 これらの問題とログには、いくつかの基本的なユーザー プロファイル情報が含まれている場合があります。 これらの問題とログは、15 日ごとに自動的に削除されます。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>収集されたデータはすべてここで説明します。説明に従って、ログは 15 日間一時的に保存され、 https://developers.salestim.com/platform/datamanagement.html#application-data 自動的に削除されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>ほとんどのデータは、Azure Cosmos DB に格納されます。
実稼働環境へのアクセスは 2 人に制限され、これらの管理者アカウントは MFA が適用されます。
これらのアカウントは専用であり、企業アカウントとは異なります。
データは、使用しているすべての Azure サービスで保存時に暗号化されます。
実稼働環境への展開は、2 人だけが変更を承認できる GitHub環境の専用の保護されたブランチを通じて自動化されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

