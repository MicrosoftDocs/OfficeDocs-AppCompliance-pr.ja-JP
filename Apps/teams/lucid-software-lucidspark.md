---
title: Lucid Software による Lucidspark のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 05/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Lucidspark のすべての利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: e79bed420b3081ae31a0abda25299610eeb1bc5f
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287436"
---
# <a name="lucidspark"></a>Lucidspark

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 5 月 13 日</p>

* <a href="https://teams.microsoft.com/l/app/e9ab21fa-5fd5-48bb-a85d-4de7ced89cd1" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002583" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Lucid Software から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Lucidspark |
| ID | WA200002583 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Lucid Software |
| パートナー Web サイトの URL | [https://lucid.co](https://lucid.co) |
| [アプリケーション情報Teamsページの URL | [https://lucidchart.zendesk.com](https://lucidchart.zendesk.com) |
| プライバシー ポリシーの URL | [https://lucid.co/privacy](https://lucid.co/privacy) |
| 利用規約の URL | [https://lucid.co/tos](https://lucid.co/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関して、Lucid Software によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| メール | 委任 | 名前と電子メール アドレス。 | 電子メール、openid、およびプロファイルのアクセス許可を使用すると、Lucidspark はユーザーの openid トークンを生成し、必要に応じてユーザーに対して Lucidspark アカウントを登録するのに十分な基本的な情報を取得できます。 Microsoft から返されるデータを確認するために、応答に署名されている公開キーを取得する要求を行います。 その他のデータは、SSO フローの一部として Microsoft から受信または Microsoft に送信されません。 | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |
>| openid | 委任 | 名前と電子メール アドレス。 | 電子メール、openid、およびプロファイルのアクセス許可を使用すると、Lucidspark はユーザーの openid トークンを生成し、必要に応じてユーザーに対して Lucidspark アカウントを登録するのに十分な基本的な情報を取得できます。 Microsoft から返されるデータを確認するために、応答に署名されている公開キーを取得する要求を行います。 その他のデータは、SSO フローの一部として Microsoft から受信または Microsoft に送信されません。 | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |
>| profile | 委任 | 名前と電子メール アドレス。 | 電子メール、openid、およびプロファイルのアクセス許可を使用すると、Lucidspark はユーザーの openid トークンを生成し、必要に応じてユーザーに対して Lucidspark アカウントを登録するのに十分な基本的な情報を取得できます。 Microsoft から返されるデータを確認するために、応答に署名されている公開キーを取得する要求を行います。 その他のデータは、SSO フローの一部として Microsoft から受信または Microsoft に送信されません。 | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Lucidspark および lucidchart データは AWS と Snowflake に保存されます | 組織名、連絡先情報、およびライセンス レベル | Microsoft API は使用しない。 openID を使用して、SSO を実行するための基本的なユーザー データを取得します。 ファイル ピッカー API を使用しますが、ピッカーから送信されたファイル以外のユーザーのファイルにアクセスすることはできません。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>セキュリティおよびサポート上の理由から、電子メールと IP アドレスをログに記録します。 ログへのアクセスはすべて、第三者システムでは実際には変更できません &amp; 。 ログへのアクセスには MFA が必要です。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>Lucidspark および lucidchart データは AWS に保存されます。 これは、保存時と転送中に暗号化されます。 Lucid は、最小特権と MFA のルールを使用します。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について、Lucid Software によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
