---
title: Salesforce のアプリケーション情報 :salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Salesforce で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 88e6a4913e3a3c85ea76fd58c1a724f957c9a3e6
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095885"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2019 年 12 月 16 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Microsoft に提供される salesforce.com 情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Salesforce |
| ID | WA104379334 |
| Office 365サポートされているクライアント | Outlook 2013 以降の Mac Windows、Outlook 2016以降の Mac 上Outlook Web 上 |
| パートナー会社名 | salesforce.com |
| パートナー Web サイトの URL | [https://www.salesforce.com/](https://www.salesforce.com/) |
| プライバシー ポリシーの URL | [https://www.salesforce.com/company/privacy](https://www.salesforce.com/company/privacy) |
| 利用規約の URL | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474843361/Product_42949677285/Asset_540860c0-685e-4047-9f3a-082a748e57a2/LIGHTNINGFOROUTLOOKOrderFormSu.doc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリ salesforce.com 収集および保存する方法、およびアプリが収集するデータに対して組織が持つコントロールに関する情報を提供しています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft アプリケーションをGraph。

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript API for Office | はい | このアドインは、Office.js および EWS の関数を使用して、ユーザーが Salesforce にログインすることを決定した電子メールに関するOutlook添付ファイルをコピーします。 予定表側でも同様の機能を使用して、予定を Salesforce に記録します。 |  | アドインは getUserIdentityTokenAsync のような関数を使用して、現在のユーザー id をOutlook取得します。 GetItem (.js と EWS) を使用して、Salesforce レコードに保存する場合の AdditionalProperties と現在の電子メール メッセージの内容を設定し、getAttachment (EWS) を使用して、Exchange から添付ファイルを取得し、ペアの Salesforce 電子メール UpdateItem (.js)、GetFolder (.js) に追加して下書きメッセージを作成するために使用する下書きフォルダー CreateItem (.js) を取得します。 |  |
>| Exchange Web サービス (EWS) | はい | このアドインは、Office.js および EWS の関数を使用して、ユーザーが Salesforce にログインすることを決定した電子メールに関するOutlook添付ファイルをコピーします。 予定表側でも同様の機能を使用して、予定を Salesforce に記録します。 |  | アドインは getUserIdentityTokenAsync のような関数を使用して、現在のユーザー id をOutlook取得します。 GetItem (.js と EWS) を使用して、Salesforce レコードに保存する場合の AdditionalProperties と現在の電子メール メッセージの内容を設定し、getAttachment (EWS) を使用して、Exchange から添付ファイルを取得し、ペアの Salesforce 電子メール UpdateItem (.js)、GetFolder (.js) に追加して下書きメッセージを作成するために使用する下書きフォルダー CreateItem (.js) を取得します。 |  |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。



#### <a name="add-in-data-access"></a>アドイン のデータ アクセス

このアプリが組織のデータにアクセスするために必要なアクセス許可、このアクセス許可の正当性と目的 (アプリは何のためにこの情報を使用するのか)、およびアプリがデータベースにこの情報を格納するかどうかを一覧表示します。

>| **アクセス許可**  | **説明** |
>|:----------------|:----------------|
>| ReadWrite メールボックス | このアドインは、メールボックス内の任意のアイテムの内容を読み取りまたは変更し、新しいアイテムを作成できます。 任意のメッセージまたは予定表アイテムの本文、件名、送信者、受信者、添付ファイルなどの個人情報にアクセスできます。 このデータは、サードパーティ のサービスに送信される場合があります。 |
>| データの送信 | インターネットを使用してデータを送信できます |

#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>いいえ

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>Salesforce ストレージについては、「セキュリティ ガイド」で説明されています。 https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

