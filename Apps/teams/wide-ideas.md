---
title: 幅広いアイデアによる幅広いアイデアのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Wide Ideas、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STARレジストリ内のセキュリティ/コンプライアンス情報に関する利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f1fc5d97736ba587595ef6c742b14ce75c0b1863
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550897"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年6月3日</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

マイクロソフトにワイドアイデアから提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Wide Ideas |
| ID | WA200000819 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Wide Ideas |
| パートナーウェブサイトのURL | [https://getwideideas.com](https://getwideideas.com) |
| プライバシーポリシーの URL | [https://getwideideas.com/privacy-policy](https://getwideideas.com/privacy-policy) |
| 利用規約の URL | [https://getwideideas.com/terms](https://getwideideas.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法と、アプリが収集するデータに対する組織のコントロールに関するワイドアイディアによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | アプリケーション | グループ ID と、どのユーザーがどのグループに属しているかが保存されます。 | ユーザーやグループなど、アプリが Customers 組織のディレクトリ内のデータを読み取ることを許可します。  | 77baef51-6387-4aff-9b3f-23e4654c30cd |
>| Group.ReadWrite.All | アプリケーション | グループに関連付けられているチャネル ID を保存します。 | ユーザーは、カスタマーポータルからMicrosoft Teams内にチーム、チャネル、タブを作成できます。 これにより、ユーザーはMicrosoft Teamsの既存のチームをカスタマーポータルに同期することもできます。 | 77baef51-6387-4aff-9b3f-23e4654c30cd |
>| User.Read | 委任 | 名前の電子メールを保存します &amp; 。 | ユーザーがサインインし、自分の代わりに Microsoft Graphへのアクセスを許可します。 | 77baef51-6387-4aff-9b3f-23e4654c30cd |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>| **すべての非Microsoft サービス OII は、** |  **どのようなOIIが転送されますか?** | **OIIを転送するための正当性?** |
>|:-------------------|:--------------------------|:--------------------------|
>| メール通知に使用されるメールジェットメール。 |  | 該当なし |

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| バックエンドにユーザーを作成し、チームにリンクされたコンテンツにアクセスする権限を付与するため。 | ストア: 名前 - ユーザーの名前を表示するには、電子メール アドレス - ユーザーを識別するには |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>ログには IP 番号のみを保存します。 

組織は、データを削除する場合は、サプライヤーとして当社に要求を送信することができます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>データストレージ: すべての顧客データは、Microsoft Azureサービスに保存されます。 ユーザーは、Azure AD を介して 2 要素の認証を受ける必要があります。 ロール ベースのアクセス (RBAC) が設定されています。 Microsoft Azureへのすべてのアクセスは、暗号化された接続を通じて厳密に行われます。 すべてのデータは保存時に暗号化されます。 すべてのサービスは、Azure セキュリティ センターのベスト プラクティスによって保護されています。 

また、最小限の特権の原則に従ってアクセスポリシーを実施しています。 


#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

