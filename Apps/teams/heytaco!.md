---
title: ヘイタコの申込情報! ヘイタコによって!
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: HeyTaco!、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、およびCSA STARレジストリ内のセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 66739977ba4aa3eef7456d4ec60530f94065a2b9
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553128"
---
# <a name="heytaco"></a>HeyTaco!

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年11月3日</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

HeyTacoが提供する情報! マイクロソフトに:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | HeyTaco! |
| ID | WA200001346 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | HeyTaco! |
| パートナーウェブサイトのURL | [https://www.heytaco.chat](https://www.heytaco.chat) |
| プライバシーポリシーの URL | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| 利用規約の URL | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報はHeyTacoによって提供されています! このアプリが組織データをどのように収集して保存するかについて、およびアプリが収集するデータに対して組織が持つ制御について説明します。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| メール | 委任 | Slack から MS Teamsへのデータ転送にユーザーを照合するために使用されます。 | Slack から MS チームへのデータ転送にユーザーを照合するために使用されます。 | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| openid | 委任 | ヘイタコに人に署名するために使用! | ヘイタコに人に署名するために使用! | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| profile | 委任 | ユーザー名、プロファイル イメージ、タイムゾーン オフセット、テナント ID、およびチーム ID のキャプチャに使用 | ユーザー名、アバター、タイムゾーンオフセット、テナント ID、およびチーム ID の取得に使用 | be8d11cf-265a-4974-9912-4ff28c29fc21 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| タコスを受け取ったユーザーと、それが誰からだかを伝えるために。 | 電子メールアドレス (あるプラットフォームから別のプラットフォームへの移行タコス用) 名前 (ユーザーへの挨拶用) プロファイルイメージ (リーダーボードに表示する場合) タイムゾーン (アクティビティページに与えられたタコスを適切に表示するため) テナント ID (テナント別データの集計用) チーム ID (チーム別データを集計する場合)  |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>EUII と OII は、どのログにも接続されていません。 エラーの種類とアクションの種類のみ。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>HeyTaco! データベースとデータのバックアップは、アマゾン ウェブ サービス (AWS) でホストされます。 

アマゾンのデータセンターオペレーションは、ISO 27001、SOC 1、SOC 2/SSAE 16/ISAE 3402(以前はSAS 70タイプII)、PCIレベル1、FISMAモデレート、Sarbanes-Oxley(SOX)の下で認定されています。

当社のサービスを通じて情報を送信すると、お客様の情報は安全な接続を介して保管中および転送中に保護され、暗号化されます。 お客様の個人情報の安全を確保するため、各種のセキュリティ対策を実施します。

サーバー上のデータを保護するために、特権アクセス管理を用意しています。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

