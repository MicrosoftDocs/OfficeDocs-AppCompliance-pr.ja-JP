---
title: Nulia Works by Nulia のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 03/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Nulia Works の利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4471074b2e15b41894f709cb2a25dee1d0dc5187
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552898"
---
# <a name="nulia-works"></a>Nulia Works

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 3 月 11 日</p>

* <a href="https://teams.microsoft.com/l/app/e49e0f69-600c-460c-80b3-8809a9d97a4c" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002051" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Nulia から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Nulia Works |
| ID | WA200002051 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Nulia |
| パートナー Web サイトの URL | [https://nulia.com](https://nulia.com) |
| [アプリケーション情報Teamsページの URL | [https://nulia.com/product](https://nulia.com/product) |
| プライバシー ポリシーの URL | [https://nulia.com/privacy](https://nulia.com/privacy) |
| 利用規約の URL | [https://nulia.com/terms](https://nulia.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Nulia によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | アプリケーション | 収集されたデータを使用して、スキルと結果に関するユーザーの進捗状況を評価します。 複数の O365 ワークロードにわたる使用状況カウントを収集します。 | 収集したデータはすべて BLOB ストレージに格納されます。 このデータを使用して、スキルと結果の進行状況についてユーザーにスコアを付け取っています。 たとえば、ユーザーが持つ予定表イベントの数をカウントします。 この値は、スキルの進捗状況に影響します。 | お客様ごとに新しいアプリケーション ID を作成します。 たとえば、Nulia テナントはアプリケーション ID 623B1D5D-6D82-493E-9990-1FBFE82ED046 を使用しています。 |
>| Contacts.Read | アプリケーション | 収集されたデータを使用して、スキルと結果に関するユーザーの進捗状況を評価します。 複数の O365 ワークロードにわたる使用状況カウントを収集します。 | 収集したデータはすべて BLOB ストレージに格納されます。 このデータを使用して、スキルと結果の進行状況についてユーザーにスコアを付け取っています。 たとえば、ユーザーが作成した連絡先の数をカウントします。 この値は、スキルの進捗状況に影響します。 | お客様ごとに新しいアプリケーション ID を作成します。 たとえば、Nulia テナントはアプリケーション ID 623B1D5D-6D82-493E-9990-1FBFE82ED046 を使用しています。 |
>| Files.Read.All | アプリケーション | 収集されたデータを使用して、スキルと結果に関するユーザーの進捗状況を評価します。 複数の O365 ワークロードにわたる使用状況カウントを収集します。 | 収集したデータはすべて BLOB ストレージに格納されます。 このデータを使用して、スキルと結果の進行状況についてユーザーにスコアを付け取っています。 たとえば、ユーザーがコンピューターと同期しているファイルの数をカウントします。 この値は、スキルの進捗状況に影響します。 | お客様ごとに新しいアプリケーション ID を作成します。 たとえば、Nulia テナントはアプリケーション ID 623B1D5D-6D82-493E-9990-1FBFE82ED046 を使用しています。 |
>| Group.Read.All | アプリケーション | 収集されたデータを使用して、スキルと結果に関するユーザーの進捗状況を評価します。 複数の O365 ワークロードにわたる使用状況カウントを収集します。 | 収集したデータはすべて BLOB ストレージに格納されます。 このデータを使用して、スキルと結果の進行状況についてユーザーにスコアを付け取っています。 たとえば、ユーザーが属するグループTeams取得します。 この値は、スキルの進捗状況に影響します。 | お客様ごとに新しいアプリケーション ID を作成します。 たとえば、Nulia テナントはアプリケーション ID 623B1D5D-6D82-493E-9990-1FBFE82ED046 を使用しています。 |
>| Mail.Read | アプリケーション | 収集されたデータを使用して、スキルと結果に関するユーザーの進捗状況を評価します。 複数の O365 ワークロードにわたる使用状況カウントを収集します。 | 収集したデータはすべて BLOB ストレージに格納されます。 このデータを使用して、スキルと結果の進行状況についてユーザーにスコアを付け取っています。 たとえば、ユーザーが作成したカスタム メール フォルダーの数をカウントします。 この値は、スキルの進捗状況に影響します。 | お客様ごとに新しいアプリケーション ID を作成します。 たとえば、Nulia テナントはアプリケーション ID 623B1D5D-6D82-493E-9990-1FBFE82ED046 を使用しています。 |
>| MailboxSettings.Read | アプリケーション | 収集されたデータを使用して、スキルと結果に関するユーザーの進捗状況を評価します。 複数の O365 ワークロードにわたる使用状況カウントを収集します。 | 収集したデータはすべて BLOB ストレージに格納されます。 このデータを使用して、スキルと結果の進行状況についてユーザーにスコアを付け取っています。 たとえば、ユーザーがアウトオブオフィスの返信セットを持つ場合を確認します。 この値は、スキルの進捗状況に影響します。 | お客様ごとに新しいアプリケーション ID を作成します。 たとえば、Nulia テナントはアプリケーション ID 623B1D5D-6D82-493E-9990-1FBFE82ED046 を使用しています。 |
>| Notes.Read | アプリケーション | 収集されたデータを使用して、スキルと結果に関するユーザーの進捗状況を評価します。 複数の O365 ワークロードにわたる使用状況カウントを収集します。 | 収集したデータはすべて BLOB ストレージに格納されます。 このデータを使用して、スキルと結果の進行状況についてユーザーにスコアを付け取っています。 たとえば、ユーザーが共有したノートブックの数をカウントします。 この値は、スキルの進捗状況に影響します。 | お客様ごとに新しいアプリケーション ID を作成します。 たとえば、Nulia テナントはアプリケーション ID 623B1D5D-6D82-493E-9990-1FBFE82ED046 を使用しています。 |
>| Reports.Read.All | アプリケーション | 収集されたデータを使用して、スキルと結果に関するユーザーの進捗状況を評価します。 複数の O365 ワークロードにわたる使用状況カウントを収集します。 | 収集したデータはすべて BLOB ストレージに格納されます。 このデータを使用して、スキルと結果の進行状況についてユーザーにスコアを付け取っています。 たとえば、ユーザーレポートから、1 日に送信Teamsメッセージの数を取得します。 この値は、スキルの進捗状況に影響します。 | お客様ごとに新しいアプリケーション ID を作成します。 たとえば、Nulia テナントはアプリケーション ID 623B1D5D-6D82-493E-9990-1FBFE82ED046 を使用しています。 |
>| Sites.Read.All | アプリケーション | 収集されたデータを使用して、スキルと結果に関するユーザーの進捗状況を評価します。 複数の O365 ワークロードにわたる使用状況カウントを収集します。 | 収集したデータはすべて BLOB ストレージに格納されます。 このデータを使用して、スキルと結果の進行状況についてユーザーにスコアを付け取っています。 たとえば、ユーザーが作成したサイト コレクションの数をカウントします。 この値は、スキルの進捗状況に影響します。 | お客様ごとに新しいアプリケーション ID を作成します。 たとえば、Nulia テナントはアプリケーション ID 623B1D5D-6D82-493E-9990-1FBFE82ED046 を使用しています。 |
>| User.Read | アプリケーション | ユーザーの表示名、部署、プロファイル画像が表示されます。 | データベースに表示名と部署を保存しますので、毎回検索にアクセスするGraph必要があります。 プロファイル画像は保存しない。 | お客様ごとに新しいアプリケーション ID を作成します。 たとえば、Nulia テナントはアプリケーション ID 623B1D5D-6D82-493E-9990-1FBFE82ED046 を使用しています。 |
>| Organization.Read.All | アプリケーション | テナントの名前と基本 URL をYammerします。 これを使用して、ユーザー Yammerアクティビティに関連するアプリの [Try It] ボタンをクリックすると、Yammer &quot; &quot; します。 | 収集したデータはすべて BLOB ストレージに格納されます。 たとえば、ユーザーがアプリの [試Yammer] ボタンをクリックすると、アクティビティに関連するアプリを起動Yammer &quot; &quot; します。 | 収集されたデータを使用して、スキルと結果に関するユーザーの進捗状況を評価します。 複数の O365 ワークロードにわたる使用状況カウントを収集します。 |


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

>パートナー システム上のデータを制御しない

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36557" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 条件を処理する方法について Nulia によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
