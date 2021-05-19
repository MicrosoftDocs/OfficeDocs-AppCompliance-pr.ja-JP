---
title: ダーダック・シグネル4によるSIGNL4のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: SIGNL4、データ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STARレジストリ内のセキュリティ/コンプライアンス情報に関する、利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a619327000c93e3292e266c8b025034370a8b623
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553208"
---
# <a name="signl4"></a>SIGNL4

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年8月6日</p>

* <a href="https://teams.microsoft.com/l/app/bd19c878-00b7-47cd-9b65-74a2def84427" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001239" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

デルダック・シグネル4がマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | SIGNL4 |
| ID | WA200001239 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Derdack SIGNL4 |
| パートナーウェブサイトのURL | [https://www.signl4.com](https://www.signl4.com) |
| プライバシーポリシーの URL | [https://www.signl4.com/privacy-policy/](https://www.signl4.com/privacy-policy/) |
| 利用規約の URL | [https://www.signl4.com/terms_of_use/](https://www.signl4.com/terms_of_use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法、およびアプリが収集するデータに対する組織のコントロールに関する Derdack SIGNL4 によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションは、マイクロソフトのGraphを使用していません。


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>| **すべての非Microsoft サービス OII は、** |  **どのようなOIIが転送されますか?** | **OIIを転送するための正当性?** |
>|:-------------------|:--------------------------|:--------------------------|
>| 繰り返し、電子メールアドレス、電子メールアドレスは、彼がアプリを使用しているときに顧客に請求通知を送信するために必要とされます。 Twilio, 電話番号, テキストメッセージを介してアラートを送信するための警告コンテンツ携帯ショートメール |  | Azure 管理 API、Azure モニター アラートが収集され、システムがアラートの通知を送信するため、収集が行われます。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>電子メール アドレス情報はログに含まれています。 また、組織が送信する追加のアラート・コンテンツ・データがログに含まれる場合があります。 これを防ぐために、組織はアプリでアカウントを終了できます。
ログのデータは、お客様がアプリで抱えている問題のサポートとトラブルシューティングに必要です。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>データはヨーロッパの Azure データ センターに格納されます。 管理者はアクセス可能です。 AAD 認証を使用した 2FA。 ストレージ アカウントへのアクセス キーは、アクセスを管理するためにも使用されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35955' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35955" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

