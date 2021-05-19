---
title: 株式会社ゾーホーCRMの申請情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Zoho CRM の利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5448307eeccd20e77b25282f299b52b094077b82
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550507"
---
# <a name="zoho-crm"></a>Zoho CRM

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/003a8a54-9d27-41cd-9c28-aec5875a3497" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382094" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Zoho株式会社 Pvt Ltdがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Zoho CRM |
| ID | WA104382094 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Zoho Corporation Pvt Ltd |
| パートナーウェブサイトのURL | [https://www.zoho.com/](https://www.zoho.com/) |
| アプリケーション情報ページTeams URL | [https://www.zoho.com/crm/help/microsoft-teams-integration.h...](https://www.zoho.com/crm/help/microsoft-teams-integration.html) |
| プライバシーポリシーの URL | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| 利用規約の URL | [https://www.zoho.com/crm/zohocrm-terms.html](https://www.zoho.com/crm/zohocrm-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが収集し、組織のデータを格納する方法と、アプリが収集するデータに対する組織の制御についてZoho Corporation Pvt Ltdによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 委任 | 予定表フォルダー ID は、Zoho CRM から Microsoft に Microsoft の連絡先を同期するために格納されます &amp; 。 event_name、event_location、participant_detailsなどのカレンダー情報が保存されます。 | ユーザーが Office365 イベントを Zoho CRM と同期できるようにします。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | 委任 | 連絡先フォルダー ID は、Zoho CRM から Microsoft に Microsoft の逆の連絡先を同期するために格納されます &amp; 。 first_name、last_name、メールアドレスなどの連絡先情報が保存されます。 | ユーザーは、Office365 の連絡先を Zoho CRM と同期できます。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | 委任 |  | ユーザーが Office365 ファイルを Zoho CRM にインポートできるようにします。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | 委任 |  | ユーザーが Office365 ファイルを Zoho CRM にインポートできるようにします。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | 委任 | ユーザー ID 用に保存されます。 | ユーザーが Office365 ファイルを Zoho CRM にインポートできるようにします。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | 委任 | first_name、last_name、電子メール アドレスなどのユーザー プロパティ。 | すべてのユーザーの基本プロファイルの読み取り | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| メール | 委任 | ユーザーのインデントのためにユーザーが格納されている | ユーザーの電子メール アドレスの表示 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | 委任 |  | アクセス許可を付与したデータへのアクセスの維持 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profile | 委任 |  | ユーザーの基本プロファイルを表示する | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>テレメトリとログでEUII / PIIを収集しません。 私たちは、そのようなデータが見える修正のために探し、警告するスクリプトを用意しています

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>お客様は、証明書の制限を適用して、EAR (保管時の暗号化) を介して暗号化する必要があるデータを選択できます。パスワードはデフォルトでハッシュされます。 サーバへの論理的なアクセスは、独立した専用ネットワークを介して提供 &amp; され、高度にセキュリティ保護


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

