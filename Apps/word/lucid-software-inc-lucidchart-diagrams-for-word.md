---
title: Lucid Software Inc. による Word 用 Lucidchart ダイアグラムのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 11/01/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Lucidchart Diagrams for Word、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: df9a4b46213f5bf7cecba6de5e539674dadec369
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60428440"
---
# <a name="lucidchart-diagrams-for-word"></a>Word 用の Lucidchart ダイアグラム

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2019 年 12 月 16 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380118" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Lucid Software Inc から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Word 用の Lucidchart ダイアグラム |
| ID | WA104380118 |
| Office 365サポートされているクライアント | Word 2016 Mac、Word 2013 以降では、Windows 以降Word on the web |
| パートナー会社名 | Lucid Software Inc |
| パートナー Web サイトの URL | [https://www.lucidchart.com](https://www.lucidchart.com) |
| プライバシー ポリシーの URL | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| 利用規約の URL | [https://www.lucidchart.com/pages/tos](https://www.lucidchart.com/pages/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて、Lucid Software Inc.によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| メール | 委任 | 名前と電子メール アドレス。 | 電子メール、openid、およびプロファイルのアクセス許可を使用すると、Lucidchart はユーザーの openid トークンを生成し、必要に応じてユーザーに対して Lucidchart アカウントを登録するのに十分な基本的な情報を取得できます。 Microsoft から返されるデータを確認するために、応答に署名されている公開キーを取得する要求を行います。 その他のデータは、SSO フローの一部として Microsoft から受信または Microsoft に送信されません。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| openid | 委任 | 名前と電子メール アドレス。 | 電子メール、openid、およびプロファイルのアクセス許可を使用すると、Lucidchart はユーザーの openid トークンを生成し、必要に応じてユーザーに対して Lucidchart アカウントを登録するのに十分な基本的な情報を取得できます。 Microsoft から返されるデータを確認するために、応答に署名されている公開キーを取得する要求を行います。 その他のデータは、SSO フローの一部として Microsoft から受信または Microsoft に送信されません。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| profile | 委任 | 名前と電子メール アドレス。 | 電子メール、openid、およびプロファイルのアクセス許可を使用すると、Lucidchart はユーザーの openid トークンを生成し、必要に応じてユーザーに対して Lucidchart アカウントを登録するのに十分な基本的な情報を取得できます。 Microsoft から返されるデータを確認するために、応答に署名されている公開キーを取得する要求を行います。 その他のデータは、SSO フローの一部として Microsoft から受信または Microsoft に送信されません。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| JavaScript API for Office | はい | javascript SDK のOffice OneDriveを使用して、OneDrive.open() を使用OneDriveファイル選択ツールを開きます。 アクセス トークンは生成されないので、ユーザー自身がアクセスOneDrive要求を行う必要があります。ファイル選択OneDrive SDK は、この機能を使用します。 ユーザーが選択したファイル名だけが表示されます。 |  | ユーザーがファイル選択ツールを使用してファイルを選択OneDrive、ファイル名を保存します。 |  |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Lucidchart データは AWS に保存されます。 |  | Microsoft API は使用しない。 openID を使用して、SSO を実行するための基本的なユーザー データを取得します。 ファイル ピッカー API を使用しますが、ピッカーから送信されたファイル以外のユーザーのファイルにアクセスすることはできません。 |



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>セキュリティおよびサポート上の理由から、電子メールと IP アドレスをログに記録します。 ログへのアクセスはすべて、第三者システムでは実際には変更できません &amp; 。 ログへのアクセスには MFA が必要です。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>Lucidchart データは AWS に保存されます。 これは、保存時と転送中に暗号化されます。 Lucidchart は、最小特権と MFA のルールを使用します。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>不要

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

