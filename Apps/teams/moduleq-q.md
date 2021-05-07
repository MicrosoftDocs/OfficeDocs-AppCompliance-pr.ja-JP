---
title: ModuleQ による Q のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: CSA STAR レジストリ内のすべての利用可能なセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、およびセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2821009fea219a32a935dba7043d5ba0a48b826c
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/06/2021
ms.locfileid: "52252407"
---
# <a name="q"></a>Q

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020 年 3 月 17 日</p>

* <a href="https://teams.microsoft.com/l/app/72bb25c7-3644-4318-8249-a08e5493a520" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381433" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

ModuleQ から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Q |
| ID | WA104381433 |
| 機能 | ボット、タブ |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | ModuleQ |
| パートナー Web サイトの URL | [https://moduleq.com](https://moduleq.com) |
| プライバシー ポリシーの URL | [https://moduleq.com/privacy-policy/](https://moduleq.com/privacy-policy/) |
| 利用規約の URL | [https://moduleq.com/terms-of-service/](https://moduleq.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する ModuleQ によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | アプリケーション | メッセージ本文と添付ファイルを除く会議データを格納する | アプリケーションがユーザーの予定表イベントを読み取って、ユーザーのビジネスの優先順位をインテリジェントに理解できます。 | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Group.Read.All | 委任 | なし | アプリがチームでコンテンツを共有するための操作を許可します。 | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Mail.Read | アプリケーション | メッセージ本文と添付ファイル以外の電子メール データを格納する | アプリケーションがユーザーのメールを読み取って、ユーザーのビジネスの優先順位をインテリジェントに理解できます。 | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read | 委任 | ユーザーの電子メールトークンと認証トークン | ユーザーが自分のアカウントにサインインして、自分のアカウントOffice 365 ModuleQ アカウントにリンクできます。 | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read.All | 委任 | なし | アプリで、ユーザーが参加しているTeams一覧を取得できます。 共有にのみ使用  | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>内部ユーザー GUID と組織名とドメインを記録します。 現時点では、アーカイブまたは削除のコントロールはありません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>データは、機能に応じて複数Microsoft Azureクラウドに格納されます。 すべてのユーザー識別可能なデータは、ストレージ用に送信する前に、AES-256 暗号化を使用してクライアント側で暗号化されます。 データは、上級管理職の承認を得て、デバッグ目的でエンジニアによって表示される場合があります。 データへのアクセスは、内部 VPN を介して制御されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

