---
title: Lightning Tools による Lightning Tools Lightning コンダクターのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 09/29/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Lightning Tools Lightning Conductor、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリのセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 9541cab6ba5fcd7da59cfe43c89e2e3bf3fceab9
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412046"
---
# <a name="lightning-tools-lightning-conductor"></a>Lightning Tools Lightning コンダクター

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 7 月 12 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200001926" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Lightning Tools から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Lightning Tools Lightning コンダクター |
| ID | WA200001926 |
| Office 365サポートされているクライアント | SharePoint 2016 以降 |
| パートナー会社名 | Lightning Tools |
| パートナー Web サイトの URL | [https://lightningtools.com](https://lightningtools.com) |
| プライバシー ポリシーの URL | [https://lightningtools.com/lightning-conductor-cswp-privacy...](https://lightningtools.com/lightning-conductor-cswp-privacy-policy) |
| 利用規約の URL | [https://lightningtools.com/lightning-tools-lightning-conduc...](https://lightningtools.com/lightning-tools-lightning-conductor-client-side-web-part-software-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Lightning Tools によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | アプリケーション | 予定表情報のクエリとレポートを作成するには | Lightning コンダクターは、データベースを使用したり、データを保存したりすることはできません。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Contacts.Read | アプリケーション | データは収集または保存されません。 データは、現在のユーザーの連絡先の DisplayName を表示するために使用されます。 | Lightning コンダクターは、データベースを使用したり、データを保存したりすることはできません。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Directory.Read.All | アプリケーション | Lightning コンダクターにユーザーを表示する | Lightning コンダクターは、データベースを使用したり、データを保存したりすることはできません。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Files.Read.All | アプリケーション | Lightning OneDriveのファイルを表示する | Lightning コンダクターは、データベースを使用したり、データを保存したりすることはできません。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Mail.Read | アプリケーション | Lightning コンダクターのクエリに現在のユーザー メールボックスからのメッセージが表示される場合 | Lightning コンダクターは、データベースを使用したり、データを保存したりすることはできません。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| People.Read.All | アプリケーション | サイトのメンバーとしてユーザーにクエリを実行する場合は、Lightning コンダクターにユーザー ビューを表示します。 | Lightning コンダクターは、データベースを使用したり、データを保存したりすることはできません。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Presence.Read.All | アプリケーション | ユーザー カードにユーザーのプレゼンスを表示するには | Lightning コンダクターは、データベースを使用したり、データを保存したりすることはできません。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |
>| Sites.Read.All | アプリケーション | Lightning コンダクター ツリービューのサイトを列挙するには | Lightning コンダクターは、データベースを使用したり、データを保存したりすることはできません。 | [a96cbd10-e960-47b8-855b-3af4b5dbd6f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/a96cbd10-e960-47b8-855b-3af4b5dbd6f4) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>アプリ内のデータは、顧客テナント内に存在します。 Lightning Tools は、顧客テナントの外部にデータを保存または処理しない。 

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity 条件を処理する方法について、Lightning Tools によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

