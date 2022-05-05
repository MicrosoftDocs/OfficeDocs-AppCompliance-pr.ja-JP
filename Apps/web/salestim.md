---
title: SalesTim のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: SalesTim で使用可能なすべてのセキュリティ情報とコンプライアンス情報、データ処理ポリシー、Microsoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9fce7871fc306b19170cddb2d1524ef7a82a01f4
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/05/2022
ms.locfileid: "65222438"
---
# <a name="application-information-for-salestim-by-salestim"></a>SalesTim by SalesTim のアプリケーション情報

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 6 月 24 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/salestim.salestim" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

SalesTim から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | SalesTim |
| ID | salestim.salestim |
| パートナー会社名 | SalesTim |
| パートナー Web サイトの URL | [https://salestim.com](https://salestim.com) |
| プライバシー ポリシーの URL | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| 使用条件の URL | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて、SalesTim によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graphを使用したデータ アクセス

このアプリ[で必要な Microsoft Graphアクセス許可](/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当な理由は?** | **データは格納されますか?それを格納するための正当な理由は?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | 委任 | 動作しない | アプリが企業アプリ カタログに独自のパッケージをインストールして更新できるようにします。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | 委任 | プロファイル データではなく、一部のユーザー ID のみを保存&#8217;。 | ユーザーは、ワークフローで承認者を選択するなど、アプリケーションのさまざまな場所で他のユーザーを選択できます。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | 委任 | グループ/チーム ID のみを保存&#8217;、グループやチームのコンテンツは保存&#8217;。 | アプリでグループを作成し、サインインしているユーザーに代わってすべてのグループ プロパティとメンバーシップを読み取ることを許可します。 さらに、グループの所有者が自身のグループを管理できるよう、またグループ メンバーがグループのコンテンツを更新できるようにします。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | 委任 | 通知日、受信者 (ID のみ)、要求 ID など、このアクションのメタデータを保存&#8217;。 | 承認ワークフロー中に、アプリが通知メールを送信できるようにします。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | 委任 | 一部の Azure サービスを使用してデータを格納しています。特に Azure および Cosmos DB 上の Redis | チームのプロビジョニング プロセス中に、アプリがチームに関連付けられているドライブ (ファイルとフォルダー) を管理できるようにします。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | 委任 | プロファイル データではなく、一部のユーザー ID のみを保存&#8217;。 | アプリで、任意のユーザーのプロファイル プロパティ、レポート、およびマネージャーの完全なセットを読み取ります。 これは、対象ユーザーのターゲット設定プロセス中に特に使用され、現在のユーザー プロファイルに基づいて一部のコンテンツをフィルター処理します。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| offline_access | 委任 | いいえ | アプリがユーザーとしていくつかのバックグラウンド操作とアクションを実行できるようにします。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>使用されていないMicrosoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由の正当な理由を含めます。

>| **Microsoft サービス以外のすべての OII は、** |  **転送される OII は何ですか?** | **OII を転送するための正当な理由** |
>|:-------------------|:--------------------------|:--------------------------|
>| メイン サポート アプリケーションとして Intercom を使用しています。 Intercom には、次に説明するように、いくつかの基本的なユーザー プロファイル情報が含まれている場合があります。 https://developers.salestim.com/platform/datamanagement.html#support-data | 会社名 | GitHub API を使用して、運用環境から問題を自動的に生成しています。 また、いくつかの技術ログをGitHubに格納しています (以下で説明しますhttps://developers.salestim.com/platform/datamanagement.html#error-reporting-data))。 これらの問題とログには、いくつかの基本的なユーザー プロファイル情報が含まれている可能性があります。 これらの問題とログは、15 日ごとに自動的に削除されます。 |



#### <a name="telemetry-data"></a>テレメトリ データ

組織の識別可能な情報 (OII) またはエンド ユーザー識別情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はい場合は、保存されるデータと保持ポリシーと削除ポリシーについて説明します。

>収集されたすべてのデータについては、ここで説明します。 https://developers.salestim.com/platform/datamanagement.html#application-data 説明したように、ログは 15 日間一時的に保存され、自動的に削除されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって格納されたデータの組織コントロール

組織の管理者がパートナー システムで自分の情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンド ユーザー ポリシーなど。

>ほとんどのデータは、Azure Cosmos DB に格納されます。
運用環境へのアクセスは 2 人に制限されており、これらの管理者アカウントは MFA が適用されます。
これらのアカウントは専用であり、会社のアカウントとは異なります。
データは、使用しているすべての Azure サービスで保存時に暗号化されます。
運用環境へのデプロイは、GitHub環境内の専用の保護されたブランチを通じて自動化され、変更を承認できるのは 2 人だけです。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) カタログからの情報が次に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、およびその他の ID 条件を処理する方法に関する SalesTim によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか?  | はい |
| アプリは認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | MFA、場所の条件 |
| アプリでは、シナリオに対して最小限の特権アクセス許可が要求されますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているすべてのリダイレクト統合リソース識別子 (URI) を所有していますか? | はい |
| アプリでは、何を使用しないでくださいか? | ,<br/>- OAuth2 暗黙的なFlow(SPA に必要な場合を除く)<br/> |
| アプリで Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ、呼び出しを成功させることができますか? | はい |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
