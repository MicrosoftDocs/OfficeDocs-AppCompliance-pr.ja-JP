---
title: Soapbox による Soapbox のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Soapbox で使用可能なすべてのセキュリティおよびコンプライアンス情報、データ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 66c465226543dcd95500631162eaa1a7f88c3280
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096077"
---
# <a name="soapbox"></a>Soapbox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2019 年 12 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/b49e7913-3b3f-4125-adde-2b698fc12c8b" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381501" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Soapbox から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Soapbox |
| ID | WA104381501 |
| 機能 | ボット、タブ |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Soapbox |
| パートナー Web サイトの URL | [https://soapboxhq.com](https://soapboxhq.com) |
| [アプリケーション情報Teamsページの URL | [https://msteams.services.soapboxhq.com/faqs](https://msteams.services.soapboxhq.com/faqs) |
| プライバシー ポリシーの URL | [https://soapboxhq.com/privacy-policy/microsoft-teams](https://soapboxhq.com/privacy-policy/microsoft-teams) |
| 利用規約の URL | [https://soapboxhq.com/terms-of-service](https://soapboxhq.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Soapbox によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 委任 | 同期トークン。 | SoapBox 会議を予定表イベントに同期するには、予定表へのアクセスが必要です |  |
>| User.Read | 委任 | 名前、電子メール、Microsoft ユーザー ID。 | 名前と電子メールは、SoapBox ユーザーの作成に使用されます。 |  |
>| offline_access | 委任 |  | 同期された予定表イベントに関連する SoapBox 通知時間を作成するには、予定表へのオフライン アクセスが必要です。 |  |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| アプリはチーム名簿とチャット名簿にアクセスし、これを使用してチーム/チャットのメンバーと SoapBox でチーム チャネルを作成します。 | Microsoft Teams ユーザーのアプリの外観を改善し、各ユーザーが会議ソフトウェアに完全に参加できるよう、ユーザーの名前、電子メール、Microsoft ユーザー ID。 |  |



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>はい。 名前、電子メール、Microsoft ユーザー ID は、最大 30 日間、統合ログ プラットフォーム内に表示され、問題の特定とユーザーによるプラットフォームの使用を支援します。 30 日後、ログ サーバーからデータが削除されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>プライマリ インフラストラクチャは、プライベート ネットワーク内の AWS に保存されます。 また、Heroku と Azure でボットが構成されています。 サーバーへのアクセスは、SSH キー要件によって制限されます。 すべての要求が SSL (TLS 1.3) を超える。 署名された要求を使用して、ボットからプラットフォームへのトラフィックが安全に保護されます。 データは保存時に暗号化されます。 Dev ops スタッフがアカウントにアクセスするには 2FA が必要

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35464' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35464" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

