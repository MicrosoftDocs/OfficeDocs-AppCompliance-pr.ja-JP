---
title: Carnduff Co による CoffeePals のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 07/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CoffeePals で利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 2f058ef9ce4f3d19644a6223c394afefa257085b
ms.sourcegitcommit: 0f47d02fff001cd7cba6a7ab9e276e020cfc053e
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/27/2021
ms.locfileid: "53610027"
---
# <a name="coffeepals"></a>CoffeePals

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 7 月 9 日</p>

* <a href="https://teams.microsoft.com/l/app/0905c41d-9f67-4ab7-8d94-4e2da3d2ff08" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003040" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Carnduff Co から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | CoffeePals |
| ID | WA200003040 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Carnduff Co |
| パートナー Web サイトの URL | [https://coffeepals.co](https://coffeepals.co) |
| [アプリケーション情報Teamsページの URL | [https://coffeepals.co/product](https://coffeepals.co/product) |
| プライバシー ポリシーの URL | [https://coffeepals.co/privacy](https://coffeepals.co/privacy) |
| 利用規約の URL | [https://coffeepals.co/terms-of-service](https://coffeepals.co/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて、Carnduff Co によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft アプリケーションをGraph。


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Analytics, Stripe, Mailchimp, Heroku, MongoDB Atlas, AWS, Logentries | ユーザーの電子メール アドレス、支払い情報 (ストライプで処理)、名と名 | アプリが支払われるので、クレジット カード情報と連絡先情報が必要です。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| ユーザーの名前にアクセスして、コーヒー用にユーザーと一致するメッセージでユーザーを参照し、電子メール アドレスを保存して支払いを収集するために Web アプリにログインします。 名前を使用すると、エクスペリエンスのカスタマイズが行われ、電子メール アドレスが一意の識別子として使用され、ログインへのリンクが送信されます。 | 電子メール アドレス、名と名。 | データは保存され、ユーザーの照合、メッセージング、ログインのために必要な度に取得する必要がなされません。 |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>バグのデータが不足している場合は、システム内のデータを変更できます。 また、お客様からの要求に応じてデータを追加および削除できます。 厳密なデータ保護プロトコルの概要に従います https://coffeepals.co/security 。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/41839' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/41839" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity 条件を処理する方法について Carnduff Co によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
