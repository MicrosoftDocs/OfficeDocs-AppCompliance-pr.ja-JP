---
title: iGlobe による iPlanner Pro Office 365アプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/16/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: iPlanner Pro Office 365、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリのセキュリティ/コンプライアンス情報に関する利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity-certification
ms.openlocfilehash: da9bb9dca4c30efa0def18209b0467d4d6fcd1a8
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413951"
---
# <a name="iplanner-pro-office-365"></a>iPlanner Pro Office 365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者が最終更新日: 2021 年 8 月 16 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/17859280.iplannerpro" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

iGlobe から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | iPlanner Pro Office 365 |
| ID | 17859280.iplannerpro |
| パートナー会社名 | iGlobe |
| パートナー Web サイトの URL | [https://www.iglobecrm.com](https://www.iglobecrm.com) |
| プライバシー ポリシーの URL | [https://www.iglobecrm.com/content/legal-information](https://www.iglobecrm.com/content/legal-information) |
| 利用規約の URL | [https://iglobecrm.com/content/end-user-license-agreement-ig...](https://iglobecrm.com/content/end-user-license-agreement-iglobe-iplanner-add-ins) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する iGlobe によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 委任 | アプリケーション データベースにデータは格納されません。 | プランナー タスクを取得し、新しいタスクを追加するには、特定のユーザーのバケットとスイム ラインを更新します。 | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Contacts.ReadWrite | 委任 | アプリケーション データベースにデータは格納されません。 | タスクの期日にユーザーの予定表に予定を作成するには | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Directory.AccessAsUser.All | 委任 | アプリケーション データベースにデータは格納されません。 | サインインしているユーザーと同じように、アプリでディレクトリ内の情報にアクセスできるようにします。 | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Files.Read | 委任 | アプリケーション データベースにデータは格納されません。 | 添付ファイルとしてファイルにアクセスし、ファイルをタスクにアップロードするには | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Files.ReadWrite.All | 委任 | アプリケーション データベースにデータは格納されません。 | 選択したメールからメールの件名を取得します。 アプリが選択したメールから情報を取得できるようにし、説明フィールドをタスクの説明にコピーし、メールまたはメール自体からタスクに添付ファイルを保存できます。 | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| Group.Read.All | 委任 | アプリケーション データベースにデータは格納されません。 | プランナー タスクを取得し、新しいタスクを追加すると、特定のユーザーのバケットとスイム ラインが更新されます。 | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| User.Read | 委任 | アプリケーション データベースにデータは格納されません。 | プランナー タスクを取得し、新しいタスクを追加するには、特定のユーザーのバケットとスイム ラインを更新します。 | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| User.ReadBasic.All | 委任 | アプリケーション データベースにデータは格納されません。 | アクセス許可を確認し、プランナー タスクを取得し、新しいタスクを追加すると、特定のユーザーのバケットとスイム ラインが更新されます。 | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |
>| profile | 委任 | アプリケーション データベースにデータは格納されません。 | プランナー タスクを取得し、新しいタスクを追加するには、特定のユーザーのバケットとスイム ラインを更新します。 | [a6f5c2f4-0bc2-48bf-8afe-6c93583a152b](https://docs.microsoft.com/microsoft-365-app-certification/azure/a6f5c2f4-0bc2-48bf-8afe-6c93583a152b) |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| Exchange - EWS。AccessAsUser.All | 不要 |  |  |  |  |
>| Exchange - Mail.Read.All | 不要 |  |  |  |  |
>| SharePoint - AllSites.Manage | いいえ |  |  |  |  |
>| SharePoint - AllSites.Read | いいえ |  |  |  |  |
>| SharePoint - AllSites.Write | いいえ |  |  |  |  |
>| SharePoint - MyFiles.Read | 不要 |  |  |  |  |
>| SharePoint - MyFiles.Write | 不要 |  |  |  |  |

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

>いいえ

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
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | いいえ |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | セキュリティの既定値と、従来の認証をブロックする* [管理者に MFA を要求する] * [Azure 管理に MFA を要求する] * [すべてのユーザーに MFA を要求する] などの一般的なポリシー。 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリは Web API を公開していますか? | 不要 |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | 不要 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="certification"

### <a name="certification-information"></a>認定情報

| **Control** | **Microsoft 365認定結果** |
|:------------|:---------------------------------------|
| [**アプリケーション のセキュリティ**](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification-submission-guide#application-security) | **該当なし** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;侵入テスト | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;脆弱性評価レビュー (DAST/SAST/侵入テスト) | 該当なし |
| [**運用上のセキュリティ**](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification-submission-guide#operational-security) | **該当なし** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;マルウェア保護 - ウイルス対策 | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;マルウェア保護 - アプリケーション制御 | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;パッチ管理 - リスクランキング | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;パッチ管理 - パッチ適用 | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;脆弱性スキャン | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ファイアウォール - ファイアウォール (または同等のテクノロジ) | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ファイアウォール - Web アプリケーション ファイアウォール (WAF) (オプション) | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;変更コントロール | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Secure Software Development/Deployment | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;アカウント管理 | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;侵入の検出と防止 (オプション) | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;セキュリティ イベント ログ | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;レビュー (ログ データ) | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;セキュリティ イベントの警告 | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;情報セキュリティリスク管理 | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;インシデント対応 | 該当なし |
| [**データ処理の &amp; セキュリティプライバシー**](https://docs.microsoft.com/en-us/microsoft-365-app-certification/docs/certification-submission-guide#data-handling-security-and-privacy) | **該当なし** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;転送中のデータ | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;保存中のデータ | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;データの保持と廃棄 | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;データ アクセスの管理 | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;GDPR | N/A |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
