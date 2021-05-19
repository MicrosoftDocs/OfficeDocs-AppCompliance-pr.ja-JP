---
title: スライデイ株式会社によるカルマのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: カルマの利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、およびCSA STARレジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9da5f26e68be07cc9817c50434e214de3f3784c4
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551637"
---
# <a name="karma"></a>Karma

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/9ff28b02-ccc5-4cac-9d17-4cf6987c371f" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381640" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

スライデイ株式会社がマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Karma |
| ID | WA104381640 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Sliday LTD |
| パートナーウェブサイトのURL | [https://karmabot.chat/ms](https://karmabot.chat/ms) |
| アプリケーション情報ページTeams URL | [https://karmabot.readme.io/](https://karmabot.readme.io/) |
| プライバシーポリシーの URL | [https://karmabot.readme.io/v3.0/docs/privacy-policy-for-mic...](https://karmabot.readme.io/v3.0/docs/privacy-policy-for-microsoft-teams) |
| 利用規約の URL | [https://karmabot.readme.io/docs/karma-end-user-license-agre...](https://karmabot.readme.io/docs/karma-end-user-license-agreement-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法と、アプリが収集するデータに対する組織のコントロールについて、Sliday LTDによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | アプリケーション | 姓、姓、会社のメールアドレス。管理者がレポートに直面する名、姓。カルマ、請求目的、ヘルアーキーに関する通信用のメールアドレス。 | 管理者の同意表示名。サインインしてユーザー プロファイルを読みます。管理者の同意の説明。ユーザーがアプリにサインインできるようにし、アプリがサインインしているユーザーのプロファイルを読み取ることができます。 また、アプリはサインインしているユーザーの基本的な会社情報を読み取ることができます。ユーザー同意表示名 サインインしてプロファイルを読みます。ユーザーの同意の説明。組織アカウントでアプリにサインインし、アプリにプロフィールを読み取らせることができます。 また、アプリは基本的な会社の情報を読み取ることができます。 | 9ff28b02-ccc5-4cac-9d17-4cf6987c371f |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 姓、姓、会社のメールアドレス 名、カルマに関する通信用の報告電子メールアドレスを表示する管理者の姓。 名簿は、請求目的で、大規模なユーザーを別々の出発に分割するために必要です。 | 姓、姓、会社の電子メール アドレス 名、管理者向けのレポートの姓。 カルマ、請求目的、カルマユーザー階層に関する通信のための電子メールアドレス。 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>テナント ID とユーザー ID をログに保存します。 どちらも識別できません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>1. **DLP ソリューションは導入されていますか?データ漏洩を防ぐために実装される内容**

はい、データは転送中と保管時の両方で暗号化されます。

2. **データの整合性がエラー、破損、誤用、および制御される頻度から確実に保護されるように、どのようなメカニズムを実装しますか**

すべてのサーバーは異なる RAID レベルでハードウェア RAID を実行しますが、いずれの場合も、データ損失が発生するために同時に複数のドライブ障害が発生する必要があります。 私たちは余分な安全を行き、自動バックアップと手動バックアップの両方を持っています。 データベースは毎日自動的にバックアップされ、7 日間保存されます。
VM は毎週自動的にバックアップされ、1 か月間保存されます。

**スナップショットとバックアップは、パブリックに表示されない内部ネットワークに保存されます。**

3. **マルチテナント ソリューションで顧客のデータが他の顧客から適切に分離されていることを確認する方法と、本番データが非運用環境でレプリケートまたは使用されないように制御する方法について説明します。**

異なるデータベースに格納されます。

4. **転送中のデータと保存時のデータに対して、どのような種類の暗号化を提案するか(アルゴリズム、プロトコル、キーの長さ)**

すべての転送中のデータは、TLS または SSL によって暗号化されます。 HTTP は、SSL によって暗号化された TLS 1.2 または TLS 1.3 データベース トラフィックによって暗号化されます。

データは、米国のデータセンターにあるデジタル海洋クラウドセンターに保存されています。

5. **独自の使用とテナントごとに、一意の暗号化キー (プロセス、ストレージ、使用、RACI、SOD) の管理方法を説明する**

デジタルオーシャンが担当。

6. **プロバイダーの最後に配置されているアクセス管理プロセスについて説明し、不要になったアクセスをタイムリーに削除する方法と、ジョブ ロールに対する特権の適切性を制御する方法を示します。また、再検証プロセスとその実行頻度についても説明します。**

コントロールパネルにアクセスするには、2要素認証を使用します。 3人だけがアクセスでき、毎月パスワードを変更し、アクセスログを監査し続け、ユーザーがもはや私たちと一緒に働かないようにして、プラットフォームからアカウントを削除します。

7. **共有 ID (ルート、Sys、システムなど)、グループ ID (同じチームに属する複数の個人が使用する汎用アカウントなど) およびローカル アカウントを管理するために、最後に実装する手順を指定します。特権アカウントの使用とセキュリティ デバイスへのアクセス (ハイパーバイザー、ファイアウォール、脆弱性スキャナー、ネットワーク スニファー、API など) を制限、ログ、監視する方法、チームを変更するユーザーや退社したユーザーがグループ ID にアクセスできないようにする方法、および ID のトレーサビリティのレベルを説明します。**

私たちは共有可能なIDを共有するために1Passwordを使用&#8217;、共有リソースが共有パスワード預託からアクセスされるたびに別のアクティビティフィードを持っています。 絶対に必要でない限り、共有アカウントを使用せず、代わりに個々のアカウントを使用します。 共有ログインを介して、Karma データベースの情報にアクセスできませんでした。 2FA は、個別のログインを取得するために 1Password にアクセスするために使用されます。

8. **職務分掌が尊重され、制御される頻度を確保および監視するプロセスを説明する**

私たちは、義務の分離、専用ログイン使用の重要性、可能なすべてのログインの2FAをカバーする毎月の会議を実行しました。

SIEM には、ファイアウォール ログ、Web サーバー ログ、およびアプリケーション ログが含まれています。 SIEMは毎日、そして受け取ったときに分析を受けています。 ログは 1 か月間保持され、その後は安全に削除されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35674" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

