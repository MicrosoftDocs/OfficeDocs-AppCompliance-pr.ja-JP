---
title: 意思決定による意思決定に関するアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 06/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 意思決定、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリのセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 19a710fc8edbcb5243b81755ce3d61e8bcaa5b25
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287004"
---
# <a name="decisions"></a>決定事項

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 6 月 2 日</p>

* <a href="https://teams.microsoft.com/l/app/d3d1be68-066c-4967-a74b-9edcf902dcfb" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381880" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Microsoft に対して Decisions によって提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | 決定事項 |
| ID | WA104381880 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | 決定事項 |
| パートナー Web サイトの URL | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| [アプリケーション情報Teamsページの URL | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| プライバシー ポリシーの URL | [https://www.meetingdecisions.com/privacy](https://www.meetingdecisions.com/privacy) |
| 利用規約の URL | [https://www.meetingdecisions.com/terms-of-service](https://www.meetingdecisions.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する決定によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 委任 | 会議の一覧や検索&#8217;機能を有効にするには、ユーザーの予定表から情報を読み取る場合に使用します。 また、アイテムが Decisions から削除された場合に、予定表から特定の会議を削除するオプションもユーザーに与えます。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Chat.ReadWrite | 委任 | 投票の決定を送信し、個々の議題アイテムのスピーカー リストを会議チャットに直接送信Microsoft Teams使用します。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Directory.Read.All | 委任 | テナント名や検証済みドメインなど、Office 365に関する基本情報を収集するために使用します。 また、グループ メンバーシップの確認にも必要です。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.Read.All | 委任 | ユーザーと共有されているファイルを読み取り、それらのファイルを PDF 会議帳に結合するために使用します。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Files.ReadWrite.All | 委任 | 個人用ファイル注釈のサポートをユーザーに提供するために使用します。 注釈付きファイルは、ユーザーファイルに&#8217;保存OneDrive for Business。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Group.ReadWrite.All | 委任 | 会議の議題、関連ファイル、およびグループOffice 365の&#8217;グループ SharePointサイトにフォルダー構造を作成するために使用します。   注: 意思決定のユーザーは、組織のテナント内のリソース (グループなど) へのアクセス権を持Office 365できません。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Mail.Send | 委任 | 意思決定のユーザーが会議参加者の通知 (議題の更新や共同執筆者向け会議へのリンクなど) を送信するために使用します。 メールは、会議の参加者または会議の所有者が選択した配布リストに移動します。 送信された通知と電子メールはすべて、Decisions ユーザーによってアクティブに行われます。  注: これにより、ユーザーは Decisions を介して受信トレイにアクセスできます。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| MailboxSettings.Read | 委任 | ユーザーの言語設定&#8217;識別するために使用されます。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Notes.ReadWrite | 委任 | 会議用のプライベート ノートブックをセットアップしてメモを取り、備考や質問を準備するために使用します。 また、グループが会議の使用を選択した場合に、グループ会議の議OneNote共有ノートブック内に保存OneNote。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Sites.ReadWrite.All | 委任 | 会議情報のプライベート チャネルにフォルダー構造を作成するために使用します。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| Tasks.ReadWrite | 委任 | タスクと決定を Microsoft Planner に同期するために使用します。 また、ユーザーはタスクや意思決定をエクスポートして、タスクをExcel。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser | 委任 | チャットに Decisions App をプログラムでインストールするために必要です。 これは、会議のエクスペリエンスに [決定] タブを追加する前に必要です。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsAppInstallation.ReadWriteForUser.All | 委任 | チャットに Decisions App をプログラムでインストールするために必要です。 これは、会議のエクスペリエンスに [決定] タブを追加する前に必要です。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Create | 委任 | [会議内/チャネル] タブを [会議内] タブに追加するTeams。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| TeamsTab.Read.All | 委任 | タブがインストールされていないか確認するために必要です。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| User.ReadBasic.All | 委任 | グループ メンバーと外部参加者の名前、写真、電子メール アドレスを表示するために使用します。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |
>| profile | 委任 | サインインに使用します。 | 顧客データは、テナント&#8217;にOffice 365、すべての顧客データが顧客デバイスでのみ処理されます。 Decisions データベースは、実際のデータではなく、テナント内Office 365オブジェクトへの参照のみを保持します。 詳細については https://www.meetingdecisions.com/security-and-privacy 、「」を参照してください。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](https://docs.microsoft.com/microsoft-365-app-certification/azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>お客様がソフトウェアを使用している間に提供されるデータは、お客様だけが利用できます。  サービスは、クラウド サービスとMicrosoft Office 365で配信Microsoft Azure。 すべての顧客データは、テナントの顧客Microsoft Office 365されます。 サービスに保存または処理されたデータはすべて匿名であり、個人に対して追跡できません。 そのため、意思決定は、お客様に代わって個人データを保存、収集、または処理することはできません。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 基準を処理する方法に関する決定によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | すべて |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
