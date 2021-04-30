---
title: 365Apps による 365Projects のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 03/16/2021
ms.topic: article
ms.service: attestation
description: 365Projects で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d981f18f0001d14c2c6bb88fae95464fa6a62bde
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095678"
---
# <a name="365projects"></a>365Projects

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 3 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/a9c31598-b014-4e20-b3bd-3d275fa738d3" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002160" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Microsoft に 365Apps によって提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | 365Projects |
| ID | WA200002160 |
| 機能 | タブ、コネクタ |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | 365Apps |
| パートナー Web サイトの URL | [https://365projects.app](https://365projects.app) |
| [アプリケーション情報Teamsページの URL | [https://365projects.app](https://365projects.app) |
| プライバシー ポリシーの URL | [https://365projects.app/privacy](https://365projects.app/privacy) |
| 利用規約の URL | [https://365projects.app/eula](https://365projects.app/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する 365Apps によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Channel.ReadBasic.All | 委任 | プロジェクトをチャネルにリンクするチーム内のチャネル | プロジェクトをチャネルにリンクするチーム内のチャネル | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Group.Read.All | 委任 | チームプランナー/プランナーのタスクを取得する場合、別の最小特権スコープでアプリがユーザーの計画と計画タスクを取得できる方が良くなりますが、残念ながらこれを許可するスコープはありません | DB に格納しない | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Group.ReadWrite.All | アプリケーション | 作成Teams  | DB に格納されない | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| People.Read | 委任 | チーム メンバーとして追加したり、タスクを割り当てるには、ユーザー名を使用します。 | user Guid がタスクの割り当てに格納されている | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| Team.ReadBasic.All | 委任 | チーム名に参加し、プロジェクトをチャネルにTeamsする | チーム Guid は、リンクを確立するためにプロジェクト のメタデータに格納されます。 | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| User.Read | 委任 | ヘッダーに表示するユーザー情報を取得する  | ユーザーの電子メールは、テナントを最初にプロビジョニングするときに所有者として保存されます | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |
>| User.Read.All | 委任 | タスクの割り当てを更新するユーザーの読み取り | ユーザー Guid だけが格納され、個人を特定した情報は DB に保存されません | 99a0a9b1-5d28-45df-9f99-792aa32795f4 |


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

>アプリは、アプリ管理者の Guid とは別にユーザー データを格納しない (最初のユーザーがテナント内でアプリを使用する) 

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36555" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、365Apps が認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity の条件を処理する方法について提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | いいえ |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | ,
<br />
- OAuth2 暗黙的なFlow(SPA に必要な場合を含む)
<br />
 | |アプリは Web API を公開していますか? |はい | |アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? |はい | |アプリでプレビュー API を使用していますか? |いいえ| |アプリで非推奨の API を使用していますか? |いいえ|

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
