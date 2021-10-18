---
title: キャロットHR 社によるアセンブリのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 06/08/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: アセンブリで使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ec566b8195ee476fa1b971cd638ebc1899a3a629
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430869"
---
# <a name="assembly"></a>Assembly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 5 月 21 日</p>

* <a href="https://teams.microsoft.com/l/app/3e674b5f-ba5d-41cc-8b06-e065b4394aeb" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002271" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

キャロットHR 社から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Assembly |
| ID | WA200002271 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | CarrotHR Inc. |
| パートナー Web サイトの URL | [https://www.joinassembly.com](https://www.joinassembly.com) |
| [アプリケーション情報Teamsページの URL | [https://www.joinassembly.com/about](https://www.joinassembly.com/about) |
| プライバシー ポリシーの URL | [https://joinassembly.com/privacy-policy](https://joinassembly.com/privacy-policy) |
| 利用規約の URL | [https://joinassembly.com/terms-of-service](https://joinassembly.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールについて、キャロットHR 社から提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.Create | 委任 | ユーザーがアプリから新しく作成したチャネルにアプリを割り当て許可する | アプリを正しいチャネルと同期するためにチャネル ID を保存します | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Directory.Read.All | アプリケーション | Assembly でメンバーが適切に検索可能な状態でプロファイルを同期する | Assembly でメンバーを検索可能に保つために使用できる可能性があるその他のプロファイル情報 | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Group.Read.All | 委任 | データを確認して、アプリを正しいグループに割り当て可能 | グループは保存しない | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| Teams.ReadBasic.All | アプリケーション | アプリを正しいチーム タブに割り当てる機能 | チームは、追加するチームを期待しているのを格納しない  | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| TeamsTab.Create | アプリケーション | これを使用して、アプリをチャネル/チームに適切に追加できます。 | タブ データを収集または保存していない | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| メール | 委任 | ユーザーの電子メールを使用して、ユーザーに特定のアカウントへのアクセス権を付与する | ユーザーの電子メールを使用して、特定のアカウントへのアクセス権を付与し、ID と一致する | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |
>| profile | 委任 | アセンブリを自動入力し、アセンブリ内の変更と同期を維持するユーザー Microsoft Teams | ユーザーの完全な名前 | [0a1b7ca8-390e-4f55-a7b5-eee089c5a905](https://docs.microsoft.com/microsoft-365-app-certification/azure/0a1b7ca8-390e-4f55-a7b5-eee089c5a905) |


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

>削除、保持、監査、アーカイブ

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39111' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39111" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 基準を処理する方法について、キャロットHR 社から提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | 不要 |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | 不要 |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
