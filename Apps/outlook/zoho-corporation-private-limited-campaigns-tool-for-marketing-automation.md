---
title: Zoho Corporation Private Limited によるマーケティング自動化のための Zoho キャンペーン ツールのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: マーケティングの自動化、データ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報に関する Zoho Campaigns ツールで利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: e6107ce4526c7880253d52b6cecb0898c205f57e
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252908"
---
# <a name="zoho-campaigns-tool-for-marketing-automation"></a>マーケティング自動化のための Zoho キャンペーン ツール

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2019 年 12 月 16 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380835" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Zoho Corporation Private Limited to Microsoft から提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | マーケティング自動化のための Zoho キャンペーン ツール |
| ID | WA104380835 |
| Office 365サポートされているクライアント | Outlook 2013 以降の Mac Windows、Outlook 2016以降の Mac 上Outlook Web 上 |
| パートナー会社名 | Zoho Corporation Private Limited |
| パートナー Web サイトの URL | [https://www.zoho.com/](https://www.zoho.com/) |
| プライバシー ポリシーの URL | [https://zoho.com/privacy.html](https://zoho.com/privacy.html) |
| 利用規約の URL | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、Zoho Corporation Private Limited から、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | 委任 | カレンダー ID は、Zoho キャンペーンからその予定表にイベントを作成するために格納されます。 | ユーザーが Office365 カレンダー イベントを Zoho キャンペーンにインポートできます。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Calendars.ReadWrite | 委任 |  | ユーザーが Office365 カレンダーに Zoho キャンペーン イベントを追加できます。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.Read | 委任 |  連絡先情報を保存します。 | ユーザーが Office365 連絡先を Zoho キャンペーンにインポートできます。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | 委任 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | 委任 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | 委任 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| メール | 委任 | 電子メールは、ユーザー識別のために保存されます。 |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | 委任 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profile | 委任 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。



#### <a name="add-in-data-access"></a>アドイン のデータ アクセス

このアプリが組織のデータにアクセスするために必要なアクセス許可、このアクセス許可の正当性と目的 (アプリは何のためにこの情報を使用するのか)、およびアプリがデータベースにこの情報を格納するかどうかを一覧表示します。

>| **アクセス許可**  | **説明** |
>|:----------------|:----------------|
>| アイテムの読み取り | このアドインは、送信者名、受信者名、電子メール アドレス、メッセージ本文、添付ファイル情報など、アクティブなメッセージの個人情報にアクセスできます。 アドインは、このデータをサードパーティ のサービスに送信する場合があります。 メールボックス内の他のアイテムは&#8217;変更することはできません。 |
>| データの送信 | インターネットを使用してデータを送信できます |

#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>テレメトリとログでは EUII/PII は収集しない。 このようなデータが表示されている場合は、そのデータを修正するためのスクリプトを探し、警告するスクリプトが提供されています。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>お客様は、CERTAAT 制限付き EAR (保存時の暗号化) を使用して暗号化する必要があるデータを選択できます。パスワードは既定でハッシュ化されます。 サーバーへの論理的なアクセスは、分離された専用ネットワークを介して提供され &amp; 、高度にセキュリティで保護され、


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/28293' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/28293" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

