---
title: ServiceNow による今すぐ仮想エージェントのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
description: Now Virtual Agent で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c6cc9da641b2e1f03aee7b23b0bae5312793cc80
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096130"
---
# <a name="now-virtual-agent"></a>Now Virtual Agent

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 3 月 23 日</p>

* <a href="https://teams.microsoft.com/l/app/49471a10-fdbc-4ffb-b0b8-944f3df985d9" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381816" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

ServiceNow から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Now Virtual Agent |
| ID | WA104381816 |
| 機能 | Bot |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | ServiceNow |
| パートナー Web サイトの URL | [https://www.servicenow.com/](https://www.servicenow.com/) |
| [アプリケーション情報Teamsページの URL | [https://docs.servicenow.com/bundle/london-servicenow-platfo...](https://docs.servicenow.com/bundle/london-servicenow-platform/page/administer/virtual-agent/task/install-va-integrations.html#install-va-integrations) |
| プライバシー ポリシーの URL | [https://www.servicenow.com/service-privacy.html](https://www.servicenow.com/service-privacy.html) |
| 利用規約の URL | [https://www.servicenow.com/terms-of-use.html](https://www.servicenow.com/terms-of-use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールについて ServiceNow によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 委任 | ドメインは、将来のメッセージ ルーティングの目的でデータ センターに保存されます。 | ServiceNow 管理者が MS サーバーとの統合をインストールTeams、管理者は MS アカウントにログインTeamsがあります。 メール アドレス (完全な電子メール アドレスではない) からドメインを読み取ります。 |  |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>ServiceNow で使用できない場合。 お客様は、Virtual Agent フレームワークを利用して、組織またはエンド ユーザー情報にアクセスできる追加の機能を構築できます。 ユーザーは、ボットとの対話中に個人を特定できる情報を入力し、その情報を ServiceNow に送信することができます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>詳細については [、「Cloud Security Alliance」セクション](/microsoft-365-app-certification/teams/servicenow-now-virtual-agent?pivots=csa) を参照してください。


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10638' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10638" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

