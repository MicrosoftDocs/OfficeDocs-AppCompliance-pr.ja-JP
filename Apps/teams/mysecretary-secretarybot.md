---
title: 秘書ボットの申請情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: セカテクボットの利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、およびCSA STARレジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: bff3e6ebffc94861dc4112375ac943124b4fe386
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551887"
---
# <a name="secretarybot"></a>SecretaryBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381085" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

マイクロソフトに私の秘書によって提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | SecretaryBot |
| ID | WA104381085 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | MySecretary |
| パートナーウェブサイトのURL | [https://secretarybot.wordpress.com/](https://secretarybot.wordpress.com/) |
| アプリケーション情報ページTeams URL | [https://secretarybot.wordpress.com/faq/](https://secretarybot.wordpress.com/faq/) |
| プライバシーポリシーの URL | [https://secretarybot.wordpress.com/privacy-policy/](https://secretarybot.wordpress.com/privacy-policy/) |
| 利用規約の URL | [https://secretarybot.wordpress.com/terms-of-use/](https://secretarybot.wordpress.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法と、アプリが収集するデータに対する組織のコントロールについて My秘書によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read.Shared | 委任 |  | ユーザーと同僚の空き時間情報を取得します。 |  |
>| Calendars.ReadWrite | 委任 |  | ユーザーの代わりに会議出席依頼を送信します。 |  |
>| MailboxSettings.Read | 委任 | 正しいラングージを表示するためのストアの言語。 MS Graphカレンダー API を正しく呼び出すためにタイムゾーンを保存します。 | ユーザーの言語とタイムゾーンの設定を取得します。 |  |
>| People.Read | 委任 |  | ユーザーとの関係が強い同僚を探してみてください。 |  |
>| User.Read | 委任 | ユーザー分析用のユーザー名、都市、国、および言語を格納します。 顧客に連絡するための電子メールを保存します。 私たちは、電子メールアドレスを使用したことがありませんが、サポートのために使用することができます。 | ユーザーの国と優先言語を検索してみてください。 これは、メールボックス設定のバックアップに使用されます。 |  |
>| メール | 委任 | 上記を参照してください。 | 電子メールを保存します。 |  |
>| openid | 委任 |  | OpenID 認証の場合。 |  |
>| profile | 委任 | MS ID システムでユーザーの一意の ID を識別するための OID を保存します。 | ユーザー名と OID を取得しています。 今後、アドインOutlook接続するために OID を使用してみてください。 |  |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| チームミーティングのスケジュールにこのインフロメンテーションを使用します | いいえ |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>OII または EUII データは、テレメトリまたはログに表示されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>エンドユーザーに対して管理制御はまだ提供されていませんが、エンドユーザーからデータの削除を要求された場合は、その要求に従うことができます。


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

