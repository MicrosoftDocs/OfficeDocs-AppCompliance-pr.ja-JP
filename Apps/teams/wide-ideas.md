---
title: 幅広いアイデアによる幅広いアイデアのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Wide Ideas、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 075136dcf0c7e03d3f70461490f1b8c181478c43
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414373"
---
# <a name="wide-ideas"></a>Wide Ideas

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 8 月 27 日</p>

* <a href="https://teams.microsoft.com/l/app/2a64f929-bed9-44d9-aa65-d7b921889959" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000819" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Wide Ideas から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Wide Ideas |
| ID | WA200000819 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Wide Ideas |
| パートナー Web サイトの URL | [https://getwideideas.com](https://getwideideas.com) |
| プライバシー ポリシーの URL | [https://getwideideas.com/privacy-policy/](https://getwideideas.com/privacy-policy/) |
| 利用規約の URL | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474849364/Product_42949683744/Asset_0831a14b-e5df-4f0b-8385-3c06edaeceeb/GENERALTERMSANDCONDITIONSWideI.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Wide Ideas によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | 委任 | チームにチャネルを作成するには  | 作成されたチャレンジのチャネル ID を格納します。  | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| Directory.Read.All | 委任 | これを使用して顧客ディレクトリからユーザーを一覧表示する  | 該当なし | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| Group.Read.All | 委任 | これを使用して、チームを読み取り、同期Microsoft Teams。 | チームのグループ ID とチームのメンバーを保存します。  | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| TeamsAppInstallation.ReadWriteForTeam | 委任 | これは、アプリをアプリに自動的にインストールTeamsします。  | アプリがインストールされているチームに関する情報を保存します | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| TeamsTab.Create | 委任 | これを使用して、Wide Ideas によって作成されたチャネルにアプリケーション (チャレンジ/検索のアイデア) タブを自動的に作成します。 | 該当なし | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |
>| User.Read | 委任 | SSO を使用してユーザーを認証し、ユーザー データを同期するために使用されます。 | 名前、メール、ユーザー ID を保存します。  | [b0656c15-44aa-4aab-8956-bb97e3016535](https://docs.microsoft.com/microsoft-365-app-certification/azure/b0656c15-44aa-4aab-8956-bb97e3016535) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| メール通知に使用される Mailjet Email。 | 電子メール アドレス | アクティビティを通して電子メール通知を送信するには  |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| バックエンドでユーザーを作成し、チームにリンクされたコンテンツにアクセスするためのアクセス許可を与えるために。 | 保存: 名前 - ユーザーの名前を表示するには、電子メール アドレス - ユーザーを識別します。 | バックエンドのコンテンツに対するアクセス許可を管理するには |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>名前、電子メール、IP 番号はログに保存されます。 組織は、データを削除する場合は、サプライヤーとして要求を送信できます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>データストレージ: すべての顧客データは、サービスMicrosoft Azureされます。 ユーザーは、ユーザーが 2 つの要素を使用してAzure AD。 役割ベースのアクセス (RBAC) が設定されています。 サーバーへのすべてのアクセスMicrosoft Azure、暗号化された接続によって厳密に行います。 すべてのデータは保存時に暗号化されます。 すべてのサービスは、Azure セキュリティ センターの最善の実践によって保護されています。 

また、最小特権の原則に従ってアクセス ポリシーが設定されています。 


#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35870" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity 条件を処理する方法に関する Wide Ideas によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | MFA |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | 不要 |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

