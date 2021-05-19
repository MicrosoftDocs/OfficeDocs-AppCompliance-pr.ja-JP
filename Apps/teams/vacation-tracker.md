---
title: バケーショントラッカーによるバケーショントラッカーのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 02/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: バケーショントラッカー、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、およびCSA STARレジストリ内のセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 89ed0cc27e26acdeae13cc787fc180cc9f93b8ae
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550997"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 2 月 5 日</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

バケーショントラッカーがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Vacation Tracker |
| ID | WA200002167 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Vacation Tracker |
| パートナーウェブサイトのURL | [https://vacationtracker.io](https://vacationtracker.io) |
| アプリケーション情報ページTeams URL | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| プライバシーポリシーの URL | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| 利用規約の URL | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法と、アプリが収集するデータに対する組織のコントロールについて、バケーショントラッカーによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | 委任 | ユーザーが毎週または毎日の通知を設定すると、パブリック チャネル ID と名前を読み取ります。 | ユーザーは、バケーショントラッカーから毎日または毎週の通知を受信するチャンネルを選択できます。 ユーザーが優先チャネルを選択すると、チャネル ID が保存されます。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| Team.ReadBasic.All | 委任 | サインアップ中に参加したチームのMicrosoft Teamsが一覧表示され、ユーザーが休暇トラッカーにサインアップするチームを選択できます。 代わりに、組織全体にサインアップすることもできます。 | 選択したチームのMicrosoft Teamsチーム ID は、ユーザーが (組織全体ではなく) 1 つのチームとしてバケーション トラッカーにサインアップした場合にのみ保存されます。 チーム ID を使用して、ログインしているユーザーをバケーション トラッカーの既存のアカウントに接続します。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read | 委任 | 名前、ID、テナント ID などの基本的なユーザー情報を収集します。 このデータは、バケーショントラッカーでログインしたユーザーを組織に接続するために使用します。 | ユーザーの名前、ID、およびテナント ID を格納します。 このデータは、バケーショントラッカーでログインしたユーザーを組織に接続するために使用します。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.Read.All | 委任 | ユーザーは、Microsoft 365組織またはMicrosoft Teamsチームからすべてのユーザーをインポートできます。 この権限は、選択したMicrosoft Teamsのチームまたは組織のライセンスユーザーのみをインポートするために使用されます。 | インポートされたユーザーに関する基本情報 (名前、電子メール アドレス、ユーザー ID など) が格納されます。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| User.ReadBasic.All | 委任 | ユーザーは、組織またはMicrosoft Teamsチームから他のユーザーをインポートできます。 このアクセス許可を使用して、利用可能なユーザーとその電子メール アドレスをインポート ポップアップに表示します。 | ユーザーが休暇トラッカーにインポートする同僚を選択すると、名前、電子メール アドレス、ユーザー ID など、インポートされたユーザーに関する基本情報が保存されます。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| メール | 委任 | ユーザーが Microsoft AAD を使用してログインすると、一意の識別子として電子メール アドレスが格納されます。 | ユーザーの電子メールは一意の識別子として保存されます。 私たちは、この電子メールを通信に使用しません、ユーザーは、サインアップ中に通信に使用するビジネス用メールアドレスを入力します。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| offline_access | 委任 | この許可を得てデータを収集しません。 これは、アクセス許可を与えるデータへのアクセスを維持するために使用されます。 | この許可を得てデータを保存しません。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| openid | 委任 | この権限を使用して、ユーザーのサインインや、バケーショントラッカーへのサインアップを行います。 この許可を得て特定のデータを収集しません。 | この権限を使用して、ユーザーのサインインや、バケーショントラッカーへのサインアップを行います。 この許可を得て特定のデータを保存しません。 | eab5463e-8168-40ee-887a-7ac78de1d266 |
>| profile | 委任 | 名前、ID、テナント ID などの基本的なユーザー情報を収集します。 このデータは、バケーショントラッカーでログインしたユーザーを組織に接続するために使用します。 | ユーザーの名前、ID、およびテナント ID を格納します。 このデータは、バケーショントラッカーでログインしたユーザーを組織に接続するために使用します。 | eab5463e-8168-40ee-887a-7ac78de1d266 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>| **すべての非Microsoft サービス OII は、** |  **どのようなOIIが転送されますか?** | **OIIを転送するための正当性?** |
>|:-------------------|:--------------------------|:--------------------------|
>| ストライプ, AWS, クリスプ, Customer.io, セグメント, 振幅, グーグルタグマネージャー | 会社名 (ユーザーが入力した) | ユーザーがサインアップすると、会社名を入力し、この名前を製品内の組織名として使用します。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| ボットは、ボットと通信するユーザーに関する基本情報を確認できます。 ただし、その情報は保存または使用しません。 ユーザーの ID、会話 ID、およびボットに送信されたメッセージのみが使用されます。 | Microsoft は、ユーザーの電子メール アドレス、ユーザー名 (Microsoft AAD で定義されている) およびユーザーのプロファイル写真 (Microsoft AAD から) を格納します。 | 電子メール アドレスは、ユーザーの一意の識別子として、ユーザーの名前とプロフィール写真を使用して、同じ会社の管理者と承認者がダッシュボードで従業員を認識できるようにします。  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>会社名と、このタイプのデータに関する標準の 1 年間の保存ポリシーに従って会社名と会社名が保持され、削除されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>まず、ユーザーから必要な最小限のデータを収集します。 その後、パートナーと可能な限り最小限の情報を共有し、最終的にデータ保持ポリシーを作成し、該当する場合は 1 年以内にすべてのデータが削除されるようにします。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベストプラクティス、およびその他のID基準を処理する方法についてのバケーショントラッカーによって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| マイクロソフト識別プラットフォーム (Azure AD) と統合しますか。  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか。  | はい |
| アプリは認証に MSAL (マイクロソフト認証ライブラリ) を使用していますか? | いいえ |
| アプリで条件付きアクセス ポリシーがサポートされていますか。 | いいえ |
| アプリがシナリオに対して最低限の権限を要求しているか。 | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的に、または増分的に要求するアクセス許可を正確に反映していますか。 | はい |
| アプリでマルチテナント機能がサポートされていますか。 | はい |
| アプリに機密クライアントが存在しますか? | はい |
| アプリに登録されているすべてのリダイレクト統一リソース識別子 (URI) を所有していますか。 | はい |
| アプリの場合、何を使用しないようにしますか。 | - ワイルドカードリダイレクト URI<br/>- Spa に必要な場合を除き、OAuth2 暗黙的なFlow<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか。 | はい |
| クライアント アプリが適切な同意を得た場合にのみ、アクセス許可モデルで呼び出しが成功することを許可しますか。 | はい |
| アプリでプレビュー API を使用していますか。 | いいえ |
| アプリで非推奨の API が使用されていますか。 | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
