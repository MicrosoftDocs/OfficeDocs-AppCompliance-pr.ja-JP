---
title: iGlobe による Office 365 プランナーの iPlanner レポート ツールのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Office 365プランナーのiPlannerレポートツール、そのデータ処理ポリシー、Microsoft Cloud App Securityアプリカタログ情報、CSA STARレジストリのセキュリティ/コンプライアンス情報に関する、利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a577fcc75982703bfae0de740a7e69d9d13e509a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548767"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>Office 365プランナー用のiPlannerレポートツール

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者による最終更新日: 2019年12月16日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

iGlobe がマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Office 365プランナー用のiPlannerレポートツール |
| ID | WA104380686 |
| サポートされるクライアントOffice 365 | mac 上のWindows、Excel on the web、Excel 2016以降のExcel 2016 |
| パートナー会社名 | iGlobe |
| パートナーウェブサイトのURL | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| プライバシーポリシーの URL | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| 利用規約の URL | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474836912/Product_42949680354/Asset_9d620695-979f-49e4-bc56-98259b0cdeb2/EULAPlanner.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法、およびアプリが収集するデータに対する組織のコントロールに関する情報を iGlobe によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 委任 | アプリケーション データベースにはデータは格納されません。 | ユーザーのカレンダーにカレンダーエントリを作成するには、タスクの期限にカレンダーを&#8217;。 |  |
>| Directory.AccessAsUser.All | 委任 | アプリケーション データベースにはデータは格納されません。 | ユーザーが同意を得て、API を使用するアクセス権を持っていることを確認する。 |  |
>| Directory.ReadWrite.All | 委任 | アプリケーション データベースにはデータは格納されません。 | プランナータスクをOutlook To Doするには、フラグを設定してメールを更新します。 新しいプランナー タスクを作成します。 |  |
>| Files.ReadWrite.All | 委任 | アプリケーション データベースにはデータは格納されません。 | 添付ファイルとしてファイルにアクセスし、タスクにファイルをアップロードします。 |  |
>| Group.Read.All | 委任 | アプリケーション データベースにはデータは格納されません。 | プランリストを取得し、タスクを更新します。 |  |
>| Group.ReadWrite.All | 委任 | アプリケーション データベースにはデータは格納されません。 | プランナータスクを取得し、新しいタスクを追加するには、バケットとスイムラインを更新します。 |  |
>| Mail.Read | 委任 | アプリケーション データベースにはデータは格納されません。 | User.Read、プランナータスクを取得するには、Outlook To Do、フラグを立てた電子メールとそれらを更新します。 新しいプランナー タスクを作成するには |  |
>| Mail.ReadWrite | 委任 | アプリケーション データベースにはデータは格納されません。 | メールを表示し、メールを送信します。 |  |
>| メール.読み取り書き込み.すべて | 委任 | アプリケーション データベースにはデータは格納されません。 | 選択したメールからメールの件名を取得します。 アプリが選択した電子メールから情報を取得できるようにして、タスクの説明に説明フィールドをコピーし、メールまたはメール自体からタスクに添付ファイルを保存できるようにします。 通知を送信します。 |  |
>| Tasks.ReadWrite | 委任 | アプリケーション データベースにはデータは格納されません。 | サインインしたユーザーをOutlook To Doし、User.Read を更新するには、プランナータスクをOutlook To Doし、メールにフラグを設定して更新します。 新しいプランナー タスクを作成します。 |  |
>| User.Read | 委任 | アプリケーション データベースにはデータは格納されません。 | サインインおよびユーザー プロファイルの読み取り |  |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>iGlobeは、効果的に動作し、あなたに当社の製品やサービスで最高の体験を提供するためにデータを収集します。 ライセンスの場合: 無料のアドインを展開する場合、試用版サブスクリプションを作成したりサブスクリプションを購入したりする場合など、組織&#8217;のライセンス アカウントを管理するために収集されたデータ。 以下の情報が収集されます。 
- 財務上の目的: 会社名と住所
- 登録ユーザー: ユーザー名とメール

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>すべてのデータは、顧客自身のテナントに含まれます。 アプリケーション データは格納されません。 最新のアドインは、プロセス&#8221;から&#8220;、サンドボックス 化されたブラウザーで実行されます。 Microsoft サービスを使用してユーザーデータと対話します。 アドインは、ユーザーが作業しているデータにのみアクセスできます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

