---
title: コーナーストーン OnDemand による CSOD Learn のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 07/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSOD Learn、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報に関する利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 2064ed00ba6306d86a09b3eff9dc6e56c8d1cc40
ms.sourcegitcommit: 34fde42f42c623b37d1db154bf348bdc8b76a8c7
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/19/2021
ms.locfileid: "58407480"
---
# <a name="csod-learn"></a>CSOD Learn

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 7 月 1 日</p>

* <a href="https://teams.microsoft.com/l/app/81726ee9-4d27-47ad-8b22-08147c6f8613" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003020" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Cornerstone OnDemand から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | CSOD Learn |
| ID | WA200003020 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Cornerstone OnDemand |
| パートナー Web サイトの URL | [https://www.cornerstoneondemand.com](https://www.cornerstoneondemand.com) |
| プライバシー ポリシーの URL | [https://www.cornerstoneondemand.com/client-privacy-policy/](https://www.cornerstoneondemand.com/client-privacy-policy/) |
| 利用規約の URL | [https://www.microsoft.com/en-us/microsoft-teams/group-chat-...](https://www.microsoft.com/en-us/microsoft-teams/group-chat-software) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Cornerstone OnDemand によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft アプリケーションをGraph。


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 組織データは、CSOD Services と Microsoft の間で共有されます。 詳細については、「CSOD との契約条件」を参照してください。 | 組織データは、CSOD Services と Microsoft の間で共有されます。 詳細については、「CSOD との契約条件」を参照してください。 | CSOD サービスは、API のGraph使用します。 Microsoft frameworks botbuilder^4.9.2 をサービスのパフォーマンスに使用します。 OII データは、CSOD サービスコンシューマーを識別するためにサービスによって使用されます。 詳細については、「CSOD との契約条件」を参照してください。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| この点に関する情報については、CSOD との契約条件を参照してください。 | エンド ユーザー aadObjectId の CSOD ユーザー内部 ID へのマッピング | この点に関する情報については、CSOD との契約条件を参照してください。 |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>CSOD サービスは、アプリとのユーザー操作を含むアプリケーション ログを一期間保存して、バグやユーザーから報告された問題のトラブルシューティングを行います。 個々のログ ステートメントは、エンド ユーザーの内部 lms ユーザー ID、CSOD サービス内で構成された組織名、および実行される適切なアクションで構成されます。 はい

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>CSOD サービスへのアクセスは、エンド ユーザー組織の管理者によって制御されます。 詳細については、「CSOD との契約条件」を参照してください。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

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

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について Cornerstone OnDemand によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
