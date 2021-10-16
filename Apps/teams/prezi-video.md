---
title: Prezi による Prezi ビデオのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 05/15/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Prezi Video で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a6e3cf632919160819471385eff35cdf82f005e3
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414964"
---
# <a name="prezi-video"></a>Prezi Video

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 6 月 23 日</p>

* <a href="https://teams.microsoft.com/l/app/78bbd675-511e-41a2-9a1a-8793920efa9e" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001577" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Prezi から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Prezi Video |
| ID | WA200001577 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Prezi |
| パートナー Web サイトの URL | [https://prezi.com](https://prezi.com) |
| プライバシー ポリシーの URL | [https://prezi.com/privacy-policy/](https://prezi.com/privacy-policy/) |
| 利用規約の URL | [https://prezi.com/terms-of-use/](https://prezi.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Prezi によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft アプリケーションをGraph。


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 詳細については、次のページをご覧ください。 https://prezi.com/privacy-policy/ |  | 次の API/SDK は、1 と共に統合するために使用されます。 Botbuilder-SDK (python): この SDK を使用して、Azure Active Directory オブジェクト ID (API によって参照される) をaad_object_id。 この情報は、ユーザーのユーザーをMicrosoft Teamsに作成された Prezi Video 関連コンテンツにマップ prezi.com。  2. Botbuilder-js (javascript): この SDK をMicrosoft Teams特定のデータは収集されません。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| ボットは、前述の名簿情報にアクセスしない。 | ボットは、前述の名簿情報にアクセスしない。 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのログに EUII または OII は表示されません。


#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>RDS データベースには、次の情報が格納されます。

1. Azure Active Directoryオブジェクト ID (API によって aad_object_id) が格納され、ユーザーが Microsoft Teamsビデオ&#8217;取得します。 サーバー aad_object_id、Microsoft の公式ボットビルダー&#8217;を使用して安全に取得されます。

2. ビデオ リンクは、prezi.com。 サイトで作成 prezi.com は、セクション 14 に従って次の URL に格納されます。 https://prezi.com/privacy-policy/ 

リスクの高い外部システム (AWS など) へのアクセス権は、サードパーティの統合 ID およびアクセス管理プラットフォーム (OneLogin) を介して管理されます。

パスワード ポリシーと多要素認証は、統合 ID およびアクセス管理プラットフォームの担当者に適用されます。 ケースバイケースでは、オフィスの IP アドレスから多要素認証は必要ありません。

AWS がホストするサービスとデータベースは、既定ではどこからでもアクセスできません。明示的な受信ルールは手動で追加する必要があります。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


