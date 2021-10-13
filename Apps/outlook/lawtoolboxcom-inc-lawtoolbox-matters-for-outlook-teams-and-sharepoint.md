---
title: LawToolBox のアプリケーション情報 Outlook、Teams SharePoint LawToolBox.com。 &amp;
ms.author: elmalova
author: elenamalova
ms.date: 06/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Outlook、Teams SharePoint、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報に関する LawToolBox Matters で利用可能なすべてのセキュリティおよびコンプライアンス情報 &amp; 。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 039b83277d1e3a6823b16079ec6a0fa8fbec68d2
ms.sourcegitcommit: 1d47df35430334cfc0c60f7ea0b62392b99b7cbf
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/13/2021
ms.locfileid: "60286014"
---
# <a name="lawtoolbox-matters-for-outlook-teams-amp-sharepoint"></a>LawToolBox Outlook、Teams SharePoint &amp;

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 6 月 24 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003103" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

LawToolBox.com Inc. から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | LawToolBox Outlook、Teams SharePoint &amp; |
| ID | WA200003103 |
| Office 365サポートされているクライアント | Outlook 2013 以降の Mac Windows、Outlook 2016以降の場合は、Outlook on the web |
| パートナー会社名 | LawToolBox.com Inc. |
| パートナー Web サイトの URL | [https://www.lawtoolbox.com](https://www.lawtoolbox.com) |
| プライバシー ポリシーの URL | [https://www.lawtoolbox.com/privacy-policy/](https://www.lawtoolbox.com/privacy-policy/) |
| 利用規約の URL | [https://www.lawtoolbox.com/customersupport/2019/LawToolBox_...](https://www.lawtoolbox.com/customersupport/2019/LawToolBox_End_User_License_Agreement_and_SLA_LAWTOOLBOX_2019_APR.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、LawToolBox.com Inc. から、このアプリが組織データを収集および保存する方法、およびアプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | 委任 | このアクセス許可は、ユーザーが自分の予定表情報&#8217;取得するために使用する &#8211; に既にアクセスしているユーザーの連絡先へのアクセスを制限されます。 | [省略可能]ユーザーの予定表を読み取ります。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite | 委任 | このアクセス許可は、ユーザーが既に &#8211; にアクセスできるユーザー&#8217;の連絡先へのアクセスを制限され、ユーザーが自分の予定表情報を取得して予定表に書き込むのを許可するために使用します。 | ユーザーの予定表への予定表の招待を作成するには。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Calendars.ReadWrite.Shared | 委任 | このアクセス許可は、ユーザーが自分の予定表情報&#8217;取得するために使用する &#8211; に既にアクセスしているユーザーの連絡先へのアクセスを制限されます。 | 共有予定表への予定表の招待を作成するには。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite | 委任 | このアクセス許可は、ユーザーが既にアクセス&#8217;連絡先へのアクセスを制限されます。  このアクセス許可を使用して、ユーザーが自分の O365 連絡先を検索し、LawToolBox &#8211; に追加できます(この機能を手動で追加したくない場合は、これは取り消される可能性があります) | [省略可能] - ユーザーの連絡先を読み取り、連絡先リストからグループにユーザーを接続します。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Contacts.ReadWrite.Shared | 委任 | このアクセス許可を使用して、ユーザーが共有 O365 連絡先を検索し、LawToolBox に追加&#8211;連絡先を自動的に追加しない場合 | [省略可能] - ユーザーの共有連絡先を読み取り、ケースに関連する連絡先の一覧を提供します。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.AccessAsUser.All | 委任 | 管理者ポータルで使用して、アカウントに追加する O365 テナントからユーザーの一覧を取得する | [省略可能]グループとユーザーの情報をユーザーとして読み取る。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Directory.ReadWrite.All | 委任 | 管理者ポータルで使用して、アカウントに追加する O365 テナントからユーザーの一覧を取得する | [省略可能]グループとユーザーの情報をユーザーとして読み取る。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read | 委任 | これにより、アドインは、ユーザーが既にアクセスできるユーザー ファイルを読み取り、一覧表示できます。 | [省略可能]ユーザーのページを読OneDrive。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.Read.All | 委任 | このアクセス許可を使用して、ユーザーが既にアクセスできるユーザー ファイルを読み取り、一覧表示します。 | [Optional]-Read ユーザーのOneDrive。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite | 委任 | 会議用に Teams、グループ、OneDriveからファイルを読み取る (取り消すと、アドインがアプリ内の重要なファイルを一覧に表示できません) | [Optional]-ユーザーのファイルを読み取り、変更OneDrive。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Files.ReadWrite.All | 委任 | 会議用に Teams、グループ、OneDriveファイルを読み取ります (無効にした場合、LTB はアプリ内の重要なファイルを一覧に表示できません)。  ユーザーは addin のみを使用して、ユーザーが既にアクセスできるユーザー ファイルを読み取り、一覧表示できます。 | [省略可能]Matter に関連付けられたユーザーのOneDriveファイルを読み取り/書き込み。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Group.ReadWrite.All | 委任 | GroupID、GroupName、GroupEmail | システムで作成された各問題に対してグループを作成します。 これにより、ユーザーは重要な情報をグループに保存し、データを自分のテナントに保存します。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Read | 委任 | このアクセス許可を使用して、Outlook アドインで PACER メールを読み取り、その問題を自動的に開き、連絡先システムに追加するためにメールから連絡先を読み取る  | [省略可能][InProgress]重要事項に関するユーザーのメールを読む。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite | 委任 | このアクセス許可を使用して、Outlook アドインで PACER メールを読み取り、その問題を自動的に開き、連絡先システムに追加するためにメールから連絡先を読み取る  | [省略可能][InProgress]ユーザーの電子メールの読み取り/書き込み。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.ReadWrite.Shared | 委任 | このアクセス許可を使用して、Outlook アドインで PACER メールを読み取り、その問題を自動的に開き、連絡先システムに追加するためにメールから連絡先を読み取る  | [省略可能][InProgress]ユーザーの電子メールの読み取り/書き込み。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Mail.Send | 委任 | この送信メールをユーザーとして使用して、ユーザーが自分のシステムに既にアクセスできるデータのレポートのみを送信できます。 | [省略可能][InProgress]メールの期限をユーザーとして送信します。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| Tasks.ReadWrite.Shared | 委任 | このアクセス許可は、ユーザーが既に &#8211; タスクにアクセスできる&#8217;タスクへのアクセスを制限され、ユーザーが自分の TASK 情報を取得および更新できます。  | [省略可能]-[InProgress] ユーザーのタスクとして書き込み期限を読み取る。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.Read | 委任 | 会議や連絡先に追加する最近の連絡先を提案するために使用される | ユーザーの情報を読み取る。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite | 委任 | 会議や連絡先に追加する最近の連絡先を提案するために使用される | ユーザーの情報の読み取り/書き込み。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| User.ReadWrite.All | 委任 | これは、API の読み取り、Teams作成、予定表Teams作成、チャネルの作成、ファイル共有機能Teams必要です。 | ユーザーの情報の読み取り/書き込み。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| メール | 委任 | メール、Office365 UserID、ObjectID、TenantID。 | ユーザーのメール アドレスを読み取る。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |
>| profile | 委任 | これは SSO 認証に必要です- M365 テナントに保存されたイメージと名前を取得して、ユーザーが正しいツールボックスに保存されていることをユーザーが知っているように表示することもできます。 | ユーザー プロファイル情報の読み取り。 | [3ee373aa-62fa-4fc6-b11f-9627d5b4a73d](https://docs.microsoft.com/microsoft-365-app-certification/azure/3ee373aa-62fa-4fc6-b11f-9627d5b4a73d) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>ユーザーメール、UserID、AccessToken、デバッグ ログのグループ情報

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>データの削除要求を受信しない限り、ケース レコードは保持されます。

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

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Id 条件を処理する方法について、LawToolBox.com Inc. から提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | 管理者がアプリのアクセス許可を実装できる制御を向上するには |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | いいえ |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | ,<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/> |
| アプリは Web API を公開していますか? | いいえ |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
