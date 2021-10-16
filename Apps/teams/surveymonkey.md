---
title: SurveyMonkey による SurveyMonkey のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 06/30/2011
ms.topic: article
ms.service: attestation
certification_type: attested
description: SurveyMonkey、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4d792807b4a8160b3e62c7c1a23b4cf8a49b2148
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413349"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2019 年 12 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

SurveyMonkey から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | SurveyMonkey |
| ID | WA104381088 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | SurveyMonkey |
| パートナー Web サイトの URL | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| [アプリケーション情報Teamsページの URL | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| プライバシー ポリシーの URL | [https://www.surveymonkey.com/mp/legal/privacy-policy/](https://www.surveymonkey.com/mp/legal/privacy-policy/) |
| 利用規約の URL | [https://www.surveymonkey.com/mp/legal/terms-of-use/](https://www.surveymonkey.com/mp/legal/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する SurveyMonkey によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.ReadWrite.All | 委任 | 不要 | アンケートを共有するグループ/チャネルのリストを提供するには | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 応答とアンケートをチーム ユーザーに関連付けるには、MS ユーザー ID だけが SurveyMonkey に格納されます。 |  | チームの場合は、作成Microsoft Teams javascript SDK を使用して、アンケートとアンケート結果のタスク モジュールモーダルを使用します。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| v3/conversations/{id}/pagedmembers を呼び出して、アプリがチームに追加され、メンバー数を取得します。 これは、使用状況の内部追跡用です。チャット名簿のサイズのみを確認し、他の情報は無視されます。 | はい、チャットのサイズが格納されます (1 つの整数) |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>EUII - アンケートが応答を取得し、コネクタを介して Teams に応答を送信しようとするたびに成功/失敗ログが作成され、このログには user_id、survey_id、integration_id が含まれます (データベース内で MS チーム ID、MS ユーザー ID の参照に使用できます)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>プライマリ データ センターは、NV のラスベガスにあり、セカンダリ データ センターはカリフォルニア州サンタ クララにあります。 SurveyMonkey は、これらの場所ですべてのサーバーとインフラストラクチャを所有および運用します。 また、特定の SurveyMonkey ユーザーがカナダにEnterpriseデータ常駐を利用できます。 すべてのデータは、TDE と AES256 を使用して保存時に暗号化され、転送中のデータは TLS 1.2 を使用して暗号化されます。

SurveyMonkey は、中央ユーザー認証を使用して ID とアクセス管理を維持します。 このシステムは、すべての企業、および運用インフラストラクチャ、システム、サービスに対するすべての認証と承認を管理します。 厳密なアクセス ポリシーは四半期ごとに維持およびレビューされます。 レビューには、ユーザー アクセス リスト、ポリシー グループ、サードパーティ アクセス レビューが含まれますが、これらに限定されない場合があります。 実稼働環境 (特権アカウントを取得する場合) にアクセスするには、管理者の承認を取得し、必要なトレーニングを多数完了し、セキュリティ チームの承認を得る必要があります。 その時点で、追加の VPN アカウントがプロビジョニングされ、通常の &#8216;&#8217; アカウントと&#8216;を&#8217;します。

会社が発行したデバイスだけが、実稼働ネットワークにアクセスできます。 すべてのワイヤレス ベンダーの既定値は、既定のワイヤレス暗号化キー、パスワード、および SNMP コミュニティ文字列など、インストール前に変更されます。 2FA と VPN は、リモートで行う必要があります。 弊社の企業オフィスには、ゲストアクセス用の個別の無線LAN ネットワークがあります。

すべてのサービス、プロトコル、および許可ポートには、セキュリティが保護されていないと見なされるプロトコルに実装されたセキュリティ機能の使用を含む、文書化されたビジネス上の正当性と承認が必要です。 ルーターとファイアウォールは、IP 漏えいを許可されていないまたは意図しない当事者に制限し、DMZ ファイアウォール内の IP アドレスへの受信インターネット アクセスを制限するように構成され、ルーター ルールセットは少なくとも 6 か月ごとに確認されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


