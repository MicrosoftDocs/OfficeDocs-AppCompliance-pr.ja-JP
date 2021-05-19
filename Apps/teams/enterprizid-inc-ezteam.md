---
title: エンタープリズID社によるezTeamの申請情報
ms.author: elmalova
author: elenamalova
ms.date: 02/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: ezTeamの利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STARレジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: da54d5a540fd43c2bdc25a6f4e31ba88520ecbc3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553178"
---
# <a name="ezteam"></a>ezTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 2 月 24 日</p>

* <a href="https://teams.microsoft.com/l/app/b02f0b53-d3b7-4d53-85a9-f820f5ab33c7" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002546" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

エンタープリズID社がマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | ezTeam |
| ID | WA200002546 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | EnterprizID Inc |
| パートナーウェブサイトのURL | [https://enterprizid.com](https://enterprizid.com) |
| アプリケーション情報ページTeams URL | [https://enterprizid.com/discover/](https://enterprizid.com/discover/) |
| プライバシーポリシーの URL | [https://enterprizid.com/privacy-policy/](https://enterprizid.com/privacy-policy/) |
| 利用規約の URL | [https://enterprizid.com/terms-of-use/](https://enterprizid.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法、およびアプリが収集するデータに対する組織のコントロールに関する EnterprizID Inc.によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.Read.All | 委任 | Teamsで利用可能なアプリのリストを使用して、リクエスト作成プロセスで表示Teams可能 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Application.Read.All | 委任 | サインインしたユーザーの代理としてアプリとサービスプリンシパルを読み取ることをアプリに許可します。 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.AccessAsUser.All | 委任 | サインインしているユーザーと同じように、アプリでディレクトリ内の情報にアクセスできるようにします。 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | 委任 | アプリで、ユーザー、グループ、アプリなどの組織のディレクトリ内のデータを読み取ることができるようにします。 | Teams所有権とメンバーシップ情報  | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.Read.All | アプリケーション | サインインしているユーザーなしで、ユーザー、グループ、アプリなどの組織のディレクトリ内のデータをアプリで読み取りできるようにします。 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | 委任 | アプリが組織のディレクトリ (ユーザー、グループなど) のデータを読み書きできるようにします。 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Directory.ReadWrite.All | アプリケーション | アプリで、サインインしているユーザーなしで、ユーザー、グループなどの組織のディレクトリ内のデータを読み取りと書き込みができるようにします。ユーザーまたはグループの削除はできません。 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Files.Read.All | アプリケーション | アプリで、サインインしているユーザーなしで、すべてのサイト コレクション内のすべてのファイルを読み取れるようにします。 | エンド ユーザー のガバナンス下のデータ量 (GB) | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Create | アプリケーション | アプリは、サインインしているユーザーなしでグループを作成できます。 | 新しいグループ プロパティの詳細。 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | 委任 | アプリで、サインインしているユーザーの代わりに、グループを一覧表示し、グループのプロパティとすべてのグループ メンバーシップを読み取ることができるようにします。 マイTeamsを決定するために使用  | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.Read.All | アプリケーション | アプリがグループ のプロパティとメンバーシップを読み取り、サインインしているユーザーなしですべてのグループのカレンダーと会話を読み取ることができます。 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | 委任 | アプリで、サインインしているユーザーの代わりに、グループを作成したり、すべてのグループのプロパティとメンバーシップを読み取ったりできるようにします。  | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Group.ReadWrite.All | アプリケーション | アプリでグループの作成、すべてのグループ プロパティとメンバーシップの読み取り、グループ のプロパティとメンバーシップの更新、グループの削除を行うことができます。 また、アプリは、グループのカレンダーや会話を読み書きすることができます。  | チームの最後のアクティビティ。 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.Read.All | アプリケーション | アプリで、サインインしているユーザーがいなくても、すべてのグループのメンバーシップおよび基本的なグループのプロパティを読み取れるようにします。 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| GroupMember.ReadWrite.All | アプリケーション | サインインしているユーザーがいなくても、グループのリスト、基本的なプロパティの読み取り、およびこのアプリのグループのメンバーシップの読み取りと更新をアプリに許可します。 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| People.Read.All | アプリケーション | アプリは、サインインしているユーザーなしで、関連するユーザーのユーザーのスコア付きリストを読み取ることができます。 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | 委任 | サインインしているユーザーの代わりに、アプリですべてのサービス利用状況レポートの読み取りを実行できるようにします。 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Reports.Read.All | アプリケーション | アプリでサインインしているユーザーがいなくても、すべてのサービス利用状況レポートの読み取りができるようにします。 | グループごとの最後のユーザー アクティビティ | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| Sites.ReadWrite.All | アプリケーション | アプリは、サインインしているユーザーなしで、すべてのサイト コレクション内のドキュメントの作成、読み取り、更新、削除と、アイテムの一覧表示を行うことができます。 | 各ユーザーのサイズ別上位 10 サイト | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read | 委任 | ユーザーがアプリにサインインできるようにし、アプリがサインインしているユーザーのプロファイルを読み取ることができます。 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| User.Read.All | アプリケーション | アプリは、サインインしているユーザーなしで、ユーザー プロファイルを読み取ることができます。 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| offline_access | 委任 | ユーザーが現在アプリを使用していない場合でも、アクセス権を付与したデータをアプリで表示および更新できるようにします。  | ボット通知 | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| openid | 委任 | ユーザーが職場または学校アカウントでアプリにサインインできるようにします。またアプリで、ユーザーの基本的なプロファイル情報を読み取れるようにします。 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |
>| profile | 委任 | アプリでユーザーの基本プロファイル (名前、画像、ユーザー名) を表示できます。 | 該当なし | 2b1fb18f-54e4-4b08-9ef2-5610d0fffa8b |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| ウェルカム メッセージ、承認、および構成証明プロセスの通知 | ID の表示名を保存します  | このツールを使用すると、エンドユーザーはさまざまなサービスアイテムのリクエストを作成でき、依頼者の表示名を保存できます。 要求は承認ワークフローに従い、要求の詳細を表示するには承認者の表示名が必要です。 さらに、チーム認定プロセスのメンバーには、メンバーの表示名を一覧表示します。 |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>エンドユーザーと組織のフル ネーム。 保存と削除のポリシーは、[ https://enterprizid.com/privacy-policy &quot; 個人データの保持] &quot; セクションにあります。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>Azure 内の特権アクセス管理 (PMA) を有効にし、リソースに接続する特権を持つ ID は、セキュリティを強化するために 2FA を使用します。 Azure をクラウド パートナー プロバイダーとして使用しており、Azure のプライバシーと利用規約が適用されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36552" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、およびその他の ID 条件を処理する方法について、EnterprizID Inc.によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| マイクロソフト識別プラットフォーム (Azure AD) と統合しますか。  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか。  | はい |
| アプリは認証に MSAL (マイクロソフト認証ライブラリ) を使用していますか? | いいえ |
| アプリで条件付きアクセス ポリシーがサポートされていますか。 | いいえ |
| アプリがシナリオに対して最低限の権限を要求しているか。 | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的に、または増分的に要求するアクセス許可を正確に反映していますか。 | はい |
| アプリでマルチテナント機能がサポートされていますか。 | はい |
| アプリに機密クライアントが存在しますか? | いいえ |
| アプリに登録されているすべてのリダイレクト統一リソース識別子 (URI) を所有していますか。 | はい |
| アプリの場合、何を使用しないようにしますか。 | - ワイルドカードリダイレクト URI<br/>- Spa に必要な場合を除き、OAuth2 暗黙的なFlow<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか。 | はい |
| クライアント アプリが適切な同意を得た場合にのみ、アクセス許可モデルで呼び出しが成功することを許可しますか。 | はい |
| アプリでプレビュー API を使用していますか。 | はい |
| アプリで非推奨の API が使用されていますか。 | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
