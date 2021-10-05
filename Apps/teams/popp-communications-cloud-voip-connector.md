---
title: POPP コミュニケーションによるポップ クラウド VoIP コネクタのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: POPP Cloud VoIP Connector、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9f64b18c26d3fd38e4272171e7a90f493e76de5f
ms.sourcegitcommit: 11288ac2cbae57aaa7820be0d9fb87c631805b7b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/05/2021
ms.locfileid: "60112321"
---
# <a name="popp-cloud-voip-connector"></a>ポップ クラウド VoIP コネクタ

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 9 月 20 日</p>

* <a href="https://teams.microsoft.com/l/app/b8e57f6b-31cf-468e-9e99-81f0395cb1f9" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003306" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

POPP Communications から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | ポップ クラウド VoIP コネクタ |
| ID | WA200003306 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | POPP コミュニケーション |
| パートナー Web サイトの URL | [https://popp.com](https://popp.com) |
| プライバシー ポリシーの URL | [https://popp.com/terms/privacy-policy/](https://popp.com/terms/privacy-policy/) |
| 利用規約の URL | [https://popp.com/pvnterms/](https://popp.com/pvnterms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する情報を、ポップ コミュニケーションズによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.Read.All | 委任 | 現在のチャネルのメンバーのユーザー ID と表示名。 アプリはこれを使用して、呼び出すチャネル メンバーの一覧をユーザーに提示します。 | メタスイッチは、このデータを格納しない。 | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| Chat.Read | 委任 |  収集または使用されるデータ データを収集または使用する理由を追加します。 現在のチャットのメンバーのユーザー ID と表示名。 アプリはこれを使用して、通話するチャット メンバーの一覧をユーザーに提示します。 | メタスイッチは、このデータを格納しない。 | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| TeamMember.Read.All | 委任 | 現在のチームのメンバーのユーザー ID と表示名。 アプリはこれを使用して、呼び出すチーム メンバーの一覧をユーザーに提示します。 | メタスイッチは、このデータを格納しない。 | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| User.Read.All | 委任 |  収集または使用されるデータ データを収集または使用する理由を追加します。 ユーザーのビジネス電話番号と携帯電話番号。 これは、これらの番号への電話を開始するために必要です。 |   メタスイッチは、このデータを格納しない | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |
>| openid | 委任 | ユーザーの承認トークンで、アプリが自分の代わりにリストされている他Graph API エンドポイントにアクセスする権限を付与します。 | メタスイッチは、このデータを格納しない。 | [b8e57f6b-31cf-468e-9e99-81f0395cb1f9](https://docs.microsoft.com/microsoft-365-app-certification/azure/b8e57f6b-31cf-468e-9e99-81f0395cb1f9) |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Microsoft Identity Platform | いいえ |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| メタスイッチ ネットワークとポップ コミュニケーション | 次の OII が MCT ホストボット サーバーに転送されます。Azure AD テナント ID チーム ID チャネル/チャット ID メッセージの内容も転送され、OII が含まれる可能性があります 次の OII が CommPortal JSON API に転送される可能性があります 電話。 | OII を転送する必要がある理由の正当性を追加する アプリの主な&#8217;は、電話の呼び出しを容易にすることでした。 ユーザーが電話を呼び出す場合は、この情報を提供して CommPortal アカウントにログインし、呼び出しを正しいユーザーに関連付ける必要があります。  MCT ホスト型ボット サーバーに転送される OII は、ボット フレームワーク API に組み込Teams使用され、回避できません。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| アプリの主&#8217;目的は、電話の呼び出しを容易に行う方法です。 ユーザーが電話を呼び出す場合は、正しいテレフォニー ユーザー間で通話を確立するために、通話のすべての関係者に対して EUII を指定する必要があります。 | いいえ |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>メタスイッチと POPP は、CommPortal Web から MCT Web ページを読み込む即時の必要性よりも長い間データを格納します。 データは保持されないので、すぐに削除されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

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

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 基準を処理する方法について、POPP Communications によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | 必要 |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | いいえ |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | 必要 |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 必要 |
| サポートされているポリシーの種類を一覧表示する | 条件付きアクセス ポリシーは、このようなサポートが認証に使用される MSAL ライブラリによって自動的に提供される範囲です。  |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | 必要 |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | 必要 |
| アプリはマルチテナントをサポートしていますか? | いいえ |
| アプリに機密クライアントがありますか? | いいえ |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | 必要 |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/><br/> |
| アプリは Web API を公開していますか? | いいえ |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
