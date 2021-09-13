---
title: MySecretary による SecretaryBot のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: SecretaryBot、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8d7e2fce37cf43fe52cb050e85aa9e4fd5e00802
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287379"
---
# <a name="secretarybot"></a>SecretaryBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2019 年 12 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/256ff1bc-fd16-4f82-aeb3-8a6977ff2ec4" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381085" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

MySecretary が Microsoft に提供する情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | SecretaryBot |
| ID | WA104381085 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | MySecretary |
| パートナー Web サイトの URL | [https://secretarybot.wordpress.com/](https://secretarybot.wordpress.com/) |
| [アプリケーション情報Teamsページの URL | [https://secretarybot.wordpress.com/faq/](https://secretarybot.wordpress.com/faq/) |
| プライバシー ポリシーの URL | [https://secretarybot.wordpress.com/privacy-policy/](https://secretarybot.wordpress.com/privacy-policy/) |
| 利用規約の URL | [https://secretarybot.wordpress.com/terms-of-use/](https://secretarybot.wordpress.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する MySecretary によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read.Shared | 委任 |  | ユーザーとその同僚の空き時間情報を取得します。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Calendars.ReadWrite | 委任 |  | ユーザーではなく会議出席依頼を送信します。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| MailboxSettings.Read | 委任 | 正しい言語を表示する言語を保存します。 MS カレンダー API を正しく呼び出Graphタイム ゾーンを節約する | ユーザーの言語とタイムゾーンの設定を取得します。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| People.Read | 委任 |  | ユーザーと強い関係を持つ同僚を探してみてください。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | 委任 | ユーザー分析用のユーザー名、都市、国、および言語を保存します。 顧客に連絡するメールを保存します。 メール アドレスは一度も使用したことが、サポートに使用される場合があります。 | ユーザーの国と優先言語を検索してみてください。 MailboxSettings.Read のバックアップに使用されます。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| メール | 委任 | 上記を参照してください。 | メールを保存する場合。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| openid | 委任 |  | OpenID 認証の場合。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| profile | 委任 | OID を保存して、MS ID システムでユーザーの一意の ID を識別します。 | ユーザー名と OID を取得します。 将来、OID を使用して addin Outlook接続してみてください。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| チーム会議のスケジュールを設定するには、この追加機能を使用します。 | いいえ |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>OII または EUII データは、テレメトリまたはログに表示されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>エンド ユーザーに対して管理制御はまだ提供されていませんが、エンド ユーザーがデータの削除を要求した場合は、その要求に従います。


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35678" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

