---
title: 幅広いアイデアによる幅広いアイデアのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Wide Ideas、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 05daba10da032e947976d99411e0e70982e17f00
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/02/2021
ms.locfileid: "53279051"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 6 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Wide Ideas から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Wide Ideas |
| ID | WA200000819 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Wide Ideas |
| パートナー Web サイトの URL | [https://getwideideas.com](https://getwideideas.com) |
| プライバシー ポリシーの URL | [https://getwideideas.com/privacy-policy/](https://getwideideas.com/privacy-policy/) |
| 利用規約の URL | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474849364/Product_42949683744/Asset_0831a14b-e5df-4f0b-8385-3c06edaeceeb/GENERALTERMSANDCONDITIONSWideI.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Wide Ideas によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | アプリケーション | グループ ID と、どのユーザーが属するグループを保存します。 | アプリで、ユーザーやグループなどの顧客組織のディレクトリ内のデータを読み取ります。  | 77baef51-6387-4aff-9b3f-23e4654c30cd |
>| Group.ReadWrite.All | アプリケーション | グループに関連付けられているチャネル ID を保存します。 | ユーザーは、カスタマー ポータルからチーム、チャネル、Microsoft Teamsを作成できます。 これにより、ユーザーは既存のチームを顧客ポータルMicrosoft Teamsに同期することもできます。 | 77baef51-6387-4aff-9b3f-23e4654c30cd |
>| User.Read | 委任 | 名前のメールを保存 &amp; する | ユーザーが自分の代わりにサインインして Microsoft Graphアクセスを許可する | 77baef51-6387-4aff-9b3f-23e4654c30cd |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-------------------|:--------------------------|:--------------------------|
>| メール通知に使用される Mailjet Email。 |  | N/A |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| バックエンドでユーザーを作成し、チームにリンクされたコンテンツにアクセスするためのアクセス許可を与えるために。 | 保存: 名前 - ユーザーの名前を表示するには、電子メール アドレス - ユーザーを識別します。 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>IP 番号はログにのみ保存されます。 

組織は、データを削除する場合は、サプライヤーとして要求を送信できます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>データストレージ: すべての顧客データは、サービスMicrosoft Azureされます。 ユーザーは、Azure アカウントを介して 2 要素認証AD。 役割ベースのアクセス (RBAC) が設定されています。 サーバーへのすべてのアクセスMicrosoft Azure、暗号化された接続によって厳密に行います。 すべてのデータは保存時に暗号化されます。 すべてのサービスは、Azure セキュリティ センターの最善の実践によって保護されています。 

また、最小特権の原則に従ってアクセス ポリシーが設定されています。 


#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

