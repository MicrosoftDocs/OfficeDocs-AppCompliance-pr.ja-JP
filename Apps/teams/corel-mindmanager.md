---
title: Corel による MindManager のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 05/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: MindManager で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 69efbc45560d3271f03f8af8e9cfeb1aa7c89e5d
ms.sourcegitcommit: 41be194e2be4de3cdb686daee7a8f6e4d1fc765a
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/11/2021
ms.locfileid: "52904543"
---
# <a name="mindmanager"></a>MindManager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 5 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/cebe4a59-b076-47f3-a7bf-79148daf82f7" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002261" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Corel が Microsoft に提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | MindManager |
| ID | WA200002261 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Corel |
| パートナー Web サイトの URL | [https://www.mindmanager.com](https://www.mindmanager.com) |
| プライバシー ポリシーの URL | [https://www.corel.com/en/corel-privacy-policy/](https://www.corel.com/en/corel-privacy-policy/) |
| 利用規約の URL | [https://www.mindjet.com/go/mmcloudterms](https://www.mindjet.com/go/mmcloudterms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Corel によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ChannelMessage.Send | 委任 | メッセージとして投稿できる MindManager ファイル内で行われた変更に関する情報 | ファイル メタデータ、ファイル コンテンツ - ファイル ブラウザーの場合、ユーザーはファイルを参照して MindManager (.mmap) ファイルを開きます。 | 51e2b67d-9854-446a-8da1-cdd89ef0b987 |
>| Chat.Send | 委任 | メッセージとして投稿できる MindManager ファイル内で行われた変更に関する情報 | ファイル メタデータ、ファイル コンテンツ - ファイル ブラウザーの場合、ユーザーはファイルを参照して MindManager (.mmap) ファイルを開きます。 | 51e2b67d-9854-446a-8da1-cdd89ef0b987 |
>| Files.ReadWrite | 委任 | サイト一覧、フォルダー一覧、ファイル メタデータ、ファイル コンテンツ - ファイル ブラウザーの場合、ユーザーはファイルを参照して MindManager (.mmap) ファイルを開きます。 | - プロファイル データ: ユーザーを識別し、そのユーザーのプロファイルを表示する - ファイル コンテンツ: 共同編集セッション中 (MindManager .mmap ファイルのリアルタイム共同編集) | 51e2b67d-9854-446a-8da1-cdd89ef0b987 |
>| Sites.ReadWrite.All | 委任 | サイト一覧、フォルダー一覧、ファイル メタデータ、ファイル コンテンツ - ファイル ブラウザーの場合、ユーザーはファイルを参照して MindManager (.mmap) ファイルを開きます。 | ファイルコンテンツ: 共同編集セッション中 (MindManager .mmap ファイルのリアルタイム共同編集) | 51e2b67d-9854-446a-8da1-cdd89ef0b987 |
>| User.Read | 委任 | プロファイル データ: ユーザーを識別してプロファイルを表示する | プロファイル データ: ユーザーを識別してプロファイルを表示する | 51e2b67d-9854-446a-8da1-cdd89ef0b987 |
>| offline_access | 委任 | これにより、必要に応じて後でユーザーの代わりにファイルを元の場所に保存できます。 | ファイルコンテンツ: 共同編集セッション中 (MindManager .mmap ファイルのリアルタイム共同編集) | 51e2b67d-9854-446a-8da1-cdd89ef0b987 |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-------------------|:--------------------------|:--------------------------|
>| Amazon Web Services | 組織名、組織ドメイン | 組織内でアプリケーションを使用するには、アプリケーション インフラストラクチャ内でアカウントのセットアップが必要Teams |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>ここで説明します。 https://www.mindjet.com/go/mmcloudterms

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38778' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38778" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity 条件を処理する方法について Corel によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | いいえ |
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
