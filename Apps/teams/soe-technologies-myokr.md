---
title: SOE テクノロジによる myOKR のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 10/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: myOKR で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 71c27d24b0f93cafa4f899e845c8d056a55721eb
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60434546"
---
# <a name="myokr"></a>myOKR

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 6 月 18 日</p>

* <a href="https://teams.microsoft.com/l/app/c0b70874-2c95-4be7-a0cb-0d893e25a2a3" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003308" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

SOE Technologies から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | myOKR |
| ID | WA200003308 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | SOE Technologies |
| パートナー Web サイトの URL | [https://www.myokr.co](https://www.myokr.co) |
| [アプリケーション情報Teamsページの URL | [https://www.myokr.co](https://www.myokr.co) |
| プライバシー ポリシーの URL | [https://www.myokr.co/privacy](https://www.myokr.co/privacy) |
| 利用規約の URL | [https://www.myokr.co/terms](https://www.myokr.co/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する SOE Technologies によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 委任 | ユーザーカレンダーの詳細を取得して、ユーザーカレンダーで 1:1 会議を作成し、myOKR プラットフォームによって作成された更新または削除を行い、空き時間スロットを表示する | myOKR プラットフォームで作成された会議の作成された予定表 ID と参加 URL をデータベースに保存します。 | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| User.Read | 委任 | ユーザー azure オブジェクト ID を使用して、電子メールに対する Microsoft 認証を使用して myOKR アプリにユーザー ログインを行う | ユーザーの電子メールと Azure のアクティブ なオブジェクト ID | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| User.Read.All | アプリケーション | ユーザー情報を myOKR プラットフォームと同期し、場所、部門マネージャーなどのさまざまなユーザー カットに基づいて myOKR アプリケーション分析を管理者に表示 &amp; する | myOKR システムには、ユーザー ID、名前、メール、部署、役職、マネージャーの情報が保存されます。 | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| offline_access | 委任 | ユーザーの Azure アクティブ ディレクトリ ID | ユーザー カレンダーで定期的な会議を作成するには、オフライン アクセスを使用します。 | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |
>| openid | 委任 | Microsoft 認証を使用してユーザーが myOKR アプリにログインするには、ユーザー Azure オブジェクト ID を使用します。 | ユーザーのアクティブな Azure ID が電子メールに対して保存される | [5f5ab403-96ae-46a9-b78e-a06d60cc9e4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/5f5ab403-96ae-46a9-b78e-a06d60cc9e4e) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| ユーザー Active Azure Directory ID は、ボットからプロアクティブ メッセージを送信するユーザーの電子メールに対して格納されます。 | 電子メール、名前、マネージャー情報、タイトル、ユーザー id Azure Active Directory ID  | この情報は、myOKR アプリケーションで使用してユーザー アカウントを作成し、マネージャーが platfrom でレポートの詳細を表示し、管理者が部門、場所、マネージャーに基づいて全体的な分析とレポートを表示できます。 |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>組織 SPOC は、サービスの閉鎖について連絡を取り、そのデータは、30 日後に削除され、さらに 30 日後にデータベース バックアップからロールオーバーされます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 基準を処理する方法について SOE Technologies によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | 不要 |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | 不要 |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
