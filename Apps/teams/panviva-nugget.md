---
title: Panviva による Nugget のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 10/12/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Nugget、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関する利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1d5f6adea09ed546fae6b6c9ca0aa4ef13beb683
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552868"
---
# <a name="nugget"></a>Nugget

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 10 月 12 日</p>

* <a href="https://teams.microsoft.com/l/app/4e85cc82-5187-4059-af36-a49e7db32bee" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001737" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Panviva から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Nugget |
| ID | WA200001737 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Panviva |
| パートナー Web サイトの URL | [https://www.panviva.com](https://www.panviva.com) |
| プライバシー ポリシーの URL | [https://www.panviva.com/privacy-policy](https://www.panviva.com/privacy-policy) |
| 利用規約の URL | [https://www.panviva.com/terms-and-conditions](https://www.panviva.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Panviva によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft アプリケーションをGraph。


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>はい。
Teams ID が格納されている場合: これは必要なので、ユーザーがどのテナントに入っているのか、ユーザーが管理者かしないかに関する情報を取得できます。
Teams ID : テナント内のユーザーを取得し、その特定のテナントのサブスクリプションの詳細を取得するために格納されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>Azure CosmosDB を使用して、すべてのアプリケーション データを格納します。 データにアクセスするには、エンドポイントとキーが必要です。どちらも、データへのアクセスに使用される構成サービスに挿入されます。 構成サービスは、ボット アプリ サービスからの要求で受け取るベアラー トークンを持つ要求のみを処理します。 このトークンは、ユーザーがチーム インターフェイスでボットにログインすると、Okta によって最初に作成されます。 このデータには、2 要素認証を使用して Microsoft Azureプラットフォームにログオンする必要がある Panviva 管理者がアクセスできます。 電子メールとユーザー名は OKTA に格納され、構成サービスによってアクセスされるキー コンテナーに格納されているプライベート キーでのみアクセスできます。 管理 ID を使用してキー コンテナーにアクセスできるのは、構成サービスのみです。資格情報はアプリに保存されません。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36079' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36079" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

