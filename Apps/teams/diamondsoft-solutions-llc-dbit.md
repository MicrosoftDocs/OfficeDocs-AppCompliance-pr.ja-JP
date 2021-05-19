---
title: ダイヤモンドソフトソリューションズによるDBit向けアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: DBit、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、およびCSA STARレジストリ内のセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 23995f613c3c3b6d7b2ab7d161f8710ccddf07d0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553958"
---
# <a name="dbit"></a>DBit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年6月23日</p>

* <a href="https://teams.microsoft.com/l/app/b28bb657-8edd-47ae-a912-c5fc11b3e89e" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001536" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

マイクロソフトに提供されるダイヤモンドソフトソリューションズ、LLCによって提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | DBit |
| ID | WA200001536 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Diamondsoft Solutions, LLC |
| パートナーウェブサイトのURL | [https://www.dbit.io/index.html](https://www.dbit.io/index.html) |
| プライバシーポリシーの URL | [https://www.dbit.io/privacypolicy.html](https://www.dbit.io/privacypolicy.html) |
| 利用規約の URL | [https://www.dbit.io/termsofuse.html](https://www.dbit.io/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法、およびアプリが収集するデータに対する組織のコントロールに関するDiamondsoftソリューションズ、LLCによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 委任 | 当社は、システムやデータベースにGraph情報を保存しません。 | サインインおよびユーザー プロファイルの読み取り | 1533d702-7604-463a-9fa3-63077c425e76 |
>| メール | 委任 | 当社は、システムやデータベースにGraph情報を保存しません。 | ユーザーのメール アドレスの表示 | 1533d702-7604-463a-9fa3-63077c425e76 |
>| offline_access | 委任 | 当社は、システムやデータベースにGraph情報を保存しません。 | アクセス許可を付与したデータへのアクセスの維持 | 1533d702-7604-463a-9fa3-63077c425e76 |
>| openid | 委任 | 当社は、システムやデータベースにGraph情報を保存しません。 | ユーザーのサインイン | 1533d702-7604-463a-9fa3-63077c425e76 |
>| profile | 委任 | 当社は、システムやデータベースにGraph情報を保存しません。 | ユーザーの基本プロファイルの表示 | 1533d702-7604-463a-9fa3-63077c425e76 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| ウェルカム メッセージを作成するには | 私たちは、私たちのシステムやデータベースに名簿情報を格納しません。 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>この情報は収集しません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>Azure キャッシュ Redis を使用し、キャッシュ内のデータの最大寿命は 300 分です。 キャッシュ データ項目は AES256 で暗号化されます。 アプリ サービスのみが SSL 経由で Azure キャッシュ Redis に接続でき、接続文字列は Azure 環境変数に格納されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

