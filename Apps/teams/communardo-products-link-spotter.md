---
title: Communardo 製品によるリンク スポットターのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 07/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: リンク スポットター、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 8a6c2ee716c7e07686e2c62e1cd79196acbdc5a3
ms.sourcegitcommit: 34fde42f42c623b37d1db154bf348bdc8b76a8c7
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/19/2021
ms.locfileid: "58407534"
---
# <a name="link-spotter"></a>Link Spotter

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 7 月 27 日</p>

* <a href="https://teams.microsoft.com/l/app/9e486bb8-9633-48ba-8416-71da1d30cd08" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003092" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Communardo 製品から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Link Spotter |
| ID | WA200003092 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Communardo 製品 |
| パートナー Web サイトの URL | [https://www.communardo.com](https://www.communardo.com) |
| [アプリケーション情報Teamsページの URL | [https://communardo.atlassian.net/wiki/spaces/LINK/overview](https://communardo.atlassian.net/wiki/spaces/LINK/overview) |
| プライバシー ポリシーの URL | [https://www.communardo.com/privacy-statement/](https://www.communardo.com/privacy-statement/) |
| 利用規約の URL | [https://www.communardo.com/customer-agreement/](https://www.communardo.com/customer-agreement/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、Communardo Products から、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | 委任 | 現在のユーザーのチャネル メンバーシップの確認 | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| ChannelMessage.Read.All | アプリケーション | メッセージ内の URL、messageid、返信先メッセージ ID、チャネル ID、作成者 ID.。。これらの情報は、Graphメッセージに投稿されたすべてのリンクを取得するためのパフォーマンスの高い方法を提供しないので必要です。 したがって、リンク機能を [リンク] タブで提供するには、メッセージを積極的にTeamsがあります。 | メッセージ内の URL、messageid、返信先メッセージ ID、チャネル ID、作成者 ID | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| User.Read | 委任 | サインインおよびユーザー プロファイルの読み取り | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| User.Read.All | アプリケーション | ライセンスを持つユーザーの数Teamsします。 顧客テナントの有料アプリ ソース サブスクリプションのシート サイズを更新するために使用します。 | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| User.ReadBasic.All | 委任 | アプリ内のメッセージ作成者のプロファイル画像と名前を表示する | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| メール | 委任 | OpenID Connect | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| offline_access | 委任 | OpenID Connect | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| openid | 委任 | OpenID Connect | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |
>| profile | 委任 | OpenID Connect | none | [a4c28379-0840-42c5-9407-f088a7f54048](https://docs.microsoft.com/microsoft-365-app-certification/azure/a4c28379-0840-42c5-9407-f088a7f54048) |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Marketplace API (SaaS フルフィルメント API) | いいえ |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>テナント ID、チャネル ID、ユーザーはデータを直接削除できます。データは 90 日後に自動的に削除されます

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>削除、エンドユーザー ポリシー

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 基準を処理する方法について Communardo 製品によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
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
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
