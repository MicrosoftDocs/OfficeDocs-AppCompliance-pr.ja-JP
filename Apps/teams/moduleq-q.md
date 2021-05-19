---
title: モジュールQ別Qのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Q に関する利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3424ac372f46be0fc9834611fb1a0d57c69831a4
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551907"
---
# <a name="q"></a>Q

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年3月17日</p>

* <a href="https://teams.microsoft.com/l/app/72bb25c7-3644-4318-8249-a08e5493a520" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381433" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

モジュールQがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Q |
| ID | WA104381433 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | ModuleQ |
| パートナーウェブサイトのURL | [https://moduleq.com](https://moduleq.com) |
| プライバシーポリシーの URL | [https://moduleq.com/privacy-policy/](https://moduleq.com/privacy-policy/) |
| 利用規約の URL | [https://moduleq.com/terms-of-service/](https://moduleq.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法、およびアプリが収集するデータに対する組織のコントロールに関する ModuleQ によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | アプリケーション | メッセージ本文と添付ファイルを除く、会議データを格納します。 | アプリケーションは、ユーザーのビジネスの優先順位をインテリジェントに理解するために、ユーザーのカレンダー イベントを読み取ることができます。 | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Group.Read.All | 委任 | なし | アプリがチーム内でコンテンツを共有するために対話できるようにします。 | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Mail.Read | アプリケーション | メッセージ本文と添付ファイルを除く、電子メールデータを保存します。 | アプリケーションがユーザーのビジネスの優先順位をインテリジェントに理解するためにユーザーのメールを読み取ることができます。 | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read | 委任 | ユーザーの電子メールと認証トークン | ユーザーがサインインし、自分のOffice 365アカウントをModuleQアカウントにリンクすることを許可します | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read.All | 委任 | なし | ユーザーが参加しているTeamsの一覧をアプリが取得できるようにします。 共有にのみ使用  | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>内部ユーザーの GUID と組織名とドメインをログに記録します。 現時点では、アーカイブや削除の制御はありません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>データは、その機能に従って、複数のマイクロサービスにわたってMicrosoft Azureクラウドに格納されます。 ユーザーを特定できるデータはすべて、ストレージ用に送信する前に、AES-256 暗号化を使用してクライアント側で暗号化されます。 データは、当社の上級管理職の承認を得て、デバッグ目的でエンジニアによって閲覧される場合があります。 データへのアクセスは、内部 VPN を介して制御されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

