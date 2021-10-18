---
title: Arrangr, Inc. による Arrangr のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Arrangr、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f4a5df023e906ad18e260debe09953351210d5bc
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60427869"
---
# <a name="arrangr"></a>Arrangr

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 6 月 15 日</p>

* <a href="https://teams.microsoft.com/l/app/57de46f8-193a-400c-9a34-c862333aed55" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002975" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Arrangr, Inc. から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Arrangr |
| ID | WA200002975 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Arrangr, Inc. |
| パートナー Web サイトの URL | [https://arrangr.com](https://arrangr.com) |
| [アプリケーション情報Teamsページの URL | [https://arrangr.com/welcome](https://arrangr.com/welcome) |
| プライバシー ポリシーの URL | [https://arrangr.com/privacy_policy](https://arrangr.com/privacy_policy) |
| 利用規約の URL | [https://arrangr.com/terms_of_use](https://arrangr.com/terms_of_use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールについて、Arrangr, Inc. から提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 委任 | 会議のスケジュールを容易にするために、ユーザーの予定表の名前と予定表イベントの詳細を収集します。 | 接続している予定表の名前を保存して、接続している予定表を表示および変更できます。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Channel.ReadBasic.All | 委任 | ユーザーが利用できるチャネルの一覧を収集し、そのチャネルのリストを表示して、アレンジの招待を共有するチャネルを選択できます。 | ユーザーのチャネルに関する情報は保存しない | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChannelMessage.Send | 委任 | このアクセス許可は、ユーザーに代わってチーム チャネルに Arrangr の招待を送信するために使用されます。 データの収集には使用されません。 | このアクセス許可を使用して収集されるデータは保存されません。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Chat.ReadWrite | 委任 | このアクセス許可は、ユーザーの代わりに、Teamsに Arrangr の招待を送信するために使用されます。 このアクセス許可は、データの収集には使用されません。 | このアクセス許可を使用して収集されるデータは保存されません。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| ChatMessage.Send | 委任 | このアクセス許可は、ユーザーに代わって 1:1 およびグループ チャットに Arrangr の招待を送信するために使用されます。 データの収集には使用されません。 | このアクセス許可を使用して収集されるデータは保存されません。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| OnlineMeetings.ReadWrite | 委任 | Arrangr は、Microsoft Teamsアクセス許可を使用して会議リンクを生成する過程で、会議リンクを収集します。 ユーザーのTeamsに基Teamsを生成します。 | 会議のリンクを保存して、会議に参加する適切な関係者と共有できます。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| People.Read | 委任 | ユーザーに関連するユーザーの名前とメールを収集します。 これにより、ユーザーが簡単にアレンジの招待の受信者として選択できます。 | ユーザーがこの API を介して提供される受信者を選択した場合、その受信者の名前と電子メールを保存して会議を実施し、ユーザーが将来受信者として選択し直すのを容易にします。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| Team.ReadBasic.All | 委任 | ユーザーの Teams の名前を収集し、ユーザーが Arrangr に接続する Teams と、そのユーザーがアレンジャーの招待を共有するチームを選択できます。 | Arrangr は、ユーザーが Arrangr へのリンクを選択した Teams の名前を格納し、それらの Teams を設定で表示し、アレンジの招待を共有する場所を決定するときにそれらの Teams から選択できます。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| TeamsAppInstallation.ReadWriteSelfForUser | 委任 | ユーザーの Teams アカウントにアプリがインストールされているかどうかを確認し、アプリをインストールするかどうかを確認し、アプリをインストールできます。 | このアクセス許可を通じて収集されたデータは保存されません。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |
>| profile | 委任 | 名前と電子メール アドレス | ユーザーがサービスに接続したアカウントをユーザーに表示するために、名前と電子メール アドレス。 | [57de46f8-193a-400c-9a34-c862333aed55](https://docs.microsoft.com/microsoft-365-app-certification/azure/57de46f8-193a-400c-9a34-c862333aed55) |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Outlook | はい | 名前、電子メール、予定表名、予定表イベント情報 | この情報を収集して、ユーザーが予定表を Arrangr に接続して会議のスケジュールを容易に行う | 名前、電子メール、予定表名 | この情報を保存して、ユーザーがサービスに接続したアカウントとカレンダーをユーザーに表示できます。 |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Cloud, SendGrid, Stripe, Quaderno | Google Cloud には、すべてのユーザー データ、ユーザー名、メールが SendGrid と共有され、ユーザーにメールを送信し、Stripe が受信したユーザー名、電子メール、支払い情報を支払い処理に使用します。 Quaderno は、売上税コンプライアンスを支援するために、ユーザー名、電子メール、および地理情報を受け取ります。 | Google Cloud は、ユーザーを記憶し、ユーザーが選択した情報を Arrangr に保存するためにデータを格納するために必要です。 使用に電子メールを送信するには、そのメール アドレスを SendGrid に提供する必要があります。 支払いを収集するには、Stripe で支払い情報を処理する必要がありますが、支払い情報は独自のサーバーに保存されません。 Quaderno は、売上税を計算し、売上税の規制に準拠している必要があります。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| ユーザーは、メッセージング拡張機能を使用して他のユーザーとの会議をスケジュールします。 ログインしているアカウントをユーザーに表示する必要があります。また、ユーザーが送信した招待を正しい Arrangr ユーザーに関連付ける必要があります。 | ユーザー名、電子メール、および通信情報。 | この情報は、複数の関係者間の会議を調整し、接続の詳細と、会議の開催者と共有するために必要です。 |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>Google Cloud Datastore に保存されているデータは、API を介して制御し、必要なデータを削除できます。 ユーザーは、アカウントの削除とデータの削除を要求できます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 基準を処理する方法について、Arrangr, Inc. から提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
