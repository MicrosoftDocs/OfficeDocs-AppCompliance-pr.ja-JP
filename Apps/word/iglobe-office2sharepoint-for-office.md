---
title: iGlobe によるOffice用 Office2SharePoint のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Office2SharePoint で利用可能なすべてのセキュリティおよびコンプライアンス情報Office、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 1d1fccbab2aab91eacbc5a43ef79462dd536ff6e
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552648"
---
# <a name="office2sharepoint-for-office"></a>Office用の Office2Share ポイント

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者による最終更新日: 2020年11月17日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381787" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

iGlobe がマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Office用の Office2Share ポイント |
| ID | WA104381787 |
| サポートされるクライアントOffice 365 | Excel 2016以降のMacで、Windows、Excel on the web、Word 2016以降のWindows、Excel on the web、Word 2016、Word on the web、Word 2016以降、PowerPoint 2016 Mac、PowerPoint on the web、PowerPoint 2016、以降のWindowsでExcel 2016 Windows |
| パートナー会社名 | iGlobe |
| パートナーウェブサイトのURL | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| プライバシーポリシーの URL | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| 利用規約の URL | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法、およびアプリが収集するデータに対する組織のコントロールに関する情報を iGlobe によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.AccessAsUser.All | 委任 | アプリケーション データベースにはデータは格納されません。 | サインインしているユーザーと同じように、アプリでディレクトリ内の情報にアクセスできるようにします。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.Read.All | 委任 | アプリケーション データベースにはデータは格納されません。 | アクセス許可を確認し、サイトとリストを取得します。 フォルダを作成し、ファイルを取得し、ファイルを保存します。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.ReadWrite.All | 委任 | アプリケーション データベースにはデータは格納されません。 | アクセス許可を確認し、サイトとリストを取得します。 フォルダを作成し、ファイルを取得し、ファイルを保存します。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.Read.All | 委任 | アプリケーション データベースにはデータは格納されません。 | ユーザーを取得するには、サイトをグループ化します。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.ReadWrite.All | 委任 | アプリケーション データベースにはデータは格納されません。 | 選択したメールにアクセスして添付ファイルを取得します。 SharePointまたはグループ サイトからメールに追加します。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Mail.ReadWrite | 委任 | アプリケーション データベースにはデータは格納されません。 | 選択したメールにアクセスして添付ファイルを取得します。 SharePointまたはグループ サイトからメールに追加します。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Manage.All | 委任 | アプリケーション データベースにはデータは格納されません。 | アプリケーションは、すべてのサイト コレクションにあるドキュメント ライブラリおよびリストを、サインインしたユーザーのために作成または削除することを許可されます。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Read.All | 委任 | アプリケーション データベースにはデータは格納されません。 | ユーザーをサイトSharePoint取得します。 選択したメールからファイルを取得し、添付ファイルを保存します。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.ReadWrite.All | 委任 | アプリケーション データベースにはデータは格納されません。 | リスト、ライブラリ、ファイルSharePoint取得します。 ファイルをSharePointリストに保存します。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| User.Read | 委任 | アプリケーション データベースにはデータは格納されません。 | サイト、OneDrive、およびグループ サイトSharePointユーザーを取得します。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |

#### <a name="data-access-using-other-microsoft-apis"></a>他のマイクロソフト API を使用したデータ アクセス

Microsoft 365上に構築されたアプリやアドインでは、Microsoft Graph 以外の Microsoft API を使用して、組織を識別できる情報 (OII) を収集または処理できます。 このアプリが使用するマイクロソフトGraph以外のマイクロソフト API を一覧表示します。

>| **API** |  **OIIは収集されますか?** |  **OIIは何を収集されますか?** | **OIIを収集するための正当性?** | **OII は保存されていますか?** | **OIIを格納するための正当性?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS。アクセスアスユーザー.All | いいえ |  |  |  |  |
>| Exchange - メール.読み取り書き込み | いいえ |  |  |  |  |
>| Exchange - メールボックス設定.読み取り書き込み | いいえ |  |  |  |  |
>| SharePoint - すべてのサイト.管理 | いいえ |  |  |  |  |
>| SharePoint - すべてのサイト.書き込み | いいえ |  |  |  |  |
>| SharePoint - マイファイル.書き込み | いいえ |  |  |  |  |
>| SharePoint - ユーザー.読み取り.すべて | いいえ |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>iGlobeは、効果的に動作し、あなたに当社の製品やサービスで最高の体験を提供するためにデータを収集します。 ライセンスの場合: 無料のアドインを展開する場合、試用版サブスクリプションを作成したりサブスクリプションを購入したりする場合など、組織&#8217;のライセンス アカウントを管理するために収集されたデータ。 以下の情報が収集されます。 財務上の目的: 会社名と住所 購読ユーザー: ユーザー名と電子メール


#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>すべてのアプリケーション データは、顧客自身のテナント上にあり、Office 365の他のすべてのサービスとしてテナント管理者によって制御されます。 アプリケーション データはアドインに格納されません。 最新のアドインは、プロセス&#8221;から&#8220;、サンドボックス 化されたブラウザーで実行されます。 アドインは、ユーザーが作業しているデータにのみアクセスできます。 Microsoft サービスを使用してユーザーデータと対話します。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、およびその他の ID 条件を処理する方法について iGlobe によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| マイクロソフト識別プラットフォーム (Azure AD) と統合しますか。  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか。  | はい |
| アプリは認証に MSAL (マイクロソフト認証ライブラリ) を使用していますか? | いいえ |
| アプリで条件付きアクセス ポリシーがサポートされていますか。 | はい |
| サポートされているポリシーの種類を一覧表示する | セキュリティの既定値と[従来の認証をブロックする] * 管理者に MFA を要求する* Azure 管理に MFA を要求する* すべてのユーザーに MFA を必要とする* |
| アプリがシナリオに対して最低限の権限を要求しているか。 | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的に、または増分的に要求するアクセス許可を正確に反映していますか。 | はい |
| アプリでマルチテナント機能がサポートされていますか。 | はい |
| アプリに機密クライアントが存在しますか? | はい |
| アプリに登録されているすべてのリダイレクト統一リソース識別子 (URI) を所有していますか。 | はい |
| アプリは Web API を公開していますか。 | いいえ |
| アプリでプレビュー API を使用していますか。 | いいえ |
| アプリで非推奨の API が使用されていますか。 | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
