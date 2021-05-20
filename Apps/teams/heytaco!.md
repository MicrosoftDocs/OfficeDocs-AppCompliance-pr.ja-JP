---
title: HeyTaco のアプリケーション情報! by HeyTaco!
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: HeyTaco!、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリのセキュリティ/コンプライアンス情報に関する利用可能なすべてのセキュリティおよびコンプライアンス情報。
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
<p>開発者が最終更新日: 2020 年 11 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

HeyTaco が提供する情報! Microsoft に:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | HeyTaco! |
| ID | WA200001346 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | HeyTaco! |
| パートナー Web サイトの URL | [https://www.heytaco.chat](https://www.heytaco.chat) |
| プライバシー ポリシーの URL | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| 利用規約の URL | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は HeyTaco によって提供されています。 このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールについて。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| メール | 委任 | Slack から MS へのデータ転送にユーザーを一致Teams | Slack から MS Team へのデータ転送にユーザーを一致するために使用される | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| openid | 委任 | HeyTaco にユーザーをサインインするために使用されます。 | HeyTaco にユーザーをサインインするために使用されます。 | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| profile | 委任 | ユーザー名、プロファイル イメージ、タイム ゾーン オフセット、テナント ID、およびチーム ID をキャプチャするために使用されます。 | ユーザー名、アバター、タイム ゾーン オフセット、テナント ID、およびチーム ID をキャプチャするために使用されます。 | be8d11cf-265a-4974-9912-4ff28c29fc21 |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| タコを受け取ったユーザーと、そのタコの受け取り者をユーザーに伝える。 | メール アドレス (あるプラットフォームから別のプラットフォームへの移行用) Name (ユーザーに案内応答用) プロファイル イメージ (ランキングに表示する場合) タイム ゾーン (アクティビティ ページに指定されたタコスを適切に表示する) テナント ID (テナントによるデータの集計用) チーム ID (チームによるデータの集計用)  |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>EUII と OII は、ログに接続されていません。 エラーの種類とアクションの種類のみ。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>HeyTaco! データベースとデータバックアップは、Amazon Web Services (AWS) でホストされます。 

Amazonのデータセンター運用は、ISO 27001、SOC 1、SOC 2/SSAE 16/ISAE 3402 (以前は SAS 70 Type II)、PCI Level 1、FISMA Moderate、および Sarbanes-Oxley (SOX) の下で認定されています。

お客様がサービスを通じて情報を送信する場合、お客様の情報は、安全な接続を介して、保存中と転送中の両方で保護され、暗号化されます。 お客様の個人情報の安全性を維持するために、さまざまなセキュリティ対策を実施します。

サーバー上のデータを保護するために、特権アクセス管理が提供されています。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

