---
title: Medxnote による Medxnote MT のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
description: Medxnote MT で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c76c9e0fe6166bf3acc8c2d48abb8172583d8dc9
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094498"
---
# <a name="medxnote-mt"></a>Medxnote MT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 9 月 28 日</p>

* <a href="https://teams.microsoft.com/l/app/02ffb7cc-5fcd-4b31-bcbd-b24bbca74cc7" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001823" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Medxnote が Microsoft に提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Medxnote MT |
| ID | WA200001823 |
| 機能 | Bot |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Medxnote |
| パートナー Web サイトの URL | [https://medxnote.com](https://medxnote.com) |
| プライバシー ポリシーの URL | [https://medxnote.com/privacy-policy/](https://medxnote.com/privacy-policy/) |
| 利用規約の URL | [https://medxnote.com/terms-conditions/](https://medxnote.com/terms-conditions/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Medxnote によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read.All | アプリケーション | 私たちは、ユーザーの特権をチェックするために病院側で使用される名前と電子メールをキャッシュしています | メッセージを送信するときに、名前と電子メール アドレスが追加された場合、サーバー側のデータをキャッシュしています。病院側でのオプションの特権チェックにも使用されます。 | fc70bbbe-91c4-4d8f-a9c9-a022068d5752 |
>| openid | 委任 | Task モジュールでユーザーにサインインするために使用されるセッション ID、ユーザー ID、ベアラー トークン、および電子メールをキャッシュしています | タスク モジュールでユーザーにサインインするためにそれを使用して、セッション ID、userid、電子メール、ベアラー トークンを保存しています | fc70bbbe-91c4-4d8f-a9c9-a022068d5752 |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>電子メール アドレス、名前、テナント ID、チャネル ID がログに表示される場合がありますすべてのログ データは、最新の 1 か月後に自動的に削除されます。
これらへのアクセスは、2FA の強制アクセス権を持つ一握りの組織管理者に制限されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>アクセスは、2FA の強制アクセス権を持つ一握りの組織管理者に制限されます。
重要なシステムには、特定の IP アドレスからのみアクセスできます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36056' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36056" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

