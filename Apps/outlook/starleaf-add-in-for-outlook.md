---
title: StarLeaf による StarLeaf アドインのアプリケーションOutlookアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Outlook の StarLeaf アドインで使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1ae18b1e6d9f89f0680c4b50e0e144851f052b0b
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252928"
---
# <a name="starleaf-add-in-for-outlook"></a>StarLeaf アドイン for Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 8 月 24 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381343" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

StarLeaf から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | StarLeaf アドイン for Outlook |
| ID | WA104381343 |
| Office 365サポートされているクライアント | Outlook 2013 以降の Mac Windows、Outlook 2016以降の Mac 上Outlook Web 上 |
| パートナー会社名 | StarLeaf |
| パートナー Web サイトの URL | [https://www.starleaf.com/](https://www.starleaf.com/) |
| プライバシー ポリシーの URL | [https://www.starleaf.com/privacy-policy](https://www.starleaf.com/privacy-policy) |
| 利用規約の URL | [https://support.starleaf.com/legal-information/end-user-lic...](https://support.starleaf.com/legal-information/end-user-license-agreement-for-starleaf-applications) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する StarLeaf によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | アプリケーション | 会議の iCalUId、会議の日時、出席者の電子メール アドレス、および Office.js カスタム プロパティ インターフェイスを使用して会議で読み書きする単一値拡張プロパティを格納します。 iCalUId は、ユーザーの outlook カレンダー内の会議を、&#8217;サービス上のビデオ会議と関連付ける場合に使用されます。 時間/日付と出席者は、サービス上の適切なユーザーに適切な時間にビデオ会議を提供するために使用されます。 SVEP は、O365 アドインと一緒に使用して、ユーザーが録画などのサービス上のビデオ会議に関する詳細を設定するインターフェイスを提供します。 | Webhook 通知を購読して、予定表内のイベントに対するユーザーの変更を追跡し、一貫性を保つためにサービスを更新するために使用されます。 また、ユーザーがアプリとやり取りし、Teamsサービスで会議をスケジュールするときに、予定表にイベントを作成するためにも使用されます。 | 6e86b349-768f-4953-ac2e-fb03f92db4be |
>| User.Read | アプリケーション | ログイン可能な oauth 更新トークンを格納します。 ユーザー プロファイル ID を保存して、そのユーザーからの将来の OAuth 試行と比較し、その詳細を 2 回&#8217;確認します。  | ユーザーがアプリにサインインし、アプリがユーザーの電子メール アドレス&#8217;を取得して、ログインとサービス上のアカウントを関連付けることができます。  | 6e86b349-768f-4953-ac2e-fb03f92db4be |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-------------------|:--------------------------|:--------------------------|
>| テクニカル サポートの問題が発生した場合、ケース管理のために組織データが SalesForce に転送される場合があります。 ユーザーが PSTN ダイヤルイン機能を使用する場合、通話は Twilio、Plivo、または Voxbone を経由して流れる |  | 該当なし |



#### <a name="add-in-data-access"></a>アドイン のデータ アクセス

このアプリが組織のデータにアクセスするために必要なアクセス許可、このアクセス許可の正当性と目的 (アプリは何のためにこの情報を使用するのか)、およびアプリがデータベースにこの情報を格納するかどうかを一覧表示します。

>| **アクセス許可**  | **説明** |
>|:----------------|:----------------|
>| ReadWrite アイテム | このアドインは、本文、件名、送信者、受信者、添付ファイル情報など、アクティブなメッセージ内の個人情報にアクセスして変更できます。 このデータは、サードパーティ のサービスに送信される場合があります。 メールボックス内の他のアイテムは&#8217;変更することはできません。 |
>| データの送信 | インターネットを使用してデータを送信できます |

#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>はい。 ログには、ユーザー名、IP アドレス、通話詳細レコード、接続品質 (パケット損失、ビットレート)、デバイスの種類、通話の進行状況に関する情報が含まれます。 この情報は、サービスの問題を診断するためにテクニカル サポート チームとシニア開発者が利用できます。 データは 90 日後に匿名化されます。 このデータを保護するためのコントロールは、ISO/IEC 27001 の認定を受け監査されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>データは、ユーザー&#8217;のアカウントが格納されているデータ センター内の StarLeaf&#8217;独自のログ サーバーに格納され、同じ管轄内の 1 つ以上のデータ センターにバックアップされます。 データへのアクセスは、強度チェックされたユーザーごとのパスワードを使用する個々のユーザー アカウントによって行います。 StarLeaf&#8217;サービス ユーザー アカウントは、人事システムと企業の Active Directory グループに対して自動的に監査され、異常が見つかった場合はセキュリティとコンプライアンス チームに警告します。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35997" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

