---
title: PagerDuty, Inc. による PagerDuty のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 09/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: PagerDuty、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: a296483ba42328a306131aee8a2f29aed8d7006b
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412837"
---
# <a name="pagerduty"></a>PagerDuty

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 8 月 27 日</p>

* <a href="https://teams.microsoft.com/l/app/c8c302dc-4e77-4536-890d-0c2bffbef9cc" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001637" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

PagerDuty, Inc. から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | PagerDuty |
| ID | WA200001637 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | PagerDuty, Inc. |
| パートナー Web サイトの URL | [https://www.pagerduty.com](https://www.pagerduty.com) |
| [アプリケーション情報Teamsページの URL | [https://www.pagerduty.com/integrations/microsoft-teams](https://www.pagerduty.com/integrations/microsoft-teams) |
| プライバシー ポリシーの URL | [https://www.pagerduty.com/privacy-policy/](https://www.pagerduty.com/privacy-policy/) |
| 利用規約の URL | [https://www.pagerduty.com/service-terms-use/](https://www.pagerduty.com/service-terms-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、PagerDuty, Inc. から、このアプリが組織データを収集および保存する方法、およびアプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| OnlineMeetings.ReadWrite | 委任 | 会議の作成/応答の取得から、このようなフィールドを使用しています。join_web_url、audioConferencing。 これらのフィールドは、ユーザーに会議へのリンクを表示したり、会議で接続する別の方法を示したりするために必要です。 | 保存: join_web_url、audioConferencing。 これらのフィールドは、ユーザーに会議へのリンクを表示したり、会議で接続する別の方法を示したりするために必要です。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadForTeam | 委任 | チャットに pagerduty アプリを追加する場合に使用します。 | チャットに pagerduty アプリを追加する場合に使用します。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadWriteForTeam.All | 委任 | チャットに pagerduty アプリを追加する場合に使用します。 | チャットに pagerduty アプリを追加する場合に使用します。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsTab.ReadWrite.All | 委任 | 会議で pagerduty アプリをタブとして追加する場合の使用 | 会議で pagerduty アプリをタブとして追加する場合の使用 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.Read | 委任 | データが使用される: id、userPrincipalName 。Microsoft Teams ユーザーに参加者として会議に追加するために使用されます。 | データが使用される: id、userPrincipalName 。Microsoft Teams ユーザーに参加者として会議に追加するために使用されます。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.ReadBasic.All | 委任 | データが使用される: id、userPrincipalName 。Microsoft Teams ユーザーに参加者として会議に追加するために使用されます。 | データが使用される: id、userPrincipalName 。Microsoft Teams ユーザーに参加者として会議に追加するために使用されます。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| メール | 委任 | 承認およびトークン要求に使用する。 データの使用: access_token、refresh_token、expires_inスコープ | access_token、refresh_token、expires_inスコープ。 このデータは、ユーザー会議とオンライン会議に関する情報を取得するために必要です。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| offline_access | 委任 | 承認およびトークン要求に使用する。 データの使用: access_token、refresh_token、expires_inスコープ | access_token、refresh_token、expires_inスコープ。 このデータは、ユーザー会議とオンライン会議に関する情報を取得する場合に再確認されます。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| openid | 委任 | 承認およびトークン要求に使用する。 データの使用: access_token、refresh_token、expires_inスコープ | access_token、refresh_token、expires_inスコープ。 このデータは、ユーザーに関する情報を取得し、オンライン会議を作成/取得する場合に使用します。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| profile | 委任 | 承認およびトークン要求に使用する。 データの使用: access_token、refresh_token、expires_inスコープ | access_token、refresh_token、expires_inスコープ。 このデータは、ユーザーに関する情報を取得し、オンライン会議を作成/取得する場合に使用します。 | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| OnlineMeetings.ReadWrite | 委任 | 会議の作成/応答の取得から、このようなフィールドを使用しています。join_web_url、audioConferencing。 これらのフィールドは、ユーザーに会議へのリンクを表示したり、会議で接続する別の方法を示したりするために必要です。 | 保存: join_web_url、audioConferencing。 これらのフィールドは、ユーザーに会議へのリンクを表示したり、会議で接続する別の方法を示したりするために必要です。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam | 委任 | チャットに pagerduty アプリを追加する場合に使用します。 | チャットに pagerduty アプリを追加する場合に使用します。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam.All | 委任 | チャットに pagerduty アプリを追加する場合に使用します。 | チャットに pagerduty アプリを追加する場合に使用します。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsTab.ReadWrite.All | 委任 | 会議で pagerduty アプリをタブとして追加する場合の使用 | 会議で pagerduty アプリをタブとして追加する場合の使用 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.Read | 委任 | データが使用される: id、userPrincipalName 。Microsoft Teams ユーザーに参加者として会議に追加するために使用されます。 | データが使用される: id、userPrincipalName 。Microsoft Teams ユーザーに参加者として会議に追加するために使用されます。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.ReadBasic.All | 委任 | データが使用される: id、userPrincipalName 。Microsoft Teams ユーザーに参加者として会議に追加するために使用されます。 | データが使用される: id、userPrincipalName 。Microsoft Teams ユーザーに参加者として会議に追加するために使用されます。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| メール | 委任 | 承認およびトークン要求に使用する。 データの使用: access_token、refresh_token、expires_inスコープ | access_token、refresh_token、expires_inスコープ。 このデータは、ユーザー会議とオンライン会議に関する情報を取得するために必要です。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| offline_access | 委任 | 承認およびトークン要求に使用する。 データの使用: access_token、refresh_token、expires_inスコープ | access_token、refresh_token、expires_inスコープ。 このデータは、ユーザー会議とオンライン会議に関する情報を取得するために必要です。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| openid | 委任 | 承認およびトークン要求に使用する。 データの使用: access_token、refresh_token、expires_inスコープ | access_token、refresh_token、expires_inスコープ。 このデータは、ユーザーに関する情報を取得し、オンライン会議を作成/取得する場合に使用します。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| profile | 委任 | 承認およびトークン要求に使用する。 データの使用: access_token、refresh_token、expires_inスコープ | access_token、refresh_token、expires_inスコープ。 このデータは、ユーザーに関する情報を取得し、オンライン会議を作成/取得する場合に使用します。 | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| PagerDuty が保持するデータは、監視製品のコンピューター データに制限され、PII 情報は企業の電子メール アドレス、名、名、電話番号に制限されます。 そのデータにアクセスできるサブプロセッサの一覧は、次に示します。 https://www.pagerduty.com/subprocessors/ | PagerDuty が保持するデータは、監視製品のコンピューター データに制限され、PII 情報は企業の電子メール アドレス、名、名、電話番号に制限されます。 そのデータにアクセスできるサブプロセッサの一覧は、次に示します。 https://www.pagerduty.com/subprocessors/ | PagerDuty が保持するデータは、監視製品のコンピューター データに制限され、PII 情報は企業の電子メール アドレス、名、名、電話番号に制限されます。 そのデータにアクセスできるサブプロセッサの一覧については、次のページを参照してください。データのプライバシーに関する詳細については、以下 https://www.pagerduty.com/subprocessors/ を参照してください。 https://www.pagerduty.com/privacy-policy/ |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>PagerDuty では、少なくとも PagerDuty が管理するデータセキュリティ基準は、契約上の義務を含め、契約上の DPA の形式でデータを転送するベンダーによって維持される必要があります。 データ セキュリティ標準の詳細については、次のページをご覧ください。 https://www.pagerduty.com/data-security-policy/

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 基準を処理する方法について、PagerDuty, Inc. から提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

