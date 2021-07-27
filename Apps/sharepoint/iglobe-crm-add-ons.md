---
title: iGlobe による iGlobe CRM アドオンのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: iGlobe CRM アドオンに使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 67cfb36f4720e72e6cbd284aa86d5d7da4c785cb
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/22/2021
ms.locfileid: "53522200"
---
# <a name="iglobe-crm-add-ons"></a>iGlobe CRM アドオン

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者が最終更新日: 2020 年 11 月 17 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200002010" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

iGlobe から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | iGlobe CRM アドオン |
| ID | WA200002010 |
| Office 365サポートされているクライアント | SharePoint 2016 以降 |
| パートナー会社名 | iGlobe |
| パートナー Web サイトの URL | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| プライバシー ポリシーの URL | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| 利用規約の URL | [https://iglobecrm.com/content/iglobe-crm-office-365-end-use...](https://iglobecrm.com/content/iglobe-crm-office-365-end-user-license-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する iGlobe によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 委任 | アプリケーション データベースにデータは格納されません。 | canlendar から iGlobe に会議レポートを読み込むときに、ユーザーの予定表にアクセスする | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Contacts.ReadWrite | 委任 |  Directory.AccessAsUser.All | サインインしているユーザーと同じように、アプリでディレクトリ内の情報にアクセスできるようにします。 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Directory.Read.All | 委任 | アプリケーション データベースにデータは格納されません。 | アクセス許可を確認し、サイトとリストを取得します。 フォルダーを作成し、ファイルを取得し、ファイルを保存します。 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Directory.ReadWrite.All | 委任 | アプリケーション データベースにデータは格納されません。 | サインインしているユーザーと同じように、アプリでディレクトリ内の情報にアクセスできるようにします。 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Files.ReadWrite.All | 委任 | アプリケーション データベースにデータは格納されません。 | 読み取り、更新、パンナー タスクの作成、ユーザーの最近のファイルと共有ファイルの読み取り、リスト、ライブラリ、ファイルSharePoint取得します。 ファイルとデータをリストに保存SharePointします。 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Group.Read.All | 委任 | アプリケーション データベースにデータは格納されません。 | 読み取り、更新、パンナー タスクの作成、ユーザーの最近のファイルと共有ファイルの読み取り、リスト、ライブラリ、ファイルSharePoint取得します。 ファイルをリストに保存SharePointします。 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Group.ReadWrite.All | 委任 | アプリケーション データベースにデータは格納されません。 | 読み取り、更新、パンナー タスクの作成、ユーザーの最近のファイルと共有ファイルの読み取り、リスト、ライブラリ、ファイルSharePoint取得します。 ファイルをリストに保存SharePointします。 iGlobe CRM Office 365 | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Mail.ReadWrite | 委任 | アプリケーション データベースにデータは格納されません。 | eamil を iGlobe CRM に Svae し、iGlobe から新しい e-amil に informatiopn を取得する | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Sites.Manage.All | 委任 | アプリケーション データベースにデータは格納されません。 | iGlobe CRM でアイテムとリストを作成、編集、および削除する | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Sites.Read.All | 委任 | アプリケーション データベースにデータは格納されません。 | iGlobe CRM のアイテムの読み取り | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Sites.ReadWrite.All | 委任 | アプリケーション データベースにデータは格納されません。 |  iGlobe CRM のアイテムとリストを編集、削除する | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| Tasks.ReadWrite | 委任 | アプリケーション データベースにデータは格納されません。 | iGlobe CRM からプランナー タスクを作成する | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |
>| User.Read | 委任 | アプリケーション データベースにデータは格納されません。 | speficic ユーザーの iGlobe CRM の情報を取得するには | [0bb1641a-3b3b-47f7-a11e-01279d92abfb](https://docs.microsoft.com/microsoft-365-app-certification/azure/0bb1641a-3b3b-47f7-a11e-01279d92abfb) |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange - Calendars.ReadWrite.All | なし |  |  |  |  |
>| Exchange - Mail.Read.All | なし |  |  |  |  |
>| Exchange - Contacts.Read | なし |  |  |  |  |
>| Exchange - EWS。AccessAsUser.All | なし |  |  |  |  |
>| Exchange - Tasks.ReadWrite | なし |  |  |  |  |
>| SharePoint - AllSites.Manage | なし |  |  |  |  |
>| SharePoint - AllSites.Read | なし |  |  |  |  |
>|  SharePoint -AllSites.Write | なし |  |  |  |  |
>| SharePoint - MyFiles.Write | なし |  |  |  |  |
>| SharePoint - Sites.Manage.All | なし |  |  |  |  |
>| SharePoint - Sites.Read.All | なし |  |  |  |  |
>| SharePoint - Sites.ReadWrite.All | なし |  |  |  |  |
>| SharePoint - Sites.Search.All | なし |  |  |  |  |
>|  SharePoint - TermStore.Read.All | なし |  |  |  |  |
>| SharePoint - TermStore.ReadWrite.All | なし |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>iGlobe は、効果的に運用するためのデータを収集し、製品とサービスで最高のエクスペリエンスを提供します。 ライセンスの場合: 無料アドインの展開、試用版サブスクリプションの作成、サブスクリプションの購入など、組織&#8217;のライセンス アカウントを管理するために収集されたデータ。 以下の情報が収集されます。 
- 財務目的: 会社名と住所
- サブスクライブしたユーザー: ユーザー名とメール

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>すべてのデータは、お客様自身のテナント上に含まれており、 アプリケーション データは保存されません。 最新のアドインはサンドボックス ブラウザーで実行され、&#8220;プロセスが&#8221;。 ユーザー データと対話するには、ユーザー データを使用Microsoft サービス。 アドインは、ユーザーが作業しているデータにのみアクセスできます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>なし

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36163" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 基準を処理する方法について iGlobe によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | なし |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | セキュリティの既定値と、従来の認証をブロックする* [管理者に MFA を要求する] * [Azure 管理に MFA を要求する] * [すべてのユーザーに MFA を要求する] などの一般的なポリシー。 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリは Web API を公開していますか? | なし |
| アプリでプレビュー API を使用していますか? | なし |
| アプリで非推奨の API を使用していますか? | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
