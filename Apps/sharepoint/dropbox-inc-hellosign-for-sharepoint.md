---
title: HelloSign for SharePoint(Dropbox)
ms.author: elmalova
author: elenamalova
ms.date: 10/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: SharePoint 用 HelloSign、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報に関する利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 5ff681f19369a1020cd67e6c161fb1a1dcca135e
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412096"
---
# <a name="hellosign-for-sharepoint"></a>HelloSign for SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 8 月 3 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003245" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Dropbox Inc. から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | HelloSign for SharePoint |
| ID | WA200003245 |
| Office 365サポートされているクライアント | SharePoint 2013 以降 |
| パートナー会社名 | DropboxInc. |
| パートナー Web サイトの URL | [https://hellosign.com](https://hellosign.com) |
| プライバシー ポリシーの URL | [https://www.hellosign.com/privacy](https://www.hellosign.com/privacy) |
| 利用規約の URL | [https://hellosign.com/terms](https://hellosign.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、Dropbox Inc. から、このアプリが組織データを収集および保存する方法、およびアプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Files.ReadWrite.All | アプリケーション | これは Sites.ReadWrite.All と一緒に使用して、HelloSign 署名付きファイルを新しいサイトに書きSharePointします。 | このスコープに関連するデータは保存しない | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |
>| Sites.ReadWrite.All | アプリケーション | これは Files.ReadWrite.All と一緒に使用して、HelloSign 署名済みファイルを別のサイトに書きSharePointします。 | このスコープに関連するデータは保存しない | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |
>| User.Read | 委任 | アプリケーション内のユーザーを識別するために使用される電子メール | 電子メールに基づいて HelloSign アカウントと相互参照するために使用される電子メール | [6fcff87e-0f86-49c3-81eb-bc028d1ccfe6](https://docs.microsoft.com/microsoft-365-app-certification/azure/6fcff87e-0f86-49c3-81eb-bc028d1ccfe6) |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePointAPI | はい | メール、テナント ID、およびサイト ID | 識別と認証の目的で使用される | メール、テナント ID、サイト ID | 識別と認証の目的で使用される |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| https://www.hellosign.com/subprocessors | メール、テナント ID、サイト ID | JN Projects, Inc. dba HelloSign (&#8220;HelloSign&#8221;) は、特定のサブプロセッサを使用してサービスの提供を支援します。 弊社は、お客様およびエンド ユーザーに関する個人データを保存および処理するサービス プロバイダーを使用します (それぞれ、&#8220;Sub-Processor&#8221;)。 このページでは、これらのマテリアルサブプロセッサの ID、場所、および役割に関する重要な情報を提供します。 このページで使用されるが定義されていない用語は、利用規約 (&#8220;契約&#8221;)。 |



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>パートナー システムに存在するデータの削除、保持、およびログ機能があります

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>不要

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity 条件を処理する方法について、Dropbox Inc. から提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | 不要 |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリは Web API を公開していますか? | いいえ |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

