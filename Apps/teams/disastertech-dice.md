---
title: 災害向けアプリケーション情報 ダイスバイ災害技術
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: DisasterTech DICEの利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STARレジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 29d53402a9bbf635e83d6d262227a8363577e261
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552238"
---
# <a name="disastertech-dice"></a>DisasterTech DICE

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年8月24日</p>

* <a href="https://teams.microsoft.com/l/app/7df3e67b-ed62-48e9-a950-c95bd7ebce80" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001909" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

ディザスターテックがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | DisasterTech DICE |
| ID | WA200001909 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | DisasterTech |
| パートナーウェブサイトのURL | [https://dice.disastertech.com](https://dice.disastertech.com) |
| プライバシーポリシーの URL | [https://dice.disastertech.com/privacy.html](https://dice.disastertech.com/privacy.html) |
| 利用規約の URL | [https://dice.disastertech.com/tos.html](https://dice.disastertech.com/tos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して保存する方法と、アプリが収集するデータに対する組織の制御について、DisasterTechによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 委任 | ユーザーを識別するためのアクセス権の確立用に保存されたユーザーメールアドレスと、名前でユーザーを識別するユーザー名 | ユーザーがサインインし、アプリに UPN へのアクセス権を付与して、サイレント ログインとログインを有効にTeams、ユーザー名と電子メール アドレスを確立できるようにします。 | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| メール | 委任 | なし | 単一TeamsSign-Onに必要 | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| offline_access | 委任 | なし | 単一TeamsSign-Onに必要 | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| openid | 委任 | なし | 単一TeamsSign-Onに必要 | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| profile | 委任 | なし | シングル サインオンTeams必要です。 | 36d23b76-c58b-4a34-a60f-dceac6962bad |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>Azure がホストする PostgreSQL データベースには、ユーザー名、名、姓が格納され、ユーザーがアプリケーション内で共同作業を行えるようにします。 このコントロールは、災害技術の従業員だけがデータベースに直接アクセスできるということです。 ユーザーがアプリケーションから削除されると、情報がアーカイブされます。 ユーザーは、いつでもシステムから個人データを削除する権利を保持します。 ただし、このような情報を削除すると、アプリケーションの使用も禁止されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>アプリケーション データは、保存時に暗号化された Azure の PostgreSQL データベースに格納されます。 データベースまたはバックエンド API に直接アクセスできるユーザーはいません。 すべての API 呼び出しは、アクティブ ディレクトリ アクセス トークンで保護されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

