---
title: サーベイモンキーによるサーベイモンキーのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: SurveyMonkey、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、およびCSA STARレジストリ内のセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 57ba8ed84e0d9ea4101ea82ed5d92aef1f634ed1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552728"
---
# <a name="surveymonkey"></a>SurveyMonkey

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/0fd925a0-357f-4d25-8456-b3022aaa41a9" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381088" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

サーベイモンキーがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | SurveyMonkey |
| ID | WA104381088 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | SurveyMonkey |
| パートナーウェブサイトのURL | [https://www.surveymonkey.com](https://www.surveymonkey.com) |
| アプリケーション情報ページTeams URL | [https://help.surveymonkey.com/articles/en_US/kb/Microsoft-T...](https://help.surveymonkey.com/articles/en_US/kb/Microsoft-Teams-Integration) |
| プライバシーポリシーの URL | [https://www.surveymonkey.com/privacy](https://www.surveymonkey.com/privacy) |
| 利用規約の URL | [https://www.surveymonkey.com/mp/policy/terms-of-use/](https://www.surveymonkey.com/mp/policy/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法と、アプリが収集するデータに対する組織のコントロールについて SurveyMonkey によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | 委任 | いいえ | アンケートを共有するグループ/チャネルのリストを提供するには |  |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>| **すべての非Microsoft サービス OII は、** |  **どのようなOIIが転送されますか?** | **OIIを転送するための正当性?** |
>|:-------------------|:--------------------------|:--------------------------|
>| チーム ユーザーに回答とアンケートを関連付けるために、SurveyMonkey に MS ユーザー ID のみが保存されます。 |  | チームの場合は、Microsoft Teams javascript SDK を作成、調査結果、アンケート結果タスク モジュールモーダルで使用します。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| v3/会話/{id}/pagedmembers に電話をかけ、アプリがチームに追加され、メンバー数を取得することを確認します。 これは、使用の内部追跡のためであり、我々はチャット名簿のサイズを見るだけ、他の情報は無視されます。 | はい、チャットのサイズは格納されます(単一の整数) |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>EUII - アンケートが回答を受け取るたびに成功/失敗ログが作成され、その回答をコネクタ経由でTeamsに送信しようとすると、このログにはuser_id、survey_id、integration_idが含まれます(データベース内ではMSチームID、MSユーザーIDを検索できます)。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>当社のプライマリデータセンターは、ラスベガス、NVに位置し、セカンダリデータセンターは、サンタクララ、カリフォルニア州にあります。 SurveyMonkey は、これらの場所ですべてのサーバーとインフラストラクチャを所有および運用しています。 また、カナダにある特定のSurveyMonkey Enterpriseのお客様にもカナダのデータ居住地があります。 すべてのデータは、AES256 を使用して TDE を使用して保管時に暗号化され、転送中のデータは TLS 1.2 を使用して暗号化されます。

サーベイモンキーは、アイデンティティとアクセス管理を維持するために、中央ユーザ認証を使用します。 このシステムは、企業、および本番インフラストラクチャ、システム、サービスに対するすべての認証と承認を管理します。 厳格なアクセス ポリシーは四半期ごとに維持され、見直されます。 レビューには、ユーザー アクセス リスト、ポリシー グループ、サード パーティアクセス レビューなどがありますが、これらに限定されません。 運用環境にアクセスするには (特権アカウントを取得するため)、管理者の承認を得て、必要なトレーニングを多数完了し、セキュリティ チームの承認を得る必要があります。 その時点で、追加の VPN アカウントがプロビジョニングされ、通常の&#8217; アカウントと&#8216;特権&#8217; アカウント&#8216;区別されます。

会社が発行したデバイスのみが、当社の本番ネットワークにアクセスできます。 インストール前に、デフォルトのワイヤレス暗号化キー、パスワード、SNMP コミュニティストリングなど、すべてのワイヤレスベンダーのデフォルトが変更されます。 2FAとVPNはリモートで行う必要があります。 当社は、当社のオフィスでゲストアクセスのための別の無線LANネットワークを持っています。

すべてのサービス、プロトコル、および許可されたポートには、セキュリティ保護されていないプロトコルに実装されたセキュリティ機能の使用を含め、文書化されたビジネス上の正当性と承認が必要です。 ルーターとファイアウォールは、IP の公開を無許可または意図しない当事者に制限し、DMZ ファイアウォール内の IP アドレスへのインバウンド インターネット アクセスを制限するように構成され、ルーター ルールセットは少なくとも 6 か月ごとに確認されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12024" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

