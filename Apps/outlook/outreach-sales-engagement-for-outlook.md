---
title: Outreach によるユーザー向け Outreach Sales Engagement Outlookアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Outlook の Outreach Sales Engagement、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリのセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d3b2a00ddb4023a54e78825c2382c1dbdad6f28a
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430727"
---
# <a name="outreach-sales-engagement-for-outlook"></a>Outreach Sales Engagement for Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 6 月 14 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381052" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Outreach から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Outreach Sales Engagement for Outlook |
| ID | WA104381052 |
| Office 365サポートされているクライアント | Outlook 2013 以降の Mac Windows、Outlook 2016以降の場合は、Outlook on the web |
| パートナー会社名 | Outreach |
| パートナー Web サイトの URL | [https://www.outreach.io](https://www.outreach.io) |
| プライバシー ポリシーの URL | [https://www.outreach.io/legal/privacy-policy/](https://www.outreach.io/legal/privacy-policy/) |
| 利用規約の URL | [https://www.outreach.io/terms](https://www.outreach.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Outreach によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft アプリケーションをGraph。

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlookアドイン API 、EWS API、O36 REST API | 不要 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Salesforce CRM | Outreach と Salesforce を統合すると、両方のサービス間で制限されたデータセットを安全に双方向に同期できます。組織名、電子メール アドレス、およびユーザー名。 | Outreach のインテリジェントな双方向同期により、両方のシステムのデータ間の完全な忠実度が保証されます。 Outreach &#8212; 呼び出し、電子メール、&#8212; で実行されたアクティビティはすべて自動的に Salesforce にログインされ、競合の解決によって競合が検出され、解決され、データが元のままの状態に保たされます。 Salesforce Aloha エディションと Lightning エディションで動作します。 |



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>Outreach は、お客様のデータに保持期間&#8217;適用されません。 Outreach はデータ プロセッサとして動作します。そのため、お客様の明示的な許可なく、&#8217;に変更を加える必要があります。 すべての顧客データは、MSA および DPA に基いて、ビジネス関係が終了した 60 日後に削除されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>Outreach は、契約上および規制上の理由から、新しいサブプロセッサの使用、またはサブプロセッサへの変更について、すべてのお客様に対して、時に通知する必要があります。 ほとんどの Outreach Customers の場合、これは 30 日間の期間です。 ただし、60 日と 90 日の通知要件を持つ少数の顧客がいます。 新しいサブプロセスの法的に必要な通知がすべての顧客に送信され、必要な該当する期間が過ぎるまで、顧客データを転送できません。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について Outreach によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
