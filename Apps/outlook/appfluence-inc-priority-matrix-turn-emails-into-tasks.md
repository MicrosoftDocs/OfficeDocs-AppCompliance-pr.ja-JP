---
title: プライオリティ・マトリックスのアプリケーション情報 - 電子メールをAppfluence Inc.によるタスクに変換
ms.author: elmalova
author: elenamalova
ms.date: 04/16/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Priority Matrixのすべての利用可能なセキュリティおよびコンプライアンス情報 - 電子メールをタスク、データ処理ポリシー、Microsoft Cloud App Securityアプリカタログ情報、CSA STARレジストリのセキュリティ/コンプライアンス情報に変換します。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 9843ece5a330f4a8b8adb6f1388a4a26e12dbe21
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553758"
---
# <a name="priority-matrix---turn-emails-into-tasks"></a>優先度マトリックス - メールをタスクに変換する

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者による最終更新日: 2021年4月16日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381735" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

マイクロソフトに提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | 優先度マトリックス - メールをタスクに変換する |
| ID | WA104381735 |
| サポートされるクライアントOffice 365 | Outlook 2016以降のWindows、Outlook 2016以降、macでOutlook、iOSでOutlook、AndroidでOutlook、ウェブ上でOutlook |
| パートナー会社名 | Appfluence Inc |
| パートナーウェブサイトのURL | [https://appfluence.com/](https://appfluence.com/) |
| プライバシーポリシーの URL | [https://appfluence.com/privacy](https://appfluence.com/privacy) |
| 利用規約の URL | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法、およびアプリが収集するデータに対する組織のコントロールに関する Appfluence Inc. によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | 委任 | 新しいユーザーがアカウントに追加された場合にのみ、メールを保存します。 | 新しいアカウントの作成では、これを使用して他のチーム メンバーを提案します。 | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| User.ReadBasic.All | 委任 | 新しいユーザーがアカウントに追加された場合にのみ、メールを保存します。 | 新しいアカウントの作成では、これを使用して他のチーム メンバーを提案します。 | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| offline_access | 委任 | ユーザーに代わって要求を実行するためにログイントークンを保存します | ユーザーに煩わされることなくトークンを更新する。 (Teamsのプライオリティマトリクス) | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| Files.Read.All | 委任 | ユーザーが明示的かつ故意に元のファイルにリンクする優先度マトリックス項目を作成しない限り、ファイル情報は保存しません。 | One-one 機能 (Web アプリと Outlook/Teams アドインを通じて利用できます) では、この機能を使用して、会議や全体的なコラボレーションを円滑に進める方法として、システム内の 2 人のユーザー間で共有されるSharePoint/OneDrive ファイルを強調表示します。 | アファドfb6-f17b-428f-97f9-9aae3b6175bc |
>| User.Read | 委任 | 基本的なユーザープロファイル情報(表示名、名、姓、電子メール、アバター)は、当社によって保存されます。 | ユーザーの名前、電子メール、アバターを取得し、アカウントをパーソナライズします。 | アファドfb6-f17b-428f-97f9-9aae3b6175bc |
>| openid | 委任 | ユーザーのログイン モードを示す SSO 接続を格納します。 | シングル サインオンを使用してユーザーにサインインする場合。 | アファドfb6-f17b-428f-97f9-9aae3b6175bc |
>| Calendars.Read | 委任 | 少数のカレンダーイベントは、システムに保存されたタスクに変わります。 | カレンダーイベントを読み、1:1 ビューに表示できるようにします。 また、新しいアカウントを初期化します。  | d76f016f-52c7-41b5-835b-900361d7040c |
>| Mail.Read | 委任 | システムに作成されたタスクを、元のメッセージへのリンクと共に保存します。 | 電子メールをタスクに変換し、共有作業を 1:1 ビューで表示するために、Outlook アドインで使用されます。 | d76f016f-52c7-41b5-835b-900361d7040c |
>| Tasks.Read | 委任 | いくつかのOutlook/プランナータスクは、新しいユーザーを支援するために、当社のシステムに複製されています。 | 新しいユーザー アカウントをGraphタスクでブートストラップします。 | d76f016f-52c7-41b5-835b-900361d7040c |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>はい、当社は、ユーザーの電子メールをシステム内の一意のIDとして使用し、アプリケーションエラーを追跡し、システムの主要なイベント(ダウンロード、サインイン、アプリケーションバージョンなど)を追跡するために使用されるため、カスタマーサービスチームが顧客の問い合わせに迅速に対応できるようにします。 GDPR のコンプライアンスの一環として、削除要求から 2 週間以内にすべての顧客データを削除しますが、実際には半自動で行う内部スクリプトが用意されています。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>アプリケーション データは、少数の管理者グループに制限されたアクセスで、暗号化されたデータベースに安全に格納されます。 アクセスをさらに安全にするため、2 要素認証を実施し、制御された IP アドレスへのアクセスを制限し、オープンインターネットから直接アクセスできない専用サブネット内のデータベースを検索します。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベストプラクティス、およびその他のID基準を処理する方法についてAppfluence Inc.によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| マイクロソフト識別プラットフォーム (Azure AD) と統合しますか。  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか。  | はい |
| アプリは認証に MSAL (マイクロソフト認証ライブラリ) を使用していますか? | はい |
| アプリで条件付きアクセス ポリシーがサポートされていますか。 | いいえ |
| アプリがシナリオに対して最低限の権限を要求しているか。 | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的に、または増分的に要求するアクセス許可を正確に反映していますか。 | はい |
| アプリでマルチテナント機能がサポートされていますか。 | はい |
| アプリに機密クライアントが存在しますか? | はい |
| アプリに登録されているすべてのリダイレクト統一リソース識別子 (URI) を所有していますか。 | はい |
| アプリの場合、何を使用しないようにしますか。 | - ワイルドカードリダイレクト URI<br/><br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか。 | はい |
| クライアント アプリが適切な同意を得た場合にのみ、アクセス許可モデルで呼び出しが成功することを許可しますか。 | はい |
| アプリでプレビュー API を使用していますか。 | いいえ |
| アプリで非推奨の API が使用されていますか。 | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
