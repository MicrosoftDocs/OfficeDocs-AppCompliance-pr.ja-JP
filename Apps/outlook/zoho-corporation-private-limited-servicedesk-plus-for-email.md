---
title: 株式会社ゾー氏によるメール用サービスデスクプラスのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: ServiceDesk Plus for Emailの利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Securityアプリカタログ情報、CSA STARレジストリのセキュリティ/コンプライアンス情報
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: dc342375eba7084f5afb31b0f879e46e959fa970
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553658"
---
# <a name="servicedesk-plus-for-email"></a>メール用サービスデスクプラス

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2019年12月16日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381518" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Zohoコーポレーションプライベートリミテッドがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | メール用サービスデスクプラス |
| ID | WA104381518 |
| サポートされるクライアントOffice 365 | 2013 年以降Outlook、Windows、Outlook 2016 以降、Mac 上で、ウェブ上でOutlook |
| パートナー会社名 | Zoho Corporation Private Limited |
| パートナーウェブサイトのURL | [https://www.zoho.com/](https://www.zoho.com/) |
| プライバシーポリシーの URL | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
| 利用規約の URL | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;オンクト=エン・US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対する組織のコントロールについてZoho Corporation Private Limitedによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | アプリケーション |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | 委任 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | 委任 |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | 委任 | ユーザーの電子メール ID。 | ユーザーがサインインできるようにし、アプリに UPN へのアクセス権を付与して、サイレント ログインを有効にします。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | アプリケーション |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | 委任 | 電子メール ID、名前、従業員 ID、役職、電話、モバイル、サイト、部門、ロケール、ユーザーのプロファイル写真。 | Azure Active Directoryからユーザーの基本情報をインポートできます。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| メール | 委任 | ユーザーの電子メール ID。 | ユーザーの電子メール アドレスを表示します。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | 委任 |  | アクセス権を与えたデータへのアクセスを維持する。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profile | 委任 |  | ユーザーの基本プロファイルを表示します。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>テレメトリ/ログでEUII / PIIを収集しません。 私たちは、パターンを探し、それを修正するためのアラートを配置しています

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>すべてのデータは REST で暗号化されます。 権限のある人だけが、アクセスが保護されたシステムにアクセスし、すべてのタイプのアクセスについて完全に監査されます。 アクセス用の MFA、承認されたアカウントは、企業のディレクトリとホストに維持されます。


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

