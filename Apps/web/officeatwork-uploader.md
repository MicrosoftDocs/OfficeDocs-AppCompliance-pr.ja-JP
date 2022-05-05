---
title: Uploader のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Uploader で使用可能なすべてのセキュリティ情報とコンプライアンス情報、データ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 0dec6f3975671223610272950956d4e5fd4085c0
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/05/2022
ms.locfileid: "65226111"
---
# <a name="application-information-for-uploader-by-officeatwork"></a>Officeatwork による Uploader のアプリケーション情報

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 6 月 23 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/officeatwork-ag.uploader" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Officeatwork から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | アップローダー |
| ID | officeatwork-ag.uploader |
| パートナー会社名 | officeatwork |
| パートナー Web サイトの URL | [https://www.officeatwork.com](https://www.officeatwork.com) |
| プライバシー ポリシーの URL | [https://links.officeatwork.com/officeatwork-privacystatement](https://links.officeatwork.com/officeatwork-privacystatement) |
| 使用条件の URL | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する officeatwork によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graphを使用したデータ アクセス

このアプリ[で必要な Microsoft Graphアクセス許可](/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当な理由は?** | **データは格納されますか?それを格納するための正当な理由は?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | 委任 | データは格納されません。 | OneDrive: ユーザーのOneDriveにデータを読み書きできるようにする。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| Group.ReadWrite.All | 委任 | データは格納されません。 | Teams: グループに対するデータの読み取りと書き込みを行います。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| GroupMember.Read.All | 委任 | データは格納されません。 | SharePoint オンライン - セキュリティ グループのサポート: アプリでグループの一覧表示、基本的なグループ プロパティの読み取り、サインインしているユーザーがアクセスできるすべてのグループのメンバーシップの読み取りを許可します。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| Sites.Read.All | 委任 | データは格納されません。 | SharePoint Online: SharePoint Online でデータの読み取りを有効にするには、サインインしているユーザーがアクセスできます。 SharePoint Online へのデータのアップロードを有効にするには | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| User.Read | 委任 | データは格納されません。 | Sing-In: officeatwork アプリがユーザーの基本プロパティを読み取られるようにします。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| User.Read.All | 委任 | データは格納されません。 | Teams: ユーザーが属しているグループを確認します。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| offline_access | 委任 | データは格納されません。 | Sing-In: 更新トークンを使用して自動サインインを有効にするには、ユーザーが officeatwork アプリを起動するたびに手動でサインインする必要があります。 このスコープは、SSO が有効でないホスト アプリケーションでのみ必要です。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| openid | 委任 | データは格納されません。 | Sing-In: ユーザーが組織または Microsoft アカウントを使用して officeatwork アプリにサインインできるようにします。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |
>| profile | 委任 | データは格納されません。 | Sing-In: Officeatwork アプリでサインインしているユーザーを表示します。 これにより、Officeatwork アプリへのサインインに使用されたアカウントをユーザーに保証/確認できます。 | f5c9f179-b9a5-4364-8f99-18d203b902ad |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

Microsoft 365に基づいて構築されたアプリとアドインでは、Microsoft Graph以外の追加の Microsoft API を使用して、組織の識別可能な情報 (OII) を収集または処理できます。 このアプリで使用Graph Microsoft 以外の Microsoft API を一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集するための正当な理由** | **OII は格納されますか?** | **OII を格納するための正当な理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint REST API | 不要 |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>使用されていないMicrosoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由の正当な理由を含めます。

>Microsoft サービス以外は使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

組織の識別可能な情報 (OII) またはエンド ユーザー識別情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はい場合は、保存されるデータと保持ポリシーと削除ポリシーについて説明します。

>はい。イベントには oid と tenantId が含まれており、Azure AppInsights に送信されます。 イベントは 90 日後に自動的に削除されます。 お客様がこのデータを削除したい場合は、プライバシーに関する声明に記載されているリンクを使用して、そのデータの削除を開始できます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって格納されたデータの組織コントロール

組織の管理者がパートナー システムで自分の情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンド ユーザー ポリシーなど。

>アプリケーション設定データ (機能フラグ、組織の表示名、tenantId、管理者 oid の一覧) は、Azure Cosmos DB インスタンス (テナントごとに 1 つのファイル) に格納されます。 DB ファイルは暗号化され、アクセスは選択した officeatwork エンジニアとサポート スタッフに制限されます。 顧客は、Admin Center Web アプリを使用して officeatwork アプリ設定データにアクセスして操作できます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>不要

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) カタログからの情報が次に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35750' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35750" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、およびその他の ID 条件を処理する方法に関する officeatwork によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか?  | はい |
| アプリは認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | 不要 |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | セキュリティの既定値 |
| アプリでは、シナリオに対して最小限の特権アクセス許可が要求されますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | 不要 |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているすべてのリダイレクト統合リソース識別子 (URI) を所有していますか? | はい |
| アプリでは、何を使用しないでくださいか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的なFlow(SPA に必要な場合を除く)<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリで Web API を公開していますか? | 不要 |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
