---
title: UAB Lucid Agreements による isLucid のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: isLucid、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 5c482dbb0a7fda2f588eef80e16abb5f495be478
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60445019"
---
# <a name="islucid"></a>isLucid

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 8 月 9 日</p>

* <a href="https://teams.microsoft.com/l/app/a5711b63-5e70-4e4e-b040-0d714b64f684" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002385" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

UAB Lucid Agreements から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | isLucid |
| ID | WA200002385 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | UAB Lucid Agreements |
| パートナー Web サイトの URL | [https://islucid.com](https://islucid.com) |
| [アプリケーション情報Teamsページの URL | [https://islucid.com](https://islucid.com) |
| プライバシー ポリシーの URL | [https://islucid.com/privacy-policy/](https://islucid.com/privacy-policy/) |
| 利用規約の URL | [https://islucid.com/eula/](https://islucid.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する UAB Lucid Agreements によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calls.AccessMedia.All | 両方とも | 各呼び出しに対するユーザー固有の同意 (開始された文字起こし) を使用すると、オーディオ ストリームにアクセスします。 オーディオ ストリームはトランスクリプション サービスに転送され、ユーザーはさらに機能を利用できます。 | アプリは、Azure 上の分離されたコンテナー (BLOB ストレージと各クライアントCosmos DB) の文字起こしと関連するメタ情報に格納します。 これは、アプリケーションを使用し、特定の会議に参加したユーザーに対して、会議情報をさらにアクセスするために必要です。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Calls.JoinGroupCall.All | 両方とも | 各呼び出しに対するユーザー固有の同意 (開始された文字起こし) を使用すると、オーディオ ストリームにアクセスします。 オーディオ ストリームはトランスクリプション サービスに転送され、ユーザーはさらに機能を利用できます。 | アプリは、Azure 上の分離されたコンテナー (BLOB ストレージと各クライアントCosmos DB) の文字起こしと関連するメタ情報に格納します。 これは、アプリケーションを使用し、特定の会議に参加したユーザーに対して、会議情報をさらにアクセスするために必要です。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Group.ReadWrite.All | 両方とも | ユーザーが Microsoft Planner との統合を使用して通話からタスクを作成し、MS Planner に自動的に保存する場合、isLucid は、そのユーザーが利用可能なグループ、計画、担当者に対して収集します。 この権限がない場合、ユーザーは isLucid を使用して文字起こしからタスクを作成できない | タスクタイトル、タスク作成者、タスクタイムスタンプ、タスクの説明が保存され、ユーザーは特定の会議から作成されたタスクの履歴にアクセスできます。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| OnlineMeetings.Read.All | 両方とも | アプリケーションは会議のタイトルを収集し、ユーザーが後で (会議が終了すると) 以前のトランスクリプトやタスクを簡単に見つけ出す可能性があります。 | 会議のタイトル、会議のタイムスタンプ、会議の開催者 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| Tasks.ReadWrite | 両方とも | ユーザーが Microsoft Planner との統合を使用して通話からタスクを作成し、MS Planner に自動的に保存する場合、isLucid は、そのユーザーが利用可能なグループ、計画、担当者に対して収集します。 この権限がない場合、ユーザーは isLucid を使用して文字起こしからタスクを作成できない | タスクタイトル、タスク作成者、タスクタイムスタンプ、タスクの説明が保存され、ユーザーは特定の会議から作成されたタスクの履歴にアクセスできます。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| User.ReadWrite.All | 両方とも | ユーザーが Microsoft Planner との統合を使用して通話からタスクを作成し、MS Planner に自動的に保存する場合、isLucid は、そのユーザーが利用可能なグループ、計画、担当者に対して収集します。 この権限がない場合、ユーザーは isLucid を使用して文字起こしからタスクを作成できない | タスクタイトル、タスク作成者、タスクタイムスタンプ、タスクの説明が保存され、ユーザーは特定の会議から作成されたタスクの履歴にアクセスできます。 | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |
>| openid | 両方とも | ユーザー ID、テナント ID が収集され、Azure Active Directoryのログイン機能が提供されます。 | ユーザー ID、さらに権限管理を行うテナント ID | [98b70422-b0b2-41bf-8673-60d85f5d38c7](https://docs.microsoft.com/microsoft-365-app-certification/azure/98b70422-b0b2-41bf-8673-60d85f5d38c7) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| hubspot.com | 新しく登録されたユーザーの電話、姓、メール、およびユーザー番号 | Hubspot CRM を使用して販売関連情報を管理しています |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| ボットは、トランスクリプション サービスへのオーディオ ストリームの送信を有効にしています。 読み取り可能な文字起こしを提供するには、音声をユーザー (スピーカー) に関連付ける必要があります。 このような情報トランスクリプトを提供しない場合は、使用しない | ゲスト アカウントまたは Microsoft アカウントの場合の名前、姓、状態 | ボットは、トランスクリプション サービスへのオーディオ ストリームの送信を有効にしています。 読み取り可能な文字起こしを提供するには、音声をユーザー (スピーカー) に関連付ける必要があります。 会議参加者の情報は、ユーザーが会議に出席していたユーザーを表示するためにも関連します。 |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>サービスを使用しているユーザーはトランスクリプトを生成しています。 トランスクリプトでは、会議参加者 (名前、姓) が提示されます。 呼び出し中に何でも言及できる可能性があります。 このデータは、ユーザーがサービスを使用している限り保存されます。 クライアントが弊社の使用を終了すると、30 日以内に関連付けられているすべてのデータが破棄されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>クライアントがホスト型ソリューションとして IsLucid を購入した場合、クライアント上のデータは制御しません。 SaaS ソリューションでは、ユーザーがサービスを使用して取り消しを行い、パートナーにCosmos DB isntance を削除します。 コンプライアンス API にも情報を送信中です

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 基準を処理する方法に関する UAB Lucid Agreements によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | いいえ |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | はい |
| アプリで非推奨の API を使用していますか? | はい |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
