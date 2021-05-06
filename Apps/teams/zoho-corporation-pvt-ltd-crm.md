---
title: Zoho Corporation Pvt Ltd による Zoho CRM のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Zoho CRM で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4387faccb63299392acb23ab91f312d175d1524d
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251606"
---
# <a name="zoho-crm"></a>Zoho CRM

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2019 年 12 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/003a8a54-9d27-41cd-9c28-aec5875a3497" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382094" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Zoho Corporation Pvt Ltd から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Zoho CRM |
| ID | WA104382094 |
| 機能 | ボット、タブ、メッセージングの拡張機能 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Zoho Corporation Pvt Ltd |
| パートナー Web サイトの URL | [https://www.zoho.com/](https://www.zoho.com/) |
| [アプリケーション情報Teamsページの URL | [https://www.zoho.com/crm/help/microsoft-teams-integration.h...](https://www.zoho.com/crm/help/microsoft-teams-integration.html) |
| プライバシー ポリシーの URL | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| 利用規約の URL | [https://www.zoho.com/crm/zohocrm-terms.html](https://www.zoho.com/crm/zohocrm-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、Zoho Corporation Pvt Ltd から、このアプリが組織データを収集および保存する方法、およびアプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 委任 | 予定表フォルダー ID は、Zoho CRM から Microsoft に連絡先を同期するために &amp; 格納されます。その逆も同様です。 カレンダー情報 (event_name、event_location、participant_detailsなど) が格納されます。 | ユーザーが Office365 イベントを Zoho CRM と同期できます。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | 委任 | 連絡先フォルダー ID は、Zoho CRM から Microsoft に連絡先を同期するために &amp; 格納されます。その逆も同様です。 連絡先の情報 (first_name、last_name、電子メール アドレスなど) が格納されます。 | ユーザーが Office365 連絡先を Zoho CRM と同期できます。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | 委任 |  | ユーザーが Office365 ファイルを Zoho CRM にインポートできます。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | 委任 |  | ユーザーが Office365 ファイルを Zoho CRM にインポートできます。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | 委任 | UserPrincipalName は、ユーザー ID 用に格納されます。 | ユーザーが Office365 ファイルを Zoho CRM にインポートできます。 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | 委任 | ユーザー プロパティ (first_name、last_name アドレスなど)。 | すべてのユーザーの基本プロファイルの読み取り | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| メール | 委任 | UserPrincipaName は、ユーザーのインデントのために格納されます。 | ユーザーのメール アドレスを表示する | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | 委任 |  | アクセス許可を付与したデータへのアクセスの維持 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profile | 委任 |  | ユーザーの基本的なプロファイルの表示 | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>テレメトリとログでは EUII/PII は収集しない。 そのようなデータが表示されている場合は、そのデータを修正するためのスクリプトを探して警告するスクリプトがインストールされています

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>お客様は、CERTAAT 制限付き EAR (保存時の暗号化) を使用して暗号化する必要があるデータを選択できます。パスワードは既定でハッシュ化されます。 サーバーへの論理的なアクセスは、分離された専用ネットワークを介して提供され &amp; 、高度にセキュリティで保護され、


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

