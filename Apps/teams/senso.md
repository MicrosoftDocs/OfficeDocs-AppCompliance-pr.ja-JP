---
title: Senso による Senso のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Senso、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3e538fddf6ca799348ca010c7553a0dd1439fba1
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429575"
---
# <a name="senso"></a>Senso

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 8 月 2 日</p>

* <a href="https://teams.microsoft.com/l/app/3973b9d4-b50e-472d-8145-8967e01379b4" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002571" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Senso から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Senso |
| ID | WA200002571 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Senso |
| パートナー Web サイトの URL | [https://www.senso.cloud](https://www.senso.cloud) |
| [アプリケーション情報Teamsページの URL | [https://www.senso.cloud/safeguarding-microsoft-teams/](https://www.senso.cloud/safeguarding-microsoft-teams/) |
| プライバシー ポリシーの URL | [https://www.senso.cloud/privacy](https://www.senso.cloud/privacy) |
| 利用規約の URL | [https://www.senso.cloud/eula](https://www.senso.cloud/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて、Senso によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | アプリケーション | すべてのチャネルのチャネル名と説明を読み、違反のフラグが設定された場所を特定します。   | 違反が発生すると、送信者 (From) の名前、受信者 (To) の名前、チャネル名、日付、時刻、およびそのチャット チャネルからのメッセージが、違反にコンテキストを提供するためにログに記録されます。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMember.Read.All | アプリケーション | すべてのチャネルのメンバー リストとチャット メッセージを読み取る。 | 違反が発生すると、送信者 (From) の名前、受信者 (To) の名前、チャネル名、日付、時刻、およびそのチャット チャネルからのメッセージが、違反にコンテキストを提供するためにログに記録されます。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| ChannelMessage.Read.All | アプリケーション | すべてのチャネル メッセージを読み取る | 違反が発生すると、送信者 (From) の名前、受信者 (To) の名前、チャネル名、日付、時刻、およびそのチャット チャネルからのメッセージが、違反にコンテキストを提供するためにログに記録されます。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Chat.Read.All | アプリケーション | すべてのチャット メッセージの読み取り | 違反が発生すると、送信者 (From) の名前、受信者 (To) の名前、チャネル名、日付、時刻、およびそのチャット チャネルからのメッセージが、違反にコンテキストを提供するためにログに記録されます。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Directory.Read.All | アプリケーション | ディレクトリ データの読み取り | 違反が発生すると、送信者 (From) の名前、受信者 (To) の名前、チャネル名、日付、時刻、およびそのチャット チャネルからのメッセージが、違反にコンテキストを提供するためにログに記録されます。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| Files.Read.All | アプリケーション | すべてのサイト コレクションにおけるファイルの読み取り | 違反が発生すると、送信者 (From) の名前、受信者 (To) の名前、チャネル名、日付、時刻、およびそのチャット チャネルからのメッセージが、違反にコンテキストを提供するためにログに記録されます。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read | 委任 | サインインおよびユーザー プロファイルの読み取り | シングル サインオンに使用される | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |
>| User.Read.All | アプリケーション | すべてのユーザーの完全なプロファイルの読み取り | 違反が発生すると、送信者 (From) の名前、受信者 (To) の名前、チャネル名、日付、時刻、およびそのチャット チャネルからのメッセージが、違反にコンテキストを提供するためにログに記録されます。  | [a9d28fcf-036e-4a85-9003-332303e3a29b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a9d28fcf-036e-4a85-9003-332303e3a29b) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Senso.cloud は、サービスのパフォーマンスに次のサブプロセッサを使用します。セクション https://www.senso.cloud/privacy-policy/ 5。 個人データの開示。 | サード パーティのアカウントおよびサード パーティ プロバイダーと共有するデータの種類は、表のセクション 5 の右記列 ( に示されています https://www.senso.cloud/privacy-policy/) 。 | それぞれを処理する合法的な根拠は、お客様との契約のパフォーマンスに基づいており、または正当な利益のために必要です (ビジネスの実行、データのアーカイブ、管理と IT サービスの提供、ネットワーク セキュリティ、詐欺やデータ漏洩を防ぐため)。 たとえば、ビジネス メール アドレス、電子メール アドレスは、請求連絡先の通知を顧客に送信するために必要です。またはクレジット カードで支払う場合は、顧客サポートにアクセスするときにサポート チケットを調達するために情報が必要です。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Senso.cloud は、サービスのパフォーマンスに次のサブプロセッサを使用します。セクション https://www.senso.cloud/privacy-policy/ 5。 個人データの開示。 | サード パーティのアカウントおよびサード パーティ プロバイダーと共有するデータの種類は、表のセクション 5 の右記列 ( に示されています https://www.senso.cloud/privacy-policy/) 。 | それぞれを処理する合法的な根拠は、お客様との契約のパフォーマンスに基づいており、または正当な利益のために必要です (ビジネスの実行、データのアーカイブ、管理と IT サービスの提供、ネットワーク セキュリティ、詐欺やデータ漏洩を防ぐため)。 たとえば、ビジネス メール アドレス、電子メール アドレスは、請求連絡先の通知を顧客に送信するために必要です。またはクレジット カードで支払う場合は、顧客サポートにアクセスするときにサポート チケットを調達するために情報が必要です。 |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>Senso は、キーワードや画像の脅威検出ライブラリに対してチャット メッセージを監視します。  一致が発生した場合は、違反トリガーに対して次の情報を記録します。時間と日付、サイト ID、語句/画像、重大度、From、To、チャネル名、ステータス、およびエンド ユーザーによるレビューのためのライブラリのトリガー。  PII は、法的、運用上、会計上、または報告の要件を満たす目的を含め、収集した目的を達成するために必要な期間のみ保持します。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>シニア開発者、IP ロック、2 要素認証、監査証跡へのアクセスが制限されています。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/40112" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について Senso によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | 役割ベースのアクセス許可 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/><br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | いいえ |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
