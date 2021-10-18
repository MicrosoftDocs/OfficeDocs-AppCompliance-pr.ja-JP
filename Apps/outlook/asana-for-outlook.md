---
title: Asana for Outlookアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 10/29/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: asana for Outlook、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 754ee6bf347114c9d76107d641da940d5a62c10e
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60430557"
---
# <a name="asana-for-outlook"></a>Asana for Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 11 月 2 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381833" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Asana から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Asana for Outlook |
| ID | WA104381833 |
| Office 365サポートされているクライアント | Outlook 2016 Mac 上の Windows、Outlook 2016以降の Mac の場合は、Outlook on the web |
| パートナー会社名 | Asana |
| パートナー Web サイトの URL | [https://asana.com](https://asana.com) |
| プライバシー ポリシーの URL | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| 利用規約の URL | [https://asana.com/terms#terms-of-service](https://asana.com/terms#terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関して Asana によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft アプリケーションをGraph。


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| アドインは、ユーザーからの要求に応じて、基本的な電子メール情報 (送信者、再通知、件名、本文) と添付ファイルを Asana に転送します。 |  | [メール] - 作業ウィンドウに表示されている現在開いている電子メールを読み取ります。 - Asana タスクにアップロードする現在開いているメール添付ファイルを読み取ります。 - これにより、ユーザーは Asana のタスクをすばやく作成し、電子メールからの情報を得る機能を提供します。 |



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションは、Asana データに関連する情報のみをログに記録します。 Outlook ユーザー情報に関連する情報をログに記録する唯一の時間は、ユーザーが明示的に電子メールを添付するか、Asana に添付ファイルをアップロードし、その後もコンテンツをログに記録しない場合です。 短期的なログは、一部のユーザー データを含む可能性があるサーバーに存在しますが、一時的なログであり、72 時間未満の期間に制限されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>Enterpriseは、AES-256 を使用して保存時の暗号化を保証しています。 データは Amazon Web Services に保存され、AWS はキー管理システムを使用して暗号化キーを管理します。 すべての管理者に 2FA があります。 アクセスは、最小特権の原則に基付けされます。
Asana 組織の管理者は、SAML、SCIM、Service アカウントをセットアップし、ツールに入れるデータの包括的なビューを持つ機能を持っています。 管理者は、管理コンソール内から組織全体のエクスポートを要求し、必要に応じて監査を行います。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>不要

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

