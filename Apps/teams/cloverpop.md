---
title: クローバーポップによるクローバーポップのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Cloverpop の利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: eaee7a04f4d8e74f97eef1fae358f80a0c3e2249
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553228"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年8月24日</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

クローバーポップがマイクロソフトに提供した情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Cloverpop |
| ID | WA200001803 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Cloverpop |
| パートナーウェブサイトのURL | [https://www.cloverpop.com](https://www.cloverpop.com) |
| プライバシーポリシーの URL | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| 利用規約の URL | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法と、アプリが収集するデータに対する組織のコントロールに関する Cloverpop によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 委任 | ユーザーデータを格納します。 電子メール、oid、与えられた名前、家族名、ユーザーアバター、ユーザーオブジェクトID.組織ID(テナントId)、組織の表示名、また、私たちは私たちのサイドチーム/チャンネル名、ID、チームメンバーに保存します。 ユーザーが決定を作成して対話する際に、このデータを作成したユーザー、チーム、および組織に関連付けます。 また、この所有権を人間に優しいUXで表示する必要があるため、ユーザー&#8217;のアバターなど、表示情報を保存しています。 | ユーザーがサインインし、サイレント ログイン&#8221;を有効にするためにアプリにアクセスをアプリに与える - 電子メール、名前、oid、tid、与えられた名前、姓、家族名、ユーザーアバター(写真)、組織の displayName | 1040474b-572d-4575-a423-95dd262a8b8a |
>| openid | 委任 | のようなユーザーデータを格納します。 電子メール、oid、与えられた名前、家族名、ユーザーアバター、ユーザーオブジェクトID.組織ID(テナントId)、組織の表示名、また、私たちは私たちのサイドチーム/チャンネル名、ID、チームメンバーに保存します。 ユーザーが決定を作成して対話する際に、このデータを作成したユーザー、チーム、および組織に関連付けます。 また、この所有権を人間に優しいUXで表示する必要があるため、ユーザー&#8217;のアバターなど、表示情報を保存しています。 | web アプリ&#8220;Teams&#8221;でサインインを実装します。 | 1040474b-572d-4575-a423-95dd262a8b8a |
>| profile | 委任 | のようなユーザーデータを格納します。 電子メール、oid、与えられた名前、家族名、ユーザーアバター、ユーザーオブジェクトID.組織ID(テナントId)、組織の表示名、また、私たちは私たちのサイドチーム/チャンネル名、ID、チームメンバーに保存します。 ユーザーが決定を作成して対話する際に、このデータを作成したユーザー、チーム、および組織に関連付けます。 また、この所有権を人間に優しいUXで表示する必要があるため、ユーザー&#8217;のアバターなど、表示情報を保存しています。 | web アプリ&#8220;Teams&#8221;でサインインを実装します。 | 1040474b-572d-4575-a423-95dd262a8b8a |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 特定のユーザーが決定に関連して行ったアクションを正確に表示するために、最初/最後/表示名データにアクセスします。 各ユーザーが複数の組織に属することを可能にするため、私たちは、db内の各ユーザーの一意の識別子として電子メールアドレスを使用します。 このデータは、アプリとやり取りする場合にのみアクセスします。 | 特定のユーザーが決定に関連して行ったアクションを正確に表示するために、最初/最後/表示名のデータを保存します。  各ユーザーが複数の組織に属することを許可するため、私たちは、db内の各ユーザーの一意の識別子として使用するため、電子メールアドレスを保存します。 このデータは、アプリとやり取りする場合にのみ保存されます。 当社の意思決定データは意思決定の記録のシステムであると考えられているので、意思決定に関与する各ユーザーがその決定にどのように貢献したかを特定するためのデータを保存することが重要です。 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>はい。
アプリがチーム内でやり取りされると、チーム ID がログに表示されます。
私たちは、すべて米国に拠点を置く3人の創設者に生産ログへのアクセスを制限しています。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>CloverpopアプリはRuby on Railsを使用して構築され、AWSをクラウドインフラストラクチャに利用するHeroku PaaS(サービスとしてのプラットフォーム)でホストされています。 Heroku と AWS の両方に、アクセスできる SOC レポートがあります。 私たちのアプリは、保存データストレージで暗号化するためにPostgreSQLを使用し、マルチテナント環境です。
 
すべてのコードは、データ アクセス セキュリティをカバーする自動テストを記述しています。 各ビルドでは、セキュリティに関する厳格なコード レビュー プロセスと、ユーザー認証のチェックと使用可能なユーザーアクションによるデータ アクセスを含む手動 QA テスト プロセスが実行されます。 当社の運用環境と、開発やテストなどの他のすべての環境との間には明確な分離があります。
 
一部の担当者だけが運用環境とデータベースにアクセスできます: 会社の創業者と、身元調査を受け、定量化されたニーズ (顧客サポートなど) を持っている少数の審査済み従業員。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

