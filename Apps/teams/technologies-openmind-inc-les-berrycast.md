---
title: Berrycast by Technologies Openmind Inc, Les のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 04/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Berrycast、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 726a087d07e64f82ee44932a450a038e5bfaa858
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551938"
---
# <a name="berrycast"></a>Berrycast

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 4 月 20 日</p>

* <a href="https://teams.microsoft.com/l/app/c7cde650-1e32-11eb-af14-639b3a7d6491" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002798" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Technologies Openmind Inc, Les to Microsoft が提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Berrycast |
| ID | WA200002798 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Technologies Openmind Inc, Les |
| パートナー Web サイトの URL | [https://berrycast.com](https://berrycast.com) |
| プライバシー ポリシーの URL | [https://berrycast.com/privacy-policy](https://berrycast.com/privacy-policy) |
| 利用規約の URL | [https://berrycast.com/terms-of-use](https://berrycast.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、Technologies Openmind Inc, Les から、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| People.Read | 委任 | すべてのユーザー連絡先を取得するには | 連絡先の電子メール、フィストネーム、姓、および画像は、レコードの迅速な共有アクセスを与えるために保存されます | 094f3986-3951-4f0c-88fa-514d117c8dd0 |
>| User.Read | 委任 | 基本情報 (姓と名と画像) を使用してユーザーを識別するには | 名を表示するには。 lastname と picture into the application | 094f3986-3951-4f0c-88fa-514d117c8dd0 |
>| メール | 委任 | ユーザーを識別するには | ログ記録用のユーザーを特定し、通知を送信するには | 094f3986-3951-4f0c-88fa-514d117c8dd0 |
>| offline_access | 委任 | アクセス許可を付与したデータへのアクセスの維持 | 該当なし | 094f3986-3951-4f0c-88fa-514d117c8dd0 |
>| openid | 委任 | ユーザーを識別するには | ログ記録のユーザーを識別するには | 094f3986-3951-4f0c-88fa-514d117c8dd0 |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-------------------|:--------------------------|:--------------------------|
>| Stripe、Intercom、MixPanel、振幅 | 電子メール、ユーザー固有の ID、姓、姓  | 安全な支払いを処理し、マーケティング キャンペーンを実行し、効率的な顧客サービスを提供し、ユーザー分析を追跡して製品を改善するには |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>ユーザーが自分のアカウントを削除した場合、電子メール、名、姓、およびすべてのデータが削除されます 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>ユーザーが自分のアカウントを削除した場合、ユーザーに関連するデータはすべて削除されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38163" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity の条件を処理する方法について、Technologies Openmind Inc, Les から提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | いいえ |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | いいえ |
| アプリに機密クライアントがありますか? | いいえ |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | いいえ |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
