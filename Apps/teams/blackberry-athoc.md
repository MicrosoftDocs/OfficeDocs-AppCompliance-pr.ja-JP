---
title: BlackBerry AtHoc by BlackBerry のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/05/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: BlackBerry AtHoc で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 38e85981b12faf81ce3b737300aacdbee42dc2a1
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2021
ms.locfileid: "60415204"
---
# <a name="blackberry-athoc"></a>BlackBerry AtHoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 6 月 23 日</p>

* <a href="https://teams.microsoft.com/l/app/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003065" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

BlackBerry から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | BlackBerry AtHoc |
| ID | WA200003065 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | BlackBerry |
| パートナー Web サイトの URL | [https://www.blackberry.com](https://www.blackberry.com) |
| [アプリケーション情報Teamsページの URL | [https://www.blackberry.com/us/en/products/blackberry-athoc](https://www.blackberry.com/us/en/products/blackberry-athoc) |
| プライバシー ポリシーの URL | [https://www.blackberry.com/us/en/legal/privacy-policy](https://www.blackberry.com/us/en/legal/privacy-policy) |
| 利用規約の URL | [https://www.athoc.com/pss/terms.html#](https://www.athoc.com/pss/terms.html#) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関して BlackBerry によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Send | 委任 | チームにアラート カードを送信&#8217;送信するために、プリンシパル名やチームの一般的なチャネル (サインインしているユーザーが承認されている) へのリンクなど、ユーザーの基本的な詳細にアクセスします。 | ユーザー データ&#8217;ボット メモリに格納する必要があります。 サインインしているユーザーのプリンシパル名、AAD トークン、BlackBerry AtHoc Token、BlackBerry AtHoc Server の基本設定/構成をボット メモリに格納します。 Microsoft サービス API と BlackBerry AtHoc Server に API 要求を送信Graph情報が必要です。 | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| Group.Read.All | 委任 | チームにアラート カードを送信&#8217;送信するために、プリンシパル名やチームの一般的なチャネル (サインインしているユーザーが承認されている) へのリンクなど、ユーザーの基本的な詳細にアクセスします。 | ユーザー データ&#8217;ボット メモリに格納する必要があります。 サインインしているユーザーのプリンシパル名、AAD トークン、BlackBerry AtHoc Token、BlackBerry AtHoc Server の基本設定/構成をボット メモリに格納します。 Microsoft サービス API と BlackBerry AtHoc Server に API 要求を送信Graph情報が必要です。 | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| User.Read | 委任 | チームにアラート カードを送信&#8217;送信するために、プリンシパル名やチームの一般的なチャネル (サインインしているユーザーが承認されている) へのリンクなど、ユーザーの基本的な詳細にアクセスします。 | ユーザー データ&#8217;ボット メモリに格納する必要があります。 サインインしているユーザーのプリンシパル名、AAD トークン、BlackBerry AtHoc Token、BlackBerry AtHoc Server の基本設定/構成をボット メモリに格納します。 Microsoft サービス API と BlackBerry AtHoc Server に API 要求を送信Graph情報が必要です。 | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| メール | 委任 | チームにアラート カードを送信&#8217;送信するために、プリンシパル名やチームの一般的なチャネル (サインインしているユーザーが承認されている) へのリンクなど、ユーザーの基本的な詳細にアクセスします。 | ユーザー データ&#8217;ボット メモリに格納する必要があります。 サインインしているユーザーのプリンシパル名、AAD トークン、BlackBerry AtHoc Token、BlackBerry AtHoc Server の基本設定/構成をボット メモリに格納します。 Microsoft サービス API と BlackBerry AtHoc Server に API 要求を送信Graph情報が必要です。 | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| openid | 委任 | チームにアラート カードを送信&#8217;送信するために、プリンシパル名やチームの一般的なチャネル (サインインしているユーザーが承認されている) へのリンクなど、ユーザーの基本的な詳細にアクセスします。 | ユーザー データ&#8217;ボット メモリに格納する必要があります。 サインインしているユーザーのプリンシパル名、AAD トークン、BlackBerry AtHoc Token、BlackBerry AtHoc Server の基本設定/構成をボット メモリに格納します。 Microsoft サービス API と BlackBerry AtHoc Server に API 要求を送信Graph情報が必要です。 | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |
>| profile | 委任 | チームにアラート カードを送信&#8217;送信するために、プリンシパル名やチームの一般的なチャネル (サインインしているユーザーが承認されている) へのリンクなど、ユーザーの基本的な詳細にアクセスします。 | ユーザー データ&#8217;ボット メモリに格納する必要があります。 サインインしているユーザーのプリンシパル名、AAD トークン、BlackBerry AtHoc Token、BlackBerry AtHoc Server の基本設定/構成をボット メモリに格納します。 Microsoft サービス API と BlackBerry AtHoc Server に API 要求を送信Graph情報が必要です。 | [f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7](https://docs.microsoft.com/microsoft-365-app-certification/azure/f18b3ce0-a7a9-4fb7-96be-9b4a7dee68f7) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>該当なし

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12225' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12225" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity 条件を処理する方法について BlackBerry によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

