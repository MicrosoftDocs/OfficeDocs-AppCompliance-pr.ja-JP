---
title: ti m AG による ti8m の場所 &amp; のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 10/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: ti8m の場所で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 92b67a17394d796e0d743c6b3c570698e54e2fec
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411432"
---
# <a name="ti8m-places"></a>ti8m places

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 8 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/9e384ce2-2db2-412e-8da7-08c5cf4c418e" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003311" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

ti m AG から Microsoft &amp; に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | ti8m places |
| ID | WA200003311 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | ti&amp;m AG |
| パートナー Web サイトの URL | [https://www.ti8m.com/places](https://www.ti8m.com/places) |
| [アプリケーション情報Teamsページの URL | [https://www.ti8m.ch/places](https://www.ti8m.ch/places) |
| プライバシー ポリシーの URL | [https://ti8m.com/products/places/places-datenschutzerklaeru...](https://ti8m.com/products/places/places-datenschutzerklaerung) |
| 利用規約の URL | [https://ti8m.com/products/places/places-nutzungsbedingungen](https://ti8m.com/products/places/places-nutzungsbedingungen) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する ti m AG によって &amp; 提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite.Shared | 委任 | Workplaces とユーザーの予定表でイベントをキャンセルする  | 予約した予定表エントリをキャンセルする場合のイベント ID | [43134ae0-301f-4762-b7a9-aa9f2ff77b38](https://docs.microsoft.com/microsoft-365-app-certification/azure/43134ae0-301f-4762-b7a9-aa9f2ff77b38) |
>| Directory.ReadWrite.All | 委任 | 管理サーバー グループのインストールとAAD - セキュリティ グループ  | GroupNames と GroupIDs | [43134ae0-301f-4762-b7a9-aa9f2ff77b38](https://docs.microsoft.com/microsoft-365-app-certification/azure/43134ae0-301f-4762-b7a9-aa9f2ff77b38) |
>| Place.ReadWrite.All | 委任 | Workplaces とマップ名の一覧  | Workplace ID、Workplace および Displayname のメール アドレス。 Workplace の予約に使用する | [43134ae0-301f-4762-b7a9-aa9f2ff77b38](https://docs.microsoft.com/microsoft-365-app-certification/azure/43134ae0-301f-4762-b7a9-aa9f2ff77b38) |
>| User.Read | 委任 | ユーザー名、メール、および表示名、アプリケーションで Userdata を表示するために必要 | ユーザー名、メール、および表示名、アプリケーションで Userdata を表示するために必要 | [43134ae0-301f-4762-b7a9-aa9f2ff77b38](https://docs.microsoft.com/microsoft-365-app-certification/azure/43134ae0-301f-4762-b7a9-aa9f2ff77b38) |


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

>アーカイブ、削除

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 基準を処理する方法について、ti &amp; m AG によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | いいえ |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリは Web API を公開していますか? | いいえ |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

