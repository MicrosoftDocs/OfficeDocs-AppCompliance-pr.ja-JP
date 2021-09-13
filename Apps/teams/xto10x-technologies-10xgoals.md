---
title: xto10x Technologies による 10xGoals のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 07/08/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 10xGoals で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 52b806ec307e396e67d9d91624e8be80c94142bb
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/12/2021
ms.locfileid: "59284963"
---
# <a name="10xgoals"></a>10xGoals

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 7 月 8 日</p>

* <a href="https://teams.microsoft.com/l/app/950aa4fb-0583-4b13-9b5f-bbc92b9cc376" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003122" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

xto10x Technologies から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | 10xGoals |
| ID | WA200003122 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | xto10x Technologies |
| パートナー Web サイトの URL | [https://www.xto10x.com/10xgoals/](https://www.xto10x.com/10xgoals/) |
| [アプリケーション情報Teamsページの URL | [https://www.xto10x.com/10xgoals/](https://www.xto10x.com/10xgoals/) |
| プライバシー ポリシーの URL | [https://www.xto10x.com/security/privacy-policy/](https://www.xto10x.com/security/privacy-policy/) |
| 利用規約の URL | [https://www.xto10x.com/security/terms-of-use/](https://www.xto10x.com/security/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、xto10x Technologies によって、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | アプリケーション | ユーザーのメールと azure ID がフェッチされ、組織のすべてのユーザーに対してアプリをプロアクティブにインストールできます。  | このアプリでは最初に 10xGoals サービス サブスクリプションが必要なので、ユーザーの電子メールとユーザーの Azure ID が 10xGoals サービスに送信され、そのユーザーに関連するアクティビティが発生すると、ユーザーのチーム アプリにプロアクティブ通知を送信できます。 | [950aa4fb-0583-4b13-9b5f-bbc92b9cc376](https://docs.microsoft.com/microsoft-365-app-certification/azure/950aa4fb-0583-4b13-9b5f-bbc92b9cc376) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | アプリケーション | アプリが管理者用にインストールされた teamsAppDefinition をフェッチし、組織のすべてのユーザーに対してプロアクティブにインストールするために必要です。  | この API からフェッチされるデータベースには何も格納されません。 | [950aa4fb-0583-4b13-9b5f-bbc92b9cc376](https://docs.microsoft.com/microsoft-365-app-certification/azure/950aa4fb-0583-4b13-9b5f-bbc92b9cc376) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| 10xGoals, AWS | ユーザーのメールとユーザーの AzureId を指定します。  | このアプリでは、最初に 10xGoals サービス サブスクリプションが必要なので、ユーザーの電子メールと azure ID のユーザーが 10xGoals サービスに送信され、そのユーザーに関連するアクティビティが発生すると、システムはユーザーにプロアクティブな通知を送信できます。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| このアプリでは最初に 10xGoals サービス サブスクリプションが必要なので、ユーザーの電子メールとユーザーの Azure ID が 10xGoals サービスに送信され、そのユーザーに関連するアクティビティが発生すると、ユーザーのチーム アプリにプロアクティブ通知を送信できます。 | いいえ |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>テナントが必要なアクセス許可を付与したかどうかに応じて、組織の tenantId が保存され、ウェルカム メッセージが異なっています。 テナントが既にアクセス許可を付与している場合、その組織の他のユーザーがアクセス許可を再び付与するフローを確認する必要はありません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>該当なし

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、xto10x Technologies によって、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity 条件を処理する方法について提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | いいえ |
| アプリに機密クライアントがありますか? | いいえ |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
