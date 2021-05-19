---
title: トライアン分析のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Tryane Analytics で利用可能なすべてのセキュリティ情報およびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリ カタログ情報、および CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 265fa798414c907f25690252e1714bebfdbdde1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551107"
---
# <a name="tryane-analytics"></a>Tryane Analytics

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年9月28日</p>

* <a href="https://teams.microsoft.com/l/app/87631b95-fcd9-46e9-8d86-3d5205c04fec" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001827" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

マイクロソフトにトリアンから提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Tryane Analytics |
| ID | WA200001827 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Tryane |
| パートナーウェブサイトのURL | [https://tryane.com/en/produit/tat/](https://tryane.com/en/produit/tat/) |
| プライバシーポリシーの URL | [https://tryane.com/tryane-analytics/privacy_policy.html](https://tryane.com/tryane-analytics/privacy_policy.html) |
| 利用規約の URL | [https://tryane.com/tryane-analytics/terms_of_use.html](https://tryane.com/tryane-analytics/terms_of_use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法、およびアプリが収集するデータに対する組織のコントロールについて、Tryane によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| アクティビティフィード.読み取り | アプリケーション |  | チーム内のすべてのユーザーアクティビティを読み取る | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Channel.ReadBasic.All | アプリケーション |  | すべての名前、説明を持つすべてのチャンネルを一覧表示 | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| ChannelMessage.Read.All | アプリケーション |  | メタデータ&#8217;すべてのチャネル メッセージを一覧表示する | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Directory.Read.All | アプリケーション |  | テナントのチーム ライセンスを持つユーザーを特定する | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Member.Read.Hidden | アプリケーション |  | すべてのチーム、チーム&#8217;メンバー、および非表示のメンバーシップのリストを取得する | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Reports.Read.All | アプリケーション |  | チーム内のすべてのユーザーアクティビティを読み取る | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Team.ReadBasic.All | アプリケーション |  | すべてのチャネルとチームのプロパティを一覧表示する | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| User.Read | 委任 | ユーザー ID、名前、電子メール アドレス、作成日。このデータは、Teamsに利用状況分析を提供するために保存されます。 | サブスクリプション中に現在のユーザーを識別する | 9b03f15d-1219-4b2f-9699-640be54e1319 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>IT セキュリティ ポリシーとコーディング標準に記載されている組織ルールにより、EUII と OII がログに記録されないようにする

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>場所/方法: Whoアクセスできる PostgreSQL サーバーの Azure/Azure データベース: アプリケーションとデータベース管理者承認コントロール: 
 - 個々の許可制御: RBAC
 - システム承認制御: Azure 仮想ネットワーク内のプライベート エンドポイント

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

