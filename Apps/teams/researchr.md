---
title: KBE による researcHR のアプリケーション&#26666;&#24335;&#20250;&#31038;
ms.author: elmalova
author: elenamalova
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: researcHR、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリのセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: b57d492945766c8d65417cf2f1d642ea4ecb8aae
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/12/2021
ms.locfileid: "59284011"
---
# <a name="researchr"></a>researcHR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 8 月 5 日</p>

* <a href="https://teams.microsoft.com/l/app/13a58c36-8f58-46e7-90dd-16084830876c" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002557" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

KBE によって提供される情報&#26666;&#24335;&#20250;&#31038; Microsoft に提供されます。

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | researcHR |
| ID | WA200002557 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | KBE&#26666;&#24335;&#20250;&#31038; |
| パートナー Web サイトの URL | [https://app.researchr.work/corporate](https://app.researchr.work/corporate) |
| [アプリケーション情報Teamsページの URL | [https://app.researchr.work](https://app.researchr.work) |
| プライバシー ポリシーの URL | [https://researchr.work/privacypolicy](https://researchr.work/privacypolicy) |
| 利用規約の URL | [https://app.researchr.work/tos](https://app.researchr.work/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリ&#26666;&#24335;&#20250;&#31038; 収集および保存する方法、およびアプリが収集するデータに対して組織が持つコントロールに関する KBE&#26666;&#24335;&#20250;&#31038; によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | アプリケーション | このスコープを使用して、ボットがクライアント上に新しいチャネルを作成Teamsします。 参照: https://docs.microsoft.com/en-us/graph/api/channel-post | これらのデータはデータベースに保存されません。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Directory.Read.All | アプリケーション | このスコープを使用して、チャネルの ID と名前を取得して、これらのデータを Web サイトに表示します。 参照: https://docs.microsoft.com/en-us/graph/api/channel-list | これらのデータはデータベースに保存されません。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Group.Read.All | アプリケーション | このスコープを使用して、チャネルの ID と名前を取得して、これらのデータを Web サイトに表示します。 参照: https://docs.microsoft.com/en-us/graph/api/channel-list | これらのデータはデータベースに保存されません。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| Team.ReadBasic.All | アプリケーション | このスコープを使用してチームのメンバーを取得し、ユーザーが自分のチーム メンバーを Web サイトで表示できます。 参照: https://docs.microsoft.com/en-us/graph/api/group-list-members | これらのデータは、アウト データベースに保存されません。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| User.Read.All | アプリケーション | このスコープを使用して、ユーザーの参加チャネルを取得し、ユーザーが参加しているチームを Web サイトで確認できます。 参照: https://docs.microsoft.com/en-us/graph/api/user-list-joinedteams | これらのデータはデータベースに保存されません。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| User.ReadBasic.All | 委任 | このスコープを使用して、OAuth ログインを有効にし、ユーザーの AAD ID、アクセス トークン、および更新トークンを収集します。 参照: https://docs.microsoft.com/en-us/graph/auth-v2-user | ユーザーが OAuth を使用して Web サイトにログインできるよう、ユーザーの AAD ID、アクセス トークン、および更新トークンをデータベースに保存します。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |
>| offline_access | 委任 | このスコープを使用して更新トークンを取得し、ユーザー操作なしで認証されたユーザーのアクセス トークンを更新できます。 参照: https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-permissions-and-consent#offline_access | 更新トークンはデータベースに保存され、ユーザー操作なしでアクセス トークンを更新できます。 | [82df726e-0de2-46af-b4f1-0645fd95fc97](https://docs.microsoft.com/microsoft-365-app-certification/azure/82df726e-0de2-46af-b4f1-0645fd95fc97) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>データベース内のすべてのデータが暗号化されます。 データベース データのバックアップは、社内の運用ポリシーに従って一定の期間、取得および保存されます。 ユーザーが本サービスを取り消した場合、法律で定められた保管義務を果たすために必要な範囲を除き、ユーザーのユーザー情報を遅れることなく削除します。 詳細は次のとおりです。 https://app.researchr.work/privacypolicy

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認&#26666;&#24335;&#20250;&#31038; アプリケーション登録のベスト プラクティス、その他の Id の条件を処理する方法に関する KBE によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
