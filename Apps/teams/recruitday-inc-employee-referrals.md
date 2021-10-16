---
title: リクルートデイ社による従業員紹介のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 従業員紹介、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d83797a31c7ec68009ebf17773c3b8d2fe587fce
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413469"
---
# <a name="employee-referrals"></a>従業員についての参照資料

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 6 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/c179cdf6-f93d-4aa3-9e2d-e934e5a81846" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002708" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Recruitday Inc. から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | 従業員についての参照資料 |
| ID | WA200002708 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Recruitday Inc. |
| パートナー Web サイトの URL | [https://www.recruitday.com](https://www.recruitday.com) |
| [アプリケーション情報Teamsページの URL | [https://employer.recruitday.com/solutions/employee-referral...](https://employer.recruitday.com/solutions/employee-referrals/microsoft-teams) |
| プライバシー ポリシーの URL | [https://www.recruitday.com/privacy-policy](https://www.recruitday.com/privacy-policy) |
| 利用規約の URL | [https://www.recruitday.com/terms-of-use](https://www.recruitday.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つ制御に関して、リクルートデイ社から提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 両方とも | ファースト ネームと Last Name (アプリ ユーザー、つまり従業員) は、主に人事ユーザーが、紹介アプリケーション追跡とリワード支払いの候補者を参照した従業員を簡単に識別するために使用されます。 また、システムによって生成された電子メール通知の送信時に従業員に適切に対処するためにも使用されます。 | ファースト ネームと Last Name (アプリ ユーザー、つまり従業員) は、主に人事ユーザーが、紹介アプリケーション追跡とリワード支払いの候補者を参照した従業員を簡単に識別するために使用されます。 また、システムによって生成された電子メール通知の送信時に従業員に適切に対処するためにも使用されます。 | [7414b436-87d1-4904-9d52-ff47885b89f1](https://docs.microsoft.com/microsoft-365-app-certification/azure/7414b436-87d1-4904-9d52-ff47885b89f1) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 1. リクルートデイが次の目的で処理する場合: 1.1。 従業員アカウント 1.2 を作成します。 トランザクションとリマインダーに関するシステム生成の通知を送信する 2. 次の目的でユーザーの組織によって処理される: 2.1。 参照 2.2 のソースを特定します。 紹介 2.3 の成功に対して紹介報酬を受け取るユーザーを決定します。 システムへのアクセスを妨げる従業員を決定する (つまり、アクセスをブロックする) | 名、名、電子メール アドレス | 1. リクルートデイが次の目的で処理する場合: 1.1。 従業員アカウント 1.2 を作成します。 トランザクションとリマインダーに関するシステム生成の通知を送信する 2. 次の目的でユーザーの組織によって処理される: 2.1。 参照 2.2 のソースを特定します。 紹介 2.3 の成功に対して紹介報酬を受け取るユーザーを決定します。 システムへのアクセスを妨げる従業員を決定する (つまり、アクセスをブロックする) |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>管理者は、ポータル経由でユーザーのデータをアーカイブできます。 削除、更新などのその他の機能は、リクルートデイへの要求を介して行われます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 基準を処理する方法について、リクルートデイ社から提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | いいえ |
| アプリに機密クライアントがありますか? | 不要 |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリは Web API を公開していますか? | いいえ |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

