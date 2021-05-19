---
title: 365Appによる365プロジェクトのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 03/16/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 365Projects、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、およびCSA STARレジストリ内のセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d760c1c5bacf37fa23e26f4a9a15eb7dbbd75bb1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553468"
---
# <a name="365projects"></a>365Projects

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021年3月16日</p>

* <a href="https://teams.microsoft.com/l/app/a9c31598-b014-4e20-b3bd-3d275fa738d3" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002160" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

365Apps がマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | 365Projects |
| ID | WA200002160 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | 365Apps |
| パートナーウェブサイトのURL | [https://365projects.app](https://365projects.app) |
| アプリケーション情報ページTeams URL | [https://365projects.app](https://365projects.app) |
| プライバシーポリシーの URL | [https://365projects.app/privacy](https://365projects.app/privacy) |
| 利用規約の URL | [https://365projects.app/eula](https://365projects.app/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法、およびアプリが収集するデータに対する組織のコントロールに関する 365Apps によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Channel.ReadBasic.All | 委任 | プロジェクトをチャネルにリンクするチーム内のチャネル | プロジェクトをチャネルにリンクするチーム内のチャネル | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Group.Read.All | 委任 | チーム プランナー/プランナー のタスクを取得する、別の最小特権のスコープは、アプリがユーザーの計画を取得し、タスクを計画するが、悲しいことにこれを許可するスコープがない場合は、より良いだろう | DB に格納されない | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Group.ReadWrite.All | アプリケーション | Teamsの作成  | DB に格納されていません | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| People.Read | 委任 | ユーザー名:チーム メンバーとして追加するか、タスクを割り当てる | ユーザー Guid はタスク割り当てに格納されます | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Team.ReadBasic.All | 委任 | 参加チーム名、プロジェクトをTeamsチャンネルにリンク | チーム GUID は、リンクを確立するためにプロジェクト のメタデータに格納されます。 | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| User.Read | 委任 | ヘッダーに表示するユーザー情報の取得  | ユーザーの電子メールは、テナントを最初にプロビジョニングするときに所有者として保存されます。 | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| User.Read.All | 委任 | タスクの割り当てを更新するためにユーザーを読み取る | ユーザー Guid のみが保存されている個人識別情報は、DB に格納されません。 | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>アプリは、アプリ管理者の Guid 以外のユーザー データを格納しません (最初のユーザーは、テナント内でアプリを使用します) 

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、およびその他の ID 条件を処理する方法に関する 365Apps によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| マイクロソフト識別プラットフォーム (Azure AD) と統合しますか。  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか。  | はい |
| アプリは認証に MSAL (マイクロソフト認証ライブラリ) を使用していますか? | はい |
| アプリで条件付きアクセス ポリシーがサポートされていますか。 | いいえ |
| アプリがシナリオに対して最低限の権限を要求しているか。 | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的に、または増分的に要求するアクセス許可を正確に反映していますか。 | はい |
| アプリでマルチテナント機能がサポートされていますか。 | はい |
| アプリに機密クライアントが存在しますか? | いいえ |
| アプリに登録されているすべてのリダイレクト統一リソース識別子 (URI) を所有していますか。 | はい |
| アプリの場合、何を使用しないようにしますか。 | ,<br/>- Spa に必要な場合を除き、OAuth2 暗黙的なFlow<br/> |
| アプリは Web API を公開していますか。 | はい |
| クライアント アプリが適切な同意を得た場合にのみ、アクセス許可モデルで呼び出しが成功することを許可しますか。 | はい |
| アプリでプレビュー API を使用していますか。 | いいえ |
| アプリで非推奨の API が使用されていますか。 | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
