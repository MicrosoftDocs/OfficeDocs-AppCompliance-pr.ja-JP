---
title: SalesTim による SalesTim のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: SalesTim、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 912f828c405178b056c50b261e408617e239f540
ms.sourcegitcommit: ddedb98532d7cef5cff47b137aa0ad87494b163d
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/02/2022
ms.locfileid: "64627259"
---
# <a name="salestim"></a>SalesTim

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 6 月 24 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/salestim.salestim" target="_blank">AppSource での表示</a>

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
| 利用規約の URL | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する SalesTim によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph を使用したデータ アクセス

このアプリが[必要とする microsoft Graphアクセス許可](/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | 委任 | 動作しない | アプリが企業アプリ カタログに独自のパッケージをインストールして更新できます。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | 委任 | プロファイル データ&#8217;、一部のユーザーの ID のみを保存する必要があります。 | ユーザーは、ワークフロー内の承認者の選択など、アプリケーションのさまざまな場所で他のユーザーを選択できます。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | 委任 | グループ&#8217;チームの ID のみを格納する必要があります。グループ/チームの&#8217;は保存されません。 | サインインしているユーザーに代わって、アプリがグループを作成し、すべてのグループ プロパティとメンバーシップを読み取ることができます。 さらに、グループの所有者が自身のグループを管理できるよう、またグループ メンバーがグループのコンテンツを更新できるようにします。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | 委任 | 通知&#8217;、受信者 (ID のみ)、要求 ID など、このアクションのメタデータを再格納する必要があります。 | アプリが承認ワークフロー中に、たとえば通知メールを送信できます。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | 委任 | Azure サービスの一部を使用してデータを格納しています。特に Azure および DB 上の Redis Cosmosしています | チームのプロビジョニング プロセス中に、チームに関連付けられたドライブ (ファイルとフォルダー) を管理できます。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | 委任 | プロファイル データ&#8217;、一部のユーザーの ID のみを保存する必要があります。 | アプリが、すべてのユーザーのプロファイル プロパティ、レポート、および管理者の完全なセットを読み取ることができます。 これは、現在のユーザー プロファイルに基づいてコンテンツをフィルター処理するために、特に対象ユーザーのターゲット設定プロセス中に使用されます。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| offline_access | 委任 | いいえ | アプリがユーザーとしていくつかのバックグラウンド操作とアクションを実行できます。 | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **すべての非Microsoft サービス OII がに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-------------------|:--------------------------|:--------------------------|
>| メイン サポート アプリケーションとして Intercom を使用しています。 Intercom には、次の説明に従って、いくつかの基本的なユーザー プロファイル情報が含まれている場合があります。 https://developers.salestim.com/platform/datamanagement.html#support-data | 会社名 | この API では、GitHubを使用して、実稼働環境から自動的に問題を生成しています。 また、いくつかの技術的なログをGitHub説明https://developers.salestim.com/platform/datamanagement.html#error-reporting-data)します。 これらの問題とログには、いくつかの基本的なユーザー プロファイル情報が含まれている場合があります。 これらの問題とログは、15 日ごとに自動的に削除されます。 |



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>収集されたデータはすべてここで説明します。 https://developers.salestim.com/platform/datamanagement.html#application-data 説明に従って、ログは 15 日間一時的に保存され、自動的に削除されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>ほとんどのデータは Azure Cosmos DB に格納されます。
実稼働環境へのアクセスは 2 人に制限され、これらの管理者アカウントは MFA が適用されます。
これらのアカウントは専用であり、企業アカウントとは異なります。
データは、使用しているすべての Azure サービスで保存時に暗号化されます。
実稼働環境への展開は、2 人だけが変更を承認できる GitHub環境の専用の保護されたブランチを通じて自動化されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

次[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報を示します。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 条件を処理する方法について SalesTim によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | MFA、場所の条件 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | ,<br/>- OAuth2 暗黙的Flow、SPA に必要な場合を含む場合を含む<br/> |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
