---
title: ルシッドソフトウェア社によるPowerPointのための明晰チャート図のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: PowerPointのLucidchart図、そのデータ処理ポリシー、Microsoft Cloud App Securityアプリカタログ情報、CSA STARレジストリのセキュリティ/コンプライアンス情報に関する利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 024b2e925ba84967bf40754908a8d98baa1d705f
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553608"
---
# <a name="lucidchart-diagrams-for-powerpoint"></a>PowerPointのための明晰チャート図

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2019年12月16日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380117" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Lucid ソフトウェア社がマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | PowerPointのための明晰チャート図 |
| ID | WA104380117 |
| サポートされるクライアントOffice 365 | PowerPoint 2016 2013年以降のMac PowerPoint PowerPoint on the web Windows |
| パートナー会社名 | ルシッド・ソフトウェア株式会社 |
| パートナーウェブサイトのURL | [https://www.lucidchart.com/](https://www.lucidchart.com/) |
| プライバシーポリシーの URL | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| 利用規約の URL | [https://www.lucidchart.com/pages/tos](https://www.lucidchart.com/pages/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法と、アプリが収集するデータに対する組織の制御についてLucid Software Inc.によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| メール | 委任 | 名前と電子メール アドレス。 | 電子メール、openid、およびプロファイルのアクセス許可により、LucidchartはユーザーのOpenidトークンを生成し、必要に応じてLucidchartアカウントを登録するのに十分な基本的な情報を取得できます。 Microsoft から返されるデータを確認するために、応答に署名された公開キーを取得するよう要求します。 SSO フローの一部として、マイクロソフトから他のデータを受信または送信するデータはありません。 |  |
>| openid | 委任 | 名前と電子メール アドレス。 | 電子メール、openid、およびプロファイルのアクセス許可により、LucidchartはユーザーのOpenidトークンを生成し、必要に応じてLucidchartアカウントを登録するのに十分な基本的な情報を取得できます。 Microsoft から返されるデータを確認するために、応答に署名された公開キーを取得するよう要求します。 SSO フローの一部として、マイクロソフトから他のデータを受信または送信するデータはありません。 |  |
>| profile | 委任 | 名前と電子メール アドレス。 | 電子メール、openid、およびプロファイルのアクセス許可により、LucidchartはユーザーのOpenidトークンを生成し、必要に応じてLucidchartアカウントを登録するのに十分な基本的な情報を取得できます。 Microsoft から返されるデータを確認するために、応答に署名された公開キーを取得するよう要求します。 SSO フローの一部として、マイクロソフトから他のデータを受信または送信するデータはありません。 |  |

#### <a name="data-access-using-other-microsoft-apis"></a>他のマイクロソフト API を使用したデータ アクセス

Microsoft 365上に構築されたアプリやアドインでは、Microsoft Graph 以外の Microsoft API を使用して、組織を識別できる情報 (OII) を収集または処理できます。 このアプリが使用するマイクロソフトGraph以外のマイクロソフト API を一覧表示します。

>| **API** |  **OIIは収集されますか?** |  **OIIは何を収集されますか?** | **OIIを収集するための正当性?** | **OII は保存されていますか?** | **OIIを格納するための正当性?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript API for Office | はい | OneDrive.open() を使用してOneDriveファイル選択機能を開くには、javascript SDK Office OneDriveを使用します。 当社はアクセストークンを生成せず、OneDriveのAPIに対していかなる要求も行いません。OneDriveファイル選択SDKは私たちのためにそれを行います。 ユーザーが選択したファイル名のみが表示されます。 |  | ユーザーがファイル選択OneDriveを使用してファイルを選択した場合は、ファイル名を保存します。 |  |

#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>| **すべての非Microsoft サービス OII は、** |  **どのようなOIIが転送されますか?** | **OIIを転送するための正当性?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Lucidchart データは AWS に保存されます。 |  | マイクロソフト API は使用しません。 OpenID を使用して、SSO を実行するための基本的なユーザー データを取得します。 私たちは彼らのファイルピッカーAPIを使用しますが、ピッカーを通じて送信するもの以外のユーザーのファイルへのアクセスは提供されません。 |



#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>セキュリティとサポートの理由から、電子メールとIPアドレスを記録します。 ログへのアクセスはすべて記録された &amp; ログであり、実際にはサードパーティのシステムでは変更できません。 ログへのアクセスには MFA が必要です。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>Lucidchart データは AWS に保存されます。 これは、保存時および転送中に暗号化されます。 Lucidchart では、最小特権と MFA の規則を使用します。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

