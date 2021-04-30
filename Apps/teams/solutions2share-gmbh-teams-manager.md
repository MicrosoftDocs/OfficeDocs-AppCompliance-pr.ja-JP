---
title: Solutions2Share GmbH Teamsマネージャーのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: Teams Manager、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0587bc112fafa4b4fb336084a1b71551d78de110
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2021
ms.locfileid: "52096074"
---
# <a name="teams-manager"></a>Teams Manager

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2019 年 12 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/87000000-3db9-bb44-5015-0b4a327a6597" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000764" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Solutions2Share GmbH から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Teams Manager |
| ID | WA200000764 |
| 機能 | ボット、タブ |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Solutions2Share GmbH |
| パートナー Web サイトの URL | [https://www.teams-manager.com](https://www.teams-manager.com) |
| プライバシー ポリシーの URL | [https://www.teams-manager.com/privacy](https://www.teams-manager.com/privacy) |
| 利用規約の URL | [https://www.teams-manager.com/terms-of-use/](https://www.teams-manager.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、Solutions2Share GmbH によって、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | 両方とも | テンプレートをマップするために TenantID と TeamId を格納しています。  | すべてのリストを許可Teams、また、Teams。 | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| Notes.ReadWrite.All | アプリケーション | なし | アプリで承認済みチームにノートブックを追加できます。 | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.Read | 委任 | なし | ユーザーがサインインし、アプリに UPN へのアクセス権を与え、サイレント ログインを有効にできます。 | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.Read.All | 両方とも | 承認者/管理者セクションに入力されたユーザーの ID を保存します。 | アプリ内のユーザーピッカーに表示するユーザーを一覧表示します。 | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |
>| User.ReadBasic.All | 委任 | なし | アプリ内のユーザーピッカーに表示するユーザーを一覧表示します。 | b9a1aaab-e8aa-4b92-b4ce-f13cae74caa7 |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>Azure Log Analytics にログインし、アーカイブ/保持ポリシーを使用しています。
テナント ID とチーム ID をログに記録して、問題を特定し、お客様が問題を解決するのに役立ちます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>アクセス制御のコンプライアンスと運用プロセスがあります。 すべてのユーザー関連のデータとトークンが暗号化されます。 データは、1 つのデータにAzure SQL Database。 ファイアウォールを使用して、特定の IP (システム間の保護された IP 範囲) からの接続のみを許可しています。 Azure 内で特権アクセス管理 (PMA) が有効になっています。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35836" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

