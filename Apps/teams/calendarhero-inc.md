---
title: カレンダーヒーローのアプリケーション情報(株式会社カレンダヒーロー)
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: CalendarHero、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、およびCSA STARレジストリ内のセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d27858000c591c320cfadc301ea16ddf2fac89bd
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553333"
---
# <a name="calendarhero"></a>カレンダーヒーロー

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年3月17日</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

マイクロソフトにカレンダーヒーロー社によって提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | カレンダーヒーロー |
| ID | WA200000150 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | 株式会社カレンダーヒーロー |
| パートナーウェブサイトのURL | [https://calendarhero.com](https://calendarhero.com) |
| アプリケーション情報ページTeams URL | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| プライバシーポリシーの URL | [https://calendarhero.com/privacy](https://calendarhero.com/privacy) |
| 利用規約の URL | [https://calendarhero.com/terms-of-use](https://calendarhero.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法と、アプリが収集するデータに対する組織のコントロールに関するカレンダーヒーロー社によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 両方とも | 会議は Azure の mongoDB にキャッシュされますが、説明は暗号化されています。 | ユーザーのカレンダーイベントへのアクセス。 |  |
>| Contacts.ReadWrite | 両方とも | 連絡先の名前と電子メール アドレス。 | ユーザーの連絡先を読み取ります (会議に招待できるようにします)。 |  |
>| Group.Read.All | 両方とも | グループ名とメンバー。 | (オプション)企業ユーザーグループを読み取る(グループを使用してスケジュールする場合)。 |  |
>| Mail.Read | 両方とも | 連絡先の電子メール/名前、相互作用の頻度/最新性。 | (省略可能) は、(Machine Learning経由で) ユーザーの最も重要な連絡先が誰であるかに電子メール のメタ データを読み取るために使用されます。 |  |
>| MailboxSettings.ReadWrite | 両方とも | ユーザーのタイムゾーン。 | ユーザーのタイムゾーン。 |  |
>| User.Read.All | 両方とも | ユーザーの名前の &amp; 電子メール (連絡先として保存されます)。 | (オプション)企業ユーザーの読み取り(同僚とのスケジューリング用) |  |
>| offline_access | アプリケーション | いいえ | ユーザーが存在することなく、いつでもバックエンドを通じて読み書きする必要があります。 |  |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 会議アシスタントボットが同僚とのミーティングをスケジュールできるように、同僚の名前/電子メールをインポートする | &amp;電子メールに名前を付けます。 どちらも、クイックルックアップと部分的な名前の検索のためにデータベースに格納されています(例えば. ジョーPと会う) |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>ユーザーや連絡先のメールアドレスは、ログプロバイダであるLogDNAにイベントを記録するために使用されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>すべてのデータは、カナダのケベックシティにあるMS Azureクラウドデータセンターに保存されます。 いくつかのフィールドは AES256 で暗号化されます。 データベースへのアクセスは、エンジニアとバックエンド サーバーがユーザー/サービス レベルの資格情報を使用してのみ利用できます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

