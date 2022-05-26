---
title: SHEETGO EUROPE SL によって提供される Sheetgo のアプリケーション情報
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Sheetgo の利用可能なすべてのセキュリティ情報とコンプライアンス情報、データ処理ポリシー、Microsoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報を確認します。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 001ad5dcce2a95885420f8413bfbfe03562eb5b2
ms.sourcegitcommit: ef767e1079411056cb3ca86d6b29084e31b0ef1c
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/26/2022
ms.locfileid: "65690432"
---
# <a name="sheetgo-application-information"></a>Sheetgo アプリケーション情報

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 11 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/583de270-58d0-4f94-af06-bf971f82fd94" target="_blank">Teams ストアで表示する</a>
* <a href="https://appsource.microsoft.com/en-US/product/office/WA200002128?tab=Overview" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

SHEETGO EUROPE SL から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Sheetgo |
| ID | WA200002067 |
| サポートされているOffice 365 クライアント | Microsoft Teams |
| パートナー会社名 | SHEETGO EUROPE SL |
| パートナー Web サイトの URL | [https://www.sheetgo.com/](https://www.sheetgo.com/) |
| プライバシー ポリシーの URL | [https://www.sheetgo.com/legal/privacy/](https://www.sheetgo.com/legal/privacy/) |
| 使用条件の URL | [https://www.sheetgo.com/legal/terms/](https://www.sheetgo.com/legal/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて、SHEETGO EUROPE SL によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graphを使用したデータ アクセス

このアプリ[で必要な Microsoft Graphアクセス許可](/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft Graphは使用されません。


#### <a name="non-microsoft-services-used"></a>使用されていないMicrosoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由の正当な理由を含めます。

>| **Microsoft サービス以外のすべての OII は、** |  **転送される OII は何ですか?** | **OII を転送するための正当な理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| MongoDB: 機能するためにシステムとユーザー データを記録する、Google BigQuery: システム ログの使用状況を記録する、Google Firestore: マイクロサービスの状態を維持および調整するシステム、ストライプ: 支払いシステム |  | これらのアプリケーションでは、追加の Microsoft API は使用されません |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、チーム内のチーム メンバーの名簿 (名、姓、表示名、電子メール アドレス) または追加されたチャットなど、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII にアクセスできません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織の識別可能な情報 (OII) またはエンド ユーザー識別情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はい場合は、保存されるデータと保持ポリシーと削除ポリシーについて説明します。

>テレメトリ/ログには、エンド ユーザーが識別できる情報としてのみ、ユーザーの電子メール アドレスが含まれます。 ユーザーから要求されると、アプリケーション サポート チームは、テレメトリ/ログ間で電子メール アドレスをぼかし、ユーザー データを識別できないようにする内部自動ルーチンを実行します。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって格納されたデータの組織コントロール

組織の管理者がパートナー システムで自分の情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンド ユーザー ポリシーなど。

>MongoDB: Google BigQuery を機能させるためにシステムデータとユーザー データを記録する: システム ログの使用状況を記録する Google Firestore: マイクロサービスの状態を維持および調整するシステム。 このサービス転送の唯一の重要なデータは、AES256 Stripe: Payment System を使用して暗号化されたユーザー資格情報です。
 
転送中のすべてのデータはセキュリティで保護された接続に HTTPS を使用し、すべての機密データは AES256 を使用して暗号化されます

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) カタログからの情報が次に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36141" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

