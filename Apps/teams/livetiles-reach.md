---
title: LiveTiles によるリーチのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 03/22/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Reach の利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 83df050a6f58bc1d0b7d49239b40ddf2ba80849a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551998"
---
# <a name="reach"></a>Reach

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021年3月22日</p>

* <a href="https://teams.microsoft.com/l/app/5df8ebd2-bf7b-4fb5-bb35-0bfbf5d10a23" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002045" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

マイクロソフトにライブタイルによって提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Reach |
| ID | WA200002045 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | LiveTiles |
| パートナーウェブサイトのURL | [https://livetilesglobal.com](https://livetilesglobal.com) |
| アプリケーション情報ページTeams URL | [https://livetilesglobal.com/products/livetiles-reach/](https://livetilesglobal.com/products/livetiles-reach/) |
| プライバシーポリシーの URL | [https://livetilesglobal.com/privacy-policy](https://livetilesglobal.com/privacy-policy) |
| 利用規約の URL | [https://livetilesglobal.com/eula](https://livetilesglobal.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法、およびアプリが収集するデータに対する組織のコントロールに関する LiveTiles によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| TeamsActivity.Send | アプリケーション | none | none | a7c1920d-3ac0-42db-9757-078a2b321fd8  |
>| User.Read | 委任 | ユーザー表示名、ユーザーの電子メール アドレス、UPN。 ユーザーがアプリにサインインし、サインインしているユーザーの基本情報 (表示名など) を取得できるようにするために必要です。 電子メール アドレスは、電子メール通知の送信に使用されます。  | ユーザー表示名、ユーザーの電子メール アドレス、UPN。 ユーザーがアプリにサインインし、サインインしているユーザーの基本情報 (表示名など) を取得できるようにするために必要です。 電子メール アドレスは、電子メール通知の送信に使用されます。  | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| User.ReadBasic.All | 委任 | ユーザー表示名、ユーザー電子メール アドレス、UPN、ユーザー部門、ユーザーの役職、ユーザーの携帯電話電話番号、ユーザービジネス電話番号、ユーザー Office場所。 ユーザーがアプリ内で他のユーザーを検索できるようにする (電話帳) し、他のユーザーの基本的なプロファイルと連絡先情報を表示するために必要です。  | none | d492530a-8cff-481c-90da-9c3c3f1be7da |
>| Directory.Read.All | アプリケーション | グループ メンバーシップ、ディレクトリ内の AD グループ。 ユーザーのグループ メンバーシップは、Microsoft Graph API への呼び出しを最小限に抑えるためにキャッシュに格納されます。 ユーザーがアクティブ ディレクトリ グループを検索できるようにするには必須です。 さらに、このアクセス許可は、バックエンドの Web ジョブでユーザーの AD グループ メンバーシップを解決するアプリケーションに必要です。 | ユーザーのグループ メンバーシップ。 ユーザーのグループ メンバーシップは、Microsoft Graph API への呼び出しを最小限に抑えるためにキャッシュに格納されます。 ユーザーがアクティブ ディレクトリ グループを検索できるようにするには必須です。 さらに、このアクセス許可は、バックエンドの Web ジョブでユーザーの AD グループ メンバーシップを解決するアプリケーションに必要です。  | d492530a-8cff-481c-90da-9c3c3f1be7da  |
>| User.Read.All | アプリケーション | ユーザー プロファイルから取得されるデータは、アプリ内で指定された対象ユーザーの設定によって異なります。 サインインしているユーザーなしでアプリがユーザー プロファイルを読み取ることができるようにするために必要です。 プロファイル データの読み取りは、アプリケーション内の情報ターゲット機能に必要であり、特定のプロファイル プロパティ値に基づいて特定のユーザーに情報が表示されるようにします。  | none | d492530a-8cff-481c-90da-9c3c3f1be7da  |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>| **すべての非Microsoft サービス OII は、** |  **どのようなOIIが転送されますか?** | **OIIを転送するための正当性?** |
>|:-------------------|:--------------------------|:--------------------------|
>| 送信グリッド、ワンシグナル | メールアドレス、表示名 | メールとモバイルプッシュ通知を介してユーザーに通知を送信 |

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>電子メール アドレス、UPN。 最大60日間の保持、その後、それらが削除されます

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>管理者は、任意の問い合わせのサポートに連絡することができます

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36551" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、およびその他の ID 条件を処理する方法について LiveTiles によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| マイクロソフト識別プラットフォーム (Azure AD) と統合しますか。  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか。  | いいえ |
| アプリは認証に MSAL (マイクロソフト認証ライブラリ) を使用していますか? | はい |
| アプリで条件付きアクセス ポリシーがサポートされていますか。 | はい |
| サポートされているポリシーの種類を一覧表示する | 多要素認証、ユーザーの場所と IP 範囲の制限 |
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
