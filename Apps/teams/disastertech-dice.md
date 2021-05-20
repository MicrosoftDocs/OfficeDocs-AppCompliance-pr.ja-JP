---
title: DisasterTech による DisasterTech DICE のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: DisasterTech DICE で利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
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
<p>開発者が最終更新日: 2020 年 8 月 24 日</p>

* <a href="https://teams.microsoft.com/l/app/7df3e67b-ed62-48e9-a950-c95bd7ebce80" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001909" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

DisasterTech から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | DisasterTech DICE |
| ID | WA200001909 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | DisasterTech |
| パートナー Web サイトの URL | [https://dice.disastertech.com](https://dice.disastertech.com) |
| プライバシー ポリシーの URL | [https://dice.disastertech.com/privacy.html](https://dice.disastertech.com/privacy.html) |
| 利用規約の URL | [https://dice.disastertech.com/tos.html](https://dice.disastertech.com/tos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールについて、DisasterTech によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 委任 | アクセス権を確立するために保存されたユーザーの電子メール アドレスと、名前でユーザーを識別するユーザー名 | ユーザーがサインインし、アプリに UPN へのアクセス権を与え、サイレント ログインと Teams ログインを有効にして、ユーザー名と電子メール アドレスを確立できます。 | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| メール | 委任 | なし | 単一のTeamsにSign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| offline_access | 委任 | なし | 単一のTeamsにSign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| openid | 委任 | なし | 単一のTeamsにSign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| profile | 委任 | なし | シングル サインオンTeamsに必要です。 | 36d23b76-c58b-4a34-a60f-dceac6962bad |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>Azure がホストする PostgreSQL データベースに、ユーザー名、名、および名を保存して、ユーザーがアプリケーションで共同作業できるようにしています。 このコントロールでは、障害技術の従業員だけがデータベースに直接アクセスできます。 ユーザーがアプリケーションから削除されると、情報がアーカイブされます。 ユーザーは、いつでもシステムから個人データを削除する権利を保持します。 ただし、そのような情報を削除すると、アプリケーションの使用も禁止されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>アプリケーション データは Azure の PostgreSQL データベースに格納され、保存時に暗号化されます。 データベースまたはバック エンド API に直接アクセスできるユーザーはありません。 すべての API 呼び出しは Active Directory アクセス トークンで保護されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

