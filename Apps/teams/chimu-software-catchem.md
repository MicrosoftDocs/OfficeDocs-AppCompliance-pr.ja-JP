---
title: Chimu Software による CatchEm のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 04/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR レジストリ内の CatchEm、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、およびセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ba7936c4896fa9c6fc77eee773b6c52bec0af19d
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60435551"
---
# <a name="catchem"></a>CatchEm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 3 月 27 日</p>

* <a href="https://teams.microsoft.com/l/app/fc686a41-3bd0-45b3-a56d-f278888fd694" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002639" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Chimu Software から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | CatchEm |
| ID | WA200002639 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Chimu Software |
| パートナー Web サイトの URL | [https://chimusoftware.com](https://chimusoftware.com) |
| [アプリケーション情報Teamsページの URL | [https://catchem.apps.chimusoftware.com/help](https://catchem.apps.chimusoftware.com/help) |
| プライバシー ポリシーの URL | [https://www.chimusoftware.com/apps/catchem/privacy.html](https://www.chimusoftware.com/apps/catchem/privacy.html) |
| 利用規約の URL | [https://www.chimusoftware.com/apps/catchem/termsofuse.html](https://www.chimusoftware.com/apps/catchem/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、Chimu Software から、このアプリが組織データを収集および保存する方法、およびアプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.ReadBasic | 委任 | このアクセス許可は、アプリケーション ユーザーの連絡先を決定するために必要です。 AadObjectId: ユーザーを一意に識別します。 TenantId: 連絡先がユーザーの内部または外部かどうかを判断します。 DisplayName、GivenName、Surname: アプリケーション ユーザーへの連絡先を識別します。 メール、UserPrincipalName: 同じ名前の連絡先を区別し、クリックしてチャット機能 &quot; を &quot; 許可します。 最新のチャット ID: クリック &quot; してチャット機能を &quot; 有効にするには | このアクセス許可は、アプリケーション ユーザーの連絡先を決定するために必要です。 AadObjectId: ユーザーを一意に識別します。 TenantId: 連絡先がユーザーの内部または外部かどうかを判断します。 DisplayName、GivenName、Surname: アプリケーション ユーザーへの連絡先を識別します。 メール、UserPrincipalName: 同じ名前の連絡先を区別し、クリックしてチャット機能 &quot; を &quot; 許可します。 最新のチャット ID: クリック &quot; してチャット機能を &quot; 有効にするには | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| People.Read | 委任 | 外部連絡先のデータの精度を向上させる。 DisplayName: アプリケーション ユーザーへの連絡先を識別します。 | 外部連絡先のデータの精度を向上させる。 DisplayName: アプリケーション ユーザーへの連絡先を識別します。 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| Presence.Read.All | 委任 | 連絡先の現在のプレゼンス状態 | 該当なし | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| TeamsActivity.Send | 両方とも | 連絡先のプレゼンス状態が変更された場合にユーザーに通知を送信するには | 該当なし | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| TeamsAppInstallation.ReadWriteSelfForUser | 委任 | アプリケーションの自動更新を有効にするには | 該当なし | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| User.Read | 委任 | AadObjectId: ユーザーを一意に識別します。 TenantId: 連絡先がユーザーの内部または外部かどうかを判断します。 DisplayName、GivenName、Surname: アプリケーション ユーザーへの連絡先を識別します。 メール、IM アドレス、UserPrincipalName: 同じ名前の連絡先を区別し、クリックしてチャット機能を &quot; &quot; 許可します。 CompanyName、Country: Analytics。 AccountEnabled、DeletedDateTime: 無効なユーザーのユーザー データの自動削除 | AadObjectId: ユーザーを一意に識別します。 TenantId: 連絡先がユーザーの内部または外部かどうかを判断します。 DisplayName、GivenName、Surname: アプリケーション ユーザーへの連絡先を識別します。 メール、IM アドレス、UserPrincipalName: 同じ名前の連絡先を区別し、クリックしてチャット機能を &quot; &quot; 許可します。 CompanyName、Country: Analytics。 AccountEnabled、DeletedDateTime: 無効なユーザーのユーザー データの自動削除 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| User.ReadBasic.All | 委任 | 内部連絡先のデータの精度を向上させる。 AadObjectId: ユーザーを一意に識別します。 TenantId: 連絡先がユーザーの内部または外部かどうかを判断します。 DisplayName、GivenName、Surname: アプリケーション ユーザーへの連絡先を識別します。 メール、UserPrincipalName: 同じ名前の連絡先を区別し、クリックしてチャット機能 &quot; を &quot; 許可します。 | 内部連絡先のデータの精度を向上させる。 AadObjectId: ユーザーを一意に識別します。 TenantId: 連絡先がユーザーの内部または外部かどうかを判断します。 DisplayName、GivenName、Surname: アプリケーション ユーザーへの連絡先を識別します。 メール、UserPrincipalName: 同じ名前の連絡先を区別し、クリックしてチャット機能 &quot; を &quot; 許可します。 | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |
>| offline_access | 委任 | Graphトークンを使用して、ユーザーがアプリケーションをアクティブに使用していないときに、アプリケーションが連絡先プレゼンスの変更を通知し、連絡先リストを更新する | Graphセキュリティ トークン | [fc686a41-3bd0-45b3-a56d-f278888fd694](https://docs.microsoft.com/microsoft-365-app-certification/azure/fc686a41-3bd0-45b3-a56d-f278888fd694) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| メッセージ機能のタグは、連絡先の表示名を使用してアプリケーション &quot; &quot; ユーザーに表示する必要があります。 | 連絡先の表示名 | 連絡先の名前をアプリケーション ユーザーに返せ |


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

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36911" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、Chimu Software によって、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity 条件を処理する方法について提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | 不要 |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | はい |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
