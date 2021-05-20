---
title: アプリケーション別のアプリケーション monday.com 情報 monday.com
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: monday.com、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 64fc8e948618b760a3f82ee9c1ac67a32de9afb6
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552928"
---
# <a name="mondaycom"></a>monday.com

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 9 月 28 日</p>

* <a href="https://teams.microsoft.com/l/app/eab2d3ce-6d6a-4415-abc4-5f40a8317b1f" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001798" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Microsoft に提供される monday.com 情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | monday.com |
| ID | WA200001798 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | monday.com |
| パートナー Web サイトの URL | [https://monday.com](https://monday.com) |
| プライバシー ポリシーの URL | [https://monday.com/privacy](https://monday.com/privacy) |
| 利用規約の URL | [https://monday.com/terms/tos](https://monday.com/terms/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリ monday.com 収集および保存する方法、およびアプリが収集するデータに対して組織が持つコントロールに関する情報を提供しています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft アプリケーションをGraph。


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-------------------|:--------------------------|:--------------------------|
>| monday.com は、サービスのパフォーマンスに次のサブプロセッサを使用します。&#160;https://monday.com/terms/subprocessors |  | monday.com API は使用しない。 サービスのパフォーマンスには、次の Microsoft フレームワークを使用します (上記の応答で詳細に説明します)。 &#8216;botbuilder&#8217; &#8216;botframework-connector&#8217; &#8216;@micorosft/teams-js&#8217; |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>monday.com、ユーザーが生成したコンテンツを含むアプリケーション ログを保存し、R D 担当者がバグやユーザー報告の問題をトラブルシューティング &amp; できます。 IP アドレスを含むセキュリティ ログは、データ保持ポリシーごとに、より長い期間保持されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>monday.com サービスは、北バージニア州の AWS インフラストラクチャ上で複数の可用性ゾーンでホストされ、DR サイトは別の地域に確立されます。 特定のバックアップ データは GCP (米国、複数地域) に保存されます。 monday.com サービスへのアクセスは、ユーザー組織の管理者によって制御され、次の機能を利用して実現されます。
- ユーザーの種類
- アカウント レベルのアクセス許可
- Workspaces
- ボードの種類
- ボード レベルのアクセス許可
- 列レベルのアクセス許可は monday.com 認証方法をサポートしています。
- 資格情報
- Google SSO (Proプラン)
- okta、OneLogin、およびカスタム SAML 2.0 (Enterprise プランの場合) 2FA は、携帯ショートメール 経由または認証アプリ経由で、プラットフォームの管理パネルを介してアカウント管理者がオプションで有効にできます。
保存中のすべてのデータは、AES-256 を使用して暗号化されます。 開いているネットワーク間で転送中のすべてのデータは、TLS 1.3 (少なくとも TLS 1.2) を使用して暗号化されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35338" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

