---
title: 開発者による InStation のアプリケーション情報 Invillia
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: InStation で利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1db56e204dc2fd83916a9ec6f2b20a13e02ed357
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/12/2021
ms.locfileid: "59286971"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 8 月 6 日</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

開発者 Invillia から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | InStation |
| ID | WA200001701 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Developers Invillia |
| パートナー Web サイトの URL | [https://invillia.com/](https://invillia.com/) |
| プライバシー ポリシーの URL | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| 利用規約の URL | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する開発者 Invillia によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| OnlineMeetings.Read.All | 委任 | stores: id、join_url、join_web_url、chat_id。 アプリで会議の作成を許可する | stores: id、join_url、join_web_url、chat_id。 アプリで会議の作成を許可する | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| OnlineMeetings.ReadWrite.All | 委任 | stores: id、join_url、join_web_url、chat_id。 アプリで会議の作成を許可する | stores: id、join_url、join_web_url、chat_id。 アプリで会議の作成を許可する | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| Presence.Read | 委任 | アプリが最初の手順で組織にログインすることを許可する | アクティビティと操作性。 アプリがユーザーの状態をキャプチャできます。 | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| Presence.Read.All | 委任 | アプリが最初の手順で組織にログインすることを許可します。 | アクティビティと操作性。 アプリがユーザーの状態をキャプチャできます。 | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| User.Read | 委任 | ストア: ID、メール、表示名、姓、画像。 アプリでユーザー データを検索できます。 | ストア: ID、メール、表示名、姓、画像。 アプリでユーザー データを検索できます。 | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| User.Read.All | 委任 | ストア: ID、メール、表示名、姓、画像。 アプリでユーザー データを検索できます。 | ストア: ID、メール、表示名、姓、画像。 アプリでユーザー データを検索できます。 | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| メール | 委任 | アプリが最初のログイン時に管理者&#180;基本情報を取得できます | アプリが最初のログイン時に管理者&#180;基本情報を取得できます | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| offline_access | 委任 | stores: トークンと更新トークン。 アプリが MS トークンで更新を実行できます | stores: トークンと更新トークン。 アプリが MS トークンで更新を実行できます | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| openid | 委任 | アプリが最初の手順で組織にログインすることを許可する | アプリが最初の手順で組織にログインすることを許可する | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |
>| profile | 委任 | アプリが最初のログインで管理者&#180;基本情報を取得できます。 | アプリが最初のログインで管理者&#180;基本情報を取得できます。 | [0c841985-9919-4c0a-b87d-b06b301148b3](https://docs.microsoft.com/microsoft-365-app-certification/azure/0c841985-9919-4c0a-b87d-b06b301148b3) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>ユーザー使用状況ログは、アプリケーション内にのみ保存されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>ユーザー使用状況ログは、アプリケーション内にのみ保存されます。 機密は何もありません。暗号化は必要とせず、特定の管理者だけがこのデータにアクセスできます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

