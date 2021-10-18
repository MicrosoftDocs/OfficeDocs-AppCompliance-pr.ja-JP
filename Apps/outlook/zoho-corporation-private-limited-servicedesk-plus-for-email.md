---
title: Zoho Corporation Private Limited による ServiceDesk Plus for Email のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 09/04/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: ServiceDesk Plus for Email、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報に関する利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0ccf0b8f7a17077bbf468369779e70335ac8e7e5
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60439268"
---
# <a name="servicedesk-plus-for-email"></a>電子メール用 ServiceDesk Plus

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2019 年 12 月 16 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381518" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Zoho Corporation Private Limited to Microsoft から提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | 電子メール用 ServiceDesk Plus |
| ID | WA104381518 |
| Office 365サポートされているクライアント | Outlook 2013 以降の Mac Windows、Outlook 2016以降の場合は、Outlook on the web |
| パートナー会社名 | Zoho Corporation Private Limited |
| パートナー Web サイトの URL | [https://www.manageengine.com/products/service-desk](https://www.manageengine.com/products/service-desk) |
| プライバシー ポリシーの URL | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
| 利用規約の URL | [https://ondemand.manageengine.com/terms.html](https://ondemand.manageengine.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、Zoho Corporation Private Limited から、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | アプリケーション |  |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Files.Read | 委任 |  |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Files.Read.Selected | 委任 |  |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| User.Read | 委任 | ユーザーの電子メール ID。 | ユーザーがサインインし、アプリに UPN へのアクセス権を与え、サイレント ログインを有効にできます。 | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| User.Read.All | アプリケーション |  |  | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| User.ReadBasic.All | 委任 | メール ID、名前、従業員 ID、役職、電話、モバイル、サイト、部署、ロケール、ユーザーのプロファイル写真。 | ユーザーの基本情報をユーザーからインポートAzure Active Directory。 | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| メール | 委任 | ユーザーの電子メール ID。 | ユーザーのメール アドレスを表示します。 | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| offline_access | 委任 |  | アクセス権を与えられたデータへのアクセスを維持します。 | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| profile | 委任 |  | ユーザーの基本的なプロファイルを表示します。 | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>テレメトリ/ログで EUII/PII を収集する必要があります。 パターンを探し、それを修正するための警告を表示するスクリプトが配置されています

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>すべてのデータは REST で暗号化されます。 すべての種類のアクセスに対して完全に監査された、アクセスが保護されているシステムにアクセスできるのは、承認されたユーザーのみです。 アクセス用に MFA を設定すると、承認済みアカウントは企業ディレクトリとホストに保持されます


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

