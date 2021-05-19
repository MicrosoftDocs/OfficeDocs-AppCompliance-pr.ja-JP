---
title: スマートシート別アプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Smartsheet で利用可能なすべてのセキュリティ情報およびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ddf77e7e73cc0bef1a21e72d1db328a4845a12f5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551527"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

スマートシートがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Smartsheet |
| ID | WA104380975 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Smartsheet |
| パートナーウェブサイトのURL | [https://help.smartsheet.com/articles/2476201](https://help.smartsheet.com/articles/2476201) |
| アプリケーション情報ページTeams URL | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| プライバシーポリシーの URL | [https://www.smartsheet.com/privacy](https://www.smartsheet.com/privacy) |
| 利用規約の URL | [https://www.smartsheet.com/user-agreement](https://www.smartsheet.com/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して保存する方法、およびアプリが収集するデータに対する組織のコントロールに関する情報を Smartsheet によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | 委任 | なし。 | アプリがユーザーに代わってアプリをインストールできるようにします。 | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Directory.Read.All | 委任 | UI に表示する情報を取得するためのテナント ID。 | このテナントが使用しているアプリを読み取り、アプリをインストールする必要があるかどうかを確認できます。 | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.Read.All | 委任 | メッセージ配信のチーム ID/グループ ID。 | アプリは、グループ(またはTeamsチーム)に関する基本情報や会話を読み取ることができます。 | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.ReadWrite.All | 委任 | メッセージ配信のチーム ID/グループ ID。 | アプリがチームで新しい会話を開始できるようにします。 この権限には上記の Read.All スコープも含まれますが、技術的な理由からも必要です。 | c68947ae-a07f-44ce-9a13-7b559251731d |
>| User.Read.All | 委任 | ユーザー ID。 | 認証プロセス中にユーザーに関する基本情報を読み取ることができます。 | c68947ae-a07f-44ce-9a13-7b559251731d |
>| offline_access | 委任 | リフレッシュトークン。 | アプリがアプリを使用するときに、更新トークンを受信し、ユーザーの代わりに認証トークンを更新することを許可します。 | c68947ae-a07f-44ce-9a13-7b559251731d |

#### <a name="data-access-using-other-microsoft-apis"></a>他のマイクロソフト API を使用したデータ アクセス

Microsoft 365上に構築されたアプリやアドインでは、Microsoft Graph 以外の Microsoft API を使用して、組織を識別できる情報 (OII) を収集または処理できます。 このアプリが使用するマイクロソフトGraph以外のマイクロソフト API を一覧表示します。

>| **API** |  **OIIは収集されますか?** |  **OIIは何を収集されますか?** | **OIIを収集するための正当性?** | **OII は保存されていますか?** | **OIIを格納するための正当性?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| ボット フレームワーク API | はい | ボット フレームワーク API を使用して、チーム アプリのアプリとしてメッセージを配信します。 スマートシートは、ユーザー ID 情報を格納して、スマートシート ボットが誰と話しているかを追跡します。 |  | なし |  |

#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>| **すべての非Microsoft サービス OII は、** |  **どのようなOIIが転送されますか?** | **OIIを転送するための正当性?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Smartsheet は、Equinix でホストされている本番データセンター環境内および AWS S3 で、プライベート暗号化されたバケットに顧客の添付ファイルを保存する際に、暗号化された状態で情報を保存します。 |  | ボット フレームワーク API を使用して、チーム アプリのアプリとしてメッセージを配信します。 スマートシートは、ユーザー ID 情報を格納して、スマートシート ボットが誰と話しているかを追跡します。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Smartsheetは、ボットが誰と話しているかを追跡するためにこれを使用します。 最初の認証フローでは、Smartsheet 通知システムでユーザーのボット レコードを作成します。 | ボットTeams用の Smartsheet では、ボットが誰と話しているのかを追跡するために、Teamsからユーザーの電子メールと userId を保存します。  Smartsheet には、ユーザーがディレクトリ内に属するグループを一覧表示するためのテナント ID と、メッセージ配信の groupId が格納されます。 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>いいえ

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>Smartsheetは、保存されているすべてのユーザー情報を暗号化し、管理者は2FAを使用する必要があります。 Smartsheet は、ビューのない SaaS プロバイダーとして動作し、既定では、お客様がプラットフォームにアップロードまたは入力することを選択したコンテンツは確認しません。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

