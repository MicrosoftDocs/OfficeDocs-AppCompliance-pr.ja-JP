---
title: monday.com 別 monday.com のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: monday.com、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STARレジストリ内のセキュリティ/コンプライアンス情報に関する、利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 64fc8e948618b760a3f82ee9c1ac67a32de9afb6
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552928"
---
# <a name="mondaycom"></a>monday.com

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年9月28日</p>

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

monday.com がマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | monday.com |
| ID | WA200001798 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | monday.com |
| パートナーウェブサイトのURL | [https://monday.com](https://monday.com) |
| プライバシーポリシーの URL | [https://monday.com/privacy](https://monday.com/privacy) |
| 利用規約の URL | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法、およびアプリが収集するデータに対する組織の制御方法に関する monday.com によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションは、マイクロソフトのGraphを使用していません。


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>| **すべての非Microsoft サービス OII は、** |  **どのようなOIIが転送されますか?** | **OIIを転送するための正当性?** |
>|:-------------------|:--------------------------|:--------------------------|
>| monday.com は、サービスのパフォーマンスに次のサブプロセッサを使用します &#160;。 https://monday.com/terms/subprocessors |  | monday.com API は使用しません。 当社は、サービスのパフォーマンスに次のマイクロソフトフレームワークを使用しています (上記の応答で詳述されているように): &#8216;ボットビルダー&#8217; &#8216;ボットフレームワークコネクタ&#8217; &#8216;@micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>monday.com は、R &amp; D 担当者がバグやユーザーから報告された問題のトラブルシューティングを行えるように、ユーザーが生成したコンテンツを一定期間保存します。 IP アドレスを含むセキュリティ ログは、データ保持ポリシーに従って、より長い期間保持されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>monday.com サービスは、複数のアベイラビリティーゾーンにわたって北バージニアの AWS インフラストラクチャでホストされ、DR サイトは別のリージョンに設置されています。 特定のバックアップ データは GCP(米国、複数リージョン)に格納されます。 monday.com サービスへのアクセスは、ユーザー組織の管理者によって制御され、次の機能を利用して実現されます。
- ユーザーの種類
- アカウント レベルのアクセス許可
- Workspaces
- ボードタイプ
- ボードレベルの権限
- 列レベルのアクセス許可 monday.com、次の認証方法をサポートします。
- 資格情報
- グーグルSSO(Proプラン用)
- Okta、OneLogin、カスタム SAML 2.0 (Enterprise プランの場合) 2FA は、携帯ショートメールを介して、または認証アプリを介して、プラットフォームの管理者パネルを介してアカウント管理者によってオプションで有効にすることができます。
保存しているデータはすべて AES-256 を使用して暗号化されます。 オープンネットワークを介して転送されるすべてのデータは、TLS 1.3(TLS 1.2)を使用して暗号化されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

