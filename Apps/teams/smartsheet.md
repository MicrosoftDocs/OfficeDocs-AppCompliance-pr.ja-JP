---
title: Smartsheet による Smartsheet のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Smartsheet で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c97f12b0e1f423318c98419f11e7569c5285830d
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/02/2021
ms.locfileid: "53280939"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2019 年 12 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Smartsheet から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Smartsheet |
| ID | WA104380975 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Smartsheet |
| パートナー Web サイトの URL | [https://www.smartsheet.com](https://www.smartsheet.com) |
| [アプリケーション情報Teamsページの URL | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| プライバシー ポリシーの URL | [https://www.smartsheet/legal/privacy](https://www.smartsheet/legal/privacy) |
| 利用規約の URL | [https://Default ユーザー契約: https://www.smartsheet.com/.. .](https://Default User Agreement: https://www.smartsheet.com/legal/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Smartsheet によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | 委任 | なし。 | ユーザーに代わってアプリをインストールできます。 | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Directory.Read.All | 委任 | ui に表示する情報を取得するための tenantId。 | このテナントが使用しているアプリを読み取り、アプリをインストールする必要がある場合に確認できます。 | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.Read.All | 委任 | メッセージ配信用の teamId/groupId。 | グループ (またはチーム) に関する基本情報と会話Teamsアプリで読み取りを許可します。 | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.ReadWrite.All | 委任 | メッセージ配信用の teamId/groupId。 | アプリがチームで新しい会話を開始できます。 このアクセス許可には上記の Read.All スコープも含まれますが、技術的な理由からこのスコープも必要です。 | c68947ae-a07f-44ce-9a13-7b559251731d |
>| User.Read.All | 委任 | userId。 | 認証プロセス中にユーザーに関する基本情報を読み取る事が可能です。 | c68947ae-a07f-44ce-9a13-7b559251731d |
>| offline_access | 委任 | refreshToken。 | アプリを使用すると、ユーザーに代わって更新トークンを受信し、認証トークンを更新できます。 | c68947ae-a07f-44ce-9a13-7b559251731d |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| ボット フレームワーク API | はい | ボット フレームワーク API を使用して、Teams アプリのアプリとしてメッセージを配信します。 Smartsheet は、Smartsheet ボットが話しているユーザーを追跡するために userId 情報を格納します。 |  | なし |  |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-------------------|:--------------------------|:--------------------------|
>| Smartsheet は、Equinix でホストされる運用データセンター環境と AWS S3 の暗号化された保管状態に情報を保存し、顧客の添付ファイルをプライベート暗号化バケットに保存します。 |  | ボット フレームワーク API を使用して、Teams アプリのアプリとしてメッセージを配信します。 Smartsheet は、Smartsheet ボットが話しているユーザーを追跡するために userId 情報を格納します。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Smartsheet は、ボットが話しているユーザーを追跡するのに役立ちます。 最初の認証フローの間に、Smartsheet 通知システムでユーザーのボット レコードを作成します。 | Smartsheet for Teamsボットの場合、ボットが誰と話Teamsを追跡するために、ユーザーのメールと userId を保存します。  Smartsheet には、ユーザーがディレクトリに含むグループの一覧と、メッセージ配信用の groupId を格納します。 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>いいえ

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>Smartsheet は保存されているユーザー情報を暗号化し、管理者は 2FA を使用する必要があります。 Smartsheet はビューなし SaaS プロバイダーとして動作し、既定では、お客様がプラットフォームのアップロードまたは入力を選択したコンテンツは確認されません。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

