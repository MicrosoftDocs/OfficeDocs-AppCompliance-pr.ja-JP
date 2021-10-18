---
title: 動的信号による動的信号のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 11/01/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 動的シグナル、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d25efd4a6dffac1dde98995505e5ca913a8e4501
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60435611"
---
# <a name="dynamic-signal"></a>Dynamic Signal

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2019 年 12 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/6f98619e-a822-4a74-8ee9-af6a358f2750" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000102" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Dynamic Signal から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Dynamic Signal |
| ID | WA200000102 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Dynamic Signal |
| パートナー Web サイトの URL | [https://www.dynamicsignal.com](https://www.dynamicsignal.com) |
| [アプリケーション情報Teamsページの URL | [https://support.dynamicsignal.com/hc/en-us/requests/new?tic...](https://support.dynamicsignal.com/hc/en-us/requests/new?ticket_form_id=360000290032) |
| プライバシー ポリシーの URL | [https://dynamicsignal.com/privacy/](https://dynamicsignal.com/privacy/) |
| 利用規約の URL | [https://dynamicsignal.com/terms-of-use/platform-terms-of-us...](https://dynamicsignal.com/terms-of-use/platform-terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Dynamic Signal によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 委任 | 動的シグナルは、ユーザー Azure ADからプラットフォームに同期し、ユーザーのアクティブ化と非アクティブ化をリアルタイムで可能にします。 データは動的シグナル内に格納され、同期の実行中にユーザーがアプリケーションを使用できます。 | 特定のユーザーの読み取りアクセス許可を使用して、動的シグナル プラットフォーム のユーザーとユーザーを同期Azure AD。 | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| User.Read.All | 委任 | 動的シグナルは、ユーザー Azure ADからプラットフォームに同期し、ユーザーのアクティブ化と非アクティブ化をリアルタイムで可能にします。 データは動的シグナル内に格納され、同期の実行中にユーザーがアプリケーションを使用できます。 | 特定のユーザーの読み取りアクセス許可を使用して、動的シグナル プラットフォーム のユーザーとユーザーを同期Azure AD。 | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| offline_access | 委任 | 動的シグナルは、ユーザー Azure ADからプラットフォームに同期し、ユーザーのアクティブ化と非アクティブ化をリアルタイムで可能にします。 データは動的シグナル内に格納され、同期の実行中にユーザーがアプリケーションを使用できます。 | テナントのグループとチームへのアクセスを保持します。 | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |
>| openid | 委任 | 動的シグナルは、ユーザー Azure ADからプラットフォームに同期し、ユーザーのアクティブ化と非アクティブ化をリアルタイムで可能にします。 データは動的シグナル内に格納され、同期の実行中にユーザーがアプリケーションを使用できます。 | 動的シグナル アプリケーションを使用してユーザーを認証します。 | [79ff4a2a-e22b-47d5-94dc-ef76fe46af75](https://docs.microsoft.com/microsoft-365-app-certification/azure/79ff4a2a-e22b-47d5-94dc-ef76fe46af75) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| openid directory.readwrite.all access to the tenant's domain and groups, add a app to a team offline_access retain access to the tenant's groups and teams | openid 独立認証を許可します。 directory.readwrite.all access to the tenant's domain and groups, add a app to a team offline_access retain access to the tenant's groups and teams Note: Dynamic Signal のアプリケーションでは、Dynamic Signal 内で作成されたグループとアクセス許可を Teams に適用して、Dynamic Signal でアクティブなユーザーが Teams 内の同じグループとユーザーにアクセスできます。 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>動的シグナル アプリとプラットフォームは、ユーザー情報を使用して、ユーザー情報との統合を容易Microsoft Teams。 この情報は、動的シグナル プラットフォーム内で適切なアクセス許可を持つユーザーが利用できます。 関連情報は、名前、表示名、および電子メールです。 この情報は、動的シグナル ライセンスを持つ各組織のポリシーに従って、動的シグナル プラットフォーム ログに格納されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>登録時に収集され、動的シグナル プラットフォーム内に保存される PII データには、名、名、電子メール/識別子、およびブランドおよび/または代理店パートナーによって設定されたカスタム フィールドが含まれます。 メンバーが oAuth 登録を使用して Facebook または Twitter を使用する場合、公開されているユーザー データの一部が動的シグナル プラットフォームに表示され、データを事前に入力します。 このデータには、名前、場所、写真が含まれます。 ユーザーは、コミュニティのバイオ ページ上のユーザーに表示される情報とデータを制御できます。 メンバーは、個人用またはブランドの写真の読み込み、ソーシャル アカウント/チャネルの接続、およびバイオ ページに表示されるプログラムの利用状況/ポイントをオプトインできます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35740" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

