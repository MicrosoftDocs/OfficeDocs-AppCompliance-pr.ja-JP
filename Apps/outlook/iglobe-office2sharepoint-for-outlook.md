---
title: iGlobe による Office2SharePoint Outlookアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 11/17/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: office2SharePoint for Outlook、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリのセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f51cdca3731f332707e843076aa18b277b5f5000
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251726"
---
# <a name="office2sharepoint-for-outlook"></a>Office2SharePoint for Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者が最終更新日: 2020 年 11 月 17 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380689" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

iGlobe から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Office2SharePoint for Outlook |
| ID | WA104380689 |
| Office 365サポートされているクライアント | Outlook 2013 以降の Mac Windows、Outlook 2016以降の Mac 上Outlook Web 上 |
| パートナー会社名 | iGlobe |
| パートナー Web サイトの URL | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| プライバシー ポリシーの URL | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| 利用規約の URL | [https://www.iglobecrm.com/content/end-user-license-agreemen...](https://www.iglobecrm.com/content/end-user-license-agreement-office2sharepoint) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する iGlobe によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.AccessAsUser.All | 委任 | アプリケーション データベースにデータは格納されません。 | サインインしているユーザーと同じように、アプリでディレクトリ内の情報にアクセスできるようにします。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.Read.All | 委任 | アプリケーション データベースにデータは格納されません。 | アクセス許可を確認し、サイトとリストを取得します。 フォルダーを作成し、ファイルを取得し、ファイルを保存します。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Directory.ReadWrite.All | 委任 | アプリケーション データベースにデータは格納されません。 | アクセス許可を確認し、サイトとリストを取得します。 フォルダーを作成し、ファイルを取得し、ファイルを保存します。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.Read.All | 委任 | アプリケーション データベースにデータは格納されません。 | ユーザーを取得するには、サイトをグループ化します。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Group.ReadWrite.All | 委任 | アプリケーション データベースにデータは格納されません。 | 選択したメール/s にアクセスし、添付ファイルを取得します。 [メール] または [グループ] サイトSharePointからメールに追加します。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Manage.All | 委任 | アプリケーション データベースにデータは格納されません。 | アプリケーションは、すべてのサイト コレクションにあるドキュメント ライブラリおよびリストを、サインインしたユーザーのために作成または削除することを許可されます。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.Read.All | 委任 | アプリケーション データベースにデータは格納されません。 | ユーザーをサイトにSharePointします。 選択したメールからファイルを取得し、添付ファイルを保存します。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| Sites.ReadWrite.All | 委任 | アプリケーション データベースにデータは格納されません。 | リスト、SharePointファイルを取得します。 ファイルをリストに保存SharePointします。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |
>| User.Read | 委任 | アプリケーション データベースにデータは格納されません。 | ユーザーをサイト、SharePoint、グループ OneDrive取得します。 | 5971c986-9d39-409c-a6f8-1385b1f690ef |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Exchange - EWS。AccessAsUser.All | いいえ |  |  |  |  |
>| Exchange - Mail.ReadWrite | いいえ |  |  |  |  |
>| Exchange - MailboxSettings.ReadWrite | いいえ |  |  |  |  |
>| SharePoint- AllSites.Manage | いいえ |  |  |  |  |
>| SharePoint - AllSites.Write | いいえ |  |  |  |  |
>| SharePoint - MyFiles.Write | いいえ |  |  |  |  |
>| SharePoint - User.Read.All | いいえ |  |  |  |  |

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

>iGlobe は、効果的に運用するためのデータを収集し、製品とサービスで最高のエクスペリエンスを提供します。 ライセンスの場合: 無料アドインの展開、試用版サブスクリプションの作成、サブスクリプションの購入など、組織&#8217;のライセンス アカウントを管理するために収集されたデータ。 以下の情報が収集されます。 財務上の目的: 会社名とアドレス 購読ユーザー: ユーザー名と電子メール


#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>すべてのアプリケーション データは、お客様自身のテナント上に含まれており、テナント管理者が管理するサービスは、その他のすべてのサービスOffice 365。 アプリケーション データはアドインに格納されません。 最新のアドインはサンドボックス ブラウザーで実行され、&#8220;プロセスが&#8221;。 アドインは、ユーザーが作業しているデータにのみアクセスできます。 ユーザー データと対話するには、ユーザー データを使用Microsoft サービス。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35747" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 基準を処理する方法について iGlobe によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | いいえ |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | セキュリティの既定値と、従来の認証をブロックする* [管理者に MFA を要求する] * [Azure 管理に MFA を要求する] * [すべてのユーザーに MFA を要求する] などの一般的なポリシー。 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリは Web API を公開していますか? | いいえ |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
