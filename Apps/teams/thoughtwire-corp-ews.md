---
title: ThoughtWire Corp. による ThoughtWire EWS のアプリケーション情報。
ms.author: elmalova
author: elenamalova
ms.date: 09/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: ThoughtWire EWS、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: ebff314a2e2532b6d4b1c2a8e89e600fced83512
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429515"
---
# <a name="thoughtwire-ews"></a>ThoughtWire EWS

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 6 月 17 日</p>

* <a href="https://teams.microsoft.com/l/app/ed27363f-755e-4658-b7bf-409d475959d6" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003239" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

ThoughtWire Corp. から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | ThoughtWire EWS |
| ID | WA200003239 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | ThoughtWire Corp. |
| パートナー Web サイトの URL | [https://thoughtwire.com](https://thoughtwire.com) |
| プライバシー ポリシーの URL | [https://thoughtwire.com/privacy-policy](https://thoughtwire.com/privacy-policy) |
| 利用規約の URL | [https://www.thoughtwire.com/end-user-license-agreement/](https://www.thoughtwire.com/end-user-license-agreement/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、ThoughtWire Corp. から提供されています。このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについてです。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Create | アプリケーション | アプリケーションで、病院の病棟/単位のグループ/チームを作成できます。 | なし | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| Group.ReadWrite.All | アプリケーション | アプリケーションが作成/再作成する必要があるグループを決定し、メンバーシップを管理するために必要です。 | なし | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| GroupMember.ReadWrite.All | アプリケーション | アプリケーションがグループ メンバーシップを管理できる必要があります。 つまり、シフトの変化に合ってチームから看護師を追加/削除する。 | なし | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| TeamMember.ReadWrite.All | アプリケーション | アプリケーションがグループ メンバーシップを管理できる必要があります。 つまり、シフトの変化に合ってチームから看護師を追加/削除する。 | なし | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| TeamsAppInstallation.ReadWriteForTeam | アプリケーション | アプリケーションが作成/管理するチームに ThoughtWire ボットを自動的にインストールできます。 | なし | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |
>| User.Read | アプリケーション | メンバーシップを管理したり、アプリケーション内でユーザーを識別するためにユーザー名を取得したりするときに、必要に応じてアプリケーションがユーザーの AADID/ユーザー名を取得できます。 | なし | [49a15c37-4eca-48b1-a327-7a8b5a3b399c](https://docs.microsoft.com/microsoft-365-app-certification/azure/49a15c37-4eca-48b1-a327-7a8b5a3b399c) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| アクションを実行しているユーザーを識別するには、ユーザー名が必要です。 | ユーザー名とユーザー ID | 通知とイベントの監査。 |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>ThoughtWire は、独自のデータ制御プロセスを満たすか超過しているパートナーを選択します。 データは、絶対に必要とされない限り、パートナー システムには提供されない。 すべての ThoughtWire サービスと関連するパートナー システムは、お客様によって確認および承認されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>不要

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は ThoughtWire Corp. から提供されています。このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity の条件を処理する方法について説明します。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | 不要 |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | 不要 |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
