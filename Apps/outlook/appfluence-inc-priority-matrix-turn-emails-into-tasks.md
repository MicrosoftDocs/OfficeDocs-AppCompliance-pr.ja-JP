---
title: 優先度マトリックスのアプリケーション情報 - Appfluence Inc によるメールをタスクに変換する
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
description: Priority Matrix で使用可能なすべてのセキュリティおよびコンプライアンス情報 - CSA STAR レジストリのタスク、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、およびセキュリティ/コンプライアンス情報に電子メールを変換します。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f92f29796daf072b24233bdcc9459d7db82d40bc
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095994"
---
# <a name="priority-matrix---turn-emails-into-tasks"></a>優先度マトリックス - メールをタスクに変換する

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者が最終更新日: 2020 年 11 月 17 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381735" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Appfluence Inc から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | 優先度マトリックス - メールをタスクに変換する |
| ID | WA104381735 |
| Office 365サポートされているクライアント | Outlook 2016、Windows Outlook 2016以降の Mac、Outlook on iOS、Outlook android、Outlook web |
| パートナー会社名 | Appfluence Inc |
| パートナー Web サイトの URL | [https://appfluence.com/](https://appfluence.com/) |
| プライバシー ポリシーの URL | [https://appfluence.com/privacy](https://appfluence.com/privacy) |
| 利用規約の URL | [https://appfluence.com/eula](https://appfluence.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関して Appfluence Inc によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | 委任 | 新しいユーザーがアカウントに追加された場合にのみ、メールを保存します。 | 新しいアカウントの作成では、これを使用して他のチーム メンバーを提案します。 | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| User.ReadBasic.All | 委任 | 新しいユーザーがアカウントに追加された場合にのみ、メールを保存します。 | 新しいアカウントの作成では、これを使用して他のチーム メンバーを提案します。 | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| offline_access | 委任 | ユーザーに代わって要求を実行するためにログイン トークンを保存します | ユーザーに迷惑をかけることなくトークンを更新します。 (優先行列のTeams) | 5be2b320-a5b7-4221-893c-dee506e4e365 |
>| Files.Read.All | 委任 | ユーザーが元のファイルにリンクする Priority Matrix アイテムを明示的に作成しない限り、ファイル情報は保存しない。 | 1 対 1 の機能 (Web アプリと Outlook/Teams アドインで利用できます)では、この機能を使用して、会議と全体的な共同作業を促進する方法として、システム内の 2 人のユーザー間で共有される SharePoint/OneDrive ファイルを強調表示します。 | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| User.Read | 委任 | 基本的なユーザー プロファイル情報 (表示名、名、名、電子メール、アバター) は、私たちによって保存されます。 | ユーザーの名前、メール、アバターを取得して、アカウントをカスタマイズします。 | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| openid | 委任 | SSO 接続を保存して、ユーザーのログイン モードを示します。 | シングル サインオンを使用してユーザーにサインインする場合。 | affadfb6-f17b-428f-97f9-9aae3b6175bc |
>| Calendars.Read | 委任 | カレンダー イベントの数が少ない場合は、システムに格納されているタスクに変換されます。 | 予定表イベントを読み取り、1:1 ビューに表示できます。 また、新しいアカウントを初期化します。  | d76f016f-52c7-41b5-835b-900361d7040c |
>| Mail.Read | 委任 | システムで作成されたタスクを、元のメッセージへのリンクと一緒に保存します。 | メールをタスクOutlook、共有作業を 1:1 ビューで表示するために、このアドインで使用されます。 | d76f016f-52c7-41b5-835b-900361d7040c |
>| Tasks.Read | 委任 | 一部Outlook/Planner タスクは、新しいユーザーを支援するためにシステムにレプリケートされます。 | 新しいユーザー アカウントは、ユーザーのタスクGraphブートストラップします。 | d76f016f-52c7-41b5-835b-900361d7040c |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。



#### <a name="add-in-data-access"></a>アドイン のデータ アクセス

このアプリが組織のデータにアクセスするために必要なアクセス許可、このアクセス許可の正当性と目的 (アプリは何のためにこの情報を使用するのか)、およびアプリがデータベースにこの情報を格納するかどうかを一覧表示します。

>| **アクセス許可**  | **説明** |
>|:----------------|:----------------|
>| ReadWrite メールボックス | このアドインは、メールボックス内の任意のアイテムの内容を読み取りまたは変更し、新しいアイテムを作成できます。 任意のメッセージまたは予定表アイテムの本文、件名、送信者、受信者、添付ファイルなどの個人情報にアクセスできます。 このデータは、サードパーティ のサービスに送信される場合があります。 |
>| データの送信 | インターネットを使用してデータを送信できます |

#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>はい、ユーザーの電子メールをシステム内の一意の ID として使用し、アプリケーション エラーを追跡し、システム内の主要なイベント (ダウンロード、サインイン、アプリケーション バージョンなど) を追跡して、顧客サービス チームが顧客のクエリに迅速に応答するために使用します。 GDPR コンプライアンスの一環として、削除要求から 2 週間以内にすべての顧客データを削除しますが、実際には、半自動でこれを行う内部スクリプトが用意されているので、同じ日にこれを行います。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>アプリケーション データは、小規模な管理者グループに限定されたアクセス権を持つ暗号化されたデータベースに安全に格納されます。 アクセスをさらにセキュリティで保護するために、2 要素認証を適用し、制御された IP アドレスセットへのアクセスを制限し、開いているインターネットから直接アクセスできない独自のプライベート サブネットでデータベースを見つける。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35667" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について Appfluence Inc によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、
<br />

<br />
- リソース所有者パスワード資格情報 (ROPC) フロー | |アプリは Web API を公開していますか? |はい | |アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? |はい | |アプリでプレビュー API を使用していますか? |いいえ| |アプリで非推奨の API を使用していますか? |いいえ|

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
