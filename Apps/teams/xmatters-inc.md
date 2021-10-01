---
title: xMatters Inc. による xMatters のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: cSA STAR レジストリ内の xMatters、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、およびセキュリティ/コンプライアンス情報に関する利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 1cb8d22b32d76f47bd64c0d4b4e3d3da311ecb46
ms.sourcegitcommit: 874e586a5a9a5eb0c5c5aae0c59f7c75c0742ec4
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/01/2021
ms.locfileid: "60080933"
---
# <a name="xmatters"></a>xMatters

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 8 月 31 日</p>

* <a href="https://teams.microsoft.com/l/app/ccfe5256-29b8-4cc2-95ed-6612c0e1b10d" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382013" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

xMatters Inc. から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | xMatters |
| ID | WA104382013 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | xMatters Inc. |
| パートナー Web サイトの URL | [https://www.xmatters.com](https://www.xmatters.com) |
| [アプリケーション情報Teamsページの URL | [https://help.xmatters.com/integrations/socialchat/microsoft...](https://help.xmatters.com/integrations/socialchat/microsoftteams.htm) |
| プライバシー ポリシーの URL | [https://www.xmatters.com/policy/privacy-policy/](https://www.xmatters.com/policy/privacy-policy/) |
| 利用規約の URL | [https://www.xmatters.com/policy/terms-conditions](https://www.xmatters.com/policy/terms-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールについて、xMatters Inc.によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft アプリケーションをGraph。

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft Teamsボット API | 不要 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google クラウド | スレッドに追加のメッセージを送信するために使用されるシステム識別子。 | xMatters から通知または応答するユーザーの詳細を含むスレッドを更新するために。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| メッセージング拡張機能で使用して、インシデント イニシエーターへのリンクをカードに追加します。 | 不要 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>ユーザーは、データを削除して作成を監査できます。 イベントまたはアラート ベースのデータは、組織の設定に従ってアーカイブおよび保存されます。

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

この情報は、xMatters Inc. によって、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity 条件を処理する方法について提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
