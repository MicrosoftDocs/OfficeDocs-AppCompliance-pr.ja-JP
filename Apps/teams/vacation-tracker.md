---
title: 休暇追跡ツールによる休暇トラッカーのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 09/15/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: バケーション トラッカー、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7fb611741379a3c4d2f9f7a80708385e1b7f2675
ms.sourcegitcommit: d5c60e66355ffa8fb84565e565f8bb15a665a099
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/24/2021
ms.locfileid: "59785157"
---
# <a name="vacation-tracker"></a>Vacation Tracker

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 9 月 15 日</p>

* <a href="https://teams.microsoft.com/l/app/eab5463e-8168-40ee-887a-7ac78de1d266" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002167" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

バケーション トラッカーから Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Vacation Tracker |
| ID | WA200002167 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Vacation Tracker |
| パートナー Web サイトの URL | [https://vacationtracker.io](https://vacationtracker.io) |
| [アプリケーション情報Teamsページの URL | [https://vacationtracker.io/vacation-calendar-tracker-featur...](https://vacationtracker.io/vacation-calendar-tracker-features/) |
| プライバシー ポリシーの URL | [https://vacationtracker.io/privacy-policy/](https://vacationtracker.io/privacy-policy/) |
| 利用規約の URL | [https://vacationtracker.io/terms-of-service/](https://vacationtracker.io/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関して、バケーション トラッカーによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Group.Read.All | 委任 | ユーザーが毎週または毎日の通知を設定すると、パブリック チャネルの ID と名前が読み取りされます。 | ユーザーは、休暇トラッカーから毎日または毎週の通知を受信するチャネルを選択できます。 ユーザーが優先チャネルを選択すると、チャネル ID が保存されます。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| Team.ReadBasic.All | 委任 | ユーザーがバケーション トラッカー Microsoft Teamsするチームを選択するために、サインアップ中に参加したチームのメンバーを一覧表示します。 代わりに、組織全体にサインアップすることもできます。 | 選択したチームMicrosoft Teamsチーム ID は、ユーザーが (組織全体ではなく) 1 つのチームとして Vacation Tracker に登録した場合にのみ保存されます。 チーム ID を使用して、ログインしているユーザーをバケーション トラッカーの既存のアカウントに接続します。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.Read | 委任 | ユーザーの名前、ID、テナント ID など、基本的なユーザー情報を収集します。 このデータを使用して、ログインしているユーザーをバケーション トラッカーの組織に接続します。 | ユーザーの名前、ID、テナント ID を格納します。 このデータを使用して、ログインしているユーザーをバケーション トラッカーの組織に接続します。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.Read.All | 委任 | ユーザーは、組織またはチームからすべてのユーザー Microsoft 365インポートMicrosoft Teamsできます。 このアクセス許可を使用して、選択したユーザーまたはチームまたは組織Microsoft Teamsユーザーのみをインポートします。 | インポートされたユーザーに関する基本情報 (名前、電子メール アドレス、ユーザー ID など) が保存されます。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| User.ReadBasic.All | 委任 | ユーザーは、自分の組織または自分のチームから他のユーザー Microsoft Teamsできます。 このアクセス許可を使用して、インポート ポップアップで使用可能なユーザーとその電子メール アドレスを一覧表示します。 | ユーザーがバケーション トラッカーにインポートする同僚を選択すると、名前、電子メール アドレス、ユーザー ID など、これらのインポートされたユーザーに関する基本情報が保存されます。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| メール | 委任 | ユーザーが Microsoft AAD を使用してログインすると、電子メール アドレスは一意の識別子として保存されます。 | ユーザーのメールは一意の識別子として保存されます。 このメールは通信には使用しないので、ユーザーはサインアップ中に通信に使用するビジネス用の電子メール アドレスを入力します。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| offline_access | 委任 | この権限を持つデータは収集しない。 アクセス許可があるデータへのアクセスを維持するために使用されます。 | このアクセス許可を持つデータは保存しない。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| openid | 委任 | このアクセス許可を使用して、ユーザーをバケーション トラッカーにサインインまたはサインアップします。 この権限を持つ特定のデータは収集しない。 | このアクセス許可を使用して、ユーザーをバケーション トラッカーにサインインまたはサインアップします。 この権限を持つ特定のデータは保存しない。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |
>| profile | 委任 | ユーザーの名前、ID、テナント ID など、基本的なユーザー情報を収集します。 このデータを使用して、ログインしているユーザーをバケーション トラッカーの組織に接続します。 | ユーザーの名前、ID、テナント ID を格納します。 このデータを使用して、ログインしているユーザーをバケーション トラッカーの組織に接続します。 | [eab5463e-8168-40ee-887a-7ac78de1d266](https://docs.microsoft.com/microsoft-365-app-certification/azure/eab5463e-8168-40ee-887a-7ac78de1d266) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Stripe, AWS, Crisp, Customer.io, Segment, Amplitude, Google Tag Manager | 会社名 (ユーザーが入力) | ユーザーが登録すると、ユーザーは会社名を入力し、この名前を製品内の組織名として使用します。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| ボットは、ボットと通信するユーザーに関する基本的な情報を確認できます。 ただし、その情報を保存または使用することはできません。 ユーザーの ID、会話 ID、およびボットに送信されたメッセージのみを使用します。 | ユーザーの電子メール アドレス、ユーザーの名前 (Microsoft AAD で定義されている)、およびユーザーのプロファイル写真 (Microsoft AAD から) を保存します。 | ユーザーの一意の識別子として電子メール アドレスを使用し、ユーザーの名前とプロファイル写真を使用して、同じ会社の管理者と承認者がダッシュボードで従業員を認識できます。  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>会社名と、この種類のデータに関する標準の 1 年間の保持ポリシーに従って保持および削除される

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>まず、ユーザーから必要な最小データ量を収集します。 その後、可能な限り最小限のデータをパートナーと共有し、最終的にデータ保持ポリシーを設定し、該当する場合は 1 年間ですべてのデータが削除されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>必要

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36417" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 基準を処理する方法について、Vacation Tracker によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
