---
title: Flexfone による Myfone のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 07/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Myfone のすべての利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 37967a116553b7c7b83b1809c9b23a56822be5ed
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287915"
---
# <a name="myfone"></a>Myfone

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 7 月 15 日</p>

* <a href="https://teams.microsoft.com/l/app/5f447fa4-da1f-4651-a0da-d2488a404c19" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000716" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Flexfone から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Myfone |
| ID | WA200000716 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Flexfone |
| パートナー Web サイトの URL | [https://flexfone.dk](https://flexfone.dk) |
| [アプリケーション情報Teamsページの URL | [https://faq.flexfone.dk/da](https://faq.flexfone.dk/da) |
| プライバシー ポリシーの URL | [https://flexfone.dk/privatlivs-og-cookiepolitik](https://flexfone.dk/privatlivs-og-cookiepolitik) |
| 利用規約の URL | [https://flexfone.dk/Content/pdf/Slutkundebetingelser.pdf](https://flexfone.dk/Content/pdf/Slutkundebetingelser.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて、Flexfone によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | 委任 | カレンダーは、ユーザーが同僚に自分のケーランドを表示し、会議を使用してテレフォニーを設定するために使用するために使用されます。 | カレンダーは、ユーザーが同僚に自分のケーランドを表示し、会議を使用してテレフォニーを設定するために使用するために使用されます。 | [cdd5ed6f-ceda-4d46-a522-b7526d6d9e50](https://docs.microsoft.com/microsoft-365-app-certification/azure/cdd5ed6f-ceda-4d46-a522-b7526d6d9e50) |
>| Contacts.Read | 委任 | ユーザーの連絡先をアプリに表示して連絡先にダイヤルしやすくする場合は、連絡先を保存できます。 | ユーザーの連絡先をアプリに表示して連絡先にダイヤルしやすくする場合は、連絡先を保存できます。 | [cdd5ed6f-ceda-4d46-a522-b7526d6d9e50](https://docs.microsoft.com/microsoft-365-app-certification/azure/cdd5ed6f-ceda-4d46-a522-b7526d6d9e50) |
>| User.Read | 委任 | このアプリケーションで読み取ったユーザーは、識別の目的で使用されます。 | このアプリケーションで読み取ったユーザーは、識別の目的で使用されます。 | [cdd5ed6f-ceda-4d46-a522-b7526d6d9e50](https://docs.microsoft.com/microsoft-365-app-certification/azure/cdd5ed6f-ceda-4d46-a522-b7526d6d9e50) |
>| User.Read | 委任 | データは保存しない。 アプリケーションは単に認証の目的で使用されます。 | データは保存しない。 アプリケーションは単に認証の目的で使用されます。 | [f0199b83-0ca3-4b41-a23b-d9b234484438](https://docs.microsoft.com/microsoft-365-app-certification/azure/f0199b83-0ca3-4b41-a23b-d9b234484438) |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| EWS。AccessAsUser.All | はい | 会社名、従業員名、電話番号 | アプリ内のユーザーにデータを表示し、そのデータを使用するには | 会社名、従業員名、電話番号 | アプリ内のユーザーにデータを表示し、そのデータを使用するには |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| リボン コミュニケーション, Voxbone, team.blue, Fakturaservice.dk A/S, Elastic | 会社名、従業員名、電話番号 | リボンは、SBC Teams提供します。 Voxbone は国際番号に使用されますが、持っている場合にのみ使用されます。 team.blue はホスティング プロバイダーです。 FakturaService.dk/S は課金に使用されます。 Elastic はログ記録に使用されます。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>各ユーザーは、サービスを使用する会社の従業員です。 データを削除および編集できる管理者がいます。 エンド ユーザーがアクセス権を取得する前に、DDP も配置されている

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

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

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について Flexfone によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | いいえ |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | 多要素認証 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | いいえ |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | いいえ |
| アプリでプレビュー API を使用していますか? | はい |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
