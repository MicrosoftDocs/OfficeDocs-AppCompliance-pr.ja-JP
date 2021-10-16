---
title: Cloverpop による Cloverpop のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/04/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Cloverpop、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 28d424f384d8b16ff70e7d00f366c3a0f89f64b5
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412517"
---
# <a name="cloverpop"></a>Cloverpop

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 8 月 24 日</p>

* <a href="https://teams.microsoft.com/l/app/3f8519a6-2428-4088-8d12-1b4fd234ff19" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001803" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Cloverpop が Microsoft に提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Cloverpop |
| ID | WA200001803 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Cloverpop |
| パートナー Web サイトの URL | [https://www.cloverpop.com/](https://www.cloverpop.com/) |
| プライバシー ポリシーの URL | [https://www.cloverpop.com/privacy-policy/](https://www.cloverpop.com/privacy-policy/) |
| 利用規約の URL | [https://www.cloverpop.com/terms-of-service](https://www.cloverpop.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Cloverpop によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | 委任 | ユーザー データを保存します。 メール、oid、givenName、familyName、ユーザー アバター、ユーザー オブジェクト ID。組織 ID(tenantId)、組織の表示名、また、サイド チーム/チャネル名、ids、teams メンバーに保存します。 ユーザーが意思決定を作成して操作する場合、このデータを作成したユーザー、チーム、組織に関連付ける。 また、人間に優しい UX でこの所有権を表示する必要があるため、表示情報 (ユーザーのアバターなど)&#8217;格納されます。 | ユーザーはサインインし、アプリに UPN へのアクセス権を与え、電子メール、名前、oid、tid、givenName、姓、familyName、ユーザー アバター(写真)、組織の displayName など、サイレント ログイン&#8221; を有効にします。 | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |
>| openid | 委任 | ユーザー データを保存します。 メール、oid、givenName、familyName、ユーザー アバター、ユーザー オブジェクト ID。組織 ID(tenantId)、組織の表示名、また、サイド チーム/チャネル名、ids、teams メンバーに保存します。 ユーザーが意思決定を作成して操作する場合、このデータを作成したユーザー、チーム、組織に関連付ける。 また、人間に優しい UX でこの所有権を表示する必要があるため、表示情報 (ユーザーのアバターなど)&#8217;格納されます。 | Web アプリ&#8220;でサインインTeams&#8221;実装するには、次の方法を使用します。 | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |
>| profile | 委任 | ユーザー データを保存します。 メール、oid、givenName、familyName、ユーザー アバター、ユーザー オブジェクト ID。組織 ID(tenantId)、組織の表示名、また、サイド チーム/チャネル名、ids、teams メンバーに保存します。 ユーザーが意思決定を作成して操作する場合、このデータを作成したユーザー、チーム、組織に関連付ける。 また、人間に優しい UX でこの所有権を表示する必要があるため、表示情報 (ユーザーのアバターなど)&#8217;格納されます。 | Web アプリ&#8220;でサインインTeams&#8221;実装するには、次の方法を使用します。 | [1040474b-572d-4575-a423-95dd262a8b8a](https://docs.microsoft.com/microsoft-365-app-certification/azure/1040474b-572d-4575-a423-95dd262a8b8a) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 決定に関連する特定のユーザーが実行したアクションを正確に表示するために、最初/最後/表示名のデータにアクセスします。 各ユーザーが複数の組織に属する場合は、メール アドレスを db 内の各ユーザーの一意の識別子として使用します。 このデータにアクセスできるのは、アプリとやり取りする場合のみです。例:アンケートに応答した場合などです。 | 決定に関連する特定のユーザーが実行したアクションを正確に表示するために、最初/最後/表示名のデータを格納します。  メール アドレスは、各ユーザーが複数の組織に属する場合に、db 内の各ユーザーの一意の識別子として使用されます。 このデータは、アプリとやり取りするときにのみ保存されます。例: アンケートに応答した場合などです。 意思決定データは決定のための記録システムであるはずなので、決定に関与する各ユーザーが決定に貢献した方法を特定するためのデータを格納することが重要です。 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>はい。
チーム ID は、アプリがチームで操作される際にログに表示されます。
米国に拠点を置く 3 人の創設者に対して、生産ログへのアクセスが制限されています。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>Cloverpop アプリは Ruby on Rails を使用して構築され、クラウド インフラストラクチャに AWS を利用する Heroku PaaS (サービスとしてのプラットフォーム) でホストされます。 Heroku と AWS の両方に、アクセスできる SOC レポートがあります。 アプリは、保存データストレージで暗号化するために PostgreSQL を使用し、マルチテナント環境です。
 
すべてのコードには、データ アクセスのセキュリティをカバーする自動テストが記述されています。 各ビルドでは、セキュリティに関する厳格なコード レビュー プロセスと、ユーザー認証のチェックと、利用可能なユーザー 操作によるデータ アクセスを含む手動の QA テスト プロセスが実行されます。 実稼働環境と、開発やテストなど、他のすべての環境との間には明確な分離があります。
 
一部の担当者だけが実稼働環境とデータベースにアクセスできます。会社の創設者と、バックグラウンド チェックを受け、定量化されたニーズ (顧客サポートなど) を持つ一握りの従業員。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35992" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


