---
title: MIPA のアプリケーション情報 - My Intelligent Personal Assistant
ms.author: elmalova
author: elenamalova
ms.date: 06/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: MIPA で利用可能なすべてのセキュリティ情報とコンプライアンス情報 - My Intelligent Personal Assistant、データ処理ポリシー、Microsoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d7afb4021dfb969d4dca3a6171ad4710d5138488
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225024"
---
# <a name="mipa---my-intelligent-personal-assistant-by-iglobe"></a>MIPA - iGlobe による自分のインテリジェントパーソナル アシスタント

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 6 月 22 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.mipa" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

iGlobe から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | MIPA - インテリジェント パーソナル アシスタント |
| ID | 17859280.mipa |
| パートナー会社名 | iGlobe |
| パートナー Web サイトの URL | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| プライバシー ポリシーの URL | [https://instassl.iglobecrm.com/legal-information](https://instassl.iglobecrm.com/legal-information) |
| 使用条件の URL | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する iGlobe によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graphを使用したデータ アクセス

このアプリ[で必要な Microsoft Graphアクセス許可](/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当な理由は?** | **データは格納されますか?それを格納するための正当な理由は?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 委任 | アプリケーション データベースにはデータは格納されません。 | カレンダー全体の読み取りと更新 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Contacts.ReadWrite | 委任 | アプリケーション データベースにはデータは格納されません。 | カレンダー全体の読み取りと更新 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Directory.AccessAsUser.All | 委任 | アプリケーション データベースにはデータは格納されません。 | 読み取り、更新、パンナー タスクの作成、ユーザーの最近のファイルと共有ファイルの読み取り。 ユーザーが同意し、API を使用するアクセス権を持っていることを確認します。 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Directory.ReadWrite.All | 委任 | アプリケーション データベースにはデータは格納されません。 | 読み取り、更新、パンナー タスクの作成、ユーザーの最近のファイルと共有ファイルの読み取り、リスト、ライブラリ、ファイルSharePoint取得します。 SharePointリストにファイルを保存します。 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Files.ReadWrite.All | 委任 | アプリケーション データベースにはデータは格納されません。 | 読み取り、更新、パンナー タスクの作成、ユーザーの最近のファイルと共有ファイルの読み取り、リスト、ライブラリ、ファイルSharePoint取得します。 SharePointリストにファイルを保存します。 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Group.Read.All | 委任 | アプリケーション データベースにはデータは格納されません。 | 読み取り、更新、パンナー タスクの作成、ユーザーの最近のファイルと共有ファイルの読み取り、リスト、ライブラリ、ファイルSharePoint取得します。 SharePointリストにファイルを保存します。 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Group.ReadWrite.All | 委任 | アプリケーション データベースにはデータは格納されません。 | 読み取り、更新、パンナー タスクの作成、ユーザーの最近のファイルと共有ファイルの読み取り、リスト、ライブラリ、ファイルSharePoint取得します。 SharePointリストにファイルを保存します。 iGlobe CRM Office 365への統合 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Mail.ReadWrite | 委任 | アプリケーション データベースにはデータは格納されません。 | フラグ付きメールの読み取りと更新 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| MailboxSettings.ReadWrite | 委任 | アプリケーション データベースにはデータは格納されません。 | カレンダー全体の読み取りと更新、フラグ付きメールの読み取りと更新、Outlook To Do全体の読み取りと更新 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| Tasks.ReadWrite | 委任 | アプリケーション データベースにはデータは格納されません。 | カレンダー全体の読み取りと更新、読み取りと更新Outlook Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| User.Read | 委任 | アプリケーション データベースにはデータは格納されません。 | カレンダー全体の読み取りと更新、読み取りと更新Outlook Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| User.Read.All | 委任 | アプリケーション データベースにはデータは格納されません。 | カレンダー全体の読み取りと更新、Outlookの読み取りと更新、読み取り、更新、パンナー タスクの作成 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| User.ReadBasic.All | 委任 | アプリケーション データベースにはデータは格納されません。 | カレンダー全体の読み取りと更新、Outlookの読み取りと更新、読み取り、更新、パンナー タスクの作成 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| User.ReadWrite | 委任 | アプリケーション データベースにはデータは格納されません。 | カレンダー全体の読み取りと更新、読み取りと更新Outlook Do Entreies | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| メール | 委任 | アプリケーション データベースにはデータは格納されません。 | アプリがユーザーのプライマリ電子メール アドレスを読み取る (SSO の場合) ことを許可します。 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| offline_access | 委任 | アプリケーション データベースにはデータは格納されません。 | ユーザーが現在アプリを使用していない場合でも、アプリがアクセス権を付与したデータを表示および更新できるようにします。 これにより、アプリに追加のアクセス許可は付与されません (SSO の場合)。 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| openid | 委任 | アプリケーション データベースにはデータは格納されません。 | ユーザーが職場または学校のアカウントを使用してアプリにサインインし、アプリに基本的なユーザー プロファイル情報 (SSO の場合) を表示できるようにします。 | e854ea05-68ab-4204-babe-db4a784fb4d8 |
>| profile | 委任 | アプリケーション データベースにはデータは格納されません。 | カレンダー全体の読み取りと更新、Outlookの読み取りと更新、読み取り、更新、パンナー タスクの作成 | e854ea05-68ab-4204-babe-db4a784fb4d8 |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

Microsoft 365に基づいて構築されたアプリとアドインでは、Microsoft Graph以外の追加の Microsoft API を使用して、組織の識別可能な情報 (OII) を収集または処理できます。 このアプリで使用Graph Microsoft 以外の Microsoft API を一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集するための正当な理由** | **OII は格納されますか?** | **OII を格納するための正当な理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - Calendars.ReadWrite.All | いいえ |  |  |  |  |
>| Exchange - EWS。AccessAsUser.All | いいえ |  |  |  |  |
>| Exchange - Mail.Read | いいえ |  |  |  |  |
>| Exchange - Mail.ReadWrite.All | いいえ |  |  |  |  |
>| Exchange - MailboxSettings.Read | いいえ |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | いいえ |  |  |  |  |
>| Exchange - Tasks.ReadWrite | いいえ |  |  |  |  |
>| SharePoint - MyFiles.Read | いいえ |  |  |  |  |
>| SharePoint - MyFiles.Write | いいえ |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>使用されていないMicrosoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由の正当な理由を含めます。

>Microsoft サービス以外は使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

組織の識別可能な情報 (OII) またはエンド ユーザー識別情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はい場合は、保存されるデータと保持ポリシーと削除ポリシーについて説明します。

>iGlobe は、効果的に運用するためにデータを収集し、Microsoft の製品とサービスで最高のエクスペリエンスを提供します。 ライセンスの場合: 無料アドインの展開、試用版サブスクリプションの作成、サブスクリプションの購入など、組織&#8217;ライセンス アカウントを管理するために収集されたデータ。 次の情報が収集されます。 
- 財務目的: 会社名と住所
- サブスクライブしているユーザー: ユーザー名と電子メール

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって格納されたデータの組織コントロール

組織の管理者がパートナー システムで自分の情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンド ユーザー ポリシーなど。

>すべてのデータは、顧客自身のテナントにあります。 アプリケーション データは格納されません。 最新のアドインはサンドボックス ブラウザーで実行され、プロセス&#8221;&#8220;。 Microsoft サービスを使用してユーザー データと対話します。 アドインは、ユーザーが作業しているデータにのみアクセスできます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) カタログからの情報が次に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、およびその他の ID 条件を処理する方法に関する iGlobe によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか?  | はい |
| アプリは認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | いいえ |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | セキュリティの既定値とその他の一般的なポリシー (レガシ認証をブロックする* 管理者に MFA を要求する* Azure 管理に MFA を要求する* すべてのユーザーに MFA を要求する* など) |
| アプリでは、シナリオに対して最小限の特権アクセス許可が要求されますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | いいえ |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているすべてのリダイレクト統合リソース識別子 (URI) を所有していますか? | はい |
| アプリで Web API を公開していますか? | いいえ |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
