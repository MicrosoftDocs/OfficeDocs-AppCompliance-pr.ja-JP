---
title: アサナのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: ASANA の利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6c18bb20cdf753b1a5d998b3d7b7144f950f00c0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553408"
---
# <a name="asana"></a>Asana

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年11月2日</p>

* <a href="https://teams.microsoft.com/l/app/f0e33e18-08fc-4511-a2a7-c6bdff367263" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001727" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

アサナがマイクロソフトに提供した情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Asana |
| ID | WA200001727 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Asana |
| パートナーウェブサイトのURL | [https://asana.com/?noredirect&amp;utm_source=asana_inproduct &amp;](https://asana.com/?noredirect&amp;utm_source=asana_inproduct&amp;utm_medium=organic_inproduct&amp;utm_campaign=msft_teams_launch) |
| プライバシーポリシーの URL | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| 利用規約の URL | [https://asana.com/terms#terms-of-service](https://asana.com/terms#terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法、およびアプリが収集するデータに対する組織のコントロールに関する情報を Asana によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションは、マイクロソフトのGraphを使用していません。


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>| **すべての非Microsoft サービス OII は、** |  **どのようなOIIが転送されますか?** | **OIIを転送するための正当性?** |
>|:-------------------|:--------------------------|:--------------------------|
>| アドインは、ユーザーから要求された場合に、基本的な電子メール情報 (送信者、受信情報、件名、本文) と添付ファイルを Asana に転送します。 |  | 電子メール - 作業ウィンドウに表示されているときに現在開いている電子メールを読み取ります。 - 現在開いている電子メールの添付ファイルを読み取り、Asana タスクにアップロードします。 - これにより、ユーザーは、メールからの情報をAsanaで迅速にタスクを作成することができます。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>当社のアプリケーションは、Asanaデータに関連する情報のみを記録します。 ユーザー情報Outlook関連するものを記録するのは、ユーザーが明示的にメールを添付したり、添付ファイルをAsanaにアップロードしたりした場合のみで、その場合でも内容を記録しません。 短期ログは、一部のユーザー データを含むサーバー上に存在しますが、一時的なログであり、72 時間以内の期間に制限されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>Enterpriseお客様は、AES-256を使用して保管時の暗号化を保証しています。 データはアマゾン ウェブ サービスに保存され、AWS はキー管理システムを使用して暗号化キーを管理します。 私たちはすべての管理者のための2FAを持っています。 アクセスは最小特権の原則に基づいて与えられます。
Asana 組織の管理者は、SAML、SCIM、サービス アカウントを設定し、ツールに配置されるデータを包括的に表示できます。 管理者は、管理コンソールから完全な組織のエクスポートをリクエストし、必要に応じて監査できます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

