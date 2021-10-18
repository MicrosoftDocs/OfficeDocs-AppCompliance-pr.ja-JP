---
title: アプリケーション導入ボット C.AI アプリケーション情報(contexxt.ai
ms.author: elmalova
author: elenamalova
ms.date: 06/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: C.AI 導入ボット、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 85c64b89b739d96d48de528d2394f909f404b06e
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430517"
---
# <a name="cai-adoption-bot"></a>C.AI Adoption Bot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 5 月 6 日</p>

* <a href="https://teams.microsoft.com/l/app/f5323aab-3063-46cb-b632-ee01d95de494" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002633" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Microsoft に提供される contexxt.ai 情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | C.AI Adoption Bot |
| ID | WA200002633 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | contexxt.ai |
| パートナー Web サイトの URL | [https://contexxt.ai](https://contexxt.ai) |
| [アプリケーション情報Teamsページの URL | [https://contexxt.ai/cai-adoption-bot/](https://contexxt.ai/cai-adoption-bot/) |
| プライバシー ポリシーの URL | [https://contexxt.ai/privacy-policy](https://contexxt.ai/privacy-policy) |
| 利用規約の URL | [https://contexxt.ai/terms-of-use](https://contexxt.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリ contexxt.ai 収集および保存する方法、およびアプリが収集するデータに対して組織が持つコントロールに関する情報を提供しています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | アプリケーション | ユーザーの可用性は、フォーカス時ではなく、適切な時間にヒントを送信できる | 匿名化されたユーザーの可用性は、フォーカス時間中ではなく、適切な時間にヒントを送信できる | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| ChannelMessage.Read.All | アプリケーション | Microsoft Teamsの使用状況を分析するために、チャネルごとのプライベートまたは会話の量など、チャネル メタデータをTeams | 匿名化Microsoft Teams、プライベートまたはチャネルごとの会話の量など、チャネルメタデータを使用して、チャネルの使用状況をTeams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Chat.Read.All | アプリケーション | Microsoft Teamsの利用状況を分析するために、メッセージが気に入ったか、グループと 1:1 のチャットが何件存在するかなど、チャット のメタデータをTeams | 匿名化Microsoft Teamsチャット メタデータ (メッセージが気に入った場合や、グループと 1:1 のチャットが存在する数など) を使用して、チャットの使用状況を分析Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Directory.Read.All | アプリケーション | 後で specifi ユーザーにヒントを送信できるユーザー オブジェクト ID。 | 後で specifi ユーザーにヒントを送信できるユーザーのハッシュ (匿名化) オブジェクト ID。 | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Group.Read.All | アプリケーション | Microsoft Teamsの使用状況を分析するTeamsの量やチャネルなど、メタデータをTeams | Microsoft Teamsの使用状況を分析するTeamsの量やチャネルなど、メタデータをTeams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Mail.Read | アプリケーション | Microsoft Exchangeメタデータ (メールの量やグループ数など) と 1:1 の電子メールを使用して、Exchange の使用状況を分析します (Teams) | 匿名化された Microsoft Exchangeメタデータ (メールやグループの量と 1:1 メールなど) を使用して、Exchange の使用状況を分析します (Teams) | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| User.Read.All | アプリケーション | Microsoft Teamsの使用状況を分析するためにユーザーが言及された場合など、チャットと会話のメタデータをTeams | 匿名化Microsoft Teamsチャットと会話のメタデータ (ユーザーがユーザーの使用状況を分析するために言及された場合など) Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Bot Framework では、ユーザー ID が自動的に送信され、ユーザーと通信できます。 C.AI Adoption Analytics のその他の使用状況データは、ユーザーの学習エクスペリエンスを個別化するために使用されます。したがって、これらのヒントを知らない可能性があるユーザーに適切で役立つヒントのみをユーザーに送信します。 | いいえ |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>組織は、ユーザーのライセンスを管理 (割り当て/削除) できます。 組織は、ライセンスを管理するためにさまざまな役割を割り当てることができます。 Administartors は、常にデータの削除を要求できます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37589' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37589" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリ contexxt.ai 認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について説明しています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリは Web API を公開していますか? | 不要 |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
