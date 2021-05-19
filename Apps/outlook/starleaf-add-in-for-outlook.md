---
title: スターリーフによるOutlook用の StarLeaf アドインのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Outlook用の StarLeaf アドイン、そのデータ処理ポリシー、Microsoft Cloud App Securityアプリカタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関する利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f201131be32c743550a02a24e653f784a1d91817
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552478"
---
# <a name="starleaf-add-in-for-outlook"></a>スターリーフ アドイン (Outlook用)

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年8月24日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381343" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

スターリーフがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | スターリーフ アドイン (Outlook用) |
| ID | WA104381343 |
| サポートされるクライアントOffice 365 | 2013 年以降Outlook、Windows、Outlook 2016 以降、Mac 上で、ウェブ上でOutlook |
| パートナー会社名 | StarLeaf |
| パートナーウェブサイトのURL | [https://www.starleaf.com/](https://www.starleaf.com/) |
| プライバシーポリシーの URL | [https://www.starleaf.com/privacy-policy](https://www.starleaf.com/privacy-policy) |
| 利用規約の URL | [https://support.starleaf.com/legal-information/end-user-lic...](https://support.starleaf.com/legal-information/end-user-license-agreement-for-starleaf-applications) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法と、アプリが収集するデータに対する組織のコントロールに関する StarLeaf によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | アプリケーション | 会議の iCalUId、会議の時刻/日付、出席者の電子メール アドレス、およびOffice.jsカスタム プロパティ インターフェイスを使用して、会議で読み書きする単一値拡張プロパティを格納します。 iCalUId は、ユーザーの outlook 予定表&#8217;の会議を、サービスのビデオ 会議と関連付けるために使用されます。 時刻/日付と出席者は、適切なタイミングで、適切な時間にビデオ会議を提供するために使用されます。 SVEPは、録画などのサービスでビデオ会議の詳細を設定するためのインターフェイスをユーザーに提供するために、当社のO365アドインに使用されます。 | カレンダー内のイベントに対するユーザーの変更を追跡し、一貫性を保つためにサービスを更新するために、Webhook通知を購読するために使用されます。 また、ユーザーがTeamsアプリと対話し、サービスで会議をスケジュールするときに、カレンダーにイベントを作成するためにも使用されます。 | 6e86b349-768f-4953-ac2e-fb03f92db4be |
>| User.Read | アプリケーション | ログインできるように oauth 更新トークンを保存します。 ユーザープロファイル ID は、そのユーザーからの今後の OAuth 試行と比較できるように保存し、そのユーザーの詳細を2回保存&#8217;しないようにします。  | ユーザーがアプリにサインインできるようにし、ユーザーが自分のログインをサービスのアカウントに関連付けるために、ユーザー&#8217;電子メール アドレスを取得できます。  | 6e86b349-768f-4953-ac2e-fb03f92db4be |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>| **すべての非Microsoft サービス OII は、** |  **どのようなOIIが転送されますか?** | **OIIを転送するための正当性?** |
>|:-------------------|:--------------------------|:--------------------------|
>| テクニカルサポートの問題が発生した場合、組織データはケース管理のために SalesForce に転送される可能性があります。 ユーザーが PSTN ダイヤルイン機能を使用すると、コールは Twilio、プリボ、または Voxbone を経由します。 |  | 該当なし |



#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>はい。 ログには、ユーザ名、IP アドレス、コール詳細レコード、接続品質(パケット損失、ビットレート)、デバイスタイプ、コールの進行状況に関する情報が含まれます。 この情報は、テクニカル サポート チームおよび上級開発者がサービスの問題を診断するために利用できます。 データは90日後に匿名化されます。 このデータを保護するための管理は、ISO/IEC 27001認証の下で監査されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>データは、ユーザー&#8217;のアカウントが配置されているデータセンターのStarLeaf&#8217;独自のログサーバーに保存され、同じ管轄内の1つまたは複数のデータセンターにバックアップされます。 データへのアクセスは、強度チェックされているユーザーごとのパスワードを使用して、個々のユーザーアカウントによって行われます。 StarLeaf&#8217;サービスユーザーアカウントは、HRシステムと企業のActive Directoryグループに対して自動的に監査され、異常が見つかった場合はセキュリティとコンプライアンスチームに警告します。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

