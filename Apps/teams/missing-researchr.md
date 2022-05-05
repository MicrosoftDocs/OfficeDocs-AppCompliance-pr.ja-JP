---
title: KBE&#26666;&#24335;&#20250;&#31038;による researcHR のアプリケーション情報
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: researcHR に使用可能なすべてのセキュリティ情報とコンプライアンス情報、データ処理ポリシー、Microsoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 66460d332f54b1868fbcd2895b6de088bb362d97
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/05/2022
ms.locfileid: "65229011"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 8 月 5 日</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">Teams ストアで表示する</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

KBE&#26666;&#24335;&#20250;&#31038; から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | researcHR |
| ID | WA200002557 |
| サポートされているOffice 365 クライアント | Microsoft Teams |
| パートナー会社名 | KBE&#26666;&#24335;&#20250;&#31038; |
| パートナー Web サイトの URL | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| Teamsアプリケーション情報ページの URL | [https://app.researchr.work](https://app.researchr.work) |
| プライバシー ポリシーの URL | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| 使用条件の URL | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する KBE&#26666;&#24335;&#20250;&#31038; によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graphを使用したデータ アクセス

このアプリ[で必要な Microsoft Graphアクセス許可](/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当な理由は?** | **データは格納されますか?それを格納するための正当な理由は?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | アプリケーション | このスコープを使用して、ボットがTeams クライアントに新しいチャネルを作成できるようにします。 参照: /graph/api/channel-post | これらのデータはデータベースに格納されません。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Directory.Read.All | アプリケーション | このスコープを使用して、これらのデータを Web サイトに表示するチャネル ID と名前を取得します。 参照: /graph/api/channel-list | これらのデータはデータベースに格納されません。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Group.Read.All | アプリケーション | このスコープを使用して、これらのデータを Web サイトに表示するチャネル ID と名前を取得します。 参照: /graph/api/channel-list | これらのデータはデータベースに格納されません。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| Team.ReadBasic.All | アプリケーション | このスコープを使用してチームのメンバーを取得し、ユーザーが自分のチーム メンバーを Web サイトで表示できるようにします。 参照: /graph/api/group-list-members | これらのデータはデータベースに保存されません。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.Read.All | アプリケーション | このスコープを使用してユーザーの参加チャネルを取得し、ユーザーが参加しているチームを Web サイトで表示できるようにします。 参照: /graph/api/user-list-joinedteams | これらのデータはデータベースに格納されません。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| User.ReadBasic.All | 委任 | このスコープを使用して、OAuth ログインを有効にし、ユーザーのAAD ID、アクセス トークン、更新トークンを収集します。 参照: /graph/auth-v2-user | ユーザーが OAuth を使用して Web サイトにログインできるように、ユーザーのAAD ID、アクセス トークン、更新トークンをデータベースに格納します。 | [82df726e-0de2-46af-b4f1-0645fd95fc97]../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |
>| offline_access | 委任 | このスコープを使用して更新トークンを取得し、ユーザー操作なしで認証されたユーザーのアクセス トークンを更新できるようにします。 参照: /azure/active-directory/develop/v2-permissions-and-consent#offline_access | ユーザーの操作なしでアクセス トークンを更新できるように、更新トークンをデータベースに格納します。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](../azure/82df726e-0de2-46af-b4f1-0645fd95fc97.md) |


#### <a name="non-microsoft-services-used"></a>使用されていないMicrosoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由の正当な理由を含めます。

>Microsoft サービス以外は使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、チーム内のチーム メンバーの名簿 (名、姓、表示名、電子メール アドレス) または追加されたチャットなど、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII にアクセスできません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織の識別可能な情報 (OII) またはエンド ユーザー識別情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はい場合は、保存されるデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって格納されたデータの組織コントロール

組織の管理者がパートナー システムで自分の情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンド ユーザー ポリシーなど。

>データベース内のすべてのデータが暗号化されます。 データベース データのバックアップは、社内の運用ポリシーに従って一定の期間行われ、保存されます。 ユーザーが本サービスを取り消した場合、法律で定められた保存義務を果たすために必要な範囲を除き、ユーザーのユーザー情報を遅延なく削除します。 詳細を次に示します。 https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>不要

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) カタログからの情報が次に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、およびその他の ID 条件を処理する方法に関する KBE&#26666;&#24335;&#20250;&#31038; によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
