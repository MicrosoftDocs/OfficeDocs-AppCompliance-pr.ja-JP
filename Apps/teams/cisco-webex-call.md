---
title: Cisco による Webex 呼び出しのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 01/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR レジストリの Webex Call、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、およびセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3cfd7063461a56ee5c56ff4f4c57437583b288e2
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60426859"
---
# <a name="webex-call"></a>Webex Call

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 1 月 4 日</p>

* <a href="https://teams.microsoft.com/l/app/0924e969-85d8-4acb-8687-faacd6abd228" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001495" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

シスコから Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Webex Call |
| ID | WA200001495 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Cisco |
| パートナー Web サイトの URL | [https://www.cisco.com](https://www.cisco.com) |
| プライバシー ポリシーの URL | [https://www.cisco.com/c/en/us/about/legal/privacy.html](https://www.cisco.com/c/en/us/about/legal/privacy.html) |
| 利用規約の URL | [https://www.cisco.com/c/en/us/products/universal-cloud-agre...](https://www.cisco.com/c/en/us/products/universal-cloud-agreement.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールについて、シスコから提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.Read | 委任 | チャット メンバーを取得して、Cisco WebEx とのプライベート チャットで他のメンバーを呼び出す | アプリはデータベースにデータを保存しない | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |
>| Contacts.Read | 委任 | ユーザーの連絡先を取得して、ユーザーが Cisco WebEx で連絡先を呼び出す | アプリはデータベースにデータを保存しない | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |
>| User.Read | 委任 | ユーザーの電子メール、電話を取得して、電子メールまたは電話を呼び出す Cisco WebEx を起動する | アプリはデータベースにデータを保存しない | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |
>| User.ReadBasic.All | 委任 | ユーザーの電子メール、電話を取得して、電子メールまたは電話を呼び出す Cisco WebEx を起動する | アプリはデータベースにデータを保存しない | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |
>| User.ReadWrite | 委任 | このアクセス許可は、短縮ダイヤル情報をユーザー内線番号に保存します。 | アプリはデータベースにデータを保存しない  | [9a7ce614-bdc8-4640-aaea-d8c626c58966](https://docs.microsoft.com/microsoft-365-app-certification/azure/9a7ce614-bdc8-4640-aaea-d8c626c58966) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| このメッセージ拡張機能は、チャット メンバーのメール/電話を読み取り、ユーザーが Cisco WebEx でそれらを呼び出す | いいえ |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>このアプリはユーザー データを保存しなかった

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>不要

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10549' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10549" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 基準を処理する方法について、シスコから提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
