---
title: Hoylu による Hoylu のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 07/20/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Hoylu で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 7206fc0355b6e30f4a66dd6b5751f6ad72587ac4
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250625"
---
# <a name="hoylu"></a>Hoylu

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020 年 7 月 20 日</p>

* <a href="https://teams.microsoft.com/l/app/732e01bc-570a-43ac-9671-8c7fc4152662" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001573" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Hoylu が Microsoft に提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Hoylu |
| ID | WA200001573 |
| 機能 | Tab |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Hoylu |
| パートナー Web サイトの URL | [https://hoylu.com](https://hoylu.com) |
| プライバシー ポリシーの URL | [https://hoylu.com/privacy-policy](https://hoylu.com/privacy-policy) |
| 利用規約の URL | [https://hoylu.com/terms-of-use](https://hoylu.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールについて Hoylu によって提供されています。

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

>はい。 ログはアプリケーション セキュリティのために行われ、EUII と OII は名、電子メール、IP アドレス、組織 ID の形式で収集されます。 Hoylu のログ プロバイダーは Datadog です。 Datadog は EU-U.S. Privacy Shield Framework への準拠を認定し、クラウド セキュリティ アライアンス (CSA) の STAR レジストラントです。 また、Datadog は、SOC 2 Type II 監査の完了を含む、セキュリティ、プロセス、およびサービスに関する主要な独立したサードパーティの検証を追求しています。 ユーザーは、いつでも GDPR 準拠のプロセスを通じてこの情報の削除を要求できます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>アプリケーション データは FIPS 140-2 Microsoft Azure Cloud Servicesに格納され、使用されている暗号化プロトコルはすべて FIPS 140-2 に準拠しています。 この運用データには、インフラストラクチャ管理者 (PMA) だけがアクセスできます。 組織のアカウント管理は、2FA の Azure AD経由で行われます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35933' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35933" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

