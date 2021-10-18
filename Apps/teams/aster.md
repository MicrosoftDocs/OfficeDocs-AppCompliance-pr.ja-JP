---
title: Aster による Aster のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 09/29/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Aster で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f7691d2a438b8245092cc364810e1a42baa20258
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60436621"
---
# <a name="aster"></a>Aster

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>最終更新日: 2021 年 9 月 28 日</p>

* <a href="https://teams.microsoft.com/l/app/2d8e8042-66df-4605-8c3a-9ca8962f3e99" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002379" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Aster から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Aster |
| ID | WA200002379 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Aster |
| パートナー Web サイトの URL | [https://asterapp.co](https://asterapp.co) |
| [アプリケーション情報Teamsページの URL | [https://asterapp.co/solution/](https://asterapp.co/solution/) |
| プライバシー ポリシーの URL | [https://asterapp.co/politique-de-confidentialite/](https://asterapp.co/politique-de-confidentialite/) |
| 利用規約の URL | [https://asterapp.co/conditions-generales/](https://asterapp.co/conditions-generales/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Aster によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | 委任 | Sharepoint ドキュメントの Planner タスクを送信するディレクトリの一覧 | なし | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| Group.ReadWrite.All | 委任 | 既存または作成されたグループの Sharepoint ドキュメントの Planner タスクを送信するグループの一覧 | なし | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| Notes.ReadWrite.All | 委任 | メモに書き込むOneNote | なし | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| Tasks.ReadWrite.Shared | 委任 | タスク、割り当て、期限 | すべての API タスクを Aster タスクGraph同期するデータ | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| User.Read | 委任 | ユーザーを識別するためのユーザーメール | 割り当て内のユーザーメール (例) | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |
>| offline_access | 委任 | データは収集されません。トークンを明らかに更新するだけの場合 | なし | [27c89ce8-b449-4959-b801-988d8b727512](https://docs.microsoft.com/microsoft-365-app-certification/azure/27c89ce8-b449-4959-b801-988d8b727512) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 人的および人的な方法でユーザーと通信するには | 不要 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>すべてのアクセスがログに記録され、ユーザーの電子メールで識別されます

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>RGPD コントラクト

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Id 条件を処理する方法について Aster によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | いいえ |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | いいえ |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリは Web API を公開していますか? | 不要 |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
