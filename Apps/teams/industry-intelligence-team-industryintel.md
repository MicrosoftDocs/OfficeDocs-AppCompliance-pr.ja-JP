---
title: 業界インテリジェンス チームによる IndustryIntel のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: IndustryIntel で利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 667a8680991551e79b9be5ae404c660e4ed72092
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251366"
---
# <a name="industryintel"></a>IndustryIntel

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 11 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/beb2be89-a403-46fe-9a67-c1294c9f9740" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001907" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

業界インテリジェンス チームから Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | IndustryIntel |
| ID | WA200001907 |
| 機能 | ボット、タブ、メッセージングの拡張機能 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Industry Intelligence Team |
| パートナー Web サイトの URL | [https://www.industryintel.com/public:about-us/our-team](https://www.industryintel.com/public:about-us/our-team) |
| プライバシー ポリシーの URL | [https://www.industryintel.com/public:legal/privacy-policy-m...](https://www.industryintel.com/public:legal/privacy-policy-msteams) |
| 利用規約の URL | [https://www.industryintel.com/public:legal/terms-of-use](https://www.industryintel.com/public:legal/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールについて、業界インテリジェンス チームから提供されています。

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
>| ユーザーが業界インテリジェンス ネットワークにアクセスできるかどうかを検証します。 ユーザーが正常に検証された場合、ユーザーはボットとメッセージング拡張機能の完全な機能を使用できます。 | Id w/ Industry Intelligence/internal user id をマッピングするチーム メンバー ID のみを格納しました。 |  |



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>いいえ。 ユーザーと SO ユーザー Teamsのマッピングは、SO Teams製品でTeamsされます。 MS Teams識別可能な ID を送信し、ユーザーをマップするために内部的に保存します。 さらに、MS Teamsボット要求用の JWT (要求偽造を防止) を送信し、タブ要求は SO Cookie を使用して検証します。


#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>データ アクセスは IP 範囲システムによって保護され、安全に認証されます。 データは、独自のスキーマに論理的SQL分離され、別のデータベース セットに格納されます。 データは論理的に独立したデータ ストアに格納され、チームの要求でのみアクセスできます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36080' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36080" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

