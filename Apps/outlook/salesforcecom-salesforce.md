---
title: salesforce.com 別の Salesforce のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Salesforce で利用可能なすべてのセキュリティ情報およびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリケーションカタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 29c00595a806c5144b34701ba54860353f9cafc0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553708"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2019年12月16日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

salesforce.com がマイクロソフトに提供した情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Salesforce |
| ID | WA104379334 |
| サポートされるクライアントOffice 365 | 2013 年以降Outlook、Windows、Outlook 2016 以降、Mac 上で、ウェブ上でOutlook |
| パートナー会社名 | salesforce.com |
| パートナーウェブサイトのURL | [https://www.salesforce.com/](https://www.salesforce.com/) |
| プライバシーポリシーの URL | [https://www.salesforce.com/company/privacy](https://www.salesforce.com/company/privacy) |
| 利用規約の URL | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474843361/Product_42949677285/Asset_540860c0-685e-4047-9f3a-082a748e57a2/LIGHTNINGFOROUTLOOKOrderFormSu.doc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法、およびアプリが収集するデータに対する組織の制御について、salesforce.com によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションは、マイクロソフトのGraphを使用していません。

#### <a name="data-access-using-other-microsoft-apis"></a>他のマイクロソフト API を使用したデータ アクセス

Microsoft 365上に構築されたアプリやアドインでは、Microsoft Graph 以外の Microsoft API を使用して、組織を識別できる情報 (OII) を収集または処理できます。 このアプリが使用するマイクロソフトGraph以外のマイクロソフト API を一覧表示します。

>| **API** |  **OIIは収集されますか?** |  **OIIは何を収集されますか?** | **OIIを収集するための正当性?** | **OII は保存されていますか?** | **OIIを格納するための正当性?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript API for Office | はい | アドインは、Office.jsと EWS の関数を使用して、ユーザーが Salesforce にログインすることを決定した電子メールに関するコンテンツと添付ファイルOutlookコピーします。 同様の機能は、Salesforce に予定を記録するために、カレンダー側で使用されます。 |  | アドインは、getUserIdentityTokenAsync などの関数を使用して、現在のOutlookユーザー ID を取得し、GetItem (.js と EWS) を取得して Salesforce レコードに保存する際に追加のプロパティと現在の電子メール メッセージの内容を設定し、GetAttachment (EWS) はExchangeから添付ファイルを取得し .js、ペアの Salesforce 電子メール .js .jsに追加します。 |  |
>| Exchange Web サービス (EWS) | はい | アドインは、Office.jsと EWS の関数を使用して、ユーザーが Salesforce にログインすることを決定した電子メールに関するコンテンツと添付ファイルOutlookコピーします。 同様の機能は、Salesforce に予定を記録するために、カレンダー側で使用されます。 |  | アドインは、getUserIdentityTokenAsync などの関数を使用して、現在のOutlookユーザー ID を取得し、GetItem (.js と EWS) を取得して Salesforce レコードに保存する際に追加のプロパティと現在の電子メール メッセージの内容を設定し、GetAttachment (EWS) はExchangeから添付ファイルを取得し .js、ペアの Salesforce 電子メール .js .jsに追加します。 |  |

#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>いいえ

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>Salesforce ストレージについては、セキュリティガイドの https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

