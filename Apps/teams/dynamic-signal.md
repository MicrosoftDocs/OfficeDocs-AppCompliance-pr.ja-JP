---
title: 動的信号による動的信号のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 動的信号、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、およびCSA STARレジストリ内のセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0d3c59f6809bafe16eec2a1d709f40a980576b1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552228"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

マイクロソフトに動的信号によって提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Dynamic Signal |
| ID | WA200000102 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Dynamic Signal |
| パートナーウェブサイトのURL | [https://dynamicsignal.com](https://dynamicsignal.com) |
| アプリケーション情報ページTeams URL | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| プライバシーポリシーの URL | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| 利用規約の URL | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法、およびアプリが収集するデータに対する組織のコントロールに関する Dynamic Signal によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 委任 | 動的信号は、Azure AD からプラットフォームにユーザーを同期し、ユーザーのアクティブ化と非アクティブ化をリアルタイムで合理化できるようにします。 データは動的信号内に格納され、同期が行われている間にユーザーがそのアプリケーションを使用できるようにします。 | 動的シグナル プラットフォーム ユーザーと Azure AD を同期するための特定のユーザーの読み取りアクセス許可。 | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| User.Read.All | 委任 | 動的信号は、Azure AD からプラットフォームにユーザーを同期し、ユーザーのアクティブ化と非アクティブ化をリアルタイムで合理化できるようにします。 データは動的信号内に格納され、同期が行われている間にユーザーがそのアプリケーションを使用できるようにします。 | 動的シグナル プラットフォーム ユーザーと Azure AD を同期するための特定のユーザーの読み取りアクセス許可。 | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| offline_access | 委任 | 動的信号は、Azure AD からプラットフォームにユーザーを同期し、ユーザーのアクティブ化と非アクティブ化をリアルタイムで合理化できるようにします。 データは動的信号内に格納され、同期が行われている間にユーザーがそのアプリケーションを使用できるようにします。 | テナントのグループとチームへのアクセスを保持します。 | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |
>| openid | 委任 | 動的信号は、Azure AD からプラットフォームにユーザーを同期し、ユーザーのアクティブ化と非アクティブ化をリアルタイムで合理化できるようにします。 データは動的信号内に格納され、同期が行われている間にユーザーがそのアプリケーションを使用できるようにします。 | 動的シグナルアプリケーションでユーザを認証します。 | 79ff4a2a-e22b-47d5-94dc-ef76fe46af75 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| テナントのドメインとグループへの openid ディレクトリ.readwrite.all アクセス権を使用してサインインし、テナントのグループおよびチームへのアクセスを保持offline_accessチームにアプリを追加します。 | openid 独立認証を許可します。 directory.readwrite.all テナントのドメインとグループへのアクセス権、テナントのグループとチームへのアクセスを保持offline_accessチームにアプリを追加する 注: Dynamic Signal のアプリケーションは、チーム ボットを使用してグループを適用し、動的信号内で作成されたアクセス許可をTeamsに使用して、動的信号でアクティブなユーザーがTeams内の同じグループとユーザーにアクセスできるようにします。 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>動的信号アプリとプラットフォームは、Microsoft Teamsとの統合を容易にするためにユーザー情報を利用します。 この情報は、動的シグナル プラットフォーム内で適切なアクセス許可を持つユーザーが利用できます。 関連情報は、名前、表示名、および電子メールです。 この情報は、動的シグナルライセンスを持つ各組織のポリシーに従って、動的信号プラットフォームログ内に保存されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>登録時に収集され、動的信号プラットフォーム内に保存される PII データには、姓、姓、E メール/識別子、およびブランドや代理店パートナーによって設定されたカスタムフィールドが含まれます。 メンバーがoAuth登録を使用してFacebookまたはTwitterを使用する場合、公開されたユーザーデータの一部がダイナミックシグナルプラットフォームに提示され、データが事前に入力されます。 このデータには、名前、場所、写真が含まれます。 ユーザーは、コミュニティのバイオページでユーザーに提示される情報とデータを制御できます。 メンバーは、個人またはブランドの写真の読み込み、ソーシャルアカウント/チャンネルの接続、およびバイオページに表示されるプログラム内の使用/ポイントを選択できます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

