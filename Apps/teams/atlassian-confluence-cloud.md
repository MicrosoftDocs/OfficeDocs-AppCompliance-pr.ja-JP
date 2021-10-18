---
title: Atlassian による Confluence Cloud のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Confluence Cloud で利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 965ac513d4d13a0995b992a5022bc4f7d9e44a9f
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60427169"
---
# <a name="confluence-cloud"></a>Confluence Cloud

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 8 月 18 日</p>

* <a href="https://teams.microsoft.com/l/app/30bb610c-6321-40fe-a047-056e7d0dac96" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003113" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Atlassian から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Confluence Cloud |
| ID | WA200003113 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Atlassian |
| パートナー Web サイトの URL | [https://www.atlassian.com](https://www.atlassian.com) |
| プライバシー ポリシーの URL | [https://www.atlassian.com/legal/privacy-policy](https://www.atlassian.com/legal/privacy-policy) |
| 利用規約の URL | [https://www.atlassian.com/licensing/marketplace/termsofuse](https://www.atlassian.com/licensing/marketplace/termsofuse) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールについて、Atlassian によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | 委任 | - 会議のチャット メンバーの一覧を読み取ったので、会議への招待者の一覧が分かっています。   - 会議アプリに条件付&#8217;表示するユーザー名と電子メール アドレスを読み取る。 たとえば、会議メモを取っている現在のユーザーの名前を表示します。   - アプリは、&#8217;に追加された予定表イベントのユーザーを読み取り、会議のタイトルなどの会議に関する基本情報を取得します。 | 収集および保存するコンテンツの例には、JIRA の問題に追加された概要と説明、Confluence で作成したページ、Bitbucket でのリポジトリとプル要求、Statuspage のインシデントに関連して入力したコメント、およびフィードバックが含まれます。 コンテンツには、サービスにアップロードするファイルとリンクも含まれます。 | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| Chat.ReadBasic | 委任 |  - 会議のチャット メンバーの一覧を読み取ったので、会議への招待者の一覧が分かっています。   - 会議アプリに条件付&#8217;表示するユーザー名と電子メール アドレスを読み取る。 たとえば、会議メモを取っている現在のユーザーの名前を表示します。   - アプリは、&#8217;に追加された予定表イベントのユーザーを読み取り、会議のタイトルなどの会議に関する基本情報を取得します。 | 収集および保存するコンテンツの例には、JIRA の問題に追加された概要と説明、Confluence で作成したページ、Bitbucket でのリポジトリとプル要求、Statuspage のインシデントに関連して入力したコメント、およびフィードバックが含まれます。 コンテンツには、サービスにアップロードするファイルとリンクも含まれます。 | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| User.ReadBasic.All | 委任 | - 会議のチャット メンバーの一覧を読み取ったので、会議への招待者の一覧が分かっています。   - 会議アプリに条件付&#8217;表示するユーザー名と電子メール アドレスを読み取る。 たとえば、会議メモを取っている現在のユーザーの名前を表示します。   - アプリは、&#8217;に追加された予定表イベントのユーザーを読み取り、会議のタイトルなどの会議に関する基本情報を取得します。 | 収集および保存するコンテンツの例には、JIRA の問題に追加された概要と説明、Confluence で作成したページ、Bitbucket でのリポジトリとプル要求、Statuspage のインシデントに関連して入力したコメント、およびフィードバックが含まれます。 コンテンツには、サービスにアップロードするファイルとリンクも含まれます。 | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| メール | 委任 | - 会議のチャット メンバーの一覧を読み取ったので、会議への招待者の一覧が分かっています。   - 会議アプリに条件付&#8217;表示するユーザー名と電子メール アドレスを読み取る。 たとえば、会議メモを取っている現在のユーザーの名前を表示します。   - アプリは、&#8217;に追加された予定表イベントのユーザーを読み取り、会議のタイトルなどの会議に関する基本情報を取得します。 | 収集および保存するコンテンツの例には、JIRA の問題に追加された概要と説明、Confluence で作成したページ、Bitbucket でのリポジトリとプル要求、Statuspage のインシデントに関連して入力したコメント、およびフィードバックが含まれます。 コンテンツには、サービスにアップロードするファイルとリンクも含まれます。 | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| offline_access | 委任 | - 会議のチャット メンバーの一覧を読み取ったので、会議への招待者の一覧が分かっています。   - 会議アプリに条件付&#8217;表示するユーザー名と電子メール アドレスを読み取る。 たとえば、会議メモを取っている現在のユーザーの名前を表示します。   - アプリは、&#8217;に追加された予定表イベントのユーザーを読み取り、会議のタイトルなどの会議に関する基本情報を取得します。 | 収集および保存するコンテンツの例には、JIRA の問題に追加された概要と説明、Confluence で作成したページ、Bitbucket でのリポジトリとプル要求、Statuspage のインシデントに関連して入力したコメント、およびフィードバックが含まれます。 コンテンツには、サービスにアップロードするファイルとリンクも含まれます。 | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| openid | 委任 |  - 会議のチャット メンバーの一覧を読み取ったので、会議への招待者の一覧が分かっています。   - 会議アプリに条件付&#8217;表示するユーザー名と電子メール アドレスを読み取る。 たとえば、会議メモを取っている現在のユーザーの名前を表示します。   - アプリは、&#8217;に追加された予定表イベントのユーザーを読み取り、会議のタイトルなどの会議に関する基本情報を取得します。 | 収集および保存するコンテンツの例には、JIRA の問題に追加された概要と説明、Confluence で作成したページ、Bitbucket でのリポジトリとプル要求、Statuspage のインシデントに関連して入力したコメント、およびフィードバックが含まれます。 コンテンツには、サービスにアップロードするファイルとリンクも含まれます。 | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |
>| profile | 委任 |  - 会議のチャット メンバーの一覧を読み取ったので、会議への招待者の一覧が分かっています。   - 会議アプリに条件付&#8217;表示するユーザー名と電子メール アドレスを読み取る。 たとえば、会議メモを取っている現在のユーザーの名前を表示します。   - アプリは、&#8217;に追加された予定表イベントのユーザーを読み取り、会議のタイトルなどの会議に関する基本情報を取得します。 | 収集および保存するコンテンツの例には、JIRA の問題に追加された概要と説明、Confluence で作成したページ、Bitbucket でのリポジトリとプル要求、Statuspage のインシデントに関連して入力したコメント、およびフィードバックが含まれます。 コンテンツには、サービスにアップロードするファイルとリンクも含まれます。 | [4aa38041-66a2-41a4-ac97-55bc828a9803](https://docs.microsoft.com/microsoft-365-app-certification/azure/4aa38041-66a2-41a4-ac97-55bc828a9803) |


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

>https://www.atlassian.com/trust/privacy/how-we-handle-your-data

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>不要

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22926' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22926" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について、Atlassian によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | いいえ |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | いいえ |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
