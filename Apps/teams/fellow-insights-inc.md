---
title: フェローによるフェロー向けアプリケーション情報 インサイト Inc.
ms.author: elmalova
author: elenamalova
ms.date: 06/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: フェローに利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4fb839013c38dcf7b490e02810ad5726be0aabda
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428594"
---
# <a name="fellow"></a>Fellow

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 5 月 21 日</p>

* <a href="https://teams.microsoft.com/l/app/f6671df0-1909-428c-91f7-1c42df04d3e4" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002576" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

フェロー インサイト Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Fellow |
| ID | WA200002576 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Fellow Insights Inc |
| パートナー Web サイトの URL | [https://fellow.app](https://fellow.app) |
| プライバシー ポリシーの URL | [https://fellow.app/privacy-policy/](https://fellow.app/privacy-policy/) |
| 利用規約の URL | [https://fellow.app/terms-of-use/](https://fellow.app/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関して、フェロー インサイト Inc. から提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 両方とも | フェローはユーザーの予定表に接続して、データにメモを取る機能を提供します。 | Fellow は、ユーザーのプライマリ カレンダーのすべてのイベント データを格納します。 添付ファイルは保存されません。 これは、カレンダーベースのメモ作成エクスペリエンスを提供するために、Fellow 内で使用されます。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Channel.ReadBasic.All | 委任 | ユーザーがメンバーであるチャネルの名前を収集して、メモを送信できるチャネルの一覧を表示します。 | ユーザーが Fellow から指定したチャネルにメモを送信するために、ユーザーがメンバーであるチャネルの名前と ID をキャッシュします。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Directory.Read.All | アプリケーション | このデータは、組織全体に対して管理者のインストールが行われた場合にのみ収集されます。 ディレクトリ データを使用して、ユーザーの一覧を同期し、アカウントを自動的にプロビジョニングします。 | 管理者が Fellow 内のワークスペース設定内から組織全体のインストールを実行する場合にのみ、管理者は Azure AD から Fellow (自動プロビジョニング) へのすべてのユーザーの自動同期を有効にできます。 この場合、ID、Name、Email、Manager、グループ メンバーシップなどのユーザー情報 (チーム管理機能用) が格納されます。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Group.Read.All | アプリケーション | このデータは、組織全体に対して管理者のインストールが行われた場合にのみ収集されます。 ディレクトリ データを使用して、ユーザーの一覧を同期し、アカウントを自動的にプロビジョニングします。 | 管理者が Fellow 内のワークスペース設定内から組織全体のインストールを実行する場合にのみ、管理者は Azure AD から Fellow (自動プロビジョニング) へのすべてのユーザーの自動同期を有効にできます。 この場合、ID、Name、Email、Manager、グループ メンバーシップなどのユーザー情報 (チーム管理機能用) が格納されます。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read | 委任 | ユーザーの連絡先は、特定の連絡先の表示名と電子メール アドレスで収集されます。 これは、フェロー内で、メモへの招待やメモの共有に招待するユーザーのリストを提供するために使用されます。 | ユーザーの連絡先は、特定の連絡先の表示名と電子メール アドレスで収集されます。 これは、フェロー内で、メモへの招待やメモの共有に招待するユーザーのリストを提供するために使用されます。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| People.Read.All | アプリケーション | このデータは、組織全体に対して管理者のインストールが行われた場合にのみ収集されます。 ユーザーの連絡先は、特定の連絡先の表示名と電子メール アドレスで収集されます。 これは、フェロー内で、メモへの招待やメモの共有に招待するユーザーのリストを提供するために使用されます。 | 管理者が Fellow 内のワークスペース設定内から組織全体のインストールを実行する場合にのみ、管理者は Azure AD から Fellow (自動プロビジョニング) へのすべてのユーザーの自動同期を有効にできます。 この場合、ユーザーの連絡先は、特定の連絡先 displayNames と電子メール アドレスで収集されます。 これは、フェロー内で、メモへの招待やメモの共有に招待するユーザーのリストを提供するために使用されます。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| Team.ReadBasic.All | 委任 | ユーザーが参加しているチームの一覧が収集されます。 これは、ユーザーがフェローからチームにメモを送信することを許可する目的で、fellow 内で使用されます。 | ユーザーがメンバーであるチームの名前と ID をキャッシュして、ユーザーが Fellow から指定したチーム チャネルにメモを送信できます。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read | 委任 | 基本的なユーザー情報が収集されます。 ユーザー名、電子メール、役職。 この情報は、Fellow 内でユーザー アカウントと会社アカウントを作成するために使用されます。 | 基本的なユーザー情報が格納されます。 ユーザー名、電子メール、役職。 この情報は、ユーザー アカウントと会社アカウントを管理するために、Fellow 内で使用されます。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| User.Read.All | アプリケーション | このデータは、組織全体に対して管理者のインストールが行われた場合にのみ収集されます。 ディレクトリ データを使用して、ユーザーの一覧を同期し、アカウントを自動的にプロビジョニングします。 | 管理者が Fellow 内のワークスペース設定内から組織全体のインストールを実行する場合にのみ、管理者は Azure AD から Fellow (自動プロビジョニング) へのすべてのユーザーの自動同期を有効にできます。 この場合、ID、Name、Email、Manager、グループ メンバーシップなどのユーザー情報 (チーム管理機能用) が格納されます。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |
>| offline_access | 委任 | 他のスコープを介して収集されたデータへのアクセスを維持するためのユーザーの更新トークン。 | ユーザーの更新トークンはデータベースに格納されます。 これは、カレンダーベースのメモ作成エクスペリエンスのバックグラウンドでイベントを同期し、スケジュールされたイベントにメモを取る通知を同期するために、フェロー内で使用されます。 | [f6671df0-1909-428c-91f7-1c42df04d3e4](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6671df0-1909-428c-91f7-1c42df04d3e4) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>フェローは、個人データを含む、ユーザーが直接提供する情報を保存します。 また、フェローは、OAuth データ、予定表データ、名前電子メールなどの PII など、サード パーティ製システムからの情報も格納 &amp; します。 弊社は、収集された目的のために必要で法的に許容される限り、すべてのデータを無期限に保持します。 ユーザーからの要求を受け取った時点で、この情報を安全に削除します。 ログ データは 30 日間保持されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>すべてのデータ転送は、セキュリティで保護された API からバックエンド システムに対して行われます。 フェローは、AICPA で定義されている SOC 2 フレームワークに従って、システムのセキュリティと機密性を確保するために多くのコントロールを採用しています。 フェローの管理は、継続的なコンプライアンスを確保するために年次監査を受けます。 SOC 2 レポートは、要求に応じて NDA と共有できます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>不要

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39739" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 基準を処理する方法について、フェロー インサイト Inc. から提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | いいえ |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | ,<br/><br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | いいえ |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
