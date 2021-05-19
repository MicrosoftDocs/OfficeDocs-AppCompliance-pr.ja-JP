---
title: ウィティビオによる学習のためのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 03/31/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: 「Learn」で利用可能なすべてのセキュリティ情報およびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STARレジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: acb0b07f25bc3fa2e86246a061ff73d3152b9810
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550857"
---
# <a name="learn"></a>詳細

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年3月31日</p>

* <a href="https://teams.microsoft.com/l/app/2d96b540-aa26-431b-bc31-222321c762e3" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001308" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

ウィティビオがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | 詳細 |
| ID | WA200001308 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Witivio |
| パートナーウェブサイトのURL | [https://www.witivio.com/learn](https://www.witivio.com/learn) |
| プライバシーポリシーの URL | [https://www.witivio.com/en/privacy](https://www.witivio.com/en/privacy) |
| 利用規約の URL | [https://witivio.com/en/terms-of-use](https://witivio.com/en/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが収集し、組織のデータを格納する方法と、アプリが収集するデータに対する組織のコントロールについて、Witivioによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 委任 | 該当なし | 承認の UPN と AAD ID を収集します。 | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| User.ReadBasic.All | 委任 | 該当なし | 承認の UPN と AAD ID を収集します。 | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| openid | 委任 | 該当なし | 承認の UPN と AAD ID を収集します。 | 8c5c0060-2892-4355-b0db-661f206028a9 |
>| profile | 委任 | 該当なし | 承認の UPN と AAD ID を収集します。 | 8c5c0060-2892-4355-b0db-661f206028a9 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 私たちは、1)承認(ボットへのアクセスを許可する)、2)フレンドリーなUXを提供する名を検出するために名簿を使用し、3)ボットのビジネス管理者のためのチャットログを管理するには | 該当する場合は、お知りいの場合は、お またはボットは個人的なものです |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>ボットのテレメトリには、UPN および AAD ID fr 診断が含まれています。
PROD/Run 管理者のみが実稼働テレメトリにアクセスできます。 ログは 90 日間保存され、専用のポータル support.witivio.com または電子メールで要求に応じて削除 dpo@witivio.com

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>Witivio は、北ヨーロッパ リージョンにデプロイされた Azure コンポーネントのみを使用します。 データ分析とストレージには、アプリケーションインサイトとCosmos DBを使用しています。
Witivio は、管理者を含むすべてのユーザーに MFA を使用します。 管理者は、(ワークステーション用の) ユーザー アカウントと、Azure のリソースにアクセスするための特権アカウントを持っています。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35854" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

