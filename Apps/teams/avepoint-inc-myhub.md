---
title: 株式会社アベポイントによるMyHubのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/21/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: MyHub の利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ccf5367ea692731bafcdc03d04ab4dad2e76c976
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553388"
---
# <a name="myhub"></a>MyHub

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者による最終更新日: 2020年12月21日</p>

* <a href="https://teams.microsoft.com/l/app/c3ff6344-f6f0-4bfa-8697-b9d47b32ca4b" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000726" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

アベポイント社がマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | MyHub |
| ID | WA200000726 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | AvePoint, Inc. |
| パートナーウェブサイトのURL | [https://www.avepoint.com](https://www.avepoint.com) |
| プライバシーポリシーの URL | [https://www.avepoint.com/company/privacy-policy](https://www.avepoint.com/company/privacy-policy) |
| 利用規約の URL | [https://www.avepoint.com/company/terms-and-conditions/](https://www.avepoint.com/company/terms-and-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法、およびアプリが収集するデータに対する組織のコントロールに関する AvePoint, inc. によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | 両方とも | アプリケーション構成データは、データ処理の観点から保存されます。 | ディレクトリ データの読み取り | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Group.ReadWrite.All | 両方とも | アプリケーション構成データは、データ処理の観点から保存されます。 | すべてのグループの読み取りと書き込み | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Mail.Send | 委任 | アプリケーション構成データは、データ処理の観点から保存されます。 | ユーザーからのメールとして送信 | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Reports.Read.All | アプリケーション | アプリケーション構成データは、データ処理の観点から保存されます。 | すべての利用状況レポートの読み取り | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.FullControl.All | アプリケーション | アプリケーション構成データは、データ処理の観点から保存されます。 | すべてのサイト コレクションのフル コントロール | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.Read.All | アプリケーション | アプリケーション構成データは、データ処理の観点から保存されます。 | すべてのサイト コレクションに含まれるアイテムの読み取り  | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| Sites.ReadWrite.All | 委任 | アプリケーション構成データは、データ処理の観点から保存されます。 | すべてのサイト コレクションのアイテムを編集または削除する | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |
>| User.Read.All | 両方とも | アプリケーション構成データは、データ処理の観点から保存されます。 | 全プロファイル&#8217;すべてのユーザーを読み取る | 4d69a8e1-9c38-4b33-b76f-9d59b5ae051b |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>はい、ユーザーのメールとテナント ID がログに表示されます。 ログはセキュリティで保護された場所に保存され、トラブルシューティング中にアクセスできるのは権限のある担当者のみです。 ログは、セキュリティ監査のために 60 日後にアーカイブされ、1 年後に削除されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>アプリケーションのデータは、Azure SQL DatabaseおよびAzure Storageに格納されます。 Azure SQLとAzure Storage暗号化が有効になります。
権限のある管理者のみがデータにアクセスできます。 管理者がログインするには MFA が必要です。 操作が監査されます。 IP ホワイトリストは、データへのアクセスを制限するためにも使用されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35843" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

