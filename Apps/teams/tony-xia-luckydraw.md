---
title: Tony Xia による LuckyDraw のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 07/21/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: LuckyDraw、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5ba1afff33ce27c6f520b34f73423c734c8859ec
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551267"
---
# <a name="luckydraw"></a>LuckyDraw

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020 年 7 月 21 日</p>

* <a href="https://teams.microsoft.com/l/app/75c676b5-be32-430e-acee-71bcb929b297" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000091" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Tony Xia から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | LuckyDraw |
| ID | WA200000091 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Tony Xia |
| パートナー Web サイトの URL | [https://luckydraw.teetee365.com](https://luckydraw.teetee365.com) |
| [アプリケーション情報Teamsページの URL | [https://luckydraw4web4prd.z7.web.core.windows.net/](https://luckydraw4web4prd.z7.web.core.windows.net/) |
| プライバシー ポリシーの URL | [https://luckydraw.teetee365.com/privacy](https://luckydraw.teetee365.com/privacy) |
| 利用規約の URL | [https://luckydraw.teetee365.com/terms](https://luckydraw.teetee365.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて、Tony Xia によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft アプリケーションをGraph。


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| LuckyDraw が名簿にアクセスしない | LuckyDraw が名簿にアクセスしない |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>EUII は状況によってはログに記録されます。 たとえば、ユーザーは幸運な描画アクティビティを開始します。 アプリは、データ保持が既定で 90 日間である Azure Application Insights を使用しています。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>データは Table Storage に格納されます。 ストレージ アカウントのキーは KeyVault に格納され、MSI (Managed System Identity) を介して App Service (Bot app) によってアクセスされます。 このアプリ サービスは、KeyVault アクセス ポリシー リストで許可される唯一の ID です。 PROD 環境でこのアプリのすべての Azure リソースが作成され、ネットワーク経由でARM。 手動操作はありません。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35696' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35696" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

